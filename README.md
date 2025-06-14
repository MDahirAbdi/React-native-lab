
# 🧪 React Native Lab

*A playground for testing React Native libraries, components, and code snippets.*

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

---

## 📖 Overview

**React Native Lab** is a personal development lab and testing ground for experimenting with:

- New libraries and third-party integrations
- Custom components and animations
- Performance optimizations and rendering techniques
- Useful code snippets, hooks, and utilities

This project is ideal for prototyping, rapid testing, and storing reusable patterns.

---

## 🧪 Purpose

- 🧱 Build and preview UI components
- 🔌 Try out and debug third-party packages
- ⚡ Benchmark performance and UX patterns
- 🧠 Collect useful tricks, patterns, and hooks

---

## 🚀 Features

- ⚛️ **Component Demos** – Reusable UI elements like buttons, modals, inputs, etc.
- 🛠️ **Library Integration Tests** – Firebase, maps, Chatwoot, navigation, etc.
- 📦 **Hooks & Utilities** – Custom logic, formatters, and reusable tools
- 🧩 **UI/UX Prototyping** – Test gestures, animations, layout techniques
- 🧠 **Snippets Archive** – Store helpful patterns and logic for reuse

---

## 🔧 Tech Stack

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- Navigation: React Navigation
- State Management: Zustand / Redux Toolkit / Context API *(varies by test)*
- Testing: Jest & React Native Testing Library *(optional)*

---

## 📂 Project Structure

```bash
react-native-lab/
├── components/       # Reusable UI components
├── screens/          # Test screens for demos
├── experiments/      # Library/component integrations
├── hooks/            # Custom React hooks
├── utils/            # Helpers and formatters
├── assets/           # Fonts, images, icons
├── App.tsx           # Entry point
└── README.md
````

---

## ⚙️ Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/react-native-lab.git

# Navigate into the project folder
cd react-native-lab

# Install dependencies
npm install  # or yarn install

# Start the development server
npx expo start  # or npm start / yarn start
```

> Replace `expo` with `react-native run-android` or `run-ios` if not using Expo.

---

## 💡 Usage Tips

* Add new test screens in `/screens` and wire them in `App.tsx`
* Store reusable code in `/hooks` and `/utils`
* Commit only generic, shareable snippets — avoid hardcoded credentials

---

## 🧠 Snippet Example

Here’s a sample utility hook for quick Android toast messages:

```ts
import { ToastAndroid } from 'react-native';

export const useToast = () => {
  const show = (msg: string) => {
    ToastAndroid.show(msg, ToastAndroid.SHORT);
  };
  return { show };
};
```

---

## 📝 Notes

* This project is intended for **personal use**, learning, and fast prototyping
* Expo is used for quick setup and device testing
* Avoid committing any sensitive keys — use `.env` for local secrets

---

## 🤝 Contributing

Found a cool trick or fixed a bug? Open a PR or fork and customize for your own lab!


