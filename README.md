# HiFrequency - Android Music Player  

HiFrequency is a sleek and intuitive **music player** built using **Java** and **Android Studio**, designed for a seamless listening experience. With smooth controls, real-time playback tracking, and a visually appealing interface, this app enhances how you enjoy your favorite tunes.  


## Features & Key Concepts  

✅ **Automatic Song Detection** – Fetches and displays all MP3 files from storage using **ListView** with **ArrayAdapter** for efficient management.  
✅ **Smooth Playback Controls** – Event-driven **button interactions** for seamless play, pause, next, and previous functionality.  
✅ **Real-Time Progress Tracking** – Integrated **SeekBar** for precise playback control and dynamic updates using **Threads & URI Integration**.  
✅ **Dynamic UI Updates** – Displays the currently playing song in real-time for an engaging experience.  
✅ **Custom UI & Visual Enhancements** – Styled **ImageView buttons**, **vector assets**, and **image resources** for a polished, modern look.  
✅ **Secure Permissions Handling** – Uses the **Dexter Library** for runtime storage permissions, ensuring smooth access to music files.  



## 🛠 Tech Stack  

- **Java (Android Development)**  
- **Android Studio (IDE)**  
- **MediaPlayer API (Audio Playback)**  
- **Dexter Library (Runtime Permissions)**  


## 📂 Project Structure  

```plaintext
HiFrequency/                     # Root project directory
│── app/
│   ├── src/main/
│   │   ├── java/com/example/hifrequency/
│   │   │   ├── MainActivity.java         # Displays list of songs
│   │   │   ├── PlaySong.java             # Handles media playback
│   │   │   ├── Utils.java                # Utility functions (if applicable)
│   │   │
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   │   ├── activity_main.xml     # UI for song list
│   │   │   │   ├── activity_play_song.xml  # UI for music player
│   │   │   │
│   │   │   ├── drawable/                 # App icons and UI assets
│   │   │   ├── mipmap/                   # Launcher icons
│   │   │   ├── values/
│   │   │   │   ├── strings.xml           # String resources
│   │   │   │   ├── colors.xml            # App colors
│   │   │   │   ├── styles.xml            # Theme and styles
│   │   │
│   │   ├── AndroidManifest.xml           # App permissions & configurations
│
│   ├── build.gradle                      # Project build configuration
│   ├── gradle.properties                  # Gradle settings
│
│── README.md                              # Project documentation
│── .gitignore                              # Git ignore file
│── LICENSE (if applicable)                 # License file

```
## How to Run  
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/yourusername/hifrequency.git
   cd hifrequency
2. **Open in Android Studio**
3. **Run the App on a physical device/emulator with storage permissions enabled.**

📜 Permissions Used
- READ_MEDIA_AUDIO (Android 13+)
- READ_EXTERNAL_STORAGE (Android 12 and below)

📢 Contributions are welcome! Feel free to fork and enhance this project!!
