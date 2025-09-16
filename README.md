
---

# Bowling Events Results Manager 🎳

This repository contains the logic, automation, and UI integration for managing  **bowling event results** .

It bridges the gap between **Google Sheets** (where organizers input scores) and a **web-based results page** (where players and visitors view results).

The goal is to make the process **simple for organizers** with no technical background, while providing a **polished, real-time experience** for end users.

---

## 📌 How It Works

1. **Score Input (Non-technical users):**
   * Organizers update results directly in **Google Sheets** .
   * No coding, no setup — just entering scores like a normal spreadsheet.
2. **Backend Logic (This repository):**
   * Fetches and processes scores from Google Sheets.
   * Applies business rules: standings, totals, pairs/ternas, and tie-break logic.
   * Prepares clean, structured data for the front-end.
3. **Frontend UI:**
   * Displays results in a **user-friendly webpage** .
   * Data updates automatically whenever the sheet changes.

---

## 🛠 Tech Stack

* **Google Apps Script / Sheets API** → Access and sync scores
* **JavaScript / HTML / CSS** → Frontend UI
* **Custom Logic Layer** → Processes event rules (ranking, merging, formatting, etc.)

---

## 🚀 Setup

### Prerequisites

* A Google Sheet with results structured according to the event rules.
* Access to deploy via Google Apps Script or connect with the Sheets API.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/JuanManuelJaureguiRozo/InterclubesBolos.git
   ```
2. Configure environment variables (e.g. Sheets ID, API keys).
3. Deploy backend script (Google Apps Script or Node.js bridge depending on setup).
4. Serve the frontend (static hosting or GitHub Pages).

---

## 🧩 Repository Structure

```
/src
  /tournaments -> Logic for connecting & fetching data from Google Sheets
/public        -> Static assets for the site (CSS, images, etc.)
README.md      -> Project documentation
```

---

## 🎯 Features

* ✅ Non-technical score input (Google Sheets)
* ✅ Automatic sync to web UI
* ✅ Flexible logic: standings, pairs, trios, tie-breaks
* ✅ Lightweight, easy to maintain
* ✅ Future-proof: extendable to new event formats

---

## 👥 Audience

* **Event organizers:** Just enter results in Google Sheets.
* **Players & visitors:** View a clean webpage with live results.
* **Developers:** Extend or adapt logic for new tournament rules.

---
