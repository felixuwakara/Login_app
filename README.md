Felix Chigozirim Uwakara
BHU/24/04/05/0093
Computer science

# Login App

A simple Flutter app with a login screen and a registration screen, built as a school assignment.

**Name:** Your Full Name
**Matric No:** Your Matric Number
**Course:** Your Course Code and Title

## Features

- Login screen with email and password fields
- Registration screen with full name, email, password and confirm password
- Form validation:
  - Required fields cannot be empty
  - Email must be in a valid format
  - Password must be at least 6 characters
  - Confirm password must match the password
- Show and hide password toggle
- Navigation between the login and registration screens
- Works on Android, web and Windows from the same code

## Technologies Used

- Flutter
- Dart
- Material 3 design
- Android Studio

## Project Structure

```
login_app/
├── lib/
│   └── main.dart     # App entry point, LoginScreen and RegisterScreen
├── pubspec.yaml      # Project settings and dependencies
└── README.md
```

## How to Run

1. Install [Flutter](https://docs.flutter.dev/get-started/install) and Android Studio.
2. Clone this repository:
   ```
   git clone https://github.com/yourusername/login_app.git
   cd login_app
   ```
3. Get the dependencies:
   ```
   flutter pub get
   ```
4. Run the app:
   ```
   flutter run -d chrome
   ```
   To run on an Android phone or emulator instead, use `flutter run`.

## Screenshots

Add screenshots of the login and registration screens here.

## Notes

This app has no backend. Validation runs on the device, and a message is shown when the form is filled in correctly.
