# \# 👻 Haunted Tombstone — Odd-One-Out Sprint (Unity 2D)

# 

# \*\*Haunted Tombstone\*\* is a fast-paced, replayable 2D Unity game where the player must quickly identify the \*odd tombstone\* in a cursed 3×3 graveyard grid by clicking the stone in front of it. The game focuses on \*\*reaction time\*\*, \*\*adaptive difficulty\*\*, and \*\*continuous gameplay flow\*\*.

# 

# ---

# 

# \## 🎮 How to Play

# 

# \* Each round shows a \*\*3×3 grid of tombstones\*\*

# \* \*\*Exactly one tombstone is different\*\* (the "odd one out")

# \* Click the \*\*stone in front of the odd tombstone\*\* as fast as possible

# \* The next round begins \*\*instantly\*\*

# \* The game continues endlessly until you press \*\*Stop\*\*

# 

# \### Controls

# 

# \* \*\*Mouse Click on Stones\*\* → Select the stone in front of a tombstone

# \* \*\*Esc / Stop Button\*\* → Pause \& view performance

# \* \*\*Retry\*\* → Restart the haunted sprint

# 

# ---

# 

# \## 🪦 Gameplay Rules Implemented

# 

# Each round randomly selects \*\*one rule type\*\*:

# 

# 1\. \*\*Rotation Rule\*\*

# &nbsp;  \* One tombstone is rotated differently, breaking the pattern

# 

# 2\. \*\*Movement Rule\*\*

# &nbsp;  \* One tombstone shifts position while the others remain still

# 

# \*\*Visual feedback:\*\*

# \* The odd tombstone and its stone remain visible with \*\*glowing blue text\*\*

# \* \*\*Stones in front of non-odd tombstones fade out over time\*\*

# \* \*\*Non-odd tombstones' glow (blue text) gradually turns grey\*\*, making the odd one stand out

# 

# This creates increasing tension and urgency as the player races against time.

# 

# ---

# 

# \## ⏱️ Scoring System

# 

# \* Scoring is \*\*reaction-time based\*\*

# \* Faster selections → \*\*higher score\*\*

# \* Slower reactions → \*\*lower score\*\*

# \* Wrong selection or timeout → \*\*penalty\*\*

# 

# \*\*Displayed stats:\*\*

# \* \*\*Total Score\*\*

# \* \*\*Wrong Clicks\*\*

# \* \*\*Accuracy (%)\*\*

# 

# ---

# 

# \## 💀 Wrong Click Penalty

# 

# \* Clicking the wrong tombstone:

# &nbsp; \* Applies a score penalty

# &nbsp; \* Increases wrong click count

# \* Timeouts are treated as incorrect attempts

# 

# This keeps penalties consistent and easy to understand.

# 

# ---

# 

# \## 📈 Adaptive Difficulty

# 

# The game uses a \*\*moving average of the last 10 reaction times\*\* to dynamically adjust difficulty.

# 

# \* Faster average reaction → \*\*shorter time window\*\*

# \* Slower average reaction → \*\*longer time window\*\*

# \* Difficulty changes smoothly to avoid sudden spikes

# 

# \*\*Gameplay impact:\*\*

# \* Faster fading of stones in front of non-odd tombstones

# \* Increased pressure as the player improves

# 

# ---

# 

# \## 🔁 Replayability

# 

# \* Continuous rounds with no end screen

# \* No fixed win or loss condition

# \* Player can stop and restart at any time

# \* Reset reloads the scene and clears all state

# 

# ---

# 

# \## 🛑 Stop \& Reset

# 

# \* \*\*Stop button\*\* pauses the game and shows performance stats

# \* \*\*Retry\*\* fully resets:

# &nbsp; \* Score

# &nbsp; \* Accuracy

# &nbsp; \* Difficulty

# &nbsp; \* Timers

# &nbsp; \* Current round state

# 

# No persistent data storage is used.

# 

# ---

# 

# \## 📋 Assignment Requirements Met

# 

# ✅ 3×3 grid with odd-one-out mechanic  

# ✅ 2+ rule types (rotation, movement)  

# ✅ Time-based scoring with reaction time tracking  

# ✅ Wrong click penalty system  

# ✅ Adaptive difficulty (moving average of last 10 rounds)  

# ✅ Continuous replayability  

# ✅ Reset functionality  

# ✅ Clean UI with score/accuracy display  

# 

# ---

# 

# \## 🧪 Built With

# 

# \* \*\*Unity 2D\*\*

# \* \*\*C#\*\*

# \* Unity UI / TextMeshPro

# \* Coroutines for timing, fading, and rule effects

# 

# ---

# 

# \## 🚀 How to Run

# 

# \### Option 1: Play the Build

# 

# \* Download the complete build from:  

# 👉 \[https://github.com/Honey-Badger-407/Haunted-Tombstone](https://github.com/Honey-Badger-407/Haunted-Tombstone)

# 

# \### Option 2: Run in Unity

# 

# 1\. Clone the Unity project repository:

# &nbsp;  ```bash

# &nbsp;  git clone https://github.com/Honey-Badger-407/Brainzym\_Assignment.git

# &nbsp;  ```

# 2\. Open the project in Unity (2022.3 or later recommended)

# 3\. Load the `HauntedTombstone` scene

# 4\. Press Play

# 

# \### Repository Links

# 

# \* 📁 \*\*Unity Project Files:\*\* \[Brainzym\_Assignment](https://github.com/Honey-Badger-407/Brainzym\_Assignment)

# \* 🎮 \*\*Complete Builds:\*\* \[Haunted-Tombstone](https://github.com/Honey-Badger-407/Haunted-Tombstone)

# 

# ---

# 

# \## 🔮 5 Things I'd Improve With More Time

# 

# 1\. \*\*More rule variety\*\* - Add color-based, size-based, and symbol count rules

# 2\. \*\*Audio feedback\*\* - Ambient graveyard sounds, click feedback, tension music

# 3\. \*\*Visual polish\*\* - Particle effects on correct/wrong clicks, smoother transitions

# 4\. \*\*Tutorial overlay\*\* - First-time "How to Play" screen with visual examples

# 5\. \*\*Difficulty indicators\*\* - Visual feedback showing current difficulty level

# 

# ---

# 

# \## 👤 Author

# 

# \*\*Kartikey\*\*  

# Unity Developer Intern Assignment  

# Game: \*\*Haunted Tombstone\*\*



