# 🦠 You Are A Dumbass (Python-based Prank Script)

"You Are A Dumbass" is a modern Python and Tkinter-based reincarnation of the legendary 2000s internet meme virus that used to flood browsers with bouncing windows. This project is **completely harmless** and serves purely as an educational experiment in GUI manipulation, event-driven programming, and social engineering for a harmless prank.

## 🚀 Project Overview

When executed, the script presents the user with an innocent "System Error" window. The moment the user clicks any button, the chaos begins: the screen is flooded with floating, uncatchable, self-replicating windows that create the terrifying illusion of a "C:\ drive wipe".

## ✨ Key Technical Features

- **Runaway Button Algorithm:** The "Cancel" button teleports to a random location inside the window the moment it detects the mouse cursor approaching. It is impossible to click!
- **Differential Drifting:** Windows float smoothly across the screen using vector math (`math.hypot`). If the mouse cursor gets too close, they triple their speed and enter a "panic mode," rapidly flashing different colors (glitch effect).
- **Self-Replication (Mitosis):** - Attempting to close a window via the `X` button spawns **3 new copies**.
  - Forcing closure with `Alt + F4` spawns **5 new copies**.
  - Even if left completely alone, each window spawns a new copy every **15 seconds**.
- **Fake Hacker Terminal:** A realistic-looking terminal inside the windows continuously scrolls fake logs, claiming that `System32` and personal user files are being deleted.
- **Topmost Domination:** All windows are locked to the topmost layer of the operating system (`attributes("-topmost", True)`), making it impossible for other applications or browsers to cover them.

## 🛠️ Installation & Execution

The project only requires Python 3.x to run. It uses built-in standard libraries, so no external dependencies are needed.
