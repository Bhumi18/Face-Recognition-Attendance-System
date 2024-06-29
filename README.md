# 📸 Face Recognition Attendance System

## Project Overview
This Face Recognition Attendance System is a Python-based machine learning project designed to automate attendance tracking in various industries. The system uses facial recognition technology to identify individuals and record their attendance in an Excel sheet, effectively preventing fraudulent attendance entries.

## 🚀 Key Features
- Facial recognition using the Haar-cascade algorithm
- Automatic attendance recording in Excel
- New user registration with 12x12 photo format
- Training module for improved recognition accuracy
- User-friendly interface built with Tkinter

## Technology Stack
- Python
- Machine Learning
- OpenCV (for Haar-cascade implementation)
- Tkinter (for GUI)
- Excel (for attendance records)

## ⚙️ How It Works
1. The system captures an image of the user.
2. It recognizes the face using the Haar-cascade algorithm.
3. If the face matches a record in the database, attendance is automatically recorded in an Excel sheet.
4. For new users, the system takes photographs and saves them in a 12x12 format.
5. The "Train Image" feature allows the system to learn from multiple perspectives, enhancing recognition accuracy.
