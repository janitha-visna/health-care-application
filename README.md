
# Mobile Health App

 mobile application designed to help users monitor their kidney health by tracking serum creatinine levels. It supports report uploads via camera/gallery, OCR-based extraction using Tesseract.js, personalized notifications, and eGFR calculation.

---

## How to Run the Application (Local Files)

### 1. Frontend (React Native + Expo Go)

**Requirements:**
- Android phone with Expo Go app installed
- Node.js and npm installed
- Internet connection

## Install Expo Go

To run the mobile application on your Android device, install the **Expo Go** app:

- Expo Go for Android (Google Play): https://play.google.com/store/apps/details?id=host.exp.exponent

**Steps:**
1. Open a terminal and navigate to the `frontend` folder:
   cd frontend

2. Install dependencies:
   npm install

3. Start Expo:
   npx expo start

4. Scan the QR code with Expo Go on your Android device.

> note that: This app supports **Android only** and runs via **Expo Go**.

---

### 2. Backend (Node.js + Express + Tesseract.js)

**Requirements:**
- Node.js 14+ installed
- Internet connection

**Steps:**
1. Open a separate terminal and navigate to the `backend` folder:
   cd backend

2. Install dependencies:
   npm install

3. Start the server:
   node app.js

---

## Alternative: Clone from GitHub

Instead of local files, you can also clone the repositories directly from GitHub:

### Frontend:
git clone 
cd React-Native-Login-with-SQlite
npm install
npx expo start

### Backend:
git clone 
cd OCR---Creatinine-Value-Reader
npm install
node app.js

---

## Project Structure
CreatinineCare/
├── frontend/ # React Native frontend application
│ ├── app/ # Main app entry point and configuration
│ ├── components/ # Reusable UI components
│ ├── screens/ # Individual screen components (e.g., Home, Upload, Trend)
│ └── Database/ # Local SQLite database integration
├── backend/ # Node.js + Express backend server
│ ├── app.js # Main server entry file
│ ├── ocr-benchmark.js # OCR performance testing and benchmarking
│ ├── test/ # Unit and integration test files
│ └── views/ # API route handlers and OCR logic



## Notes

- Use tested report formats only for accurate OCR results.
- Internet connection is required for OCR processing.
- SQLite is used for local data storage.
- Tesseract.js is used in the backend for text extraction.

>>>>>>> fb93135 (Initial commit)
