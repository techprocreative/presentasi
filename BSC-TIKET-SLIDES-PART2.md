# BSC TIKET - PART 2
## Platform Ticketing & Event Management Terlengkap di Indonesia

**Presentasi Slide - Part 2: Fitur Lanjutan & Dashboard**  
**Slide 11-20 dari 28**

---

## 📋 ISI PART 2

### FITUR UTAMA - BAGIAN 2 (Slide 11-15)
- Slide 11: Operasi Di Lokasi - Scanner
- Slide 12: Multi-Organization
- Slide 13: Payment Gateway (Midtrans)
- Slide 14: Payment Gateway (Xendit)
- Slide 15: Fitur Cerdas

### DASHBOARD & MANAJEMEN (Slide 16-20)
- Slide 16: Dashboard Admin
- Slide 17: Dashboard Organizer Detail
- Slide 18: Manajemen Peserta
- Slide 19: Sistem Pelaporan
- Slide 20: Tiket QR Code

---

# SLIDE 11: OPERASI DI LOKASI - SCANNER

## Check-in Cepat & Aman

```
PROSES SCANNING
═══════════════════════════════

Customer Tunjukkan QR
        │
        ▼
┌──────────────────┐
│  SCAN QR CODE    │
│   dengan Device  │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ Validasi Sistem: │
│ ✓ Sudah bayar?   │
│ ✓ Belum scan?    │
│ ✓ Tanggal benar? │
│ ✓ Tidak batal?   │
└────────┬─────────┘
         │
    ┌────┴────┐
    │         │
    ▼         ▼
 VALID    INVALID
    │         │
    ▼         ▼
✅ MASUK  ❌ TOLAK
```

### Fitur Scanner:

**Verifikasi Real-Time**
- Check database instant
- Prevent duplicate entry

**Multi-Gate Support**
- Banyak scanner bersamaan
- Sync otomatis

**Offline Mode** (coming soon)
- Tetap bisa scan tanpa internet
- Sync saat online kembali

**Catatan Presenter:**
- Demo scanner app
- Show validation speed
- 3 menit

---

# SLIDE 12: MULTI-ORGANIZATION

## Satu Platform, Banyak Organizer

```
STRUKTUR ORGANISASI
═══════════════════════════════════

        ANDA (Platform Owner)
                │
       ┌────────┼────────┐
       │        │        │
   Organizer Organizer Organizer
      A         B         C
       │        │        │
   Fee 3%   Fee 5%   Fee 7%
```

### Fleksibilitas Komisi:

**Custom per Organizer**
- Organizer A: 3% (partner strategis)
- Organizer B: 5% (standar)
- Organizer C: 7% (new organizer)

### Keuntungan Model Ini:

**Untuk Anda:**
- Revenue dari semua organizer
- Kontrol penuh platform
- Scalable business model

**Untuk Organizer:**
- Fee lebih murah dari kompetitor
- Platform profesional
- Support lengkap

**Catatan Presenter:**
- Calculate example revenue
- Show scalability potential
- 4 menit

---

# SLIDE 13: PAYMENT GATEWAY - MIDTRANS

## 11 Metode Pembayaran

```
┌─────────────────────────────────┐
│       MIDTRANS INTEGRATION      │
├─────────────────────────────────┤
│                                 │
│ 💳 KARTU KREDIT/DEBIT           │
│    • Visa                       │
│    • Mastercard                 │
│    • JCB                        │
│                                 │
│ 🏦 VIRTUAL ACCOUNT              │
│    • BCA Virtual Account        │
│    • Mandiri Bill Payment       │
│    • BNI Virtual Account        │
│    • BRI Virtual Account        │
│    • Permata Virtual Account    │
│                                 │
│ 📱 E-WALLET                     │
│    • GoPay                      │
│                                 │
└─────────────────────────────────┘
```

### Keunggulan Midtrans:

✅ Halaman pembayaran aman (Snap)
✅ Verifikasi otomatis
✅ Notifikasi real-time
✅ Settlement T+2
✅ 3D Secure support
✅ Fee: ~2.9% + Rp 2.000

**Catatan Presenter:**
- Familiar untuk customer Indonesia
- Trusted brand
- 2 menit

---

# SLIDE 14: PAYMENT GATEWAY - XENDIT

## 7 Metode Pembayaran Tambahan

```
┌─────────────────────────────────┐
│        XENDIT INTEGRATION       │
├─────────────────────────────────┤
│                                 │
│ 📱 E-WALLET                     │
│    • OVO                        │
│    • Dana                       │
│    • LinkAja                    │
│    • ShopeePay                  │
│                                 │
│ 🔲 QRIS                         │
│    • Universal QR               │
│    • Semua e-wallet support     │
│                                 │
│ 🏪 RETAIL OUTLET                │
│    • Alfamart                   │
│    • Indomaret                  │
│                                 │
└─────────────────────────────────┘
```

### Total: **18+ Metode Pembayaran**

| Gateway  | Metode | Settlement | Fee    |
|----------|--------|------------|--------|
| Midtrans | 11     | T+2        | ~2.9%  |
| Xendit   | 7      | T+1        | ~2-3%  |

**Catatan Presenter:**
- Coverage lengkap payment methods Indonesia
- Customer punya banyak pilihan
- 2 menit

---

# SLIDE 15: FITUR CERDAS

## Technology yang Memudahkan

### 1️⃣ Timer 8 Menit
```
Tiket Direservasi: 8:00
████████░░░░░░░░ 60%
Selesaikan pembayaran!
```
**Benefit:** Cegah penimbunan, fair distribution

### 2️⃣ Inventori Real-Time
```
VIP Ticket
Tersedia: 47/200 ⚠️
Direservasi: 12
Terjual: 141
```
**Benefit:** Akurat, tidak overselling

### 3️⃣ Notifikasi Otomatis
```
✉️ Konfirmasi Booking
✉️ Bukti Pembayaran
✉️ Tiket PDF (QR Code)
✉️ Pengingat Event (H-1)
```
**Benefit:** Kurangi beban customer service

### 4️⃣ Sinkronisasi Langsung
```
Booking Baru
    ↓
Update ke SEMUA:
• Dashboard Organizer
• Dashboard Admin
• Email Customer
• Scanner Device
```
**Benefit:** Real-time, tidak ada delay

**Catatan Presenter:**
- Highlight automation
- Compare manual vs automated
- 4 menit

---

# SLIDE 16: DASHBOARD ADMIN

## Kontrol Penuh Platform

```
ADMIN OVERVIEW
═══════════════════════════════════

📊 PLATFORM STATISTICS
   Total Events:     247 (89 aktif)
   Total Organizers: 45  (3 pending)
   Total Customers:  15,234
   Revenue Bulan Ini: Rp 1.2 Miliar

🏆 TOP 5 EVENTS
   1. Festival Musik Jakarta  Rp 245 Jt
   2. Seminar Bisnis 2025     Rp 180 Jt
   3. Konser Indie Night      Rp 156 Jt
   4. Workshop Marketing      Rp 123 Jt
   5. Tech Expo               Rp  98 Jt

💰 COMMISSION TRACKING
   Platform Commission: Rp 87.500.000
   Organizer Earnings:  Rp 1.112.500.000
   Payout Pending:      Rp 45.000.000

📈 TREND ANALYSIS
   Sales Growth:  ▲ +23% (vs bulan lalu)
   New Customers: ▲ +456 (bulan ini)
   Event Success: ▲ 94% positive rating
```

### Aksi Cepat Admin:
- Approve pending organizers
- Review event baru
- Kelola payment gateways
- Export laporan keuangan
- Monitor system health

**Catatan Presenter:**
- Show real admin dashboard
- Highlight control & visibility
- 3 menit

---

# SLIDE 17: DASHBOARD ORGANIZER DETAIL

## Tools Lengkap untuk Organizer

```
EVENT SAYA
═══════════════════════════════════

┌────────────────────────────────┐
│ 🎭 Konser Jazz Night          │
│    25 Des 2025                │
│    🎫 567/800 terjual         │
│    💰 Rp 142.500.000          │
│    [Detail] [Kelola] [Promosi]│
└────────────────────────────────┘

AKSI CEPAT
┌────────────────────────────────┐
│ [➕ Buat Event Baru]           │
│ [📊 Laporan Penjualan]         │
│ [👥 Kelola Peserta]            │
│ [📧 Email Massal]              │
└────────────────────────────────┘

BOOKING TERBARU (Real-time)
┌────────────────────────────────┐
│ 🆕 Budi - 2x VIP (5 menit lalu)│
│ 🆕 Siti - 1x Regular (12 menit)│
│ 🆕 Andi - 4x Group (23 menit)  │
└────────────────────────────────┘
```

### Detail Performa Event:

**Rincian Pendapatan**
- Penjualan Kotor: Rp 142.500.000
- Biaya Platform (5%): Rp 7.125.000
- Biaya Payment (3%): Rp 4.275.000
- **Pendapatan Bersih: Rp 131.100.000**

**Catatan Presenter:**
- Emphasize ease of management
- Real-time updates
- 3 menit

---

# SLIDE 18: MANAJEMEN PESERTA

## Database & Komunikasi Lengkap

```
DATABASE PESERTA
═══════════════════════════════════

📋 FILTER & CARI
┌────────────────────────────────┐
│ Cari: [____________] 🔍        │
│                                │
│ Filter:                        │
│ [Semua] [VIP] [Regular]       │
│ [Lunas] [Pending] [Hadir]     │
└────────────────────────────────┘

📊 ANALYTICS
┌────────────────────────────────┐
│ Total Terjual:    567          │
│ Tingkat Check-in: 78%          │
│ Tidak Hadir:      22%          │
│ Rata-rata Nilai:  Rp 251.234   │
│                                │
│ Demografi:                     │
│ • Usia 25-34: 45%             │
│ • L:55% | P:45%               │
│ • Jakarta: 67%                │
└────────────────────────────────┘
```

### Fitur Komunikasi:

**📧 Email Massal**
- Kirim ke semua/sebagian peserta
- Template custom
- Track delivery

**📥 Export Data**
- CSV (Excel compatible)
- Semua data peserta
- Custom field selection

**🎫 Resend Ticket**
- Kirim ulang tiket hilang
- Individual atau bulk

**Catatan Presenter:**
- Highlight CRM capabilities
- 3 menit

---

# SLIDE 19: SISTEM PELAPORAN

## Laporan Lengkap & Akurat

```
LAPORAN TERSEDIA
═══════════════════════════════════

📊 LAPORAN PENJUALAN
┌────────────────────────────────┐
│ Total Pendapatan: Rp 142.500.000│
│ Total Tiket:      567 terjual  │
│                                │
│ Metode Pembayaran:             │
│ • Kartu Kredit:   234 (41%)   │
│ • Virtual Account: 189 (33%)   │
│ • E-wallet:       123 (22%)   │
│ • Tunai/POS:       21 (4%)    │
└────────────────────────────────┘

📋 LAPORAN PESERTA
┌────────────────────────────────┐
│ Total Terdaftar:  567          │
│ Checked-in:       443 (78%)    │
│ Tidak Hadir:      124 (22%)    │
│                                │
│ Per Jenis Tiket:               │
│ • VIP:     120 peserta        │
│ • Regular: 327 peserta        │
│ • Pelajar: 120 peserta        │
└────────────────────────────────┘

💰 LAPORAN KEUANGAN
┌────────────────────────────────┐
│ Penjualan Kotor:   Rp 142.5 Jt│
│ Biaya Platform:    Rp   7.1 Jt│
│ Payment Gateway:   Rp   4.3 Jt│
│ Pendapatan Bersih: Rp 131.1 Jt│
│                                │
│ Status: ✅ Siap dibayar        │
└────────────────────────────────┘
```

### Format Export:
- 📄 CSV (Excel)
- 📊 PDF (Print)
- 📧 Email otomatis
- 📅 Jadwal otomatis

**Catatan Presenter:**
- Show sample reports
- Highlight actionable insights
- 3 menit

---

# SLIDE 20: TIKET QR CODE

## Tiket Digital Profesional

```
┌─────────────────────────────────┐
│  ╔═══════════════════════════╗ │
│  ║   🎫 BSC TIKET           ║ │
│  ║                           ║ │
│  ║   Festival Musik Jakarta  ║ │
│  ║   Sabtu, 20 Jan 2026      ║ │
│  ║   19:00 WIB               ║ │
│  ║                           ║ │
│  ║   TIKET VIP               ║ │
│  ║   Budi Santoso            ║ │
│  ║                           ║ │
│  ║   ┌───────────────┐       ║ │
│  ║   │  [QR CODE]    │       ║ │
│  ║   │  █▀▀▀█ █▀█    │       ║ │
│  ║   │  █   █ ▀▀     │       ║ │
│  ║   │  █▄▄▄█ █▄▀    │       ║ │
│  ║   └───────────────┘       ║ │
│  ║                           ║ │
│  ║   #BSC-2025-1234         ║ │
│  ╚═══════════════════════════╝ │
└─────────────────────────────────┘
```

### Fitur Tiket:

✅ **Unique QR code** per tiket
✅ **Design profesional** & branded
✅ **Multi-format:**
   - PDF (email attachment)
   - Mobile display
   - Print-ready

✅ **Keamanan:**
   - Encrypted QR
   - Cannot duplicate
   - Real-time validation

✅ **Delivery:**
   - Email otomatis
   - Download dari dashboard
   - Resend kapan saja

**Catatan Presenter:**
- Show real ticket sample
- Emphasize security
- 2 menit
- Closing: "Ini mengakhiri Part 2. Di Part 3 terakhir, kita akan bahas use cases, keunggulan kompetitif, dan penutup."

---

## 📌 AKHIR PART 2

**Slide yang telah dibahas di Part 2:**
- ✅ Scanner System
- ✅ Multi-Organization Detail
- ✅ Payment Gateway (Midtrans & Xendit - 18+ metode)
- ✅ Fitur Cerdas (Timer, Inventori, Notifikasi, Sync)
- ✅ Dashboard Admin
- ✅ Dashboard Organizer Detail
- ✅ Manajemen Peserta & CRM
- ✅ Sistem Pelaporan Lengkap
- ✅ Tiket QR Code

**Lanjut ke Part 3:**
- Jenis Event yang Didukung
- Use Cases (3 industri)
- 10 Keunggulan Kompetitif
- Multi-Device Access
- Proses Implementasi
- Penutup & Call to Action

---

**BSC Tiket - Presentasi Part 2**  
*20 dari 28 Slide*  
*Version: 2.1*  
*Date: 2025-11-17*
