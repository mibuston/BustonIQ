BUSTONIQ v0.10.0 — COMMERCIAL HERO EDITION

NEW HERO EXPERIENCE
- Replaced the basic CSS character with six premium illustrated BustonIQ heroes.
- Added commercial-quality Knight, Mage, Ninja, Space Explorer, Tech Hero and Adventurer artwork.
- Redesigned My Hero as a cinematic character stage and Hero Command Center.
- Upgraded avatar selection, child profiles, parent profiles, Adventure HUD and game HUD with matching hero artwork.
- Preserved unlocked equipment and companions as premium gear chips on the hero identity panel.
- Replaced oversized internal page branding with a compact commercial product header.
- Added a responsive mobile layout for the new character stage and controls.

PRESERVED FROM v0.9.0

COMMERCIAL POLISH
- Refined the opening screen into a clearer commercial product experience.
- Added a professional product description and browser/social metadata.
- Clarified Parent Dashboard and Start Child Adventure entry points.
- Added child-safety and local-progress disclosures on the opening screen.
- Improved typography, button depth, hover behavior and keyboard focus visibility.
- Added reduced-motion support and more readable labels and secondary text.
- Added BustonIQ logo as the browser icon.

PRESERVED FROM v0.8.0

LEARNING REVIEW
- Added a Learn From My Mistakes review at the end of every mission.
- Records each missed or timed-out question during the current mission.
- Shows the child's answer, correct answer, and a clear step-by-step solution.
- Added a perfect-mission review message when there are no mistakes.
- Added explanations for arithmetic, fractions, geometry, reasoning, word problems, algebra, and decimals.
- Prevented elementary rectangle questions from generating equal length and width; equal sides are reserved for square questions.

PRESERVED FROM v0.7.3

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
