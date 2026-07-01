<div align="center">
  <br />
  <img src="assets/readme/hero.png" alt="Project Banner">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="Expo" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=F02E65" alt="Appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
  </div>

  <h3 align="center">Food Delivery Mobile App</h3>
</div>

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

## <a name="introduction">🤖 Introduction</a>

Built with React Native, TypeScript, and Tailwind CSS, this full-stack Food Delivery app features Google Authentication, dynamic search and filters, cart functionality, and smooth navigation. Powered by Appwrite for backend, database, and file storage, it delivers a responsive, scalable, and intuitive user experience with modern UI/UX best practices.

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Appwrite](https://appwrite.io/)** — an open-source backend-as-a-service platform offering authentication, databases, file storage, real-time messaging, and serverless functions.

- **[Expo](https://expo.dev/)** — an open-source platform for building universal native apps (Android, iOS, web) using JavaScript/TypeScript and React Native. Features file-based routing via Expo Router, fast refresh, native modules, over-the-air updates (EAS), and streamlined app deployment.

- **[NativeWind](https://www.nativewind.dev/)** — brings Tailwind CSS to React Native and Expo, allowing utility-first styling for mobile components.

- **[React Native](https://reactnative.dev/)** — a framework for building mobile UIs with React, enabling component-based, cross-platform development with declarative UI and deep native API support.

- **[Tailwind CSS](https://tailwindcss.com/)** — a utility-first CSS framework enabling rapid UI design via low-level classes.

- **[TypeScript](https://www.typescriptlang.org/)** — a statically-typed superset of JavaScript providing type annotations, interfaces, enums, and generics for improved error detection and maintainability.

- **[Zustand](https://github.com/pmndrs/zustand)** — a minimal, hook-based state management library for React and React Native, offering global state with zero boilerplate and no context providers.

- **[Sentry](https://sentry.io/)** — an error tracking and performance monitoring tool for React Native apps, helping detect, diagnose, and fix issues in real-time.

## <a name="features">🔋 Features</a>

👉 **Google Authentication**: Secure and seamless user sign-ins using Google.

👉 **Home Page**: Showcases the latest offers and directs users to filtered search results.

👉 **Search Page**: Lets users explore all foods with category filters and keyword search.

👉 **Product Details Page**: Displays food images, key details, and allows adding items to the cart.

👉 **Cart Page**: Review selected items and see the total price.

👉 **Profile Page**: Manage user settings and preferences.

👉 **Appwrite Integration**: Handles backend database and file storage for food items.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Installation**

```bash
npm install
```

**Set Up Environment Variables**

Create a `.env` file in the root of your project:

```env
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_ENDPOINT=
```

Replace the placeholder values with your Appwrite project credentials.

**Running the Project**

```bash
npx expo start
```

Scan the QR code with Expo Go on your phone to view the project.
