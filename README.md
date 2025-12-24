## Information

1. app.blade.php (Sebagai "Kerangka Rumah")
File ini berada di dalam folder layouts. Fungsinya adalah sebagai Master Layout atau kerangka utama website.

Isinya: Hal-hal yang selalu muncul di setiap halaman, seperti tag <head>, link CSS (Bootstrap/Google Fonts), Navbar, dan Footer.

Ciri Khas: Terdapat kode @yield('content'). Kode ini adalah "lubang" atau tempat kosong yang nantinya akan diisi oleh konten dari halaman lain.

2. home.blade.php (Sebagai "Isi Kamar")
File ini adalah halaman spesifik (konten) yang ingin ditampilkan.

Isinya: Hanya fokus pada konten unik halaman home saja (seperti teks "Present your business..." yang ada di gambar kamu).

Ciri Khas: * Dimulai dengan @extends('layouts.app'): Artinya dia meminjam kerangka dari app.blade.php.

Dibungkus dengan @section('content') ... @endsection: Kode di dalam section ini akan otomatis "masuk" ke bagian @yield('content') yang ada di file layout.

## Structure
<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/3488db73-f275-4bdc-a183-a9f35875e56e" />

## Home
<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/c87ac8a4-e0ff-4b0d-b49b-77e649a38a49" />

## Login
<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/68c2888d-cee1-4683-baae-a05697bdb6ed" />

## Admin
<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/36eb81cf-1a68-487b-a707-a875454f65a5" />

