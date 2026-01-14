# 🎬 Movie App - Flutter

A modern, cross-platform movie application built with Flutter, featuring user authentication and a clean architecture design. This project demonstrates best practices in Flutter development with responsive UI design and scalable code structure.

![Flutter](https://img.shields.io/badge/Flutter-3.4.4+-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.4.4+-0175C2?logo=dart&logoColor=white)
![License](https://img.shields.io/badge/License-Not%20Specified-lightgrey)

## ✨ Features

- 🔐 **User Authentication** - Login and sign-up screens for user management
- 📱 **Responsive Design** - Adaptive UI using ScreenUtil for all screen sizes
- 🎨 **Modern UI/UX** - Clean and intuitive Material Design interface
- 🏗️ **Clean Architecture** - Separation of concerns with core and presentation layers
- 🌐 **Cross-Platform Support** - Runs on Android, iOS, Web, Windows, macOS, and Linux
- 🚀 **Splash Screen** - Professional app launch experience

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Flutter** | Cross-platform mobile framework |
| **Dart** | Programming language |
| **flutter_screenutil** | Responsive UI adaptation |
| **Material Design** | UI component library |

### Dependencies
```yaml
dependencies:
  flutter_screenutil: ^5.9.3  # Responsive design
  cupertino_icons: ^1.0.6     # iOS-style icons

```

📁 Project Structure
lib/
├── core/                    # Core functionality
│   ├── routes_manager/     # Navigation and routing
│   └── utils/              # Utility functions and helpers
├── presentation/            # UI Layer
│   ├── auth/               # Authentication screens
│   │   └── pages/
│   │       ├── login_screen.dart
│   │       └── sign_up_screen.dart
│   └── splash/             # Splash screen
└── main.dart               # Application entry point



🚀 Getting Started
Prerequisites
Before you begin, ensure you have the following installed:

Flutter SDK (version 3.4.4 or higher)

Dart SDK (comes with Flutter)

An IDE (VS Code, Android Studio, or IntelliJ IDEA)

For mobile: Android Studio/Xcode

For desktop: Platform-specific requirements


Installation
Clone the repository

bash
git clone https://github.com/HamoudAl-Jowlahi/Movie-App-with-Dart-Flutter.git
cd Movie-App-with-Dart-Flutter
Install dependencies

bash
flutter pub get
Run the app

bash
flutter run
Platform-Specific Commands
bash
# Run on Chrome (Web)
flutter run -d chrome

# Run on Windows
flutter run -d windows

# Run on macOS
flutter run -d macos

# Run on Linux
flutter run -d linux

# Run on Android
flutter run -d android

# Run on iOS
flutter run -d ios
📱 App Screens
Splash Screen - Welcome screen with app branding

Login Screen - User authentication interface

Sign Up Screen - New user registration

(More screens to be added)

🧪 Testing
Run the test suite:

bash
# Run all tests
flutter test

# Run tests with coverage
flutter test --coverage
🏗️ Build for Production
Android (APK)
bash
flutter build apk --release
Android (App Bundle)
bash
flutter build appbundle --release
iOS
bash
flutter build ios --release
Web
bash
flutter build web --release
Windows
bash
flutter build windows --release
macOS
bash
flutter build macos --release
Linux
bash
flutter build linux --release
🎯 Roadmap
 Integrate movie database API (TMDB/OMDb)

 Implement movie browsing and search functionality

 Add movie details page with ratings and reviews

 Implement favorites/watchlist feature

 Add user profile management

 Implement state management (Bloc/Provider/Riverpod)

 Add offline mode with local database

 Include dark mode theme

 Add localization support (English/Arabic)

 Implement unit and widget tests

📐 Architecture
This project follows Clean Architecture principles:

Presentation Layer (lib/presentation/) - UI components and screens

Core Layer (lib/core/) - Business logic, routing, and utilities

(Domain and Data layers to be added)

🤝 Contributing
Contributions, issues, and feature requests are welcome!

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

👨‍💻 Author
Hamoud Al-Jowlahi

GitHub: @HamoudAl-Jowlahi

📄 License
This project currently has no license specified. Consider adding a license (MIT, Apache 2.0, etc.) if you plan to make it open source.

🙏 Acknowledgments
Flutter Documentation

Material Design Guidelines

Flutter ScreenUtil Package


