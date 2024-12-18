🎵 Music Player App 🎶
A simple, interactive, and user-friendly Music Player App built using Android Studio. This app allows users to play, pause, and navigate their favorite songs seamlessly with an intuitive UI.

📋 Features
1. 🎧 Play/Pause/Stop: Start, pause, or stop the music playback.
2. ⏩ Next/Previous Track: Skip to the next song or revisit the previous one.
3. 🔄 Shuffle and Repeat: Enjoy shuffled playback or loop your favorite tracks.
4. 🎨 Interactive UI: Smooth navigation and clean interface.
5. 📂 Local Storage: Scans and lists all music files stored on your device.
6. 🎵 Song Details: Displays song title, artist, and album art (if available).
   
🛠️ Tech Stack
1. Language: Kotlin
2. IDE: Android Studio
3. Android SDK: Minimum API Level 21 (Android 5.0 Lollipop)
4. Dependencies:
                MediaPlayer (Built-in Android library for audio playback)
                RecyclerView (for displaying songs)
                Glide/Picasso (for loading album art images)

🚀 Installation <br>
Follow these steps to clone and run the project on your local machine:<br>

1. Clone the Repository:<br>
git clone https://github.com/your-username/music-player-app.git<br>
2. Open in Android Studio:<br>
        Launch Android Studio.<br>
        Open the cloned project folder.<br>
3. Build the Project:<br>
        Ensure all dependencies are downloaded.<br>
        Sync the Gradle files.<br>
4. Run the App:<br>
        Connect an Android device or launch an emulator.<br>
        Click the "Run" button in Android Studio.<br>


💻 Code Overview
1. MainActivity.java/Kotlin:  Handles the navigation and song list display.
2. MediaPlayerService.java:  Background service for playing audio using MediaPlayer.
3. RecyclerViewAdapter.java:  Adapter to display songs in a list.
4. layout/:  XML files for UI design.


🔧 Dependencies <br>
Add these dependencies to your build.gradle file:
<DIV>
dependencies {<br>
    implementation 'com.squareup.picasso:picasso:2.5.2' <br>
    implementation 'androidx.recyclerview:recyclerview:1.2.1'<br>
    implementation 'com.github.bumptech.glide:glide:4.12.0'<br>
    implementation "androidx.media:media:1.4.0"<br>
    }
    
</DIV>

    
Happy Coding! 🎉
