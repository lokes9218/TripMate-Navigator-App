# TripMate Navigator App (DONE BY LOKESWARAN S)

TripMate Navigator is an Android application designed to help users plan, navigate, and manage their trips efficiently. This app leverages Google Maps, Firebase Authentication, and other modern Android technologies to provide a seamless travel experience.

---

## Features

- **User Authentication:** Secure login and registration using Firebase Authentication.
- **Trip Planning:** Create, edit, and delete trips with destinations, dates, and notes.
- **Navigation:** Integrated Google Maps for real-time navigation and location tracking.
- **Trip History:** View and manage past trips.
- **Reminders & Notifications:** Get reminders for upcoming trips.
- **User Profile:** Manage your profile and settings.

---

## Screenshots

<!-- Add screenshots of your app here -->
![Home Screen](<img width="385" height="810" alt="Screenshot 2025-09-29 225422" src="https://github.com/user-attachments/assets/b2790b92-cbec-43c9-af4a-3c13b96dfa4c" />)
![Trip Planning](<img width="402" height="821" alt="Screenshot 2025-09-29 224939" src="https://github.com/user-attachments/assets/ae8dc5bc-585a-48fc-bdd5-bf08bdaaff8c" />)


---

## Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (latest version recommended)
- Android SDK (API level 33+ recommended)
- A physical Android device or emulator
- A [Google Maps API key](https://developers.google.com/maps/documentation/android-sdk/get-api-key)
- [Firebase project](https://console.firebase.google.com/) with Authentication enabled

---

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/lokes9218/TripMate-Navigator-App.git
   cd TripMate-Navigator-App
   ```

2. **Open in Android Studio:**
   - Open Android Studio.
   - Select `Open an existing project` and choose the cloned folder.

3. **Add Google Services Configuration:**
   - Download `google-services.json` from your Firebase project.
   - Place it in `app/` directory.

4. **Add your Google Maps API key:**
   - Open `app/src/main/res/values/google_maps_api.xml`.
   - Replace `YOUR_API_KEY_HERE` with your actual API key.

5. **Sync Gradle:**
   - Android Studio should prompt you to sync Gradle. If not, go to `File > Sync Project with Gradle Files`.

6. **Run the app:**
   - Connect your device or start an emulator.
   - Click the green "Run" arrow or use `Shift+F10`.

---

## Project Structure

```
TripMate-Navigator-App/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/yourpackage/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle
├── build.gradle
├── settings.gradle
└── README.md
```

---

## Usage

1. **Register or log in** with your email and password.
2. **Create a new trip** by entering destination, dates, and notes.
3. **Navigate** to your destination using the integrated map.
4. **View trip history** and manage your trips.
5. **Edit your profile** and app settings as needed.

---

## Technologies Used

- **Kotlin / Java**
- **Android SDK**
- **Firebase Authentication**
- **Google Maps SDK**
- **Material Design Components**

---

## Contributing

Contributions are welcome!  
1. Fork the repository  
2. Create your feature branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add some feature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Contact

For any queries or support, contact [YOUR EMAIL] or open an issue on GitHub.
