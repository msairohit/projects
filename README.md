# 🚀 Sai Rohit's Projects Portfolio


This document serves as a comprehensive index of my projects.

---

## 🌟 Featured Projects

### 📱 1. Timeliney 👋
> **A privacy-focused life logging & journaling application**
*   **Platform:** Mobile (iOS & Android)
*   **Repository:** [msairohit/timeliney](https://github.com/msairohit/timeliney)
*   **Core Stack:** Expo, TypeScript, Expo Router, Google Drive REST API
*   **Download APK:** [Releases (Latest APK) ↗](https://github.com/msairohit/timeliney/releases)

#### 🚀 Key Features
*   **Interactive Dashboard:** Surfacing memories on "On This Day" (1, 2, 5+ years ago) and random flashback prompts to keep users connected to their past.
*   **Google Drive Sync:** Private, cross-device synchronization. User data resides entirely in the user’s Google Drive space, ensuring zero backend data leaks.
*   **Highlights & Series:** Curate media-rich moment collections or track ongoing life logs (e.g., travel logs or workout streaks).

---

### 🏪 2. ShopGrid
> **A multi-tenant inventory & commerce platform**
*   **Platform:** Mobile (iOS & Android)
*   **Repository:** [msairohit/shopgrid](https://github.com/msairohit/shopgrid)
*   **Core Stack:** Expo, TypeScript, Supabase, Zustand, SQLite
*   **Download APK:** [Releases (Latest APK) ↗](https://github.com/msairohit/shopgrid/releases)

#### 🚀 Key Features
*   **Multi-Tenant Architecture:** Built-in security context where Admins, Sellers, and Customers only access data scoped to their specific tenant.
*   **Modular Catalogue Templates:** Dynamic UI fields that adapt based on the business type (e.g., *Prescription checks* for Medicines, *Color/Size matrices* for Clothes, *SKU/Barcode scanner* for Supermarkets).
*   **Offline Billing & Fulfillment:** Sellers can operate fully offline. Local changes queue up in `sync_log` and synchronize bi-directionally on network restoration.
*   **Granular Fulfillment Flow:** Multi-seller order routing where items are packed, shipped, and fulfilled independently per seller.

---

### 📊 3. Spendly
> **A modern, interactive expense tracking application**
*   **Platform:** Mobile (iOS & Android)
*   **Repository:** [msairohit/spendly](https://github.com/msairohit/spendly)
*   **Core Stack:** Expo, TypeScript, Expo Router, Zustand
*   **Download APK:** [Releases (Latest APK) ↗](https://github.com/msairohit/spendly/releases)

#### 🚀 Key Features
*   **Interactive Visualization:** Super-attractive financial analysis dashboards, dynamic graphs, and expense tracking visualization tools.
*   **Multiple Viewing Modes:** View expenditures structured as a chronological timeline, interactive calendar, monthly/weekly aggregates, or granular sorted-by-time lists.
*   **Scoped User Context:** Tracks and displays logs specific to the logged-in user with persistent storage.

---

### 🎨 4. QuoteCanvas
> **A clean, delightful, and highly customizable quotes app for daily inspiration**
*   **Platform:** Mobile (iOS & Android)
*   **Repository:** [msairohit/quotes_rn](https://github.com/msairohit/quotes_rn)
*   **Core Stack:** React Native, TypeScript, AsyncStorage, Sharing APIs
*   **Download APK:** [Releases (Latest APK) ↗](https://github.com/msairohit/quotes_rn/releases)

#### 🚀 Key Features
*   **Zero-Interruption Policy:** Ad-free, sign-up-free content delivery with no user tracking or data collection.
*   **Dynamic Visual Customizer:** Allows users to share quotes as custom-designed images. Supports custom photo imports, random background generation, and an inline color picker.
*   **Auto-Resizing Text Engine:** Automatically scales text based on length to guarantee clean typography on generated images.
*   **Color Theme Palette:** 10 curated color themes that dynamically recolor the entire app's active style.
*   **Local Bookmarks:** Simple, offline-friendly caching to quickly save and categorize favorite quotes.

---

### 🧩 5. Riddle Realm
> **An interactive trivia app featuring a fuzzy matching evaluation engine**
*   **Platform:** Mobile (iOS & Android)
*   **Repository:** [msairohit/riddle-realm](https://github.com/msairohit/riddle-realm)
*   **Core Stack:** Expo, TypeScript, AsyncStorage
*   **Download APK:** [Releases (Latest APK) ↗](https://github.com/msairohit/riddle-realm/releases)

#### 🚀 Key Features
*   **Fuzzy Answer Checker:** Leverages Levenshtein distance similarity scoring with a custom threshold (0.75 by default) to accept close guesses.
*   **Normalization Pipeline:** Sanitizes user inputs by automatically handling case-insensitivity, stripping whitespace, removing punctuation, and ignoring grammatical articles ("a/an/the").
*   **Progress Persistence:** Tracks solved indexes, hints accessed, and game progression using local `AsyncStorage` across restarts.
*   **Flexible Schema:** Supports mapping multiple correct answers or synonyms for each riddle.

---

### 🔐 6. ApexCalc (Polyglot Vault)
> **A security steganography utility and private vault for compiled polyglot files**
*   **Platform:** Mobile (iOS & Android)
*   **Repository:** [msairohit/ApexCalc](https://github.com/msairohit/ApexCalc)
*   **Core Stack:** Expo, TypeScript, `expo-file-system`, `expo-secure-store`
*   **Download APK:** [Releases (Latest APK) ↗](https://github.com/msairohit/ApexCalc/releases)

#### 🚀 Key Features
*   **Stitching Engine:** Decodes cover files to raw binary strings, embeds secret assets as Base64 strings wrapped in delimiter markers, and encapsulates them in syntax-compliant comments (C-style block, HTML/XML comments, shell `#`, or PDF `%`) appended after the parsing boundary (e.g. `%%EOF` or `FF D9`).
*   **Reveal/Extraction Engine:** Automatically locates the polyglot marker in binary streams, trims the comment wrappers to restore the cover file to its pristine original state, and extracts/decodes the hidden Base64 payload (such as private images/videos).
*   **Private Sandbox Vault:** Encrypted vault storage via private sandboxed folders, protected by `expo-secure-store` credentials, and structured via a local `vault_metadata.json` database.

---
> 💡 **Note:** All of the projects in this portfolio were built and engineered with the help of AI (Vibe Coding) — demonstrating the power of modern AI-collaborative software development.
---
📫 **Get in touch:** Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sai-rohit-manikonda/) or explore my profile at [github.com/msairohit](https://github.com/msairohit).
