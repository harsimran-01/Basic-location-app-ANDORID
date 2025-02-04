# Basic Location App

## 📍 Overview
The **Basic Location App** is an Android application built using **Jetpack Compose**. It retrieves the user's current location and displays the **latitude, longitude, and address** using **Google's FusedLocationProvider** and **Geocoder** for reverse geocoding.

## 🚀 Features
- Retrieves user's **current location (latitude & longitude)**.
- Converts coordinates into a **readable address**.
- Uses **Google's FusedLocationProvider** for location updates.
- Requests **runtime permissions** for location access.
- Built using **Jetpack Compose** for a modern UI.

## 🛠️ Tech Stack
- **Kotlin**
- **Jetpack Compose**
- **FusedLocationProvider API**
- **Google Maps Geocoder**
- **Android Studio**

## 📸 Screenshots
![WhatsApp Image 2025-02-04 at 7 45 56 PM](https://github.com/user-attachments/assets/68a88dae-1778-407f-85ec-43f8e978bb2e)


📜 Permissions Used
The app requires the following permissions in AndroidManifest.xml:

<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
