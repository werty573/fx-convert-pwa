Currency Converter – Progressive Web App (PWA)
A mobile-first, real-time currency converter designed for speed and offline reliability. This project was developed as part of Assignment 4, focusing on transforming a web-based utility into a functional Android application using PWA standards.

🚀 Live Demo
View the Live Site: https://werty573.github.io/fx-convert-pwa/

✨ Key Features
Real-time Exchange Rates: Fetches live data to ensure accurate financial conversions.

PWA Integration: Installable directly onto Android home screens with a custom branded icon.

Offline Capability: Powered by a Service Worker to ensure the UI remains functional even without a network connection.

Responsive UI: Optimized for mobile viewports using a clean, professional blue-and-white theme.

🛠️ Technical Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

PWA Core: * manifest.json: Defines the app identity, icons, and theme colors.

sw.js (Service Worker): Handles background caching and offline support.

Deployment: GitHub Pages

Packaging: PWABuilder (Android APK generation)

📱 UI/UX Considerations
User Flow: Designed for "one-handed" mobile use with large input fields and clear action buttons.

Branding: A custom logo was designed and implemented across multiple sizes (192x192 and 512x512) to ensure a native look on Android launchers.

Visual Feedback: High-contrast color scheme (#2E75B6) used to ensure readability in various lighting conditions (e.g., outdoor travel).

📂 Project Structure
Plaintext
├── index.html        # Main application interface
├── style.css         # Custom mobile-first styling
├── script.js        # Conversion logic and API integration
├── manifest.json     # Web App Manifest for PWA installation
├── sw.js             # Service Worker for offline caching
├── icon-192.png      # App icon (192x192)
└── icon-512.png      # App icon (512x512)
📝 Installation
Visit the live link on an Android device using Chrome.

Select "Add to Home Screen" when prompted.

Open the app from your home screen to experience the full standalone interface.
