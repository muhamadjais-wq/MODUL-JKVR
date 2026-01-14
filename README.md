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
            transition: background-color 0.3s ease;
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

        /* Simulator Styles */
        #view-simulator {
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            margin: 0 auto;
            background: white;
            overflow-x: hidden;
        }

        .mobile-mode {
            max-width: 375px !important;
            border: 12px solid #333;
            border-radius: 40px;
            height: 812px;
            overflow-y: auto;
            margin-top: 20px !important;
            margin-bottom: 20px !important;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
        }

        .desktop-mode {
            max-width: 100% !important;
        }

        .toggle-active {
            background-color: #1e3a8a !important;
            color: white !important;
        }

        @media (max-width: 768px) {
            #mode-toggle-bar {
                display: none; /* Sembunyikan toggle pada peranti sebenar untuk elak kekeliruan */
            }
            .logo-container img {
                height: 50px;
            }
            .header-title {
                font-size: 1rem !important;
            }
        }
    </style>
</head>
<body class="bg-gray-200">

    <!-- Mode Toggle Bar (Hanya muncul di Desktop untuk simulasi) -->
    <div id="mode-toggle-bar" class="bg-white border-b sticky top-0 z-[100] p-2 flex justify-center items-center gap-4 shadow-sm">
        <span class="text-xs font-bold text-gray-500 uppercase tracking-widest">Pilih Mod Paparan:</span>
        <div class="inline-flex p-1 bg-gray-100 rounded-lg">
            <button onclick="setMode('desktop')" id="btn-desktop" class="toggle-active px-4 py-2 rounded-md text-sm font-bold flex items-center transition-all">
                <i class="fas fa-desktop mr-2"></i> MOD KOMPUTER
            </button>
            <button onclick="setMode('mobile')" id="btn-mobile" class="px-4 py-2 rounded-md text-sm font-bold flex items-center transition-all text-gray-600 hover:bg-gray-200">
                <i class="fas fa-mobile-alt mr-2"></i> MOD HANDPONE
            </button>
        </div>
    </div>

    <!-- Wrapper for Simulator -->
    <div id="view-simulator" class="desktop-mode">

        <!-- Header Section -->
        <header class="bg-white shadow-md sticky top-0 z-50">
            <div class="container mx-auto px-4 py-3 flex items-center justify-between">
                <!-- Left Logo: Kerajaan Malaysia -->
                <div class="logo-container">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Coat_of_arms_of_Malaysia.svg" alt="Logo Kerajaan Malaysia" onerror="this.src='https://via.placeholder.com/80?text=JATA+NEGARA'">
                </div>
                
                <!-- Central Title -->
                <div class="text-center px-4">
                    <h1 class="header-title text-xl md:text-2xl font-bold text-blue-900 uppercase tracking-tight">
                        INFO DAN BORANG KURSUS MODUL JANAKUASA DENGAN PENYEGERAKAN
                    </h1>
                    <p class="text-xs md:text-sm text-gray-600 font-medium text-center">Jabatan Elektrik IKBN Kinarut Sabah</p>
                </div>

                <!-- Right Logo: IKBN -->
                <div class="logo-container">
                    <img src="https://upload.wikimedia.org/wikipedia/ms/thumb/0/01/Logo_KBS.png/250px-Logo_KBS.png" alt="Logo IKBN / KBS" onerror="this.src='https://via.placeholder.com/80?text=IKBN+LOGO'">
                </div>
            </div>
        </header>

        <!-- Hero Section -->
        <section class="hero-gradient text-white py-16">
            <div class="container mx-auto px-4 text-center">
                <h2 class="text-3xl md:text-5xl font-extrabold mb-6 leading-tight">Tingkatkan Kompetensi Elektrik Anda</h2>
                <p class="text-lg md:text-xl mb-10 opacity-90 max-w-2xl mx-auto">Sertai kursus moduler 80 jam diiktiraf ECoS Sabah. Masa depan kerjaya anda bermula di IKBN Kinarut.</p>
                <div class="flex flex-col md:flex-row justify-center gap-4">
                    <a href="#prosedur" class="bg-yellow-500 hover:bg-yellow-400 text-blue-900 font-bold py-4 px-8 rounded-full shadow-lg transition duration-300 flex items-center justify-center text-sm md:text-base">
                        <i class="fas fa-download mr-2"></i> MUAT TURUN BORANG & DAFTAR
                    </a>
                    <a href="#maklumat" class="bg-transparent border-2 border-white hover:bg-white hover:text-blue-900 font-bold py-4 px-8 rounded-full transition duration-300 text-sm md:text-base">
                        LIHAT SYARAT KELAYAKAN
                    </a>
                </div>
            </div>
        </section>

        <!-- Registration Steps & Download -->
        <section id="prosedur" class="py-12 bg-blue-50">
            <div class="container mx-auto px-4">
                <div class="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl overflow-hidden">
                    <div class="bg-blue-900 p-6 text-white text-center">
                        <h2 class="text-xl md:text-2xl font-bold uppercase tracking-wide">Langkah Pendaftaran & Muat Turun</h2>
                        <p class="text-blue-200 text-xs md:text-sm">Sila ikuti prosedur di bawah untuk kelancaran permohonan anda</p>
                    </div>
                    
                    <div class="p-6 md:p-8">
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="step-number mr-4">1</div>
                                <div>
                                    <h4 class="font-bold text-blue-900">Muat Turun Borang</h4>
                                    <p class="text-xs md:text-sm text-gray-600 mb-3">Klik butang di bawah untuk memuat turun borang permohonan rasmi.</p>
                                    <a href="https://drive.google.com/file/d/1715CZNVigrQBpf5nZ0Zne6Rne8xC8tUF/view" target="_blank" class="inline-flex items-center px-4 py-2 bg-blue-100 text-blue-800 rounded-lg hover:bg-blue-200 transition text-xs font-semibold">
                                        <i class="fas fa-file-pdf mr-2"></i> MUAT TURUN BORANG (.PDF)
                                    </a>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="step-number mr-4">2</div>
                                <div>
                                    <h4 class="font-bold text-blue-900 text-sm md:text-base">Lengkapkan Borang & Cop Majikan</h4>
                                    <p class="text-xs md:text-sm text-gray-600">Isi maklumat dengan lengkap dan dapatkan <strong>PENGESAHAN/COP MAJIKAN</strong>.</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="step-number mr-4">3</div>
                                <div>
                                    <h4 class="font-bold text-blue-900">Imbas & Muat Naik</h4>
                                    <p class="text-xs md:text-sm text-gray-600 mb-3">Muat naik borang lengkap ke dalam sistem online di bawah.</p>
                                    <a href="https://forms.gle/nKLba9HoKWWpQuVZ9" target="_blank" class="inline-flex items-center px-6 py-3 bg-yellow-500 text-blue-900 rounded-lg hover:bg-yellow-400 transition font-bold shadow-md text-xs md:text-sm">
                                        <i class="fas fa-external-link-alt mr-2"></i> BORANG PERMOHONAN (ONLINE)
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Main Content -->
        <main id="maklumat" class="container mx-auto px-4 py-12">
            <!-- Modul JKVR -->
            <div class="mb-16">
                <div class="flex items-center mb-8 border-b-4 border-blue-900 pb-2">
                    <span class="bg-blue-900 text-white p-3 rounded-lg mr-4">
                        <i class="fas fa-bolt fa-lg md:fa-2x"></i>
                    </span>
                    <h2 class="text-xl md:text-3xl font-bold text-blue-900 uppercase">Modul Janakuasa VR Dengan Penyegerakan</h2>
                </div>
                
                <div class="grid md:grid-cols-3 gap-6 md:gap-8">
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-yellow-500 card-hover">
                        <h3 class="font-bold text-lg mb-4 text-blue-800"><i class="fas fa-info-circle mr-2"></i> Info Kursus</h3>
                        <ul class="space-y-3 text-sm">
                            <li class="flex justify-between border-b pb-2"><span>Yuran:</span> <span class="font-bold text-green-600">RM 2,000</span></li>
                            <li class="flex justify-between border-b pb-2"><span>Tempoh:</span> <span class="font-bold">80 Jam</span></li>
                        </ul>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-yellow-500 card-hover md:col-span-2">
                        <h3 class="font-bold text-lg mb-4 text-blue-800"><i class="fas fa-user-check mr-2"></i> Syarat Kelayakan</h3>
                        <div class="grid md:grid-cols-2 gap-4 text-xs md:text-sm">
                            <ul class="list-disc ml-5 space-y-1">
                                <li><strong>A0:</strong> Min. 2 tahun.</li>
                                <li><strong>A1:</strong> Min. 1 tahun.</li>
                            </ul>
                            <ul class="list-disc ml-5 space-y-1 text-gray-600">
                                <li>Warganegara (20 thn+).</li>
                                <li>Buku Log lengkap.</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Modul MKP -->
            <div class="mb-16">
                <div class="flex items-center mb-8 border-b-4 border-red-800 pb-2">
                    <span class="bg-red-800 text-white p-3 rounded-lg mr-4">
                        <i class="fas fa-industry fa-lg md:fa-2x"></i>
                    </span>
                    <h2 class="text-xl md:text-3xl font-bold text-red-800 uppercase">Modul Pencawang (MKP) 11kV</h2>
                </div>
                
                <div class="grid md:grid-cols-3 gap-6">
                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-red-500 card-hover md:col-span-2">
                        <h3 class="font-bold text-lg mb-4 text-red-800"><i class="fas fa-clipboard-list mr-2"></i> Pengalaman Kerja</h3>
                        <ul class="space-y-2 text-xs md:text-sm">
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Perakuan PJ VR & Daftar ECoS.</li>
                            <li><i class="fas fa-check-circle text-green-500 mr-2"></i> Min. 3 tahun pengalaman elektrik.</li>
                        </ul>
                    </div>

                    <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-red-500 card-hover text-sm">
                        <h3 class="font-bold text-lg mb-4 text-red-800"><i class="fas fa-tag mr-2"></i> Butiran</h3>
                        <p class="border-b pb-2 mb-2">Yuran: <span class="font-bold text-red-600">RM 4,800</span></p>
                        <p>Kapasiti: <span class="font-bold">20 Calon</span></p>
                    </div>
                </div>
            </div>
        </main>

        <!-- Footer -->
        <footer class="bg-blue-950 text-white py-12">
            <div class="container mx-auto px-4 text-center">
                <div class="mb-6">
                    <img src="https://upload.wikimedia.org/wikipedia/ms/thumb/0/01/Logo_KBS.png/250px-Logo_KBS.png" alt="Logo" class="h-12 mx-auto mb-4 opacity-80">
                    <p class="text-base md:text-lg font-bold tracking-wider uppercase">Jabatan Elektrik IKBN Kinarut Sabah</p>
                    <p class="text-xs opacity-60">Urusetia Pengambilan Kursus 2026</p>
                </div>
                <p class="text-[10px] md:text-xs opacity-50 border-t border-blue-900 pt-6 px-4">
                    @hakcipta Terpelihara Urusetia Pengambilan kursus 2026. <br>
                    IKBN Kinarut, Papar, Sabah.
                </p>
            </div>
        </footer>
    </div>

    <!-- JavaScript untuk Simulai Mod Paparan -->
    <script>
        function setMode(mode) {
            const simulator = document.getElementById('view-simulator');
            const btnDesktop = document.getElementById('btn-desktop');
            const btnMobile = document.getElementById('btn-mobile');

            if (mode === 'mobile') {
                simulator.classList.remove('desktop-mode');
                simulator.classList.add('mobile-mode');
                
                btnMobile.classList.add('toggle-active');
                btnMobile.classList.remove('text-gray-600');
                
                btnDesktop.classList.remove('toggle-active');
                btnDesktop.classList.add('text-gray-600');
                
                document.body.style.backgroundColor = "#4b5563"; // Kelabu gelap untuk menyerlahkan bingkai fon
            } else {
                simulator.classList.remove('mobile-mode');
                simulator.classList.add('desktop-mode');
                
                btnDesktop.classList.add('toggle-active');
                btnDesktop.classList.remove('text-gray-600');
                
                btnMobile.classList.remove('toggle-active');
                btnMobile.classList.add('text-gray-600');
                
                document.body.style.backgroundColor = "#e5e7eb";
            }
        }
    </script>

</body>
</html>
