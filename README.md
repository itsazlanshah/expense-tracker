# Flutter Expense Tracker

A cross-platform expense tracking application developed as a university Mobile App Development project using Flutter and Firebase.

**Live Demo:** Not deployed yet

## Overview

The Expense Tracker helps users manage their personal finances by recording income and expenses, viewing spending patterns, and analyzing financial activity through interactive charts.

The application uses Firebase for authentication and cloud data storage, allowing users to securely manage their financial records.

## Features

* **User Authentication:** Secure registration and login using Firebase Authentication.
* **Expense Management:** Create, view, update, and delete income and expense records.
* **Cloud Database:** Stores financial data using Cloud Firestore.
* **Analytics Dashboard:** Displays financial information through interactive charts.
* **Spending Categories:** Organizes expenses into different categories for easier analysis.
* **State Management:** Uses Provider for managing application state.
* **Responsive UI:** Designed to work across mobile and web platforms.
* **Loading Effects:** Uses shimmer effects to improve the user experience.

## Technologies Used

* **Flutter & Dart** — Application development
* **Firebase Authentication** — User authentication
* **Cloud Firestore** — Cloud database
* **Provider** — State management
* **fl_chart** — Data visualization
* **Syncfusion Flutter Charts** — Financial charts
* **Google Fonts** — Typography
* **Font Awesome** — Icons

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/itsazlanshah/expense-tracker.git
cd expense-tracker
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Configure Firebase

Configure Firebase for your platform and add the required Firebase configuration files.

For Android:

```text
android/app/google-services.json
```

For iOS:

```text
ios/Runner/GoogleService-Info.plist
```

For Web, ensure the appropriate Firebase configuration is available in the project.

### 4. Run the application

```bash
flutter run
```

## Project Team

**Azlan Shah**  
**Muhammad Nofal Zia**

This project was developed collaboratively as part of a Mobile App Development course at Bahria University.

## Purpose

The project was developed to gain practical experience in Flutter application development, Firebase integration, authentication, CRUD operations, state management, and data visualization while building a practical financial management application.
