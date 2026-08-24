BUSTONIQ v0.7.3 — NAVIGATION FIX

FIXED
- Added Back to Child Profiles button on My Hero.
- Added Back to My Hero button on Adventure screen.
- Repaired Adventure Map button.
- Repaired Hero Workshop button.
- Repaired Progress Assessment button.
- Repaired My Achievements button.
- Repaired Logout navigation.
- Repaired bottom game navigation.
- Converted event setup to null-safe bindings so one missing button can no longer break the rest of the app.
- Keeps v0.7.2 Submit Answer fix.
- Keeps v0.7.1 fullscreen Adventure UI.

ROOT CAUSE
The new full-screen Adventure screen removed an older element, but the old JavaScript still tried to bind to it. That JavaScript error stopped later buttons from receiving their click handlers.

GITHUB
Upload:
1. index.html
2. bustoniq-logo.png
3. adventure-world.png
