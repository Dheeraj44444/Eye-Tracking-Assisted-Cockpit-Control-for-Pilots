# Eye-Tracking Assisted Cockpit Control for Pilots

This project enables hands-free cockpit control using eye-tracking and blink detection. Pilots can move the cursor and select icons by tracking eye movements and blinking, improving efficiency and safety during flight.

## Features
- **Eye Gaze Tracking**: Control the cursor with eye movements.
- **Blink Detection**: Select icons by blinking.
- **Real-Time Control**: Provides immediate feedback based on eye movements and blinks.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/eye-tracking-cockpit-control.git
   cd eye-tracking-cockpit-control
   ```

2. Create and activate a virtual environment:
   - **Windows**:
     ```bash
     python -m venv venv
     .\venv\Scripts\activate
     ```
  
3. Install dependencies:
   ```bash
   pip install opencv-python mediapipe pyautogui
   ```

## Usage

1. Ensure your camera is connected.
2. Run the script:
   ```bash
   python main.py
   ```

## Dependencies
- `opencv-python`
- `mediapipe`
- `pyautogui`

---
