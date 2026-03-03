# Lab 7 - Pemrograman Web 2 (Framework CodeIgniter 4)

Repositori ini berisi hasil Praktikum 1 pada mata kuliah Pemrograman Web 2, yang berfokus pada pengenalan Framework PHP **CodeIgniter 4 (CI4)** dengan konsep **MVC (Model-View-Controller)**.

## Identitas
* **Nama:** Abdi Putra Perdana
* **NIM:** 312410426
* **Kelas:** I241C

## Persiapan
1.  Mengaktifkan ekstensi PHP di `php.ini` (XAMPP):
    - `php-json`
    - `php-mysqlnd`
    - `php-xml`
    - `php-intl`
    - `mbstring`
2.  Konfigurasi `.env` untuk mode development:
    ```env
    CI_ENVIRONMENT = development
    ```

## Langkah Praktikum
1.  **Instalasi CI4:** Melakukan instalasi manual di folder `htdocs/lab11_php_ci`.
2.  **Membuat Controller:** Membuat file `Page.php` untuk menangani navigasi halaman (About, Contact, FAQs, Artikel).
3.  **Konfigurasi Routing:** Mengatur rute URL di `app/Config/Routes.php`.
4.  **Membuat Layout (Template):** Membagi tampilan menjadi `header.php` dan `footer.php` agar desain konsisten di semua halaman.
5.  **Membuat View:** Implementasi file view untuk setiap menu menggunakan perintah `$this->include()`.

## Tugas: Melengkapi Menu Navigasi
Tugas praktikum ini adalah memastikan semua link pada navigasi (Home, Artikel, About, Contact, FAQ) bekerja dengan layout yang seragam.

### Struktur File yang Dikerjakan:
- `app/Controllers/Page.php`
- `app/Config/Routes.php`
- `app/Views/template/header.php`
- `app/Views/template/footer.php`
- `app/Views/about.php`, `contact.php`, `faqs.php`, `artikel.php`

## Screenshot Hasil

### Halaman About
<img width="1919" height="946" alt="image" src="https://github.com/user-attachments/assets/e3c9c625-f32b-4d61-8c1e-b8b15f090f8a" />

### Halaman Contact
<img width="1919" height="869" alt="image" src="https://github.com/user-attachments/assets/fb613316-36c6-4c7b-b34c-f1072488a489" />

---
© 2026 - Abdi Putra Perdana - Universitas Pelita Bangsa
