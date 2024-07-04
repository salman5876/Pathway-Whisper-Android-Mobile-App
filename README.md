# Pathway-Whisper-Android-Mobile-App

Welcome to Pathway Whisper! This is an Android mobile application designed to help you find your ideal career path through interactive features and AI-driven insights.

## Features

1. **Career Path Questionnaire**
   - Answer questions about your interests using dropdowns.
   - Backend AI model analyzes your responses to suggest the right career path.

2. **Integrated Chatbot**
   - Get career guidance through a chatbot similar to OpenAI.
   - Chatbot is hosted on your laptop; connect via IP and URL setup.

3. **Video Streaming Page**
   - Mentors can create meetings.
   - Users can attend meetings, chat during sessions, and participate in video conferencing.
   - Utilizes backend APIs for seamless interaction.

4. **Profile Management**
   - Separate profiles for users and mentors.
   - Update your name, password, and profile picture.

5. **Authentication**
   - Login and signup pages to manage user access.

## Tools & Technologies Used

- **Frontend:** Java, XML, Android Studio
- **Backend:** Python, TensorFlow Lite, VS Code

## Getting Started

### Prerequisites

- Android Studio installed on your development machine.
- Python environment set up with TensorFlow Lite.
- Basic understanding of Java and XML for Android development.
- A laptop to host the chatbot.

## Android Project Setup Guide


1. **Clone the repository:**
   ```bash
   git clone https://github.com/salman5876/Pathway-Whisper-Android-Mobile-App
   cd pathway-whisper

## Step 1: Open Android Studio
1. Launch Android Studio on your computer.
2. Import the project by navigating to `File > Open` and selecting the project directory.

## Step 2: Backend AI Model
1. Convert your AI model to TensorFlow Lite:
   - Follow the TensorFlow Lite conversion guide [here](https://www.tensorflow.org/lite/convert).
2. Host the TensorFlow Lite model locally:
   - Ensure the server hosting the model is running and accessible.
   - Update the Android app configuration to point to the correct IP and port of the hosted model.

## Step 3: Chatbot Setup
1. Ensure the chatbot is running on your laptop:
   - Start the chatbot server on your laptop.
2. Configure the app to connect to the chatbot's IP and URL:
   - Open the Android app configuration file.
   - Set the `CHATBOT_IP` and `CHATBOT_URL` to the correct values of your laptop's IP and URL.

## Step 4: Run the Application
1. Build and run the app:
   - Connect your Android device or start an emulator.
   - Click on the `Run` button in Android Studio to build and deploy the app.

## Usage

### Register User
1. First register yourself
2. Login through your credentials

### Career Path Questionnaire
1. Open the app and navigate to the questionnaire section.
2. Select your interests from the dropdowns.
3. View career suggestions based on your responses.

### Chatbot
1. Access the chatbot for personalized career advice.
2. Ensure your laptop's IP and URL are correctly set in the app settings.

### Video Streaming
1. Join meetings hosted by mentors.
2. Participate in video conferencing and send chats during sessions.

### Profile Management
1. Update your profile details, including name, password, and picture:
   - Navigate to the profile management section.
   - Make the necessary updates and save your changes.

Feel free to reach out if you have any questions or need assistance `Salman Ahmed`, `mughalsalman616@gmail.com`.
