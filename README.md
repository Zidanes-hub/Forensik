# 🛡️ Digital Forensic Investigation: PT. Membara Bosku Tech Case

Repository ini berisi laporan lengkap dan hasil analisis investigasi digital forensik terhadap barang bukti digital (Flashdisk) dalam kasus sabotase dan rencana pelarian tersangka di PT. Membara Bosku Tech.

## 🕵️ Overview Kasus
Seorang tersangka diduga melakukan pencurian data perusahaan dan berencana melarikan diri. Investigasi ini dilakukan untuk merekonstruksi jejak digital tersangka melalui pemulihan data, analisis aktivitas browser, pelacakan lokasi, dan perbaikan integritas file.

## 🚀 Mission Accomplished
Investigasi ini mencakup 5 misi utama:

1.  **File Recovery:** Memulihkan 13 berkas yang dihapus sengaja oleh tersangka menggunakan **Autopsy**.
2.  **Browser Forensic:** Bedah file database `index.dat` untuk mengungkap riwayat pencarian (Sao Paulo Hotels, Cracking Tools).
3.  **Search Query Analysis:** Menemukan kata kunci spesifik yang digunakan pelaku untuk membobol lisensi perangkat lunak perusahaan.
4.  **Geolocation Analysis:** Melacak koordinat GPS tersembunyi pada metadata foto pemandangan, yang mengarah ke **Arezzo, Italia**.
5.  **Corrupt Header Repair:** Melakukan "operasi" pada file JPEG yang dirusak headernya (`DE AD BE EF`) menggunakan **HxD Hex Editor** untuk mengembalikan akses ke barang bukti.

## 🛠️ Tools Used
* **Autopsy** (Digital Forensics Platform)
* **HxD** (Hex Editor)
* **Exif Viewer / ExifTool** (Metadata Analysis)
* **BrowsingHistoryView** (Browser History Parser)

## 📁 Repository Structure
* `/Laporan`: File laporan akhir (PDF/Word).
* `/Evidence`: Kumpulan file hasil recovery dan file yang telah diperbaiki.
* `/Documentation`: Screenshot proses pengerjaan tiap misi.

---
**Investigator:** Zidanes Surya Nugraha  
*Digital Forensic Analyst Intern*
