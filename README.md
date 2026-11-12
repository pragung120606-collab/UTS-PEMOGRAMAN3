# Personal Portfolio --- Bayu Pratama Agung

Website portofolio pribadi yang dibuat untuk tugas **UTS Pemrograman
Web**. Website ini memperkenalkan profil, riwayat pendidikan,
pengalaman, keahlian, media perkenalan, dan informasi kontak.

## Daftar Isi

-   [Tentang Proyek](#tentang-proyek)
-   [Fitur Website](#fitur-website)
-   [Teknologi](#teknologi)
-   [Struktur Folder](#struktur-folder)
-   [Cara Menjalankan](#cara-menjalankan)
-   [Menambahkan Audio dan Video](#menambahkan-audio-dan-video)
-   [Bagian Website](#bagian-website)
-   [Screenshot](#screenshot)
-   [Catatan Pengembangan](#catatan-pengembangan)

## Tentang Proyek

Proyek ini merupakan website portofolio sederhana dan responsif. Konten
utamanya berisi:

-   Profil singkat dan biografi.
-   Informasi program studi dan institusi.
-   Riwayat pendidikan.
-   Riwayat pengalaman organisasi/kegiatan.
-   Daftar keahlian teknis dan nonteknis.
-   Pemutar audio dan video perkenalan.
-   Formulir kontak dengan validasi HTML5 dan JavaScript.

## Fitur Website

1.  **Navigasi halaman** --- menu mengarah ke bagian Tentang,
    Pendidikan, Pengalaman, Keahlian, dan Kontak.
2.  **Hero section** --- menampilkan salam pembuka dan pengenalan
    pemilik website.
3.  **Profil pribadi** --- menampilkan biografi dan informasi utama.
4.  **Riwayat pendidikan** --- disajikan dalam tabel.
5.  **Riwayat pengalaman** --- berisi kegiatan organisasi dan
    kepanitiaan.
6.  **Keahlian** --- menampilkan kemampuan HTML, CSS, JavaScript dasar,
    kerja tim, dan kemampuan lainnya.
7.  **Multimedia** --- menyediakan pemutar audio dan video HTML5.
8.  **Formulir kontak** --- memeriksa isian nama, email, subjek, dan
    pesan di browser.
9.  **Tahun otomatis** --- tahun pada footer diperbarui menggunakan
    JavaScript.

> Catatan: formulir kontak saat ini hanya demo front-end. Pesan belum
> dikirim ke email atau server.

## Teknologi

-   **HTML5** untuk struktur dan konten.
-   **CSS3** untuk tampilan, tata letak, dan responsivitas.
-   **JavaScript** untuk interaksi menu, tahun footer, dan validasi
    formulir.
-   **Visual Studio Code** sebagai editor kode.

## Struktur Folder

Pastikan susunan file proyek kurang lebih seperti berikut:

``` text
UTS_Web_1243B_Nama/
├── index.html
├── style.css
├── README.md
├── README.txt                 (jika masih digunakan)
├── images/
│   ├── profil.svg
│   ├── video-poster.svg
│   └── screenshot-website.png (tambahkan screenshot hasil website)
└── media/
    ├── audio.mp3
    └── video.mp4
```

Nama file audio dan video harus sama persis dengan yang dipanggil di
`index.html`. Jika nama file berbeda, ubah alamat pada atribut `src`.

## Cara Menjalankan

1.  Buka folder proyek di Visual Studio Code.
2.  Pastikan `index.html`, `style.css`, folder `images`, dan folder
    `media` berada di lokasi yang benar.
3.  Pastikan file audio dan video sudah dimasukkan ke folder `media`.
4.  Jalankan `index.html` di browser. Disarankan menggunakan ekstensi
    **Live Server**:
    -   Klik kanan `index.html`.
    -   Pilih **Open with Live Server**.
5.  Periksa semua menu, gambar, audio, video, dan formulir kontak.

Website ini merupakan proyek front-end statis sehingga tidak memerlukan
database atau server backend.

## Menambahkan Audio dan Video

Simpan rekaman perkenalan dengan nama berikut:

-   `audio.mp3` di dalam folder `media`.
-   `video.mp4` di dalam folder `media`.

Kode audio pada `index.html`:

``` html
<audio controls preload="none">
  <source src="media/audio.mp3" type="audio/mpeg">
  Browser Anda tidak mendukung pemutar audio.
</audio>
```

Kode video pada `index.html`:

``` html
<video controls preload="metadata" poster="images/video-poster.svg">
  <source src="media/video.mp4" type="video/mp4">
  Browser Anda tidak mendukung pemutar video.
</video>
```

Jika pemutar tidak dapat digunakan, periksa kembali nama file, ekstensi,
dan lokasi folder. Pastikan file video benar-benar berformat MP4 dan
audio benar-benar berformat MP3.

## Bagian Website

  Bagian       Isi
  ------------ ---------------------------------------
  Beranda      Salam pembuka dan pengenalan singkat
  Tentang      Biografi dan informasi pribadi
  Pendidikan   Riwayat pendidikan
  Pengalaman   Pengalaman organisasi dan kepanitiaan
  Keahlian     Keahlian teknis dan nonteknis
  Multimedia   Audio dan video perkenalan
  Kontak       Formulir pesan demo

## Screenshot

### Tampilan editor proyek

Screenshot berikut menunjukkan struktur folder proyek dan bagian kode
multimedia di Visual Studio Code:

![Screenshot editor proyek](images/screenshot-editor.png)

### Tampilan website di browser

Tambahkan screenshot halaman website setelah proyek dijalankan di
browser. Simpan gambar dengan nama `screenshot-website.png` di folder
`images`, kemudian gunakan Markdown berikut:

``` markdown
![Screenshot website](images/screenshot-website.png)
```

**Cara mengambil screenshot website:** 1. Jalankan website di browser.
2. Atur tampilan agar bagian website terlihat rapi. 3. Tekan
`Windows + Shift + S`. 4. Pilih area website yang ingin ditangkap. 5.
Simpan hasilnya sebagai `screenshot-website.png` di folder `images`.

## Catatan Pengembangan

-   Ganti ilustrasi `images/profil.svg` dengan foto profil sendiri jika
    diperlukan.
-   Perbarui data profil, pendidikan, dan pengalaman jika ada perubahan.
-   Pastikan alamat email dan informasi kontak sudah benar sebelum
    website dipublikasikan.
-   Tambahkan screenshot hasil website ke folder `images`.
-   Untuk membuat formulir benar-benar mengirim pesan, diperlukan
    backend atau layanan formulir pihak ketiga.

------------------------------------------------------------------------

**Dibuat oleh:** Bayu Pratama Agung\
**Mata kuliah:** UTS Pemrograman Web\
**Program studi:** Teknik Informatika\
**Institusi:** Universitas Pelita Bangsa
