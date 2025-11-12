# 🏋️‍♂️ Healtho – Fitness App (Flutter)

**Healtho** is a Flutter-based **gym and fitness application** designed to help users achieve their health and fitness goals through personalized workouts, progress tracking, and reminders.  
It features a clean UI, a smooth onboarding experience, and backend connectivity powered by **Node.js**.

---

## 🚀 Features

### 🌟 Core Functionalities
- **Splash & Onboarding Flow**  
  - Engaging splash screen  
  - Multi-page onboarding with skip & next navigation  
  - Dynamic page indicators and animations  

- **User Authentication**
  - Mobile number sign-up  
  - OTP verification  
  - Name and goal selection screens  
  - Google & Facebook sign-in options  

- **Workout Management**
  - Categorized exercise screens with grid & list views  
  - Level-based exercise filtering (Beginner, Intermediate, Advanced)  
  - Detailed exercise cards with images, titles, and actions  

- **Health Tips & Articles**
  - Curated health advice and articles  
  - “Favorite” and “Share” options for engagement  

- **Profile & Settings**
  - Editable profile (name, email, phone, location)  
  - View challenges, goals, and fitness plans  
  - Notification, language, and referral settings  

- **Reminders & Notifications**
  - Customizable workout reminders  
  - Smart notification center for updates  

---

## 🧩 Project Structure

```bash
lib/
│
├── common/
│   ├── color_extensions.dart
│   ├── app_extensions.dart
│   └── widgets/
│       └── round_button.dart
│
├── screens/
│   ├── splash/
│   │   └── splash_screen.dart
│   ├── onboarding/
│   │   └── onboarding_screen.dart
│   ├── signup/
│   │   ├── signup_screen.dart
│   │   ├── otp_screen.dart
│   │   ├── name_screen.dart
│   │   └── goal_selection_screen.dart
│   ├── home/
│   │   ├── exercise_tab.dart
│   │   ├── exercise_list.dart
│   │   ├── health_tip_detail.dart
│   │   ├── reminder_screen.dart
│   │   └── notification_screen.dart
│   ├── profile/
│   │   ├── settings_screen.dart
│   │   └── profile_screen.dart
│   └── utils/
│       └── navigation.dart
│
└── main.dart
```

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | Flutter (Dart) |
| **Backend** | Node.js, Express.js, Socket.io |
| **Database** | MongoDB |
| **Design Tools** | Adobe XD, Figma |
| **Authentication** | Firebase Auth / Custom OTP Flow |
| **State Management** | Provider / GetX |

---

## 🎨 UI Design Highlights
- Custom **Popins** font family  
- Consistent **primary color palette** across screens  
- Reusable **RoundButton** widget  
- Adaptive, responsive layout for all screen sizes  

---

## 🧰 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/healtho-fitness-app.git
cd healtho-fitness-app
```

### 2️⃣ Install Dependencies
```bash
flutter pub get
```

### 3️⃣ Run the App
```bash
flutter run
```

### 4️⃣ Backend Setup (Optional)
- Clone the backend API repo  
- Install dependencies:
  ```bash
  npm install
  ```
- Run the server:
  ```bash
  npm start
  ```

---

## 🏗️ Development Tips
- Register all assets and fonts in `pubspec.yaml`  
- Use the common widgets for consistency  
- Update Flutter regularly:
  ```bash
  flutter upgrade
  ```

---

## 🏁 Roadmap

- [x] Splash and Onboarding  
- [x] Sign-Up Flow (Mobile + Social)  
- [x] Profile & Settings  
- [x] Health Tips & Articles  
- [x] Reminder & Notification Screens  
- [ ] Backend Integration  
- [ ] Real-time Tracking and Analytics  

---

## 🤝 Contributing

1. Fork the repository  
2. Create a feature branch (`feature/your-feature-name`)  
3. Commit your changes  
4. Push and open a Pull Request  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 💪 Credits

- **UI/UX Design:** Ashish Chutake  
- **Development:** Flutter & Node.js Team  
- **Tutorial Source:** Healtho Flutter Development Series  

---

> 💡 *"Train smart. Stay consistent. Healtho helps you stay on track — every day."*
