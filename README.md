<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Info & Borang Kursus Modul Janakuasa - IKBN Kinarut</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #1e3a8a 0%, #1e40af 100%);
        }

        .card-hover:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }

        .logo-container img {
            height: 80px;
            object-fit: contain;
        }

        .step-number {
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
            background-color: #1e3a8a;
            color: white;
            font-weight: bold;
            flex-shrink: 0;
        }

        @media (max-width: 768px) {
            .logo-container img {
                height: 50px;
            }
            .header-title {
                font-size: 1rem !important;
            }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex items-center justify-between">
            <div class="logo-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Coat_of_arms_of_Malaysia.svg" alt="Logo Kerajaan Malaysia" onerror="this.src='https://via.placeholder.com/80?text=JATA+NEGARA'">
            </div>
            
            <div class="text-center px-4">
                <h1 class="header-title text-xl md:text-2xl font-bold text-blue-900 uppercase tracking-tight">
                    INFO DAN BORANG KURSUS MODUL JANAKUASA DENGAN PENYEGERAKAN
                </h1>
                <p class="text-xs md:text-sm text-gray-600 font-medium">Jabatan Elektrik IKBN Kinarut Sabah</p>
            </div>

            <div class="logo-container">
                <img src="https://upload.wikimedia.org/wikipedia/ms/thumb/0/01/Logo_KBS.png/250px-Logo_KBS.png" alt="Logo IKBN / KBS" onerror="this.src='https://via.placeholder.com/80?text=IKBN+LOGO'">
            </div>
        </div>
    </header>

    <section class="hero-gradient text-white py-16">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-5xl font-extrabold mb-6">Tingkatkan Kompetensi Elektrik Anda</h2>
            <p class="text-lg md:text-xl mb-10 opacity-90 max-w-2xl mx-auto">Sertai kursus moduler 80 jam diiktiraf ECoS Sabah. Masa depan kerjaya anda bermula di IKBN Kinarut.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#prosedur" class="bg-yellow-500 hover:bg-yellow-400 text-blue-900 font-bold py-4 px-8 rounded-full shadow-lg transition duration-300 flex items-center justify-center">
                    <i class="fas fa-download mr-2"></i> MUAT TURUN BORANG & DAFTAR
                </a>
                <a href="#maklumat" class="bg-transparent border-2 border-white hover:bg-white hover:text-blue-900 font-bold py-4 px-8 rounded-full transition duration-300">
                    LIHAT SYARAT KELAYAKAN
                </a>
            </div>
        </div>
    </section>

    <section id="prosedur" class="py-16 bg-blue-50">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl overflow-hidden">
                <div class="bg-blue-900 p-6 text-white text-center">
                    <h2 class="text-2xl font-bold uppercase tracking-wide">Langkah Pendaftaran & Muat Turun</h2>
                    <p class="text-blue-200 text-sm">Sila ikuti prosedur di bawah untuk kelancaran permohonan anda</p>
                </div>
                
                <div class="p-8">
                    <div class="grid md:grid-cols-1 gap-8">
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="step-number mr-4">1</div>
                                <div>
                                    <h4 class="font-bold text-blue-900">Muat Turun Borang</h4>
                                    <p class="text-sm text-gray-600 mb-3">Klik butang di bawah untuk memuat turun borang permohonan rasmi.</p>
                                    <a href="https://drive.google.com/file/d/1715CZNVigrQBpf5nZ0Zne6Rne8xC8tUF/view" target="_blank" class="inline-flex items-center px-4 py-2 bg-blue-100 text-blue-800 rounded-lg hover:bg-blue-200 transition text-sm font-semibold">
                                        <i class="fas fa-file-pdf mr-2"></i> Klik Untuk Muat Turun Borang (.PDF)
                                    </a>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="step-number mr-4">2</div>
                                <div>
                                    <h4 class="font-bold text-blue-900">Lengkapkan Borang & Cop Majikan</h4>
                                    <p class="text-sm text-gray-600">Isi maklumat dengan lengkap dan dapatkan <strong>PENGESAHAN/COP MAJIKAN</strong> pada ruangan yang disediakan.</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="step-number mr-4">3</div>
                                <div>
                                    <h4 class="font-bold text-blue-900">Imbas (Scan) & Muat Naik</h4>
                                    <p class="text-sm text-gray-600 mb-3">Sila muat naik borang yang telah lengkap di ruang borang online di bawah.</p>
                                    <a href="https://forms.gle/nKLba9HoKWWpQuVZ9" target="_blank" class="inline-flex items-center px-6 py-3 bg-yellow-500 text-blue-900 rounded-lg hover:bg-yellow-400 transition font-bold shadow-md">
                                        <i class="fas fa-external-link-alt mr-2"></i> BORANG PERMOHONAN KURSUS (ONLINE)
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <main id="maklumat" class="container mx-auto px-4 py-16">
        <div class="mb-20">
            <div class="flex items-center mb-8 border-b-4 border-blue-900 pb-2">
                <span class="bg-blue-900 text-white p-3 rounded-lg mr-4">
                    <i class="fas fa-bolt fa-2x"></i>
                </span>
                <h2 class="text-2xl md:text-3xl font-bold text-blue-900 uppercase">Program IV: Modul Janakuasa VR Dengan Penyegerakan</h2>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-yellow-500 card-hover">
                    <h3 class="font-bold text-xl mb-4 text-blue-800"><i class="fas fa-info-circle mr-2"></i> Info Kursus</h3>
                    <ul class="space-y-3">
                        <li class="flex justify-between border-b pb-2"><span>Yuran Kursus:</span> <span class="font-bold text-green-600">RM 2,000</span></li>
                        <li class="flex justify-between border-b pb-2"><span>Tempoh:</span> <span class="font-bold">80 Jam</span></li>
                        <li class="flex justify-between border-b pb-2"><span>Mod:</span> <span class="font-bold">Sepenuh/Separuh Masa</span></li>
                    </ul>
                </div>

                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-yellow-500 card-hover md:col-span-2">
                    <h3 class="font-bold text-xl mb-4 text-blue-800"><i class="fas fa-user-check mr-2"></i> Syarat Kelayakan Tambahan</h3>
                    <div class="grid md:grid-cols-2 gap-4">
                        <ul class="list-disc ml-5 space-y-1 text-sm">
                            <li><strong>A0:</strong> Min. 2 tahun pengalaman.</li>
                            <li><strong>A1:</strong> Min. 1 tahun pengalaman.</li>
                            <li>Warganegara Malaysia (20 tahun+).</li>
                        </ul>
                        <ul class="list-disc ml-5 space-y-1 text-sm text-gray-600">
                            <li>Buku Log lengkap & disahkan.</li>
                            <li>Kehadiran wajib 90% ke atas.</li>
                            <li>Tamat Tingkatan 5 (Kerajaan).</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="mb-20">
            <div class="flex items-center mb-8 border-b-4 border-red-800 pb-2">
                <span class="bg-red-800 text-white p-3 rounded-lg mr-4">
                    <i class="fas fa-industry fa-2x"></i>
                </span>
                <h2 class="text-2xl md:text-3xl font-bold text-red-800 uppercase">Modul Kendalian Pencawang (MKP) 11kV</h2>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-red-500 card-hover md:col-span-2">
                    <h3 class="font-bold text-xl mb-4 text-red-800"><i class="fas fa-clipboard-list mr-2"></i> Syarat Kelayakan & Pengalaman</h3>
                    <div class="grid md:grid-cols-2 gap-4">
                        <ul class="space-y-2 text-sm">
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Perakuan PJ VR & Daftar ECoS.</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Min. 3 tahun pengalaman elektrik.</li>
                        </ul>
                        <ul class="space-y-2 text-sm">
                            <li><i class="fas fa-file-alt text-blue-500 mr-2"></i> Surat Pengesahan Majikan.</li>
                            <li><i class="fas fa-file-alt text-blue-500 mr-2"></i> Buku log kerja harian lengkap.</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-red-500 card-hover">
                    <h3 class="font-bold text-xl mb-4 text-red-800"><i class="fas fa-tag mr-2"></i> Butiran Kursus</h3>
                    <ul class="space-y-3">
                        <li class="flex justify-between border-b pb-2"><span>Yuran:</span> <span class="font-bold text-red-600">RM 4,800</span></li>
                        <li class="flex justify-between border-b pb-2"><span>Kapasiti:</span> <span class="font-bold">20 Calon / Sesi</span></li>
                        <li class="flex justify-between"><span>Kekerapan:</span> <span class="font-bold text-sm">2 Sesi Setahun</span></li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="bg-yellow-50 border-l-8 border-yellow-500 p-8 rounded-lg shadow-inner">
            <h3 class="text-xl font-bold text-yellow-800 mb-2 uppercase flex items-center">
                <i class="fas fa-exclamation-triangle mr-3"></i> Nota Penting ECoS Sabah
            </h3>
            <p class="text-gray-700 text-sm leading-relaxed">
                Semua jadual lengkap dan perancangan kursus mesti mendapat kebenaran <strong>ECoS (Energy Commission of Sabah)</strong> sebelum dijalankan.
            </p>
        </div>
    </main>

    <footer class="bg-blue-950 text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <div class="mb-6">
                <img src="https://upload.wikimedia.org/wikipedia/ms/thumb/0/01/Logo_KBS.png/250px-Logo_KBS.png" alt="Logo" class="h-14 mx-auto mb-4 opacity-80">
                <p class="text-lg font-bold tracking-wider">JABATAN ELEKTRIK IKBN KINARUT SABAH</p>
                <p class="text-sm opacity-60">Urusetia Pengambilan Kursus 2026</p>
            </div>
            
            <p class="text-xs opacity-50 border-t border-blue-900 pt-6">
                &copy; Hakcipta Terpelihara Urusetia Pengambilan kursus 2026.
            </p>
        </div>
    </footer>

</body>
</html>
