
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Judul diperbarui untuk SMP NEGERI 1 WIRADESA -->
    <title>SMP NEGERI 1 WIRADESA - Sekolah Favorit</title> 
    <!-- Memuat Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Konfigurasi Tailwind untuk font dan warna -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary-blue': '#1E3A8A', // Biru Tua
                        'secondary-blue': '#BFDBFE', // Biru Muda
                        'accent-white': '#F9FAFB', // Putih Keabu-abuan
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style>
        /* Menggunakan font Inter secara default */
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        /* Style untuk efek hover pada card */
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        /* Mengatur scrollbar yang lebih halus (optional, hanya untuk estetika) */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-thumb {
            background: #1E3A8A;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <!-- Navbar/Header (Beranda) -->
    <header class="sticky top-0 z-50 bg-primary-blue shadow-lg">
        <nav class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- Nama Sekolah Diperbarui -->
                <div class="flex-shrink-0">
                    <span class="text-2xl font-bold text-white tracking-wide">SMP NEGERI 1 WIRADESA</span>
                </div>
                <!-- Navigasi Utama -->
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#beranda" class="text-white hover:bg-secondary-blue hover:text-primary-blue px-3 py-2 rounded-md text-sm font-medium transition duration-200">Beranda</a>
                        <a href="#profil" class="text-white hover:bg-secondary-blue hover:text-primary-blue px-3 py-2 rounded-md text-sm font-medium transition duration-200">Profil Sekolah</a>
                        <a href="#akademik" class="text-white hover:bg-secondary-blue hover:text-primary-blue px-3 py-2 rounded-md text-sm font-medium transition duration-200">Akademik</a>
                        <a href="#ekstrakurikuler" class="text-white hover:bg-secondary-blue hover:text-primary-blue px-3 py-2 rounded-md text-sm font-medium transition duration-200">Ekstrakurikuler</a>
                        <a href="#galeri" class="text-white hover:bg-secondary-blue hover:text-primary-blue px-3 py-2 rounded-md text-sm font-medium transition duration-200">Galeri</a>
                        <a href="#kontak" class="text-white hover:bg-secondary-blue hover:text-primary-blue px-3 py-2 rounded-md text-sm font-medium transition duration-200">Kontak</a>
                    </div>
                </div>
                <!-- Menu Mobile (disederhanakan, bisa ditambahkan logika JS jika diperlukan) -->
                <div class="md:hidden">
                    <span class="text-white text-sm">Menu</span>
                </div>
            </div>
        </nav>
    </header>

    <!-- Konten Utama -->
    <main>
        <!-- 1. Beranda/Hero Section -->
        <section id="beranda" class="bg-secondary-blue py-20 md:py-32 flex items-center min-h-[70vh]">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h1 class="text-4xl sm:text-6xl font-extrabold text-primary-blue mb-4 leading-tight">
                    Mencetak Bintang Masa Depan
                </h1>
                <p class="text-xl sm:text-2xl text-primary-blue/90 max-w-3xl mx-auto mb-8">
                    Selamat datang di SMP Negeri 1 Wiradesa, pusat pengembangan karakter, ilmu, dan kreativitas.
                </p>
                <a href="#profil" class="inline-block bg-primary-blue text-white text-lg font-medium py-3 px-8 rounded-full shadow-lg hover:bg-primary-blue/90 transition duration-300 transform hover:scale-105">
                    Pelajari Lebih Lanjut
                </a>
            </div>
        </section>

        <!-- 2. Profil Sekolah -->
        <section id="profil" class="py-16 md:py-24 bg-accent-white">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-primary-blue mb-12 border-b-4 border-secondary-blue pb-2 max-w-sm mx-auto">
                    Profil Sekolah
                </h2>

                <div class="grid md:grid-cols-2 gap-12 items-start">
                    <!-- Visi Misi -->
                    <div>
                        <h3 class="text-2xl font-semibold text-primary-blue mb-4">Visi & Misi</h3>
                        <div class="bg-white p-6 rounded-xl shadow-md">
                            <h4 class="text-xl font-bold text-gray-700 mb-2">Visi</h4>
                            <p class="mb-4">Mewujudkan lulusan yang beriman, berprestasi, berkarakter, dan berwawasan lingkungan.</p>

                            <h4 class="text-xl font-bold text-gray-700 mb-2">Misi</h4>
                            <ul class="space-y-2 text-gray-600 list-inside list-none">
                                <li>- Menumbuhkan penghayatan terhadap ajaran agama.</li>
                                <li>- Melaksanakan pembelajaran yang aktif, inovatif, kreatif, efektif, dan menyenangkan.</li>
                                <li>- Mengembangkan potensi akademik dan non-akademik siswa.</li>
                                <li>- Menerapkan budaya peduli lingkungan dan disiplin.</li>
                            </ul>
                        </div>
                    </div>

                    <!-- Sejarah Singkat -->
                    <div>
                        <h3 class="text-2xl font-semibold text-primary-blue mb-4">Sejarah Singkat</h3>
                        <div class="bg-white p-6 rounded-xl shadow-md h-full">
                            <p class="text-gray-600 leading-relaxed">
                                SMP Negeri 1 Wiradesa berdiri sejak tahun 1980 dan telah menjadi sekolah unggulan di Kabupaten Pekalongan. Kami berkomitmen untuk menyediakan pendidikan dasar yang kokoh, berfokus pada keseimbangan antara pengetahuan akademis, pengembangan karakter, dan keterampilan hidup. Dengan fasilitas yang terus diperbarui, sekolah kami siap membimbing siswa menuju jenjang pendidikan yang lebih tinggi.
                            </p>
                            <!-- Sesuai permintaan: Tidak ada daftar guru dan staf pengajar di sini -->
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 3. Akademik (4 Program) - Disesuaikan untuk SMP -->
        <section id="akademik" class="py-16 md:py-24">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-primary-blue mb-12 border-b-4 border-secondary-blue pb-2 max-w-xs mx-auto">
                    Akademik
                </h2>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Program 1: Sains Dasar Inovatif -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary-blue transition duration-300 card-hover">
                        <h3 class="text-xl font-bold text-primary-blue mb-3">Sains Dasar Inovatif</h3>
                        <p class="text-gray-600">Fokus pada penguasaan dasar-dasar ilmu pengetahuan alam dan matematika melalui metode eksperimen kreatif dan berpikir kritis.</p>
                    </div>
                    <!-- Program 2: Sosial & Kewarganegaraan -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary-blue transition duration-300 card-hover">
                        <h3 class="text-xl font-bold text-primary-blue mb-3">Sosial & Kewarganegaraan</h3>
                        <p class="text-gray-600">Pembelajaran interaktif ilmu sosial, sejarah, dan pendidikan kewarganegaraan untuk membentuk siswa yang sadar lingkungan dan sosial.</p>
                    </div>
                    <!-- Program 3: Literasi Multi-Bahasa -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary-blue transition duration-300 card-hover">
                        <h3 class="text-xl font-bold text-primary-blue mb-3">Literasi Multi-Bahasa</h3>
                        <p class="text-gray-600">Program intensif untuk meningkatkan kemampuan Bahasa Indonesia dan Bahasa Inggris, serta apresiasi seni dan budaya daerah.</p>
                    </div>
                    <!-- Program 4: Pengembangan Minat & Bakat -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-primary-blue transition duration-300 card-hover">
                        <h3 class="text-xl font-bold text-primary-blue mb-3">Pengembangan Minat & Bakat</h3>
                        <p class="text-gray-600">Penemuan dan pengembangan minat serta bakat siswa sebagai persiapan untuk jenjang pendidikan selanjutnya.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. Ekstrakurikuler (6 Kegiatan) -->
        <section id="ekstrakurikuler" class="py-16 md:py-24 bg-secondary-blue">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-primary-blue mb-12 border-b-4 border-primary-blue pb-2 max-w-sm mx-auto">
                    Ekstrakurikuler
                </h2>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-6">
                    <!-- E-K-S 1 -->
                    <div class="bg-white p-4 text-center rounded-xl shadow-md transition duration-300 card-hover">
                        <h4 class="text-lg font-bold text-primary-blue">Pramuka</h4>
                        <p class="text-sm text-gray-600">Pembentukan karakter disiplin, mandiri, dan kepemimpinan.</p>
                    </div>
                    <!-- E-K-S 2 -->
                    <div class="bg-white p-4 text-center rounded-xl shadow-md transition duration-300 card-hover">
                        <h4 class="text-lg font-bold text-primary-blue">Sepak Bola Mini</h4>
                        <p class="text-sm text-gray-600">Pengembangan bakat olahraga dan kerjasama tim.</p>
                    </div>
                    <!-- E-K-S 3 -->
                    <div class="bg-white p-4 text-center rounded-xl shadow-md transition duration-300 card-hover">
                        <h4 class="text-lg font-bold text-primary-blue">Seni Lukis</h4>
                        <p class="text-sm text-gray-600">Eksplorasi kreativitas melalui media gambar dan warna.</p>
                    </div>
                    <!-- E-K-S 4 -->
                    <div class="bg-white p-4 text-center rounded-xl shadow-md transition duration-300 card-hover">
                        <h4 class="text-lg font-bold text-primary-blue">Klub Matematika</h4>
                        <p class="text-sm text-gray-600">Pendalaman logika dan pemecahan masalah matematika.</p>
                    </div>
                    <!-- E-K-S 5 -->
                    <div class="bg-white p-4 text-center rounded-xl shadow-md transition duration-300 card-hover">
                        <h4 class="text-lg font-bold text-primary-blue">Olimpiade IPA</h4>
                        <p class="text-sm text-gray-600">Persiapan intensif untuk lomba-lomba sains tingkat kabupaten.</p>
                    </div>
                    <!-- E-K-S 6 -->
                    <div class="bg-white p-4 text-center rounded-xl shadow-md transition duration-300 card-hover">
                        <h4 class="text-lg font-bold text-primary-blue">Paskibra</h4>
                        <p class="text-sm text-gray-600">Pelatihan baris-berbaris dan penanaman rasa nasionalisme.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. Galeri Foto dan Video -->
        <section id="galeri" class="py-16 md:py-24 bg-white">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-3xl sm:text-4xl font-bold text-center text-primary-blue mb-12 border-b-4 border-secondary-blue pb-2 max-w-xs mx-auto">
                    Galeri
                </h2>

                <p class="text-center text-gray-600 mb-8">Dokumentasi momen-momen berharga dari kegiatan SMP Negeri 1 Wiradesa.</p>

                <!-- Grid Galeri (menggunakan placeholder karena tidak ada file eksternal) -->
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                    <!-- Foto 1 -->
                    <div class="rounded-xl overflow-hidden shadow-lg transform transition duration-300 hover:scale-[1.02]">
                        <img src="https://placehold.co/600x400/1E3A8A/FFFFFF?text=FOTO+ACARA+PERPISAHAN" onerror="this.onerror=null;this.src='https://placehold.co/600x400/1E3A8A/FFFFFF?text=FOTO+1';" alt="Foto Acara Perpisahan" class="w-full h-48 object-cover">
                        <div class="p-4 bg-accent-white">
                            <p class="text-primary-blue font-semibold">Acara Perpisahan Kelas IX</p>
                        </div>
                    </div>
                    <!-- Foto 2 -->
                    <div class="rounded-xl overflow-hidden shadow-lg transform transition duration-300 hover:scale-[1.02]">
                        <img src="https://placehold.co/600x400/BFDBFE/1E3A8A?text=FOTO+LOMBA+EKSTERN" onerror="this.onerror=null;this.src='https://placehold.co/600x400/BFDBFE/1E3A8A?text=FOTO+2';" alt="Foto Kegiatan Lomba" class="w-full h-48 object-cover">
                        <div class="p-4 bg-accent-white">
                            <p class="text-primary-blue font-semibold">Kegiatan Lomba Antar Kelas</p>
                        </div>
                    </div>
                    <!-- Video Placeholder 1 -->
                    <div class="rounded-xl overflow-hidden shadow-lg transform transition duration-300 hover:scale-[1.02]">
                        <div class="w-full h-48 flex items-center justify-center bg-gray-700 text-white">
                            <p class="text-lg">VIDEO SENI TARI</p>
                        </div>
                        <div class="p-4 bg-accent-white">
                            <p class="text-primary-blue font-semibold">Pementasan Seni Tari Tradisional</p>
                        </div>
                    </div>
                    <!-- Foto 4 -->
                    <div class="rounded-xl overflow-hidden shadow-lg transform transition duration-300 hover:scale-[1.02]">
                        <img src="https://placehold.co/600x400/1E3A8A/FFFFFF?text=FOTO+UPACARA+BENDERA" onerror="this.onerror=null;this.src='https://placehold.co/600x400/1E3A8A/FFFFFF?text=FOTO+4';" alt="Foto Upacara Bendera" class="w-full h-48 object-cover">
                        <div class="p-4 bg-accent-white">
                            <p class="text-primary-blue font-semibold">Upacara Bendera Hari Senin</p>
                        </div>
                    </div>
                    <!-- Foto 5 -->
                    <div class="rounded-xl overflow-hidden shadow-lg transform transition duration-300 hover:scale-[1.02]">
                        <img src="https://placehold.co/600x400/BFDBFE/1E3A8A?text=FOTO+KEGIATAN+PRAMUKA" onerror="this.onerror=null;this.src='https://placehold.co/600x400/BFDBFE/1E3A8A?text=FOTO+5';" alt="Foto Kegiatan Pramuka" class="w-full h-48 object-cover">
                        <div class="p-4 bg-accent-white">
                            <p class="text-primary-blue font-semibold">Latihan Pramuka di Lapangan</p>
                        </div>
                    </div>
                    <!-- Video Placeholder 2 -->
                    <div class="rounded-xl overflow-hidden shadow-lg transform transition duration-300 hover:scale-[1.02]">
                        <div class="w-full h-48 flex items-center justify-center bg-gray-700 text-white">
                            <p class="text-lg">VIDEO KUNJUNGAN</p>
                        </div>
                        <div class="p-4 bg-accent-white">
                            <p class="text-primary-blue font-semibold">Video Kunjungan ke Perpustakaan Daerah</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 6. Kontak Sekolah -->
        <section id="kontak" class="py-16 md:py-24 bg-primary-blue">
            <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-white">
                <h2 class="text-3xl sm:text-4xl font-bold text-center mb-12 border-b-4 border-secondary-blue pb-2 max-w-xs mx-auto">
                    Kontak Sekolah
                </h2>

                <div class="grid md:grid-cols-3 gap-8 text-center">
                    <!-- Alamat -->
                    <div class="bg-primary-blue/80 p-6 rounded-xl shadow-xl">
                        <h3 class="text-xl font-bold mb-3">Alamat Kami</h3>
                        <p class="text-secondary-blue/90">Jl. Pahlawan No. 1, Wiradesa, Pekalongan, 51152</p>
                        <p class="text-sm mt-2">(Area pusat Wiradesa yang strategis)</p>
                    </div>
                    <!-- Telepon -->
                    <div class="bg-primary-blue/80 p-6 rounded-xl shadow-xl">
                        <h3 class="text-xl font-bold mb-3">Hubungi Kami</h3>
                        <p class="text-secondary-blue/90 font-mono text-xl">(0285) 441 556</p>
                        <p class="text-sm mt-2">Jam Kerja: Senin - Jumat (07:00 - 15:00)</p>
                    </div>
                    <!-- Email -->
                    <div class="bg-primary-blue/80 p-6 rounded-xl shadow-xl">
                        <h3 class="text-xl font-bold mb-3">Kirim Email</h3>
                        <p class="text-secondary-blue/90 font-mono text-xl">info@smpn1wiradesa.sch.id</p>
                        <p class="text-sm mt-2">Respon cepat dalam 1x24 jam kerja</p>
                    </div>
                </div>

                <!-- Formulir Kontak Sederhana (Opsional) -->
                <div class="mt-12 max-w-2xl mx-auto bg-white p-8 rounded-xl shadow-2xl text-gray-800">
                    <h3 class="text-2xl font-bold text-primary-blue mb-6 text-center">Kirim Pesan</h3>
                    <form action="#" method="POST" class="space-y-4">
                        <div>
                            <label for="nama" class="block text-sm font-medium text-gray-700">Nama Lengkap</label>
                            <input type="text" id="nama" name="nama" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-primary-blue focus:border-primary-blue">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                            <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-primary-blue focus:border-primary-blue">
                        </div>
                        <div>
                            <label for="pesan" class="block text-sm font-medium text-gray-700">Pesan</label>
                            <textarea id="pesan" name="pesan" rows="4" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-primary-blue focus:border-primary-blue"></textarea>
                        </div>
                        <div class="pt-2">
                            <button type="submit" class="w-full bg-primary-blue text-white py-3 px-4 rounded-md font-semibold hover:bg-primary-blue/90 transition duration-300">
                                Kirim
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-100 py-6">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-600 text-sm">
            &copy; 2025 SMP NEGERI 1 WIRADESA. All rights reserved.
        </div>
    </footer>

</body>
</html>
