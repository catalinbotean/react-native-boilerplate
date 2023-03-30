## React Native Boilerplate

### Requirements

Node 18 or greater is required. Development for iOS requires a Mac and Xcode 14 or up.
You also need to install the dependencies required by React Native.
Go to the [React Native environment setup](https://reactnative.dev/docs/environment-setup), then select React Native CLI Quickstart tab.
Follow instructions for your given `development OS` and `target OS`.

### Installation

Install the dependencies and start the server.

```sh
cd react-native-boilerplate
yarn install
yarn start
```

### Run on Android

You need to have an Android emulator running or a device connected.

```sh
yarn android
```

### Run on iOS

##

```sh
cd ios
pod install
yarn ios
```

You can also open ./ios/BoilerplateApp.xcworkspace in Xcode and press on the Build button.

### Run the tests

##

```sh
yarn test
```
