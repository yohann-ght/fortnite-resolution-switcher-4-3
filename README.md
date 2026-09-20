# Fortnite Resolution Switcher

A small Windows utility that automatically changes your resolution to **1440×1080 (4:3)** when Fortnite starts and restores your previous resolution when Fortnite closes.

## How it works

* Detects when Fortnite starts
* Saves your current resolution
* Changes it to 1440×1080
* Restores the previous resolution when Fortnite closes

## Important

**Do not manually change your resolution while Fortnite is running.**

The program saves your resolution when Fortnite starts and restores that resolution when the game closes.

You can change your resolution normally **before launching Fortnite**. The program will automatically save your current resolution when Fortnite starts.

## Requirements

* Windows
* Python 3.x
* `psutil`
* `winotify`

Install the dependencies:

```bash
pip install psutil winotify
```

## Bonus

To close the program, open **Task Manager**, search for `fortnite_resolution.exe`, right-click it, and select **End task**.

## Status

Small personal project made with Python to learn process monitoring, Windows APIs and automation.
