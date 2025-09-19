# Dzikobora - Online Game

## What is this?
This is the "Dzikobora" game - collect truffles, avoid wild boars! The game is in Polish for Polish audience.

## Files
- `index.html` - Main game file (ready for publishing)
- `dzikobora_game.js` - Original React code (not needed for publishing)

## How to publish the game to your domain

### Option 1: Simple publishing (recommended)
1. **Copy the `index.html` file** to your domain's public folder
2. **Name it `index.html`** (this is important!)
3. **Done!** The game will be available at your domain address

### Option 2: Through cPanel (if you have it)
1. Log into your domain's cPanel
2. Open **File Manager**
3. Go to `public_html` folder (or `www`)
4. Upload the `index.html` file
5. Make sure the file is named `index.html`

### Option 3: Through FTP
1. Use an FTP client (like FileZilla)
2. Connect to your domain's server
3. Go to `public_html` or `www` folder
4. Upload the `index.html` file

## Controls
- **WASD** or **arrow keys** - movement
- **P** - pause
- **R** - restart
- **M** - mute/unmute sound

## Game objective
- Collect 8 truffles
- Survive 60 seconds
- Avoid wild boars!

## Technical requirements
- Modern browser (Chrome, Firefox, Safari, Edge)
- Internet connection (to load React)
- WebAudio support (all modern browsers have this)

## Troubleshooting
- If the game doesn't work, check if you have internet connection
- Make sure the file is named exactly `index.html`
- Check if the file is in the main domain folder (public_html or www)
