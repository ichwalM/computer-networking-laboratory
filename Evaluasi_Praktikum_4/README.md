# 📘 SOAL EVALUASI IV — VLSM (Variable Length Subnet Mask)

## 📝 Deskripsi Soal

Diketahui sebuah jaringan dengan IP Address untuk akses internet (**IP Public**) sebagai berikut:

```txt
175.20.0.0/16
```

Jaringan tersebut akan dibagi menjadi beberapa ruang dengan kebutuhan host berbeda menggunakan metode:

# 🔧 VLSM (Variable Length Subnet Mask)

---

# 📊 Kebutuhan Host

| Ruangan        | Jumlah Host |
|----------------|------------|
| Ruang Utama    | 10000 Host |
| Ruang Kedua    | 5000 Host |
| Ruang Ketiga   | 300 Host |
| Ruang Server   | 3 Host |

---

# 📌 Tugas

Lakukan pembagian IP Lokal untuk mengakses IP Public menggunakan teknik **VLSM**.

Kemudian tentukan untuk masing-masing subnet:

- a. Jumlah Host
- b. Alamat Jaringan (Net ID)
- c. Alamat Broadcast
- d. Range IP yang dapat digunakan

---

# 📖 Ketentuan

- Gunakan metode **VLSM**
- Urutkan subnet dari kebutuhan host terbesar ke terkecil
- Tentukan subnet mask yang sesuai untuk setiap kebutuhan host
- Sertakan perhitungan subnet jika diperlukan

---

# 📂 Format Jawaban yang Diharapkan

| Ruangan | Jumlah Host | Net ID | Prefix/Subnet Mask | Range IP | Broadcast |
|----------|-------------|--------|--------------------|-----------|------------|
| ... | ... | ... | ... | ... | ... |

---

# 🎯 Tujuan Evaluasi

Mahasiswa diharapkan mampu:

- Memahami konsep subnetting
- Mengimplementasikan teknik VLSM
- Menentukan pembagian jaringan berdasarkan kebutuhan host
- Menghitung Net ID, Broadcast, dan Range IP

---

# 📚 Materi Terkait

- IP Addressing
- Subnetting
- CIDR
- VLSM
- Network Address
- Broadcast Address

---

# ⚠️ Catatan

Pastikan setiap subnet:

- Tidak overlap
- Memiliki jumlah host yang cukup
- Menggunakan subnet mask yang efisien

---