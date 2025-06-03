# 🎟️ Nilah's Raffle Plugin - Splash Bash '25 Edition 




![raffler](https://github.com/user-attachments/assets/7b872e1f-e993-49e6-bbeb-5caab1c66335)

✨ A lightweight Dalamud plugin for FFXIV that allows players to run in-game raffles. This specific release has some features pruned back to make it more intuitive for the event. 

## Add to dalamud experimental, check the box and save!:

`https://raw.githubusercontent.com/nilah-xiv/Raffler-SP/main/repo.json`

![image](https://github.com/user-attachments/assets/18f1a0aa-2fa3-4e98-85fa-bedec746cfce)

### Once the above step is complete, look for the plug-in in the "all plug-ins" section of dalamud. 

---

## ✨ Current Features
➖ ~~**Bonus Tickets for Early Entries**~~
~~Configurable "BOGO" (Buy One, Get One) bonus tickets for the first players who enter.~~

➖ ~~**Chat Trigger Detection**~~ 
~~Watch for trigger words (like "raffle", "ticket", "join") in chat to automatically open the raffle UI.~~

➖ ~~**BOGO Ticket Locking**~~  
~~Bonus ticket offers lock after the first bonus is awarded to maintain fairness.~~

✅ **Toggleable Raffle System**  
Toggle ui with `/raffler`

✅ **Use a discord webhook to push ticket lists (in csv format) to a disrcord channel**  
Inside the main window, insert your webhook. This is saved locally so you dont have to input it each time it's used. 

✅ **Persistent Entry Saving**  
Raffle entries are saved locally (`raffle_entries.json`) to survive crashes and resume your session safely.

✅ **Sequential Ticket Numbers**  
Every ticket is tracked with a clean, unique number to avoid confusion.

✅ **Dynamic Ticket List Views**  
Choose between a simplified or detailed view of all current entries.

✅ **Intuitive, Lightweight UI**  
Seamless windows to configure raffles, review entries, and draw winners.

✅ **Logging and Debugging**  
Key actions and errors are cleanly logged via Dalamud's plugin log viewer (`/xllog`).

✅ **Name Prefill via Targeting**  
Autofill raffle entries using your current in-game target's name. Target the user and click the `@` button.

---


🏆 **Starting Pot Configuration**  
Set an initial prize pool (gil) for the raffle when it begins.


💬 **Session History Saving**  
Save and review past raffle sessions easily for transparency or event history.

🔢 **Metrics Display**  
Show real-time stats like **Tickets Sold** and **Gil Collected** at the bottom of the raffle window.

⚠️ **Confirmation Prompts**  
Add confirmations before clearing active raffles or deleting data.

---

## 📜 Commands

```plaintext
/raffler        - Open the main UI window
```
---
## 📸 Screenshots
![Preview](https://github.com/user-attachments/assets/be44e8d0-b49a-48ad-ab4e-59d2db1c2a54)



---



