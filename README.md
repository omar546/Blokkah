# Blokkah 🏢

<img src="Screenshots/logo.png" alt="Blokkah Logo" width="200" height="200"/>

A modern property marketplace mobile application built with Flutter, offering a seamless experience for property buyers, sellers, and agents. Features an AI-powered chatbot, real-time notifications, and multilingual support.

## ✨ Key Features

- 🏠 Property Listings with Advanced Filters
- 🏢 Agent Profiles
- 🔍 Search Functionality
- 🗂️ Saved Properties & Favorites
- 📊 User Profiles & Ratings
- 📈 Market Trends & Insights
- 🏦 Payment Integration (paymob)
- 🤖 AI-Powered Chatbot Assistant
- 🔐 Secure Authentication (Email, Google, Twitter)
- 🌙 Dynamic Theme (Light/Dark Mode)
- 🌐 Multilingual Support (English & Arabic)
- 📍 Interactive Maps & Location Services
- 🔔 Real-time Push Notifications
- 📱 Intuitive Onboarding Experience
- 💼 Property Management Dashboard
- 📊 Analytics & Performance Tracking

## 🎯 Technical Highlights

- **State Management**: Advanced BLoC pattern implementation with proper state handling
- **Custom Widgets**: Reusable widget library following Material Design 3 guidelines
- **API Integration**: RESTful API integration with error handling and retry mechanisms

## 🏗️ Architecture & Design Patterns

### BLoC-First Architecture
We chose a Feature-First architecture with BLoC pattern because:

#### 1. Project Structure
```
lib/
├── bloc_observer.dart      # Global BLoC state observer
├── firebase_options.dart   # Firebase configuration
├── main.dart              # Application entry point
├── generated/            # Generated localization files
├── l10n/                # Localization resources
├── layout/              # Core layout components
│   ├── app/            # Main app layout with bottom navigation
│   └── fab/            # Floating action button & dialogs
├── models/             # Data models and DTOs
├── modules/           # Feature modules
│   ├── authentication/  # Auth related features
│   ├── home/           # Home screen features
│   ├── property/       # Property listing features
│   ├── crm/           # CRM & Analytics features
│   └── more/          # Additional features
└── shared/           # Shared components
    ├── cubit/        # Global state management
    ├── router/       # Navigation & routing
    ├── theme/        # App theming & styling
    ├── utils/        # Common utilities
    └── widgets/      # Reusable widgets
```

#### 2. Architecture Benefits

- **Feature Separation**: Each feature (property, authentication, CRM) is self-contained
- **State Management**: BLoC pattern for predictable state handling
- **Modular Design**: Features can be developed and tested independently
- **Code Organization**: Clear separation between UI, business logic, and data
- **Scalability**: Easy to add new features without affecting existing one

## 📱 Screenshots

### 🧑‍💼 Agent Flow

* ![](Screenshots/agent_flow/Splash.png)
* ![](Screenshots/agent_flow/On%20Boarding.png)
* ![](Screenshots/agent_flow/Create%20Account.png)
* ![](Screenshots/agent_flow/Log%20In.png)
* ![](Screenshots/agent_flow/Dashboard.png)
* ![](Screenshots/agent_flow/Property%20Listings.png)
* ![](Screenshots/agent_flow/Add%20Listings.png)
* ![](Screenshots/agent_flow/Stepper%20Flow.png)
* ![](Screenshots/agent_flow/Profile.png)
* ![](Screenshots/agent_flow/More.png)
* ![sups](https://github.com/user-attachments/assets/e1d700c4-fa0c-42a8-b7f1-60a783da1db9)


### 🙋‍♂️ User Flow

* ![userOnboardin](https://github.com/user-attachments/assets/86562493-aadd-400e-be5d-fe23d5f55040)
* ![](Screenshots/user_flow/Home.png)
* ![](Screenshots/user_flow/Explore.png)
* ![](Screenshots/user_flow/Search.png)
* ![](Screenshots/user_flow/Property.png)
* ![](Screenshots/user_flow/Chat%20Bot.png)
* ![](Screenshots/user_flow/More.png)
* ![](Screenshots/user_flow/App%20Information.png)



## 🛠️ Technologies Used

- **Framework**: Flutter 3.x
- **State Management**: Flutter Bloc
- **Backend Services**: Firebase (Auth, Analytics, Messaging)
- **Maps**: Google Maps Flutter
- **Networking**: Dio
- **Local Storage**: SharedPreferences
- **Localization**: Flutter Intl
- **Authentication**: Firebase Auth, Google Sign-In, Twitter Login
- **Notifications**: Firebase Cloud Messaging, Flutter Local Notifications
- **Analytics**: Firebase Analytics
- **Branch.io**: Deep Linking
- **Payment Integration**: Paymob




## 📥 Download
> **Note**: App download links may not be available as the client didn't deploy. Check back later.

[![Get it on App Store](https://img.shields.io/badge/Download_on-the_App_Store-black.svg?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/us/app/%D8%A8%D9%84%D9%88%D9%83%D9%87-%D8%B9%D9%82%D8%A7%D8%B1-%D9%88-%D8%A7%D9%83%D8%AB%D8%B1-blokkah/id6740733193)
[![Get it on Google Play](https://img.shields.io/badge/Get_it_on-Google_Play-green.svg?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.blokkahco.blokkah)


