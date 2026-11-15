# Plotframe

A Figma-style board for building charts: column, bar, line, area and donut charts, KPI tiles and text. Paste data from Excel or Google Sheets, then export PNG or SVG.

Live page: https://k4rlis.github.io/plotframe/

The page is password-protected. `index.html` holds only an encrypted copy of the app (AES-256-GCM, with the key derived from the password by PBKDF2-SHA256 at 600,000 iterations). Your browser decrypts it after you enter the password, and the password is never stored in this repository.
