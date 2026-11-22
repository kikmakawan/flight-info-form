# Flight Information Form

Mobile web app for filling in the cabin crew Flight Information Form.

## Features

- **Sectors**: flight no., destination, STD, Depart–Arrive, PAX
- **Aircraft picker**: tap HS-VKA … HS-VKT or VZ- (Boeing) and the safety equipment (HAL, PBE, POB, ELT, F, Slide, LV, ILV, safety card) fills in automatically
- **Cockpit & crew** list with positions and IDs
- **Paper-style preview** matching the printed form
- **Save as PNG or PDF**
- **Auto-fill from screenshots** of the roster app (Duty Detail / Flight Detail). This works only when the page is opened as a Claude artifact, because it uses Claude to read the images.
- Form is saved in the browser (localStorage)

## Use

Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main` / root).

## Notes

Equipment data comes from the CCD Aircraft Information list and MTC2026-07 (safety cards effective 01 AUG 2026). Check it against the latest crew notices before relying on it.
