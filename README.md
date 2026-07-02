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
<img width="792" height="528" alt="image" src="<img width="431" height="350" alt="image" src="https://github.com/user-attachments/assets/c4483589-c40e-4530-8b72-29771d2b886a" />
" />
<img width="1364" height="598" alt="image" src="<img width="943" height="462" alt="image" src="https://github.com/user-attachments/assets/9005b318-8b89-4550-99ca-ff514022c194" />
" />


## 🚀 How to Deploy
1. Open Google Sheets → Extensions → Apps Script
2. Paste Code.gs and Index.html
3. Run `firstTimeSetup()` once
4. Open via Weekly Plan → Open Plan Form

## 📁 Project Structure
- `weekplansystemcode.gs.txt` — All backend logic (auth, save, load, triggers)
- `weekplansystem.html` — Frontend form (UI + client-side JS)
