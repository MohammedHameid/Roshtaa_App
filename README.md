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
 Roshtaa_App/
 │── android/ # Android native files
 │── assets/ # Images, logos, banners
 │── lib/
 │ ├── Screens/ # Login, Home, Admin, Medicine
 │ ├── Widgets/ # Reusable UI widgets
 │ ├── constants/ # Global constants & helpers
 │── README.md # Project documentation


---

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/MohammedHameid/Roshtaa_App.git
cd Roshtaa_App

2. Install dependencies
flutter pub get

3. Run the app
flutter run


Make sure you have a connected device or emulator running.

📱 Screenshots

👉 (Add app screenshots here once available)

🔗 Related Repositories

🧠 FLask_API (NLP Backend)

👤 Author

Mohamed Hamed
📍 Data Scientist – Giza, Egypt
🔗 LinkedIn
 | GitHub


Do you want me to also add a **“How it Works”** section (showing the flow: user scans prescription → app → Flask API → 
