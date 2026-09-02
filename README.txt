BUSTONIQ v0.12.1 — PREMIUM ENTRANCE & PARENT COMMAND CENTER

NEW IN v0.12.1
- Replaced the flat Parent Dashboard and Child Adventure entrance buttons
  with large commercial game-style portal cards
- Added premium hero artwork, dashboard iconography, depth, lighting and motion
- Redesigned the Parent Dashboard actions as a responsive command center
- Preserved all login, profile, assessment, reporting and settings behavior

PREVIOUSLY IN v0.12.0

NEW IN v0.12.0
- Grade-specific U.S. elementary math pathways for Grades 1 through 5
- Each grade now receives an appropriate set of available math topics
- Question ranges and concepts are calibrated separately by grade
- New Place Value, Measurement & Money, and Data & Graphs practice
- In-session difficulty adapts within the child's grade based on performance
- Harder modes deepen grade-level thinking without jumping to the next grade
- New heroes begin with no equipment or companion
- Unlocking an item never equips it automatically; the child chooses Equip
- Added Solver Sword, Fraction Staff, Number Bow, Adventure Backpack,
  Rocket Pack, Star Wings, Math Glasses, Power Gloves and Hero Boots
- Equipment slots prevent overlapping items of the same category
- Existing child profiles, earned points, history and unlocked items are preserved

PREVIOUSLY IN v0.11.0
- Premium illustrated art for every Workshop upgrade and companion
- Equipped shield, cape, armor, helmet and animated aura appear on the active hero
- Selected companion appears beside the hero
- Compact visual loadout icons replace emoji placeholders
- Unlock, equip, remove and saved-progress behavior remains unchanged

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
