# Music Player App - Project Documentation

## Overview
The Music Player App is a simple, user-friendly, and feature-rich music player built using Kotlin. It allows users to play, pause, skip tracks, and manage their music library with ease. Whether you're at home, on the go, or at the gym, this app ensures you have a seamless music experience.

## Features
- **Play Music**: Listen to your favorite tracks in high quality.
- **Track Navigation**: Skip, pause, and play any song effortlessly.
- **Playlist Support**: Create and manage custom playlists.
- **Shuffle & Repeat**: Play songs randomly or repeat tracks for continuous play.
- **Equalizer Settings**: Adjust audio output with built-in equalizer for a personalized sound experience.
- **Background Play**: Keep listening to your music while using other apps.
- **Music Search**: Easily find songs, albums, or artists within your library.
- **Notifications**: Control playback from notifications with play/pause and skip buttons.
- **Beautiful UI**: Modern, clean, and easy-to-use interface for a smooth user experience.

## Core Components
- **MainActivity.kt**: Handles the main screen with song list, playback controls, and playlist management.
- **PlayerService.kt**: Manages background music play and control.
- **MusicDatabase.kt**: Stores and manages the music library (songs, albums, playlists).
- **MusicPlayerViewModel.kt**: Manages the data and states of the music player.
- **PlayerControlsFragment.kt**: Displays the music control UI (play/pause, skip, shuffle, etc.).
- **PlaylistFragment.kt**: Allows users to manage and view their playlists.

## Layouts
- **activity_main.xml**: Main layout containing the song list, current track display, and playback controls.
- **fragment_player_controls.xml**: Controls for playing, pausing, skipping, and repeating music.
- **fragment_playlist.xml**: Layout to manage playlists and view songs.
- **notification_player.xml**: Custom layout for the playback notification.

## Resources
- **Icons**: Various icons for play, pause, skip, shuffle, and repeat actions.
- **Colors**: Custom theme colors for the app's UI.
- **Strings**: All text used within the app, including song names, button labels, and error messages.

## Technologies Used
- Kotlin
- Android SDK
- RecyclerView (for song lists)
- MediaPlayer API (for audio playback)
- Room Database (for saving playlists)
- Glide (for album art loading)

## Installation
1. Clone or download the project.
2. Open the project in Android Studio.
3. Build and run the app on your Android device or emulator.

## License
 Absolutely free to use, no license required to modify it. 

## Contributing
Feel free to fork this project, submit issues, and send pull requests. If you have any feature requests or bug reports, don't hesitate to open an issue.
