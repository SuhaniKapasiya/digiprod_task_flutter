# Digiprod Task Flutter

This Flutter project demonstrates a simple implementation of a home page inspired by the Myntra app design. It uses Appwrite for the backend.

## Features
- Product list display
- Responsive UI for mobile and web

## Getting Started

### Prerequisites
- Flutter SDK
- Android Studio
- Xcode (for iOS)
- Appwrite Server
- Firebase Account

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SuhaniKapasiya/digiprod_task_flutter.git
   cd digiprod_task_flutter

Install dependencies:

flutter pub get

Set up Appwrite:

Follow the instructions here to set up Appwrite for your project.
Ensure you have an Appwrite server running and note the endpoint and project ID.
Create a .env file in the root of your project and add your Appwrite endpoint and project ID:

APPWRITE_ENDPOINT=https://your-appwrite-endpoint
APPWRITE_PROJECT_ID=your-project-id

Set up Firebase:

Go to the Firebase Console.
Create a new project or use an existing one.
For Android:
Download google-services.json and place it in the android/app directory.
Add the classpath to the [project]/android/build.gradle file

classpath 'com.google.gms:google-services:4.3.3'


Apply the plugin to the [project]/android/app/build.gradle file

apply plugin: 'com.google.gms.google-services'

Run the app:- flutter run


Project Structure
lib/main.dart: Main entry point of the application.
Appwrite Structure
Collection: products
Document: { id }
Fields: name, description, image
APK
You can download the APK for this project here.

Troubleshooting
If you encounter any issues, please refer to the official Flutter documentation here or the Appwrite setup guide here.

License
This project is licensed under the MIT License.
