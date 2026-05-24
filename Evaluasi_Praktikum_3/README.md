# 📘 Tugas Evaluasi Modul 3 — Subnetting & Konversi IP

Assalamualaikum 👋

Berikut adalah tugas evaluasi Modul 3 mengenai:

# 🌐 Konversi IP Address dan Subnetting

Mahasiswa diminta untuk:

- Mengonversi IP Address ke bentuk biner
- Menentukan subnet berdasarkan prefix
- Membuat tabel:
  - IP Network
  - IP Awal
  - IP Akhir
  - IP Broadcast
- Menjelaskan langkah/cara pengerjaan

---

# 📝 Daftar Soal

1. Konversi IP dari:

```txt
192.168.100.100/29
```

2. Konversi IP dari:

```txt
192.168.10.0/30
```

3. Konversi IP dari:

```txt
192.168.200.0/28
```

4. Konversi IP dari:

```txt
172.125.10.0/26
```

5. Konversi IP dari:

```txt
100.100.10.0/27
```

---

# 📌 Ketentuan Pengerjaan

Untuk setiap soal:

## 1️⃣ Konversi IP ke Biner

Contoh:

```txt
192.168.1.1

11000000.10101000.00000001.00000001
```

---

## 2️⃣ Tentukan Informasi Berikut

| Keterangan | Isi |
|------------|------|
| IP Network | ... |
| IP Awal | ... |
| IP Akhir | ... |
| IP Broadcast | ... |
| Subnet Mask | ... |
| Jumlah Host | ... |

---

## 3️⃣ Tuliskan Cara Kerja/Subnetting

Minimal menjelaskan:

- Cara menentukan subnet mask
- Cara menentukan blok subnet
- Cara menentukan IP awal dan akhir
- Cara menentukan broadcast
- Cara menghitung jumlah host

---

# 📖 Contoh Format Jawaban

## 🔹 Soal 1

### IP Address

```txt
192.168.100.100/29
```

---

### Konversi Biner

```txt
192     = 11000000
168     = 10101000
100     = 01100100
100     = 01100100
```

Hasil:

```txt
11000000.10101000.01100100.01100100
```

---

### Informasi Subnet

| Keterangan | Hasil |
|------------|--------|
| Subnet Mask | 255.255.255.248 |
| Jumlah Host | 6 Host |
| IP Network | 192.168.100.96 |
| IP Awal | 192.168.100.97 |
| IP Akhir | 192.168.100.102 |
| IP Broadcast | 192.168.100.103 |

---

### Cara Kerja

- Prefix `/29` berarti subnet mask:
  
```txt
255.255.255.248
```

- Total IP:

```txt
2^(32-29) = 8 IP
```

- Host yang dapat digunakan:

```txt
8 - 2 = 6 Host
```

- Blok subnet:

```txt
256 - 248 = 8
```

- Kelipatan subnet:

```txt
0, 8, 16, 24, ..., 96, 104
```

- Karena IP `100` berada di antara `96–103`, maka:

```txt
Network ID  : 192.168.100.96
Broadcast   : 192.168.100.103
```

---

# 🎯 Tujuan Pembelajaran

Mahasiswa diharapkan mampu:

- Memahami konsep subnetting
- Menghitung subnet berdasarkan CIDR
- Mengonversi IP ke biner
- Menentukan Network ID dan Broadcast
- Menghitung range host

---

# 📚 Materi Terkait

- IP Address
- Binary Conversion
- CIDR
- Subnet Mask
- Network Address
- Broadcast Address
- Subnetting

---

# ⚠️ Catatan

- Kerjakan secara manual
- Tulis langkah pengerjaan dengan jelas
- Gunakan tabel agar lebih rapi
- Pastikan hasil subnetting benar

---