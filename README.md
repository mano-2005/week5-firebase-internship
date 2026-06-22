# Flutter Firebase Authentication & Cloud Firestore Integration

A clean and functional Flutter mobile application demonstrating Firebase setup, Email/Password user authentication workflows, and real-time user profile data management using Cloud Firestore.

## 🚀 Features
- **Firebase Core Configuration:** Seamless connection initialization to backend cloud services.
- **Secure Authentication:** Validated Form constraints for both user Registration (Sign-Up) and Login screens.
- **Cloud Firestore Storage:** Automated user metadata generation (UID, Name, Email) mapping inside document collections upon sign-up.
- **Reactive Stream Architecture:** Automatic view rendering via `authStateChanges()` streams and real-time document listeners via database `snapshots()`.

## 🛠️ Setup Instructions

### 1. Prerequisites
- Flutter SDK configured locally.
- Firebase CLI tools activated (`dart pub global activate flutterfire_cli`).

### 2. Firebase Configuration
1. Run the compilation helper inside your root folder to map your configurations natively:
   ```bash
   flutterfire configure
