# 🔐 Android Login Application

A simple Android Login Application developed using **Kotlin** in **Android Studio**. This project demonstrates the basics of user authentication, activity navigation, Intent communication, and XML-based user interface design.

---

## 📱 Features

- 🔑 User Login Screen
- ✅ Input validation for username and password
- 📲 Navigation between Activities using Intent
- 🎨 Clean and user-friendly interface
- 🏫 University logo displayed on the login screen
- ⚡ Developed using Kotlin and Android Studio

---

## 📂 Project Structure

```
24012021094_MAD_Prac3
│
├── app
│   ├── manifests
│   │   └── AndroidManifest.xml
│   │
│   ├── java
│   │   ├── LoginActivity.kt
│   │   └── MainActivity.kt
│   │
│   ├── res
│   │   ├── layout
│   │   │   ├── activity_login.xml
│   │   │   └── activity_main.xml
│   │   │
│   │   ├── drawable
│   │   │   └── guni_pink_logo.png
│   │   │
│   │   └── values
│   │       ├── colors.xml
│   │       ├── strings.xml
│   │       └── themes.xml
│   │
│   └── build.gradle.kts
│
└── README.md
```

---

## 🛠 Technologies Used

- Kotlin
- Android Studio
- XML Layout
- Android Intents
- ConstraintLayout
- Material Design Components

---

## 📖 Project Description

This project is a basic Android Login Application that allows users to enter their login credentials. After successful validation, the application navigates to the Home Screen using Android Intents.

The project is designed to help beginners understand Android Activity lifecycle, UI development, event handling, and screen navigation.

---

## 📁 File Description

### 📄 LoginActivity.kt

- Displays the login screen.
- Accepts username and password.
- Validates user input.
- Starts the MainActivity after successful login.

---

### 📄 MainActivity.kt

- Displays the home screen after login.
- Receives data from LoginActivity (if applicable).
- Serves as the main dashboard of the application.

---

### 📄 activity_login.xml

Defines the Login Screen UI.

Contains:

- University Logo
- Username EditText
- Password EditText
- Login Button

---

### 📄 activity_main.xml

Defines the Home Screen UI displayed after successful login.

---

### 📄 AndroidManifest.xml

Registers all application activities and defines the launcher activity.

---

### 📄 guni_pink_logo.png

University logo displayed on the login screen.

---

## 🔄 Application Flow

```
Application Starts
        │
        ▼
LoginActivity
        │
        ▼
User Enters Username
        │
        ▼
User Enters Password
        │
        ▼
Click Login Button
        │
        ▼
Validate Credentials
        │
        ├───────────────┐
        │               │
        ▼               ▼
Valid Login      Invalid Login
        │               │
        ▼               ▼
MainActivity    Error Message
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/24012021094_MAD_Prac3.git
```

### 2. Open the project

Open the project using Android Studio.

### 3. Sync Gradle

Allow Gradle to download all dependencies.

### 4. Run the application

Run the app on an Android Emulator or a physical Android device.

---

## 📸 Screenshots


<img width="365" height="652" alt="Screenshot 2026-07-30 184754" src="https://github.com/user-attachments/assets/2d899a55-3bc0-4038-a70e-eafbe5c6e176" />
<img width="406" height="727" alt="Screenshot 2026-07-30 184810" src="https://github.com/user-attachments/assets/5b7d1992-522d-45d5-a3a5-0cff328f5ead" />


## 📚 Learning Outcomes

This project helps in understanding:

- Android Studio Project Structure
- Kotlin Programming
- Android Activities
- XML Layout Design
- Intent Navigation
- User Input Handling
- Button Click Events
- Basic Login Validation

---

## 🔮 Future Enhancements

- Firebase Authentication
- SQLite Database
- Remember Me Feature
- Forgot Password
- User Registration
- Password Visibility Toggle
- Dark Mode Support
- Material 3 Design
- Input Error Messages
- MVVM Architecture

---

## 🐞 Known Limitations

- Uses basic login validation.
- No database connectivity.
- Password is not encrypted.
- No registration functionality.

---

## 🎯 Educational Purpose

This project was developed as part of the **Mobile Application Development (MAD)** practical coursework to understand Android application development using Kotlin.

---

## 👨‍💻 Developed By

**Anubhav Kanthariya**

🎓 B.Tech – Information Technology

🏫 Ganpat University

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is developed for educational purposes only.
