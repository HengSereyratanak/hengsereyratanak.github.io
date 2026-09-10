# Award images

Photos for the Recognition section. One file per photo — used for both the
grid tile (shrunk by CSS) and the lightbox full view.

| Award | Round | Files |
|---|---|---|
| Huawei ICT Competition | National | `huawei-national-1.jpg`, `huawei-national-2.jpg` |
| Huawei ICT Competition | Regional | `huawei-regional-1.jpg`, `huawei-regional-2.jpg` |
| Huawei ICT Competition | Global Stage | `huawei-global-1.jpg`, `huawei-global-2.jpg` |
| E-Gen IoT Competition | — | `egen-1.jpg`, `egen-2.jpg`, `egen-3.jpg` |
| ASEAN Data Science Explorer | — | `dse-1.jpg`, `dse-2.jpg` |

- The cover photo shown inline on `index-classic.html` is `huawei-global-1`, `egen-1`,
  and `dse-1` — swap those `data-full`/`img src` references there if a different photo
  should be the cover.
- If a file is missing, that photo tile just doesn't render — nothing breaks.
- Use plain `.jpg` (not `.HEIC`) — Chrome/Firefox/Edge can't display HEIC.
