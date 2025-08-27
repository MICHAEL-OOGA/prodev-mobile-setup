# Expo Go Project Setup

This repository contains a React Native project bootstrapped with Expo.  
This README documents the full setup process, the steps I followed during scaffolding, and the challenges or observations I faced.

---

## Requirements

Before starting, make sure the following are installed:

- [Node.js](https://nodejs.org/) (Latest LTS recommended)
- npm or yarn
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Expo Go app (installed on a mobile device)

---

## Expo Go Installation

1. Visit the official Expo Go homepage: [https://expo.dev/go](https://expo.dev/go).
2. Select the latest **Expo SDK version**.
3. Install Expo Go on your device:
   - **Android:** [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
   - **iOS:** [Apple App Store](https://apps.apple.com/app/expo-go/id982107779)
4. Open the **Expo Go** app.
5. Create a new account or log in if you already have one.

---

## Steps for Scaffolding the Project

1. **Navigate to the project directory**

   ```bash
   cd prodev-mobile-setup

   ```

2. **Initialize a new Expo project**

   npx create-expo-app@latest .

3. **Run and Test the Application**

npx expo start

4. **Observations from npm run reset-project**

The command clears the existing project files and cache.

Dependencies are reinstalled from scratch.

The project resets to a clean state, similar to just after running create-expo-app.

Custom modifications, like the updated text in index.tsx, are removed.

This is useful for fixing corrupted builds or dependency mismatches.
