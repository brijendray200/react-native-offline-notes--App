# Offline Notes App - Project Documentation

## Project Overview

Offline Notes is a React Native Expo mobile app that allows users to create, edit, delete, and save notes locally on their device. The app works offline because notes are stored using AsyncStorage.

## GitHub Repository

https://github.com/brijendray200/react-native-offline-notes--App

## APK Download Link

https://drive.google.com/file/d/1c3XDgHvKERdsPG1P9N2tsb-wbDg6JqjH/view?usp=drive_link

## Technologies Used

- React Native
- Expo SDK 56
- TypeScript
- AsyncStorage
- JavaScript/JSX
- Android Gradle build

## Features

- Create new notes
- Edit existing notes
- Delete notes
- Save notes locally on the device
- Works without internet after installation
- Responsive UI for mobile and web preview
- APK generated for Android installation

## App Flow

1. User opens the app.
2. Existing saved notes are loaded from local storage.
3. User can create a new note by entering a title and body.
4. User can save the note.
5. Saved notes appear in the notes list.
6. User can select any note to edit it.
7. User can delete notes when no longer needed.

## Local Storage

The app uses AsyncStorage to store notes on the user's device. This means the notes remain saved even after closing and reopening the app.

## APK Build

The Android APK was generated using Expo prebuild and Gradle release build.

APK output path:

```text
C:\Users\brije\OneDrive\Documents\task 1\android\app\build\outputs\apk\release\app-release.apk
```

## Screenshot

The project README includes an app screenshot:

```text
assets/screenshots/offline-notes-home.png
```

## Conclusion

This project demonstrates a complete offline notes application built with React Native and Expo. It includes local data persistence, a clean user interface, Android APK generation, GitHub repository setup, and APK sharing through Google Drive.
