# MultiHello – Activity 02

**Name:** Gerald Mamasalanang  
**Section:** DIT 3-1  
**Activity Title:** MultiHello  
**Repository Name:** DIT3-1-GeraldMamasalanang-Act02

---

## Project Description
This project is an Android app with two screens (activities).

- **Screen 1:** Has a button that navigates to the second screen.  
- **Screen 2:** Displays the text **"Welcome to Screen 2"**.  
- Both activities have overridden lifecycle methods that log messages (onCreate, onStart, onResume, onPause, onStop, onRestart, onDestroy).


---

## Reflection

**What did you observe about the app lifecycle when switching screens?**  
When I switched from Screen 1 to Screen 2, I saw that the lifecycle methods of Screen 1 (like onPause and onStop) were called, and the lifecycle methods of Screen 2 (onCreate, onStart, onResume) started running.  
When I pressed back to go to Screen 1 again, Screen 2’s onPause and onStop were called, and Screen 1’s onRestart and onResume were triggered.  
This helped me understand how Android manages activities in the background when changing screens.

---

## Screenshots
You can find the screenshots here:  
`/activity2/screen1.png`  
`/activity2/screen2.png`

---

## How to Run
1. Clone this repository:
   ```bash
   git clone git@github.com:mamasalanang-gerald/DIT3-1-GeraldMamasalanang-Act02.git

