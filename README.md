# SIH26095---SMART-REAL-TIME-MONITORING-INSPECTION-MOBILE-APP
Smart real-time Monitoring &amp; Inspection Mobile App developed for Smart India Hackathon 2026
Smart Real-Time Monitoring & Inspection Mobile App

A centralized mobile application for real-time monitoring, surprise inspections, random inspector assignment, CCTV surveillance, and digital inspection report submission for registered institutes/projects.

🚀 Features

- Admin/Officer Login
- Registered Institute Management
- Flagged Institute Monitoring
- Random Inspector Assignment
- Online Inspection Report Submission
- Location-Based Report Validation
- CCTV Surveillance Integration
- Real-Time Monitoring

🔄 How It Works

1. Admin Login – The authorized officer logs into the application.
2. Institute Monitoring – Registered, flagged, assigned, and completed inspections can be viewed.
3. Random Assignment – An inspector is randomly assigned to an institute.
4. Inspection – The inspector visits the assigned institute and performs the inspection.
5. Location Verification – The inspector's location is verified before report submission.
6. Report Submission – The report can be submitted only when the inspector is within the configured 100 km radius of the assigned institute.
7. CCTV Monitoring – Authorized officers can monitor supported institutes through CCTV integration.

🛠️ Tech Stack

- Frontend: Flutter
- Programming Language: Dart
- Backend & Database: Firebase
- Location: GPS / Location Services
- Monitoring: CCTV Integration

📍 Location Validation

The system compares the inspector's current location with the assigned institute's location.

Inspector Location
        ↓
Distance Verification
        ↓
Within 100 KM?
   ↓          ↓
 YES          NO
 ↓             ↓
Submit       Submission
Report       Blocked

This helps ensure that inspection reports are submitted from within the permitted inspection area.

🎯 Objective

To provide a centralized and transparent platform for digital inspection, real-time monitoring, random inspector allocation, location-verified reporting, and CCTV-based surveillance.

👥 SIH 2026

Developed as a solution for Smart India Hackathon 2026.

Team: OreX
