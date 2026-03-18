# RATA - Playful Mouse Emulator 🐭

RATA is a fun application designed to keep your computer "active" by simulating interactions. It features a cute animated mouse that scurries around while the system stays awake, perfect for long downloads, preventing screensavers, or keeping your status active on Teams.

## Why it Works for Teams?
To ensure applications like Microsoft Teams register user presence, simple mouse nudges aren't always enough. **RATA performs a "Jiggle + Keypress" routine:**
1.  Moves the mouse cursor significantly.
2.  Presses the `Shift` key (a harmless "activity" signal for the OS).
3.  Scrolls the mouse wheel slightly.
4.  Returns the cursor to its original position.

## Fun Features
- **Animated Companion:** A cute digital mouse explores the application window.
- **Personality:** The mouse "talks" via speech bubbles.
- **Status Aware:** Look for the "Jiggle + Keypress!" bubble to know it's working.

## Installation
1. Ensure you have Python installed.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run
Double-click the **`Run RATA.bat`** file to start the application.

## Usage
1. Click **Wake Up Mouse** to start.
2. Click **Let Mouse Sleep** to stop.
3. **Important:** The app simulates a `Shift` key press. If you are typing outside the app while it runs, you might notice occasional capital letters or shift-effects. It is recommended to use this when you are away from the keyboard.
