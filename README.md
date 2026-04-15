# 📱 Todo App

A cross-platform mobile task management application (TODO) developed with modern technologies that allows you to create, edit, complete, and delete tasks. The application runs on iOS, Android, and web.

## 🚀 Quick Start

### Prerequisites

- Node.js and npm installed
- Expo CLI (can be installed globally or use npx)

### Installation

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the application:
   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in:

- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go) - Sandbox for rapid development
- [Web browser](https://docs.expo.dev/workflow/web/)

### Available Commands

```bash
npm start          # Start the development server
npm run android    # Open in Android emulator
npm run ios        # Open in iOS simulator
npm run web        # Open in web browser
npm run lint       # Run ESLint linter
npm run reset-project  # Reset the project
```

## 🛠️ Technologies Used

### Frontend

- **Expo** (~54.0.33) - Framework for React Native app development
- **React Native** (0.81.5) - Cross-platform mobile development framework
- **React** (19.1.0) - Base UI library
- **Expo Router** (~6.0.23) - File-based routing
- **React Navigation** - Navigation and tabs system

### Backend

- **Convex** (^1.35.1) - Serverless backend with real-time database

### Storage and Data

- `@react-native-async-storage/async-storage` - Local persistent storage

### Animations and Interactivity

- `react-native-reanimated` - Optimized animations
- `react-native-gesture-handler` - Gesture handling
- `expo-haptics` - Haptic feedback
- `expo-linear-gradient` - Visual gradients

### UI and Components

- `@expo/vector-icons` - Vector icons
- `expo-image` - Optimized image component
- `react-native-web` - Web support

### Development Tools

- **TypeScript** (~5.9.2) - Static typing
- **ESLint** (^9.25.0) - Code linter
- **eslint-config-expo** - Recommended configuration

## 📁 Project Structure

```
app/                    # Application screens
├── _layout.tsx        # Main layout
└── (tabs)/            # Tab navigation
    ├── index.tsx      # Main tasks screen
    └── settings.tsx   # Settings screen

components/            # Reusable components
├── TodoInput.tsx      # New task input
├── ProgressStats.tsx  # Progress statistics
├── Preferences.tsx    # User preferences
├── Header.tsx         # Header component
├── EmptyState.tsx     # Empty state
├── LoadingSpinner.tsx # Loading spinner
└── DangerZone.tsx     # Dangerous actions

convex/               # Serverless backend
├── schema.ts         # Database schema
├── todos.ts          # Backend functions (queries and mutations)
└── _generated/       # Auto-generated code

hooks/               # Custom hooks
└── useTheme.tsx      # Theme management

assets/              # Static assets
├── images/          # Icons and splash screens
└── styles/          # Shared styles
```

## ✨ Main Features

- ✅ Create, edit, and delete tasks
- ✅ Mark tasks as completed
- ✅ Real-time database with Convex
- ✅ Tab navigation (Home and Settings)
- ✅ Automatic light/dark theme
- ✅ Persistent storage
- ✅ Compatible with iOS, Android, and Web
- ✅ Modern and responsive interface

## 📚 Additional Resources

- [Expo Documentation](https://docs.expo.dev/)
- [Convex Documentation](https://docs.convex.dev/)
- [React Native Documentation](https://reactnative.dev/)
- [Expo Router Guide](https://docs.expo.dev/router/introduction/)
