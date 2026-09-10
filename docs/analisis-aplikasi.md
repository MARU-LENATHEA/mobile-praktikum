cat << 'EOF' > docs/analisis-aplikasi.md
# Analisis Aplikasi Mobile (Pertemuan 1)

## 1. Aplikasi yang Diamati
BRImo (BRI Mobile) - Aplikasi Perbankan Digital dari Bank BRI.

## 2. Target Pengguna
Nasabah Bank BRI dari berbagai kalangan, seperti mahasiswa, pekerja kantoran, hingga pelaku UMKM yang membutuhkan akses transaksi finansial secara praktis dan cepat.

## 3. Tiga Fitur Utama
1. Transfer dana (BI-Fast dan antar-bank secara real-time).
2. Pembayaran non-tunai via pemindaian QRIS.
3. Tarik tunai tanpa kartu (cardless cash withdrawal) di mesin ATM/CRM.

## 4. Usulan Perbaikan
Menambahkan toleransi jeda jaringan (grace period / session retry) selama beberapa detik sebelum pemutusan sesi demi mencegah force logout mendadak saat sinyal internet beralih atau mengalami fluktuasi singkat.