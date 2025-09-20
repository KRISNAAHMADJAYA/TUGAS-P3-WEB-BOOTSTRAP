Jadi, kode yang saya bikin ini tuh kayak nge-clone tampilan Instagram versi web. Tapi pakai Bootstrap 5 biar gampang atur layout, terus ada CSS tambahan biar feed foto
ukurannya sama semua. Jadi kalau dibuka di browser, tampilannya udah mirip banget kayak profil IG aslinya. Strukturnya yaitu, ini punya struktur HTML standar dengan
<!DOCTYPE html>, <head>, dan <body>. Di dalam <head>, kita sudah import Bootstrap 5 untuk styling cepat, Bootstrap Icons untuk ikon-ikon Instagram, dan juga CSS custom
buat styling tambahan. Di dalam <body>, kita susun layout mirip aplikasi Instagram: ada header (profil), tab navigasi, feed (foto-foto), dan footer navigasi. 
Lalu ada beberapa bagian-bagian komponen didalamnya yaitu, Head profil ini menampilkan foto profil (fotosaya.jpg) yang berbentuk lingkaran (rounded-circle) dengan ukuran
90x90px, Sebelah kanan foto profil ada statistik akun: jumlah postingan, pengikut, dan mengikuti. Formatnya dibuat flexbox dengan d-flex justify-content-around 
supaya rata secara horizontal, Di bawahnya ada username, nama, dan nickname (krisna, Kriss, @krisna AJ), Lalu ada tombol aksi: Edit profil, Bagikan profil, dan tombol
dengan ikon + orang (tambah teman/follow).Di sini Ada 2 tombol tab navigasi yaitu, Grid (ikon kotak 3x3)"untuk feed foto", Play button"untuk konten video/reels", kita
styling dengan "btn" "btn-dark" "flex-fill" supaya lebar tombol penuh, rata tengah, dan tanpa border. FEED FOTO yaitu, Bagian utama profil: kumpulan foto dalam bentuk
grid (row g-1 dan col-4), Jadi dalam satu baris ada 3 kolom foto (karena col-4 = 12/4 = 3), Kita pakai 12 gambar dummy (Upin Ipin, BoBoiBoy, Bromo, dll), Tambahan CSS
di <style> memastikan semua foto punya ukuran sama (500x300px) dan object-fit: cover supaya gambarnya tetap proporsional tanpa ketarik aneh-aneh. Footer Navigasi yaitu, 
Footer diposisikan fixed di bawah layar dengan "position-fixed bottom-0 w-100", Ada 4 ikon: Home, Search, Add, Reels, plus foto profil kecil di kanan bawah, Latar footer
hitam (bg-black), mirip dengan style Instagram dark mode. Jadi kesimpulannya yaitu,  Kode ini bikin tampilan profil Instagram sederhana dengan Bootstrap dan CSS,
hasilnya mirip IG asli lengkap dengan header, feed foto rapi, dan navigasi bawah.
