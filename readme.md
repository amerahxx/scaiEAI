

# SCAIAI - Smart Coach AI for Esports

**SCAIAI** is a smart platform for analyzing Overwatch replay videos and providing AI-generated strategic recommendations based on gameplay performance and events. It integrates game event extraction, performance evaluation, and intelligent suggestions to help players improve and win.

---

## Features

- Extracts detailed match timeline from replay videos (kills, ultimates, switches, etc.)
- Analyzes individual player performance (damage, healing, K/D ratio)
- Uses OpenAI models with prompt engineering to generate **custom strategies**
- Implements **actuarial logic** to support decision-making through EV and risk scoring

---

## Usage

1. **Download & extract** the project to a directory  
2. **Double-click `main.exe`** to run the tool  
3. Choose the **video file** to be analyzed in `Video path`  
4. Choose the **output path** in `Save to`  
5. Input **team names**:  
   - Team on the left side in `Team A`  
   - Team on the right side in `Team B`  
6. Input **player names**:  
   - Slots 1–6 for left team  
   - Slots 7–12 for right team  
7. Input:  
   - **Start & End time**  
   - **Game type**  
   - **Analysis FPS**  
   - **Stage number** (OWL replays only)  
8. Click **Analyze** and wait for results  

---

## Video File Requirements

- Must be **full-screened without watermark** during the match  
- **Minimum resolution: 720p**  
- Only **one match per video** is recommended  
- All events will be output to the **same timeline**

---

## Event Timeline Includes

- **Elimination** (Killer, killed player, ability, assist players, critical shot)  
- **Resurrection** (Resurrector, resurrected player)  
- **Ult charged / Ult used**  
- **Ult charge percentage**  
- **Character switching**

---

## Licensing

- The original Overwatch Replay Analyzer (ORA) used is licensed under **GPL v3**  
- All binaries and source code are free to use and redistribute

---

## Related Repositories

- **Player Performance Analyzer**  
  [https://github.com/hknl5/overwatch-players-analyser/tree/main](https://github.com/hknl5/overwatch-players-analyser/tree/main)

- **Main Project / Platform Code**  
  [https://github.com/Ghadihersi/SCAIAI1](https://github.com/Ghadihersi/SCAIAI1)

---

## Authors

This project is developed by a team focused on integrating AI, data science, and esports coaching to push the limits of competitive gameplay in the MENA region.
