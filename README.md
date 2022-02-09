# testbed_native_ios

This app illustrates how to integrate the Branch React Native SDK into a React Native component within an existing native iOS app.

The app was produced following the methodology outlined in these tutorials:

- https://facebook.github.io/react-native/docs/integration-with-existing-apps.html
- https://www.raywenderlich.com/136047/react-native-existing-app

In particular, it uses the `React`, `react-native-branch` and `Branch-SDK` pods from node_modules.

## Building

To build and run:

```bash
yarn install
```

or

```bash
npm install
```

then

```bash
cd ios
bundle pod install
```

then update `branch_key`, `URL types` in `info.plist` and Bundle Identifier under General Target. 
