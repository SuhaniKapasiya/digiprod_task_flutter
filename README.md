# digiprod_task

A new Flutter project.

This Flutter project demonstrates a simple implementation of a home page inspired by the Myntra app design. It uses Appwrite for the backend.

## Features
- Product list display
- Responsive UI for mobile and web

## Getting Started

### Prerequisites
- Flutter SDK
- Android Studio
- Xcode (for iOS)

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
Configure Appwrite in Flutter:

Create a .env file in the root of your project and add your Appwrite endpoint and project ID:


APPWRITE_ENDPOINT=https://your-appwrite-endpoint
APPWRITE_PROJECT_ID=your-project-id
Use the flutter_dotenv package to load these variables into your Flutter app.

Run the app:
flutter run

Project Structure
lib/main.dart: Main entry point of the application.
lib/home_page.dart: Home page implementation.

Appwrite Structure
Collection: products
Document: { id }
Fields: name, description, image

Troubleshooting
If you encounter any issues, please refer to the official Flutter documentation here or the Appwrite setup guide here.

License
This project is licensed under the MIT License.

This README file provides clear instructions for setting up and running your Flutter applica
