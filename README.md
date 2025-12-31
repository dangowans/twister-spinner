# <img src="./favicons/favicon-32x32.png" alt="Twister Spinner Icon" width="32" height="32"> Twister Spinner

An automatic Twister spinner that randomly selects body parts and colors for the classic Twister game.

## Features

- 🎲 Random selection of body parts (Left Foot, Right Foot, Left Hand, Right Hand)
- 🎨 Random selection of colors (Blue, Red, Green, Yellow)
- 🔊 Text-to-speech announcements with dual audio modes:
  - **Speech Synthesis**: Browser-based text-to-speech (default)
  - **Prerecorded Audio**: High-quality prerecorded audio files for offline use
- ⏱️ Configurable timer between spins (3-30 seconds)
- ⚙️ Settings panel with customizable options
- ▶️ Start/Stop controls
- 💤 Screen wake lock support to prevent device sleep during games

## How to Use

1. Open `index.html` in a web browser
2. Click the **Settings** ⚙️ button to configure options:
   - **Time Between Calls**: Adjust the interval between spins (3-30 seconds)
   - **Voice Announcements**: Toggle audio announcements on/off
   - **Audio Mode**: Choose between Speech Synthesis or Prerecorded Audio
3. Click the **Start** button to begin the game
4. The spinner will announce a random combination at the configured interval
5. Click the **Stop** button to pause the game

## Running Locally

Simply open the `index.html` file in any modern web browser. No additional dependencies or setup required.

Alternatively, you can serve it with a simple HTTP server:

```bash
python3 -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser. 
