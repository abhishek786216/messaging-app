# FlashChat - Real-time Messaging App

A modern Flutter messaging application with Firebase backend integration, featuring real-time chat capabilities, user authentication, and a beautiful animated UI.

## 🚀 Features

- **Real-time Messaging**: Instant messaging with Firebase Firestore
- **User Authentication**: Secure login and registration with Firebase Auth
- **Animated UI**: Beautiful animations using AnimatedTextKit
- **Modern Design**: Clean, intuitive interface with dark theme
- **Cross-platform**: Works on both Android and iOS

## 🛠️ Technologies Used

- **Frontend**: Flutter (Dart)
- **Backend**: Firebase (Firestore, Authentication)
- **State Management**: StatefulWidget
- **Animations**: AnimatedTextKit, Custom Animations
- **UI Components**: Material Design

## 📱 Screenshots

The app includes:
- Welcome screen with animated logo
- User registration and login
- Real-time chat interface
- Message bubbles with user identification

## 🔧 Setup Instructions

1. **Prerequisites**
   - Flutter SDK installed
   - Firebase project set up
   - Android Studio / VS Code

2. **Installation**
   ```bash
   git clone https://github.com/abhishek786216/messaging-app.git
   cd messaging-app
   flutter pub get
   ```

3. **Firebase Configuration**
   - Add your `google-services.json` to `android/app/`
   - Configure Firebase Authentication and Firestore

4. **Run the App**
   ```bash
   flutter run
   ```

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8
  animated_text_kit: ^4.2.3
  firebase_core: ^2.32.0
  firebase_auth: ^4.17.5
  cloud_firestore: ^4.15.5
  modal_progress_hud_nsn: ^0.5.1
  flutter_launcher_icons: ^0.13.1
```

## 🏗️ Project Structure

```
lib/
├── main.dart                 # App entry point
├── constants.dart           # App constants
└── screens/
    ├── welcome_screen.dart  # Landing page with animations
    ├── login_screen.dart    # User login
    ├── registration_screen.dart # User registration
    └── chat_screen.dart     # Main chat interface
```

## 🎯 Key Features Implementation

- **Firebase Integration**: Real-time database for instant messaging
- **Authentication**: Secure user login/registration system
- **Responsive UI**: Adapts to different screen sizes
- **Animation Effects**: Smooth transitions and loading animations
- **Message Persistence**: All messages stored in Firestore

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

**Abhishek Kumar**
- GitHub: [@abhishek786216](https://github.com/abhishek786216)
- Portfolio: [Your Portfolio Link]

---

*Built with ❤️ using Flutter and Firebase*
