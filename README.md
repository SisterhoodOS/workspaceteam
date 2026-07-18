# Workspace Monika

Pencatat kerja dan penghasilan untuk Monika Purba, kontraktor independen di Saha Synergy Group Ltd.

**Live:** https://sisterhoodos.github.io/workspaceteam/

## Isinya

- **Ringkasan Bulan** — total yang didapat bulan ini, dipisah antara yang sudah di-approve dan yang masih menunggu, plus pemantau jam admin per minggu terhadap batas 25 jam
- **Catat Kerja** — form input, tarif terisi otomatis begitu jenis pekerjaan dipilih, ada kolom link hasil kerja dan status approval
- **Approval** — daftar pekerjaan yang belum beres approval Sophia
- **Daftar Tarif** — seluruh rate card dari kontrak
- **Aturan Kerja** — syarat kontrak, contoh bulan penuh
- **Data & Backup** — unduh cadangan JSON dan CSV

## Dasar perhitungan

Mengikuti dokumen yang ditanda tangani 16 Juli 2026, versi dengan jam admin 15-25 jam per minggu. Kurs referensi 18.000 IDR per USD.

## Data

Tersimpan di `localStorage` browser, kunci `monika_workspace_v1`. Tidak dikirim ke server mana pun. Data hanya ada di komputer yang dipakai membuka halaman ini, jadi unduh cadangan secara berkala.

## Cara mengubah

Edit `index.html`, lalu:

```
git add -A
git commit -m "pesan perubahan"
git push
```

GitHub Pages menayangkan branch `main` dari root. Perubahan muncul kira-kira satu menit setelah push.
