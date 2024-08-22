# Android WebApp Example

## Introduction

The Android WebApp Example is a ready-to-use Android Studio project designed to create a simple web app. This app includes built-in controls at the bottom, such as forward, back, and home buttons. You can customize this web app by modifying the `MainActivity.java` file to specify your desired URL, and then compile it to generate a finished `.apk` file. This project simplifies the process of creating web apps related to your website. All you need is Android Studio installed on your system, and you can quickly make the necessary changes.

## Requirements

- **Android Studio**: This software is developed using Android Studio. We recommend using this development environment to modify the source code and compile the project. You can import the source folder into Android Studio to get started.

## Modifications

   - Open the `MainActivity.java` file located at `source/app/src/main/java/com/bugfish/webapp/`.
   - Modify the `theURL` variable to your desired website URL.

   - Replace the default app image by updating the image files located in `source/app/src/main/res/`.

   - If you plan to create multiple web apps, remember to update the Gradle App-ID in the Gradle files. Using the same App-ID for multiple web apps may result in conflicts when installing them on devices simultaneously.

## Usage

   - Open Android Studio and import the source folder.

   - Make the necessary changes as described in the Modifications section.

   - Compile the project in Android Studio to generate the `.apk` file.

   - Deploy the `.apk` file to your Android device for testing and use.

Feel free to customize the app further according to your needs and preferences.