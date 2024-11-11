# Keylogger Project

This is a simple keylogger built using Python with the Tkinter library for the graphical user interface (GUI) and the `pynput` library for capturing keyboard events. It captures and logs keys pressed and released by the user and saves the data in both a text file (`key_log.txt`) and a JSON file (`key_log.json`).

## Features
- Starts and stops the keylogger using a GUI.
- Logs all key presses and releases.
- Saves logged data in both a plain text file (`key_log.txt`) and a JSON file (`key_log.json`).
- Provides real-time feedback on the keylogger's status.

## Prerequisites

To run the keylogger, you need the following Python libraries:

- `tkinter`: For GUI development.
- `pynput`: For monitoring keyboard events.
- `json`: For saving data in a structured format.

To install the required dependencies, you can run:

```bash
pip install pynput
```

`tkinter` comes pre-installed with Python, so no additional installation is required.

## How to Use

1. Clone or download the repository to your local machine.
2. Install the required libraries using the command above.
3. Run the Python script using the command:

   ```bash
   python keylogger.py
   ```

4. The GUI will open with a "Start" button. Click it to begin logging keystrokes.
5. While the keylogger is running, it will log both key presses and releases and store the data in the following files:
   - `key_log.txt`: A simple text log of the keys.
   - `key_log.json`: A JSON file with detailed logging data.

6. To stop the keylogger, click the "Stop" button.

## File Structure

```
Keylogger/
│
├── keylogger.py       # Python script for the keylogger.
├── key_log.txt        # Text file with logged keystrokes.
├── key_log.json       # JSON file with detailed logged data.
└── README.md          # Project documentation.
```

## How It Works

The program uses `pynput` to monitor the keyboard and Tkinter to create a simple GUI. The keylogger listens for key press and release events and logs them in real-time.

- When a key is pressed, it is recorded as a "Pressed" event in the `key_log.json`.
- When a key is held, it is recorded as a "Held" event.
- When the key is released, it is recorded as a "Released" event.

The logged data is saved in the text file `key_log.txt` and in the JSON file `key_log.json` for easy access and analysis.
Important Notes
Legal Disclaimer: This tool is intended for educational purposes only. Unauthorized use of keyloggers can be illegal and unethical. Always get explicit consent from users before running any keylogger software.
Security: The keylogger script should only be run on machines where you have permission. Use responsibly.
License
This project is open-source and licensed under the MIT License.

## Important Notes

- **Legal Disclaimer**: This tool is intended for educational purposes only. Unauthorized use of keyloggers can be illegal and unethical. Always get explicit consent from users before running any keylogger software.
- **Security**: The keylogger script should only be run on machines where you have permission. Use responsibly.

## License

This project is open-source and licensed under the MIT License.

---
