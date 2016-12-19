# games
Dataset dari Divinekids.

TODO: 
- Normalisasi konten duplikat
- Content by year/date

<!-- 

!! Anda tidak bisa melihat ini. Hehehe~ !!

Konsep:

a Game, has:
- `title` (1)
- `year`/`date` (1)
- `author` (M)
- `filename` (M)
- `gallery` (M)

Keterangan tambahan:
- `game-name-filename.md` menjadi nama unik serta url dari konten.
  - ini hanya terdiri dari: huruf non-capital, 123..0, dan hypen ("-").
- "M" artinya Many (banyak), sedangkan "1" artinya Single (tunggal)
- Relasi, suatu data bergantung dengan data lainnya. Yaitu:
  - `filename` -> `./_data/csv/download.csv`
  - `gallery` -> `./images/gallery/`

 -->
