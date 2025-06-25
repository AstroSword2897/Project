# Sound Button App

This app lets you tap a picture (like "rice" or "chips") and hear the matching sound. The app also vibrates (haptic feedback) when you press a button. Built with React Native and Expo.

## Features
- Tap a picture to play a sound
- Device vibrates (haptic feedback) on button press
- Simple, kid-friendly interface

## Prerequisites
- Node.js (LTS recommended)
- npm (comes with Node.js)
- An iPad (or iPhone/Android device)
- [Expo Go](https://expo.dev/client) app installed on your device (from the App Store or Google Play)

## Setup Instructions

1. **Clone this repository:**
   ```bash
   git clone <your-repo-url>
   cd sound-button-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   expo install expo-av expo-haptics
   ```

3. **Add your assets:**
   - Place your images in `assets/images/` (e.g., `rice.png`, `chips.png`)
   - Place your sound files in `assets/sounds/` (e.g., `rice.mp3`, `chips.mp3`)

4. **Start the app:**
   ```bash
   npx expo start
   ```
   - A QR code will appear in your terminal or browser.

5. **Open on your device:**
   - Open the Expo Go app on your iPad/phone.
   - Scan the QR code to load the app.

## Usage
- Tap the rice or chips image to play the corresponding sound and feel a vibration.
- Add more items by editing the `items` array in `App.js`.

## Troubleshooting
- Make sure your computer and device are on the same Wi-Fi network.
- If the QR code doesn't work, try entering the URL manually in Expo Go.
- For more help, see the [Expo documentation](https://docs.expo.dev/).

---

Enjoy your sound button app!
