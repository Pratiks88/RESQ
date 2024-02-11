# RESQ: Smart Driving Safety Assistant

## Overview

RESQ is an Android application designed to enhance driving safety by providing real-time monitoring and assistance to drivers in emergency situations. The app includes features such as user authentication, emergency contact registration, driving mode activation, and accident detection using accelerometer sensors. In case of an accident, the app sends an alert message to the user's designated emergency contacts, containing live location details for immediate assistance.

## Key Features

- **User Authentication:** Users can register and log in to the RESQ app using their email and password, ensuring secure access to the application's features.

- **Emergency Contact Registration:** Users are required to register two emergency contacts who will be notified in case of an accident or emergency situation while driving.

- **Driving Mode Activation:** RESQ includes a driving mode feature that users can activate while driving to enable real-time monitoring of their driving behavior and safety.

- **Accident Detection:** The app continuously monitors the user's activity using accelerometer sensors. In the event of a sudden impact or change in movement indicative of an accident, RESQ detects the accident and initiates emergency protocols.

- **Emergency Alert System:** Upon detecting an accident, RESQ sends an alert message to the user's registered emergency contacts. The message contains the user's live location details obtained from Google Maps, enabling emergency responders to reach the user's location quickly.

## Technology Stack

- **Frontend:** Android SDK, Kotlin
- **Backend:** Firebase Authentication, Firebase Realtime Database
- **Sensor Data Processing:** Accelerometer sensors
- **Location Services:** Google Maps API

## Target Audience

- Commuters
- Travelers
- Fleet operators
- Families concerned about the safety of their loved ones while driving

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Pratiks88/RESQ.git

2. Open the project in Android Studio.

3. Build and run the application on an Android device or emulator.

## Future Enhancements

- **Integration with Wearable Devices:** Explore compatibility with wearable devices to provide hands-free access to RESQ's features and enhance user convenience.

- **Advanced Accident Detection Algorithms:** Continuously improve accident detection algorithms using machine learning techniques to enhance accuracy and reduce false positives.

- **Collaboration with Emergency Services:** Forge partnerships with local emergency services to streamline emergency response procedures and ensure seamless coordination during critical situations.

## Contributions

Contributions to RESQ are welcome! If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.

