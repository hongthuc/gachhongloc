<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>GẠCH HỒNG LỘC - Gạch Ngói Đất Sét Nung Cao Cấp Đà Nẵng | gachhongloc.com</title>
    <meta name="description" content="Gạch Hồng Lộc (gachhongloc.com) - Chuyên phân phối Ngói lợp, Phụ kiện ngói, Gạch lát sân vườn, Gạch xây không trát Gốm Mỹ chính hãng tại TP Đà Nẵng và Miền Trung. Hotline: 0935.730.797.">

    <!-- Open Graph Thumbnail Logo khi chia sẻ link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://gachhongloc.com/">
    <meta property="og:title" content="GẠCH HỒNG LỘC - Gạch Ngói Đất Sét Nung Cao Cấp Đà Nẵng">
    <meta property="og:description" content="Phân phối Ngói lợp, Phụ kiện ngói, Gạch lát nền, Gạch xây không trát chính hãng tại TP Đà Nẵng. Liên hệ báo giá: 0935.730.797">
    <meta property="og:image" content="https://placehold.co/1200x630/991B1B/FFFFFF?text=GACH+HONG+LOC+-+gachhongloc.com+-+0935.730.797">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brick: {
                            50: '#fdf4f3',
                            100: '#fbe6e4',
                            200: '#f7d1cd',
                            500: '#c83e2b',
                            600: '#b02e1c',
                            700: '#932314',
                            800: '#7a1f13',
                            900: '#651d14',
                        },
                        clay: {
                            light: '#d97742',
                            DEFAULT: '#b84a27',
                            dark: '#852e12'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền tuyệt đối trên mọi thiết bị */
        html, body {
            overflow-x: hidden;
            max-width: 100vw;
            width: 100%;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
        }
        *, *::before, *::after {
            box-sizing: border-box;
        }

        /* Chuẩn cấu trúc Flatsome Section Title */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 0.65rem;
        }
        .section-title-main {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #932314;
            letter-spacing: 0.02em;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -0.75rem;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #b02e1c;
        }

        /* Flatsome Product Box & Quick View */
        .product-small {
            transition: transform 0.25s ease, box-shadow 0.25s ease;
        }
        .product-small:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px -5px rgba(147, 35, 20, 0.12), 0 8px 10px -6px rgba(0, 0, 0, 0.06);
        }
        .box-image {
            position: relative;
            overflow: hidden;
        }
        .quick-view-bar {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(147, 35, 20, 0.92);
            color: #ffffff;
            text-align: center;
            font-size: 0.75rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.05em;
            padding: 0.5rem 0.25rem;
            transform: translateY(100%);
            transition: transform 0.25s ease-in-out;
            cursor: pointer;
            z-index: 10;
        }
        .product-small:hover .quick-view-bar {
            transform: translateY(0);
        }
        /* Trên điện thoại vẫn có nút xem nhanh thuận tiện */
        @media (max-width: 767px) {
            .quick-view-bar {
                transform: translateY(0);
                background: rgba(147, 35, 20, 0.85);
                font-size: 0.68rem;
                padding: 0.35rem 0.2rem;
            }
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.9); opacity: 0.8; }
            70% { transform: scale(1.35); opacity: 0; }
            100% { transform: scale(1.35); opacity: 0; }
        }
        .floating-pulse::before {
            content: '';
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background-color: inherit;
            animation: pulse-ring 2s infinite;
            z-index: -1;
        }

        /* Tùy chỉnh thanh cuộn gọn gàng */
        ::-webkit-scrollbar {
            width: 8px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #932314;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">

    <!-- ==================== HEADER CHUẨN FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY TRÁNH TRÀN VIỀN) ==================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200 w-full">
        <!-- Top Bar mỏng gọn -->
        <div class="bg-brick-800 text-white text-xs py-1.5 px-3 sm:px-6">
            <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-building-columns text-amber-300"></i>
                    <span class="font-medium truncate">GẠCH HỒNG LỘC - Nhà Phân Phối Gạch Ngói Đất Sét Nung Cao Cấp</span>
                </div>
                <div class="hidden md:flex items-center gap-5 text-slate-100">
                    <span><i class="fa-solid fa-globe text-amber-300 mr-1"></i>gachhongloc.com</span>
                    <span><i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>TP Đà Nẵng</span>
                    <span><i class="fa-regular fa-clock text-amber-300 mr-1"></i>07:30 - 18:00 (T2 - CN)</span>
                </div>
            </div>
        </div>

        <!-- Header Main (Logo + Tìm kiếm + Giỏ báo giá - Không có nút Gọi ngay để chống tràn viền) -->
        <div class="max-w-7xl mx-auto px-3 sm:px-6 py-3">
            <div class="flex items-center justify-between gap-3">
                <!-- Nút mở menu trên Mobile -->
                <button onclick="toggleMobileMenu()" aria-label="Menu" class="lg:hidden p-2 rounded-lg text-slate-700 hover:bg-slate-100 focus:outline-none">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>

                <!-- Logo Thiết Kế Riêng GẠCH HỒNG LỘC -->
                <a href="#top" class="flex items-center gap-2.5 sm:gap-3 group min-w-0">
                    <div class="w-11 h-11 sm:w-13 sm:h-13 flex-shrink-0">
                        <!-- Custom SVG Logo Gạch Hồng Lộc -->
                        <svg viewBox="0 0 100 100" class="w-full h-full drop-shadow-sm rounded-xl">
                            <defs>
                                <linearGradient id="hlGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#b02e1c"/>
                                    <stop offset="100%" stop-color="#651d14"/>
                                </linearGradient>
                            </defs>
                            <rect width="100" height="100" rx="18" fill="url(#hlGrad)"/>
                            <!-- Mái ngói truyền thống cách điệu -->
                            <path d="M16 42 L50 18 L84 42 L77 48 L50 29 L23 48 Z" fill="#fbbf24"/>
                            <path d="M26 48 L50 32 L74 48 L70 53 L50 39 L30 53 Z" fill="#fde68a"/>
                            <!-- Khối gạch vững chắc chữ HL -->
                            <rect x="24" y="56" width="22" height="11" rx="2" fill="#ffffff"/>
                            <rect x="50" y="56" width="26" height="11" rx="2" fill="#fcd34d"/>
                            <rect x="24" y="71" width="32" height="11" rx="2" fill="#fcd34d"/>
                            <rect x="60" y="71" width="16" height="11" rx="2" fill="#ffffff"/>
                        </svg>
                    </div>
                    <div class="truncate">
                        <div class="text-base sm:text-xl font-extrabold tracking-tight text-brick-800 leading-tight truncate">
                            GẠCH HỒNG LỘC
                        </div>
                        <div class="text-[11px] sm:text-xs font-medium text-slate-500 truncate">
                            gachhongloc.com • Đẹp nơi nơi, bền mãi mãi
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Desktop) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input
                            id="desktopSearchInput"
                            type="text"
                            oninput="handleSearch(this.value)"
                            placeholder="Tìm ngói lợp, phụ kiện ngói, gạch lát, gạch xây..."
                            class="w-full pl-4 pr-10 py-2 text-sm bg-slate-100 border border-slate-200 rounded-full focus:outline-none focus:border-brick-600 focus:bg-white transition"
                        >
                        <button onclick="handleSearch(document.getElementById('desktopSearchInput').value)" class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-500 hover:text-brick-700">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Khu vực điều hướng nhanh sang Form Báo Giá (Nhỏ gọn, không tràn viền) -->
                <div class="flex items-center gap-2 flex-shrink-0">
                    <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-amber-50 text-brick-800 border border-amber-200 hover:bg-amber-100 text-xs sm:text-sm font-semibold transition">
                        <i class="fa-solid fa-file-invoice-dollar text-brick-600"></i>
                        <span class="hidden sm:inline">Nhận Báo Giá</span>
                        <span class="sm:hidden">Báo giá</span>
                    </a>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên Mobile -->
            <div class="mt-2.5 md:hidden">
                <div class="relative w-full">
                    <input
                        id="mobileSearchInput"
                        type="text"
                        oninput="handleSearch(this.value)"
                        placeholder="Tìm kiếm sản phẩm Gạch Hồng Lộc..."
                        class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-slate-100 border border-slate-200 rounded-full focus:outline-none focus:border-brick-600 focus:bg-white"
                    >
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-xs text-slate-400"></i>
                </div>
            </div>
        </div>

        <!-- Thanh Menu Chính (Desktop Navigation chuẩn Flatsome Header Bottom) -->
        <nav class="hidden lg:block bg-brick-700 text-white">
            <div class="max-w-7xl mx-auto px-6">
                <ul class="flex items-center space-x-1 text-sm font-semibold">
                    <li>
                        <a href="#top" class="block px-4 py-3 hover:bg-brick-800 transition">TRANG CHỦ</a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="block px-4 py-3 hover:bg-brick-800 transition">GIỚI THIỆU</a>
                    </li>
                    <!-- Dropdown Danh Mục Sản Phẩm lấy từ web mẫu gommy.com.vn -->
                    <li class="relative group">
                        <a href="#san-pham" class="flex items-center gap-1.5 px-4 py-3 hover:bg-brick-800 transition">
                            <span>SẢN PHẨM</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl rounded-b-xl border border-slate-100 opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-200 z-50">
                            <div class="py-1.5 divide-y divide-slate-100">
                                <button onclick="selectCategoryAndScroll('ngoi-lop')" class="w-full text-left px-4 py-2.5 hover:bg-brick-50 hover:text-brick-700 flex items-center justify-between text-xs font-semibold">
                                    <span>Ngói Lợp Đất Sét Nung</span>
                                    <span class="text-[11px] text-slate-400">22 SP</span>
                                </button>
                                <button onclick="selectCategoryAndScroll('phu-kien-ngoi')" class="w-full text-left px-4 py-2.5 hover:bg-brick-50 hover:text-brick-700 flex items-center justify-between text-xs font-semibold">
                                    <span>Phụ Kiện Ngói</span>
                                    <span class="text-[11px] text-slate-400">4 SP</span>
                                </button>
                                <button onclick="selectCategoryAndScroll('gach-lat')" class="w-full text-left px-4 py-2.5 hover:bg-brick-50 hover:text-brick-700 flex items-center justify-between text-xs font-semibold">
                                    <span>Gạch Lát Nền & Sân Vườn</span>
                                    <span class="text-[11px] text-slate-400">27 SP</span>
                                </button>
                                <button onclick="selectCategoryAndScroll('gach-xay')" class="w-full text-left px-4 py-2.5 hover:bg-brick-50 hover:text-brick-700 flex items-center justify-between text-xs font-semibold">
                                    <span>Gạch Xây Không Trát</span>
                                    <span class="text-[11px] text-slate-400">5 SP</span>
                                </button>
                                <button onclick="selectCategoryAndScroll('tam-op')" class="w-full text-left px-4 py-2.5 hover:bg-brick-50 hover:text-brick-700 flex items-center justify-between text-xs font-semibold">
                                    <span>Tấm Ốp & Gạch Trang Trí</span>
                                    <span class="text-[11px] text-slate-400">4 SP</span>
                                </button>
                            </div>
                        </div>
                    </li>
                    <li>
                        <a href="#du-an" class="block px-4 py-3 hover:bg-brick-800 transition">DỰ ÁN</a>
                    </li>
                    <li>
                        <a href="#tieu-chuan" class="block px-4 py-3 hover:bg-brick-800 transition">TIÊU CHUẨN KỸ THUẬT</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="block px-4 py-3 hover:bg-brick-800 transition">TIN TỨC & BÀI VIẾT</a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" class="block px-4 py-3 hover:bg-brick-800 transition">BÁO GIÁ</a>
                    </li>
                    <li>
                        <a href="#ban-do-fanpage" class="block px-4 py-3 hover:bg-brick-800 transition">LIÊN HỆ</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Mobile Drawer -->
        <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
            <div onclick="toggleMobileMenu()" class="fixed inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
            <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col justify-between overflow-y-auto z-10">
                <div>
                    <div class="p-4 bg-brick-800 text-white flex items-center justify-between">
                        <span class="font-bold text-sm tracking-wide">DANH MỤC GẠCH HỒNG LỘC</span>
                        <button onclick="toggleMobileMenu()" class="p-1 text-white/80 hover:text-white">
                            <i class="fa-solid fa-xmark text-lg"></i>
                        </button>
                    </div>
                    <div class="divide-y divide-slate-100 text-sm font-medium text-slate-700">
                        <a href="#top" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50">Trang chủ</a>
                        <a href="#danh-muc-chinh" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50 font-semibold text-brick-700">Danh mục sản phẩm</a>
                        <button onclick="selectCategoryAndScroll('ngoi-lop'); toggleMobileMenu()" class="w-full text-left pl-7 pr-4 py-2.5 text-xs hover:bg-slate-50 flex justify-between">
                            <span>• Ngói lợp đất sét nung</span><span>(22)</span>
                        </button>
                        <button onclick="selectCategoryAndScroll('phu-kien-ngoi'); toggleMobileMenu()" class="w-full text-left pl-7 pr-4 py-2.5 text-xs hover:bg-slate-50 flex justify-between">
                            <span>• Phụ kiện ngói</span><span>(4)</span>
                        </button>
                        <button onclick="selectCategoryAndScroll('gach-lat'); toggleMobileMenu()" class="w-full text-left pl-7 pr-4 py-2.5 text-xs hover:bg-slate-50 flex justify-between">
                            <span>• Gạch lát sân vườn & cotto</span><span>(27)</span>
                        </button>
                        <button onclick="selectCategoryAndScroll('gach-xay'); toggleMobileMenu()" class="w-full text-left pl-7 pr-4 py-2.5 text-xs hover:bg-slate-50 flex justify-between">
                            <span>• Gạch xây không trát</span><span>(5)</span>
                        </button>
                        <button onclick="selectCategoryAndScroll('tam-op'); toggleMobileMenu()" class="w-full text-left pl-7 pr-4 py-2.5 text-xs hover:bg-slate-50 flex justify-between">
                            <span>• Tấm ốp & Gạch trang trí</span><span>(4)</span>
                        </button>
                        <a href="#du-an" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50">Dự án tiêu biểu</a>
                        <a href="#tieu-chuan" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50">Tiêu chuẩn kỹ thuật</a>
                        <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50">Bài viết & Kinh nghiệm</a>
                        <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50">Yêu cầu báo giá</a>
                        <a href="#ban-do-fanpage" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-slate-50">Bản đồ & Fanpage</a>
                    </div>
                </div>
                <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
                    <div class="font-bold text-brick-800">GẠCH HỒNG LỘC - ĐÀ NẴNG</div>
                    <div>Website: gachhongloc.com</div>
                    <div>Hotline/Zalo: 0935.730.797</div>
                    <div>Địa chỉ: TP Đà Nẵng</div>
                </div>
            </div>
        </div>
    </header>

    <!-- ==================== MAIN CONTENT (CẤU TRÚC SECTION/ROW/COL FLATSOME) ==================== -->
    <main id="top" class="flex-grow w-full">

        <!-- SECTION 1: SLIDER 2 ẢNH BANNER TỰ TRƯỢT (FLATSOME UX SLIDER) -->
        <section class="relative w-full bg-slate-900 overflow-hidden">
            <div id="heroSlider" class="relative w-full h-[270px] sm:h-[380px] lg:h-[460px]">

                <!-- Slide 1: Ngói Lợp & Phụ Kiện Ngói Đất Sét Nung -->
                <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 flex items-center">
                    <!-- Đồ họa nền kiến trúc mái ngói truyền thống & hiện đại (SVG không bao giờ lỗi ảnh) -->
                    <div class="absolute inset-0 bg-gradient-to-r from-[#4a120b] via-[#7a1f13] to-[#932314]">
                        <svg class="w-full h-full opacity-25" viewBox="0 0 1440 500" preserveAspectRatio="xMidYMid slice">
                            <defs>
                                <pattern id="roofPattern1" width="60" height="40" patternUnits="userSpaceOnUse">
                                    <path d="M0 20 Q30 45 60 20" fill="none" stroke="#fca5a5" stroke-width="2.5"/>
                                    <path d="M30 0 Q60 25 90 0" fill="none" stroke="#fcd34d" stroke-width="1.5"/>
                                </pattern>
                            </defs>
                            <rect width="1440" height="500" fill="url(#roofPattern1)"/>
                            <polygon points="850,90 1350,240 1280,260 850,130 520,260 450,240" fill="#fbbf24" opacity="0.35"/>
                            <polygon points="920,180 1390,330 1330,350 920,210 600,350 540,330" fill="#ffffff" opacity="0.2"/>
                        </svg>
                    </div>

                    <div class="relative max-w-7xl mx-auto px-4 sm:px-6 w-full grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        <div class="lg:col-span-7 text-white space-y-2.5 sm:space-y-4">
                            <div class="text-amber-300 text-xs sm:text-sm font-bold tracking-wider uppercase">
                                GẠCH HỒNG LỘC • GACHHONGLOC.COM
                            </div>
                            <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight">
                                BẢO VỆ TỔ ẤM VIỆT VỚI NGÓI LỢP & GẠCH ĐẤT SÉT NUNG CAO CẤP
                            </h1>
                            <p class="text-xs sm:text-base text-amber-50/90 max-w-2xl line-clamp-2 sm:line-clamp-none">
                                Phân phối chính hãng Ngói lợp tráng men, Ngói đất nung, Phụ kiện ngói tại TP Đà Nẵng & Miền Trung. Độ bền trên 100 năm, mát mùa hè, ấm mùa đông.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap gap-2.5">
                                <a href="#san-pham" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-amber-400 hover:bg-amber-300 text-brick-900 font-bold text-xs sm:text-sm transition shadow">
                                    Khám Phá Sản Phẩm
                                </a>
                                <a href="#form-bao-gia" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                                    Nhận Báo Giá Sỉ & Lẻ
                                </a>
                            </div>
                        </div>

                        <!-- Minh họa 3D bộ sưu tập Ngói Lợp trên Banner 1 -->
                        <div class="hidden lg:flex lg:col-span-5 justify-end">
                            <div class="w-80 h-72 bg-white/10 backdrop-blur-xs rounded-2xl p-4 border border-white/20 shadow-2xl flex items-center justify-center">
                                <svg viewBox="0 0 320 260" class="w-full h-full">
                                    <!-- Mái ngói Indo & 22TL -->
                                    <rect x="15" y="15" width="290" height="230" rx="14" fill="#fff7ed" opacity="0.95"/>
                                    <path d="M40 95 L160 32 L280 95 L260 112 L160 58 L60 112 Z" fill="#b02e1c"/>
                                    <path d="M65 112 L160 62 L255 112 L240 126 L160 84 L80 126 Z" fill="#1e3a8a"/>
                                    <!-- Các viên ngói mẫu -->
                                    <rect x="45" y="140" width="68" height="65" rx="8" fill="#b02e1c"/>
                                    <rect x="126" y="140" width="68" height="65" rx="8" fill="#1e3a8a"/>
                                    <rect x="207" y="140" width="68" height="65" rx="8" fill="#312e81"/>
                                    <text x="160" y="226" text-anchor="middle" fill="#7a1f13" font-size="13" font-weight="bold">NGÓI INDO & NGÓI 22TL TRÁNG MEN</text>
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Slide 2: Gạch Lát Sân Vườn & Gạch Xây Không Trát -->
                <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none z-0 flex items-center">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#2c1810] via-[#651d14] to-[#9a3412]">
                        <svg class="w-full h-full opacity-25" viewBox="0 0 1440 500" preserveAspectRatio="xMidYMid slice">
                            <defs>
                                <pattern id="brickWallPattern" width="80" height="40" patternUnits="userSpaceOnUse">
                                    <rect x="0" y="0" width="76" height="18" fill="none" stroke="#fdba74" stroke-width="1.5"/>
                                    <rect x="38" y="20" width="76" height="18" fill="none" stroke="#fdba74" stroke-width="1.5"/>
                                    <rect x="-42" y="20" width="76" height="18" fill="none" stroke="#fdba74" stroke-width="1.5"/>
                                </pattern>
                            </defs>
                            <rect width="1440" height="500" fill="url(#brickWallPattern)"/>
                        </svg>
                    </div>

                    <div class="relative max-w-7xl mx-auto px-4 sm:px-6 w-full grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        <div class="lg:col-span-7 text-white space-y-2.5 sm:space-y-4">
                            <div class="text-amber-300 text-xs sm:text-sm font-bold tracking-wider uppercase">
                                KHÔNG GIAN SỐNG GIẢN DỊ & ẤM CÚNG
                            </div>
                            <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight">
                                GẠCH LÁT SÂN VƯỜN CAO CẤP & GẠCH XÂY KHÔNG TRÁT ĐẤT NUNG
                            </h2>
                            <p class="text-xs sm:text-base text-amber-50/90 max-w-2xl line-clamp-2 sm:line-clamp-none">
                                Quy trình kiểm soát chất lượng nghiêm ngặt, chống rêu mốc, chịu lực cao. Giải pháp hoàn hảo cho biệt thự, resort, nhà phố và công trình tâm linh tại Đà Nẵng.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap gap-2.5">
                                <button onclick="selectCategoryAndScroll('gach-lat')" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-amber-400 hover:bg-amber-300 text-brick-900 font-bold text-xs sm:text-sm transition shadow">
                                    Xem Gạch Lát Sân Vườn
                                </button>
                                <button onclick="selectCategoryAndScroll('gach-xay')" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                                    Xem Gạch Xây Không Trát
                                </button>
                            </div>
                        </div>

                        <!-- Minh họa 3D Gạch Lát & Gạch Xây Không Trát trên Banner 2 -->
                        <div class="hidden lg:flex lg:col-span-5 justify-end">
                            <div class="w-80 h-72 bg-white/10 backdrop-blur-xs rounded-2xl p-4 border border-white/20 shadow-2xl flex items-center justify-center">
                                <svg viewBox="0 0 320 260" class="w-full h-full">
                                    <rect x="15" y="15" width="290" height="230" rx="14" fill="#fffbeb" opacity="0.95"/>
                                    <!-- Gạch sân vườn hoa văn -->
                                    <rect x="40" y="38" width="110" height="110" rx="8" fill="#b45309" stroke="#78350f" stroke-width="3"/>
                                    <circle cx="95" cy="93" r="34" fill="none" stroke="#fde68a" stroke-width="4"/>
                                    <rect x="75" y="73" width="40" height="40" transform="rotate(45 95 93)" fill="#fef3c7"/>
                                    <!-- Khối gạch xây 3 lỗ không trát -->
                                    <rect x="168" y="45" width="112" height="46" rx="5" fill="#9a3412"/>
                                    <circle cx="192" cy="68" r="8" fill="#431407"/>
                                    <circle cx="224" cy="68" r="8" fill="#431407"/>
                                    <circle cx="256" cy="68" r="8" fill="#431407"/>
                                    <rect x="168" y="102" width="112" height="46" rx="5" fill="#b02e1c"/>
                                    <circle cx="192" cy="125" r="8" fill="#431407"/>
                                    <circle cx="224" cy="125" r="8" fill="#431407"/>
                                    <circle cx="256" cy="125" r="8" fill="#431407"/>
                                    <text x="160" y="192" text-anchor="middle" fill="#7a1f13" font-size="13" font-weight="bold">GẠCH SÂN VƯỜN & GẠCH XÂY KHÔNG TRÁT</text>
                                    <text x="160" y="216" text-anchor="middle" fill="#9a3412" font-size="11" font-weight="600">Hotline Đà Nẵng: 0935.730.797</text>
                                </svg>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider trái/phải -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Dots chỉ báo 2 banner -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" id="slideDot0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToSlide(1)" id="slideDot1" class="w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </section>

        <!-- SECTION 2: 4 CAM KẾT CHẤT LƯỢNG (FLATSOME ICON BOXES) -->
        <section class="bg-white border-b border-slate-200 py-5 sm:py-7">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6">
                    <div class="flex items-start sm:items-center gap-3 p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <div class="w-10 h-10 rounded-lg bg-brick-100 text-brick-700 flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-medal text-lg"></i>
                        </div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Đất Sét Nung Tự Nhiên</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500">Bền màu, không rêu mốc</p>
                        </div>
                    </div>
                    <div class="flex items-start sm:items-center gap-3 p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <div class="w-10 h-10 rounded-lg bg-brick-100 text-brick-700 flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-truck-fast text-lg"></i>
                        </div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Giao Nhanh Tại Đà Nẵng</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500">Vận chuyển tận chân công trình</p>
                        </div>
                    </div>
                    <div class="flex items-start sm:items-center gap-3 p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <div class="w-10 h-10 rounded-lg bg-brick-100 text-brick-700 flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-tags text-lg"></i>
                        </div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Giá Gốc Nhà Máy</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500">Chiết khấu cao cho thầu & đại lý</p>
                        </div>
                    </div>
                    <div class="flex items-start sm:items-center gap-3 p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <div class="w-10 h-10 rounded-lg bg-brick-100 text-brick-700 flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-headset text-lg"></i>
                        </div>
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800">Tư Vấn Kỹ Thuật 24/7</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500">Hotline: 0935.730.797</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: DANH MỤC SẢN PHẨM TỐI ƯU TRÊN MÁY TÍNH & ĐIỆN THOẠI (LẤY TỪ GOMMY.COM.VN) -->
        <section id="danh-muc-chinh" class="py-8 sm:py-12 bg-slate-50">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-xl">KHÁM PHÁ DANH MỤC SẢN PHẨM</h2>
                        <span class="text-xs sm:text-sm text-slate-500 hidden sm:inline">Đẹp nơi nơi, bền mãi mãi</span>
                    </div>
                </div>

                <!-- Grid Danh Mục: 2 cột trên điện thoại, 5 cột cân đối sang trọng trên máy tính -->
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-5">
                    <!-- Danh mục 1: Ngói lợp -->
                    <div onclick="selectCategoryAndScroll('ngoi-lop')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 hover:border-brick-600 p-3 sm:p-4 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div class="w-full aspect-[4/3] rounded-lg bg-orange-50 flex items-center justify-center overflow-hidden mb-3">
                            <svg viewBox="0 0 160 120" class="w-4/5 h-4/5 group-hover:scale-105 transition duration-300">
                                <path d="M18 75 L80 28 L142 75 L128 88 L80 50 L32 88 Z" fill="#b02e1c"/>
                                <path d="M35 88 L80 54 L125 88 L115 98 L80 72 L45 98 Z" fill="#1e3a8a"/>
                            </svg>
                        </div>
                        <div class="text-center">
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 group-hover:text-brick-700 transition">Ngói Lợp</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5">22 Sản phẩm</p>
                        </div>
                    </div>

                    <!-- Danh mục 2: Phụ kiện ngói -->
                    <div onclick="selectCategoryAndScroll('phu-kien-ngoi')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 hover:border-brick-600 p-3 sm:p-4 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div class="w-full aspect-[4/3] rounded-lg bg-amber-50 flex items-center justify-center overflow-hidden mb-3">
                            <svg viewBox="0 0 160 120" class="w-4/5 h-4/5 group-hover:scale-105 transition duration-300">
                                <path d="M25 78 Q80 22 135 78 L122 92 Q80 46 38 92 Z" fill="#932314"/>
                                <circle cx="80" cy="66" r="10" fill="#fbbf24"/>
                            </svg>
                        </div>
                        <div class="text-center">
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 group-hover:text-brick-700 transition">Phụ Kiện Ngói</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5">4 Sản phẩm</p>
                        </div>
                    </div>

                    <!-- Danh mục 3: Gạch lát -->
                    <div onclick="selectCategoryAndScroll('gach-lat')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 hover:border-brick-600 p-3 sm:p-4 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div class="w-full aspect-[4/3] rounded-lg bg-red-50 flex items-center justify-center overflow-hidden mb-3">
                            <svg viewBox="0 0 160 120" class="w-4/5 h-4/5 group-hover:scale-105 transition duration-300">
                                <rect x="35" y="15" width="90" height="90" rx="8" fill="#b84a27" stroke="#7a1f13" stroke-width="3"/>
                                <circle cx="80" cy="60" r="26" fill="none" stroke="#fde68a" stroke-width="3"/>
                                <rect x="64" y="44" width="32" height="32" transform="rotate(45 80 60)" fill="#fef3c7"/>
                            </svg>
                        </div>
                        <div class="text-center">
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 group-hover:text-brick-700 transition">Gạch Lát</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5">27 Sản phẩm</p>
                        </div>
                    </div>

                    <!-- Danh mục 4: Gạch xây không trát -->
                    <div onclick="selectCategoryAndScroll('gach-xay')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 hover:border-brick-600 p-3 sm:p-4 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div class="w-full aspect-[4/3] rounded-lg bg-orange-50/80 flex items-center justify-center overflow-hidden mb-3">
                            <svg viewBox="0 0 160 120" class="w-4/5 h-4/5 group-hover:scale-105 transition duration-300">
                                <rect x="22" y="26" width="116" height="32" rx="4" fill="#9a3412"/>
                                <circle cx="48" cy="42" r="6" fill="#431407"/>
                                <circle cx="80" cy="42" r="6" fill="#431407"/>
                                <circle cx="112" cy="42" r="6" fill="#431407"/>
                                <rect x="22" y="65" width="116" height="32" rx="4" fill="#b02e1c"/>
                                <circle cx="48" cy="81" r="6" fill="#431407"/>
                                <circle cx="80" cy="81" r="6" fill="#431407"/>
                                <circle cx="112" cy="81" r="6" fill="#431407"/>
                            </svg>
                        </div>
                        <div class="text-center">
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 group-hover:text-brick-700 transition">Gạch Xây Không Trát</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5">5 Sản phẩm</p>
                        </div>
                    </div>

                    <!-- Danh mục 5: Tấm ốp & Gạch trang trí -->
                    <div onclick="selectCategoryAndScroll('tam-op')" class="col-span-2 md:col-span-1 group cursor-pointer bg-white rounded-xl border border-slate-200 hover:border-brick-600 p-3 sm:p-4 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div class="w-full aspect-[4/3] max-h-28 md:max-h-none rounded-lg bg-stone-100 flex items-center justify-center overflow-hidden mb-3">
                            <svg viewBox="0 0 160 120" class="w-4/5 h-4/5 group-hover:scale-105 transition duration-300">
                                <rect x="24" y="22" width="52" height="22" rx="3" fill="#b02e1c"/>
                                <rect x="82" y="22" width="54" height="22" rx="3" fill="#932314"/>
                                <rect x="24" y="50" width="34" height="22" rx="3" fill="#78350f"/>
                                <rect x="64" y="50" width="72" height="22" rx="3" fill="#b45309"/>
                                <rect x="24" y="78" width="64" height="22" rx="3" fill="#9a3412"/>
                                <rect x="94" y="78" width="42" height="22" rx="3" fill="#b02e1c"/>
                            </svg>
                        </div>
                        <div class="text-center">
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 group-hover:text-brick-700 transition">Tấm Ốp & Trang Trí</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5">4 Sản phẩm</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: DANH SÁCH SẢN PHẨM THEO DANH MỤC (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT TRÊN MÁY TÍNH, CÓ XEM NHANH & GIÁ GIẢM) -->
        <section id="san-pham" class="py-8 sm:py-12 bg-white">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <!-- Tiêu đề + Bộ lọc Tab Danh mục -->
                <div class="section-title-container">
                    <div class="section-title flex-wrap gap-3">
                        <h2 class="section-title-main text-base sm:text-xl">SẢN PHẨM GẠCH HỒNG LỘC</h2>
                        <!-- Các nút lọc danh mục trên máy tính & điện thoại -->
                        <div id="categoryFilterTabs" class="flex flex-wrap items-center gap-1.5 sm:gap-2 pt-2 sm:pt-0">
                            <button onclick="filterProducts('all')" data-cat="all" class="cat-tab px-3 py-1.5 rounded-lg text-xs font-bold bg-brick-700 text-white transition">
                                Tất cả
                            </button>
                            <button onclick="filterProducts('ngoi-lop')" data-cat="ngoi-lop" class="cat-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brick-50 hover:text-brick-700 transition">
                                Ngói lợp
                            </button>
                            <button onclick="filterProducts('phu-kien-ngoi')" data-cat="phu-kien-ngoi" class="cat-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brick-50 hover:text-brick-700 transition">
                                Phụ kiện ngói
                            </button>
                            <button onclick="filterProducts('gach-lat')" data-cat="gach-lat" class="cat-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brick-50 hover:text-brick-700 transition">
                                Gạch lát
                            </button>
                            <button onclick="filterProducts('gach-xay')" data-cat="gach-xay" class="cat-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brick-50 hover:text-brick-700 transition">
                                Gạch xây không trát
                            </button>
                            <button onclick="filterProducts('tam-op')" data-cat="tam-op" class="cat-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brick-50 hover:text-brick-700 transition">
                                Tấm ốp
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Grid Sản Phẩm: Chia đúng 2 cột trên điện thoại (grid-cols-2), 3 cột trên tablet, 4 cột trên máy tính -->
                <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Sản phẩm được render tự động bằng JS bên dưới với hình vẽ SVG sắc nét không lỗi ảnh -->
                </div>
            </div>
        </section>

        <!-- SECTION 5: GIỚI THIỆU & TIÊU CHUẨN KỸ THUẬT (THEO MẪU GOMMY.COM.VN) -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-slate-50 border-t border-slate-200">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-6 space-y-4">
                        <div class="section-title-container mb-2">
                            <div class="section-title">
                                <h2 class="section-title-main text-base sm:text-xl">VỀ GẠCH HỒNG LỘC ĐÀ NẴNG</h2>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-slate-700 leading-relaxed">
                            <strong>GẠCH HỒNG LỘC (<a href="https://gachhongloc.com" class="text-brick-700 underline">gachhongloc.com</a>)</strong> tự hào là đơn vị cung ứng các dòng sản phẩm gạch ngói đất sét nung cao cấp Gốm Mỹ tại <strong>TP Đà Nẵng</strong> và khu vực Miền Trung với mẫu mã đẹp độc đáo, màu sắc đỏ tự nhiên cùng các dòng ngói tráng men sang trọng, bền bỉ với thời gian.
                        </p>
                        <div id="tieu-chuan" class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
                            <div class="p-3.5 bg-white rounded-xl border border-slate-200">
                                <h3 class="font-bold text-sm text-brick-800 mb-1"><i class="fa-solid fa-fire-burner mr-1.5 text-brick-600"></i>Công Nghệ Nung Hiện Đại</h3>
                                <p class="text-xs text-slate-600">Đất sét được ngâm ủ kỹ lưỡng 4–5 tháng, nung ở nhiệt độ cao giúp viên gạch ngói đanh chắc, âm thanh trong trẻo, chịu lực vượt trội.</p>
                            </div>
                            <div class="p-3.5 bg-white rounded-xl border border-slate-200">
                                <h3 class="font-bold text-sm text-brick-800 mb-1"><i class="fa-solid fa-temperature-arrow-down mr-1.5 text-brick-600"></i>Cách Nhiệt & Bền Màu</h3>
                                <p class="text-xs text-slate-600">Điều hòa nhiệt độ tự nhiên: mát mẻ vào mùa hè, ấm áp vào mùa đông, thích ứng hoàn hảo với khí hậu nắng mưa miền Trung.</p>
                            </div>
                        </div>
                    </div>

                    <!-- Sơ đồ cấu trúc mái ngói & thông số kỹ thuật -->
                    <div class="lg:col-span-6">
                        <div class="bg-white p-4 sm:p-6 rounded-2xl border border-slate-200 shadow-xs">
                            <h3 class="font-bold text-sm sm:text-base text-brick-800 mb-3 uppercase">Tiêu Chuẩn Kỹ Thuật Gạch Ngói Đất Sét Nung</h3>
                            <div class="overflow-x-auto">
                                <table class="w-full text-left border-collapse text-xs sm:text-sm">
                                    <thead>
                                        <tr class="bg-slate-100 text-slate-700">
                                            <th class="p-2.5 border border-slate-200">Dòng sản phẩm</th>
                                            <th class="p-2.5 border border-slate-200">Kích thước (mm)</th>
                                            <th class="p-2.5 border border-slate-200">Định mức / m²</th>
                                        </tr>
                                    </thead>
                                    <tbody class="divide-y divide-slate-200 text-slate-600">
                                        <tr>
                                            <td class="p-2.5 border border-slate-200 font-semibold text-slate-800">Ngói Indo Tráng Men</td>
                                            <td class="p-2.5 border border-slate-200">335 x 248 x 12</td>
                                            <td class="p-2.5 border border-slate-200">14.5 viên/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="p-2.5 border border-slate-200 font-semibold text-slate-800">Ngói 22TL Men Bóng</td>
                                            <td class="p-2.5 border border-slate-200">340 x 205 x 13</td>
                                            <td class="p-2.5 border border-slate-200">22 viên/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="p-2.5 border border-slate-200 font-semibold text-slate-800">Gạch Sân Vườn GSV</td>
                                            <td class="p-2.5 border border-slate-200">400 x 400 x 14</td>
                                            <td class="p-2.5 border border-slate-200">6.25 viên/m²</td>
                                        </tr>
                                        <tr>
                                            <td class="p-2.5 border border-slate-200 font-semibold text-slate-800">Gạch Xây Không Trát</td>
                                            <td class="p-2.5 border border-slate-200">210 x 100 x 60</td>
                                            <td class="p-2.5 border border-slate-200">65 viên/m²</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 6: DANH MỤC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG & MIỀN TRUNG -->
        <section id="du-an" class="py-10 sm:py-12 bg-white border-t border-slate-200">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-xl">DANH MỤC DỰ ÁN TIÊU BIỂU</h2>
                        <span class="text-xs sm:text-sm text-slate-500 hidden sm:inline">Công trình thực tế sử dụng Gạch Hồng Lộc</span>
                    </div>
                </div>

                <!-- Grid Dự Án: 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-6">
                    <!-- Dự án 1 -->
                    <div class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:shadow-md transition">
                        <div class="aspect-[16/10] bg-gradient-to-br from-brick-800 to-amber-900 flex items-center justify-center p-4">
                            <svg viewBox="0 0 300 180" class="w-full h-full">
                                <rect width="300" height="180" rx="10" fill="#fff7ed"/>
                                <polygon points="30,95 150,25 270,95" fill="#1e3a8a"/>
                                <rect x="65" y="95" width="170" height="65" fill="#fef3c7" stroke="#b45309" stroke-width="2"/>
                                <rect x="130" y="115" width="40" height="45" fill="#78350f"/>
                            </svg>
                        </div>
                        <div class="p-3 sm:p-4">
                            <div class="text-[11px] font-semibold text-brick-700 uppercase">Biệt Thự Nghỉ Dưỡng • Sơn Trà, Đà Nẵng</div>
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 mt-1 line-clamp-2">Khu Biệt Thự Mái Ngói Indo Men Bóng Xanh Dương</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1 hidden sm:block">Cung cấp 18.000 viên ngói Indo men bóng và đồng bộ phụ kiện ngói nóc, ngói rìa.</p>
                        </div>
                    </div>

                    <!-- Dự án 2 -->
                    <div class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:shadow-md transition">
                        <div class="aspect-[16/10] bg-gradient-to-br from-amber-800 to-stone-800 flex items-center justify-center p-4">
                            <svg viewBox="0 0 300 180" class="w-full h-full">
                                <rect width="300" height="180" rx="10" fill="#fef2f2"/>
                                <polygon points="25,95 150,22 275,95" fill="#b02e1c"/>
                                <rect x="60" y="95" width="180" height="65" fill="#9a3412"/>
                                <line x1="60" y1="115" x2="240" y2="115" stroke="#fde68a" stroke-width="2"/>
                                <line x1="60" y1="135" x2="240" y2="135" stroke="#fde68a" stroke-width="2"/>
                            </svg>
                        </div>
                        <div class="p-3 sm:p-4">
                            <div class="text-[11px] font-semibold text-brick-700 uppercase">Nhà Thờ Tộc & Tâm Linh • Hòa Vang, Đà Nẵng</div>
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 mt-1 line-clamp-2">Công Trình Nhà Cổ Ngói Mũi Hài & Gạch Xây Không Trát</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1 hidden sm:block">Sử dụng gạch xây không trát 3 lỗ kết hợp ngói vảy cá và gạch lát cotto đỏ truyền thống.</p>
                        </div>
                    </div>

                    <!-- Dự án 3 -->
                    <div class="col-span-2 lg:col-span-1 group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:shadow-md transition">
                        <div class="aspect-[16/10] bg-gradient-to-br from-stone-800 to-brick-900 flex items-center justify-center p-4">
                            <svg viewBox="0 0 300 180" class="w-full h-full">
                                <rect width="300" height="180" rx="10" fill="#fffbeb"/>
                                <rect x="40" y="30" width="65" height="65" rx="4" fill="#b84a27"/>
                                <rect x="115" y="30" width="65" height="65" rx="4" fill="#932314"/>
                                <rect x="190" y="30" width="65" height="65" rx="4" fill="#b84a27"/>
                                <rect x="40" y="102" width="65" height="55" rx="4" fill="#932314"/>
                                <rect x="115" y="102" width="65" height="55" rx="4" fill="#b84a27"/>
                                <rect x="190" y="102" width="65" height="55" rx="4" fill="#932314"/>
                            </svg>
                        </div>
                        <div class="p-3 sm:p-4">
                            <div class="text-[11px] font-semibold text-brick-700 uppercase">Resort & Cafe Sân Vườn • Ngũ Hành Sơn, Đà Nẵng</div>
                            <h3 class="font-bold text-xs sm:text-base text-slate-800 mt-1 line-clamp-2">Tổ Hợp Sân Vườn Lát Gạch GSV48002 & GSV5032</h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1 hidden sm:block">Hơn 1.200m² sân vườn lát gạch đất nung định hình chống trơn trượt, kiến tạo không gian mộc mạc.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 7: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ -->
        <section id="form-bao-gia" class="py-10 sm:py-14 bg-gradient-to-br from-brick-800 via-brick-700 to-brick-900 text-white">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <!-- Thông tin hỗ trợ báo giá -->
                    <div class="lg:col-span-5 space-y-4">
                        <div class="text-amber-300 text-xs sm:text-sm font-bold uppercase tracking-wider">
                            BÁO GIÁ NHANH TRONG 5 PHÚT
                        </div>
                        <h2 class="text-xl sm:text-3xl font-extrabold leading-tight">
                             ĐĂNG KÝ NHẬN BÁO GIÁ & CHIẾT KHẤU CÔNG TRÌNH
                        </h2>
                        <p class="text-xs sm:text-sm text-amber-50/90 leading-relaxed">
                            Quý khách hàng, nhà thầu xây dựng, kiến trúc sư cần báo giá sỉ & lẻ các dòng <strong>Ngói lợp, Phụ kiện ngói, Gạch lát sân vườn, Gạch xây không trát</strong> tại Đà Nẵng vui lòng để lại thông tin hoặc liên hệ trực tiếp Hotline <strong>0935.730.797</strong>.
                        </p>
                        <div class="space-y-2.5 pt-2 text-xs sm:text-sm">
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-amber-300"></i>
                                <span>Hỗ trợ tính toán số lượng viên ngói / m² chính xác theo bản vẽ mái</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-amber-300"></i>
                                <span>Gửi mẫu gạch ngói thực tế tận công trình tại TP Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-circle-check text-amber-300"></i>
                                <span>Cam kết hàng chính hãng loại 1, bảo hành độ bền màu</span>
                            </div>
                        </div>
                    </div>

                    <!-- Form Yêu Cầu Báo Giá Chuẩn Flatsome -->
                    <div class="lg:col-span-7">
                        <div class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
                            <h3 class="text-base sm:text-lg font-extrabold text-brick-800 mb-4 uppercase border-b border-slate-100 pb-2.5">
                                Form Yêu Cầu Tư Vấn & Báo Giá
                            </h3>
                            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên Quý khách *</label>
                                        <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brick-600">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                        <input type="tel" id="qPhone" required placeholder="Ví dụ: 0935730797" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brick-600">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục sản phẩm quan tâm *</label>
                                        <select id="qCategory" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brick-600 bg-white">
                                            <option value="Ngói lợp các loại">Ngói lợp (Ngói Indo, Ngói 22TL, Ngói hài...)</option>
                                            <option value="Phụ kiện ngói">Phụ kiện ngói (Ngói nóc, Ngói rìa, Cuối mái...)</option>
                                            <option value="Gạch lát sân vườn & Cotto">Gạch lát sân vườn cao cấp GSV & Gạch Cotto</option>
                                            <option value="Gạch xây không trát">Gạch xây không trát 3 lỗ / Gạch đặc</option>
                                            <option value="Trọn gói gạch ngói công trình">Báo giá trọn gói cả công trình</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-slate-700 mb-1">Diện tích hoặc Số lượng dự kiến</label>
                                        <input type="text" id="qQuantity" placeholder="Ví dụ: 150 m² hoặc 3.000 viên" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brick-600">
                                    </div>
                                </div>

                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ giao hàng & Ghi chú thêm</label>
                                    <textarea id="qNote" rows="2" placeholder="Nhập khu vực công trình tại Đà Nẵng hoặc yêu cầu chi tiết..." class="w-full px-3.5 py-2 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brick-600"></textarea>
                                </div>

                                <button type="submit" class="w-full py-3 px-6 rounded-xl bg-brick-700 hover:bg-brick-800 text-white font-bold text-sm uppercase tracking-wide transition shadow-md cursor-pointer">
                                    <i class="fa-solid fa-paper-plane mr-2"></i>Gửi Yêu Cầu Báo Giá Ngay
                                </button>
                            </form>

                            <!-- Hộp thông báo sau khi gửi form (Không dùng alert) -->
                            <div id="quoteSuccessBox" class="hidden mt-4 p-4 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm">
                                <div class="font-bold flex items-center gap-2">
                                    <i class="fa-solid fa-circle-check text-emerald-600 text-base"></i>
                                    <span>Đã gửi yêu cầu báo giá thành công!</span>
                                </div>
                                <p id="quoteSuccessText" class="mt-1 text-emerald-700"></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM) -->
        <section id="tin-tuc" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-200">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="section-title-container">
                    <div class="section-title flex-wrap gap-2">
                        <h2 class="section-title-main text-base sm:text-xl">DANH MỤC BÀI VIẾT & KINH NGHIỆM</h2>
                        <div class="flex flex-wrap gap-1.5">
                            <button onclick="filterPosts('all')" class="post-tab px-2.5 py-1 rounded text-xs font-bold bg-brick-700 text-white">Tất cả bài viết</button>
                            <button onclick="filterPosts('ky-thuat')" class="post-tab px-2.5 py-1 rounded text-xs font-medium bg-white border border-slate-200 text-slate-700 hover:text-brick-700">Kỹ thuật lợp ngói</button>
                            <button onclick="filterPosts('kien-truc')" class="post-tab px-2.5 py-1 rounded text-xs font-medium bg-white border border-slate-200 text-slate-700 hover:text-brick-700">Xu hướng kiến trúc</button>
                        </div>
                    </div>
                </div>

                <!-- Grid Bài viết: 1 cột trên mobile nhỏ, 3 cột trên máy tính -->
                <div id="blogGrid" class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                    <!-- Bài viết 1 -->
                    <article data-post-cat="ky-thuat" class="blog-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="aspect-[16/9] bg-amber-100 flex items-center justify-center p-4">
                                <svg viewBox="0 0 280 140" class="w-full h-full">
                                    <rect width="280" height="140" rx="8" fill="#7a1f13"/>
                                    <path d="M35 95 Q140 25 245 95" fill="none" stroke="#fbbf24" stroke-width="6"/>
                                    <text x="140" y="115" text-anchor="middle" fill="#ffffff" font-size="13" font-weight="bold">CÁCH LỢP NGÓI RÌA & NGÓI NÓC</text>
                                </svg>
                            </div>
                            <div class="p-4">
                                <div class="text-[11px] font-bold text-brick-600 uppercase">Kỹ thuật lợp ngói</div>
                                <h3 class="font-bold text-sm sm:text-base text-slate-800 mt-1 hover:text-brick-700 cursor-pointer" onclick="openArticleModal(0)">
                                    Ngói rìa và ngói nóc là gì? Hướng dẫn kỹ thuật lợp ngói chuẩn thẩm mỹ
                                </h3>
                                <p class="text-xs text-slate-500 mt-2 line-clamp-3">
                                    Ngói rìa và ngói nóc là phụ kiện đi liền với ngói lợp chính, giữ vai trò chống thấm dột ở đỉnh mái và hai bên hông mái, tạo nên kết cấu mái ngói hoàn chỉnh.
                                </p>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <button onclick="openArticleModal(0)" class="text-xs font-bold text-brick-700 hover:underline">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article data-post-cat="kien-truc" class="blog-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="aspect-[16/9] bg-orange-100 flex items-center justify-center p-4">
                                <svg viewBox="0 0 280 140" class="w-full h-full">
                                    <rect width="280" height="140" rx="8" fill="#9a3412"/>
                                    <rect x="45" y="28" width="85" height="28" rx="3" fill="#fdba74"/>
                                    <rect x="140" y="28" width="95" height="28" rx="3" fill="#fed7aa"/>
                                    <rect x="45" y="64" width="190" height="28" rx="3" fill="#fb923c"/>
                                    <text x="140" y="118" text-anchor="middle" fill="#ffffff" font-size="13" font-weight="bold">TƯỜNG GẠCH XÂY KHÔNG TRÁT</text>
                                </svg>
                            </div>
                            <div class="p-4">
                                <div class="text-[11px] font-bold text-brick-600 uppercase">Xu hướng kiến trúc</div>
                                <h3 class="font-bold text-sm sm:text-base text-slate-800 mt-1 hover:text-brick-700 cursor-pointer" onclick="openArticleModal(1)">
                                    Vì sao gia chủ lại lựa chọn gạch xây không trát cho nhà phố và biệt thự?
                                </h3>
                                <p class="text-xs text-slate-500 mt-2 line-clamp-3">
                                    Gạch xây không trát đất sét nung mang vẻ đẹp mộc mạc, vuông vắn, vừa tiết kiệm chi phí trát vữa sơn tường vừa cách âm, cách nhiệt hiệu quả.
                                </p>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <button onclick="openArticleModal(1)" class="text-xs font-bold text-brick-700 hover:underline">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                            </button>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article data-post-cat="kien-truc" class="blog-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-xs hover:shadow-md transition flex flex-col justify-between">
                        <div>
                            <div class="aspect-[16/9] bg-red-100 flex items-center justify-center p-4">
                                <svg viewBox="0 0 280 140" class="w-full h-full">
                                    <rect width="280" height="140" rx="8" fill="#651d14"/>
                                    <circle cx="140" cy="60" r="32" fill="none" stroke="#fde68a" stroke-width="4"/>
                                    <text x="140" y="118" text-anchor="middle" fill="#ffffff" font-size="13" font-weight="bold">GẠCH SÂN VƯỜN ĐẤT SÉT NUNG</text>
                                </svg>
                            </div>
                            <div class="p-4">
                                <div class="text-[11px] font-bold text-brick-600 uppercase">Kinh nghiệm chọn gạch</div>
                                <h3 class="font-bold text-sm sm:text-base text-slate-800 mt-1 hover:text-brick-700 cursor-pointer" onclick="openArticleModal(2)">
                                    5 lý do nên chọn gạch sân vườn đất sét nung GSV thay vì gạch men thường
                                </h3>
                                <p class="text-xs text-slate-500 mt-2 line-clamp-3">
                                    Chống trơn trượt khi trời mưa, không bám rêu mốc, chịu được tải trọng xe ô tô và giữ được sắc đỏ ấm cúng bền lâu cho sân vườn Việt.
                                </p>
                            </div>
                        </div>
                        <div class="px-4 pb-4">
                            <button onclick="openArticleModal(2)" class="text-xs font-bold text-brick-700 hover:underline">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                            </button>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- SECTION 9: ĐƯA GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ -->
        <section id="ban-do-fanpage" class="py-10 sm:py-12 bg-white border-t border-slate-200">
            <div class="max-w-7xl mx-auto px-3 sm:px-6">
                <div class="section-title-container">
                    <div class="section-title">
                        <h2 class="section-title-main text-base sm:text-xl">BẢN ĐỒ CHỈ ĐƯỜNG & FANPAGE GẠCH HỒNG LỘC</h2>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Cột Google Map ngoài trang chủ (7 cột) -->
                    <div class="lg:col-span-7 flex flex-col justify-between bg-slate-50 rounded-2xl border border-slate-200 overflow-hidden shadow-xs">
                        <div class="p-4 bg-white border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                            <div>
                                <h3 class="font-bold text-sm sm:text-base text-brick-800">
                                    <i class="fa-solid fa-map-location-dot mr-1.5 text-brick-600"></i>Vị Trí Gạch Hồng Lộc - TP Đà Nẵng
                                </h3>
                                <p class="text-xs text-slate-500">Địa chỉ: TP Đà Nẵng • Điện thoại: 0935.730.797</p>
                            </div>
                            <a href="https://www.google.com/maps?q=Da+Nang,+Vietnam" target="_blank" rel="noopener" class="px-3 py-1.5 rounded-lg bg-brick-700 text-white text-xs font-semibold hover:bg-brick-800 transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Maps
                            </a>
                        </div>
                        <div class="w-full h-72 sm:h-80 relative bg-slate-200">
                            <iframe
                                title="Bản đồ Gạch Hồng Lộc TP Đà Nẵng"
                                src="https://www.google.com/maps?q=Da+Nang,+Vietnam&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột Fanpage chính thức ngoài trang chủ (5 cột) -->
                    <div class="lg:col-span-5 flex flex-col justify-between bg-slate-50 rounded-2xl border border-slate-200 overflow-hidden shadow-xs p-4 sm:p-5">
                        <div>
                            <h3 class="font-bold text-sm sm:text-base text-brick-800 mb-3 flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                <span>Fanpage Chính Thức Gạch Hồng Lộc</span>
                            </h3>

                            <!-- Khung Fanpage trực quan sinh động ngoài trang chủ -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-white shadow-xs">
                                <!-- Ảnh bìa Fanpage -->
                                <div class="h-32 bg-gradient-to-r from-brick-800 via-brick-700 to-amber-700 p-4 flex flex-col justify-end relative">
                                    <div class="flex items-center gap-3">
                                        <div class="w-14 h-14 rounded-xl bg-white p-1 shadow-md flex-shrink-0">
                                            <svg viewBox="0 0 100 100" class="w-full h-full rounded-lg">
                                                <rect width="100" height="100" rx="14" fill="#932314"/>
                                                <path d="M16 44 L50 18 L84 44 L76 50 L50 30 L24 50 Z" fill="#fbbf24"/>
                                                <rect x="24" y="58" width="22" height="11" rx="2" fill="#ffffff"/>
                                                <rect x="50" y="58" width="26" height="11" rx="2" fill="#fcd34d"/>
                                                <rect x="24" y="73" width="52" height="11" rx="2" fill="#fcd34d"/>
                                            </svg>
                                        </div>
                                        <div class="text-white min-w-0">
                                            <div class="font-extrabold text-sm sm:text-base truncate flex items-center gap-1">
                                                <span>Gạch Hồng Lộc - Đà Nẵng</span>
                                                <i class="fa-solid fa-circle-check text-sky-400 text-xs"></i>
                                            </div>
                                            <div class="text-xs text-amber-100">4.8K người theo dõi • Vật liệu xây dựng</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Nội dung hoạt động Fanpage -->
                                <div class="p-4 space-y-3 text-xs text-slate-600">
                                    <p class="text-slate-700 font-medium">
                                        Chuyên sỉ & lẻ Ngói lợp tráng men, Ngói đất nung, Phụ kiện ngói, Gạch lát sân vườn, Gạch xây không trát tại TP Đà Nẵng.
                                    </p>
                                    <div class="p-3 rounded-lg bg-slate-50 border border-slate-100 space-y-1">
                                        <div class="font-semibold text-slate-800">Bài đăng mới nhất:</div>
                                        <p class="text-slate-600">🔥 Bàn giao lô Ngói Indo tráng men & Gạch sân vườn GSV48002 cho công trình biệt thự tại Đà Nẵng. Liên hệ báo giá: 0935.730.797.</p>
                                    </div>
                                    <div class="grid grid-cols-2 gap-2.5 pt-1">
                                        <a href="https://facebook.com" target="_blank" rel="noopener" class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-center flex items-center justify-center gap-1.5 transition">
                                            <i class="fa-brands fa-facebook-f"></i>
                                            <span>Theo dõi Trang</span>
                                        </a>
                                        <a href="https://zalo.me/0935730797" target="_blank" rel="noopener" class="py-2 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-800 font-bold text-center flex items-center justify-center gap-1.5 transition">
                                            <i class="fa-solid fa-comment-dots text-blue-600"></i>
                                            <span>Nhắn tin ngay</span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="mt-4 pt-3 border-t border-slate-200 flex items-center justify-between text-xs text-slate-600">
                            <span><i class="fa-solid fa-phone-volume text-brick-700 mr-1"></i>Hotline: <strong>0935.730.797</strong></span>
                            <span>Website: <strong>gachhongloc.com</strong></span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer class="bg-slate-900 text-slate-300 pt-10 pb-20 lg:pb-8 border-t-4 border-brick-700 w-full">
        <div class="max-w-7xl mx-auto px-4 sm:px-6">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-slate-800">
                <!-- Cột 1: Thông tin Gạch Hồng Lộc -->
                <div class="space-y-3">
                    <div class="text-white font-extrabold text-lg tracking-wide">GẠCH HỒNG LỘC</div>
                    <p class="text-xs text-slate-400 leading-relaxed">
                        Nhà phân phối Gạch ngói đất sét nung cao cấp tại TP Đà Nẵng & Miền Trung. Sản phẩm sản xuất từ nguyên liệu tự nhiên, bền đẹp vĩnh cửu cùng công trình Việt.
                    </p>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i>Địa chỉ: <strong>TP Đà Nẵng</strong></li>
                        <li><i class="fa-solid fa-phone text-amber-400 w-5"></i>Điện thoại: <a href="tel:0935730797" class="font-bold text-amber-300 hover:underline">0935.730.797</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i>Website: <a href="https://gachhongloc.com" class="hover:underline">gachhongloc.com</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="space-y-3">
                    <div class="text-white font-bold text-sm uppercase tracking-wider">Danh Mục Sản Phẩm</div>
                    <ul class="text-xs space-y-2">
                        <li><button onclick="selectCategoryAndScroll('ngoi-lop')" class="hover:text-amber-300 transition">• Ngói lợp đất sét nung (22 sản phẩm)</button></li>
                        <li><button onclick="selectCategoryAndScroll('phu-kien-ngoi')" class="hover:text-amber-300 transition">• Phụ kiện ngói (4 sản phẩm)</button></li>
                        <li><button onclick="selectCategoryAndScroll('gach-lat')" class="hover:text-amber-300 transition">• Gạch lát sân vườn & Cotto (27 sản phẩm)</button></li>
                        <li><button onclick="selectCategoryAndScroll('gach-xay')" class="hover:text-amber-300 transition">• Gạch xây không trát (5 sản phẩm)</button></li>
                        <li><button onclick="selectCategoryAndScroll('tam-op')" class="hover:text-amber-300 transition">• Tấm ốp & Gạch trang trí (4 sản phẩm)</button></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div class="space-y-3">
                    <div class="text-white font-bold text-sm uppercase tracking-wider">Chính Sách & Hỗ Trợ</div>
                    <ul class="text-xs space-y-2">
                        <li><a href="#tieu-chuan" class="hover:text-amber-300 transition">• Tiêu chuẩn kỹ thuật gạch ngói</a></li>
                        <li><a href="#du-an" class="hover:text-amber-300 transition">• Dự án tiêu biểu tại Đà Nẵng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-300 transition">• Hướng dẫn thi công lợp ngói</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">• Chính sách vận chuyển & giao nhận</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">• Đăng ký đại lý & nhà thầu</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div class="space-y-3">
                    <div class="text-white font-bold text-sm uppercase tracking-wider">Tư Vấn Báo Giá Nhanh</div>
                    <p class="text-xs text-slate-400">Gọi trực tiếp hoặc nhắn Zalo để nhận bảng báo giá gạch ngói mới nhất kèm ưu đãi vận chuyển tại Đà Nẵng.</p>
                    <div class="pt-1 flex flex-col gap-2">
                        <a href="tel:0935730797" class="py-2.5 px-4 rounded-xl bg-brick-600 hover:bg-brick-500 text-white font-bold text-xs text-center transition">
                            <i class="fa-solid fa-phone-volume mr-1.5"></i>Hotline: 0935.730.797
                        </a>
                        <a href="https://zalo.me/0935730797" target="_blank" rel="noopener" class="py-2.5 px-4 rounded-xl bg-sky-600 hover:bg-sky-500 text-white font-bold text-xs text-center transition">
                            <i class="fa-solid fa-comment-dots mr-1.5"></i>Chat Zalo Báo Giá: 0935.730.797
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-500 flex flex-col sm:flex-row items-center justify-between gap-2">
                <div>© Bản quyền thuộc về <strong class="text-slate-300">GẠCH HỒNG LỘC (gachhongloc.com)</strong> - TP Đà Nẵng.</div>
                <div>Giao diện chuẩn Flatsome UX Builder • Hotline: 0935.730.797</div>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) ==================== -->
    <div class="fixed left-3 sm:left-5 bottom-4 sm:bottom-6 z-40 flex flex-col gap-3">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0935730797" target="_blank" rel="noopener" title="Chat Zalo 0935.730.797" class="group flex items-center gap-2">
            <div class="relative w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-blue-600 text-white flex items-center justify-center shadow-lg floating-pulse hover:scale-105 transition">
                <span class="font-extrabold text-xs tracking-tighter">Zalo</span>
            </div>
            <span class="hidden sm:inline-block px-3 py-1 rounded-full bg-slate-900/85 text-white text-xs font-semibold shadow">
                Chat Zalo
            </span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="#ban-do-fanpage" title="Fanpage Gạch Hồng Lộc" class="group flex items-center gap-2">
            <div class="relative w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-[#1877F2] text-white flex items-center justify-center shadow-lg hover:scale-105 transition">
                <i class="fa-brands fa-facebook-f text-lg"></i>
            </div>
            <span class="hidden sm:inline-block px-3 py-1 rounded-full bg-slate-900/85 text-white text-xs font-semibold shadow">
                Fanpage
            </span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0935730797" title="Gọi ngay 0935.730.797" class="group flex items-center gap-2">
            <div class="relative w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-brick-600 text-white flex items-center justify-center shadow-lg floating-pulse hover:scale-105 transition">
                <i class="fa-solid fa-phone-volume text-base"></i>
            </div>
            <span class="px-3 py-1.5 rounded-full bg-brick-700 text-white text-xs font-extrabold shadow-md border border-amber-300/40">
                0935.730.797
            </span>
        </a>
    </div>

    <!-- ==================== MODAL XEM NHANH SẢN PHẨM (FLATSOME QUICK VIEW LIGHTBOX) ==================== -->
    <div id="quickViewModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-6 bg-slate-900/70 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-3xl w-full overflow-hidden shadow-2xl border border-slate-200 relative animate-fadeIn">
            <button onclick="closeQuickView()" aria-label="Đóng" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-slate-100 hover:bg-brick-700 hover:text-white text-slate-700 flex items-center justify-center transition">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>

            <div class="grid grid-cols-1 md:grid-cols-12">
                <!-- Cột ảnh SVG sản phẩm trong Quick View -->
                <div class="md:col-span-6 bg-slate-50 p-6 flex items-center justify-center border-b md:border-b-0 md:border-r border-slate-200">
                    <div id="qvImageContainer" class="w-full max-w-[260px] aspect-square flex items-center justify-center"></div>
                </div>

                <!-- Cột thông tin chi tiết sản phẩm -->
                <div class="md:col-span-6 p-5 sm:p-6 flex flex-col justify-between space-y-4">
                    <div>
                        <div id="qvCategory" class="text-xs font-bold text-brick-600 uppercase tracking-wider"></div>
                        <h3 id="qvTitle" class="text-lg sm:text-xl font-extrabold text-slate-800 mt-1"></h3>

                        <!-- Giá gốc, Giá giảm & % Giảm giá giống Flatsome -->
                        <div class="mt-3 flex items-center gap-2.5 flex-wrap">
                            <span id="qvOldPrice" class="text-sm text-slate-400 line-through"></span>
                            <span id="qvSalePrice" class="text-xl font-extrabold text-brick-700"></span>
                            <span id="qvUnit" class="text-xs text-slate-500"></span>
                            <span id="qvDiscountPct" class="px-2 py-0.5 rounded bg-brick-700 text-white text-xs font-bold"></span>
                        </div>

                        <p id="qvDesc" class="text-xs sm:text-sm text-slate-600 mt-3 leading-relaxed"></p>

                        <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-slate-600 space-y-1.5">
                            <div><strong>Mã SP:</strong> <span id="qvSku" class="text-slate-800"></span></div>
                            <div><strong>Kích thước:</strong> <span id="qvSize" class="text-slate-800"></span></div>
                            <div><strong>Định mức:</strong> <span id="qvQuota" class="text-slate-800"></span></div>
                            <div><strong>Kho hàng:</strong> <span class="text-emerald-600 font-semibold">Sẵn hàng tại Đà Nẵng</span></div>
                        </div>
                    </div>

                    <div class="pt-2 flex flex-col sm:flex-row gap-2.5">
                        <a href="tel:0935730797" class="flex-1 py-2.5 px-4 rounded-xl bg-brick-700 hover:bg-brick-800 text-white font-bold text-xs sm:text-sm text-center transition">
                            <i class="fa-solid fa-phone mr-1.5"></i>Gọi Đặt Hàng: 0935.730.797
                        </a>
                        <button onclick="selectProductForQuote()" class="py-2.5 px-4 rounded-xl bg-amber-100 hover:bg-amber-200 text-brick-900 font-bold text-xs sm:text-sm text-center transition">
                            Nhận Báo Giá Sỉ
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==================== MODAL ĐỌC CHI TIẾT BÀI VIẾT ==================== -->
    <div id="articleModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-6 bg-slate-900/70 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-2xl w-full p-5 sm:p-7 shadow-2xl border border-slate-200 relative max-h-[88vh] overflow-y-auto">
            <button onclick="closeArticleModal()" class="absolute top-3 right-3 w-9 h-9 rounded-full bg-slate-100 hover:bg-brick-700 hover:text-white text-slate-700 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="artCategory" class="text-xs font-bold text-brick-600 uppercase"></div>
            <h3 id="artTitle" class="text-lg sm:text-xl font-extrabold text-slate-800 mt-1 pr-8"></h3>
            <div id="artContent" class="text-xs sm:text-sm text-slate-600 mt-4 space-y-3 leading-relaxed"></div>
            <div class="mt-6 pt-4 border-t border-slate-200 flex items-center justify-between">
                <span class="text-xs text-slate-500">Tư vấn kỹ thuật Gạch Hồng Lộc: <strong>0935.730.797</strong></span>
                <button onclick="closeArticleModal()" class="px-4 py-2 rounded-lg bg-slate-800 text-white text-xs font-bold">Đóng</button>
            </div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ SẢN PHẨM, MINH HỌA SVG, SLIDER & QUICK VIEW ==================== -->
    <script>
        // Danh sách sản phẩm lấy từ 4 đường dẫn gommy.com.vn:
        // 1. /san-pham/ngoi-lop/
        // 2. /san-pham/phu-kien-ngoi/
        // 3. /san-pham/gach-lat/
        // 4. /san-pham/gach-xay-khong-trat/
        // kèm giá gốc, giá giảm và % giảm giá chuẩn Flatsome
        const productsData = [
            // --- NGÓI LỢP (/san-pham/ngoi-lop/) ---
            {
                id: 1,
                sku: 'GM-INDO-XD',
                name: 'Ngói Indo Men Bóng Xanh Dương',
                category: 'ngoi-lop',
                categoryName: 'Ngói lợp',
                oldPrice: 23000,
                salePrice: 19500,
                discount: 15,
                unit: 'đ/viên',
                size: '335 x 248 x 12 mm',
                quota: '14.5 viên/m²',
                colorPrimary: '#1e3a8a',
                colorSecondary: '#3b82f6',
                svgType: 'ngoi-indo',
                desc: 'Ngói Indo tráng men bóng màu xanh dương cao cấp Gốm Mỹ, chống rêu mốc tuyệt đối, khóa âm dương chống hắt nước mưa bão miền Trung.'
            },
            {
                id: 2,
                sku: 'GM-INDO-XTT',
                name: 'Ngói Indo Men Bóng Xanh Tím Than',
                category: 'ngoi-lop',
                categoryName: 'Ngói lợp',
                oldPrice: 23000,
                salePrice: 19500,
                discount: 15,
                unit: 'đ/viên',
                size: '335 x 248 x 12 mm',
                quota: '14.5 viên/m²',
                colorPrimary: '#312e81',
                colorSecondary: '#4f46e5',
                svgType: 'ngoi-indo',
                desc: 'Ngói Indo men bóng xanh tím than sang trọng, phù hợp biệt thự tân cổ điển và nhà vườn mái Nhật, mái Thái tại Đà Nẵng.'
            },
            {
                id: 3,
                sku: 'GM-INDO-DO',
                name: 'Ngói Indo Men Bóng Đỏ',
                category: 'ngoi-lop',
                categoryName: 'Ngói lợp',
                oldPrice: 22000,
                salePrice: 18500,
                discount: 16,
                unit: 'đ/viên',
                size: '335 x 248 x 12 mm',
                quota: '14.5 viên/m²',
                colorPrimary: '#b02e1c',
                colorSecondary: '#ef4444',
                svgType: 'ngoi-indo',
                desc: 'Ngói Indo men bóng đỏ truyền thống kết hợp lớp men kính bền màu trên 50 năm, phản xạ nhiệt tốt giúp mát nhà.'
            },
            {
                id: 4,
                sku: 'GM-INDO-MT',
                name: 'Ngói Indo Men Gốm MT',
                category: 'ngoi-lop',
                categoryName: 'Ngói lợp',
                oldPrice: 23500,
                salePrice: 19900,
                discount: 15,
                unit: 'đ/viên',
                size: '335 x 248 x 12 mm',
                quota: '14.5 viên/m²',
                colorPrimary: '#78350f',
                colorSecondary: '#b45309',
                svgType: 'ngoi-indo',
                desc: 'Ngói Indo phủ men gốm mờ (Matt) chống chói sáng, tôn lên vẻ đẹp trầm mặc, đẳng cấp cho công trình kiến trúc.'
            },
            {
                id: 5,
                sku: 'GM-22TL-XTT',
                name: 'Ngói 22TL Men Bóng Xanh Tím Than',
                category: 'ngoi-lop',
                categoryName: 'Ngói lợp',
                oldPrice: 19500,
                salePrice: 16500,
                discount: 15,
                unit: 'đ/viên',
                size: '340 x 205 x 13 mm',
                quota: '22 viên/m²',
                colorPrimary: '#1e1b4b',
                colorSecondary: '#4338ca',
                svgType: 'ngoi-22',
                desc: 'Dòng ngói 22 viên/m² tráng men bóng màu xanh tím than, xương đất sét nung kết khối vững chắc, độ hút nước cực thấp.'
            },
            {
                id: 6,
                sku: 'GM-22TL-DO',
                name: 'Ngói 22TL Men Bóng Đỏ',
                category: 'ngoi-lop',
                categoryName: 'Ngói lợp',
                oldPrice: 18500,
                salePrice: 15500,
                discount: 16,
                unit: 'đ/viên',
                size: '340 x 205 x 13 mm',
                quota: '22 viên/m²',
                colorPrimary: '#991b1b',
                colorSecondary: '#dc2626',
                svgType: 'ngoi-22',
                desc: 'Ngói 22TL men bóng đỏ tươi sáng, giữ trọn nét đẹp mái ngói đỏ Việt Nam cùng độ bền cơ học vượt trội.'
            },

            // --- PHỤ KIỆN NGÓI (/san-pham/phu-kien-ngoi/) ---
            {
                id: 7,
                sku: 'GM-PK-NOC',
                name: 'Ngói Nóc Gốm Mỹ Cao Cấp',
                category: 'phu-kien-ngoi',
                categoryName: 'Phụ kiện ngói',
                oldPrice: 32000,
                salePrice: 27000,
                discount: 16,
                unit: 'đ/viên',
                size: '360 x 210 x 14 mm',
                quota: '3.3 viên/m dài',
                colorPrimary: '#932314',
                colorSecondary: '#f59e0b',
                svgType: 'phu-kien-noc',
                desc: 'Ngói nóc (ngói bò nóc) lợp trên đỉnh giao nhau của 2 mái dốc, đồng bộ màu men với ngói lợp chính Gốm Mỹ.'
            },
            {
                id: 8,
                sku: 'GM-PK-RIA',
                name: 'Ngói Rìa Men Màu Gốm Mỹ',
                category: 'phu-kien-ngoi',
                categoryName: 'Phụ kiện ngói',
                oldPrice: 31000,
                salePrice: 26000,
                discount: 16,
                unit: 'đ/viên',
                size: '335 x 220 x 14 mm',
                quota: '3.5 viên/m dài',
                colorPrimary: '#1e3a8a',
                colorSecondary: '#60a5fa',
                svgType: 'phu-kien-ria',
                desc: 'Phụ kiện ngói rìa che phủ hai bên hông mái nhà, bảo vệ kết cấu mái khỏi gió lốc và nước mưa tạt ngang.'
            },
            {
                id: 9,
                sku: 'GM-PK-NOCTIEU',
                name: 'Ngói Nóc Tiểu Đất Sét Nung',
                category: 'phu-kien-ngoi',
                categoryName: 'Phụ kiện ngói',
                oldPrice: 25000,
                salePrice: 21000,
                discount: 16,
                unit: 'đ/viên',
                size: '280 x 150 x 12 mm',
                quota: '4 viên/m dài',
                colorPrimary: '#b02e1c',
                colorSecondary: '#fbbf24',
                svgType: 'phu-kien-noc',
                desc: 'Ngói nóc tiểu chuyên dùng làm rìa mái hoặc đỉnh mái cho các công trình mái nhỏ, cổng tam quan, nhà thờ họ.'
            },
            {
                id: 10,
                sku: 'GM-PK-CUOINOC',
                name: 'Ngói Cuối Nóc & Cuối Rìa Gốm Mỹ',
                category: 'phu-kien-ngoi',
                categoryName: 'Phụ kiện ngói',
                oldPrice: 45000,
                salePrice: 38000,
                discount: 16,
                unit: 'đ/viên',
                size: '340 x 210 x 14 mm',
                quota: 'Theo đầu mái',
                colorPrimary: '#312e81',
                colorSecondary: '#818cf8',
                svgType: 'phu-kien-ria',
                desc: 'Viên ngói khóa cuối đường nóc và cuối đường rìa mái, tạo điểm nhấn thẩm mỹ sắc nét cho toàn bộ hệ mái.'
            },

            // --- GẠCH LÁT (/san-pham/gach-lat/) ---
            {
                id: 11,
                sku: 'GSV48002',
                name: 'Gạch Sân Vườn Cao Cấp GSV48002',
                category: 'gach-lat',
                categoryName: 'Gạch lát',
                oldPrice: 165000,
                salePrice: 138000,
                discount: 16,
                unit: 'đ/m²',
                size: '400 x 400 x 14 mm',
                quota: '6.25 viên/m²',
                colorPrimary: '#9a3412',
                colorSecondary: '#fde68a',
                svgType: 'gach-gsv-1',
                desc: 'Gạch sân vườn cao cấp GSV48002 đất sét nung tráng men định hình chống trơn, họa tiết cổ điển sang trọng.'
            },
            {
                id: 12,
                sku: 'GSV48001',
                name: 'Gạch Sân Vườn Cao Cấp GSV48001',
                category: 'gach-lat',
                categoryName: 'Gạch lát',
                oldPrice: 165000,
                salePrice: 138000,
                discount: 16,
                unit: 'đ/m²',
                size: '400 x 400 x 14 mm',
                quota: '6.25 viên/m²',
                colorPrimary: '#7c2d12',
                colorSecondary: '#fed7aa',
                svgType: 'gach-gsv-2',
                desc: 'Gạch lát sân vườn GSV48001 chịu lực cao, không rêu mốc, thích hợp lát sân biệt thự, lối đi công viên, resort.'
            },
            {
                id: 13,
                sku: 'GSV46009',
                name: 'Gạch Sân Vườn Cao Cấp GSV46009',
                category: 'gach-lat',
                categoryName: 'Gạch lát',
                oldPrice: 160000,
                salePrice: 135000,
                discount: 16,
                unit: 'đ/m²',
                size: '400 x 400 x 14 mm',
                quota: '6.25 viên/m²',
                colorPrimary: '#932314',
                colorSecondary: '#fcd34d',
                svgType: 'gach-gsv-1',
                desc: 'Mẫu gạch sân vườn GSV46009 hoa văn kỷ hà nổi khối giúp thoát nước bề mặt nhanh, an toàn khi di chuyển.'
            },
            {
                id: 14,
                sku: 'GSV5032',
                name: 'Gạch Sân Vườn Cao Cấp GSV5032',
                category: 'gach-lat',
                categoryName: 'Gạch lát',
                oldPrice: 175000,
                salePrice: 145000,
                discount: 17,
                unit: 'đ/m²',
                size: '500 x 500 x 15 mm',
                quota: '4 viên/m²',
                colorPrimary: '#78350f',
                colorSecondary: '#fde047',
                svgType: 'gach-gsv-2',
                desc: 'Gạch sân vườn khổ lớn GSV5032 chịu tải trọng ô tô, bề mặt đanh chắc, bền màu dưới nắng mưa khắc nghiệt.'
            },
            {
                id: 15,
                sku: 'GSV5031',
                name: 'Gạch Sân Vườn Cao Cấp GSV5031',
                category: 'gach-lat',
                categoryName: 'Gạch lát',
                oldPrice: 175000,
                salePrice: 145000,
                discount: 17,
                unit: 'đ/m²',
                size: '500 x 500 x 15 mm',
                quota: '4 viên/m²',
                colorPrimary: '#854d0e',
                colorSecondary: '#fef08a',
                svgType: 'gach-gsv-1',
                desc: 'Gạch lát sân vườn GSV5031 kết hợp hoàn hảo giữa chất liệu đất nung truyền thống và công nghệ phủ men hiện đại.'
            },
            {
                id: 16,
                sku: 'GSV5030',
                name: 'Gạch Sân Vườn Cao Cấp GSV5030',
                category: 'gach-lat',
                categoryName: 'Gạch lát',
                oldPrice: 170000,
                salePrice: 142000,
                discount: 16,
                unit: 'đ/m²',
                size: '500 x 500 x 15 mm',
                quota: '4 viên/m²',
                colorPrimary: '#b02e1c',
                colorSecondary: '#fed7aa',
                svgType: 'gach-cotto',
                desc: 'Gạch Cotto & Sân vườn GSV5030 tông đỏ đất nung ấm áp, dễ lau chùi, lý tưởng cho sân thượng, hiên nhà, sân đình.'
            },

            // --- GẠCH XÂY KHÔNG TRÁT (/san-pham/gach-xay-khong-trat/) ---
            {
                id: 17,
                sku: 'GM-GXKT-3LO',
                name: 'Gạch Xây Không Trát 3 Lỗ Gốm Mỹ',
                category: 'gach-xay',
                categoryName: 'Gạch xây không trát',
                oldPrice: 4800,
                salePrice: 3900,
                discount: 19,
                unit: 'đ/viên',
                size: '210 x 100 x 60 mm',
                quota: '65 viên/m²',
                colorPrimary: '#9a3412',
                colorSecondary: '#fdba74',
                svgType: 'gach-xay-3lo',
                desc: 'Gạch xây không trát 3 lỗ đất sét nung ngâm ủ 4-5 tháng, cạnh vuông sắc nét, xây tường trần không cần trát vữa.'
            },
            {
                id: 18,
                sku: 'GM-GXKT-DAC',
                name: 'Gạch Xây Không Trát Đặc Cổ Điển',
                category: 'gach-xay',
                categoryName: 'Gạch xây không trát',
                oldPrice: 5500,
                salePrice: 4500,
                discount: 18,
                unit: 'đ/viên',
                size: '210 x 100 x 60 mm',
                quota: '65 viên/m²',
                colorPrimary: '#7c2d12',
                colorSecondary: '#fed7aa',
                svgType: 'gach-xay-dac',
                desc: 'Gạch đặc xây không trát chịu lực nén cực cao, cách âm, cách nhiệt tuyệt vời cho nhà phố, quán cafe, nhà cổ.'
            },

            // --- TẤM ỐP & TRANG TRÍ ---
            {
                id: 19,
                sku: 'GM-TO-01',
                name: 'Tấm Ốp Tường Đất Sét Nung Đỏ Đậm',
                category: 'tam-op',
                categoryName: 'Tấm ốp',
                oldPrice: 185000,
                salePrice: 155000,
                discount: 16,
                unit: 'đ/m²',
                size: '210 x 60 x 15 mm',
                quota: '68 viên/m²',
                colorPrimary: '#932314',
                colorSecondary: '#fca5a5',
                svgType: 'tam-op',
                desc: 'Tấm gạch thẻ ốp tường nội ngoại thất đất sét nung tự nhiên, bảo vệ tường nhà khỏi thấm nước và bong tróc sơn.'
            },
            {
                id: 20,
                sku: 'GM-TO-02',
                name: 'Gạch Thông Gió Đất Nung Hoa Mai',
                category: 'tam-op',
                categoryName: 'Tấm ốp',
                oldPrice: 19000,
                salePrice: 15500,
                discount: 18,
                unit: 'đ/viên',
                size: '200 x 200 x 60 mm',
                quota: '25 viên/m²',
                colorPrimary: '#b45309',
                colorSecondary: '#fef3c7',
                svgType: 'thong-gio',
                desc: 'Gạch bông gió đất nung giúp lấy sáng tự nhiên, đón gió mát và chắn mưa hắt cho mặt tiền công trình tại Đà Nẵng.'
            }
        ];

        // Dữ liệu chi tiết bài viết
        const articlesData = [
            {
                category: 'Kỹ thuật lợp ngói',
                title: 'Ngói rìa và ngói nóc là gì? Hướng dẫn kỹ thuật lợp ngói chuẩn thẩm mỹ',
                content: `
                    <p><strong>1. Ngói rìa là gì?</strong> Ngói rìa là phụ kiện đi kèm cho các loại ngói lợp chính (như ngói Indo, ngói 22TL), được lợp ở hai bên cạnh đầu hồi của mái nhà nhằm che phủ phần kết cấu rìa mái và chống thấm dột.</p>
                    <p><strong>2. Ngói nóc là gì?</strong> Ngói nóc (còn gọi là ngói bò nóc, ngói úp nóc) được lợp trên đỉnh cao nhất nơi giao nhau của 2 mái dốc. Tùy diện tích mái lớn hay nhỏ mà gia chủ chọn ngói nóc lớn hoặc ngói nóc tiểu.</p>
                    <p><strong>3. Lưu ý khi thi công:</strong> Khi lợp cần căng dây thẳng hàng, sử dụng vữa dẻo hoặc vít chuyên dụng cố định viên ngói rìa và ngói nóc đúng bản vẽ để mái nhà bền vững trước gió bão miền Trung.</p>
                `
            },
            {
                category: 'Xu hướng kiến trúc',
                title: 'Vì sao gia chủ lại lựa chọn gạch xây không trát cho nhà phố và biệt thự?',
                content: `
                    <p><strong>1. Độ bền chắc vượt thời gian:</strong> Đất sét được ngâm ủ 4–5 tháng, đóng khuôn vuông vắn và nung ở nhiệt độ cao giúp viên gạch xây không trát đạt độ cứng và chịu lực vượt trội.</p>
                    <p><strong>2. Giá trị thẩm mỹ mộc mạc:</strong> Tường gạch trần xây theo mạch vữa đều đặn mang lại không gian ấm cúng, sang trọng mà không cần tốn chi phí trát vữa hay sơn bả định kỳ.</p>
                    <p><strong>3. Cách âm, cách nhiệt:</strong> Khả năng điều hòa nhiệt độ và chống ồn tự nhiên của gạch đất nung rất phù hợp với môi trường đô thị tại TP Đà Nẵng.</p>
                `
            },
            {
                category: 'Kinh nghiệm chọn gạch',
                title: '5 lý do nên chọn gạch sân vườn đất sét nung GSV thay vì gạch men thường',
                content: `
                    <p><strong>1. Chống trơn trượt tối đa:</strong> Dòng gạch sân vườn GSV48002, GSV48001, GSV5032 có bề mặt định hình nổi khối giúp thoát nước nhanh và bám chân tốt ngay cả khi trời mưa.</p>
                    <p><strong>2. Không rêu mốc, không phai màu:</strong> Được nung kết khối ở nhiệt độ cao nên gạch sân vườn Gốm Mỹ giữ nguyên sắc độ ấm áp sau hàng chục năm sử dụng ngoài trời.</p>
                    <p><strong>3. Chịu lực tốt:</strong> Độ dày 14–15mm chịu được tải trọng xe ô tô ra vào sân biệt thự.</p>
                `
            }
        ];

        // Hàm vẽ SVG sắc nét cho từng loại gạch/ngói (Đảm bảo 100% không bao giờ lỗi ảnh trên mạng)
        function generateProductSVG(product) {
            const c1 = product.colorPrimary;
            const c2 = product.colorSecondary;

            if (product.svgType === 'ngoi-indo' || product.svgType === 'ngoi-22') {
                return `
                <svg viewBox="0 0 200 180" class="w-full h-full">
                    <rect width="200" height="180" rx="12" fill="#f8fafc"/>
                    <!-- Bóng đổ -->
                    <ellipse cx="100" cy="148" rx="64" ry="10" fill="#cbd5e1" opacity="0.6"/>
                    <!-- Thân viên ngói lợp sóng -->
                    <path d="M36 45 C65 28, 95 62, 132 42 L166 118 C128 138, 98 104, 66 122 Z" fill="${c1}" stroke="#ffffff" stroke-width="1.5"/>
                    <path d="M52 52 C78 38, 104 68, 138 50 L158 104 C126 120, 98 92, 72 108 Z" fill="${c2}" opacity="0.38"/>
                    <!-- Gờ khóa âm dương -->
                    <rect x="34" y="42" width="12" height="78" rx="4" transform="rotate(-18 40 80)" fill="${c1}"/>
                    <text x="100" y="168" text-anchor="middle" fill="#475569" font-size="10" font-weight="700">${product.sku}</text>
                </svg>`;
            }

            if (product.svgType === 'phu-kien-noc' || product.svgType === 'phu-kien-ria') {
                return `
                <svg viewBox="0 0 200 180" class="w-full h-full">
                    <rect width="200" height="180" rx="12" fill="#f8fafc"/>
                    <ellipse cx="100" cy="146" rx="62" ry="10" fill="#cbd5e1" opacity="0.6"/>
                    <!-- Viên ngói nóc/rìa vòm -->
                    <path d="M32 112 Q100 32 168 112 L150 130 Q100 62 50 130 Z" fill="${c1}"/>
                    <path d="M46 112 Q100 48 154 112" fill="none" stroke="${c2}" stroke-width="5" opacity="0.7"/>
                    <text x="100" y="168" text-anchor="middle" fill="#475569" font-size="10" font-weight="700">${product.sku}</text>
                </svg>`;
            }

            if (product.svgType === 'gach-gsv-1' || product.svgType === 'gach-gsv-2' || product.svgType === 'gach-cotto') {
                return `
                <svg viewBox="0 0 200 180" class="w-full h-full">
                    <rect width="200" height="180" rx="12" fill="#f8fafc"/>
                    <rect x="42" y="20" width="116" height="116" rx="8" fill="${c1}" stroke="#431407" stroke-width="3"/>
                    <rect x="52" y="30" width="96" height="96" rx="4" fill="none" stroke="${c2}" stroke-width="2" opacity="0.8"/>
                    <circle cx="100" cy="78" r="28" fill="none" stroke="${c2}" stroke-width="3.5"/>
                    <rect x="82" y="60" width="36" height="36" transform="rotate(45 100 78)" fill="${c2}" opacity="0.85"/>
                    <text x="100" y="162" text-anchor="middle" fill="#475569" font-size="10" font-weight="700">${product.sku}</text>
                </svg>`;
            }

            if (product.svgType === 'gach-xay-3lo' || product.svgType === 'gach-xay-dac') {
                const holes = product.svgType === 'gach-xay-3lo'
                    ? `<circle cx="66" cy="64" r="8" fill="#431407"/><circle cx="100" cy="64" r="8" fill="#431407"/><circle cx="134" cy="64" r="8" fill="#431407"/>
                       <circle cx="66" cy="112" r="8" fill="#431407"/><circle cx="100" cy="112" r="8" fill="#431407"/><circle cx="134" cy="112" r="8" fill="#431407"/>`
                    : `<line x1="48" y1="64" x2="152" y2="64" stroke="${c2}" stroke-width="2" opacity="0.5"/>`;
                return `
                <svg viewBox="0 0 200 180" class="w-full h-full">
                    <rect width="200" height="180" rx="12" fill="#f8fafc"/>
                    <rect x="34" y="42" width="132" height="44" rx="5" fill="${c1}" stroke="#431407" stroke-width="2"/>
                    <rect x="34" y="92" width="132" height="44" rx="5" fill="${c1}" stroke="#431407" stroke-width="2"/>
                    ${holes}
                    <text x="100" y="164" text-anchor="middle" fill="#475569" font-size="10" font-weight="700">${product.sku}</text>
                </svg>`;
            }

            // Tấm ốp & gạch thông gió
            return `
            <svg viewBox="0 0 200 180" class="w-full h-full">
                <rect width="200" height="180" rx="12" fill="#f8fafc"/>
                <rect x="44" y="24" width="112" height="112" rx="10" fill="${c1}"/>
                <circle cx="100" cy="80" r="34" fill="#ffffff"/>
                <circle cx="100" cy="80" r="16" fill="${c2}"/>
                <text x="100" y="162" text-anchor="middle" fill="#475569" font-size="10" font-weight="700">${product.sku}</text>
            </svg>`;
        }

        function formatVND(num) {
            return num.toLocaleString('vi-VN') + 'đ';
        }

        let currentCategory = 'all';
        let currentQuickViewProduct = null;

        // Render danh sách sản phẩm chuẩn Flatsome (Không dán nhãn góc ảnh, hiển thị giá giảm & % giảm rõ ràng trong khung giá, có thanh Xem Nhanh)
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list.length) {
                grid.innerHTML = `
                    <div class="col-span-full py-10 text-center text-slate-500 text-sm">
                        Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi <strong>0935.730.797</strong> để được tư vấn trực tiếp.
                    </div>`;
                return;
            }

            grid.innerHTML = list.map(item => `
                <div class="product-small bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <!-- Box Image + Nút Xem Nhanh chuẩn Flatsome -->
                    <div class="box-image aspect-[10/9] bg-slate-50 p-2 sm:p-3 cursor-pointer" onclick="openQuickView(${item.id})">
                        ${generateProductSVG(item)}
                        <div class="quick-view-bar" onclick="event.stopPropagation(); openQuickView(${item.id})">
                            <i class="fa-regular fa-eye mr-1"></i>Xem nhanh
                        </div>
                    </div>

                    <!-- Box Text chuẩn Flatsome -->
                    <div class="box-text p-2.5 sm:p-4 flex-grow flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] sm:text-xs text-slate-400 uppercase font-semibold truncate">${item.categoryName}</div>
                            <h3 onclick="openQuickView(${item.id})" class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brick-700 cursor-pointer line-clamp-2 mt-0.5 min-h-[2.25rem]">
                                ${item.name}
                            </h3>
                        </div>

                        <!-- Giá giảm giá & % giảm giá giống Flatsome -->
                        <div class="mt-2 pt-2 border-t border-slate-100">
                            <div class="flex items-center flex-wrap gap-1.5">
                                <del class="text-[11px] sm:text-xs text-slate-400">${formatVND(item.oldPrice)}</del>
                                <span class="text-[10px] sm:text-[11px] font-bold px-1.5 py-0.5 rounded bg-brick-100 text-brick-800">-${item.discount}%</span>
                            </div>
                            <div class="mt-0.5 flex items-baseline justify-between gap-1">
                                <span class="text-xs sm:text-base font-extrabold text-brick-700">${formatVND(item.salePrice)}</span>
                                <span class="text-[10px] text-slate-500">${item.unit}</span>
                            </div>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Lọc theo danh mục
        function filterProducts(cat) {
            currentCategory = cat;
            document.querySelectorAll('.cat-tab').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.className = 'cat-tab px-3 py-1.5 rounded-lg text-xs font-bold bg-brick-700 text-white transition';
                } else {
                    btn.className = 'cat-tab px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brick-50 hover:text-brick-700 transition';
                }
            });

            const filtered = cat === 'all' ? productsData : productsData.filter(p => p.category === cat);
            renderProducts(filtered);
        }

        function selectCategoryAndScroll(cat) {
            filterProducts(cat);
            const section = document.getElementById('san-pham');
            if (section) {
                section.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // Tìm kiếm sản phẩm
        function handleSearch(keyword) {
            const q = keyword.trim().toLowerCase();
            if (!q) {
                filterProducts(currentCategory);
                return;
            }
            const results = productsData.filter(p =>
                p.name.toLowerCase().includes(q) ||
                p.categoryName.toLowerCase().includes(q) ||
                p.sku.toLowerCase().includes(q)
            );
            renderProducts(results);
        }

        // Mở/Đóng Modal Xem Nhanh (Quick View)
        function openQuickView(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;
            currentQuickViewProduct = product;

            document.getElementById('qvImageContainer').innerHTML = generateProductSVG(product);
            document.getElementById('qvCategory').textContent = product.categoryName;
            document.getElementById('qvTitle').textContent = product.name;
            document.getElementById('qvOldPrice').textContent = formatVND(product.oldPrice);
            document.getElementById('qvSalePrice').textContent = formatVND(product.salePrice);
            document.getElementById('qvUnit').textContent = '(' + product.unit + ')';
            document.getElementById('qvDiscountPct').textContent = 'Giảm ' + product.discount + '%';
            document.getElementById('qvDesc').textContent = product.desc;
            document.getElementById('qvSku').textContent = product.sku;
            document.getElementById('qvSize').textContent = product.size;
            document.getElementById('qvQuota').textContent = product.quota;

            const modal = document.getElementById('quickViewModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeQuickView() {
            const modal = document.getElementById('quickViewModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function selectProductForQuote() {
            closeQuickView();
            if (currentQuickViewProduct) {
                const noteField = document.getElementById('qNote');
                noteField.value = `Tôi cần báo giá sản phẩm: ${currentQuickViewProduct.name} (${currentQuickViewProduct.sku})`;
            }
            document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
        }

        // Xử lý lọc bài viết & xem bài viết
        function filterPosts(cat) {
            document.querySelectorAll('.blog-card').forEach(card => {
                if (cat === 'all' || card.getAttribute('data-post-cat') === cat) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        function openArticleModal(idx) {
            const art = articlesData[idx];
            if (!art) return;
            document.getElementById('artCategory').textContent = art.category;
            document.getElementById('artTitle').textContent = art.title;
            document.getElementById('artContent').innerHTML = art.content;
            const modal = document.getElementById('articleModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeArticleModal() {
            const modal = document.getElementById('articleModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Xử lý gửi Form Báo Giá (Không dùng alert)
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const quantity = document.getElementById('qQuantity').value.trim() || 'Chưa xác định';

            const box = document.getElementById('quoteSuccessBox');
            const text = document.getElementById('quoteSuccessText');
            text.textContent = `Cảm ơn anh/chị ${name} (${phone}). Bộ phận kinh doanh Gạch Hồng Lộc Đà Nẵng đã ghi nhận yêu cầu báo giá "${category}" (Số lượng: ${quantity}) và sẽ liên hệ lại ngay qua SĐT/Zalo 0935.730.797.`;
            box.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        // Menu Mobile
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        // Slider 2 Banner tự trượt
        let activeSlide = 0;
        let slideInterval = null;

        function showSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            const dot0 = document.getElementById('slideDot0');
            const dot1 = document.getElementById('slideDot1');

            slides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'pointer-events-none', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'pointer-events-none', 'z-0');
                }
            });

            if (index === 0) {
                dot0.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                dot1.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
            } else {
                dot0.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                dot1.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
            }
            activeSlide = index;
        }

        function changeSlide(step) {
            const next = (activeSlide + step + 2) % 2;
            showSlide(next);
            resetSliderTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSliderTimer();
        }

        function resetSliderTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                changeSlide(1);
            }, 5000);
        }

        // Khởi chạy khi tải trang
        window.onload = function () {
            renderProducts(productsData);
            resetSliderTimer();
        };
    </script>
</body>
</html>
