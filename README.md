🍅 Team Tomato Defacement Page

A lightweight, single-page web template featuring a dynamic Matrix-style rain effect, custom typography, and integrated audio. Designed for cybersecurity enthusiasts, CTF participants, and "hacker-chic" web design.
🚀 Features

    Matrix Rain Canvas: A custom JavaScript implementation of the classic digital rain effect.

    Responsive Typography: Uses the Passion One Google Font for a bold, impactful look.

    Thematic Styling: Neon green glow effects (text-shadow and box-shadow) against a dark background.

    Auto-Play Audio: Includes an integrated audio player set to play team anthems.

    Lightweight: Single-file HTML/CSS/JS with minimal external dependencies.

📂 Project Structure
File	Description
index.html	The main entry point containing HTML, CSS, and JS logic.
black_Tomato.jpg	The team logo image (Required).
anthem.mp3	The background music file (Required).
🛠️ Customization

To make this page your own, look for the following sections in index.html:
1. Update the Roster

Edit the text inside the #members div to reflect your team:
HTML

<div id="members">
    🥷 YOUR_NAME | 🥷 MEMBER_2 | 🥷 MEMBER_3
</div>

2. Change the Matrix Speed

In the <script> tag, adjust the setInterval value. Lower numbers make the rain fall faster:
JavaScript

setInterval(draw, 35); // 35ms per frame

3. Audio Policies

    Note: Modern browsers (Chrome, Firefox, Safari) often block audio from playing automatically. For the best results, users may need to click anywhere on the page to trigger the sound.

📝 Usage

    Clone this repository or copy the code into a file named index.html.

    Add Assets: Place your logo (black_Tomato.jpg) and music (anthem.mp3) in the same folder.

    Launch: Open index.html in any modern web browser.

⚠️ Disclaimer

This project is intended for educational purposes, CTF competitions, and artistic expression. Please use responsibly and only on systems you own or have explicit permission to modify.
