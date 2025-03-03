# travel_avatar_app
# Dynamic 3D Docent Mobile App

## Project Overview
This project is a **Dynamic 3D Docent Mobile App** designed to enhance the immersive experience of tourists by using **React Native** and **Three.js**. The app features a virtual 3D avatar that interacts with users through voice input and delivers historical information about a site. The goal is to build a basic prototype in **12 days**.

## Tech Stack
- **Framework:** React Native (Expo CLI)
- **3D Rendering:** Three.js via `@react-three/fiber`
- **Voice Input & Text-to-Speech:** Expo Speech API
- **Optional AI Backend:** OpenAI API

## Folder Structure
```
📁 holographic-docent-app
├─ App.js              // Main app component
├─ speech.js           // Speech recognition and text-to-speech logic
├─ Avatar.js           // 3D avatar component
└─ package.json        // Dependencies
```

## Roadmap (12-Day Sprint)

### Day 1-2: Project Setup
- Install Expo CLI: `npx create-expo-app holographic-docent`
- Install dependencies:
```bash
npm install @react-three/fiber three expo-speech expo-av
```
- Set up folder structure.

### Day 3-4: 3D Scene Setup
- Create a simple 3D sphere model.
- Add camera, lighting, and background using `@react-three/fiber`.

### Day 5-6: Voice Interaction
- Install and configure **expo-speech**.
- Implement basic voice recognition and text-to-speech logic.

### Day 7-8: Avatar Animation
- Use **@react-spring/three** to animate basic gestures like nodding.
- Sync animations with speech events.

### Day 9-10: Dwell Time Tracking
- Implement simple dwell time tracking using JavaScript timers.
- Store dwell time locally.

### Day 11: Local Tidbits
- Add random local facts using a static JSON list.
- Display facts during avatar interactions.

### Day 12: Final Testing & APK Build
- Test the app on Expo Go for both Android and iOS.
- Build APK:
```bash
expo build:android
```

## Optional Features (If Time Permits)
- Multi-language support.
- Customizable avatars.
- Background ambient sound.

## How to Run the Project
1. Clone the repository:
```bash
git clone <repository-url>
cd holographic-docent-app
```
2. Install dependencies:
```bash
npm install
```
3. Start the app:
```bash
expo start
```

## Contact
For questions or suggestions, feel free to reach out!


