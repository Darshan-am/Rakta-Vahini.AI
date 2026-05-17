# Rakta-Vahini AI 🩸

Rakta-Vahini AI is a realtime Android healthcare application developed to help patients quickly find blood donors during emergency situations. The application provides donor registration, donor search, emergency blood request management, realtime emergency feed, AI-powered healthcare assistance, and donor location services using modern Android technologies.

The project was developed using Kotlin, Jetpack Compose, Firebase Firestore, Google Gemini AI API, and MVVM architecture.

---

# Features

## 🩸 Donor Registration
Users can register as blood donors by providing:
- Name
- Blood Group
- Phone Number
- Location

## 🔍 Donor Search
Search blood donors based on:
- Blood Group
- Location
- Donor Name

## 🚨 Emergency Blood Request
Users and hospitals can send emergency blood requests with patient details and hospital information.

## 📡 Live Emergency Feed
Realtime emergency requests are synchronized using Firebase Firestore.

## 🤖 AI Assistant
Integrated Google Gemini AI Assistant for:
- Blood donation guidance
- Emergency healthcare support
- General healthcare queries

## 🌍 Multilingual Support
Supports:
- English
- Kannada
- Hindi

## 🗺 Donor Map
Google Maps SDK integration for displaying donor locations.

## 🔐 Authentication
Firebase Authentication used for secure login and registration.

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Kotlin | Android application development |
| Jetpack Compose | Modern UI framework |
| Firebase Firestore | Realtime cloud database |
| Firebase Authentication | User authentication |
| Google Gemini AI API | AI Assistant integration |
| Google Maps SDK | Donor location services |
| MVVM Architecture | Clean application architecture |
| Android Studio | IDE for development |
| OkHttp | API communication |

---

# Project Architecture

The project follows MVVM (Model-View-ViewModel) architecture.

## Layers

### View Layer
- Jetpack Compose Screens
- Navigation Components

### ViewModel Layer
- Business Logic
- State Management

### Repository Layer
- Firebase Communication
- API Calls

### Data Layer
- Firestore Database
- Local Preferences

---

# Firebase Collections

## donors
Stores:
- donorName
- bloodGroup
- location
- phoneNumber

## emergency_requests
Stores:
- patientName
- bloodGroup
- hospitalName
- phoneNumber

---

# AI Integration

The AI Assistant uses Google Gemini API for generating realtime healthcare-related responses.

Features:
- Emergency healthcare guidance
- Blood donation information
- General health assistance

---

# Installation

## Step 1
Clone the repository:

```bash
git clone https://github.com/your-repository/raktavahini-ai.git
