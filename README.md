# BURGER TIME (1982) - ARCADE VIDEO GAME

> **Assignment No. 1**
>
> **Developer:** Julián Camilo Herrera Ahumada
>
> **Engine:** Unity (2D)

## 1. Game Controls

### Main Menu

| Key | Action | 
| ----- | ----- | 
| **Spacebar** / **Enter** | Start Game | 
| **Escape (Esc)** | Quit Game | 

### In-Game (Stage 1)

| Key | Action | 
| ----- | ----- | 
| **Arrow Keys** / **W, A, S, D** | Move Chef Peter Pepper (walk & climb/descend ladders) | 
| **Spacebar** | Throw Pepper (temporarily stuns nearby enemies) | 
| **Escape (Esc)** | Exit to Desktop | 

### Victory Screen / Leaderboard Registration

| Key | Action | 
| ----- | ----- | 
| **Alphanumeric Keys** | Type player initials / arcade name | 
| **Enter** | Confirm name and submit score to Top 5 Leaderboard | 

## 2. Developer Commands & Cheat Codes

To streamline evaluation and testing of all game screens, state transitions, and audio-visual cues without requiring a full manual playthrough, two secret keyboard sequences are available:

* **`WIN` (In-Game / Stage 1):**

  Typing the letters **W**, **I**, **N** sequentially at any point during active gameplay triggers an instant stage clear. This executes Peter Pepper's victory animation, stops enemy spawns, plays the victory theme, and opens the Victory Panel showing the time bonus breakdown alongside the high score submission input.

* **`DLT` (Main Menu):**

  Typing the letters **D**, **L**, **T** sequentially on the title screen completely wipes all saved leaderboard data from persistent storage (`PlayerPrefs`). The on-screen Top 5 ranking list resets and clears in real time.

## 3. Scoring System & Gameplay Mechanics

* **Burger Ingredient Drop:** Points are awarded each time Peter walks across and steps on ingredient layers (top bun, lettuce, burger patty, bottom bun) to drop them down the scaffolding.

* **Enemy Trapping & Crushing:** Bonus points are earned by dropping ingredients onto pursuing enemies (*Mr. Hot Dog*, *Mr. Pickle*, *Mr. Egg*) or having them ride an ingredient down.

* **Time Bonus:** Players are rewarded for swift level completion.

*(Configured with a target time threshold of 120 seconds awarding 50 points per remaining second).*

## 4. Credits & Legal Disclaimer

* **Original Intellectual Property:**

  *BurgerTime* is an original arcade title designed and published by **Data East Corporation (DECO) in 1982**. All original character concepts, retro audio compositions, and core rules belong to their respective copyright owners.

* **Recreation & Codebase:**

  This project is an independent remake built strictly for **educational, non-commercial academic evaluation purposes** by **Julián Herrera ("ILICHIER")**.
