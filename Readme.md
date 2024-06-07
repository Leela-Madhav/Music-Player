# Music Player README

## Introduction

Welcome to Melody, a simple yet powerful music player built using Python's Tkinter library. This application allows you to play, pause, stop, and manage your music files with ease. The interface is user-friendly and features a themed design for a modern look.

## Features

- *Play/Pause Music:* Play your favorite songs and pause them whenever needed.
- *Stop Music:* Stop the music with a simple click.
- *Rewind Music:* Rewind to the beginning of the currently playing song.
- *Mute/Unmute:* Mute and unmute the volume with a single click.
- *Volume Control:* Adjust the volume using a slider.
- *Playlist Management:* Add and remove songs from your playlist.
- *Track Details:* View the total length and current playing time of the track.

## Requirements

- Python 3.x
- Pygame
- Mutagen
- ttkthemes

## Installation

1. *Clone the repository:*

   ```sh
   git clone https://github.com/Leela-Madhav/music-player.git
   cd Music-Player
   ```

2. *Install the required libraries:*

   ```sh
   pip install pygame mutagen ttkthemes
   ```

3. *Run the application:*

   ```sh
   python music_player.py
   ```

## Usage

### Main Window

When you start Melody, the main window will appear with the following sections:

- *Status Bar:* Displays the current status of the player (e.g., playing, paused, stopped).
- *Menu Bar:* Contains options to open files and access the help menu.
- *Left Frame:* Contains the playlist where you can see and manage your added songs.
- *Right Frame:* Contains the control buttons (play, pause, stop, rewind, mute) and volume control.

### Adding Songs to Playlist

1. Click the + Add button to open a file dialog.
2. Select the music file you want to add. The file will be added to the playlist.

### Removing Songs from Playlist

1. Select the song you want to remove from the playlist.
2. Click the - Del button to remove the selected song.

### Playing Music

1. Select a song from the playlist.
2. Click the play button to start playing the selected song. The status bar will update to show the currently playing song.

### Pausing and Resuming Music

- Click the pause button to pause the music. Click again to resume.

### Stopping Music

- Click the stop button to stop the music.

### Rewinding Music

- Click the rewind button to restart the currently playing song from the beginning.

### Mute and Unmute

- Click the volume button to mute the music. Click again to unmute.

### Adjusting Volume

- Use the volume slider to adjust the music volume.

## About

Melody is developed by Leela Madhav as a simple project to demonstrate the use of Python's Tkinter library for creating a functional and visually appealing music player.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Tkinter documentation and tutorials
- Pygame and Mutagen libraries for handling music playback
- ttkthemes for the beautiful themes

## Contact

For any inquiries or suggestions, please contact me on:

- LinkedIn: [Leela Madhav](https://www.linkedin.com/in/leela-madhav)
- GitHub: [Leela Madhav](https://github.com/Leela-Madhav)

Enjoy your music with Melody!
