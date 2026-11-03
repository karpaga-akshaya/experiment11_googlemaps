# experiment11_googlemaps

# Google Maps Application

## Aim
To develop an Android application using Kotlin that displays Google Maps and identifies a selected geographical location using a marker.

## Technologies Used
- Android Studio
- Kotlin
- XML
- Google Maps SDK for Android

## Software Requirements
- Android Studio
- Android Emulator or Android Mobile
- Internet Connection
- Google Maps API Key

## Project Description
This application displays Google Maps on an Android device. It uses latitude and longitude coordinates to identify a particular location and displays a marker on the map.

## Sample Location
- Location: Bangalore
- Latitude: 12.9716
- Longitude: 77.5946

## Project Structure
```text
GoogleMaps/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/example/googlemaps/
│           │   └── MainActivity.kt
│           ├── res/layout/
│           │   └── activity_main.xml
│           └── AndroidManifest.xml
└── README.md
```

## Implementation Steps
1. Create a new project in Android Studio.
2. Select Empty Views Activity.
3. Choose Kotlin as the programming language.
4. Add the Google Maps dependency.
5. Configure the Google Maps API key.
6. Add SupportMapFragment to the XML layout.
7. Initialize Google Maps in MainActivity.
8. Add a marker to the selected location.
9. Run the application.

## Working Principle
The application uses Google Maps SDK to display the map. The latitude and longitude values identify the selected geographical location. A marker is added to indicate the location.

## Expected Output
Google Maps is displayed on the screen with a marker indicating Bangalore.

## Result
Successfully developed an Android application to display Google Maps using Kotlin.
