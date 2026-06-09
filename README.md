# SAI Hostel Management Portal

A full-featured hostel management system for Sports Authority of India.

## Features
- Resident management with Aadhaar / Gov ID upload
- Room & bed assignment
- Meal attendance tracking
- Complaint management
- Warden management
- AI Assistant (ARIA) powered by Claude
- Excel import / export
- PWA — installable on iOS, Android, Desktop

## Deploy to Vercel

### Option A — Vercel Dashboard (No CLI needed)
1. Go to [vercel.com](https://vercel.com) and sign up / log in
2. Click **"Add New Project"**
3. Click **"Import Git Repository"** or use **"Deploy without Git"**
4. Drag and drop this folder, or upload `index.html`
5. Click **Deploy** — done in ~30 seconds

### Option B — Vercel CLI
```bash
npm install -g vercel
cd sai-hostel-vercel
vercel
```
Follow the prompts. Your app will be live at `https://your-project.vercel.app`

### Option C — GitHub + Vercel (Auto-deploy on every update)
1. Push this folder to a GitHub repo
2. Go to vercel.com → Import from GitHub
3. Every `git push` auto-deploys

## Login Credentials
| Role | Username | Password |
|------|----------|----------|
| Super Admin | `admin` | `sai@admin123` |
| Warden | `warden1` | `warden@123` |
| Resident | `resident1` | `res@123` |

## Install as App
- **iPhone**: Safari → Share → Add to Home Screen
- **Android**: Chrome → Menu → Install App
- **Desktop**: Chrome address bar → Install icon (⊕)

## Tech Stack
- Pure HTML/CSS/JavaScript — zero dependencies to install
- SheetJS for Excel import/export
- Anthropic Claude API for ARIA AI assistant
- IndexedDB for photo storage
- window.storage / localStorage for data persistence
