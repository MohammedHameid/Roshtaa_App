# 📱 Roشtaa Mobile App

This is the **Flutter mobile application** for my graduation project **Roشtaa**.  
The app is designed to help users **scan medical prescriptions, view drug information, and access health-related articles**.  
It integrates with the [Roشtaa Flask NLP API](https://github.com/MohammedHameid/FLask_API) to extract and analyze prescription text.

---

## 🚀 Features
- 🔐 **Authentication** → Email/Password login with Firebase.  
- 📰 **Articles Feed** → Displays health articles and news with images.  
- 💊 **Medicine Information** → View medicine details, active ingredients, and side effects.  
- 📸 **Prescription OCR** → Connects to backend API for text extraction & drug recognition.  
- 🎨 **Modern UI** → Swiper banners, custom widgets, Material + Cupertino design.  
- 👨‍⚕️ **Admin Dashboard** → Secure access for administrators.  

---

## 🛠️ Tech Stack
- **Flutter (Dart)** – frontend mobile framework  
- **Firebase** – authentication & data storage  
- **Flask NLP API** – backend prescription text analysis  
- **Tesseract OCR** – text extraction from images  

---

## 📂 Project Structure
``` Roshtaa_App/
│
├── android/ # Android-specific files
├── ios/ # iOS-specific files
├── lib/ # Main Flutter source code
│ ├── screens/ # App screens (Login, Home, OCR, Articles, etc.)
│ ├── widgets/ # Reusable UI components
│ ├── services/ # API calls & Firebase integration
│ └── main.dart # Entry point of the app
├── assets/ # Images, fonts, and other resources
├── pubspec.yaml # Dependencies & assets
└── README.md # Project documentation ```


## 🔄 How It Works
1. User logs in / signs up using **Firebase authentication**.  
2. User scans or uploads a **prescription image**.  
3. The app sends the image to the **Flask NLP API**.  
4. Backend uses **Tesseract OCR** + NLP model to extract medicine names.  
5. Extracted drug information is returned and displayed in the app.  
6. Users can also browse **health articles** and search for medicines.  

---

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/MohammedHameid/Roshtaa_App.git
cd Roshtaa_App
