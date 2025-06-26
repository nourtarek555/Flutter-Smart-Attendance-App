# Smart Attendance System Using BLE Beacons & Flutter
The Smart Attendance System uses BLE beacons and a Flutter app to automate student attendance. It integrates Firebase Authentication and Firestore to manage users, beacons, and records. Attendance is marked based on beacon proximity and class schedules using Bluetooth scanning.

## Features
- BLE beacon scanning using `flutter_blue_plus`
- Firebase Authentication (email/password)
- Cloud Firestore integration for storing student, beacon, and attendance data
- Automatic attendance marking based on distance and duration
- Attendance history view for each student

## Tools & Technologies
- Flutter & Dart
- Android Studio
- Firebase Authentication
- Firebase Cloud Firestore
- BLE Beacons
- `flutter_blue_plus` package

## Getting Started
1. Install Flutter and Android Studio
2. Clone the repository
3. Set up Firebase project and configure `google-services.json`
4. Run the app on a physical Android device with Bluetooth enabled
