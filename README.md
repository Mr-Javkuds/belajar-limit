# 📘 Limit Fungsi Aljabar — Modul Interaktif Lengkap

Modul interaktif berbasis **HTML + Tailwind + Chart.js** untuk mempelajari **konsep limit fungsi aljabar** secara visual.  
Dilengkapi teori, langkah aljabar otomatis, grafik interaktif, dan kuis acak dengan ekspor hasil dalam format JSON.

---

## 🚀 Deskripsi Singkat
File **`limit.html`** merupakan modul pembelajaran yang mencakup:
- Definisi dan bentuk tak tentu limit fungsi aljabar  
- Metode penyelesaian (substitusi, faktorisasi, rasionalisasi, trigonometri)  
- Visualisasi grafik dinamis berbasis **Chart.js v4.4.0**  
- **Langkah-langkah aljabar otomatis** untuk fungsi umum  
- **Latihan & kuis adaptif** (mudah, sedang, sulit) dengan skor instan  
- **Ekspor hasil kuis** ke file `soal_limit.json`  

---

## 🧩 Fitur Utama
✅ Visualisasi limit interaktif  
✅ Slider nilai `x` dan titik limit `a`  
✅ Grafik dinamis dengan garis vertikal otomatis  
✅ Langkah penyelesaian aljabar ditampilkan otomatis  
✅ Kuis acak tiga level dengan feedback langsung  
✅ Ekspor data JSON dan tombol reset modul  
✅ Dukungan **MathJax** untuk LaTeX  
✅ Desain responsif dan ringan (TailwindCSS CDN)

---

## 🛠️ Cara Penggunaan
1. Unduh atau salin file **`limit.html`**  
2. Buka di browser modern (Chrome / Firefox / Edge)  
3. Pilih contoh fungsi dari dropdown  
4. Atur nilai `x` melalui slider untuk melihat perubahan fungsi  
5. Tekan tombol **Generate Soal** untuk membuat kuis otomatis  
6. Klik **Ekspor Soal (JSON)** untuk menyimpan hasil latihan  

---

## 💡 Contoh Aktivitas
**Contoh 1 — Faktorisasi**
\[
\lim_{x \to 2} \frac{x^2 - 4}{x - 2} = 4
\]  
Langkah:
1. Faktorkan \(x^2 - 4 = (x-2)(x+2)\)  
2. Sederhanakan → \(f(x) = x + 2\)  
3. Substitusi \(x = 2\) → hasil 4  

**Contoh 2 — Rasionalisasi**
\[
\lim_{x \to 4} \frac{\sqrt{x} - 2}{x - 4} = \frac{1}{4}
\]  

---

## 🧮 Teknologi yang Digunakan
| Teknologi | Fungsi |
|------------|--------|
| **HTML5** | Struktur dan interaktivitas modul |
| **TailwindCSS CDN** | Styling responsif |
| **Chart.js v4.4.0** | Visualisasi grafik fungsi |
| **MathJax v3** | Render ekspresi matematika |
| **JavaScript DOM API** | Logika interaktif dan kuis |

---

## 📤 Integrasi & Ekspor
Tekan **Ekspor Soal (JSON)** → akan menghasilkan file seperti:
```json
[
  {
    "soal": "lim x→2 (x²−4)/(x−2)",
    "jawaban_benar": "4",
    "level": "mudah"
  }
]
