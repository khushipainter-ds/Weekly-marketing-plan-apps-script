# 📋 Weekly Marketing Plan — Google Apps Script

A full-stack automated weekly sales planning tool built with 
Google Apps Script + Google Sheets.

## ✨ Features
- Google Sign-In + manual email authentication
- Role-based access: Admin sees all salespeople, 
  others see only their own data
- Auto-generates weekly rows every Saturday via time trigger
- Tracks first-fill timestamps and edit timestamps separately
- Responsive UI — table on desktop, cards on mobile
- Dropdown status validation (Planned/Completed/Rescheduled/Cancelled)
- Oldest weeks auto-deleted to keep sheets clean

## 🛠 Tech Stack
- Google Apps Script (backend)
- HTML / CSS / Vanilla JS (frontend)
- Google Sheets API (data layer)
- Google Sign-In (OAuth 2.0)

## 📸 Screenshots
<img width="792" height="528" alt="image" src="https://github.com/user-attachments/assets/def7a3a2-3325-4efa-ba39-eade97260d0e" />
<img width="1364" height="598" alt="image" src="https://github.com/user-attachments/assets/dddcd4ce-3999-4bf1-8a67-aace633e2b25" />


## 🚀 How to Deploy
1. Open Google Sheets → Extensions → Apps Script
2. Paste Code.gs and Index.html
3. Run `firstTimeSetup()` once
4. Open via Weekly Plan → Open Plan Form

## 📁 Project Structure
- `weekplansystemcode.gs.txt` — All backend logic (auth, save, load, triggers)
- `weekplansystem.html` — Frontend form (UI + client-side JS)
