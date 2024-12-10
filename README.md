# FinalTerm1_NMo87924

An Android application built using **Android Studio** for managing a diary app with features like user settings, login, diary input, date-based browsing, animations, and web navigation.

## Features

1. **Settings (First Launch)**  
   - Allows users to input their name and set a numeric password (minimum 4 digits).
   - Skipped if the app is already set up.

2. **Login**  
   - Displays the username and today's date dynamically.
   - Users can log in using their previously set password.

3. **Welcome Animation**  
   - Displays an animation using images.
   - Shows a message: `You have been using this app for XX seconds.`  
   - Automatically transitions to the diary input page after 5 seconds.

4. **Diary Input**  
   - Allows users to input and save diary entries.
   - Preloads content if an entry for the day already exists.

5. **Browser**  
   - Users can browse diary entries by selecting a date via a calendar.
   - Displays saved entries for the selected date.

6. **Web Browser**  
   - Provides a text box to browse websites.
   - Defaults to **YouTube** when no URL is entered.

7. **Settings (Again)**  
   - Allows users to update their name and password.
   - Preloads existing settings for easy updates.

---

## Technologies Used

- **Language:** Java
- **Framework:** Android SDK
- **IDE:** Android Studio
- **Storage:** SharedPreferences for user data and diary entries.

---

## How to Build and Run the App

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/finalterm1_nmo87924.git
   ```
2. **Open in Android Studio**
   - Launch Android Studio and open the project directory.

3. **Build the APK**
   - Navigate to:
     **`Build > Build Bundle(s)/APK(s) > Build APK(s)`**
   - The APK will be generated in:
     ```plaintext
     app/build/outputs/apk/debug/
     ```

4. **Run the App**
   - Install the APK on your Android device or use an emulator.

---

## File Structure

```
FinalTerm1_NMo87924/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/finalterm1_nmo87924/
│   │   │   │   ├── MainActivity.java
│   │   │   │   ├── SettingsActivity.java
│   │   │   │   ├── LoginActivity.java
│   │   │   │   ├── WelcomeAnimationActivity.java
│   │   │   │   ├── DiaryInputActivity.java
│   │   │   │   ├── BrowserActivity.java
│   │   │   │   ├── WebBrowserActivity.java
│   │   │   │   ├── SettingsAgainActivity.java
│   │   │   └── Utils.java
│   │   ├── res/
│   │   │   ├── layout/   # XML Layout files
│   │   │   ├── drawable/ # Images and animation resources
│   │   │   └── values/   # Strings, colors, and themes
├── build.gradle           # Project-level Gradle file
└── README.md              # This README file
```

---

## Usage Instructions

1. **First Launch**
   - Set your username and password.
   - Once configured, the app starts with the login page on subsequent launches.

2. **Navigating the App**
   - Use the **diary input page** to save your entries.
   - Browse diary entries by selecting a date.
   - Use the **web browser** to navigate websites or default to YouTube.

3. **Update Settings**
   - Navigate to the **Settings (Again)** page to update your username or password.

---

## Screenshots

### Login Screen
*Displays the username and today's date.*

![Login Screen](path_to_screenshot.png)

### Welcome Animation
*Plays an animation and displays app usage time.*

![Welcome Animation](path_to_screenshot.png)

### Diary Input
*Save or edit diary entries for the day.*

![Diary Input](path_to_screenshot.png)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
