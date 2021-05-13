# rnRedux

This is an example of how to manage state using Redux inside a React Native app.

## Setup

This project was started by following the steps provided by the DEV Community tutorial: ["Comprehensive guide to using Redux in React Native"](https://blog.logrocket.com/comprehensive-guide-to-using-redux-in-react-native/).

## Available Scripts

If Yarn was installed when the project was initialized, then dependencies will have been installed via Yarn, and you should probably use it to run these commands as well. Unlike dependency installation, command running syntax is identical for Yarn and NPM at the time of this writing.

### npm install

It is important to install the project dependencies through the command:

<pre>
npm install

or

yarn install
</pre>

### npx react-native start

Runs your app in development mode.

Open it in the Expo app on your phone to view it. It will reload if you save edits to your files, and you will see build errors and logs in the terminal.

Sometimes you may need to reset or clear the React Native packager's cache. To do so, you can pass the --reset-cache flag to the start script:

<pre>
npx react-native start --reset-cache

or

yarn start -- --reset-cache
</pre>

### npx react-native test

Runs the jest test runner on your tests.

### npx react-native run-ios

Like `npx react-native start`, but also attempts to open your app in the iOS Simulator if you're on a Mac and have it installed.

### npx react-native run-android

Like `npx react-native start`, but also attempts to open your app on a connected Android device or emulator. Requires an installation of Android build tools (see [React Native docs](https://reactnative.dev/docs/getting-started) for detailed setup). We also recommend installing Genymotion as your Android emulator. Once you've finished setting up the native build environment, there are two options for making the right copy of adb available to Create React Native App.

### Example
