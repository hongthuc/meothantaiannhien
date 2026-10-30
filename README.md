<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mèo Thần Tài An Nhiên - Shop Mèo Thần Tài Khai Trương Đà Nẵng | meothantaiannhien.com</title>
    <meta name="description" content="Mèo Thần Tài An Nhiên (meothantaiannhien.com) - Chuyên Mèo Thần Tài khai trương, mèo vẫy tay, mèo mini, mèo đèn LED và vật phẩm phong thủy tại 238 Diên Hồng, Hòa Xuân, Đà Nẵng. Hotline/Zalo: 0901.956.069">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Be Vietnam Pro & Playfair Display -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@0,400;0,500;0,600;0,700;0,800;1,400&family=Playfair+Display:wght@700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Be Vietnam Pro"', 'sans-serif'],
                        serif: ['"Playfair Display"', 'serif'],
                    },
                    colors: {
                        brand: {
                            red: '#B91C1C',      /* Đỏ Chu Sa chủ đạo chuẩn Flatsome */
                            darkRed: '#881313',  /* Đỏ trầm Header/Hover */
                            gold: '#D97706',     /* Vàng Kim chiêu tài */
                            lightGold: '#FEF3C7',/* Nền vàng kem nhẹ */
                            cream: '#FAF7F2',    /* Nền kem gốm sứ ấm áp */
                            border: '#EADFD5'    /* Viền khung Flatsome nhẹ nhàng */
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Cấu trúc CSS chuẩn Flatsome đơn giản, dễ dàng dựng lại trên UX Builder */
        body {
            background-color: #FAF7F2;
            color: #1F2937;
            font-family: 'Be Vietnam Pro', sans-serif;
            overflow-x: hidden;
        }

        /* Container chuẩn Flatsome 1200px */
        .fs-container {
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 1.5rem;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #E5E7EB;
            padding-bottom: 10px;
        }
        .section-title-main h2 {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #B91C1C;
            letter-spacing: 0.02em;
        }
        .section-title-main h2::after {
            content: '';
            position: absolute;
            bottom: -12px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #B91C1C;
        }

        /* Product Box chuẩn Flatsome (Không nhãn dán / Không sticker) */
        .product-small.box {
            background: #FFFFFF;
            border: 1px solid #EFE8E0;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .product-small.box:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px -6px rgba(185, 28, 28, 0.12);
            border-color: #D97706;
        }
        .product-small .box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 1 / 1;
            background: radial-gradient(circle at center, #FFFDF9 0%, #F7EFE4 100%);
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .product-small .box-image svg {
            transition: transform 0.35s ease;
        }
        .product-small.box:hover .box-image svg {
            transform: scale(1.06);
        }

        /* Category Box chuẩn Flatsome đẹp trên cả PC và Điện thoại */
        .cat-card {
            transition: all 0.25s ease;
        }
        .cat-card:hover {
            transform: translateY(-4px);
            border-color: #B91C1C;
            box-shadow: 0 10px 20px -5px rgba(185, 28, 28, 0.14);
        }
        .cat-card.active {
            border-color: #B91C1C;
            background-color: #FEF2F2;
            box-shadow: 0 0 0 2px #B91C1C;
        }

        /* Thanh cuộn ngang mượt trên điện thoại */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(185, 28, 28, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(185, 28, 28, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(185, 28, 28, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="pb-16 md:pb-0">

    <!-- =====================================================================
         HEADER WRAPPER (Chuẩn cấu trúc Flatsome: Topbar + Header Main + Nav)
         Không có thanh công cụ chỉnh sửa UX Builder ở trên cùng
    ====================================================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm">
        
        <!-- 1. TOP BAR -->
        <div id="top-bar" class="bg-brand-darkRed text-white text-xs py-2">
            <div class="fs-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-4">
                    <span class="flex items-center gap-1.5 font-medium">
                        <i class="fa-solid fa-location-dot text-amber-300"></i>
                        <span>238 Diên Hồng, Phường Hoà Xuân, Tp.Đà Nẵng</span>
                    </span>
                    <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1 text-amber-300 hover:underline font-medium">
                        <i class="fa-solid fa-map-location-dot"></i> Xem bản đồ
                    </a>
                </div>
                <div class="hidden md:flex items-center gap-5">
                    <span class="flex items-center gap-1.5">
                        <i class="fa-regular fa-clock text-amber-300"></i>
                        <span>Mở cửa: 06:30 - 22:30 (Tất cả các ngày)</span>
                    </span>
                    <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 flex items-center gap-1">
                        <i class="fa-brands fa-facebook"></i> Fanpage Mèo Thần Tài An Nhiên
                    </a>
                    <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 flex items-center gap-1">
                        <i class="fa-solid fa-comment-dots"></i> Zalo: 0901.956.069
                    </a>
                </div>
            </div>
        </div>

        <!-- 2. HEADER MAIN (Logo + Tìm kiếm + Hotline + Giỏ hàng) -->
        <div id="masthead" class="py-3 md:py-4 bg-white border-b border-gray-100">
            <div class="fs-container flex items-center justify-between gap-3 md:gap-6">
                
                <!-- Nút Menu Mobile -->
                <button onclick="toggleMobileMenu()" class="lg:hidden p-2.5 text-gray-700 hover:text-brand-red rounded-lg border border-gray-200" aria-label="Mở menu">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>

                <!-- LOGO THIẾT KẾ RIÊNG: MÈO THẦN TÀI AN NHIÊN (meothantaiannhien.com) -->
                <a href="#" onclick="resetAllFilters(); return false;" class="flex items-center gap-2.5 md:gap-3 group shrink-0">
                    <!-- Biểu tượng Logo SVG Mèo Thần Tài An Nhiên -->
                    <div class="w-12 h-12 md:w-14 md:h-14 rounded-full bg-gradient-to-br from-brand-red to-brand-darkRed p-0.5 shadow-md flex items-center justify-center shrink-0">
                        <svg viewBox="0 0 100 100" class="w-full h-full">
                            <!-- Viền tròn kim tiền -->
                            <circle cx="50" cy="50" r="47" fill="#FFFDF9" stroke="#F59E0B" stroke-width="2.5"/>
                            <circle cx="50" cy="50" r="43" fill="none" stroke="#B91C1C" stroke-width="1" stroke-dasharray="3,2"/>
                            <!-- Tai mèo -->
                            <path d="M26 38 L22 17 L41 27 Z" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5" stroke-linejoin="round"/>
                            <path d="M26 34 L25 22 L36 28 Z" fill="#EF4444"/>
                            <path d="M74 38 L78 17 L59 27 Z" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5" stroke-linejoin="round"/>
                            <path d="M74 34 L75 22 L64 28 Z" fill="#EF4444"/>
                            <!-- Đầu & Thân mèo -->
                            <ellipse cx="50" cy="48" rx="26" ry="22" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5"/>
                            <!-- Tay trái vẫy chiêu tài -->
                            <path d="M23 52 C14 44, 15 30, 23 30 C28 30, 29 38, 28 48" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5" stroke-linecap="round"/>
                            <!-- Mắt cười An Nhiên -->
                            <path d="M36 44 Q41 38 46 44" fill="none" stroke="#1F2937" stroke-width="2.5" stroke-linecap="round"/>
                            <path d="M54 44 Q59 38 64 44" fill="none" stroke="#1F2937" stroke-width="2.5" stroke-linecap="round"/>
                            <!-- Mũi & Miệng may mắn -->
                            <polygon points="48,48 52,48 50,51" fill="#EF4444"/>
                            <path d="M45 53 Q50 57 55 53" fill="none" stroke="#B91C1C" stroke-width="2" stroke-linecap="round"/>
                            <!-- Má hồng -->
                            <circle cx="34" cy="49" r="3" fill="#FCA5A5"/>
                            <circle cx="66" cy="49" r="3" fill="#FCA5A5"/>
                            <!-- Vòng cổ đỏ & Chuông vàng -->
                            <path d="M29 63 Q50 71 71 63" fill="none" stroke="#B91C1C" stroke-width="5" stroke-linecap="round"/>
                            <circle cx="50" cy="68" r="6" fill="#F59E0B" stroke="#92400E" stroke-width="1.5"/>
                            <line x1="47" y1="68" x2="53" y2="68" stroke="#92400E" stroke-width="1.2"/>
                            <!-- Kim nguyên bảo dưới chân -->
                            <path d="M34 81 Q50 89 66 81 L62 74 Q50 79 38 74 Z" fill="#FBBF24" stroke="#B45309" stroke-width="1.5"/>
                        </svg>
                    </div>
                    <!-- Tên Thương Hiệu -->
                    <div>
                        <span class="block text-base sm:text-xl md:text-2xl font-extrabold text-brand-red tracking-tight leading-none">
                            MÈO THẦN TÀI AN NHIÊN
                        </span>
                        <span class="block text-[11px] sm:text-xs font-semibold text-amber-700 tracking-wide mt-1">
                            meothantaiannhien.com • Đà Nẵng
                        </span>
                    </div>
                </a>

                <!-- Ô Tìm Kiếm Sản Phẩm (Desktop) -->
                <div class="hidden md:flex flex-1 max-w-md mx-2">
                    <div class="relative w-full">
                        <input 
                            type="text" 
                            id="desktopSearchInput"
                            oninput="handleSearch(this.value)"
                            placeholder="Tìm mèo thần tài khai trương, vẫy tay, mini..." 
                            class="w-full pl-4 pr-11 py-2.5 text-sm bg-gray-50 border border-gray-300 rounded-full focus:outline-none focus:border-brand-red focus:bg-white transition"
                        >
                        <button onclick="handleSearch(document.getElementById('desktopSearchInput').value)" class="absolute right-1.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-brand-red text-white flex items-center justify-center hover:bg-brand-darkRed transition" aria-label="Tìm kiếm">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Cụm Nút Liên Hệ Nhanh & Giỏ Hàng -->
                <div class="flex items-center gap-2 sm:gap-3">
                    <!-- Hotline Box -->
                    <a href="tel:0901956069" class="hidden xl:flex items-center gap-2.5 bg-red-50 hover:bg-red-100 px-3.5 py-2 rounded-full border border-red-200 transition">
                        <div class="w-8 h-8 rounded-full bg-brand-red text-white flex items-center justify-center">
                            <i class="fa-solid fa-phone-volume text-xs"></i>
                        </div>
                        <div class="leading-tight">
                            <span class="block text-[10px] text-gray-500 font-medium">Hotline / Zalo đặt hàng</span>
                            <span class="block text-sm font-extrabold text-brand-red">0901.956.069</span>
                        </div>
                    </a>

                    <!-- Nút Zalo trên Header -->
                    <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1.5 bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold px-3.5 py-2.5 rounded-full shadow-sm transition">
                        <i class="fa-solid fa-comment-dots"></i>
                        <span>Chat Zalo</span>
                    </a>

                    <!-- Nút Facebook trên Header -->
                    <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-800 text-white text-xs font-bold px-3.5 py-2.5 rounded-full shadow-sm transition">
                        <i class="fa-brands fa-facebook-f"></i>
                        <span>Fanpage</span>
                    </a>

                    <!-- Nút Giỏ Hàng -->
                    <button onclick="openCartModal()" class="relative flex items-center gap-2 bg-amber-50 hover:bg-amber-100 text-amber-900 border border-amber-300 px-3 py-2 rounded-full transition" aria-label="Giỏ hàng">
                        <i class="fa-solid fa-bag-shopping text-brand-red text-base"></i>
                        <span class="hidden sm:inline text-xs font-bold">Giỏ hàng</span>
                        <span id="cartCountBadge" class="w-5 h-5 rounded-full bg-brand-red text-white text-[11px] font-bold flex items-center justify-center">0</span>
                    </button>
                </div>
            </div>

            <!-- Thanh Tìm Kiếm Trên Điện Thoại -->
            <div class="fs-container mt-2.5 md:hidden">
                <div class="relative w-full">
                    <input 
                        type="text" 
                        id="mobileSearchInput"
                        oninput="handleSearch(this.value)"
                        placeholder="Tìm mẫu mèo thần tài khai trương, vẫy tay..." 
                        class="w-full pl-4 pr-10 py-2 text-sm bg-gray-50 border border-gray-300 rounded-full focus:outline-none focus:border-brand-red"
                    >
                    <button class="absolute right-1.5 top-1/2 -translate-y-1/2 w-7 h-7 rounded-full bg-brand-red text-white flex items-center justify-center" aria-label="Tìm kiếm">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- 3. HEADER BOTTOM NAVIGATION (Thanh Danh Mục Chuẩn Flatsome) -->
        <div id="wide-nav" class="bg-brand-red text-white hidden lg:block">
            <div class="fs-container flex items-center justify-between">
                <ul class="flex items-center text-[13px] font-bold uppercase tracking-wide">
                    <li>
                        <a href="#" onclick="filterByCategory('all'); return false;" class="inline-flex items-center gap-2 px-4 py-3 bg-brand-darkRed hover:bg-black/20 transition">
                            <i class="fa-solid fa-bars"></i>
                            <span>Danh Mục Sản Phẩm</span>
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterByCategory('khai-truong')" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition">
                            Mèo Thần Tài Khai Trương
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterByCategory('vay-tay')" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition">
                            Mèo Thần Tài Vẫy Tay
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterByCategory('mini')" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition">
                            Mèo Thần Tài Mini
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterByCategory('may-man')" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition">
                            Mèo Thần Tài May Mắn
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterByCategory('den-led')" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition">
                            Mèo Thần Tài Đèn Led
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterByCategory('phong-thuy')" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition">
                            Vật Phẩm Phong Thủy
                        </a>
                    </li>
                    <li>
                        <a href="#lien-he-bando" class="inline-block px-4 py-3 hover:bg-brand-darkRed transition text-amber-200">
                            <i class="fa-solid fa-location-dot mr-1"></i> Cửa Hàng Đà Nẵng
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         MAIN CONTENT (Chuẩn cấu trúc Section -> Row -> Col của UX Builder)
    ====================================================================== -->
    <main id="main">

        <!-- SECTION 1: HERO BANNER (Banner chính trang chủ) -->
        <section class="section py-4 md:py-6">
            <div class="fs-container">
                <div class="rounded-2xl overflow-hidden bg-gradient-to-r from-[#881313] via-[#B91C1C] to-[#991B1B] text-white shadow-lg border border-amber-500/30">
                    <div class="grid grid-cols-1 lg:grid-cols-12 items-center p-6 sm:p-8 lg:p-10 gap-6">
                        
                        <!-- Cột Nội Dung Banner (7 cột) -->
                        <div class="lg:col-span-7 space-y-4 text-center lg:text-left">
                            <p class="text-amber-300 font-bold text-xs sm:text-sm uppercase tracking-widest">
                                MÈO THẦN TÀI AN NHIÊN • MEOTHANTAIANNHIEN.COM
                            </p>
                            <h1 class="text-2xl sm:text-4xl lg:text-[40px] font-extrabold leading-tight">
                                Mèo Thần Tài Khai Trương <br class="hidden sm:inline">
                                <span class="text-amber-300">Chiêu Tài Đón Lộc</span> Tại Đà Nẵng
                            </h1>
                            <p class="text-red-100 text-sm sm:text-base max-w-xl mx-auto lg:mx-0 leading-relaxed">
                                Chuyên cung cấp các mẫu Mèo Thần Tài gốm sứ cao cấp, mèo vẫy tay, mèo đèn LED và vật phẩm phong thủy. Miễn phí gói quà, tặng thiệp chúc mừng khai trương hồng phát và giao nhanh 2H tại TP. Đà Nẵng.
                            </p>
                            
                            <!-- Thông tin cửa hàng nổi bật -->
                            <div class="bg-black/20 rounded-xl p-3.5 text-left space-y-1.5 border border-white/15 max-w-xl mx-auto lg:mx-0 text-xs sm:text-sm">
                                <div class="flex items-start gap-2">
                                    <i class="fa-solid fa-location-dot text-amber-300 mt-1 shrink-0"></i>
                                    <span><strong>Địa chỉ cửa hàng:</strong> 238 Diên Hồng, Phường Hoà Xuân, Tp.Đà Nẵng</span>
                                </div>
                                <div class="flex items-center gap-2">
                                    <i class="fa-solid fa-phone text-amber-300 shrink-0"></i>
                                    <span><strong>Hotline / Zalo tư vấn:</strong> <a href="tel:0901956069" class="text-amber-300 font-bold underline">0901.956.069</a></span>
                                </div>
                            </div>

                            <!-- Nút hành động -->
                            <div class="flex flex-wrap items-center justify-center lg:justify-start gap-3 pt-2">
                                <a href="#san-pham-chinh" class="px-6 py-3 rounded-full bg-amber-400 hover:bg-amber-300 text-red-950 font-extrabold text-sm shadow-md transition inline-flex items-center gap-2">
                                    <span>Xem Mẫu Mèo Thần Tài</span>
                                    <i class="fa-solid fa-arrow-right"></i>
                                </a>
                                <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="px-5 py-3 rounded-full bg-white/15 hover:bg-white/25 text-white font-bold text-sm border border-white/30 transition inline-flex items-center gap-2">
                                    <i class="fa-solid fa-comment-dots text-amber-300"></i>
                                    <span>Nhắn Zalo: 0901.956.069</span>
                                </a>
                                <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" class="px-5 py-3 rounded-full bg-white/15 hover:bg-white/25 text-white font-bold text-sm border border-white/30 transition inline-flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-amber-300"></i>
                                    <span>Chỉ Đường Google Map</span>
                                </a>
                            </div>
                        </div>

                        <!-- Cột Hình Minh Họa Mèo Thần Tài Lớn (5 cột) -->
                        <div class="lg:col-span-5 flex justify-center">
                            <div class="w-56 h-56 sm:w-72 sm:h-72 rounded-full bg-gradient-to-b from-amber-200/30 to-amber-500/10 p-4 flex items-center justify-center border-2 border-amber-300/40">
                                <!-- Minh họa Mèo Thần Tài Khai Trương Đại Cát -->
                                <svg viewBox="0 0 240 240" class="w-full h-full drop-shadow-xl">
                                    <!-- Vòng hào quang vàng -->
                                    <circle cx="120" cy="120" r="102" fill="#FFFBEB" stroke="#F59E0B" stroke-width="5"/>
                                    <circle cx="120" cy="120" r="93" fill="none" stroke="#B91C1C" stroke-width="1.5" stroke-dasharray="6,4"/>
                                    <!-- Đệm gấm đỏ -->
                                    <rect x="48" y="182" width="144" height="24" rx="12" fill="#991B1B" stroke="#F59E0B" stroke-width="2.5"/>
                                    <path d="M58 194 L182 194" stroke="#FBBF24" stroke-width="2" stroke-dasharray="5,5"/>
                                    <!-- Thân Mèo -->
                                    <ellipse cx="120" cy="142" rx="52" ry="46" fill="#FFFFFF" stroke="#B91C1C" stroke-width="3"/>
                                    <!-- Tai Mèo -->
                                    <path d="M76 74 L68 36 L104 54 Z" fill="#FFFFFF" stroke="#B91C1C" stroke-width="3" stroke-linejoin="round"/>
                                    <path d="M78 68 L74 44 L96 55 Z" fill="#EF4444"/>
                                    <path d="M164 74 L172 36 L136 54 Z" fill="#FFFFFF" stroke="#B91C1C" stroke-width="3" stroke-linejoin="round"/>
                                    <path d="M162 68 L166 44 L144 55 Z" fill="#EF4444"/>
                                    <!-- Đầu Mèo -->
                                    <ellipse cx="120" cy="88" rx="46" ry="38" fill="#FFFFFF" stroke="#B91C1C" stroke-width="3"/>
                                    <!-- Tay trái vẫy cầm câu đối vàng -->
                                    <path d="M72 118 C48 102, 48 64, 68 64 C80 64, 82 88, 78 108" fill="#FFFFFF" stroke="#B91C1C" stroke-width="3"/>
                                    <!-- Tay phải cầm Liễn Kim Tiền -->
                                    <rect x="148" y="106" width="28" height="58" rx="6" fill="#F59E0B" stroke="#92400E" stroke-width="2.5"/>
                                    <circle cx="162" cy="124" r="6" fill="#FEF3C7"/>
                                    <circle cx="162" cy="144" r="6" fill="#FEF3C7"/>
                                    <!-- Khuôn mặt phúc hậu -->
                                    <path d="M94 82 Q103 71 112 82" fill="none" stroke="#1F2937" stroke-width="3.5" stroke-linecap="round"/>
                                    <path d="M128 82 Q137 71 146 82" fill="none" stroke="#1F2937" stroke-width="3.5" stroke-linecap="round"/>
                                    <polygon points="116,90 124,90 120,95" fill="#EF4444"/>
                                    <path d="M110 98 Q120 106 130 98" fill="none" stroke="#B91C1C" stroke-width="2.5" stroke-linecap="round"/>
                                    <circle cx="88" cy="92" r="6" fill="#FCA5A5"/>
                                    <circle cx="152" cy="92" r="6" fill="#FCA5A5"/>
                                    <!-- Yếm đỏ thêu hoa mai & chuông vàng -->
                                    <path d="M78 112 Q120 132 162 112 L156 126 Q120 144 84 126 Z" fill="#DC2626" stroke="#991B1B" stroke-width="2"/>
                                    <circle cx="120" cy="126" r="10" fill="#FBBF24" stroke="#92400E" stroke-width="2"/>
                                    <!-- Bụng Kim Nguyên Bảo -->
                                    <path d="M94 156 Q120 172 146 156 L138 142 Q120 150 102 142 Z" fill="#FBBF24" stroke="#B45309" stroke-width="2"/>
                                </svg>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: CAM KẾT DỊCH VỤ (4 Cột Icon Box chuẩn Flatsome) -->
        <section class="section py-2">
            <div class="fs-container">
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3">
                    <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-brand-border flex items-center gap-3">
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-red-50 text-brand-red flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-truck-fast text-lg sm:text-xl"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-900">Giao Nhanh Đà Nẵng</h3>
                            <p class="text-[11px] sm:text-xs text-gray-500">Ship hỏa tốc trong 1-2 giờ</p>
                        </div>
                    </div>
                    <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-brand-border flex items-center gap-3">
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-amber-50 text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-gift text-lg sm:text-xl"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-900">Miễn Phí Gói Quà</h3>
                            <p class="text-[11px] sm:text-xs text-gray-500">Tặng kèm thiệp mừng khai trương</p>
                        </div>
                    </div>
                    <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-brand-border flex items-center gap-3">
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-red-50 text-brand-red flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-medal text-lg sm:text-xl"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-900">Gốm Sứ Cao Cấp</h3>
                            <p class="text-[11px] sm:text-xs text-gray-500">Tráng men bóng đẹp, bền màu</p>
                        </div>
                    </div>
                    <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-brand-border flex items-center gap-3">
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-full bg-amber-50 text-brand-gold flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-shield-heart text-lg sm:text-xl"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-900">Đổi Trả Tận Tâm</h3>
                            <p class="text-[11px] sm:text-xs text-gray-500">Kiểm tra hàng trước khi nhận</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             SECTION 3: DANH MỤC SẢN PHẨM (Lấy đúng 6 danh mục từ web mẫu)
             Thiết kế tối ưu hiển thị đẹp trên cả Máy Tính (6 cột) và Điện Thoại (3 cột)
        ====================================================================== -->
        <section class="section py-6">
            <div class="fs-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-base sm:text-xl">Danh Mục Sản Phẩm</h2>
                        <button onclick="resetAllFilters()" class="text-xs sm:text-sm font-semibold text-brand-red hover:underline flex items-center gap-1">
                            <span>Xem tất cả</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </button>
                    </div>
                </div>

                <!-- Lưới Danh Mục: Điện thoại 3 cột x 2 hàng cân đối | Máy tính 6 cột -->
                <div id="categoryGrid" class="grid grid-cols-3 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-4">
                    
                    <!-- Danh mục 1: Mèo Thần Tài Khai Trương -->
                    <button onclick="filterByCategory('khai-truong')" data-cat="khai-truong" class="cat-card bg-white rounded-xl p-3 sm:p-4 border border-brand-border flex flex-col items-center text-center group">
                        <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full bg-red-50 border border-red-100 flex items-center justify-center mb-2.5 group-hover:bg-red-100 transition">
                            <svg viewBox="0 0 80 80" class="w-11 h-11 sm:w-14 sm:h-14">
                                <circle cx="40" cy="44" r="24" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5"/>
                                <path d="M22 28 L18 14 L32 22 Z" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2"/>
                                <path d="M58 28 L62 14 L48 22 Z" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2"/>
                                <path d="M30 40 Q34 35 38 40 M42 40 Q46 35 50 40" fill="none" stroke="#1F2937" stroke-width="2" stroke-linecap="round"/>
                                <path d="M24 54 Q40 62 56 54" fill="none" stroke="#DC2626" stroke-width="4" stroke-linecap="round"/>
                                <circle cx="40" cy="58" r="5" fill="#F59E0B"/>
                            </svg>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-brand-red leading-snug">
                            Mèo Thần Tài Khai Trương
                        </span>
                        <span class="text-[11px] text-gray-400 mt-0.5">Quà mừng hồng phát</span>
                    </button>

                    <!-- Danh mục 2: Mèo Thần Tài Vẫy Tay -->
                    <button onclick="filterByCategory('vay-tay')" data-cat="vay-tay" class="cat-card bg-white rounded-xl p-3 sm:p-4 border border-brand-border flex flex-col items-center text-center group">
                        <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full bg-amber-50 border border-amber-100 flex items-center justify-center mb-2.5 group-hover:bg-amber-100 transition">
                            <svg viewBox="0 0 80 80" class="w-11 h-11 sm:w-14 sm:h-14">
                                <circle cx="42" cy="44" r="23" fill="#FEF3C7" stroke="#B45309" stroke-width="2.5"/>
                                <path d="M16 42 C10 30, 12 18, 20 20 C25 22, 24 34, 22 42" fill="#FEF3C7" stroke="#B45309" stroke-width="2.5"/>
                                <path d="M32 40 Q36 35 40 40 M44 40 Q48 35 52 40" fill="none" stroke="#1F2937" stroke-width="2" stroke-linecap="round"/>
                                <rect x="33" y="52" width="18" height="12" rx="3" fill="#DC2626"/>
                            </svg>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-brand-red leading-snug">
                            Mèo Thần Tài Vẫy Tay
                        </span>
                        <span class="text-[11px] text-gray-400 mt-0.5">Chiêu khách tự động</span>
                    </button>

                    <!-- Danh mục 3: Mèo Thần Tài Mini -->
                    <button onclick="filterByCategory('mini')" data-cat="mini" class="cat-card bg-white rounded-xl p-3 sm:p-4 border border-brand-border flex flex-col items-center text-center group">
                        <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full bg-pink-50 border border-pink-100 flex items-center justify-center mb-2.5 group-hover:bg-pink-100 transition">
                            <svg viewBox="0 0 80 80" class="w-11 h-11 sm:w-14 sm:h-14">
                                <circle cx="40" cy="46" r="20" fill="#FCE7F3" stroke="#BE185D" stroke-width="2.5"/>
                                <path d="M25 32 L22 20 L34 26 Z" fill="#FCE7F3" stroke="#BE185D" stroke-width="2"/>
                                <path d="M55 32 L58 20 L46 26 Z" fill="#FCE7F3" stroke="#BE185D" stroke-width="2"/>
                                <path d="M31 43 Q35 39 39 43 M41 43 Q45 39 49 43" fill="none" stroke="#1F2937" stroke-width="2" stroke-linecap="round"/>
                                <circle cx="40" cy="56" r="4.5" fill="#F59E0B"/>
                            </svg>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-brand-red leading-snug">
                            Mèo Thần Tài Mini
                        </span>
                        <span class="text-[11px] text-gray-400 mt-0.5">Để bàn & quầy thu ngân</span>
                    </button>

                    <!-- Danh mục 4: Mèo Thần Tài May Mắn -->
                    <button onclick="filterByCategory('may-man')" data-cat="may-man" class="cat-card bg-white rounded-xl p-3 sm:p-4 border border-brand-border flex flex-col items-center text-center group">
                        <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full bg-red-50 border border-red-100 flex items-center justify-center mb-2.5 group-hover:bg-red-100 transition">
                            <svg viewBox="0 0 80 80" class="w-11 h-11 sm:w-14 sm:h-14">
                                <path d="M16 40 C12 26, 20 20, 24 30" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5"/>
                                <path d="M64 40 C68 26, 60 20, 56 30" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2.5"/>
                                <circle cx="40" cy="45" r="22" fill="#FEE2E2" stroke="#B91C1C" stroke-width="2.5"/>
                                <path d="M28 54 Q40 64 52 54" fill="#F59E0B" stroke="#92400E" stroke-width="1.5"/>
                            </svg>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-brand-red leading-snug">
                            Mèo Thần Tài May Mắn
                        </span>
                        <span class="text-[11px] text-gray-400 mt-0.5">Giơ 2 tay đón lộc</span>
                    </button>

                    <!-- Danh mục 5: Mèo Thần Tài Đèn Led -->
                    <button onclick="filterByCategory('den-led')" data-cat="den-led" class="cat-card bg-white rounded-xl p-3 sm:p-4 border border-brand-border flex flex-col items-center text-center group">
                        <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full bg-amber-50 border border-amber-200 flex items-center justify-center mb-2.5 group-hover:bg-amber-100 transition">
                            <svg viewBox="0 0 80 80" class="w-11 h-11 sm:w-14 sm:h-14">
                                <circle cx="40" cy="40" r="32" fill="none" stroke="#F59E0B" stroke-width="3.5" stroke-dasharray="6,3"/>
                                <circle cx="40" cy="46" r="19" fill="#FFFFFF" stroke="#B91C1C" stroke-width="2"/>
                                <rect x="22" y="64" width="36" height="7" rx="3" fill="#92400E"/>
                            </svg>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-brand-red leading-snug">
                            Mèo Thần Tài Đèn Led
                        </span>
                        <span class="text-[11px] text-gray-400 mt-0.5">Hào quang sang trọng</span>
                    </button>

                    <!-- Danh mục 6: Vật Phẩm Phong Thủy -->
                    <button onclick="filterByCategory('phong-thuy')" data-cat="phong-thuy" class="cat-card bg-white rounded-xl p-3 sm:p-4 border border-brand-border flex flex-col items-center text-center group">
                        <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full bg-emerald-50 border border-emerald-100 flex items-center justify-center mb-2.5 group-hover:bg-emerald-100 transition">
                            <svg viewBox="0 0 80 80" class="w-11 h-11 sm:w-14 sm:h-14">
                                <path d="M24 52 Q40 66 56 52 L50 34 Q40 42 30 34 Z" fill="#F59E0B" stroke="#92400E" stroke-width="2.5"/>
                                <circle cx="40" cy="28" r="10" fill="#10B981" stroke="#065F46" stroke-width="2"/>
                            </svg>
                        </div>
                        <span class="font-bold text-xs sm:text-sm text-gray-800 group-hover:text-brand-red leading-snug">
                            Vật Phẩm Phong Thủy
                        </span>
                        <span class="text-[11px] text-gray-400 mt-0.5">Tụ tài giữ lộc</span>
                    </button>

                </div>
            </div>
        </section>

        <!-- =====================================================================
             SECTION 4: KHU VỰC LỌC NHANH & DANH SÁCH SẢN PHẨM TỔNG HỢP
             - Sản phẩm chia 2 cột trên điện thoại (grid-cols-2) và 4 cột trên máy tính (lg:grid-cols-4)
             - Tuyệt đối không gắn nhãn dán (sticker/badge) trên ảnh sản phẩm
        ====================================================================== -->
        <section id="san-pham-chinh" class="section py-4 scroll-mt-28">
            <div class="fs-container">
                
                <!-- Tiêu đề & Bộ lọc khoảng giá giống web mẫu meothantaikhaitruong.com -->
                <div class="bg-white p-4 rounded-xl border border-brand-border mb-5">
                    <div class="flex flex-col md:flex-row md:items-center justify-between gap-3">
                        
                        <!-- Thanh chọn danh mục nhanh (Cuộn ngang mượt trên điện thoại) -->
                        <div class="flex items-center gap-2 overflow-x-auto no-scrollbar pb-1 md:pb-0">
                            <button onclick="filterByCategory('all')" data-pill="all" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-brand-red text-white transition">
                                Tất cả sản phẩm
                            </button>
                            <button onclick="filterByCategory('khai-truong')" data-pill="khai-truong" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition">
                                Mèo Khai Trương
                            </button>
                            <button onclick="filterByCategory('vay-tay')" data-pill="vay-tay" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition">
                                Mèo Vẫy Tay
                            </button>
                            <button onclick="filterByCategory('mini')" data-pill="mini" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition">
                                Mèo Mini
                            </button>
                            <button onclick="filterByCategory('may-man')" data-pill="may-man" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition">
                                Mèo May Mắn
                            </button>
                            <button onclick="filterByCategory('den-led')" data-pill="den-led" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition">
                                Mèo Đèn Led
                            </button>
                            <button onclick="filterByCategory('phong-thuy')" data-pill="phong-thuy" class="cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition">
                                Vật Phẩm Phong Thủy
                            </button>
                        </div>

                        <!-- Lọc theo Khoảng giá chuẩn web mẫu -->
                        <div class="flex items-center gap-2 shrink-0">
                            <label for="priceFilterSelect" class="text-xs font-semibold text-gray-600">Khoảng giá:</label>
                            <select id="priceFilterSelect" onchange="handlePriceFilter(this.value)" class="text-xs font-semibold bg-gray-50 border border-gray-300 rounded-lg px-3 py-2 focus:outline-none focus:border-brand-red">
                                <option value="all">Tất cả mức giá</option>
                                <option value="under500">Dưới 500k</option>
                                <option value="500to800">Từ 500k - 800k</option>
                                <option value="800to1000">Từ 800k - 1 triệu</option>
                                <option value="over1000">Trên 1 triệu (Trên 1000k)</option>
                            </select>
                        </div>

                    </div>
                </div>

                <!-- Tiêu đề danh mục đang hiển thị -->
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 id="activeCategoryHeading" class="text-base sm:text-xl">Mèo Thần Tài Bán Chạy</h2>
                        <span id="productCountText" class="text-xs sm:text-sm text-gray-500 font-medium">Hiển thị 16 sản phẩm</span>
                    </div>
                </div>

                <!-- LƯỚI SẢN PHẨM: 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2) & 4 CỘT TRÊN MÁY TÍNH (lg:grid-cols-4) -->
                <div id="mainProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Sản phẩm được render tự động bằng JavaScript phía dưới -->
                </div>

            </div>
        </section>

        <!-- =====================================================================
             SECTION 5: MÈO THẦN TÀI TẶNG KHAI TRƯƠNG (Section chuẩn Flatsome)
        ====================================================================== -->
        <section class="section py-6">
            <div class="fs-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-base sm:text-xl">Mèo Thần Tài Tặng Khai Trương</h2>
                        <button onclick="filterByCategory('khai-truong')" class="text-xs sm:text-sm font-semibold text-brand-red hover:underline flex items-center gap-1">
                            <span>Xem thêm</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </button>
                    </div>
                </div>
                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="khaiTruongSectionGrid" class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-5"></div>
            </div>
        </section>

        <!-- =====================================================================
             SECTION 6: MÈO THẦN TÀI ĐÈN LED & VẬT PHẨM PHONG THỦY
        ====================================================================== -->
        <section class="section py-6">
            <div class="fs-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-base sm:text-xl">Mèo Thần Tài Đèn Led & Phong Thủy</h2>
                        <button onclick="filterByCategory('den-led')" class="text-xs sm:text-sm font-semibold text-brand-red hover:underline flex items-center gap-1">
                            <span>Xem thêm</span>
                            <i class="fa-solid fa-angle-right"></i>
                        </button>
                    </div>
                </div>
                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="ledPhongThuySectionGrid" class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-5"></div>
            </div>
        </section>

        <!-- =====================================================================
             SECTION 7: Ý NGHĨA MÈO THẦN TÀI & QUY TRÌNH SẢN XUẤT
             (Chuẩn bố cục 2 khối từ trang mẫu meothantaikhaitruong.com)
        ====================================================================== -->
        <section class="section py-8">
            <div class="fs-container">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-5">
                    
                    <!-- Khối 1: Ý nghĩa Mèo Thần Tài -->
                    <div class="bg-white rounded-2xl p-6 border border-brand-border shadow-sm flex flex-col justify-between">
                        <div>
                            <h3 class="text-lg sm:text-xl font-extrabold text-brand-red uppercase mb-3">
                                Ý Nghĩa Mèo Thần Tài (Maneki Neko)
                            </h3>
                            <p class="text-sm text-gray-600 leading-relaxed mb-4">
                                Mèo Thần Tài được biết đến thông qua các truyền thuyết về chú mèo tốt bụng, luôn mang đến may mắn, tài lộc cho mọi người. Người Nhật coi Mèo Thần Tài như một “lá bùa may mắn” gửi gắm mong ước, hy vọng về công việc kinh doanh thuận buồm xuôi gió, khai trương hồng phát và gia đạo bình an.
                            </p>
                            <ul class="text-xs sm:text-sm text-gray-700 space-y-2 mb-4">
                                <li class="flex items-center gap-2">
                                    <i class="fa-solid fa-check text-brand-red"></i>
                                    <span><strong>Mèo vẫy tay trái:</strong> Thu hút khách hàng, thích hợp cửa hàng, quán cafe, spa.</span>
                                </li>
                                <li class="flex items-center gap-2">
                                    <i class="fa-solid fa-check text-brand-red"></i>
                                    <span><strong>Mèo vẫy tay phải:</strong> Chiêu tài lộc, tiền tài và may mắn cho gia chủ.</span>
                                </li>
                                <li class="flex items-center gap-2">
                                    <i class="fa-solid fa-check text-brand-red"></i>
                                    <span><strong>Mèo giơ hai tay:</strong> Trọn vẹn cả Tài Lộc lẫn Bình An Hưng Thịnh.</span>
                                </li>
                            </ul>
                        </div>
                        <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 text-sm font-bold text-brand-red hover:underline">
                            <span>Nhận tư vấn chọn mẫu hợp mệnh qua Zalo</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                    </div>

                    <!-- Khối 2: Quy trình sản xuất & Chất lượng tại Mèo Thần Tài An Nhiên -->
                    <div class="bg-white rounded-2xl p-6 border border-brand-border shadow-sm flex flex-col justify-between">
                        <div>
                            <h3 class="text-lg sm:text-xl font-extrabold text-brand-red uppercase mb-3">
                                Chất Lượng Gốm Sứ Cao Cấp Tại An Nhiên
                            </h3>
                            <p class="text-sm text-gray-600 leading-relaxed mb-4">
                                Mỗi chú Mèo Thần Tài tại <strong>Mèo Thần Tài An Nhiên (238 Diên Hồng, Đà Nẵng)</strong> đều được chế tác từ chất liệu gốm sứ cao cấp nung ở nhiệt độ cao, tráng men bóng sáng và vẽ họa tiết thủ công sắc nét. Đi kèm đầy đủ đệm gấm đỏ, dây nguồn hoặc pin, hộp quà sang trọng.
                            </p>
                            <ul class="text-xs sm:text-sm text-gray-700 space-y-2 mb-4">
                                <li class="flex items-center gap-2">
                                    <i class="fa-solid fa-check text-brand-gold"></i>
                                    <span>Động cơ vẫy tay êm ái, bền bỉ, vừa dùng điện vừa dùng pin tiện lợi.</span>
                                </li>
                                <li class="flex items-center gap-2">
                                    <i class="fa-solid fa-check text-brand-gold"></i>
                                    <span>Tặng kèm thiệp ghi lời chúc mừng khai trương theo yêu cầu khách hàng.</span>
                                </li>
                                <li class="flex items-center gap-2">
                                    <i class="fa-solid fa-check text-brand-gold"></i>
                                    <span>Có sẵn hàng trực tiếp tại 238 Diên Hồng, Hòa Xuân, TP. Đà Nẵng.</span>
                                </li>
                            </ul>
                        </div>
                        <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 text-sm font-bold text-brand-red hover:underline">
                            <span>Xem đường đi đến cửa hàng 238 Diên Hồng</span>
                            <i class="fa-solid fa-location-arrow"></i>
                        </a>
                    </div>

                </div>
            </div>
        </section>

        <!-- =====================================================================
             SECTION 8: CẨM NANG CHIA SẺ PHONG THỦY (Blog 3 cột chuẩn Flatsome)
        ====================================================================== -->
        <section class="section py-6">
            <div class="fs-container">
                <div class="section-title-container">
                    <div class="section-title-main">
                        <h2 class="text-base sm:text-xl">Góc Chia Sẻ Phong Thủy</h2>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-5">
                    <article class="bg-white rounded-xl border border-brand-border p-5 hover:shadow-md transition">
                        <span class="text-xs font-semibold text-brand-gold uppercase">Kinh nghiệm chọn quà</span>
                        <h3 class="font-bold text-base text-gray-900 mt-1 mb-2">
                            Mèo Thần Tài Màu Trắng Có Ý Nghĩa Gì? Các Mẫu Được Yêu Thích Nhất
                        </h3>
                        <p class="text-xs sm:text-sm text-gray-600 line-clamp-3">
                            Mèo thần tài màu trắng biểu trưng cho sự thuần khiết, may mắn và thu hút quý nhân phù trợ, rất thích hợp đặt tại quầy thu ngân cửa hàng, salon, quán cà phê.
                        </p>
                    </article>

                    <article class="bg-white rounded-xl border border-brand-border p-5 hover:shadow-md transition">
                        <span class="text-xs font-semibold text-brand-gold uppercase">Quà tặng khai trương</span>
                        <h3 class="font-bold text-base text-gray-900 mt-1 mb-2">
                            Cách Chọn Mèo Thần Tài Mừng Khai Trương Cửa Hàng, Công Ty Chuẩn Nhất
                        </h3>
                        <p class="text-xs sm:text-sm text-gray-600 line-clamp-3">
                            Gợi ý cách chọn kích thước và câu chúc trên tay mèo thần tài như Kim Vận Phát Tài, Khai Vận Chiêu Phúc, Sinh Ý Hưng Long phù hợp với từng quy mô cửa hàng.
                        </p>
                    </article>

                    <article class="bg-white rounded-xl border border-brand-border p-5 hover:shadow-md transition">
                        <span class="text-xs font-semibold text-brand-gold uppercase">Phong thủy bài trí</span>
                        <h3 class="font-bold text-base text-gray-900 mt-1 mb-2">
                            Mèo Thần Tài Màu Đỏ & Màu Vàng: Ý Nghĩa Và Vị Trí Đặt Đón Tài Lộc
                        </h3>
                        <p class="text-xs sm:text-sm text-gray-600 line-clamp-3">
                            Hướng dẫn đặt mèo thần tài hướng ra cửa chính hoặc trên bàn thu ngân giúp kích hoạt vượng khí, thu hút khách hàng ghé thăm nườm nượp mỗi ngày.
                        </p>
                    </article>
                </div>
            </div>
        </section>

        <!-- =====================================================================
             SECTION 9: THÔNG TIN LIÊN HỆ & BẢN ĐỒ CỬA HÀNG TẠI ĐÀ NẴNG
        ====================================================================== -->
        <section id="lien-he-bando" class="section py-8 scroll-mt-24">
            <div class="fs-container">
                <div class="bg-white rounded-2xl border border-brand-border p-5 sm:p-8 shadow-sm">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        
                        <div class="lg:col-span-6 space-y-4">
                            <span class="text-xs font-extrabold uppercase tracking-wider text-brand-red">
                                ĐỊA CHỈ MUA MÈO THẦN TÀI UY TÍN TẠI ĐÀ NẴNG
                            </span>
                            <h2 class="text-xl sm:text-2xl font-extrabold text-gray-900">
                                Cửa Hàng Mèo Thần Tài An Nhiên
                            </h2>
                            <div class="space-y-3 text-sm text-gray-700">
                                <p class="flex items-start gap-3">
                                    <i class="fa-solid fa-location-dot text-brand-red mt-1 w-4 text-center"></i>
                                    <span><strong>Địa chỉ:</strong> 238 Diên Hồng, Phường Hoà Xuân, Tp.Đà Nẵng</span>
                                </p>
                                <p class="flex items-center gap-3">
                                    <i class="fa-solid fa-phone-volume text-brand-red w-4 text-center"></i>
                                    <span><strong>Điện thoại / Zalo:</strong> <a href="tel:0901956069" class="text-brand-red font-extrabold hover:underline">0901.956.069</a></span>
                                </p>
                                <p class="flex items-center gap-3">
                                    <i class="fa-solid fa-globe text-brand-red w-4 text-center"></i>
                                    <span><strong>Website:</strong> meothantaiannhien.com</span>
                                </p>
                                <p class="flex items-center gap-3">
                                    <i class="fa-brands fa-facebook text-brand-red w-4 text-center"></i>
                                    <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" class="text-blue-600 font-semibold hover:underline">Mèo Thần Tài An Nhiên Đà Nẵng</a></span>
                                </p>
                            </div>

                            <div class="flex flex-wrap gap-3 pt-2">
                                <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-xl bg-brand-red hover:bg-brand-darkRed text-white font-bold text-xs sm:text-sm inline-flex items-center gap-2 transition shadow-sm">
                                    <i class="fa-solid fa-diamond-turn-right"></i>
                                    <span>Mở Google Maps Chỉ Đường</span>
                                </a>
                                <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-xl bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs sm:text-sm inline-flex items-center gap-2 transition shadow-sm">
                                    <i class="fa-brands fa-facebook-messenger"></i>
                                    <span>Nhắn Tin Fanpage</span>
                                </a>
                            </div>
                        </div>

                        <!-- Khung Bản Đồ 238 Diên Hồng, Hòa Xuân, Đà Nẵng -->
                        <div class="lg:col-span-6">
                            <div class="rounded-xl overflow-hidden border border-gray-200 h-64 sm:h-72 relative bg-gray-100">
                                <iframe 
                                    title="Bản đồ Mèo Thần Tài An Nhiên 238 Diên Hồng Đà Nẵng"
                                    src="https://www.google.com/maps?q=238+Di%C3%AAn+H%E1%BB%93ng,+H%C3%B2a+Xu%C3%A2n,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                                    class="w-full h-full border-0"
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- =====================================================================
         FOOTER (4 Cột chuẩn Flatsome Theme)
    ====================================================================== -->
    <footer id="footer" class="bg-[#1F1614] text-gray-300 pt-12 pb-8 mt-6 border-t-4 border-brand-red">
        <div class="fs-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-brand-red flex items-center justify-center text-amber-300 font-extrabold text-lg">
                            猫
                        </div>
                        <div>
                            <h3 class="font-extrabold text-white text-base leading-none">MÈO THẦN TÀI AN NHIÊN</h3>
                            <span class="text-xs text-amber-400">meothantaiannhien.com</span>
                        </div>
                    </div>
                    <p class="text-xs text-gray-400 leading-relaxed">
                        Chuyên sỉ & lẻ Mèo Thần Tài khai trương, mèo vẫy tay, mèo mini, mèo đèn LED và vật phẩm phong thủy cao cấp tại TP. Đà Nẵng và giao hàng toàn quốc.
                    </p>
                    <div class="text-xs space-y-1.5 text-gray-300 pt-1">
                        <p><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i> 238 Diên Hồng, Phường Hoà Xuân, Tp.Đà Nẵng</p>
                        <p><i class="fa-solid fa-phone text-amber-400 mr-1.5"></i> Hotline / Zalo: <a href="tel:0901956069" class="text-amber-400 font-bold">0901.956.069</a></p>
                        <p><i class="fa-solid fa-globe text-amber-400 mr-1.5"></i> Website: meothantaiannhien.com</p>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 border-b border-white/15 pb-2">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-chinh" onclick="filterByCategory('khai-truong')" class="hover:text-amber-400 transition">• Mèo Thần Tài Khai Trương</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterByCategory('vay-tay')" class="hover:text-amber-400 transition">• Mèo Thần Tài Vẫy Tay</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterByCategory('mini')" class="hover:text-amber-400 transition">• Mèo Thần Tài Mini</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterByCategory('may-man')" class="hover:text-amber-400 transition">• Mèo Thần Tài May Mắn</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterByCategory('den-led')" class="hover:text-amber-400 transition">• Mèo Thần Tài Đèn Led</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterByCategory('phong-thuy')" class="hover:text-amber-400 transition">• Vật Phẩm Phong Thủy</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 border-b border-white/15 pb-2">
                        Hỗ Trợ Khách Hàng
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li>• Tư vấn chọn mẫu hợp mệnh, hợp tuổi</li>
                        <li>• Miễn phí gói quà & ghi thiệp khai trương</li>
                        <li>• Giao hàng hỏa tốc nội thành Đà Nẵng</li>
                        <li>• Ship COD toàn quốc - Kiểm tra trước khi nhận</li>
                        <li>• Bảo hành tay vẫy & nguồn điện chu đáo</li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối mạng xã hội -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 border-b border-white/15 pb-2">
                        Kết Nối Với An Nhiên
                    </h4>
                    <div class="space-y-2.5">
                        <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold flex items-center gap-2.5 transition">
                            <i class="fa-brands fa-facebook text-base"></i>
                            <span>Fanpage Mèo Thần Tài An Nhiên</span>
                        </a>
                        <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-4 rounded-lg bg-blue-500 hover:bg-blue-600 text-white text-xs font-bold flex items-center gap-2.5 transition">
                            <i class="fa-solid fa-comment-dots text-base"></i>
                            <span>Chat Zalo: 0901.956.069</span>
                        </a>
                        <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" class="w-full py-2.5 px-4 rounded-lg bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-bold flex items-center gap-2.5 transition">
                            <i class="fa-solid fa-map-location-dot text-base"></i>
                            <span>Bản Đồ: 238 Diên Hồng, Đà Nẵng</span>
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-6 text-center text-xs text-gray-400">
                <p>© Bản quyền thuộc về <strong>Mèo Thần Tài An Nhiên (meothantaiannhien.com)</strong> - 238 Diên Hồng, Phường Hoà Xuân, Tp.Đà Nẵng.</p>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CỤM NÚT LIÊN HỆ NỔI (ZALO, FACEBOOK, GOOGLE MAP, HOTLINE)
         - Hiển thị cố định góc phải màn hình máy tính & thanh liên hệ dưới điện thoại
    ====================================================================== -->
    <div class="fixed right-3 bottom-20 md:bottom-6 z-40 flex flex-col gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" title="Chat Facebook Fanpage" class="w-11 h-11 md:w-12 md:h-12 rounded-full bg-[#1877F2] hover:scale-110 text-white shadow-lg flex items-center justify-center transition">
            <i class="fa-brands fa-facebook-f text-lg"></i>
        </a>
        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" title="Chat Zalo 0901.956.069" class="w-11 h-11 md:w-12 md:h-12 rounded-full bg-[#0068FF] hover:scale-110 text-white shadow-lg flex items-center justify-center font-extrabold text-[11px] tracking-tighter transition">
            Zalo
        </a>
        <!-- Nút Google Maps -->
        <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" title="Chỉ đường 238 Diên Hồng, Đà Nẵng" class="w-11 h-11 md:w-12 md:h-12 rounded-full bg-emerald-600 hover:scale-110 text-white shadow-lg flex items-center justify-center transition">
            <i class="fa-solid fa-location-dot text-lg"></i>
        </a>
        <!-- Nút Gọi Hotline -->
        <a href="tel:0901956069" title="Gọi 0901.956.069" class="w-11 h-11 md:w-12 md:h-12 rounded-full bg-brand-red text-white shadow-lg flex items-center justify-center pulse-btn">
            <i class="fa-solid fa-phone-volume text-lg"></i>
        </a>
    </div>

    <!-- Thanh Liên Hệ Nhanh Cố Định Dưới Đáy Màn Hình Điện Thoại -->
    <div class="fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-gray-200 grid grid-cols-4 md:hidden shadow-lg">
        <a href="tel:0901956069" class="py-2 flex flex-col items-center justify-center text-brand-red">
            <i class="fa-solid fa-phone-volume text-base"></i>
            <span class="text-[10px] font-bold mt-0.5">0901.956.069</span>
        </a>
        <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="py-2 flex flex-col items-center justify-center text-blue-600">
            <i class="fa-solid fa-comment-dots text-base"></i>
            <span class="text-[10px] font-bold mt-0.5">Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/profile.php?id=61564410320617" target="_blank" rel="noopener noreferrer" class="py-2 flex flex-col items-center justify-center text-[#1877F2]">
            <i class="fa-brands fa-facebook text-base"></i>
            <span class="text-[10px] font-bold mt-0.5">Facebook</span>
        </a>
        <a href="https://maps.app.goo.gl/cJRVsdy5eCPiiKLd6" target="_blank" rel="noopener noreferrer" class="py-2 flex flex-col items-center justify-center text-emerald-600">
            <i class="fa-solid fa-map-location-dot text-base"></i>
            <span class="text-[10px] font-bold mt-0.5">Chỉ đường</span>
        </a>
    </div>

    <!-- =====================================================================
         MENU DRAWER TRÊN ĐIỆN THOẠI (Flatsome Off-Canvas Mobile Menu)
    ====================================================================== -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/50"></div>
        <div class="relative w-72 max-w-[85vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
            <div>
                <div class="p-4 bg-brand-red text-white flex items-center justify-between">
                    <div>
                        <span class="font-extrabold text-sm block">MÈO THẦN TÀI AN NHIÊN</span>
                        <span class="text-[11px] text-amber-200">meothantaiannhien.com</span>
                    </div>
                    <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>

                <div class="p-3">
                    <p class="text-[11px] font-bold uppercase text-gray-400 px-3 py-1">Danh mục sản phẩm</p>
                    <ul class="space-y-1 text-sm font-semibold text-gray-800">
                        <li><button onclick="filterByCategory('all'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Tất cả sản phẩm</button></li>
                        <li><button onclick="filterByCategory('khai-truong'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Mèo Thần Tài Khai Trương</button></li>
                        <li><button onclick="filterByCategory('vay-tay'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Mèo Thần Tài Vẫy Tay</button></li>
                        <li><button onclick="filterByCategory('mini'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Mèo Thần Tài Mini</button></li>
                        <li><button onclick="filterByCategory('may-man'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Mèo Thần Tài May Mắn</button></li>
                        <li><button onclick="filterByCategory('den-led'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Mèo Thần Tài Đèn Led</button></li>
                        <li><button onclick="filterByCategory('phong-thuy'); toggleMobileMenu();" class="w-full text-left px-3 py-2.5 rounded-lg hover:bg-red-50 hover:text-brand-red">Vật Phẩm Phong Thủy</button></li>
                    </ul>
                </div>
            </div>

            <div class="p-4 bg-gray-50 border-t border-gray-200 text-xs space-y-2">
                <p class="font-bold text-gray-800">238 Diên Hồng, P. Hòa Xuân, Đà Nẵng</p>
                <a href="tel:0901956069" class="block w-full py-2.5 text-center rounded-lg bg-brand-red text-white font-bold">
                    Gọi Ngay: 0901.956.069
                </a>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         MODAL XEM NHANH & ĐẶT HÀNG (Quick View / Order Modal)
    ====================================================================== -->
    <div id="productModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-4">
        <div onclick="closeProductModal()" class="absolute inset-0 bg-black/60"></div>
        <div class="relative bg-white rounded-2xl max-w-lg w-full p-5 sm:p-6 shadow-2xl z-10 max-h-[90vh] overflow-y-auto">
            <button onclick="closeProductModal()" class="absolute top-4 right-4 w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 flex items-center justify-center text-gray-600">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="productModalContent"></div>
        </div>
    </div>

    <!-- =====================================================================
         MODAL GIỎ HÀNG (Cart Modal)
    ====================================================================== -->
    <div id="cartModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-4">
        <div onclick="closeCartModal()" class="absolute inset-0 bg-black/60"></div>
        <div class="relative bg-white rounded-2xl max-w-md w-full p-5 sm:p-6 shadow-2xl z-10 max-h-[90vh] overflow-y-auto">
            <div class="flex items-center justify-between border-b pb-3 mb-4">
                <h3 class="font-extrabold text-base text-brand-red uppercase">Giỏ Hàng Của Bạn</h3>
                <button onclick="closeCartModal()" class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="cartItemsContainer" class="space-y-3 text-sm"></div>
            <div class="border-t pt-4 mt-4 space-y-3">
                <div class="flex justify-between font-extrabold text-base">
                    <span>Tổng cộng:</span>
                    <span id="cartTotalPrice" class="text-brand-red">0 ₫</span>
                </div>
                <div class="grid grid-cols-2 gap-2.5">
                    <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="py-2.5 px-4 rounded-xl bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs text-center flex items-center justify-center gap-1.5">
                        <i class="fa-solid fa-comment-dots"></i> Đặt Qua Zalo
                    </a>
                    <a href="tel:0901956069" class="py-2.5 px-4 rounded-xl bg-brand-red hover:bg-brand-darkRed text-white font-bold text-xs text-center flex items-center justify-center gap-1.5">
                        <i class="fa-solid fa-phone"></i> Gọi 0901.956.069
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT LOGIC (Dữ liệu sản phẩm chuẩn web mẫu + Bộ lọc + Giỏ hàng)
    ====================================================================== -->
    <script>
        // Danh sách 16 sản phẩm chuẩn theo danh mục của trang web mẫu meothantaikhaitruong.com
        const PRODUCTS = [
            {
                id: 1,
                name: "Mèo Thần Tài Vẫy Tay Tài Khí Mãn Mãn",
                category: "khai-truong",
                categoryLabel: "Mèo Thần Tài Khai Trương",
                price: 850000,
                size: "Cao 25cm - Gốm sứ tráng men cao cấp",
                style: "whiteGold",
                desc: "Mẫu mèo thần tài vẫy tay chiêu tài lộc, thích hợp làm quà tặng mừng khai trương cửa hàng, quán cà phê, spa, văn phòng công ty."
            },
            {
                id: 2,
                name: "Mèo Thần Tài Vẫy Tay Bát Phương Lai Tài",
                category: "khai-truong",
                categoryLabel: "Mèo Thần Tài Khai Trương",
                price: 950000,
                size: "Cao 28cm - Kèm đệm gấm & hộp quà",
                style: "redGold",
                desc: "Thu hút tài lộc từ tám hướng, giúp gia chủ buôn may bán đắt, khách hàng tấp nập ngày khai trương."
            },
            {
                id: 3,
                name: "Mèo Thần Tài Kim Vận Phát Tài Cỡ Lớn",
                category: "khai-truong",
                categoryLabel: "Mèo Thần Tài Khai Trương",
                price: 1250000,
                size: "Cao 32cm - Mèo thần tài trên 1000k",
                style: "imperialGold",
                desc: "Dòng mèo thần tài cao cấp kích thước lớn đặt tại sảnh chính, quầy thu ngân lớn hoặc tặng đối tác quan trọng."
            },
            {
                id: 4,
                name: "Mèo Thần Tài Khai Vận Chiêu Phúc Đỏ Cát Tường",
                category: "khai-truong",
                categoryLabel: "Mèo Thần Tài Khai Trương",
                price: 680000,
                size: "Cao 23cm - Dùng điện hoặc pin AA",
                style: "redGold",
                desc: "Sắc đỏ đại cát đại lợi mang lại năng lượng tích cực, may mắn và hưng thịnh cho cửa hàng mới khai trương."
            },
            {
                id: 5,
                name: "Mèo Thần Tài Vẫy Tay Chiêu Tài Tiến Bảo",
                category: "vay-tay",
                categoryLabel: "Mèo Thần Tài Vẫy Tay",
                price: 750000,
                size: "Cao 24cm - Tay vẫy tự động êm ái",
                style: "whiteGold",
                desc: "Tay trái vẫy gọi khách hàng liên tục, bụng mèo chạm nổi Kim Nguyên Bảo mang ý nghĩa tiền vào như nước."
            },
            {
                id: 6,
                name: "Mèo Thần Tài Vẫy Tay Kim Ngọc Mãn Đường",
                category: "vay-tay",
                categoryLabel: "Mèo Thần Tài Vẫy Tay",
                price: 680000,
                size: "Cao 22cm - Kèm dây nguồn & đệm lót",
                style: "imperialGold",
                desc: "Lớp men vàng kim sang trọng giúp không gian quầy thu ngân nổi bật và thu hút vượng khí."
            },
            {
                id: 7,
                name: "Mèo Thần Tài Vẫy Tay Thuận Buồm Xuôi Gió",
                category: "vay-tay",
                categoryLabel: "Mèo Thần Tài Vẫy Tay",
                price: 850000,
                size: "Cao 26cm - Gốm sứ Bát Tràng / Nhật Bản",
                style: "whiteGold",
                desc: "Biểu tượng cánh buồm chở đầy vàng bạc vượt sóng lớn, chúc công việc kinh doanh luôn hanh thông."
            },
            {
                id: 8,
                name: "Mèo Thần Tài Mini Tài Nguyên Cổn Cổn (Hồng)",
                category: "mini",
                categoryLabel: "Mèo Thần Tài Mini",
                price: 225000,
                size: "Cao 12cm - Nhỏ gọn để bàn làm việc",
                style: "pinkCute",
                desc: "Mẫu mèo thần tài mini màu hồng ngọt ngào, thích hợp đặt trên bàn làm việc, kệ sách hoặc tặng bạn bè."
            },
            {
                id: 9,
                name: "Mèo Thần Tài Mini Tiền Đa Đa Để Bàn",
                category: "mini",
                categoryLabel: "Mèo Thần Tài Mini",
                price: 255000,
                size: "Cao 14cm - Phù hợp quầy thu ngân nhỏ",
                style: "whiteGold",
                desc: "Kích thước nhỏ xinh nhưng đầy đủ chi tiết chuông vàng, liễn chúc phúc, mang lại niềm vui mỗi ngày."
            },
            {
                id: 10,
                name: "Mèo Thần Tài Vẫy Tay Mini Nguyên Khí Mãn Mãn",
                category: "mini",
                categoryLabel: "Mèo Thần Tài Mini",
                price: 360000,
                size: "Cao 16cm - Dùng pin tiện lợi",
                style: "redGold",
                desc: "Mẫu mèo vẫy tay cỡ nhỏ không tốn diện tích, đặt gọn trên bàn lễ tân, xe bán hàng hoặc bàn làm việc."
            },
            {
                id: 11,
                name: "Mèo Thần Tài Giơ Hai Tay Sinh Ý Hưng Long",
                category: "may-man",
                categoryLabel: "Mèo Thần Tài May Mắn",
                price: 750000,
                size: "Cao 24cm - Giơ 2 tay đón Tài & Lộc",
                style: "doublePaw",
                desc: "Chú mèo giơ cả hai tay vừa đón khách hàng vừa giữ trọn tài lộc, bình an cho gia đình và cửa tiệm."
            },
            {
                id: 12,
                name: "Mèo Thần Tài Giơ Hai Tay Đại Cát Đại Lợi",
                category: "may-man",
                categoryLabel: "Mèo Thần Tài May Mắn",
                price: 450000,
                size: "Cao 20cm - Gốm sứ vẽ tay sắc nét",
                style: "doublePaw",
                desc: "Nụ cười hoan hỷ an nhiên mang đến không khí vui vẻ, hòa thuận và may mắn suốt bốn mùa."
            },
            {
                id: 13,
                name: "Mèo Thần Tài Đèn Led Hào Quang Chiêu Tài",
                category: "den-led",
                categoryLabel: "Mèo Thần Tài Đèn Led",
                price: 1150000,
                size: "Cao 35cm - Vòng đèn LED ánh vàng ấm",
                style: "ledHalo",
                desc: "Kết hợp tượng Mèo Thần Tài cùng vòng hào quang đèn LED sang trọng, cực kỳ nổi bật tại phòng khách và quầy lễ tân."
            },
            {
                id: 14,
                name: "Mèo Thần Tài Đèn Led Trăng Khuyết Bình An",
                category: "den-led",
                categoryLabel: "Mèo Thần Tài Đèn Led",
                price: 980000,
                size: "Cao 30cm - Có công tắc bật/tắt đèn",
                style: "ledHalo",
                desc: "Ánh sáng vàng dịu nhẹ kết hợp chú mèo thần tài An Nhiên tạo điểm nhấn phong thủy ấm cúng."
            },
            {
                id: 15,
                name: "Bắp Cải Phong Thủy Ngọc Xanh Chiêu Tài",
                category: "phong-thuy",
                categoryLabel: "Vật Phẩm Phong Thủy",
                price: 790000,
                size: "Cao 24cm - Đế gỗ sang trọng",
                style: "fengShui",
                desc: "Bắp cải phong thủy (Bách Tài) tượng trưng cho túi đựng tiền tài, giúp giữ của cải và sinh sôi tài lộc."
            },
            {
                id: 16,
                name: "Cây Kim Tiền Phong Thủy Đế Kim Nguyên Bảo",
                category: "phong-thuy",
                categoryLabel: "Vật Phẩm Phong Thủy",
                price: 650000,
                size: "Cao 25cm - Vật phẩm trưng bày thu ngân",
                style: "fengShui",
                desc: "Cây tài lộc sum suê trái vàng đặt cạnh Mèo Thần Tài giúp nhân đôi vượng khí cho cửa hàng kinh doanh."
            }
        ];

        let currentCategory = 'all';
        let currentPriceRange = 'all';
        let searchQuery = '';
        let cart = [];

        // Hàm tạo hình minh họa SVG Mèo Thần Tài riêng biệt theo từng kiểu dáng (Không có bất kỳ nhãn dán nào)
        function getCatIllustrationSVG(style) {
            const palettes = {
                whiteGold: { body: '#FFFFFF', stroke: '#B91C1C', ear: '#EF4444', collar: '#DC2626', accent: '#F59E0B', halo: false, doublePaw: false, fengShui: false },
                redGold: { body: '#FEE2E2', stroke: '#991B1B', ear: '#DC2626', collar: '#B91C1C', accent: '#F59E0B', halo: false, doublePaw: false, fengShui: false },
                imperialGold: { body: '#FEF3C7', stroke: '#B45309', ear: '#D97706', collar: '#B91C1C', accent: '#F59E0B', halo: false, doublePaw: false, fengShui: false },
                pinkCute: { body: '#FCE7F3', stroke: '#BE185D', ear: '#EC4899', collar: '#E11D48', accent: '#FBBF24', halo: false, doublePaw: false, fengShui: false },
                doublePaw: { body: '#FFFFFF', stroke: '#B91C1C', ear: '#EF4444', collar: '#DC2626', accent: '#F59E0B', halo: false, doublePaw: true, fengShui: false },
                ledHalo: { body: '#FFFFFF', stroke: '#B45309', ear: '#EF4444', collar: '#DC2626', accent: '#F59E0B', halo: true, doublePaw: false, fengShui: false },
                fengShui: { body: '#ECFDF5', stroke: '#047857', ear: '#10B981', collar: '#B45309', accent: '#F59E0B', halo: false, doublePaw: false, fengShui: true }
            };

            const p = palettes[style] || palettes.whiteGold;

            if (p.fengShui) {
                return `
                <svg viewBox="0 0 200 200" class="w-4/5 h-4/5">
                    <circle cx="100" cy="100" r="78" fill="#FFFBEB" stroke="#F59E0B" stroke-width="2" stroke-dasharray="4,4"/>
                    <rect x="46" y="150" width="108" height="18" rx="6" fill="#78350F"/>
                    <path d="M56 150 Q100 168 144 150 L134 118 Q100 130 66 118 Z" fill="#F59E0B" stroke="#92400E" stroke-width="2.5"/>
                    <circle cx="100" cy="84" r="36" fill="#10B981" stroke="#065F46" stroke-width="2.5"/>
                    <circle cx="84" cy="76" r="10" fill="#FBBF24"/>
                    <circle cx="116" cy="76" r="10" fill="#FBBF24"/>
                    <circle cx="100" cy="60" r="10" fill="#FBBF24"/>
                    <circle cx="100" cy="96" r="11" fill="#FBBF24"/>
                </svg>`;
            }

            return `
            <svg viewBox="0 0 200 200" class="w-4/5 h-4/5">
                ${p.halo ? `<circle cx="100" cy="98" r="82" fill="none" stroke="#F59E0B" stroke-width="5"/>
                            <circle cx="100" cy="98" r="76" fill="none" stroke="#FDE68A" stroke-width="2" stroke-dasharray="5,3"/>` : ''}
                <!-- Đệm gấm đỏ -->
                <rect x="42" y="158" width="116" height="18" rx="9" fill="#991B1B" stroke="#F59E0B" stroke-width="2"/>
                <!-- Thân mèo -->
                <ellipse cx="100" cy="124" rx="44" ry="38" fill="${p.body}" stroke="${p.stroke}" stroke-width="2.5"/>
                <!-- Tai mèo -->
                <path d="M64 68 L58 38 L88 52 Z" fill="${p.body}" stroke="${p.stroke}" stroke-width="2.5" stroke-linejoin="round"/>
                <path d="M66 63 L62 45 L82 53 Z" fill="${p.ear}"/>
                <path d="M136 68 L142 38 L112 52 Z" fill="${p.body}" stroke="${p.stroke}" stroke-width="2.5" stroke-linejoin="round"/>
                <path d="M134 63 L138 45 L118 53 Z" fill="${p.ear}"/>
                <!-- Đầu mèo -->
                <ellipse cx="100" cy="80" rx="38" ry="32" fill="${p.body}" stroke="${p.stroke}" stroke-width="2.5"/>
                <!-- Tay trái vẫy -->
                <path d="M60 104 C40 90, 42 58, 58 58 C68 58, 68 78, 66 96" fill="${p.body}" stroke="${p.stroke}" stroke-width="2.5"/>
                ${p.doublePaw
                    ? `<path d="M140 104 C160 90, 158 58, 142 58 C132 58, 132 78, 134 96" fill="${p.body}" stroke="${p.stroke}" stroke-width="2.5"/>`
                    : `<rect x="124" y="96" width="22" height="46" rx="5" fill="#F59E0B" stroke="#92400E" stroke-width="2"/>`
                }
                <!-- Mắt cười -->
                <path d="M78 76 Q86 67 94 76" fill="none" stroke="#1F2937" stroke-width="2.8" stroke-linecap="round"/>
                <path d="M106 76 Q114 67 122 76" fill="none" stroke="#1F2937" stroke-width="2.8" stroke-linecap="round"/>
                <!-- Mũi & Miệng -->
                <polygon points="97,82 103,82 100,86" fill="#EF4444"/>
                <path d="M92 89 Q100 95 108 89" fill="none" stroke="#B91C1C" stroke-width="2" stroke-linecap="round"/>
                <circle cx="73" cy="84" r="4.5" fill="#FCA5A5"/>
                <circle cx="127" cy="84" r="4.5" fill="#FCA5A5"/>
                <!-- Yếm & Chuông vàng -->
                <path d="M66 100 Q100 116 134 100" fill="none" stroke="${p.collar}" stroke-width="6" stroke-linecap="round"/>
                <circle cx="100" cy="109" r="8" fill="${p.accent}" stroke="#92400E" stroke-width="1.8"/>
                <!-- Kim nguyên bảo -->
                <path d="M78 138 Q100 150 122 138 L116 126 Q100 132 84 126 Z" fill="#FBBF24" stroke="#B45309" stroke-width="1.8"/>
            </svg>`;
        }

        function formatCurrency(amount) {
            return amount.toLocaleString('vi-VN') + ' ₫';
        }

        // Tạo HTML cho từng thẻ sản phẩm chuẩn Flatsome (Không có bất kỳ nhãn dán/sticker nào)
        function createProductCardHTML(product) {
            return `
            <div class="col">
                <div class="product-small box">
                    <!-- Hình ảnh sản phẩm sạch sẽ, không nhãn dán -->
                    <div class="box-image cursor-pointer" onclick="openProductModal(${product.id})">
                        ${getCatIllustrationSVG(product.style)}
                    </div>
                    <!-- Nội dung sản phẩm -->
                    <div class="box-text p-3 sm:p-4 flex flex-col flex-1 justify-between text-center">
                        <div>
                            <p class="text-[10px] sm:text-[11px] text-gray-400 uppercase tracking-wide mb-1 truncate">
                                ${product.categoryLabel}
                            </p>
                            <h3 onclick="openProductModal(${product.id})" class="text-xs sm:text-sm font-bold text-gray-800 hover:text-brand-red cursor-pointer line-clamp-2 min-h-[2.5rem] leading-snug">
                                ${product.name}
                            </h3>
                        </div>
                        <div class="pt-2.5 mt-2 border-t border-gray-100">
                            <div class="text-sm sm:text-base font-extrabold text-brand-red mb-2.5">
                                ${formatCurrency(product.price)}
                            </div>
                            <div class="grid grid-cols-2 gap-1.5">
                                <button onclick="addToCart(${product.id})" class="py-2 px-2 rounded-lg bg-brand-red hover:bg-brand-darkRed text-white font-bold text-[11px] sm:text-xs transition">
                                    Đặt mua
                                </button>
                                <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="py-2 px-2 rounded-lg bg-amber-50 hover:bg-amber-100 text-amber-900 border border-amber-300 font-bold text-[11px] sm:text-xs transition flex items-center justify-center">
                                    Tư vấn Zalo
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>`;
        }

        // Render danh sách sản phẩm chính theo bộ lọc
        function renderMainProducts() {
            const grid = document.getElementById('mainProductGrid');
            const countText = document.getElementById('productCountText');
            const heading = document.getElementById('activeCategoryHeading');

            const categoryTitles = {
                'all': 'Mèo Thần Tài Bán Chạy',
                'khai-truong': 'Mèo Thần Tài Khai Trương',
                'vay-tay': 'Mèo Thần Tài Vẫy Tay',
                'mini': 'Mèo Thần Tài Mini',
                'may-man': 'Mèo Thần Tài May Mắn',
                'den-led': 'Mèo Thần Tài Đèn Led',
                'phong-thuy': 'Vật Phẩm Phong Thủy'
            };

            heading.textContent = categoryTitles[currentCategory] || 'Danh Sách Sản Phẩm';

            const filtered = PRODUCTS.filter(item => {
                const matchCat = currentCategory === 'all' || item.category === currentCategory;
                const matchSearch = item.name.toLowerCase().includes(searchQuery.toLowerCase()) ||
                                    item.categoryLabel.toLowerCase().includes(searchQuery.toLowerCase());
                let matchPrice = true;
                if (currentPriceRange === 'under500') matchPrice = item.price < 500000;
                else if (currentPriceRange === '500to800') matchPrice = item.price >= 500000 && item.price <= 800000;
                else if (currentPriceRange === '800to1000') matchPrice = item.price > 800000 && item.price <= 1000000;
                else if (currentPriceRange === 'over1000') matchPrice = item.price > 1000000;

                return matchCat && matchSearch && matchPrice;
            });

            countText.textContent = `Hiển thị ${filtered.length} sản phẩm`;

            if (filtered.length === 0) {
                grid.innerHTML = `
                <div class="col-span-2 lg:col-span-4 bg-white rounded-xl p-8 text-center border border-brand-border">
                    <p class="text-sm text-gray-600 mb-3">Không tìm thấy mẫu phù hợp với bộ lọc hiện tại.</p>
                    <button onclick="resetAllFilters()" class="px-5 py-2 rounded-full bg-brand-red text-white text-xs font-bold">
                        Xem tất cả sản phẩm
                    </button>
                </div>`;
                return;
            }

            grid.innerHTML = filtered.map(createProductCardHTML).join('');
        }

        // Render các Section chuyên đề bên dưới
        function renderCategorySections() {
            const khaiTruongItems = PRODUCTS.filter(p => p.category === 'khai-truong').slice(0, 4);
            document.getElementById('khaiTruongSectionGrid').innerHTML = khaiTruongItems.map(createProductCardHTML).join('');

            const ledPhongThuyItems = PRODUCTS.filter(p => p.category === 'den-led' || p.category === 'phong-thuy').slice(0, 4);
            document.getElementById('ledPhongThuySectionGrid').innerHTML = ledPhongThuyItems.map(createProductCardHTML).join('');
        }

        // Lọc theo Danh mục
        function filterByCategory(cat) {
            currentCategory = cat;

            // Cập nhật trạng thái thẻ danh mục
            document.querySelectorAll('.cat-card').forEach(btn => {
                btn.classList.toggle('active', btn.getAttribute('data-cat') === cat);
            });

            // Cập nhật trạng thái nút pill
            document.querySelectorAll('.cat-pill').forEach(pill => {
                const isActive = pill.getAttribute('data-pill') === cat;
                pill.className = isActive
                    ? 'cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-brand-red text-white transition'
                    : 'cat-pill shrink-0 px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-red-50 hover:text-brand-red transition';
            });

            renderMainProducts();
            document.getElementById('san-pham-chinh').scrollIntoView({ behavior: 'smooth', block: 'start' });
        }

        // Lọc theo Khoảng giá
        function handlePriceFilter(range) {
            currentPriceRange = range;
            renderMainProducts();
        }

        // Tìm kiếm theo từ khóa
        function handleSearch(query) {
            searchQuery = query.trim();
            renderMainProducts();
        }

        // Đặt lại toàn bộ bộ lọc
        function resetAllFilters() {
            currentCategory = 'all';
            currentPriceRange = 'all';
            searchQuery = '';
            document.getElementById('priceFilterSelect').value = 'all';
            const dInput = document.getElementById('desktopSearchInput');
            const mInput = document.getElementById('mobileSearchInput');
            if (dInput) dInput.value = '';
            if (mInput) mInput.value = '';
            filterByCategory('all');
        }

        // Mở/Đóng Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        // Mở Modal chi tiết sản phẩm
        function openProductModal(id) {
            const product = PRODUCTS.find(p => p.id === id);
            if (!product) return;

            const modal = document.getElementById('productModal');
            const content = document.getElementById('productModalContent');

            content.innerHTML = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-center">
                    <div class="aspect-square rounded-xl bg-amber-50/60 border border-amber-200 flex items-center justify-center p-4">
                        ${getCatIllustrationSVG(product.style)}
                    </div>
                    <div class="space-y-3">
                        <span class="text-xs font-bold text-brand-gold uppercase">${product.categoryLabel}</span>
                        <h3 class="text-lg font-extrabold text-gray-900 leading-snug">${product.name}</h3>
                        <div class="text-xl font-extrabold text-brand-red">${formatCurrency(product.price)}</div>
                        <p class="text-xs text-gray-600 leading-relaxed">${product.desc}</p>
                        <div class="bg-gray-50 p-3 rounded-lg text-xs space-y-1 border border-gray-200">
                            <p><strong>Kích thước:</strong> ${product.size}</p>
                            <p><strong>Cửa hàng:</strong> 238 Diên Hồng, Hòa Xuân, Đà Nẵng</p>
                            <p><strong>Ưu đãi:</strong> Miễn phí gói quà & tặng thiệp khai trương</p>
                        </div>
                        <div class="flex flex-col gap-2 pt-2">
                            <button onclick="addToCart(${product.id}); closeProductModal();" class="w-full py-2.5 rounded-xl bg-brand-red hover:bg-brand-darkRed text-white font-bold text-xs uppercase">
                                Thêm Vào Giỏ Hàng
                            </button>
                            <div class="grid grid-cols-2 gap-2">
                                <a href="https://zalo.me/0901956069" target="_blank" rel="noopener noreferrer" class="py-2.5 rounded-xl bg-blue-600 text-white font-bold text-xs text-center">
                                    Đặt Qua Zalo
                                </a>
                                <a href="tel:0901956069" class="py-2.5 rounded-xl bg-amber-500 text-white font-bold text-xs text-center">
                                    Gọi 0901.956.069
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            `;
            modal.classList.remove('hidden');
        }

        function closeProductModal() {
            document.getElementById('productModal').classList.add('hidden');
        }

        // Quản lý Giỏ hàng
        function addToCart(id) {
            const product = PRODUCTS.find(p => p.id === id);
            if (!product) return;

            const existing = cart.find(item => item.id === id);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...product, qty: 1 });
            }
            updateCartUI();
            openCartModal();
        }

        function removeFromCart(id) {
            cart = cart.filter(item => item.id !== id);
            updateCartUI();
        }

        function updateCartUI() {
            const totalCount = cart.reduce((sum, item) => sum + item.qty, 0);
            const totalPrice = cart.reduce((sum, item) => sum + item.price * item.qty, 0);

            document.getElementById('cartCountBadge').textContent = totalCount;
            document.getElementById('cartTotalPrice').textContent = formatCurrency(totalPrice);

            const container = document.getElementById('cartItemsContainer');
            if (cart.length === 0) {
                container.innerHTML = `<p class="text-center text-gray-500 py-6">Giỏ hàng của bạn đang trống.</p>`;
                return;
            }

            container.innerHTML = cart.map(item => `
                <div class="flex items-center justify-between gap-3 bg-gray-50 p-3 rounded-xl border border-gray-200">
                    <div class="flex-1">
                        <h4 class="font-bold text-xs text-gray-800">${item.name}</h4>
                        <p class="text-xs text-brand-red font-bold mt-0.5">${formatCurrency(item.price)} x ${item.qty}</p>
                    </div>
                    <button onclick="removeFromCart(${item.id})" class="text-gray-400 hover:text-red-600 p-1">
                        <i class="fa-solid fa-trash-can"></i>
                    </button>
                </div>
            `).join('');
        }

        function openCartModal() {
            updateCartUI();
            document.getElementById('cartModal').classList.remove('hidden');
        }

        function closeCartModal() {
            document.getElementById('cartModal').classList.add('hidden');
        }

        // Khởi chạy khi tải trang
        window.onload = function () {
            renderMainProducts();
            renderCategorySections();
            updateCartUI();
        };
    </script>
</body>
</html>
