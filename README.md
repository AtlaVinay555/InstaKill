# 🛑 InstaKill

> A ruthless dopamine guillotine. Set a timer, use the app, and when time is up—it dies.

FocusBarrier does not believe in gentle nudges, passwords, or "Are you sure you want to close this?" prompts. It tracks your active screen time on designated distracting applications. Once your daily allowance is hit, it forcefully terminates the process tree. 

## ✨ Features
* **Brutalist Execution:** No complex settings menus. Just a target process name and a strict timer.
* **Process Annihilation:** Uses deep OS-level kill commands to shut down target applications instantly and prevent immediate reopening.
* **Minimalist Alerts:** Delivers a single, clean Windows toast notification: *"Time's up. Get back to work."*

## 🛠️ Tech Stack
* **Core Logic:** Python
* **Process Management:** `psutil` (for monitoring active window titles and process trees)
* **UI/Alerts:** Command Line Interface (CLI) / `win10toast`
