# Custom Changes

### Auto-Buy Upgrade Priority (v3.4.4 Logic)

This modified upgrade logic prioritizes faster progression and is structured as follows:

1. **Buy Green Upgrades**  
   - Purchase all available green upgrades, **excluding the two magnet upgrades**.  
   - This preserves the behavior of the original auto-buy upgrade method.

2. **Scroll to Bottom of Equipment**  
   - Purchase the **last equipment item** using the "Max" option.

3. **Buy 50 of Each Item in the Previous Tier**  
   - Purchase **50 units** of each item in the tier immediately preceding the one just maxed.  
   - Continue this process **until you reach the red tier**, possibly purchasing multiple times per item.

4. **Return to the Upgrade Screen**  
   - One final pass is made through the upgrade screen.

This revised logic significantly speeds up the acquisition of future upgrades such as gloves, cape, claw, and others.

---

### Reason for This Change

The primary developer switched to a "Max All" equipment strategy followed by upgrades in **v3.4.5**. While this method achieves peak CpS (Cookies per Second) — due to an early-game upgrade that grants +0.01% CpS per equipment level — it is not optimal during mid-to-late game ascensions, which can last from **5 minutes to several hours**.

The goal of this custom strategy is to **minimize the time** spent reaching peak CpS during each cycle, optimizing for overall progression speed rather than raw peak performance.

---

### Future Enhancement Ideas

Add support for **equipment-level breakpoints** to better optimize performance gains:

- **Sword Level 300** → Soul Bonus  
- **Bow Attack Speed** → Levels 100, 200, 300, 400  
- **Bow Soul Bonus** → Levels 150, 250, 350, 450, 500  
- **Magnet – Helm** → Level 150  
- **Boots** → Levels 200, 250, 350  
- **Ring** → Level 350  
- **Boost (Movement Speed)** → Boots Level 200, 350

---

# How to Make It Run?

> *(Works only with the Steam Version on Windows)*

You have two options:

---

### 1) **Run with `.exe` Files** (Easy)

- Go to [GitHub Releases](https://github.com/Devil4ngle/Idle_Slayer_Script/releases)
- Download `Idle Runner_x64.exe` or `Idle Runner_x32.exe` depending on your [system type](https://support.microsoft.com/en-us/windows/32-bit-and-64-bit-windows-frequently-asked-questions-c6ca9541-8dce-4d48-0415-94a3faa2e13d).
- Run the appropriate executable.

![image](https://github.com/Devil4ngle/Idle_Slayer_Script/assets/101042789/a6224058-0f4b-435e-bca0-45730f9b3dd4)

---

### 2) **Run with Source Code** (Harder)

If you do not trust the executable files or your antivirus prevents running them:

- Download the [Source Code](https://github.com/Devil4ngle/Idle_Slayer_Script/releases) and **unzip** it.
- Download and install [AutoIt Full Installation AND AutoIt Script Editor](https://www.autoitscript.com/site/autoit/downloads/). (You need both)

![image](https://github.com/Devil4ngle/Idle_Slayer_Script/assets/101042789/df50f05b-530e-4777-bfd3-5012adf77baf)

- Right-click `Idle Runner.au3` and select **Compile with Options**.

![image](https://github.com/Devil4ngle/Idle_Slayer_Script/assets/101042789/5dc44eb5-aa9a-435f-82fb-710526cc4795)

- In the menu, click **Compile Script**.  
It will generate `.exe` files which should run without issue.

---

# Settings

### Mandatory Settings:

- The game must run in **1280x720 resolution**, **Windowed**, and at **100% display scaling**.
- The game must be in **English**.
- The game **must be in focus** — otherwise, the script will only jump.
- **Disable the custom cursor**.
- Set keybinds:
  - Jump → Up Arrow
  - Boost → Right Arrow

---

### Optional Settings:

- **Bonus Stage 2/3** will only be completed if you check "Skip Bonus Stage" in settings.
- Ascension upgrade **Protect** is required for Bonus Stage 2/3.
- **Do NOT buy the Vertical Magnet**.
- Disable **dialogue for Portal** in the settings.
- Enable **rounded bulk** in the settings.
- Enable **hide locked quest rewards** in the settings.
- Ascension upgrade **Leadership Master** is required to auto-claim minions.
- Use **Anna** or **Roy** for Ascending Heights.

---

### For Boss Fights Only:

- Use **Anna** or **Roy**.
- Use **Bat Long Bow** or a **Multishot Bow**.
- Works only after defeating the boss in story mode.

---

# Join the Idle Slayer Scripting Discord Community!

Need help or want to connect with others?  
Join the [Idle Slayer Scripting Discord Server](https://discord.gg/aEaBr77UDn)

---

**Original Repository & Creator:**  
[https://github.com/Devil4ngle/Idle_Slayer_Script](https://github.com/Devil4ngle/Idle_Slayer_Script)

**Buy the original creator a [coffee](https://www.buymeacoffee.com/devil4ngle) ☕**
