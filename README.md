# Face-Recognition-with-Real-Time-Database
# Introduction

This project implements a real-time Face Attendance system with an elegant graphical interface and a live database integration. It's designed to provide a practical, real-world solution for attendance tracking using facial recognition technology.

# Overview

The system uses computer vision techniques to recognize faces from a webcam feed, matches them against a database of known individuals, and records attendance in real-time. It features a user-friendly graphical interface and utilizes Firebase for real-time data storage and retrieval.

# Webcam

The system uses the device's webcam to capture real-time video for face detection and recognition. Ensure your device has a functioning webcam.

# Graphics

The project includes a graphical user interface (GUI) for easy interaction. It displays the webcam feed, recognized faces, and attendance status.

# Encoding Generator

The EncodeGenerator.py script processes images of known individuals and generates facial encodings used for recognition.

# Face Recognition

Face recognition is performed in real-time on the webcam feed, matching detected faces against the known encodings.

# Database Setup

The project uses Firebase Realtime Database. Set up a Firebase project and configure the database rules for secure access.

# Add Data to the Database

Use the AddDataToDatabase.py script to populate the database with initial user information.

# Upload Images to the Database

Images of known individuals are uploaded to Firebase Storage for easy management and access.

# Download User Data

The system can download user data from the Firebase database for local processing and recognition.

# Update Attendance

When a face is recognized, the attendance status is updated in real-time in the Firebase database.

# Check if Already Marked

The system checks if an individual's attendance has already been marked to prevent duplicate entries.
