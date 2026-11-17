# Harsh-Winter-KCD2
Harsh winter mod for KCD2.
Harsh Winter - Total Winter Conversion for KCD2
A permanent, ultra-realistic 15th-century winter overhaul for Kingdom Come: Deliverance II.

📖 About the Project
Harsh Winter completely transforms the environment, survival mechanics, and atmosphere of KCD2 into a permanent, freezing Bohemian winter. No other seasons exist.

Originally hosted on Nexus Mods, this project was removed due to the platform's strict rules against custom .bat builders and direct game file modifications. GitHub is now the official home for the open-source development and distribution of Harsh Winter.

Instead of redistributing copyrighted game assets, Harsh Winter includes a highly advanced custom C#/PowerShell Builder. When run on the player's PC, it dynamically reads the vanilla game files, repaints over 600+ textures pixel-by-pixel, fixes LODs, and generates a completely frozen world.

✨ Core Features
Advanced Weather & Atmosphere: Fully deterministic, 360-degree volumetric fog that pools in valleys and reacts to time, terrain, and temperature. Massive, dense snowfall using detailed 6-armed snowflake textures. No rain, only winter weather.

Ultra-Realistic Environment: Thick snow on roofs, frosted trees (no green leaves), icy ruts on roads, and repainted distant landscapes. Smooth, physics-based snow particles that flutter and sway naturally.

Survival & Immersion: Realistic temperature drops (coldest at dawn), hypothermia stages, wind chill, and layered clothing. NPCs react to the cold with breath fog, shivering, and winter dialogue.

Advanced Tracking & Blood Trails: Henry and NPCs leave realistic footprints and bloody tracks. Hold 'E' to inspect tracks, highlight the trail, and hear Henry speak custom voice lines based on what he finds.

Audio Overhaul: All summer sounds (crickets, bees, frogs) are removed. Added realistic wind on plains, the "Winter Silence" (snow muffles sound), and wood creaking that only triggers near trees or wooden structures.

Winterized UI & Assets: Custom winter maps, loading screens, Town Banners, and Time Wheel with ice and snow. Fixed missing UI icons and localization for camping gear.

100% Crash-Free Optimization: Highly optimized Lua scripts with strict memory pooling (to prevent memory leaks from footprint generation) and optimized LOD generation.

🛠️ Installation Instructions
⚠️ IMPORTANT: Do not download and play this mod like a standard Nexus mod. It requires a one-time texture generation.

Download the latest release from the "Releases" tab or the repository files.

Extract the harsh_winter folder into your KingdomComeDeliverance2\Mods\ directory.

Close the game.

Navigate to Mods\harsh_winter\ and double-click BUILD EVERYTHING.bat.

Wait. The script will automatically run 4 steps (Repainting World Textures, Fixing LODs, Extras, Voice Installation). This process takes 45–60 minutes depending on your PC.

Once the script says "ALL 4 STEPS DONE - Harsh Winter is ready to play", launch the game and enjoy.

Note: If the game updates or you verify game files via Steam, you must run BUILD EVERYTHING.bat again.

💻 Open Source & Technical Stack
This project pushes the limits of the CryEngine. The open-source repository includes:

C#/PowerShell Builder Framework: For dynamic texture repainting and LOD generation.

Lua Scripting: For climate management, survival mechanics, AI tracking, and custom UI.

Memory Management Systems: Scripts designed to strictly limit particle and decal memory usage to maintain 60 FPS without crashes.

🤝 Support & Community
If you encounter any issues, crashes, or visual bugs, please open an "Issue" in this repository.

Include your kcd.log file from Saved Games\KingdomComeDeliverance2\ if you experience crashes.

Include a screenshot if you find a visual glitch.

Disclaimer: This is a free, open-source fan project. It is not affiliated with or endorsed by Warhorse Studios or Deep Silver. You must own a legitimate copy of Kingdom Come: Deliverance II to use this mod.
