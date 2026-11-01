# 📱 Login App 

> **Student:** Felix Chigozirim Uwakara  
> **Matric No:** BHU/24/04/05/0093 
> **Department:** Computer Science  
> **Repository:** [github.com/felixuwakara/Login_app](https://github.com/felixuwakara/Login_app)

---

## 📌 Project Overview

This is a mobile application built with **Flutter** and **Dart** as a school assignment. It demonstrates the implementation of a **Login Screen** and a **Registration Screen** with complete client-side form validation, built using Flutter's Material 3 design system.

The app runs on **Android**, **Web**, and **Windows** from a single shared codebase.

---

## ✨ Features

### 🔐 Login Screen
- Email input field with keyboard type set to email
- Password input field with show/hide toggle
- Form validation:
  - Email field cannot be empty
  - Email must contain `@` and `.` to be valid
  - Password cannot be empty
  - Password must be at least 6 characters long
- On successful validation, a success **SnackBar** message is shown
- "Don't have an account?" link to navigate to the Registration screen

### 📝 Registration Screen
- Full name input field
- Email input field
- Password input field with show/hide toggle
- Confirm password field
- Form validation:
  - All fields are required
  - Email must be in a valid format
  - Password must be at least 6 characters
  - Confirm password must exactly match the password
- On successful registration, a success **SnackBar** is shown and the user is navigated back to the Login screen
- "Already have an account?" link to go back to Login

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Flutter | Cross-platform UI framework |
| Dart | Programming language |
| Material 3 | UI design system (Indigo color scheme) |
| Android Studio | IDE used for development |

---

## 📁 Project Structure

```
login_app/
├── lib/
│   └── main.dart          # App entry point + LoginScreen + RegisterScreen
├── android/               # Android platform files
├── ios/                   # iOS platform files
├── web/                   # Web platform files
├── windows/               # Windows platform files
├── test/
│   └── widget_test.dart   # Default Flutter tests
├── pubspec.yaml           # Project metadata and dependencies
└── README.md              # Project documentation
```

### Key Classes in `main.dart`

| Class | Type | Description |
|-------|------|-------------|
| `MyApp` | `StatelessWidget` | Root app widget, sets theme and home screen |
| `LoginScreen` | `StatefulWidget` | Login form with email and password fields |
| `_LoginScreenState` | `State` | Handles login form state and validation logic |
| `RegisterScreen` | `StatefulWidget` | Registration form with 4 input fields |
| `_RegisterScreenState` | `State` | Handles registration form state and validation |

---

## 🚀 How to Run

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) installed
- Android Studio or VS Code with Flutter extension
- An Android emulator or physical device (or a browser for web)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/felixuwakara/Login_app.git
   cd Login_app/login_app
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run on Android (emulator or device):**
   ```bash
   flutter run
   ```

4. **Run on Web (Chrome):**
   ```bash
   flutter run -d chrome
   ```

5. **Run on Windows:**
   ```bash
   flutter run -d windows
   ```

---

## 🧠 Concepts Demonstrated

- **StatefulWidget & State management** — managing form input and password visibility toggle
- **Form & GlobalKey** — Flutter's built-in form validation system
- **TextEditingController** — capturing and reading text field values
- **Navigator** — screen-to-screen navigation using `push` and `pop`
- **SnackBar** — displaying feedback messages to the user
- **Material 3 design** — using `FilledButton`, `TextFormField`, `OutlineInputBorder`
- **Cross-platform development** — single Dart codebase targeting Android, Web, and Windows

---

## ⚠️ Notes

- This app has **no backend or database**. All validation is performed on the device (client-side only).
- No actual authentication occurs — the login and registration success messages are simulated UI feedback.
- This project was created purely for learning and assignment purposes.

---

