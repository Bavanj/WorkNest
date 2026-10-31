# WorkNest – Location-Based Job Matching Platform

A Flutter-based mobile application designed to connect local job providers with workers through a location-based job discovery and application management system.

WorkNest enables job providers to publish job opportunities and manage applications, while workers can discover nearby opportunities, apply for jobs, and track application status.

The application uses Firebase for backend services and Google Maps for location-based functionality.

---

## Overview

WorkNest aims to simplify the connection between local job providers and workers through a centralized mobile platform.

The application provides two primary user roles:

- **Workers:** Discover available jobs, apply for opportunities, and track application status.
- **Job Providers:** Publish job listings, review applications, and manage candidates.

## Key Features

### Worker Module
- User registration and authentication.
- Profile creation and management.
- Browse available job opportunities.
- Location-based job discovery.
- View job provider locations on Google Maps.
- Apply for available jobs.
- Track application status.

### Job Provider Module
- User registration and authentication.
- Create and publish job listings.
- Upload job-related images.
- View received applications.
- Review worker profiles.
- Accept or reject applications.
- Communicate with applicants.

### Location & Navigation
- Google Maps integration.
- Current location access using GPS.
- Distance calculation between locations.
- Route visualization using Google Directions API.
- Polyline-based route display.

---

## Technology Stack

| Category | Technologies |
|---|---|
| Mobile Development | Flutter, Dart |
| Backend Services | Firebase |
| Authentication | Firebase Authentication |
| Database | Cloud Firestore, Firebase Realtime Database |
| Cloud Storage | Firebase Storage |
| Maps Integration | Google Maps API |
| Location Services | Geolocator, Geocoding |
| State Management | GetX, Provider |
| Local Storage | Shared Preferences, Get Storage |
| API Communication | HTTP |

---

## Project Architecture

The application follows a feature-based folder structure.

```text
lib/
├── authentication/
├── login/
├── Pages/
│   ├── applications.dart
│   ├── form_page.dart
│   ├── job_status_page.dart
│   ├── jobproviderpage.dart
│   ├── map_pages.dart
│   ├── messages.dart
│   ├── workerpage.dart
│   └── ...
├── screens/
├── widgets/
└── main.dart