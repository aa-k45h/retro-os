# RetroOS — Vintage Android Simulator

A phone UI simulator in the style of Android 4.0 "Holo", built as a single HTML file. No frameworks, no build step, and it works offline (only the Roboto/VT323 fonts load from Google Fonts, with fallbacks).

## Features

- **Lock screen**: drag the lock ring right to unlock, or left to jump straight to the camera roll.
- **Home screen**: live clock, app grid, dock, app drawer, and working Back / Home / Recents keys.
- **Gallery**: albums, a photo grid and a swipeable full-screen viewer (all photos are generated art).
- **Files**: browse a fake `/sdcard`; images open in Gallery, songs open in Music, text files open in a viewer.
- **Music**: chiptune tracks synthesized live with the Web Audio API, with seek, shuffle, repeat and a spinning vinyl.
- **Snake**: Game Boy–style LCD board, swipe or D-pad or arrow keys, wrap-around walls, saved high score.
- **Settings**: Wi-Fi and Bluetooth toggles (they change the status bar), wallpaper picker, About phone.

On desktop the phone sits in a device frame (the side button locks it). On a phone it goes full screen.

## Easter eggs

There are four hidden surprises. Hints: tap something seven times, press on the clock for a while, and remember old cheat codes.

## Run it

Open `index.html` in a browser. To host it on GitHub Pages, push this folder to a repo and enable Pages for the `main` branch.

Built by Nikil.
