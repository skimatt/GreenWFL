# 🌱 Green Commit Every 3 Days

Hai! 👋  
Ini repo kecil yang aku pakai buat **jaga kotak ijo tetap hidup** di GitHub.

Setiap **3 hari sekali**, repo ini otomatis bikin commit baru lewat GitHub Actions.  
Tujuannya simpel: biar profil GitHub kelihatan aktif dan semangat terus!

## Kenapa Bikin Gini?

Karena kadang lagi sibuk, capek, atau males ngoding... tapi tetap pengen kontribusi kelihatan jalan.  
Nah, daripada kosong sama sekali, mending commit otomatis aja sekalian, kan? 😄

## Gimana Cara Kerjanya?

- Ada file `log.txt` yang tiap 3 hari ditambahin 1 baris teks.
- GitHub Actions yang urus semuanya.
- Commit-nya asli, jadi **kotak hijaunya tebal** dan masuk ke contribution graph.

## Catatan

Kalau kamu mau pake cara yang sama:
1. Buat token GitHub (PAT)
2. Simpan di repo kamu sebagai secret `GH_TOKEN`
3. Tambahkan workflow dari `.github/workflows/every-3-days.yml`

Mudah kan?

---

> Ini bukan buat cheating. Ini buat jaga semangat dan konsistensi. Kalau bisa nambah coding beneran ya lebih bagus lagi 😁

