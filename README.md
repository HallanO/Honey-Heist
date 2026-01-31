# Honey-Heist
A LongForm 3D game using Lens Studio
# Honey Heist 🐝🏹

**Honey Heist**  is an infinite arcade shooter built for Snapchat using **Lens Studio**. Defend your garden from waves of thieving bees using your trusty slingshot!

## 🎮 Gameplay
- **Defend the Flowers:** Bees are trying to steal your honey! Stop them before they reach the flowers.
- **Slingshot Action:** Drag back to aim, release to shoot. 
- **Infinite Levels:** The swarm gets denser, faster, and smarter the longer you survive.
- **Daily Challenges:** A unique, seeded level generates every day. Compete with friends on the same daily configuration!

## ✨ Features
- **"Juicy" Game Feel:** Satisfying particle effects, squishy audio, and responsive physics.
- **Progressive Difficulty:**
  - **Weighted Spawning:** Introduction of new bee types (Red Speedsters, Swarmers) as you level up.
  - **Dynamic Quotas:** The game ensures a fair but increasing challenge curve.
- **Cloud Persistence:** Your high score and current level are saved automatically using Snap's Cloud Storage, so you never lose your progress.
- **Seeded Randomness:** Custom PRNG implementation ensures Daily Challenges are consistent for all players globally based on the calendar date.

## 🛠️ Built With
- **Engine:** [Lens Studio](https://ar.snap.com/lens-studio)
- **Language:** JavaScript (ES6)
- **Backend:** Snap Cloud Storage Module
- **Physics:** Custom Vector-based projectile and collision system

## 🚀 How to Run
1.  Download [Lens Studio](https://ar.snap.com/download).
2.  Clone this repository.
3.  Open the `HoneyHeist.lsproj` file (or project folder) in Lens Studio.
4.  Press the **Pair Your Device** button to push the lens to Snapchat on your phone for testing.

## 🕹️ Controls
- **Touch & Drag:** Pull back the slingshot string.
- **Release:** Fire arrow.
- **Tap Buttons:** Navigate UI (Start, Next Level, Daily Challenge).

## 📂 Project Structure
- `Assets/scripts/`
  - `GameController.js`: Main game loop, state management, and spawning logic.
  - `SlingshotController.js`: Input handling and physics for the weapon.
  - `BeeController.js`: AI behavior for enemies.
  - `TutorialController.js`: Intro sequence logic.

## 📄 License
This project is created for the Snap Lensathon.

---
*Created by OLOA HALLAN*
