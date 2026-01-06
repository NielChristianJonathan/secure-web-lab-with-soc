PROJECT CONTEXT — Secure Web Lab + SOC Monitoring

Background:
Saya adalah mahasiswa IT yang sedang membangun Secure Web Lab
dengan fokus Web Security dan SOC Monitoring (logging & detection).

Tujuan Project:
- Membangun REST API yang aman
- Logging aktivitas user (audit trail)
- Deteksi anomali (SOC-style)
- Menjadi portfolio Web Security / SOC Engineer

Tech Stack:
- Python
- Flask
- MySQL
- VS Code
- Git & GitHub
- OS: Windows (Anaconda Python)

Progress Saat Ini:
1. Sudah memahami konsep client-server & HTTP
2. Membuat Flask REST API
3. Menggunakan MySQL sebagai database
4. Membuat tabel logs:
   - ip
   - method
   - endpoint
   - status_code
   - user_agent
   - timestamp
5. Implementasi logging otomatis menggunakan after_request middleware
6. Menggunakan environment variable (.env) untuk credential DB
7. Project dijalankan secara lokal di VS Code

Struktur Project:
secure-web-lab/
- app.py
- requirements.txt
- .env
- .gitignore
- README.md

Masalah Teknis Terakhir:
- Error menjalankan python di PowerShell karena salah path
- Solusi: jalankan dengan `python app.py` atau python.exe Anaconda

Langkah Selanjutnya (BELUM DILAKUKAN):
1. Implementasi authentication (login)
2. Password hashing (bcrypt)
3. Log login gagal
4. Deteksi brute-force (alert SOC)
5. Dashboard monitoring (Vue.js)

Catatan:
- Fokus project ini adalah SECURITY & SOC, bukan sekadar CRUD
- Semua fitur dibuat kecil, realistis, dan bisa dieksploitasi lalu diperbaiki
