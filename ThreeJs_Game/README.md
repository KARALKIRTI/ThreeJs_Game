# Hidden Object Game

This is an interactive web-based game where players must find hidden objects within a scene before the timer runs out. The game includes features like sound toggle, immersive background images, and an engaging user interface.

---

## Features

- **Interactive Gameplay**: Use your mouse to navigate and click on hidden objects.
- **Timer Challenge**: Complete the game before the timer runs out.
- **Sound Toggle**: Enable or disable background music as per your preference.
- **Responsive Design**: Works seamlessly on desktop and mobile browsers.
- **Customizable Backgrounds**: Initial pop-up and instructions come with beautiful background images.

---

## Prerequisites

To run this project, ensure you have the following:

1. A modern web browser (e.g., Google Chrome, Mozilla Firefox, or Microsoft Edge).
2. A local web server to serve the project files (optional but recommended for best performance).

---

## Installation

Follow these steps to get the project running:

### 1. Clone the Repository

### 2. Open the Project

- Run a Local Server (Recommended)

- Use any local server tool (e.g., VS Code Live Server, Python's HTTP server) to serve the project.
- For example, run the following command in the project directory if Python is installed:

  ```bash
  python -m http.server
  ```

- Open your browser and navigate to `http://localhost:8000`.

---

## How to Play

1. Wait for the initial pop-up to display and welcome you to the game.
2. Read the instructions carefully on the second pop-up.
3. Click the **Start Game** button to begin.
4. **Controls**:
   - Use your **mouse** to move around the scene.
   - Click on objects to identify hidden items.
   - Keep an eye on the **timer** at the top left corner.
   - Use the **sound toggle button** at the top right to turn background music on/off.
5. Find all hidden objects before the timer runs out to win the game.

---

## Troubleshooting

### Common Issues:

- **Background Music Doesn't Play Automatically:**
  Modern browsers require user interaction to play audio. Click anywhere on the screen to enable audio.

- **Timer Doesn't Start:**
  Ensure that you click the **Start Game** button after reading the instructions.

- **Game Not Loading Properly:**
  - Make sure all assets (images, sounds, scripts) are in their respective folders.
  - Serve the project through a local web server if assets fail to load.

---

## Customization

- Replace `assets/initail_bg.png` to update the background images for pop-ups.
- Modify `assets/sounds/good-night-261834.mp3` to use your preferred background music.
- Edit `js/items.js` to customize hidden objects and gameplay logic.

---

## Technologies Used

- **Three.js**: Rendering the 3D scene.
- **HTML5**: Structure of the web game.
- **CSS3**: Styling and animations.
- **JavaScript**: Logic and interactivity.

---

## Author

Created by Nidhi and Pooja. Feel free to reach out for any questions or suggestions!

