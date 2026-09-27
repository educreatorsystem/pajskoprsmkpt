SISTEM PENGURUSAN PAJSK & OPR
SEKOLAH MENENGAH KEBANGSAAN PADUKA TUAN

FAIL GITHUB
1. index.html
2. school-logo.png

FAIL GOOGLE APPS SCRIPT
1. Code.gs
2. appsscript.json

KONFIGURASI
SHEET ID: 1YOmPhJ3lxqkSTaJVNaSWi0g5dLUoIyupeoDtRBq9ZfU
APPS SCRIPT URL: https://script.google.com/macros/s/AKfycbx08XCLp92eDo7SuXc5rl_t-5rpoCN5w76Y8j9c6zRkldcGOZX5had08Gm77N5vmA0HMg/exec
DRIVE/FOLDER ID: 1fCc-B0JzLFKBKU14uBBp76_Pe7DFG8vy

CSV MURID:
https://docs.google.com/spreadsheets/d/e/2PACX-1vSZW_7Cs5dG2pC5DTJeqt0zpFiQfUSUPOhN80F4348WaqGF6bG0kx6TCDkdF7eqxHtoR5VfdlcVkiF7/pub?gid=1120018474&single=true&output=csv

CSV GURU:
https://docs.google.com/spreadsheets/d/e/2PACX-1vSZW_7Cs5dG2pC5DTJeqt0zpFiQfUSUPOhN80F4348WaqGF6bG0kx6TCDkdF7eqxHtoR5VfdlcVkiF7/pub?gid=464426741&single=true&output=csv

CSV UNIT:
https://docs.google.com/spreadsheets/d/e/2PACX-1vSZW_7Cs5dG2pC5DTJeqt0zpFiQfUSUPOhN80F4348WaqGF6bG0kx6TCDkdF7eqxHtoR5VfdlcVkiF7/pub?gid=405387551&single=true&output=csv

CARA PASANG
A. GitHub Pages
- Upload index.html dan school-logo.png ke root repository.
- Aktifkan GitHub Pages.

B. Apps Script
- Gantikan Code.gs dengan fail yang diberi.
- Aktifkan appsscript.json dalam Project Settings dan gantikan kandungannya.
- Jalankan authorizeDriveAccess() sekali dan benarkan akses.
- Jalankan testDriveWriteAccess() untuk menguji folder Drive.
- Deploy > Manage deployments > Edit > New version > Deploy.
- Execute as: Me
- Who has access: Anyone
