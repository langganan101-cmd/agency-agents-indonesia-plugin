# Agency Agents ID — Plugin ChatGPT/Codex

Plugin Skills berbahasa Indonesia yang dikurasi dari proyek [Agency Agents](https://github.com/msitarzewski/agency-agents) dan menggunakan referensi terjemahan komunitas [agency-agents-id](https://github.com/jnMetaCode/agency-agents-id).

## Isi paket

- `pengembangan-produk` — discovery, PRD, roadmap, dan validasi.
- `pengembangan-frontend` — implementasi UI, aksesibilitas, responsivitas, dan performa.
- `arsitektur-backend` — API, database, keamanan, reliabilitas, dan operasi.
- `audit-keamanan` — threat modeling dan penilaian keamanan defensif.
- `tinjauan-kode` — review perubahan kode berbasis bukti.
- `strategi-pertumbuhan` — funnel, akuisisi, retensi, dan eksperimen.
- `quality-gate` — verifikasi QA dan kesiapan rilis.
- `host-workspace-operator` — aturan aman untuk operasi file/repository melalui host.

## Instalasi

Paket ini menggunakan format portable Agent Plugins: `plugin.json` berada di root, sedangkan Skill ditemukan otomatis dari folder `skills/`. Unggah ZIP melalui alur impor yang tersedia di host atau gunakan sebagai sumber plugin lokal sesuai dokumentasi ChatGPT/Codex. Paket ini tidak menyertakan MCP server dan tidak meminta kredensial.

## Catatan

- Ini adalah kurasi workflow, bukan ekspor satu Skill untuk setiap persona dalam repository sumber.
- Semua tindakan workspace bergantung pada tool dan izin yang benar-benar tersedia di host.
- Belum dilakukan pengujian instalasi pada akun ChatGPT/Codex atau pengajuan ke Plugin Directory.
- Identitas penerbit dan detail legal tambahan harus diverifikasi sebelum pengajuan publik.
