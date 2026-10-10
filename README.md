<img width="368" height="960" alt="unnamed" src="https://github.com/user-attachments/assets/53c64c75-d91a-42bd-9b11-50c0633abeca" />

🦝 Jima-Gotchi

🎮 PLAY JIMOTHY-GOTCHI LIVE HERE! 🎮

Welcome to Jima-Gotchi, the ultimate 8-bit retro virtual pet experience where you are tasked with keeping a chaotic, trash-loving raccoon alive and slightly less greasy (but not too clean).

Inspired by the handheld LCD pets of the late 90s, this single-file web application brings all the nostalgia of taking care of a demanding digital creature right to your browser.

✨ Features

100% Single File: No external assets, no messy folders. Every pixel, sound, and line of logic is packed into a single, portable HTML file (jimagotchi.html).

Offline Progression & Persistent Saving: Close the tab? Jimothy remembers. His stats are saved locally via localStorage, and he will calculate time passed to age (and get hungry/chaotic) while you are offline!

Hilarious Interactions: Click directly on Jimothy's sprite for random feral reactions (purrs, hisses, or pickpocketing!). Keep an eye on the console for his chaotic inner monologues when he's idle.

Dynamic Theme Engine: Customize your handheld! Swap between multiple device shapes (Egg, Brick, Teardrop), shell colors (Atomic Purple, Glacier Blue, etc.), and LCD backlight palettes. Everything dynamically scales!

Retro 8-Bit Audio: Features an original sound engine utilizing the Web Audio API to synthesize beeps, scuttles, and munching sounds entirely from scratch. No MP3s required.

Midnight Raid Minigame: When Jimothy has enough energy, send him out to raid trash cans! Dodge the neighbor's dog and collect shiny bottle caps.

Evolution System: Feed him right and keep him filthy. Jimothy evolves through different stages (Kit, Burglar, Goblin) all the way up to the legendary Dumpster Emperor.

Google Chat Integration: Hook Jimothy up to a Google Chat Webhook to let him spam your team channel with his chaotic antics and evolution announcements.

Gemini AI Dumpster: Let an AI hallucinate weird, wonderful, and disgusting pieces of trash for Jimothy to eat! (Requires API Key configuration)

🎮 How to Play

The HUD (Heads Up Display)

Hunger: Keep this high! Feed him trash so he doesn't starve.

Chaos: A measure of his destructive tendencies. If it gets too high, he might break something.

Grease: Raccoons hate being clean. Roll him in lint to maintain a healthy layer of grime.

Energy: Depletes over time and during minigames. Put him to sleep to recharge.

Shiny Caps (💎): Currency earned from minigames and random antics. Needed for evolution!

The Buttons

[A] FEED: Opens the trash menu. Feed him soggy fries, batteries, or whatever else you find.

[B] RAID: Starts the "Midnight Raid" minigame (costs 20 Energy).

[C] COAX/SLEEP: Calms him down if Chaos is high, or puts him to sleep if he's tired.

📱 Play on Mobile (App Installation)

You don't need an app store to install Jimothy! He is fully compatible as a Progressive Web App (PWA) and can be installed directly to your device.

Open the Live Game Link on your phone's browser (Chrome on Android, Safari on iOS).

Tap the browser's menu:

Android: Tap the three vertical dots in the top right.

iOS: Tap the Share icon (square with an up arrow) at the bottom.

Select "Add to Home Screen".

Jimothy will now appear on your home screen and run as a full-screen, standalone application!

🛠️ Installation & Hosting (For Developers)

Because Jimothy-Gotchi is a completely self-contained file, running and modifying it is incredibly simple.

Quick Start (Local Play)

Clone this repository: git clone https://github.com/BE-AI-Research/JimaGotchi.git

Open jimothy_gotchi.html directly in any modern web browser.

Host Your Own Fork

If you fork this project and want to host your own version:

Go to your GitHub repository Settings > Pages.

Under "Build and deployment", set the source branch to main.

After a minute or two, your game will be live at https://[your-username].github.io/JimaGotchi/jimothy_gotchi.html.

💻 Tech Stack

HTML5 / DOM Manipulation: Core structure and game loop rendering.

Tailwind CSS: Handled via CDN for rapid UI styling and responsive layouts.

Vanilla JavaScript: ES6+ logic driving the game state, offline progression, and interaction.

Web Audio API: Synthesizes retro waveforms (square, sawtooth, triangle, white noise) for sound effects.

Inline SVG: All pixel art graphics (Jimothy, the alleyway, the UI) are drawn via code to keep the file size tiny.

⚠️ Care Warnings

Do NOT wash Jimothy with soap.

If you ignore him for too long, he will eat your digital cables.

The developer is not responsible for any virtual items stolen by the Dumpster Emperor.
