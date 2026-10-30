# Senarai Prompt Motion Claude [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md) · **Bahasa Melayu**

> Prompt yang kami tulis untuk Claude bagi menghasilkan motion graphic pendek untuk reel: kapsyen kinetik, pembuka jenama, carta bergerak, peralihan dan demo aplikasi. Setiap prompt dipapar bersama video yang dihasilkannya. Di bawahnya, alat motion sumber terbuka dipangkat ikut bintang dan aktiviti terkini, dikemas setiap minggu.

Tampal prompt ke dalam Claude seperti sedia ada, kemudian tukar perkataan, warna dan nombor kepada milik anda. Setiap pratonton dirender dengan HyperFrames daripada kod yang ditulis oleh sesi Claude baharu yang hanya diberi prompt bahasa Inggeris dan nota ringkas tentang tempat menyimpan fail.

## Kandungan

- [Teks kinetik dan kapsyen reel](#teks-kinetik-dan-kapsyen-reel)
  - [Kapsyen sorot perkataan demi perkataan](#kapsyen-sorot-perkataan-demi-perkataan)
  - [Tajuk bertindan menghentak](#tajuk-bertindan-menghentak)
  - [Cangkuk mesin taip dengan sapuan penanda](#cangkuk-mesin-taip-dengan-sapuan-penanda)
- [Pembuka dan penutup jenama](#pembuka-dan-penutup-jenama)
  - [Logo dilukis garis demi garis](#logo-dilukis-garis-demi-garis)
  - [Pembuka episod dengan letusan bentuk](#pembuka-episod-dengan-letusan-bentuk)
  - [Kad penutup untuk ikut akaun](#kad-penutup-untuk-ikut-akaun)
- [Carta dan nombor bergerak](#carta-dan-nombor-bergerak)
  - [Statistik mengira dengan cip pertumbuhan](#statistik-mengira-dengan-cip-pertumbuhan)
  - [Carta bar bulanan yang membesar](#carta-bar-bulanan-yang-membesar)
  - [Peratus cincin donat](#peratus-cincin-donat)
- [Peralihan dan latar](#peralihan-dan-latar)
  - [Sapuan jalur pepenjuru](#sapuan-jalur-pepenjuru)
  - [Riak grid titik di belakang tajuk bab](#riak-grid-titik-di-belakang-tajuk-bab)
- [Demo produk dan aplikasi](#demo-produk-dan-aplikasi)
  - [Demo ketik aplikasi](#demo-ketik-aplikasi)
  - [Notifikasi pesanan bertindan](#notifikasi-pesanan-bertindan)
  - [Demo menaip di bar carian](#demo-menaip-di-bar-carian)
- [Pemapar kod ke video](#pemapar-kod-ke-video)
- [Pustaka animasi web](#pustaka-animasi-web)
- [Skil dan templat Claude](#skil-dan-templat-claude)
- [Tanpa setup](#tanpa-setup)
- [Dibuatkan untuk anda](#dibuatkan-untuk-anda)
- [Cara pangkat dikira](#cara-pangkat-dikira)
- [Bekerja dengan Sasa Teguh](#bekerja-dengan-sasa-teguh)

## Teks kinetik dan kapsyen reel

### Kapsyen sorot perkataan demi perkataan

```text
Buat video menegak 6 saat, 1080 x
1920, yang memaparkan kapsyen reel
mengikut rentak percakapan.

Ayatnya: "Ramai orang berhenti
seminggu sebelum usaha mereka mula
menjadi."

Papar tiga atau empat perkataan
pada satu masa di sepertiga bawah,
dalam fon sistem sans-serif tebal
kira-kira 88 px, putih dengan
bayang gelap lembut, atas latar
arang dengan gradien menegak yang
halus.

Rentaknya kira-kira dua setengah
perkataan sesaat. Perkataan yang
sedang disebut bertukar kuning dan
membesar 10 peratus dengan
ease-out pantas, kemudian kembali
biasa bila perkataan seterusnya
bermula.

Setiap kumpulan perkataan naik 30
px ke tempatnya semasa muncul dan
pudar sebelum kumpulan seterusnya.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/kapsyen-sorot/pratonton.gif" alt="Pratonton: Kapsyen sorot perkataan demi perkataan" width="270">

[Video (MP4)](contoh/kapsyen-sorot/hasil.mp4) · [Kod sumber](contoh/kapsyen-sorot)

### Tajuk bertindan menghentak

```text
Buat video menegak 5 saat, 1080 x
1920, dengan tajuk tiga baris atas
latar hampir hitam.

Barisnya "Berhenti", "posting" dan
"ikut suka", bertindan dan di
tengah, dalam fon sistem
sans-serif tebal yang sempit dan
memenuhi kira-kira 80 peratus
lebar.

Setiap baris menghentak masuk 0.4
saat selepas baris sebelumnya:
bermula pada skala 140 peratus dan
mendarat pada 100 peratus dengan
sedikit lajakan. Selang-selikan
warna putih, oren, putih.

Bila baris terakhir mendarat,
goncang seluruh blok sekali dengan
pendek beberapa piksel, kemudian
tahan.

Pada saat terakhir, lukis garis
bawah oren dari kiri ke kanan di
bawah "ikut suka".

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/tajuk-hentak/pratonton.gif" alt="Pratonton: Tajuk bertindan menghentak" width="270">

[Video (MP4)](contoh/tajuk-hentak/hasil.mp4) · [Kod sumber](contoh/tajuk-hentak)

### Cangkuk mesin taip dengan sapuan penanda

```text
Buat video menegak 6 saat, 1080 x
1920, yang menaip ayat pembuka
atas latar krim hangat.

Taip "Ini perkara yang tiada siapa
beritahu tentang menyimpan duit"
huruf demi huruf pada rentak tetap
dalam fon sistem monospace, coklat
gelap, kira-kira 72 px, dibalut
kepada tiga atau empat baris di
tengah, dengan kursor teks
berkelip di hujung.

Bila menaip selesai, sapu sorotan
penanda kuning lut cahaya dari
kiri ke kanan di belakang
perkataan "tiada siapa beritahu",
seolah-olah dilukis dengan tangan,
tepinya sedikit tidak rata.

Tahan bingkai akhir pada saat
terakhir sementara kursor terus
berkelip.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/mesin-taip-sorot/pratonton.gif" alt="Pratonton: Cangkuk mesin taip dengan sapuan penanda" width="270">

[Video (MP4)](contoh/mesin-taip-sorot/hasil.mp4) · [Kod sumber](contoh/mesin-taip-sorot)

## Pembuka dan penutup jenama

### Logo dilukis garis demi garis

```text
Buat video menegak 5 saat, 1080 x
1920, yang memperkenalkan logo
sebuah kedai kopi rekaan bernama
"Kopi Senja".

Bina logo sebagai SVG sebaris:
satu bulatan dengan garis luar
cawan kopi yang ringkas di
dalamnya dan dua garis wap
melengkung di atas cawan.

Untuk 1.5 saat pertama, lukis
setiap garis seolah-olah dengan
pen, menggunakan stroke dash
offset beranimasi, dalam warna
coklat hangat atas latar putih
pudar.

Kemudian isi bulatan dengan oren
pekat dan tukar garis menjadi
krim, dalam 0.4 saat.

Selepas itu, munculkan nama "Kopi
Senja" huruf demi huruf di bawah
logo dalam fon sistem serif,
diikuti baris kecil "Sejak 2019".

Guna HTML, CSS, SVG sebaris dan
fon sistem sahaja, tanpa imej,
ikon atau fon dari luar.
```

<img src="contoh/logo-garis/pratonton.gif" alt="Pratonton: Logo dilukis garis demi garis" width="270">

[Video (MP4)](contoh/logo-garis/hasil.mp4) · [Kod sumber](contoh/logo-garis)

### Pembuka episod dengan letusan bentuk

```text
Buat video menegak 5 saat, 1080 x
1920, untuk pembuka satu episod
siri pendek.

Mula dengan skrin biru laut gelap
yang kosong. Pada 0.2 saat,
kira-kira dua puluh bentuk kecil
(bulatan, segi empat dan segi tiga
dalam warna koral, pudina dan
pasir) meletus keluar dari tengah,
berpusing sambil bergerak dan
perlahan dengan ease-out.

Pada 1.8 saat, tarik semua bentuk
kembali ke tengah lalu bercantum
menjadi satu segi empat bersudut
bulat berwarna koral.

Dalam segi empat itu, naikkan teks
"Episod 12" dalam huruf kecil dan
"Menetapkan harga produk pertama"
dalam fon sistem sans-serif tebal
yang besar, putih.

Tahan kad tajuk pada saat
terakhir.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/pembuka-bentuk/pratonton.gif" alt="Pratonton: Pembuka episod dengan letusan bentuk" width="270">

[Video (MP4)](contoh/pembuka-bentuk/hasil.mp4) · [Kod sumber](contoh/pembuka-bentuk)

### Kad penutup untuk ikut akaun

```text
Buat video menegak 6 saat, 1080 x
1920, sebagai kad penutup sebuah
reel.

Atas latar ungu muda yang lembut,
besarkan masuk satu bulatan 280 px
lebar berwarna ungu pekat dengan
huruf awal "NA" berwarna putih,
kemudian luncurkan nama "Nadia
Aziz" dan nama akaun "@akaunanda"
di bawahnya.

Pada 2 saat, munculkan butang
bujur bersudut bulat bertulis
"Ikut untuk bahagian 2", teks
putih atas ungu pekat.

Denyutkan butang itu dua kali
dengan lembut, dan lukis anak
panah melengkung yang menunjuk ke
arahnya dari sisi.

Pada saat terakhir, munculkan satu
baris kecil di bawah: "Video
baharu setiap Selasa".

Guna HTML, CSS, SVG sebaris dan
fon sistem sahaja, tanpa imej,
ikon atau fon dari luar.
```

<img src="contoh/kad-penutup/pratonton.gif" alt="Pratonton: Kad penutup untuk ikut akaun" width="270">

[Video (MP4)](contoh/kad-penutup/hasil.mp4) · [Kod sumber](contoh/kad-penutup)

## Carta dan nombor bergerak

### Statistik mengira dengan cip pertumbuhan

```text
Buat video menegak 5 saat, 1080 x
1920, yang membentangkan satu
statistik atas latar hijau tua.

Di tengah, kira satu nombor besar
dari 0 hingga 12,480 dalam 2 saat
dengan ease-out, guna pemisah ribu
dan digit jadual supaya lebarnya
tidak melompat, dalam fon sistem
sans-serif tebal kira-kira 180 px,
putih.

Bila kiraan selesai, munculkan
label "pengikut dalam 30 hari" di
bawahnya.

Kemudian luncurkan cip kecil
bersudut bulat dari kanan yang
tertulis "+38%" dengan segi tiga
menghala ke atas, dalam hijau
muda.

Anggap setiap nombor sebagai
contoh yang akan ditukar penonton.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/kaunter-statistik/pratonton.gif" alt="Pratonton: Statistik mengira dengan cip pertumbuhan" width="270">

[Video (MP4)](contoh/kaunter-statistik/hasil.mp4) · [Kod sumber](contoh/kaunter-statistik)

### Carta bar bulanan yang membesar

```text
Buat video menegak 6 saat, 1080 x
1920, dengan carta empat bar
jualan bulanan atas latar putih
pudar.

Tajuk di atas: "Jualan, Januari
hingga April", kelabu gelap, fon
sistem sans-serif tebal.

Barnya Januari 12k, Februari 18k,
Mac 9k dan April 27k, dalam biru
lembut dengan hujung atas bulat,
dilabel dengan nama bulan di
bawah.

Besarkan bar dari sifar satu demi
satu, 0.35 saat jaraknya, setiap
satu dengan sedikit lajakan,
sementara nilai di atas setiap bar
mengira naik bersamanya.

Bila keempat-empatnya sudah naik,
tukar bar April menjadi koral dan
munculkan nota pendek di atasnya:
"+50% berbanding Februari".

Pastikan setiap label dan nota itu
berada sepenuhnya dalam bingkai,
sekurang-kurangnya 60 px dari
setiap tepi.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/carta-bar/pratonton.gif" alt="Pratonton: Carta bar bulanan yang membesar" width="270">

[Video (MP4)](contoh/carta-bar/hasil.mp4) · [Kod sumber](contoh/carta-bar)

### Peratus cincin donat

```text
Buat video menegak 5 saat, 1080 x
1920, berpusatkan satu peratus
atas latar batu loh gelap.

Lukis cincin donat 600 px lebar
dengan trek kelabu yang tebal.
Dalam 2 saat, isi cincin mengikut
arah jam dari atas hingga 73
peratus dalam warna teal, dengan
ease-in-out, sementara nombor di
tengah mengira dari 0 hingga 73
dengan tanda peratus.

Selepas cincin berhenti, munculkan
kapsyen dua baris di bawahnya:
"pembeli membaca ulasan" dan,
lebih kecil, "sebelum membayar".

Akhiri dengan denyutan cahaya
kecil di hujung lengkok teal.

Anggap nombor dan teks sebagai
contoh.

Guna HTML, CSS, SVG sebaris dan
fon sistem sahaja, tanpa imej,
ikon atau fon dari luar.
```

<img src="contoh/donat-peratus/pratonton.gif" alt="Pratonton: Peratus cincin donat" width="270">

[Video (MP4)](contoh/donat-peratus/hasil.mp4) · [Kod sumber](contoh/donat-peratus)

## Peralihan dan latar

### Sapuan jalur pepenjuru

```text
Buat video menegak 4 saat, 1080 x
1920, yang beralih antara dua kad
tajuk dengan sapuan pepenjuru.

Kad pertama: latar kelabu dengan
perkataan "Sebelum" dalam teks
gelap yang besar. Kad kedua: latar
teal dengan perkataan "Selepas"
dalam teks putih yang besar, fon
sistem sans-serif tebal.

Papar kad pertama selama 1.5 saat.
Kemudian sapu tiga jalur lebar
yang selari (kuning, koral,
kemudian teal) secara pepenjuru
merentas bingkai dari kiri bawah
ke kanan atas, setiap satu bermula
0.08 saat selepas yang sebelumnya,
setiap satu melintas dalam
kira-kira 0.6 saat dengan
ease-in-out.

Jalur terakhir meninggalkan kad
kedua di belakangnya. Tahan kad
kedua hingga akhir.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/sapuan-pepenjuru/pratonton.gif" alt="Pratonton: Sapuan jalur pepenjuru" width="270">

[Video (MP4)](contoh/sapuan-pepenjuru/hasil.mp4) · [Kod sumber](contoh/sapuan-pepenjuru)

### Riak grid titik di belakang tajuk bab

```text
Buat video menegak 6 saat, 1080 x
1920, dengan tajuk bab di atas
grid titik yang bergerak.

Penuhi bingkai dengan grid titik
kecil, 12 melintang dan 21
menegak, dalam biru lembut atas
latar biru sangat gelap.

Hantar riak melalui grid dari
sudut kiri bawah: setiap titik
membesar dan menjadi terang bila
gelombang sampai kepadanya,
kemudian mengecil semula, dengan
kelewatan ikut jaraknya dari sudut
itu. Jalankan dua gelombang, 2.5
saat jaraknya.

Pada 1 saat, munculkan "Bab 2"
dalam huruf besar kecil yang
berjarak dan "Mendapat sepuluh
pelanggan pertama" dalam fon
sistem sans-serif tebal yang
besar, putih, di tengah atas grid.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/grid-titik/pratonton.gif" alt="Pratonton: Riak grid titik di belakang tajuk bab" width="270">

[Video (MP4)](contoh/grid-titik/hasil.mp4) · [Kod sumber](contoh/grid-titik)

## Demo produk dan aplikasi

### Demo ketik aplikasi

```text
Buat video menegak 6 saat, 1080 x
1920, yang menunjukkan satu
tindakan dalam aplikasi senarai
tugasan yang ringkas.

Di tengah, lukis garis luar
telefon dengan CSS: segi empat
bersudut bulat kira-kira 760 x
1560 px dengan bingkai gelap. Di
dalamnya, papar skrin aplikasi
cerah bertajuk "Hari ini" dengan
dua tugasan sedia ada.

Pada 1 saat, penanda sentuhan
bulat lut cahaya meluncur ke
butang "Tambah tugasan" di bawah
dan mengetiknya, dengan riak
pendek.

Baris tugasan baharu, "Hantar
sebut harga kepada Aina", meluncur
masuk di atas senarai dan menolak
yang lain ke bawah.

Pada 4 saat, penanda mengetik
kotak semak baris baharu itu:
kotak terisi hijau, tanda betul
melukis dirinya, dan teksnya
dipotong dengan garisan.

Guna HTML, CSS, SVG sebaris dan
fon sistem sahaja, tanpa imej,
ikon atau fon dari luar.
```

<img src="contoh/demo-ketik/pratonton.gif" alt="Pratonton: Demo ketik aplikasi" width="270">

[Video (MP4)](contoh/demo-ketik/hasil.mp4) · [Kod sumber](contoh/demo-ketik)

### Notifikasi pesanan bertindan

```text
Buat video menegak 5 saat, 1080 x
1920, yang menunjukkan pagi yang
baik sebuah kedai kecil melalui
notifikasi telefon.

Atas skrin kunci yang nampak
kabur, dibuat daripada gradien
biru lembut ke ungu, papar masa
"9:41" di atas dalam fon sistem
nipis yang besar.

Jatuhkan tiga kad notifikasi dari
atas, satu setiap 0.9 saat:
"Pesanan baharu #1042", "Bayaran
diterima RM 89.00" dan "Pesanan
#1042 dihantar".

Setiap kad putih padu, bersudut
bulat, dengan segi empat kecil
berwarna sebagai tanda aplikasi
dan cap masa "baru". Bila kad
baharu tiba, kad lama meluncur ke
bawah dan mengecil sedikit di
belakangnya, sehingga hanya jalur
nipis setiap satu kelihatan di
bawah kad terbaharu, seperti
timbunan sebenar.

Guna HTML, CSS dan fon sistem
sahaja, tanpa imej, ikon atau fon
dari luar.
```

<img src="contoh/notifikasi-bertindan/pratonton.gif" alt="Pratonton: Notifikasi pesanan bertindan" width="270">

[Video (MP4)](contoh/notifikasi-bertindan/hasil.mp4) · [Kod sumber](contoh/notifikasi-bertindan)

### Demo menaip di bar carian

```text
Buat video menegak 6 saat, 1080 x
1920, yang menunjukkan seseorang
mencari dalam aplikasi ringkas.

Berhampiran bahagian atas skrin
putih, lukis bar carian bersudut
bulat dengan kanta pembesar yang
dibuat dengan CSS atau SVG
sebaris.

Taip "nasi lemak dekat sini" ke
dalam bar, satu huruf pada satu
masa, dengan kursor berkelip.

Selepas perkataan ketiga, buka
senarai cadangan tiga baris di
bawah bar; yang kedua, "nasi lemak
dekat sini buka sekarang", disorot
seolah-olah tetikus di atasnya,
kemudian dipilih.

Senarai cadangan tertutup dan tiga
kad hasil meluncur naik dari bawah
satu demi satu, setiap satu dengan
segi empat berwarna sebagai
pemegang tempat, nama kedai,
penarafan bintang yang dilukis
dengan teks dan jarak seperti "0.8
km".

Guna HTML, CSS, SVG sebaris dan
fon sistem sahaja, tanpa imej,
ikon atau fon dari luar.
```

<img src="contoh/carian-taip/pratonton.gif" alt="Pratonton: Demo menaip di bar carian" width="270">

[Video (MP4)](contoh/carian-taip/hasil.mp4) · [Kod sumber](contoh/carian-taip)

## Pemapar kod ke video

- [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) - ★ 75.9k+ · Apache-2.0 · 2026-10 — Write HTML. Render video. Built for agents.
- [3b1b/manim](https://github.com/3b1b/manim) - ★ 95.9k+ · MIT · 2026-09 — Animation engine for explanatory math videos.
- [remotion-dev/remotion](https://github.com/remotion-dev/remotion) - ★ 69k+ · lesen lain · 2026-10 — 🎥 Make videos programmatically with React.
- [ManimCommunity/manim](https://github.com/ManimCommunity/manim) - ★ 42k+ · MIT · 2026-10 — A community-maintained Python framework for creating mathematical animations.
- [motion-canvas/motion-canvas](https://github.com/motion-canvas/motion-canvas) - ★ 19.5k+ · MIT · 2026-07 — Visualize Your Ideas With Code.
- [dmtrKovalenko/fframes](https://github.com/dmtrKovalenko/fframes) - ★ 3k+ · MIT · 2026-10 — programmatic video rendering framework that is actually fast.
- [midrender/revideo](https://github.com/midrender/revideo) - ★ 4.1k+ · MIT · 2026-07 — Create Videos with Code.
- [nexu-io/html-video](https://github.com/nexu-io/html-video) - ★ 4.7k+ · Apache-2.0 · 2026-06 — Programmatic video for coding agents — HTML to video on your laptop. Turn HTML, CSS & data into real MP4s with pluggable render engines, 21 templates, AI soundtrack. Apache-2.0, no per-render fees. An official project by the Open Design team.
- [BintzGavin/helios](https://github.com/BintzGavin/helios) - ★ 120+ · Apache-2.0 · 2026-10 — Programmatic video creation with web technologies you already know. CSS animations just work.

## Pustaka animasi web

- [juliangarnier/anime](https://github.com/juliangarnier/anime) - ★ 74k+ · MIT · 2026-08 — JavaScript animation engine.
- [motiondivision/motion](https://github.com/motiondivision/motion) - ★ 34.6k+ · MIT · 2026-10 — A modern animation library for React and JavaScript.
- [mojs/mojs](https://github.com/mojs/mojs) - ★ 18.8k+ · MIT · 2026-07 — The motion graphics toolbelt for the web.

## Skil dan templat Claude

- [latent-spaces/brag](https://github.com/latent-spaces/brag) - ★ 19.6k+ · MIT · 2026-10 — You built it. Now brag. Turn the project you just created into a short, shareable launch video with one command.
- [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) - ★ 15.1k+ · Apache-2.0 · 2026-10 — AI video skill for Claude Code & Codex — cinematic, editable product promos with Remotion: 124 shot recipe cards, 150 motion previews, beat sync, sound design, Motion Workbench & JianYing (CapCut CN) export.
- [digitalsamba/claude-code-video-toolkit](https://github.com/digitalsamba/claude-code-video-toolkit) - ★ 2.3k+ · MIT · 2026-10 — AI-native video production toolkit for Claude Code.
- [LottieFiles/motion-design-skill](https://github.com/LottieFiles/motion-design-skill) - ★ 2.6k+ · MIT · 2026-05 — Universal motion design principles for AI agents — timing, easing, choreography, and Disney animation principles adapted for UI.
- [haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill) - ★ 730 · MIT · 2026-08 — Open-source Claude agent skill that teaches Claude Code, Claude Desktop & Claude AI to create and edit professional motion graphics videos with Remotion. AI video editing, B-roll, captions, sound design — from one prompt.
- [Sunwood-ai-labs/hyperframes-motion-reel-skill](https://github.com/Sunwood-ai-labs/hyperframes-motion-reel-skill) - ★ 160 · MIT · 2026-09 — 🎬 Claude Code skill for showreel-grade, beat-synced motion graphics with HyperFrames (HTML + GSAP + SVG + Canvas, Apache-2.0) — 120 BPM / 60 FPS to MP4.
- [jhartquist/claude-remotion-kickstart](https://github.com/jhartquist/claude-remotion-kickstart) - ★ 120+ · MIT · 2025-12 — Create videos programmatically with Claude Code and Remotion.

## Tanpa setup

[Cutt](https://cutt.my) ialah connector Claude yang menyunting video talking-head 9:16 dalam Claude: muat naik video, sebut gaya, dan Claude menambah B-roll, ikon dan tipografi kinetik yang mengikut kata-kata anda. Cutt dibina oleh Sasa Teguh, penyelenggara senarai ini.

## Dibuatkan untuk anda

Jika anda mahu motion dibuatkan untuk anda, [hubungi Sasa Teguh](https://sasateguh.com/ms/contact), pasukan yang menyelenggara senarai ini.

## Cara pangkat dikira

Setiap entri ialah repositori GitHub awam. Setiap minggu satu skrip membaca bintang, tolakan terakhir dan lesennya daripada API GitHub, kemudian menyusun setiap kategori mengikut

`skor = 1 × log10(1 + bintang) + 1 × max(0, 1 − hari sejak tolakan terakhir ÷ 365)`

Repositori tidak disenaraikan bila ia diarkib, fork, tiada penerangan, kurang daripada 50 bintang atau tiada tolakan selama 365 hari. Bilangan bintang dibundarkan ke bawah kepada gandaan 10 terdekat. Penerangan ialah penerangan GitHub repositori itu sendiri.

## Bekerja dengan Sasa Teguh

[![Bekerja dengan Sasa Teguh: tempah panggilan](https://raw.githubusercontent.com/sasateguh/.github/main/assets/work-with-sasa-teguh.png)](https://sasateguh.com/ms/book)

Senarai ini diselenggara oleh [Sasa Teguh](https://sasateguh.com/ms), studio di Malaysia. Kami membina laman web yang ditemui di Google dan dalam jawapan AI, dan memasang sistem untuk perniagaan.

hello@sasateguh.com · [Lagi daripada Sasa Teguh](https://github.com/sasateguh)

## Menyumbang

Cadangan dialu-alukan. Lihat [contributing.md](contributing.md).
