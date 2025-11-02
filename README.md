# MultiHello – Activity 02

**Name:** Daniel Victorioso  
**Section:** DIT 3-1  
**Activity Title:** MultiHello  
**Repository Name:** DIT3-1-DanielVictorioso-Act02  

---

## 📱 Project Description
This project is an Android app with **two screens (activities)** demonstrating navigation and the Android activity lifecycle.

- **Screen 1:** Contains a button that navigates to Screen 2.  
- **Screen 2:** Displays the text **"Welcome to Screen 2"**.  
- Both activities have overridden lifecycle methods (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart`, `onDestroy`) that log messages to track state changes.

---

## 🧠 Reflection

**What did you observe about the app lifecycle when switching screens?**  
When switching from **Screen 1** to **Screen 2**, the lifecycle methods of Screen 1 (`onPause`, `onStop`) were called, while Screen 2’s lifecycle methods (`onCreate`, `onStart`, `onResume`) started running.  
When I pressed **Back** to return to Screen 1, Screen 2’s `onPause` and `onStop` were triggered, and then Screen 1’s `onRestart` and `onResume` executed.  
This experiment helped me clearly understand how Android handles activity transitions and manages memory efficiently in the background.

---

## 🖼️ Screenshots
You can find the screenshots here:  
`/activity2/screen1.png`  
`/activity2/screen2.png`

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone git@github.com:daniel-victorioso/DIT3-1-Dan
