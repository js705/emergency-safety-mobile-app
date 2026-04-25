# Emergency / Safety Mobile App (Android)

An Android-based emergency and personal safety application designed to help users quickly request help in dangerous situations using fast SOS triggers, location sharing, and safety-focused features.

This project was developed as part of **SOFE 4640U – Mobile Application Development** at Ontario Tech University.

---

## Overview

The app focuses on minimizing response time during emergencies by providing:

- One-tap SOS alerts
- Shake-based emergency triggers
- Real-time location sharing
- Emergency contact management
- Fake call / video call deterrent
- Photo capture for evidence collection

The system integrates multiple Android components including sensors, camera, SMS, and location services to create a complete safety solution.

---

## Tech Stack

- Android Studio
- Java / Kotlin
- SQLite
- SharedPreferences
- CameraX
- Google Fused Location Provider
- SMS Manager
- Android Sensors (Accelerometer)

---

## Key Features

### 🔐 Authentication & User Management
- User signup and login using SQLite
- Session persistence using SharedPreferences
- Forgot password via phone verification
- Profile management (edit details, logout, delete account)

### 🚨 SOS Emergency System
- **Tap-to-SOS:** Sends emergency SMS with GPS location
- **Shake-to-SOS:** Uses accelerometer to trigger alerts when user cannot interact with screen
- Real-time location integration using Google Location Services

### 📍 Location Sharing
- Retrieves live GPS coordinates
- Attaches location to SOS messages for accurate emergency response

### 📞 Emergency Contacts
- Add, edit, delete contacts (CRUD)
- Direct call integration via phone dialer
- Confirmation dialog before calling

### 🎭 Fake Call / Fake Video Call
- Simulates incoming call to help users escape unsafe situations
- Fake video call includes:
  - Pre-recorded video playback
  - CameraX self-view window
  - Call timer and controls (speaker/end)

### 📷 Photo Capture
- Built using CameraX
- Capture and store images in app storage
- Useful for documenting evidence

### 🏠 Home Interface
- Clean UI with quick access to all features
- Designed for minimal interaction during emergencies
