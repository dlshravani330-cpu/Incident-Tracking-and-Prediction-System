██████╗ ██╗███╗   ██╗ ██████╗██╗███████╗███╗   ██╗████████╗
██╔══██╗██║████╗  ██║██╔════╝██║██╔════╝████╗  ██║╚══██╔══╝
██████╔╝██║██╔██╗ ██║██║     ██║█████╗  ██╔██╗ ██║   ██║   
██╔══██╗██║██║╚██╗██║██║     ██║██╔══╝  ██║╚██╗██║   ██║   
██████╔╝██║██║ ╚████║╚██████╗██║███████╗██║ ╚████║   ██║   
╚═════╝ ╚═╝╚═╝  ╚═══╝ ╚═════╝╚═╝╚══════╝╚═╝  ╚═══╝   ╚═╝   
     Incident Tracking & Prediction System
🚨 Incident Tracking & Prediction System

An AI-powered smart system that helps users track incidents, store reports, visualize them on maps, and predict potential incident zones using machine learning.
Built using Flutter + Firebase + Google Maps + Geolocation.
# Incident-Tracking-and-Prediction-System
An Incident Tracking &amp; Prediction System where users report incidents with location, category, and details. Reports appear on a map with markers and heatmaps. The system sets priority, checks sentiment, tracks patterns, detects duplicates, predicts hotspots, and shows insights on a simple dashboard.


🚨 Overview<br>
The Incident Tracking & Prediction System is a smart Flutter application that allows users to track incidents, view them on maps, report issues, store everything in Firebase, and predict future hotspots.<br><br>

✨ Features<br>
📍 Incident Reporting<br>
    Add incident details<br>
    Auto GPS location capture<br>
    Upload to Firebase Firestore<br><br>

🗺️ Interactive Maps<br>
   Google Maps markers in real time<br>
   Color-coded severity<br>
   Optional clustering<br><br>

🤖 Prediction & Insights<br>
   Analyze stored incident data<br>
   Identify danger hotspots<br>
   Highlight frequently reported areas<br><br>

🔐 Secure & Cloud-Based<br>
   Firebase Authentication<br>
   Firestore security rules<br>
   Real-time sync<br><br>

🧰 Tech Stack<br>
Category   	Technology
Framework 	Flutter
Backend	     Firebase Firestore
Auth	          Firebase Authentication
Maps	          Google Maps Flutter
Location   	Geolocator
AI	          Python API / ML Model

📦 Dependencies<br>
dependencies:
  flutter:
    sdk: flutter

  google_maps_flutter: ^2.5.0
  geolocator: ^10.0.0

  firebase_core: ^3.0.0
  cloud_firestore: ^5.0.0


Run:<br>
flutter pub get

🔥 Firebase Setup<br>
1️⃣ Create Firebase Project<br>

https://console.firebase.google.com/
<br><br>

2️⃣ Enable Services<br>
 Firestore<br>
 Authentication<br>
 Cloud Messaging (optional)<br><br>

3️⃣ Add Flutter App<br>
Download:<br>
google-services.json → android/app/<br>
GoogleService-Info.plist → ios/Runner/<br><br>

4️⃣ Update Build Files<br>
android/build.gradle<br>
classpath 'com.google.gms:google-services:4.4.0'

android/app/build.gradle<br>
apply plugin: 'com.google.gms.google-services'

🗺️ Google Maps Setup<br>
1️⃣ Enable APIs<br>
Maps SDK for Android<br>
Maps SDK for iOS<br>
Geolocation API<br><br>

2️⃣ Add API key<br>
android/app/src/main/AndroidManifest.xml:<br>
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY"/>
<br>

▶️ Run the App<br>
flutter run
Build APK:<br>
flutter build apk

📂 Recommended Folder Structure<br>
lib/
 ├─ main.dart
 ├─ screens/
 │   ├─ home_screen.dart
 │   ├─ map_screen.dart
 │   ├─ report_screen.dart
 ├─ models/
 │   ├─ incident_model.dart
 ├─ services/
 │   ├─ firebase_service.dart
 │   ├─ location_service.dart
 ├─ widgets/
 └─ utils/
<br>

🧠 Future Enhancements<br>

FCM notifications<br>
Heatmaps for hotspots<br>
Advanced ML model<br>
Admin web dashboard<br>
Offline mode<br><br>

🤝 Contributing<br>
Feel free to submit improvements, add AI logic, or enhance UI!<br><br>


📜 License<br>
MIT License<br><br>
