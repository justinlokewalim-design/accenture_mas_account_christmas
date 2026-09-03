# 🎄 MAS Account Christmas Gift Exchange 2026

A Secret Santa web app for the Accenture MAS Account team.

**Event Date:** Friday, 27 November 2026  
**Secret Santa Reveal:** 1 November 2026  

---

## 🚀 How to Deploy on GitHub Pages

1. **Create a new GitHub repository**
   - Go to [github.com](https://github.com) → click **"New"**
   - Name it something like `mas-christmas-2026`
   - Set it to **Private** (recommended)
   - Click **"Create repository"**

2. **Upload the files**
   - Click **"uploading an existing file"**
   - Drag and drop ALL files from this folder
   - Click **"Commit changes"**

3. **Enable GitHub Pages**
   - Go to **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Branch: `main` / Folder: `/ (root)`
   - Click **Save**

4. **Your site will be live at:**
   ```
   https://YOUR-USERNAME.github.io/mas-christmas-2026/
   ```
   *(takes ~2 minutes to go live)*

5. **Share the link with your team!**

---

## 🔐 Admin Access

- Open the website → scroll to bottom of landing page → click **"Admin ›"**
- Default password: `accenture2026`
- **Change this password** in Admin → Event Settings after first login!

## 👤 Admin First Steps

1. Log in to Admin panel
2. Go to **Event Settings** → update the venue once confirmed
3. Wait for everyone to register
4. Click **"Run Draw"** to assign Secret Santa pairs
5. Pairs are revealed automatically on **1 November 2026**

---

## ✉️ Email Setup (EmailJS)

Emails are sent via [EmailJS](https://emailjs.com) when someone registers.  
Configured with:
- Service: Gmail
- Triggered on: successful registration
- Content: username confirmation + event details

---

## 📁 File Structure

```
mas-christmas-2026/
├── index.html        ← Main website (everything in one file)
├── data.json         ← Sample data structure (reference only)
└── README.md         ← This file
```

> **Note:** All live data is stored in the user's browser `localStorage`.  
> Use **Admin → Export JSON** to back up data regularly!  
> Use **Admin → Import JSON** to restore data on a new device.

---

## 🎯 Features

| Feature | Description |
|---------|-------------|
| 🔐 Secret username login | No password needed after registration |
| 📧 Auto email on register | Sends username confirmation via Gmail |
| 🎅 Secret Santa draw | Random shuffle, no self-pairing |
| 🔒 Reveal date lock | Results hidden until 1 Nov 2026 |
| 🚫 Don't-get-me list | Tell your Santa what to avoid |
| 👤 Anonymous option | Hide your name from your Santa |
| ⏱️ Countdown timer | Live countdown to the party |
| 💾 Export/Import JSON | Backup and restore all data |

---

## 📞 Contact

Questions? Contact **sin.loke.lim@accenture.com**
