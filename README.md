# Chatbot Stress Detector Project

This project is a web application that incorporates a stress detection chatbot and features a sleep routine section. Users can sign up, log in, and subscribe to different sleep routines based on the number of hours they wish to achieve for a better sleep pattern.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Firebase Configuration](#firebase-configuration)
- [Contributing](#contributing)
- [License](#license)

## Features
1. **Authentication System:**
   - Users can sign up with a valid email, password, and username.
   - Authentication is handled using Firebase Authentication.

2. **Sleep Routine Section:**
   - Users can explore different sleep routines with associated images and descriptions.
   - Each routine has a "Subscribe" button.

3. **Social Sign-In:**
   - Users can sign up using their Facebook, Twitter, or Google+ accounts.

4. **Firebase Integration:**
   - Firebase is used for real-time data storage and authentication.
   - Firestore is utilized for storing data related to users and sleep routines.

## Prerequisites
- [Firebase Account](https://firebase.google.com/): Set up a Firebase project to obtain API keys and configuration.
- Web browser with ES6 module support.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Open `index.html` in a web browser.

## Usage
1. Sign up for a new account using a valid email, password, and username.
2. Explore different sleep routines and click the "Subscribe" button for the desired routine.
3. Social sign-in options are available for convenience.
4. The application uses Firebase to handle authentication and store user-related data.

## Firebase Configuration
1. Replace the placeholder Firebase configuration in the `<script>` tag of `index.html` with your actual Firebase project configuration.

   ```javascript
   // Your web app's Firebase configuration
   const firebaseConfig = {
       // Replace with your actual configuration
       apiKey: "YOUR_API_KEY",
       authDomain: "YOUR_AUTH_DOMAIN",
       projectId: "YOUR_PROJECT_ID",
       storageBucket: "YOUR_STORAGE_BUCKET",
       messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
       appId: "YOUR_APP_ID",
       measurementId: "YOUR_MEASUREMENT_ID"
   };
   ```

2. Set up Firebase Authentication, Firestore, and update the security rules accordingly.

## Contributing
Feel free to contribute to the project. Create a pull request, and we'll review it together!

## License
This project is licensed under the [MIT License](LICENSE).
