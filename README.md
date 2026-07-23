
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Angga Aji Saputra | Portfolio & Personal Website</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Google Fonts (Plus Jakarta Sans) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        primary: '#0F172A',
                        accent: '#2563EB',
                        accentHover: '#1D4ED8',
                        surface: '#F8FAFC',
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 antialiased font-sans selection:bg-blue-500 selection:text-white">

    <!-- Navbar -->
    <nav class="fixed top-0 left-0 w-full bg-white/80 backdrop-blur-md z-50 border-b border-slate-100 transition-all duration-300">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold tracking-tight text-slate-900">
                Angga<span class="text-blue-600">.</span>
            </a>

            <!-- Desktop Menu -->
            <div class="hidden md:flex items-center space-x-8 text-sm font-semibold text-slate-600">
                <a href="#tentang" class="hover:text-blue-600 transition">Tentang</a>
                <a href="#pengalaman" class="hover:text-blue-600 transition">Pengalaman</a>
                <a href="#pendidikan" class="hover:text-blue-600 transition">Pendidikan</a>
                <a href="#keahlian" class="hover:text-blue-600 transition">Keahlian</a>
                <a href="#kontak" class="px-5 py-2.5 bg-blue-600 hover:bg-blue-700 text-white rounded-full transition shadow-md shadow-blue-500/20">
                    Hubungi Saya
                </a>
            </div>

            <!-- Mobile Hamburger -->
            <button id="menu-btn" class="md:hidden text-slate-800 focus:outline-none">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-100 px-6 py-4 space-y-4 font-medium text-slate-700">
            <a href="#tentang" class="block hover:text-blue-600">Tentang</a>
            <a href="#pengalaman" class="block hover:text-blue-600">Pengalaman</a>
            <a href="#pendidikan" class="block hover:text-blue-600">Pendidikan</a>
            <a href="#keahlian" class="block hover:text-blue-600">Keahlian</a>
            <a href="#kontak" class="block w-full text-center py-2 bg-blue-600 text-white rounded-lg">Hubungi Saya</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-36 pb-20 md:pt-44 md:pb-32 px-6 max-w-6xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-12 items-center">
            <div class="md:col-span-7 space-y-6">
                <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-blue-50 border border-blue-100 text-blue-700 text-xs font-semibold">
                    <span class="w-2 h-2 rounded-full bg-blue-600 animate-pulse"></span>
                    Professional Banking & Operations Specialist
                </div>
                
                <h1 class="text-4xl md:text-6xl font-extrabold text-slate-900 tracking-tight leading-tight">
                    Halo, Saya <br><span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-indigo-600">Angga Aji Saputra</span>
                </h1>

                <p class="text-base md:text-lg text-slate-600 leading-relaxed">
                    Lulusan Manajemen Bisnis Syariah dengan pengalaman di bidang perbankan, administrasi keuangan, dan operasional. Terbiasa menangani transaksi skala tinggi, rekonsiliasi kas, serta pelayanan nasabah prima berstandar SOP perbankan.
                </p>

                <div class="flex flex-wrap gap-4 pt-2">
                    <a href="#kontak" class="px-6 py-3 bg-blue-600 hover:bg-blue-700 text-white font-medium rounded-xl shadow-lg shadow-blue-500/25 transition duration-200 flex items-center gap-2">
                        <i class="fa-solid fa-paper-plane"></i> Kontak Saya
                    </a>
                    <a href="https://www.linkedin.com/in/angga-aji-saputra-b47617288" target="_blank" class="px-6 py-3 bg-white border border-slate-200 hover:bg-slate-50 text-slate-800 font-medium rounded-xl transition duration-200 flex items-center gap-2">
                        <i class="fa-brands fa-linkedin text-blue-600"></i> LinkedIn Profile
                    </a>
                </div>

                <!-- Fast Info Badges -->
                <div class="pt-6 grid grid-cols-2 md:grid-cols-3 gap-4 border-t border-slate-200/60">
                    <div>
                        <p class="text-xs text-slate-500 font-medium">Pendidikan</p>
                        <p class="text-sm font-semibold text-slate-800">S1 Manajemen Bisnis</p>
                    </div>
                    <div>
                        <p class="text-xs text-slate-500 font-medium">IPK Akademik</p>
                        <p class="text-sm font-semibold text-slate-800">3.48 / 4.00</p>
                    </div>
                    <div>
                        <p class="text-xs text-slate-500 font-medium">Lokasi</p>
                        <p class="text-sm font-semibold text-slate-800">Lampung, Indonesia</p>
                    </div>
                </div>
            </div>

            <!-- Profile Avatar Card -->
            <div class="md:col-span-5 flex justify-center">
                <div class="relative w-full max-w-sm">
                    <div class="absolute inset-0 bg-gradient-to-tr from-blue-600 to-indigo-500 rounded-3xl rotate-3 blur-sm opacity-20"></div>
                    <div class="relative bg-white border border-slate-100 rounded-3xl p-6 shadow-xl space-y-6">
                        <div class="w-full h-72 bg-slate-100 rounded-2xl flex items-center justify-center overflow-hidden border border-slate-200">
                            <!-- Placeholder Photo / User Avatar -->
                            <i class="fa-solid fa-user-tie text-8xl text-slate-300"></i>
                        </div>
                        <div class="space-y-2">
                            <h3 class="text-lg font-bold text-slate-900">Angga Aji Saputra, S.E.</h3>
                            <p class="text-xs text-slate-500">Ex-Teller PT Bank Rakyat Indonesia (Persero) Tbk & General Affair Specialist</p>
                        </div>
                        <div class="flex items-center justify-between text-xs font-medium text-slate-600 bg-slate-50 p-3 rounded-xl">
                            <span><i class="fa-solid fa-envelope text-blue-600 mr-2"></i>Email Verified</span>
                            <span class="text-green-600 font-semibold"><i class="fa-solid fa-circle-check mr-1"></i>Available</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Tentang Saya Section -->
    <section id="tentang" class="py-20 bg-white border-y border-slate-100">
        <div class="max-w-6xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-12">
                <h2 class="text-xs font-bold tracking-widest text-blue-600 uppercase">Tentang Saya</h2>
                <p class="text-3xl font-bold text-slate-900">Profesional Berdedikasi dengan Integritas & Ketelitian Tinggi</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100 space-y-3">
                    <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center text-blue-600 text-xl font-bold">
                        <i class="fa-solid fa-building-columns"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900">Pengalaman Perbankan</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Memiliki rekam jejak sebagai Teller di PT Bank Rakyat Indonesia (Persero) Tbk. Mahir mengelola transaksi keuangan harian, balancing kas, serta penanganan error correction sesuai Standar Operasional Prosedur (SOP).
                    </p>
                </div>

                <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100 space-y-3">
                    <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center text-blue-600 text-xl font-bold">
                        <i class="fa-solid fa-calculator"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900">Manajemen Operasional & Keuangan</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Pengalaman mengelola General Affair, verifikasi berkas tagihan, pelaporan pajak (KPP Madya), arus kas (cash flow), hingga manajemen persediaan barang secara sistematis.
                    </p>
                </div>

                <div class="p-6 bg-slate-50 rounded-2xl border border-slate-100 space-y-3">
                    <div class="w-12 h-12 bg-blue-100 rounded-xl flex items-center justify-center text-blue-600 text-xl font-bold">
                        <i class="fa-solid fa-palette"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900">Kreativitas & Multimedia</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Di samping kemampuan analitis, saya menguasai desain grafis (Canva/Visual Design), penataan interior toko, serta pengoperasian drone secara terampil.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pengalaman Kerja Section -->
    <section id="pengalaman" class="py-20 max-w-6xl mx-auto px-6">
        <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
            <h2 class="text-xs font-bold tracking-widest text-blue-600 uppercase">Karir & Pengalaman</h2>
            <p class="text-3xl font-bold text-slate-900">Riwayat Pengalaman Kerja & Magang</p>
        </div>

        <div class="relative border-l-2 border-slate-200 ml-4 md:ml-32 space-y-12">

            <!-- Item 1 -->
            <div class="relative pl-8 group">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-blue-600 ring-4 ring-white"></div>
                <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                    <h3 class="text-xl font-bold text-slate-900">Teller — PT Bank Rakyat Indonesia (Persero) Tbk</h3>
                    <span class="text-xs font-semibold px-3 py-1 bg-blue-100 text-blue-700 rounded-full w-fit mt-1 md:mt-0">Okt 2025 – Sekarang</span>
                </div>
                <p class="text-xs font-medium text-slate-500 mb-3"><i class="fa-solid fa-location-dot mr-1"></i>Lampung Utara, Lampung</p>
                <ul class="list-disc list-inside text-sm text-slate-600 space-y-1.5 leading-relaxed">
                    <li>Melayani transaksi setoran, penarikan, dan pemindahbukuan keuangan nasabah secara efisien dan akurat.</li>
                    <li>Melakukan balancing kas harian serta rekonsiliasi transaksi secara teliti.</li>
                    <li>Menangani error correction transaksi sesuai dengan Standard Operating Procedure (SOP) perbankan.</li>
                    <li>Memberikan pelayanan prima (*service excellence*) kepada seluruh nasabah.</li>
                </ul>
            </div>

            <!-- Item 2 -->
            <div class="relative pl-8 group">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-slate-300 group-hover:bg-blue-600 transition ring-4 ring-white"></div>
                <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                    <h3 class="text-xl font-bold text-slate-900">General Affair — Juwita Mart</h3>
                    <span class="text-xs font-semibold px-3 py-1 bg-slate-100 text-slate-700 rounded-full w-fit mt-1 md:mt-0">2025 – Sekarang</span>
                </div>
                <p class="text-xs font-medium text-slate-500 mb-3"><i class="fa-solid fa-location-dot mr-1"></i>Tanggamus, Lampung</p>
                <ul class="list-disc list-inside text-sm text-slate-600 space-y-1.5 leading-relaxed">
                    <li>Bertanggung jawab penuh terhadap arus kas (*cash flow*) dan pengelolaan pembayaran customer serta vendor.</li>
                    <li>Mengelola pemesanan barang ke vendor, pemeriksaan (*cross-check*) barang masuk & keluar, serta stok opname berkala.</li>
                    <li>Melakukan rekonsiliasi nilai barang dengan pendapatan operasional.</li>
                    <li>Merancang desain interior toko untuk optimalisasi penataan produk dan kenyamanan belanja.</li>
                </ul>
            </div>

            <!-- Item 3 -->
            <div class="relative pl-8 group">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-slate-300 group-hover:bg-blue-600 transition ring-4 ring-white"></div>
                <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                    <h3 class="text-xl font-bold text-slate-900">Staf Keuangan (Magang) — PT Buma Cima Nusantara</h3>
                    <span class="text-xs font-semibold px-3 py-1 bg-slate-100 text-slate-700 rounded-full w-fit mt-1 md:mt-0">Sep 2024 – Okt 2024</span>
                </div>
                <p class="text-xs font-medium text-slate-500 mb-3"><i class="fa-solid fa-location-dot mr-1"></i>Bandar Lampung, Lampung</p>
                <ul class="list-disc list-inside text-sm text-slate-600 space-y-1.5 leading-relaxed">
                    <li>Verifikasi berkas tagihan, menginput data hutang perusahaan, serta merencanakan rencana pembayaran.</li>
                    <li>Sinkronisasi data pembayaran, pelaporan pajak, serta tata kelola pengarsipan dokumen perusahaan.</li>
                </ul>
            </div>

            <!-- Item 4 -->
            <div class="relative pl-8 group">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-slate-300 group-hover:bg-blue-600 transition ring-4 ring-white"></div>
                <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                    <h3 class="text-xl font-bold text-slate-900">Staf Pelayanan (Magang) — KPP Madya Bandar Lampung</h3>
                    <span class="text-xs font-semibold px-3 py-1 bg-slate-100 text-slate-700 rounded-full w-fit mt-1 md:mt-0">Mar 2024 – Apr 2024</span>
                </div>
                <p class="text-xs font-medium text-slate-500 mb-3"><i class="fa-solid fa-location-dot mr-1"></i>Bandar Lampung, Lampung</p>
                <ul class="list-disc list-inside text-sm text-slate-600 space-y-1.5 leading-relaxed">
                    <li>Membantu mengisi daftar pelayanan publik di Kantor Pelayanan Pajak (KPP) Madya.</li>
                    <li>Pengarsipan berkas surat teguran SPT tahunan terkait keterlambatan/ketidaksesuaian pelaporan pajak.</li>
                </ul>
            </div>

            <!-- Item 5 & 6 -->
            <div class="relative pl-8 group">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-slate-300 group-hover:bg-blue-600 transition ring-4 ring-white"></div>
                <div class="flex flex-col md:flex-row md:items-center justify-between mb-2">
                    <h3 class="text-xl font-bold text-slate-900">Pengalaman Freelance & Operasional Lapangan</h3>
                    <span class="text-xs font-semibold px-3 py-1 bg-slate-100 text-slate-700 rounded-full w-fit mt-1 md:mt-0">2022 – 2024</span>
                </div>
                <ul class="list-disc list-inside text-sm text-slate-600 space-y-1.5 leading-relaxed">
                    <li><strong>PT Indopsiko Ekspres Logistik SOC Lampung:</strong> Memilah (*sortir*) & *bagging* paket berdasarkan kode daerah tujuan.</li>
                    <li><strong>PT Lembah Hijau (Frontliner):</strong> Menjaga loket, memverifikasi tiket masuk, serta memandu wisatawan.</li>
                </ul>
            </div>

        </div>
    </section>

    <!-- Pendidikan & Sertifikasi -->
    <section id="pendidikan" class="py-20 bg-white border-y border-slate-100">
        <div class="max-w-6xl mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                
                <!-- Pendidikan -->
                <div class="space-y-6">
                    <div class="space-y-2">
                        <h2 class="text-xs font-bold tracking-widest text-blue-600 uppercase">Pendidikan</h2>
                        <h3 class="text-2xl font-bold text-slate-900">Latar Belakang Akademis</h3>
                    </div>

                    <div class="p-6 bg-slate-50 rounded-2xl border border-slate-200/80 space-y-3">
                        <span class="text-xs font-semibold px-2.5 py-1 bg-blue-100 text-blue-700 rounded-md">Sarjana Ekonomi (S.E.)</span>
                        <h4 class="text-lg font-bold text-slate-900">Universitas Islam Negeri Raden Intan Lampung</h4>
                        <p class="text-sm font-medium text-slate-600">Manajemen Bisnis Syariah | IPK: <strong>3.48 / 4.00</strong> (Sangat Memuaskan)</p>
                        <p class="text-xs text-slate-500 italic pt-2 border-t border-slate-200">
                            <strong>Judul Skripsi:</strong> "Impresi Metode Pembayaran, Harga Dan Customer Review Terhadap Purchase Decision Tiktok Shop Dalam Perspektif Etika Bisnis Islam"
                        </p>
                    </div>
                </div>

                <!-- Sertifikasi & Organisasi -->
                <div class="space-y-6">
                    <div class="space-y-2">
                        <h2 class="text-xs font-bold tracking-widest text-blue-600 uppercase">Kualifikasi Lainnya</h2>
                        <h3 class="text-2xl font-bold text-slate-900">Sertifikasi & Organisasi</h3>
                    </div>

                    <div class="space-y-4">
                        <div class="p-5 bg-slate-50 rounded-2xl border border-slate-200/80 flex items-start gap-4">
                            <div class="p-3 bg-blue-600 text-white rounded-xl">
                                <i class="fa-solid fa-award text-xl"></i>
                            </div>
                            <div>
                                <h4 class="text-base font-bold text-slate-900">TOEFL Prediction Test</h4>
                                <p class="text-xs text-slate-500">English Domestic Certification</p>
                            </div>
                        </div>

                        <div class="p-5 bg-slate-50 rounded-2xl border border-slate-200/80 flex items-start gap-4">
                            <div class="p-3 bg-indigo-600 text-white rounded-xl">
                                <i class="fa-solid fa-users text-xl"></i>
                            </div>
                            <div>
                                <h4 class="text-base font-bold text-slate-900">UKM Olah Raga Raden Intan</h4>
                                <p class="text-xs font-medium text-blue-600 mb-1">Anggota Divisi Sepak Bola</p>
                                <p class="text-xs text-slate-600">Aktif mengoordinasikan agenda latihan mingguan, penyusunan strategi tim, serta berhasil menjaring 15+ anggota baru selama periode kepengurusan.</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Keahlian / Skills Section -->
    <section id="keahlian" class="py-20 max-w-6xl mx-auto px-6">
        <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
            <h2 class="text-xs font-bold tracking-widest text-blue-600 uppercase">Kompetensi</h2>
            <p class="text-3xl font-bold text-slate-900">Keahlian & Kemampuan Teknis</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Hard Skills -->
            <div class="bg-white p-6 rounded-2xl border border-slate-200/80 shadow-sm space-y-4">
                <h3 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                    <i class="fa-solid fa-gears text-blue-600"></i> Hard Skills
                </h3>
                <div class="flex flex-wrap gap-2">
                    <span class="px-3 py-1.5 bg-slate-100 text-slate-700 rounded-lg text-xs font-medium">Transaksi Bank & SOP</span>
                    <span class="px-3 py-1.5 bg-slate-100 text-slate-700 rounded-lg text-xs font-medium">Rekonsiliasi Kas</span>
                    <span class="px-3 py-1.5 bg-slate-100 text-slate-700 rounded-lg text-xs font-medium">Desain Grafis</span>
                    <span class="px-3 py-1.5 bg-slate-100 text-slate-700 rounded-lg text-xs font-medium">Pilot Drone</span>
                    <span class="px-3 py-1.5 bg-slate-100 text-slate-700 rounded-lg text-xs font-medium">Pengarsipan Dokumen</span>
                </div>
            </div>

            <!-- Soft Skills -->
            <div class="bg-white p-6 rounded-2xl border border-slate-200/80 shadow-sm space-y-4">
                <h3 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                    <i class="fa-solid fa-heart text-blue-600"></i> Soft Skills
                </h3>
                <div class="flex flex-wrap gap-2">
                    <span class="px-3 py-1.5 bg-blue-50 text-blue-700 rounded-lg text-xs font-medium">Customer Support & Service</span>
                    <span class="px-3 py-1.5 bg-blue-50 text-blue-700 rounded-lg text-xs font-medium">Kerja Tim & Mandiri</span>
                    <span class="px-3 py-1.5 bg-blue-50 text-blue-700 rounded-lg text-xs font-medium">Manajemen Waktu</span>
                    <span class="px-3 py-1.5 bg-blue-50 text-blue-700 rounded-lg text-xs font-medium">Komunikasi Efektif</span>
                </div>
            </div>

            <!-- Software Skills -->
            <div class="bg-white p-6 rounded-2xl border border-slate-200/80 shadow-sm space-y-4">
                <h3 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                    <i class="fa-solid fa-laptop-code text-blue-600"></i> Software Skills
                </h3>
                <div class="flex flex-wrap gap-2">
                    <span class="px-3 py-1.5 bg-indigo-50 text-indigo-700 rounded-lg text-xs font-medium">Microsoft Word</span>
                    <span class="px-3 py-1.5 bg-indigo-50 text-indigo-700 rounded-lg text-xs font-medium">Microsoft Excel</span>
                    <span class="px-3 py-1.5 bg-indigo-50 text-indigo-700 rounded-lg text-xs font-medium">Microsoft PowerPoint</span>
                    <span class="px-3 py-1.5 bg-indigo-50 text-indigo-700 rounded-lg text-xs font-medium">Canva</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Kontak Section -->
    <section id="kontak" class="py-20 bg-slate-900 text-white">
        <div class="max-w-6xl mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center space-y-4 mb-16">
                <h2 class="text-xs font-bold tracking-widest text-blue-400 uppercase">Hubungi Saya</h2>
                <p class="text-3xl font-bold text-white">Mari Terhubung & Bekerja Sama</p>
                <p class="text-sm text-slate-400">Terbuka untuk peluang karir di bidang Perbankan, Operasional Keuangan, General Affair, maupun Administrasi.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-4xl mx-auto">
                <a href="tel:082278058425" class="p-6 bg-slate-800/80 hover:bg-slate-800 rounded-2xl border border-slate-700 transition text-center space-y-3">
                    <div class="w-12 h-12 bg-blue-600/20 text-blue-400 rounded-full flex items-center justify-center mx-auto text-xl">
                        <i class="fa-solid fa-phone"></i>
                    </div>
                    <p class="text-xs text-slate-400">Telepon / WhatsApp</p>
                    <p class="text-sm font-semibold text-white">0822-7805-8425</p>
                </a>

                <a href="mailto:anggaajisaputra292@gmail.com" class="p-6 bg-slate-800/80 hover:bg-slate-800 rounded-2xl border border-slate-700 transition text-center space-y-3">
                    <div class="w-12 h-12 bg-blue-600/20 text-blue-400 rounded-full flex items-center justify-center mx-auto text-xl">
                        <i class="fa-solid fa-envelope"></i>
                    </div>
                    <p class="text-xs text-slate-400">Email Utama</p>
                    <p class="text-sm font-semibold text-white break-all">anggaajisaputra292@gmail.com</p>
                </a>

                <a href="https://www.linkedin.com/in/angga-aji-saputra-b47617288" target="_blank" class="p-6 bg-slate-800/80 hover:bg-slate-800 rounded-2xl border border-slate-700 transition text-center space-y-3">
                    <div class="w-12 h-12 bg-blue-600/20 text-blue-400 rounded-full flex items-center justify-center mx-auto text-xl">
                        <i class="fa-brands fa-linkedin-in"></i>
                    </div>
                    <p class="text-xs text-slate-400">LinkedIn</p>
                    <p class="text-sm font-semibold text-white">Angga Aji Saputra</p>
                </a>
            </div>

            <div class="mt-12 text-center text-xs text-slate-400">
                <p><i class="fa-solid fa-location-dot mr-1 text-blue-400"></i> Dsn. Tambah Rejo, Kel. Batu Tegi, Kec. Air Naningan, Kab. Tanggamus, Lampung</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 bg-slate-950 text-slate-500 text-xs text-center border-t border-slate-800">
        <p>&copy; 2026 Angga Aji Saputra. All rights reserved.</p>
    </footer>

    <!-- JavaScript Mobile Menu Handler -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close menu when clicking link on mobile
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
