
# OnePiece Card Prices – User Guide

This app helps you quickly check prices for trading cards on Cardmarket.  
Currently supported:

- One Piece
- Pokémon
- Magic: The Gathering
- Yu-Gi-Oh!
---

## Installation

1. Download the latest APK from the **Releases** section.
2. Transfer the APK to your Android device (if you didn’t download it directly).
3. Open the APK and follow the installation steps.
4. Launch the app — done! 🎴

---

## Overview – Main Features

### 1. Select Your Game

At the top or in the main menu, choose the game you want to check prices for:

- **One Piece (Camera)**
- **One Piece** 
- **Pokémon**
- **Magic: The Gathering**
- **Yu-Gi-Oh!**

Each game stores its own settings and favorites.

---

### 2. Global Search

Use the search bar to enter a card name, set code, or number, such as:

- `OP12-005`
- `Marco`
- `Charizard`
- `Baleful Strix`

The app automatically generates accurate results.

**How it works:**

---

### 3. The Icons on Top

_**-Change Viewmode**_
You can switch between three layouts for search results and favorites:

- **Large** – full card view with image, prices, and reprints.
- **Compact** – smaller list view (good for fast browsing).
- **Grid** – tile layout with pictures and short info.

Switch using the icons in the top bar.

_**-Favorites**_

You can save any card as a favorite:

- Tap the **heart icon** in the card view.
- The card will be added to the Favorites list.

Inside the Favorites tab you can:

- view saved cards (with images & prices),
- refresh individual cards,
- remove entries,
- open the card on Cardmarket,
- use all three view modes (Large, Compact, Grid).

Favorites are saved locally on your device.

---

### 4. Search Settings

The app supports advanced filtering:

- **Seller countries**
- **Minimum card condition** (NM, EX, PL, etc.)


These filters apply to:

- price pages  
- reprint pages  
- offers  
- favorites  

The app automatically attaches the correct query parameters (e.g., `sellerCountry`, `minCondition`, `language=1`) to Cardmarket URLs.

---

### 5. Reprints / Versions

Many cards have different editions or reprints.  
In every card detail view, you’ll find:

> **Show reprints** / **Hide reprints**

When expanded, the app loads and displays:

- all available reprints/versions,
- in **3-column tiles**,
- each showing:
  - **image** (fetched directly from the version’s product page),
  - **title** (set/edition),
  - **price “From: …”**,
  - **Open** button for the Cardmarket product page.

Opening a reprint automatically includes your chosen filters.

---

### 6. Camera Scan (One Piece)

For One Piece cards, you can use the **camera scanner**:

- The app uses ML Kit Text Recognition to read card codes (e.g., `OP07-021`).
- There is an **Auto-Scan mode**:
  - Scans the code in the camera preview,
  - Automatically performs a search,
  - Uses a built-in **cooldown** (~5 seconds) to avoid rate limits.

__How to use with Multi-Search?__
 - Scan Card-Code
 - Press the "+" Button and it add the Code on the second Box (it add the Code from the first box)
 - Scan next Card and repeat
 - After you scan the cards press "Multi-search"
 - Results also comming in a Pop-up
 - You see only the V1 Cards, but you can press "Open all reprints" to check another Versions too

Video:
<video src="https://github.com/Hylianer95/CardPrices/blob/main/CardPrices.mp4" controls width="600"></video>



Tips:

- Hold the card steady with good lighting.
- Tap the camera preview to refocus (if enabled).
- If detection fails, you can manually edit the recognized code.

---

### 8. Rate Limiter (Cooldown)

To avoid triggering Cardmarket’s rate limits, the app includes a **smart rate limiter**:

- Ensures a minimum delay between network requests.
- Automatically increases the delay after a 429 “Too Many Requests”.
- Shows a **cooldown chip** whenever you must wait.

---

## Privacy

- The app only fetches **public Cardmarket pages & images**.
- No login or personal Cardmarket data is used.
- Favorites and settings are stored **only on your device**.

---


Thank you for using the app — and enjoy checking your card prices! 💛
