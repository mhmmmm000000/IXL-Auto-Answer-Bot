# Frequently Asked Questions (FAQ)

### ❓ Why does the app say "Chrome not reachable" or fail to launch?
**Answer:** Google Chrome blocks automation tools if you already have a normal Chrome window open in the background. **Close all personal Chrome windows** completely before clicking "Launch Browser" in the app.

### ❓ Windows Defender / Antivirus is blocking the `.exe`. Is it a virus?
**Answer:** No. Because this app automates web browsers and injects JavaScript, antivirus heuristics often flag it as a "Trojan" or "PUP" (Potentially Unwanted Program). This is a false positive. Click "More Info" -> "Run Anyway", or add the folder to your antivirus exclusions.

### ❓ The AI says "API Rate Limit" or "Credits Depleted".
**Answer:** Hugging Face's free tier has hourly and monthly limits. If you farm hundreds of questions rapidly, you will hit the limit. The app will safely stop the farm when this happens. Wait an hour for the free tier to reset, or use a secondary Hugging Face account.

### ❓ Mac says the app is "damaged" or from an "unidentified developer".
**Answer:** Apple blocks unsigned apps to protect users. To bypass this: Right-click `Start_Mac.command` -> Click **Open** -> Click **Open** again on the popup warning. You only have to do this once.

### ❓ How do I use the Calculator Disguise?
**Answer:** Check "Disguise Mode" in the sidebar. The app will hide all bot interfaces and show a working calculator. 
- Use `×` and `÷` for multiply/divide.
- Type `^` for exponents (e.g., `2^3` = 8).
- Use `(` and `)` for order of operations.
- Press the **BACK** button or your keyboard's **Backspace** key to return to the bot.