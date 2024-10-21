
# Welcome to Click2Contact App 🖐️
Click2Contact is a smart solution to simplify managing and storing contact information. Our app allows you to extract key details from visiting and business cards effortlessly, turning them into well-organized mobile contacts. Whether you're at a networking event or just need to organize your connections, Click2Contact helps you capture and store important details with just a click. No more manual data entry—just snap, save, and connect instantly.
      

# Table of Contents
   - [Technologies Used](#technologies-used)
   - [Features](#features)
   - [Getting Started](#getting-started)
      - [Clone Repository](#clone-repository)
      - [Create an Expo App](#create-an-expo-aApp)
      - [Install All Dependencies](#install-all-dependencies)
      - [Setup Environment Variables](#setup-environment-variables)
      - [Start the App](#start-the-pp)
     
# Technologies Used
   - Frontend:
      - [Expo](https://docs.expo.dev/)
      - [React Native](https://reactnative.dev/docs/getting-started)
   - Backend:
      - [Express](https://expressjs.com/)
      - [Axios](https://axios-http.com/docs/intro)
      - [Multer](https://www.npmjs.com/package/multer)
      - [CORS](https://www.npmjs.com/package/cors)
      - [Dotenv](https://www.npmjs.com/package/dotenv)

# Features
   - Instant capture of business card details
   - Automatic organization of contacts
   - Streamlined user interface for easy navigation
   - Integration with OpenAI for enhanced functionalities

# Getting Started
## Prerequisites
   - Node.js installed on your machine.
   - An OpenAI account for API access.
     
## Clone Repository
To clone the repository, run:
```
   git clone <Repository_Link>
```

## Create an Expo App
To create a new Expo app, execute:
```
npm install expo
npx create-expo-app NAME_OF_THE_APP
```

## Install All Dependencies
Navigate to your project directory and run the following commands to install the necessary dependencies:
```
npx expo install expo-image-picker
npx expo install @expo/vector-icons
npx expo install expo-permissions
npm install react-native-contacts
npm install typescript @types/react @types/react-native
npm install @react-native-async-storage/async-storage
npm install express
npm install multer
npm install cors
npm install dotenv
npm install axios
```

## Setup Environment Variables
To integrate OpenAI's capabilities, set up your API key. Create a .env file in the backend directory with the following content:
```
OPENAI_API_KEY=<Your_Key>
```
## Start the App
   - Open two terminal windows.
   - Navigate to the Expo project directory:
   ```
   cd expo_file_name
   ```
   - In the first terminal, start the Express server:
   ```
   node script.js
   ```
   - In the second terminal, run the Expo prebuild and launch the app on your device:
   ```
   npx expo prebuild
   npx expo run:android --device
   ```
   - The app will launch directly on your phone.
