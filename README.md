# my_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.
Vivid is a Flutter-based mobile application designed to simplify and streamline digital content licensing agreements between licensors and licensees. The app enables users to enter detailed contract information, upload ownership proofs, define payment terms, and automatically generate legally formatted agreements using a Flask backend.

🚀 Features
Dynamic Contract Forms – Collect detailed contract information, including:
Licensor & Licensee details
Ownership proof upload
License type selection (Exclusive, Non-Exclusive, Streaming-Only, Download & Streaming, Perpetual, Time-Limited)
Payment terms (upfront payment, revenue share)
Country Dropdown with Flags – Auto-fills the country code in phone numbers.
Document Generation – Flask backend generates legally formatted license contracts from structured form data.
Responsive UI – Optimized for mobile with a clean, user-friendly design.
Ownership Proof Upload – Supports proper file selection for proof of rights.

🛠️ Tech Stack
Frontend: Flutter, Dart
Backend: Flask (Python)
Packages Used:
intl_phone_field – International phone input with country flags & codes
http – API communication with backend

Vivid/
│── lib/
│   ├── main.dart                # Entry point of the app
│   ├── licensor_details.dart    # Licensor data entry form
│   ├── licensee_details.dart    # Licensee data entry form
│   ├── contract_preview.dart    # Generated contract preview
│── backend/
│   ├── app.py                   # Flask backend for document generation
│── assets/
│── pubspec.yaml                 # Flutter dependencies


A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
