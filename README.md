# Meme App

Welcome to the Meme App! This Android application allows users to browse and share hilarious memes fetched directly from an online API. Built with simplicity and user engagement in mind, this app is perfect for meme lovers everywhere.

---

## Features

- **Browse Memes**: Fetch memes from an online API and display them in a user-friendly interface.
- **Share Memes**: Share your favorite memes with friends directly from the app. (Updated Soon)
- **Seamless Integration**: Utilizes Android's native sharing capabilities for smooth user experience. (Better UI soon)

---

## Installation

### Prerequisites

- Android Studio (latest version recommended)
- Android device or emulator running API level 21 (Lollipop) or higher

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/bisheshshrestha/meme_app
   ```
2. Open the project in Android Studio.
3. Sync the Gradle files to download dependencies.
4. Run the app on an emulator or a connected device.

---

## Usage

1. Launch the app to view the latest memes.
2. Swipe to navigate through memes.
3. Tap the share button to share a meme with friends.

---

## Technologies Used

- **Programming Language**: Dart
- **API Integration**: External meme API (e.g., Reddit API)
- **Dependency Management**: Gradle

---

## Dependencies

The project uses the following dependencies:

- **HTTP**: For making HTTP requests.
  ```gradle
  http: ^1.2.2
  ```
- **Shared Preferences**: For storing small amounts of key-value data locally.
  ```gradle
  shared_preferences: ^2.3.5
  
  ```

---

## API Integration

The app fetches memes using an external API. Ensure that you have an API key if required, and update the `response` in the `lib/controller/fetchMeme.dart` file.

 API setup:
"https://meme-api.com/gimme"

---


## Contact

For any inquiries or support, feel free to reach out at [bisheshshrestha652@gmail.com].

---

