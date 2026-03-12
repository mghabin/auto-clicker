# Auto Clicker

A simple Python auto-clicker that automatically clicks the mouse at a set interval.

## Features

- Clicks the mouse every 5 seconds
- Easy to stop by moving the mouse to the top-left corner of the screen (PyAutoGUI failsafe)

## Requirements

- Python 3.x
- [pyautogui](https://pyautogui.readthedocs.io/)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mghabin/auto-clicker.git
   cd auto-clicker
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the script with Python:

```bash
python clicker.py
```

The auto-clicker will start clicking at the current mouse position every 5 seconds.

**To stop:** Move your mouse to the top-left corner of the screen. PyAutoGUI's built-in failsafe will raise an exception and exit the program.

## Building a Standalone Executable

You can package the script into a standalone executable using [PyInstaller](https://pyinstaller.org/):

```bash
pyinstaller --onefile clicker.py
```

The executable will be placed in the `dist/` folder.

## License

This project is open source. Feel free to use and modify it.
