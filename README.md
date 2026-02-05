# Sekiro: Shadows Die Twice Save Editor (PS4)

A save editor for *Sekiro: Shadows Die Twice* on PS4, developed with Python and PyQt6. This tool allows for precise modification of character progression, currency, and a comprehensive management system for both active inventory and storage boxes.

## 🚀 Key Features

### 👤 Shinobi Progression & Stats

Modify Sargon's core attributes and progression markers to overcome the game's toughest challenges:

* **Vitality & Posture:** Adjust Current Health, Max Health, and Guard (Posture) values.
* **Power & Experience:** Edit your Attack Power and Skill Points XP directly.
* **Wealth:** Modify your Sen (currency) and Spirit Emblems.
* **Upgrades:** View and edit the number of Vitality Upgrades acquired.

### 🎒 Advanced Inventory & Storage Management

The editor provides a dual-pane system to manage items across different game locations:

* **Active Inventory:** Modify items currently carried by the player.
* **Storage Box:** Manage items sent to the storage box, including "Storage Flags" to ensure items are correctly recognized by the game.
* **Searchable Database:** Built-in integration with CSV databases for both standard items and storage items, allowing you to find any item by name.
* **Quantity Control:** Precise control over item stacks (up to 65,535).

## 🖥 User Interface

The application features a modern, functional interface built for efficiency:

* **Form-Based Editing:** Clean layout for character stats using a form-style input system.
* **Tabbed Navigation:** Easily switch between "Stats", "Inventory", and "Storage" views.
* **Search Dialogs:** Dedicated pop-up windows for searching and adding new items from the game's extensive ID list.

## 🛠 Tech Stack

* **Language:** Python 3.x
* **GUI Framework:** PyQt6
* **Data Handling:** Binary manipulation using `struct` with support for 16-byte item slots.

## 📝 How to Use

1. **Load:** Use the "Open Save File" button to select your decrypted PS4 save data.
2. **Edit Stats:** Adjust your Sen, health, or attack power in the main tab.
3. **Manage Items:** Use the Inventory or Storage tabs to search for and add items.
4. **Save:** Click "Save Changes" to write the data back to the file.

---

*Created by ArsaModz*
