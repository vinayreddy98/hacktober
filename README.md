# Hello World, This is my First PR.
## getting started with react native in expo
If you are new to mobile development, the easiest way to get started is with Expo CLI. Expo is a set of tools built around React Native and, while it has many features, the most relevant feature for us right now is that it can get you writing a React Native app within minutes. You will only need a recent version of Node.js and a phone or emulator. If you'd like to try out React Native directly in your web browser before installing any tools, you can try out Snack.


 If you are already familiar with mobile development, you may want to use React Native CLI. It requires Xcode or Android Studio to get started. If you already have one of these tools installed, you should be able to get up and running within a few minutes. If they are not installed, you should expect to spend about an hour installing and configuring them.

Expo CLI Quickstart React Native CLI Quickstart
Assuming that you have Node 10 LTS or greater installed, you can use npm to install the Expo CLI command line utility:

npm install -g expo-cli


Then run the following commands to create a new React Native project called "AwesomeProject":

expo init AwesomeProject

cd AwesomeProject
npm start # you can also use: expo start
This will start a development server for you.

Running your React Native application
Install the Expo client app on your iOS or Android phone and connect to the same wireless network as your computer. On Android, use the Expo app to scan the QR code from your terminal to open your project. On iOS, follow on-screen instructions to get a link.

Modifying your app
Now that you have successfully run the app, let's modify it. Open App.js in your text editor of choice and edit some lines. The application should reload automatically once you save your changes.

That's it!
Congratulations! You've successfully run and modified your first React Native app.


Now what?
Expo also has docs you can reference if you have questions specific to the tool. You can also ask for help at Expo forums.

These tools help you get started quickly, but before committing to building your app with Expo CLI, read about the limitations.

If you have a problem with Expo, before creating a new issue, please see if there's an existing issue about it:

in the Expo CLI issues (for issues related to Expo CLI), or
in the Expo issues (for issues about the Expo client or SDK).
If you're curious to learn more about React Native, continue on to the Tutorial.

Running your app on a simulator or virtual device
Expo CLI makes it really easy to run your React Native app on a physical device without setting up a development environment. If you want to run your app on the iOS Simulator or an Android Virtual Device, please refer to the instructions for "React Native CLI Quickstart" to learn how to install Xcode or set up your Android development environment.

Once you've set these up, you can launch your app on an Android Virtual Device by running npm run android, or on the iOS Simulator by running npm run ios (macOS only).

Caveats
Because you don't build any native code when using Expo to create a project, it's not possible to include custom native modules beyond the React Native APIs and components that are available in the Expo client app.

If you know that you'll eventually need to include your own native code, Expo is still a good way to get started. In that case you'll just need to "eject" eventually to create your own native builds. If you do eject, the "React Native CLI Quickstart" instructions will be required to continue working on your project.

Expo CLI configures your project to use the most recent React Native version that is supported by the Expo client app. The Expo client app usually gains support for a given React Native version about a week after the React Native version is released as stable. You can check this document to find out what versions are supported.

If you're integrating React Native into an existing project, you'll want to skip Expo CLI and go directly to setting up the native build environment. Select "React Native CLI Quickstart" above for instructions on configuring a native build environment for React Native.
