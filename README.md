# Flight Information Form

Mobile web app for filling in the cabin crew Flight Information Form.

## Features

- **Sectors**: flight no., destination, STD (shown as Depart–Arrive), PAX, Time (left blank to fill in)
- **Aircraft picker**: tap HS-VKA … HS-VKT or VZ- (Boeing) and the safety equipment (HAL, PBE, POB, ELT, F, Slide, LV, ILV, safety card) fills in automatically
- **Cockpit & crew** list with positions and IDs
- **Paper-style preview** matching the printed form
- **Save as PNG or PDF**
- **Print** one form on a quarter of A4 (A6, top-left corner with cut lines)
- **Auto-fill from screenshots** of the roster app (Duty Detail / Flight Detail). Reads the text on the phone with Tesseract.js OCR (the first run downloads about 10 MB). When opened as a Claude artifact, Claude reads the images instead. Use clean screenshots with no drawing on them.
- Form is saved in the browser (localStorage)

## Install on your phone

Open https://kikmakawan.github.io/flight-info-form/ then:
- **Android (Chrome / Samsung Internet)**: tap **⬇ ติดตั้งแอป** at the top, or menu ⋮ → *Install app* / *Add to Home screen*
- **iPhone (Safari)**: Share → *Add to Home Screen*

After the first load the form also works offline.

## Use

Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root).

## Notes

Equipment data comes from the CCD Aircraft Information list and MTC2026-07 (safety cards effective 01 AUG 2026). Check it against the latest crew notices before relying on it.
