# LG502 Adjustable Recoil Compensation


### Table of Contents

> * [About](https://github.com/Nathan-Bransby-NMT/LG502-Adjustable-Recoil-Comp/edit/main/README.md#about)
>   * [Key Features](https://github.com/Nathan-Bransby-NMT/LG502-Adjustable-Recoil-Comp/edit/main/README.md#key-features)
> * [Installation](https://github.com/Nathan-Bransby-NMT/LG502-Adjustable-Recoil-Comp/edit/main/README.md#installation)
> * [Controls](https://github.com/Nathan-Bransby-NMT/LG502-Adjustable-Recoil-Comp/edit/main/README.md#controls)

---

## About

This repository contains a Lua script designed for the for Logitech-G502 Hero, providing the player with a fully customizable recoil compensation with keybinding functionality. 
The script allows users to automate recoil adjustment in games when the trigger is held, enhancing aiming accuracy. 

## Key Features:

* **Recoil Compensation:** Automatically adjusts mouse movement to compensate for in-game recoil while the primary mouse button is held down.
* **Customizable Delay and Recoil:** Easily adjust the delay between movements and the intensity of recoil compensation through predefined keybindings.
* **Dynamic Key Handling:** Includes functionality to bind keys like Page Up and Page Down to increase or decrease recoil and delay, with modifier support (e.g., Alt + Page Up to modify delay).
* **Num Lock State Monitoring:** The script dynamically toggles between active and inactive states based on the Num Lock key, enabling or disabling recoil compensation accordingly.
* **Simple Toggle System:** Activate or deactivate the script with a simple key press without interrupting gameplay.
  
This script is intended for advanced users looking to automate specific mouse inputs for gaming or productivity purposes, providing a seamless way to manage in-game recoil and other key events.

---

## Installation

1. Launch Logitech GHub. &nbsp; &nbsp; <img src="https://github.com/user-attachments/assets/a511de76-eea0-4ccc-9193-221aab4b1a77">

2. Open the profile selection dropdown. <br><img src="https://github.com/user-attachments/assets/bcf408e7-fb3b-46a7-b28e-1aff46f6d6c8">

3. Select the "`Manage Profiles`" button <br><img src="https://github.com/user-attachments/assets/26f8245f-62c4-47ac-8d96-cf1ef980e4ec">

4. <samp>OPTIONAL:</samp> <em>Select the game/profile you wish to apply the script for.<br> ![image](https://github.com/user-attachments/assets/eb2b45b6-20b3-4e1d-bbfd-7bb2197e76ab)</em>

5. Along-side `DETAILS` you will see the following button ![image](https://github.com/user-attachments/assets/06314d5b-e832-4fe6-99fa-5f579e3b25ba) <br>
  ... Click on that button which will take you to a scripting menu. <br> ![image](https://github.com/user-attachments/assets/332498c8-0c74-47bb-9325-7678b768e088)

6. Copy the code found in [main.lua](./main.lua) and then click on the `Edit` menu button above the script field and click `Paste` <br> ![image](https://github.com/user-attachments/assets/896c13b6-5f61-45c9-bed3-b83414266315)

7. Click on the `Script` button next to `Edit` and click Save and Run. <br> ![image](https://github.com/user-attachments/assets/8774e703-8e20-4f1d-a0bd-ec09a6334204)

8. Enjoy!!! 😁

---

## Controls

|                Keys | Operation                              |
|--------------------:|:---------------------------------------|
|           `NumLock` | Toggle recoil compensation `on`/`off`  |
|            `PageUp` | Increase recoi compensation            |
|          `PageDown` | Decrease recoil compensation           |
|   `LAlt` + `PageUp` | Increase delay interval                |
| `LAlt` + `PageDown` | Decrease delay interval                |
