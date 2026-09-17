# Fluetro OS

Fluetro OS is a simple customizable WebOS inspired by the Microsoft Fluent Design System and older versions of macOS.

## Screenshots

### Boot Screen

<img width="1920" height="1080" alt="Screenshot 2026-09-10 215800" src="https://github.com/user-attachments/assets/4e8725d0-dec3-4e5e-9fe7-03ca8bc61876" />

### Welcome Screen

![Welcome Screen](https://github.com/user-attachments/assets/3bcd2130-6df8-4c7c-9941-93881acfd84f)

### Light Mode

![Light Mode](https://github.com/user-attachments/assets/f415d4ff-5026-458d-a92a-f43184cd7b6a)

### Dark Mode

![Dark Mode](https://github.com/user-attachments/assets/2b7b20aa-287c-4ffa-96fb-6704e8438554)

[Run Fluetro OS](https://fluetro-os-snowy.vercel.app/)

## How to Use

Just open the **Run Fluetro OS** link above and start using it.

## Features

* Fluent-style UI inspired by Windows 11 and macOS
* macOS-style top bar with date and weather
* macOS-style app dock
* Light and dark mode
* Smooth animations
* Sign out, restart and shutdown screens
* Shutdown can close the browser tab
* Memo app for notes
* Paint app
* Calculator
* Browser
* AI Brief
* Minesweeper
* 2048
* Dino Runner
* Surf
* Minecraft Classic
* Automatic accent colors based on the wallpaper
* User preferences saved locally
* No browser permissions required by the main OS

## Privacy

The AI Brief currently uses location information for weather and location features.

If location permission is not given, it can fall back to IP-based location detection. This may be improved in a future update.

Other settings such as wallpapers, dark mode and Memo content are stored locally in the browser.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/Tan5dev/Fluetro-OS.git
cd Fluetro-OS
```

Then open `index.html` in your browser.

You can also open the project folder in VS Code or another editor to modify it.

## How It Works

Fluetro OS is made using:

* HTML
* CSS
* JavaScript
* localStorage
* Open-Meteo

User preferences, wallpaper settings and Memo content are stored using `localStorage`.

Weather data is provided by Open-Meteo.

## Credits

* [Arindam Saha](https://unsplash.com/@hyperickz) — Default foggy mountain wallpaper
* [Benjamin Voros](https://unsplash.com/@vorosbenisop) — Starry mountain wallpaper
* [Bogdan Pasca](https://unsplash.com/@bogdipasca) — House near shore wallpaper
* [Joshua Woroniecki](https://unsplash.com/@joshuaworoniecki) — Trees under stars wallpaper
* [Icons8](https://icons8.com) — Dock icons
* [Lucide](https://lucide.dev) — UI icons and symbols
* [One UI MASTER](https://www.reddit.com/user/EmergencyMelodic9443/) — AI Brief inspiration

## Planned Features

* Files app
* Music player
* More UI improvements
* More animations
* More games
* Maximize/Restore animations
* More customization
* Terminal
* Possible Python coding app
