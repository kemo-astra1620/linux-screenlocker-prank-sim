# 🖥 Python Hacker Screen Locker & Simulation

> ⚠️ **DISCLAIMER:** This project is developed purely for **prank, educational, and visual simulation** purposes. It is **not** a malicious software or ransomware; it does not harm your system, files, or hardware in any way. It is designed specifically for entertainment and personal portfolio use on **Linux-based systems** (such as Linux Mint, Ubuntu, and Kali Linux).

---

## 🚀 About the Project

This project is an interactive, Hollywood/Cybersecurity-themed screen locker and hacker simulation built using Python's native **Tkinter** library and **Pillow (PIL)**. It temporarily isolates desktop management to deliver matrix-style visual effects, real-time terminal logs, and a cinematic termination sequence.

---

## ✨ Features

* **Matrix & HUD Interface:** Background code streams and a dynamic laser scanner line.
* **Custom Mask Integration:** Automatically detects and renders `fsociety_mask.png` onto the interface.
* **Synchronized Progress Bar & Firewall:** As the data breach progress bar fills from `%0` to `%100`, the firewall percentage simultaneously decreases from `%100` down to `%0`.
* **Typewriter Console Logs:** Real-time streaming Kali Linux / Metasploit-style penetration testing logs.
* **Cinematic Wipe Mode:** Triggers when the timer fills, turning the screen red and executing a 20-second root directory wipe simulation.
* **"GOODBYE" Ending Sequence:** Fades the screen to black, displays a giant **GOODBYE** message in the center, and automatically closes the application safely after 5 seconds.
* **Window Isolation:** Utilizes `overrideredirect(True)` and full-screen constraints to bypass the Linux desktop environment's window manager for a stable lockdown experience.
* **Safe Exit:** Press the **`ESC`** key at any time to instantly and safely exit the simulation.

---

## 🛠️ Prerequisites

Before running the project, ensure your Linux system has the following installed:
* **Python 3.x**
* **pip** (Python package manager)
* **python3-tk** (Tkinter GUI toolkit package for Linux)

---

## 📦 Step-by-Step Installation & Execution

Follow these detailed steps in your terminal to set up and run the project successfully:

### Step 1: Install System Dependencies (Tkinter)
Some Linux distributions do not include Tkinter by default. Install it via your package manager:
```bash
sudo apt update
sudo apt install python3-tk
```

### Step 2: Clone or Download the Repository
Open your terminal, clone the repository to your local machine, and navigate directly into the project folder:
```bash
git clone [https://github.com/your-username/linux-screen-locker-sim.git](https://github.com/your-username/linux-screen-locker-sim.git)
cd linux-screen-locker-sim
```

### Step 3: Create a Virtual Environment (Recommended)
To prevent global package restriction errors on modern Linux systems, set up a local virtual environment:
```bash
python3 -m venv venv
```

### Step 4: Activate the Virtual Environment
Activate the virtual environment you just created:
```bash
source venv/bin/activate
```

### Step 5: Install Python Requirements
With your virtual environment active, install the required Pillow library using pip:
```bash
pip install -r requirements.txt
```

### Step 6: Add the Mask Image (Optional)
To display the hacker mask graphic at the top of the interface, place an image named fsociety_mask.png directly inside the project root folder. If the image is missing, the script will still run normally without it.


### Step 7: Run the Simulation
Execute the script using Python:
```bash
python3 screenlocker.py
```

⌨️ Controls

To Exit: Press the ESC key on your keyboard to immediately terminate the simulation and restore full desktop control.
