# Notes App

## Overview
This is a Flutter-based personal note-taking app that allows users to securely create, edit, and manage their notes. The app uses Firebase for user authentication and cloud storage, ensuring that notes are synced in real-time across devices.

## Main Purpose
The main purpose of this app is to provide users with a simple and efficient way to keep track of their notes, accessible anytime and anywhere with cloud synchronization.

## Key Features
- **User Authentication:** Users can sign up and log in using their email and password.
- **Create, Edit, and Delete Notes:** Users can add new notes, update existing ones, and delete notes they no longer need.
- **Real-time Sync:** Notes are stored in Firebase Firestore and synced in real-time across devices.
- **Secure Access:** Only authenticated users can access their personal notes.
- **Logout:** Users can securely log out of the app.

## Target Audience
This app is designed for individuals who want a straightforward and secure note-taking solution with cloud synchronization. It is ideal for users who prefer to access their notes on multiple devices without worrying about data loss.

## How It Works
- Upon launching the app, users are prompted to log in or sign up using their email and password.
- Once authenticated, users are taken to the notes page where they can view their existing notes.
- Users can add a new note by tapping the "+" button, edit notes by tapping the edit icon, or delete notes by tapping the delete icon.
- All changes are synced in real-time with Firebase Firestore.
- Users can log out anytime using the logout button in the app bar.

## Technologies Used
- Flutter
- Firebase Authentication
- Firebase Firestore
- BLoC for state management

## Getting Started
To run the app locally:
1. Ensure you have Flutter installed and set up.
2. Configure Firebase for your project and update `firebase_options.dart`.
3. Run `flutter pub get` to install dependencies.
4. Use `flutter run` to launch the app on your device or emulator.

