<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Latihan CI/CD</title>
</head>
<body>
  <h1>Halo, ini web latihan CI/CD</h1>
  <p>Versi 5 - title dikembalikan</p>
  <p>Build nomor: __BUILD__</p>
  <footer>Dibuat oleh Umi Khoirullatifah</footer>
</body>
</html>
```[cite: 1, 2]

### Catatan penting saat dipakai dengan pipeline kamu:
* **`__BUILD__`** akan otomatis diganti oleh perintah `sed -i "s/__BUILD__/Build nomor: $BUILD_NUMBER/"` atau `sed -i "s/__BUILD__/$BUILD_NUMBER/"` di `stage('Deploy')` (sebelum `cp`), sehingga di browser nanti muncul sesuai nomor build Jenkins (misalnya `Build nomor: 8`)[cite: 1, 2].
* Tag `<title>`, `<html>...</html>`, dan `<footer>` sudah ada supaya seluruh pengecekan di `stage('Test')` lolos[cite: 1].
* Bagian `<footer>` sudah diisi dengan **Umi Khoirullatifah** (bisa kamu sesuaikan kalau ingin memakai nama lain)[cite: 1, 2].

Apakah kamu juga butuh baris `sed` di `Jenkinsfile` disesuaikan agar format tulisan nomor build-nya persis seperti di gambar?
