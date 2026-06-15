# Utsho App

Welcome to **Utsho**, a comprehensive educational management system comprising a React (Vite) client packaged with Capacitor for mobile deployment, and a Node.js Express backend using MongoDB.

## 🚀 Features
- **Role-Based Dashboards:** Separate dashboards for Admins, Teachers, and Students.
- **Schedule Management:** Real-time access to class schedules.
- **Notices Board:** Broadcast important announcements instantly to all users.
- **Statistics & Tracking:** Comprehensive overview for admin tracking students and teachers.
- **Mobile-Ready:** Cross-platform support with Capacitor (Android).

## 📁 Project Structure

This monorepo contains the following directories:
- `/utsho-client`: The React frontend built with Vite, Tailwind CSS, and Capacitor.
- `/utsho-backend`: The Express server and REST API for authentication, data handling, and integration with MongoDB.
- `utsho-app.apk`: Generated Android Application Package.

## 🛠️ Tech Stack
- **Frontend:** React, Vite, Tailwind CSS, React Router, Lucide React
- **Mobile Packaging:** Capacitor
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT & Bcrypt

## ⚙️ Getting Started

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd utsho-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the `.env` file with your `MONGO_URI` and `PORT`.
4. Run the server:
   ```bash
   npm start
   ```

### Client Setup
1. Navigate to the client directory:
   ```bash
   cd utsho-client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Building the Android APK
1. Build the frontend:
   ```bash
   npm run build
   ```
2. Sync capacitor:
   ```bash
   npx cap sync
   ```
3. Generate APK (requires Android Studio / Gradle):
   ```bash
   cd android && ./gradlew assembleDebug
   ```

## 📜 License
This project is for educational purposes.
