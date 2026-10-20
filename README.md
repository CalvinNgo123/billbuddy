# Bill Buddy 🧾😊

A lightweight, fully client-side receipt scanner and splitter designed for quick splitting on iPhone and web. Built with Tailwind CSS and Tesseract.js, everything runs directly in your browser with zero server dependencies—making it ideal for instant hosting on **GitHub Pages**.

---

## ✨ Features

* **📷 Instant Capture & Upload:** Seamlessly snaps photos using your iPhone camera or uploads existing images/PDF receipts.
* **🔍 Local OCR Processing:** Uses Tesseract.js client-side optical character recognition to extract line items and prices automatically.
* **➕ Dynamic People Tags:** Tap a simple `+` button to add participants and assign names instantly.
* **🏷️ Item Splitting:** Assign any item to one or multiple people with clean visual chips.
* **💰 Tax & Tip Management:** Includes built-in tip percentage presets (15%, 18%, 20%, 25%) as well as custom tax and tip input fields.
* **📊 Live Breakdown Summary:** Calculates individual sub-totals, proportionate tax, tip shares, and grand totals on the fly.
* **📱 PWA Ready:** Add it straight to your iPhone Home Screen for a native app-like experience.

---

## 🚀 Quick Setup & Deployment

1. **Create your repository:** Set up a public repository on GitHub.
2. **Add the files:**
   * Place the main app code in an `index.html` file at the root of your repository.
   * Add your app icon as `apple-touch-icon.png` in the root directory.
3. **Enable GitHub Pages:**
   * Go to your repository **Settings** > **Pages**.
   * Under **Build and deployment**, select your `main` branch (or `gh-pages`) and root folder `/` as the source, then click **Save**.
4. **Access your app:** Open the generated GitHub Pages URL on your iPhone, tap the Share button in Safari, and select **"Add to Home Screen"** to use it like a native app!

---

## 🛠️ Built With

* [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework
* [Tesseract.js](https://github.com/naptha/tesseract.js) – Pure JavaScript Multilingual OCR Engine
