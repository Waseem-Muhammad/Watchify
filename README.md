# 🎬 Watchify – React Native Movie App

Watchify is a modern **React Native + Expo** movie browsing application that allows users to explore trending movies, search films, and manage favorites in a clean and responsive UI.

---

## 🚀 Features

* 🎥 Browse trending and popular movies
* 🔍 Search movies by name
* ❤️ Add/remove favorites (real-time support if connected to backend)
* 📱 Clean and responsive mobile UI
* ⚡ Fast performance with React Native + Expo
* 🔗 API integration for movie data

---

## 🛠️ Tech Stack

* React Native
* Expo
* TypeScript
* Tailwind CSS (NativeWind)
* Axios (API calls)
* Firebase (authentication, database, and backend services)

---

## 📁 Project Structure

```
Watchify-react-native-app/
│
├── app/                # App screens (routing)
├── components/        # Reusable UI components
├── constants/         # App constants (icons, config)
├── context/           # Global state management
├── services/          # API calls (movies, backend)
├── interfaces/        # TypeScript types
├── assets/            # Images & icons
├── .expo/             # Expo config (ignored in git)
├── App.tsx            # Entry point
└── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Waseem-Muhammad/Watchify.git
cd Watchify-react-native-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start development server

```bash
npx expo start
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```
EXPO_PUBLIC_API_KEY=your_api_key
EXPO_PUBLIC_API_URL=your_api_url
```

⚠️ Do NOT commit `.env` to GitHub.

---

## 📦 APK Download

You can download and install the latest Android APK of Watchify here:

👉 **Download APK:** ([Click here to download APK File](https://expo.dev/accounts/mwaseemgc/projects/react-native-movie-app/builds/7a26d020-f1a7-4225-a371-d077d0b60546))


> After downloading, enable "Install from unknown sources" on your Android device.

---

bash
npx expo build:android

````

or using EAS:
```bash
eas build -p android
````

---

## 🧠 Future Improvements

* Firebase Authentication (login/signup)

* Cloud sync for favorites using Firebase

* Offline mode support

* User authentication (login/signup)

* Cloud sync for favorites

* Offline mode support

* Video streaming integration

* Dark/light theme toggle

---

## 👩‍💻 Author

**Muhammad Waseem**

**Yumna Arif**

**Isha Shabab**

GitHub: [https://github.com/Waseem-Muhammad](https://github.com/Waseem-Muhammad)

GitHub: [https://github.com/Yumna-Arif](https://github.com/Yumna-Arif)

GitHub: [https://github.com/Isha-Shabab](https://github.com/Isha-Shabab)

---

## ⭐ Show Support

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📄 License

This project is for educational purposes.
