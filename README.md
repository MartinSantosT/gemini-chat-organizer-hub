# 🧠 AI Knowledge Hub (v46.1 Stable)

![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-46.1-blue)
![Tech](https://img.shields.io/badge/stack-HTML%20%7C%20JS%20%7C%20Tailwind-purple)
![Status](https://img.shields.io/badge/status-Stable-success)

> **A "Local Second Brain" for your AI conversations. Single HTML file. No Install. 100% Private.**

---

## 🚀 Why I built this?

I use Google Gemini (and Claude/ChatGPT) daily for coding, business planning, and creative writing. But I ran into a problem: **managing the chaos**.

I kept losing the context of my best conversations. Brilliant prompts and complex project discussions were buried under a pile of "Untitled Chats" in my history. I tried Notion, Obsidian, and Trello, but they felt too heavy/slow for simply saving chat links.

I needed something **fast, private, and visual**. So, I built **Gemini Knowledge Hub**.

---

## ✨ Key Features

### 🎨 UI & Experience
* **📂 Zero Installation:** It's just **ONE HTML file**. No servers, no databases, no `npm install`. Just download and open in your browser.
* **🌙 Dark Mode (v46):** Native dark mode support for late-night coding sessions. Persists your preference automatically.
* **🔎 Smart Search:** Hybrid search bar with auto-complete suggestions for tags and an instant "Clear" button.

### ⚡ Workflow
* **🚦 Kanban Dashboard:** Organize chats into **Ideas**, **Pins** (High Priority), **Projects** (Active), and **Archive**.
* **☁️ Hybrid Linking:** Each card links to the **Live Cloud Chat** (to continue working) AND a **Local HTML Backup** (to preserve the context forever).
* **✅ Task Tracking:** Add checklists to cards. Unfinished tasks auto-tag the card as `⚠️ Pending`.
* **🏷️ Smart Tagging:** Organize by topic (`#python`, `#marketing`). Click any tag to filter the board instantly.

### 🔒 Data & Privacy
* **🛡️ Local-First:** All data lives in your browser's `localStorage`. Nothing is sent to any server.
* **💾 Timestamped Backups:** Export your entire database to a `.json` file with HH-MM timestamps (e.g., `backup_2025-11-25_14-30.json`).
* **🚑 Rescue Mode:** Automatic sanitization system that detects and fixes corrupt legacy data on startup to prevent crashes.

---

## 📸 Screenshots

<img width="2264" height="1235" alt="screenshot-l" src="https://github.com/user-attachments/assets/225a5737-1e4f-4faf-8511-42416faa5868" />

<img width="2282" height="1231" alt="screenshot-b" src="https://github.com/user-attachments/assets/07adced0-2414-4f97-b233-c0d61fb370f6" />

---

## 🛠️ How to Use

1.  **Download** the `index.html` file (or `Gemini_Hub.html`) from this repository.
2.  **Create a folder** on your computer (e.g., `My_AI_Projects`).
3.  **Place the file** inside that folder.
4.  **Open it** in any modern browser (Chrome, Edge, Firefox, Brave).
5.  Click **"+ New Chat"** to start organizing!

> **Universal Compatibility:** While I built this for Gemini, it works perfectly for **ChatGPT, Claude, Perplexity**, or even organizing YouTube tutorials and GitHub repos.

---

## ☁️ Pro Tip: Sync across devices

Since the app is just one file, you can save the HTML and your exported `.json` backups in **OneDrive, Dropbox, or Google Drive**.

* **The File:** Syncs automatically via your cloud provider.
* **The Data:** To move your board state to another computer, click the **Export Backup** button on PC 1, and **Import Backup** on PC 2.

---

## 🔄 Update Log (v46.1)

* **Feature:** Added native Dark Mode toggle 🌙.
* **Feature:** "Rescue Mode" added to prevent loading freezes on legacy data.
* **Feature:** Backup filenames now include timestamps to prevent overwriting.
* **UX:** Action buttons moved to card footer; Title links are now "smart" (only clickable if a link exists).
* **Localization:** Fully translated to English for universal usage.

---

## 📄 License

**MIT License**. Free and Open Source.
Feel free to fork, modify, and make it your own!

Built with ❤️ (and a lot of help from Gemini) by **Martin Santos Temponi**.

