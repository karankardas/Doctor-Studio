# 🩺 Smart Prescription Studio

A fast, interactive, and customizable medical prescription generator and EMR editor designed for clinics and physicians, modeled after standard clinical EMR layouts (such as HealthPlix / AHC Diabetes Clinic).

Live Demo on GitHub Pages: `https://<your-username>.github.io/<your-repo-name>/`

---

## ✨ Features

- **⚡ 1-Second Auto-Fill from Text**:
  - Drag & drop or paste raw prescription text files (`.txt`), OCR transcripts, or clinical notes.
  - Automatically parses and populates patient demographics, vitals, lab test history, clinical diagnosis, and all prescribed medications.
- **📄 Clean A4 Prescription Sheet**:
  - Reconstructed header, clinic branding, and doctor credentials.
  - Formatted for standard A4 paper with exact margins.
- **✏️ Dual Editing Modes**:
  - Form fields on the left with quick preset chips (`1-0-1`, `After Food`, `90 Days`, etc.).
  - Direct **WYSIWYG** click-and-edit capability on any text on the prescription preview.
- **🖨️ 1-Click Print & Clean PDF Export**:
  - Pure `@media print` styles hide all sidebars and buttons, generating a crisp, clean PDF.
- **💾 Local Storage Saver**:
  - Save patient prescriptions directly in browser storage and reload them anytime.
- **🌐 100% Client-Side / Offline Capable**:
  - Pure HTML5, CSS3, and JavaScript with zero build tools or external server dependencies.

---

## 🚀 Running Locally

### Option 1: Direct File
Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local Server
Run with Python:
```bash
python server.py
```
Or on Windows, double-click:
```
run_localhost.bat
```
Then visit `http://localhost:5000` in your browser.

---

## 🌐 Deploying to GitHub Pages

1. Push this repository to GitHub.
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**.
5. Your live app will be published at `https://<your-username>.github.io/<your-repo-name>/` in 1–2 minutes!
