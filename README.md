# JUST Cover Page Generator (A4)

A simple web app for **Jashore University of Science and Technology (JUST)** students to generate an **A4 print-ready** assignment/lab cover page.

It works fully in the browser (no backend). Students fill in required information, preview the cover page instantly, and **Print / Save as PDF**.

## Features

- **A4 Print-Perfect Layout** (fixed mm sizing + print CSS)
- **Live Preview**
- **Required Fields Validation** (highlights missing fields before printing)
- **Template Options**: Lab Report / Assignment / Project
- **Logo Presets**
  - Default JUST logo: `just-logo.png`
  - Optional department logo: `dept-logo.png`
  - Upload logo / URL logo / remove logo
- **Save & Load Student Profile** (LocalStorage)
  - Saves Name, ID, Session, Department, University in the browser
- **Batch Mode (Multiple Students)**
  - Paste or upload **CSV**
  - Generate multi-page batch preview
  - Print batch or download one combined PDF (browser-dependent)

## Demo / Live Link

- Live site: `YOUR_LIVE_LINK_HERE`

## Project Structure

```txt
.
├── index.html
├── just-logo.png
└── dept-logo.png   (optional)
