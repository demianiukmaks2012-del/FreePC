# FreePC Booking System

> **Retro‑90s Computer Lab Booking** – A static, browser‑only web app that lets students and teachers reserve a PC in a lab, view a 2‑D classroom layout, and manage bookings via a simple admin interface.

---

## 📦 Prerequisites

- **Web browser** – Chrome, Edge, Firefox, or any modern browser.
- **Local files** – The HTML file (`freepc_booking_system.html` or `index.html` inside the `FreePC` folder) and the avatar image `baldi.png` must reside in the same directory.
- **Optional (recommended) – local HTTP server** for a smoother experience (avoids CORS warnings when opening the file directly). You can use Python’s built‑in server:
  ```bash
  cd path/to/FreePC
  python -m http.server 8000
  ```
  Then open `http://localhost:8000/freepc_booking_system.html`.

## 🚀 Installation / Quick Start

1. **Download / clone the repository**
   ```bash
   git clone https://github.com/demianiukmaks2012-del/FreePC.git
   cd FreePC
   ```
2. **Ensure the image is present** – `baldi.png` should be alongside the HTML file.
3. **Open the app**
   - Double‑click `freepc_booking_system.html` **or**
   - Run a local server as shown above and navigate to the URL.
4. The UI loads with a nostalgic notebook background and the Baldi avatar ready to guide you.

## 🖱️ How to Use the App

### 1️⃣ Profile Setup
- Click **«Профіль»** in the left menu.
- Fill in your name and email. Click **«Зберегти профіль»**.

### 2️⃣ Choose a Cabinet
- Select **«Вибір кабінету»**.
- Pick a classroom (e.g., 101, 102) from the list.

### 3️⃣ 2‑D Classroom Plan
- Click **«2D План класу»** to view a top‑down view of desks and PCs.
- If a plan has not been drawn by the admin, the system will block access and redirect you to the manual booking form.

### 4️⃣ Booking a PC
- In the 2‑D view, click a free computer icon to reserve it.
- Your reservation appears in the **«Мої бронювання»** section.

### 5️⃣ Admin Mode
- Open the **«Адмін‑панель»**.
- Enter the password **`baldi`** (the only valid password).
- You can now:
  - Create or edit a classroom layout using the drag‑and‑drop editor.
  - Publish the layout so students can see the updated plan.
  - Delete or modify existing bookings.

## 🎨 Customisation
- **Add more cabinets** – Duplicate the JSON entry in `cabinets.json` (or the equivalent data block) and create a new 2‑D layout via the admin panel.
- **Change the theme** – Edit the CSS file `style.css` (look for `--bg-color`, `--accent-color`, etc.).
- **Swap the avatar** – Replace `baldi.png` with any PNG that has a transparent background.

## 📄 License & Credits
- © 2024‑2026 FreePC Project – All rights reserved.
- Inspired by classic 1990‑era school computer labs.
- Avatar: **Baldi** (original artwork created for this project).

---

*Enjoy managing your computer lab with a touch of nostalgia!*