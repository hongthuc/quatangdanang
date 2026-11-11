<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>quatangdanang.com - Shop Quà Tặng Đẹp Tại Đà Nẵng & Nước Hoa Charme Chính Hãng</title>
    <meta name="description" content="Shop Quà Tặng Đẹp Tại Đà Nẵng (quatangdanang.com) - Chuyên quà tặng sinh nhật, Valentine, Noel, 20/10, 8/3, 20/11, Set quà doanh nghiệp và Nước hoa Charme Chính hãng Đà Nẵng. Địa chỉ: 154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng. Hotline: 0932.046.022">

    <!-- Thumbnail là ảnh Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://quatangdanang.com/">
    <meta property="og:title" content="quatangdanang.com - Shop Quà Tặng Đẹp & Nước Hoa Charme Chính Hãng Đà Nẵng">
    <meta property="og:description" content="Chuyên quà tặng sinh nhật, Valentine, Noel, 20/10, 8/3, 20/11, Set quà tặng cao cấp & Nước hoa Charme chính hãng tại 154 Nguyễn Phước Nguyên, Đà Nẵng.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            DEFAULT: '#9E2A2B', /* Đỏ rượu vang sang trọng đồng bộ Logo & phong cách ANSGIFT */
                            dark: '#7A1C1D',
                            light: '#FDF4F4',
                            gold: '#C89B3C',    /* Vàng ánh kim nước hoa Charme & hộp quà cao cấp */
                            goldLight: '#F9F3E5',
                            text: '#2B2B2B'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #2B2B2B;
            background-color: #FAFAFA;
            -webkit-font-smoothing: antialiased;
        }

        /* Chuẩn khung 1500px trên máy tính của Flatsome */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Danh mục không bao giờ bị xuống dòng giữa chừng */
        .cat-pill {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }
        .cat-pill:hover, .cat-pill.active {
            background-color: #9E2A2B;
            color: #ffffff;
            border-color: #9E2A2B;
        }

        /* Badge giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-Wait-badge, .badge-circle-sale {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            background-color: #9E2A2B;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            width: 42px;
            height: 42px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.18);
            letter-spacing: -0.3px;
        }

        /* Card sản phẩm Flatsome: Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-box {
            background: #ffffff;
            border: 1px solid #ECECEC;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .product-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.07);
            border-color: #DFC5C5;
        }
        .product-title {
            font-size: 13.5px;
            line-height: 1.45;
            font-weight: 600;
            color: #222222;
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 6px;
        }
        @media (max-width: 640px) {
            .product-title {
                font-size: 12.5px;
                line-height: 1.4;
            }
            .badge-circle-sale {
                width: 36px;
                height: 36px;
                font-size: 11px;
                top: 6px;
                left: 6px;
            }
        }

        /* Tiêu đề Section kiểu Flatsome Title */
        .section-title-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #EFEFEF;
            margin-bottom: 20px;
            padding-bottom: 10px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .section-title-main {
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            color: #9E2A2B;
            position: relative;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -12px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #C89B3C;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(158, 42, 43, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(158, 42, 43, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(158, 42, 43, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==========================================
         TOP BAR (Chuẩn ANSGIFT / Flatsome)
    =========================================== -->
    <div class="bg-brand text-white text-xs py-2 border-b border-brand-dark">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <i class="fa-solid fa-gift text-brand-gold"></i>
                <span>Shop Quà Tặng Đẹp Đà Nẵng & Nước Hoa Charme Chính Hãng - Giao Nhanh Nội Thành Đà Nẵng</span>
            </div>
            <div class="hidden md:flex items-center gap-5 text-xs font-medium shrink-0">
                <span><i class="fa-solid fa-location-dot text-brand-gold mr-1"></i> 154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng</span>
                <span><i class="fa-solid fa-phone-volume text-brand-gold mr-1"></i> Hotline/Zalo: <strong>0932.046.022</strong></span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Logo gọn nhỏ, Không để nút Gọi ngay để tránh tràn viền)
    =========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-gray-100">
        <div class="flatsome-container py-2.5">
            <div class="flex items-center justify-between gap-3">
                
                <!-- Nút mở Menu trên Điện thoại -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2 text-gray-700 hover:text-brand focus:outline-none shrink-0" aria-label="Menu">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>

                <!-- LOGO MỚI CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-gradient-to-br from-brand to-brand-dark flex items-center justify-center shadow-sm border border-brand-gold/50 shrink-0">
                        <!-- Biểu tượng Hộp Quà & Giọt Nước Hoa Charme الراقية -->
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <!-- Nơ hộp quà vàng kim -->
                            <path d="M32 18C26 10 16 11 16 18C16 23 25 24 32 24C39 24 48 23 48 18C48 11 38 10 32 18Z" stroke="#C89B3C" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <!-- Thân hộp quà kết hợp lọ nước hoa -->
                            <rect x="12" y="24" width="40" height="8" rx="2" fill="#C89B3C"/>
                            <rect x="15" y="32" width="34" height="22" rx="3" stroke="#FFFFFF" stroke-width="3" fill="#9E2A2B"/>
                            <path d="M32 24V54" stroke="#C89B3C" stroke-width="3.5"/>
                            <circle cx="32" cy="42" r="4" fill="#C89B3C"/>
                        </svg>
                    </div>
                    <div class="flex flex-col">
                        <span class="font-heading font-extrabold text-sm sm:text-base md:text-lg tracking-tight text-brand leading-none">
                            QUATANGDANANG<span class="text-brand-gold">.COM</span>
                        </span>
                        <span class="text-[10px] sm:text-[11px] text-gray-500 font-medium tracking-tight mt-0.5">
                            Quà Tặng Đẹp & Nước Hoa Charme
                        </span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm (Gọn gàng ở giữa trên Desktop) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input id="desktopSearchInput" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm set quà 8/3, 20/10, 20/11, sinh nhật, nước hoa Charme..." class="w-full pl-3.5 pr-10 py-2 text-xs bg-gray-50 border border-gray-200 rounded-full focus:outline-none focus:border-brand focus:bg-white transition">
                        <button onclick="filterProductsBySearch(document.getElementById('desktopSearchInput').value)" class="absolute right-1.5 top-1/2 -translate-y-1/2 w-7 h-7 bg-brand text-white rounded-full flex items-center justify-center hover:bg-brand-dark transition">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Khu vực tiện ích bên phải (Không để nút Gọi ngay tránh tràn viền) -->
                <div class="flex items-center gap-2 sm:gap-3 shrink-0">
                    <a href="#bao-gia-section" class="hidden sm:inline-flex items-center gap-1.5 px-3 py-1.5 text-xs font-semibold text-brand bg-brand-light border border-brand/20 rounded-full hover:bg-brand hover:text-white transition">
                        <i class="fa-regular fa-paper-plane"></i>
                        <span>Nhận Báo Giá</span>
                    </a>
                    <button onclick="openCartModal()" class="relative p-2 text-gray-700 hover:text-brand transition flex items-center gap-1.5 bg-gray-50 rounded-full px-3 border border-gray-200">
                        <i class="fa-solid fa-bag-shopping text-brand text-sm"></i>
                        <span class="text-xs font-semibold hidden sm:inline">Giỏ hàng</span>
                        <span id="cartCountBadge" class="bg-brand text-white text-[10px] font-bold w-4 h-4 rounded-full flex items-center justify-center">0</span>
                    </button>
                </div>

            </div>

            <!-- Thanh tìm kiếm trên Điện thoại -->
            <div class="mt-2 md:hidden">
                <div class="relative w-full">
                    <input id="mobileSearchInput" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm quà sinh nhật, 8/3, 20/10, nước hoa Charme..." class="w-full pl-3.5 pr-9 py-1.5 text-xs bg-gray-50 border border-gray-200 rounded-full focus:outline-none focus:border-brand">
                    <i class="fa-solid fa-magnifying-glass text-gray-400 text-xs absolute right-3 top-1/2 -translate-y-1/2"></i>
                </div>
            </div>
        </div>

        <!-- ==========================================
             THANH DANH MỤC TRÊN MÁY TÍNH (Tối ưu nằm gọn trên 1 hàng hoặc xuống hàng 2, chữ nhỏ gọn, tuyệt đối không gãy chữ tên danh mục)
        =========================================== -->
        <nav class="hidden lg:block bg-brand-light/70 border-t border-gray-200/80">
            <div class="flatsome-container py-2">
                <ul class="flex flex-wrap items-center justify-center gap-x-1.5 gap-y-1.5">
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('all', event)" class="cat-pill active text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            <i class="fa-solid fa-border-all mr-1 text-[11px]"></i>Tất Cả Sản Phẩm
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Nước Hoa Charme', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Nước Hoa Charme
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Set Quà Tặng', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Set Quà Tặng
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Quà Sinh Nhật', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-200">
                            Quà Sinh Nhật
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Quà 8/3 & 20/10', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Quà 8/3 & 20/10
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Quà Tặng 20/11', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Quà Tặng 20/11
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Valentine & Noel', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Quà Valentine & Noel
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Bình Giữ Nhiệt In Logo', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Bình Giữ Nhiệt In Logo
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Ly Tách & Sổ Tay', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Ly Tách & Sổ Tay
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="selectCategory('Tiện Ích Văn Phòng', event)" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Tiện Ích Văn Phòng
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc-section" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Tin Tức
                        </a>
                    </li>
                    <li>
                        <a href="#lien-he-section" class="cat-pill text-[12px] font-semibold px-2.5 py-1 rounded bg-white text-gray-800 border border-gray-200">
                            Liên Hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ==========================================
         DRAWER MENU ĐIỆN THOẠI
    =========================================== -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/50 z-50 hidden transition-opacity"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[82vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-xl">
        <div class="p-4 bg-brand text-white flex items-center justify-between">
            <span class="font-heading font-bold text-sm">DANH MỤC QUÀ TẶNG</span>
            <button onclick="toggleMobileMenu()" class="text-white p-1">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>
        <div class="p-3 overflow-y-auto flex-1 space-y-1 text-xs font-semibold">
            <a href="#san-pham-section" onclick="selectCategory('all', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded bg-brand-light text-brand">Tất Cả Sản Phẩm</a>
            <a href="#san-pham-section" onclick="selectCategory('Nước Hoa Charme', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Nước Hoa Charme Chính Hãng</a>
            <a href="#san-pham-section" onclick="selectCategory('Set Quà Tặng', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Set Quà Tặng Cao Cấp</a>
            <a href="#san-pham-section" onclick="selectCategory('Quà Sinh Nhật', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Quà Tặng Sinh Nhật</a>
            <a href="#san-pham-section" onclick="selectCategory('Quà 8/3 & 20/10', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Quà Tặng 8/3 & 20/10</a>
            <a href="#san-pham-section" onclick="selectCategory('Quà Tặng 20/11', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Quà Tặng Thầy Cô 20/11</a>
            <a href="#san-pham-section" onclick="selectCategory('Valentine & Noel', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Quà Valentine & Noel</a>
            <a href="#san-pham-section" onclick="selectCategory('Bình Giữ Nhiệt In Logo', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Bình Giữ Nhiệt In Logo</a>
            <a href="#san-pham-section" onclick="selectCategory('Ly Tách & Sổ Tay', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Ly Tách & Sổ Tay In Logo</a>
            <a href="#san-pham-section" onclick="selectCategory('Tiện Ích Văn Phòng', event); toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Tiện Ích Văn Phòng & Trâm Cài Áo</a>
            <hr class="my-2 border-gray-200">
            <a href="#bao-gia-section" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded text-brand font-bold">Yêu Cầu Báo Giá Nhanh</a>
            <a href="#tin-tuc-section" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Tin Tức & Gợi Ý Quà Tặng</a>
            <a href="#lien-he-section" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded hover:bg-gray-100">Bản Đồ & Liên Hệ</a>
        </div>
        <div class="p-3 bg-gray-50 border-t border-gray-200 text-xs text-gray-600">
            <p class="font-bold text-brand mb-1">SHOP QUÀ TẶNG ĐẸP ĐÀ NẴNG</p>
            <p><i class="fa-solid fa-location-dot mr-1 text-brand"></i> 154 Nguyễn Phước Nguyên, Đà Nẵng</p>
            <p class="mt-1"><i class="fa-solid fa-phone mr-1 text-brand"></i> 0932.046.022</p>
        </div>
    </aside>

    <!-- ==========================================
         SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         (Thiết kế riêng Banner Máy Tính và Banner Điện Thoại để chữ gọn nhỏ, nằm trọn bên trong, không tràn viền)
    =========================================== -->
    <section class="py-3 sm:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-sm border border-gray-200 bg-white">
                
                <!-- Khung chứa 2 Slide có cùng chiều cao cố định theo từng thiết bị -->
                <div id="heroSlider" class="relative w-full h-[230px] sm:h-[270px] md:h-[370px] lg:h-[400px] overflow-hidden">
                    
                    <!-- ================= SLIDE 1 ================= -->
                    <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        
                        <!-- BANNER 1: PHIÊN BẢN MÁY TÍNH (Desktop >= 768px) -->
                        <div class="hidden md:grid grid-cols-12 w-full h-full bg-gradient-to-r from-[#8B1E20] via-[#9E2A2B] to-[#5B1314] text-white items-center px-10 lg:px-16">
                            <div class="col-span-7 pr-6 space-y-2.5">
                                <div class="inline-block px-3 py-1 rounded-full bg-brand-gold/20 border border-brand-gold text-brand-gold text-xs font-semibold tracking-wide">
                                    QUATANGDANANG.COM • 154 NGUYỄN PHƯỚC NGUYÊN
                                </div>
                                <h1 class="font-heading font-extrabold text-xl lg:text-2xl xl:text-3xl leading-snug text-white">
                                    SHOP QUÀ TẶNG ĐẸP TẠI ĐÀ NẴNG & NƯỚC HOA CHARME CHÍNH HÃNG
                                </h1>
                                <p class="text-xs lg:text-sm text-gray-100 leading-relaxed max-w-xl">
                                    Chuyên Set quà tặng Sinh Nhật, Valentine, Noel, 8/3, 20/10, 20/11, Quà tặng Doanh nghiệp in logo & Nước hoa Charme chính hãng Huỳnh Lài.
                                </p>
                                <div class="pt-1 flex items-center gap-3">
                                    <a href="#san-pham-section" class="px-4 py-2 bg-brand-gold text-gray-900 font-bold text-xs rounded-lg hover:bg-yellow-500 transition shadow">
                                        Xem Sản Phẩm Ngay
                                    </a>
                                    <a href="#bao-gia-section" class="px-4 py-2 bg-white/15 border border-white/40 text-white font-semibold text-xs rounded-lg hover:bg-white/25 transition">
                                        Đặt Quà Theo Yêu Cầu
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 flex items-center justify-center gap-3 h-full py-5">
                                <div class="w-40 lg:w-44 h-48 lg:h-56 rounded-xl overflow-hidden border-2 border-brand-gold/70 shadow-lg bg-white p-1 rotate-[-2deg]">
                                    <img src="https://lh3.googleusercontent.com/d/1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq" onerror="this.src='https://drive.google.com/thumbnail?id=1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq&sz=w800'" alt="Set Quà Tặng Nước Hoa Charme" class="w-full h-full object-cover rounded-lg">
                                </div>
                                <div class="w-40 lg:w-44 h-48 lg:h-56 rounded-xl overflow-hidden border-2 border-brand-gold/70 shadow-lg bg-white p-1 rotate-[3deg]">
                                    <img src="https://lh3.googleusercontent.com/d/1EW3ma5CeH0OIzPID31RN3Iq7VYxd2WLg" onerror="this.src='https://drive.google.com/thumbnail?id=1EW3ma5CeH0OIzPID31RN3Iq7VYxd2WLg&sz=w800'" alt="Quà Tặng Đẹp Đà Nẵng" class="w-full h-full object-cover rounded-lg">
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 1: PHIÊN BẢN ĐIỆN THOẠI RIÊNG BIỆT (Mobile < 768px - Chữ nhỏ gọn nằm trọn trong ảnh, không tràn viền) -->
                        <div class="flex md:hidden w-full h-full bg-gradient-to-br from-[#8B1E20] to-[#561112] text-white items-center justify-between px-4 py-3">
                            <div class="w-[62%] pr-2 space-y-1.5">
                                <span class="inline-block px-2 py-0.5 rounded bg-brand-gold text-gray-900 text-[10px] font-bold">
                                    QUATANGDANANG.COM
                                </span>
                                <h2 class="font-heading font-bold text-[13px] sm:text-[15px] leading-snug text-white">
                                    SHOP QUÀ TẶNG ĐẸP & NƯỚC HOA CHARME ĐÀ NẴNG
                                </h2>
                                <p class="text-[11px] text-gray-200 leading-tight">
                                    Quà Sinh nhật, 8/3, 20/10, 20/11, Valentine, Noel. Đ/c: 154 Nguyễn Phước Nguyên.
                                </p>
                                <div class="pt-1">
                                    <a href="#san-pham-section" class="inline-block px-3 py-1 bg-brand-gold text-gray-900 font-bold text-[11px] rounded shadow">
                                        Chọn Quà Ngay
                                    </a>
                                </div>
                            </div>
                            <div class="w-[36%] h-[86%] rounded-lg overflow-hidden border border-brand-gold bg-white p-0.5 shrink-0">
                                <img src="https://lh3.googleusercontent.com/d/1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq" onerror="this.src='https://drive.google.com/thumbnail?id=1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq&sz=w600'" alt="Set Quà Tặng Đà Nẵng" class="w-full h-full object-cover rounded">
                            </div>
                        </div>

                    </div>

                    <!-- ================= SLIDE 2 ================= -->
                    <div class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        
                        <!-- BANNER 2: PHIÊN BẢN MÁY TÍNH (Desktop >= 768px) -->
                        <div class="hidden md:grid grid-cols-12 w-full h-full bg-gradient-to-r from-[#2C1810] via-[#6E2123] to-[#9E2A2B] text-white items-center px-10 lg:px-16">
                            <div class="col-span-7 pr-6 space-y-2.5">
                                <div class="inline-block px-3 py-1 rounded-full bg-white/15 border border-brand-gold text-brand-gold text-xs font-semibold">
                                    GIẢI PHÁP QUÀ TẶNG TRỌN GÓI • HOTLINE: 0932.046.022
                                </div>
                                <h2 class="font-heading font-extrabold text-xl lg:text-2xl xl:text-3xl leading-snug text-white">
                                    SET QUÀ TẶNG DOANH NGHIỆP & DỊP LỄ THIẾT KẾ THEO YÊU CẦU
                                </h2>
                                <p class="text-xs lg:text-sm text-gray-100 leading-relaxed max-w-xl">
                                    Combo Nước Hoa Charme, Bình giữ nhiệt, Ly sứ, Sổ tay, Hoa sáp thơm & Hộp quà sang trọng. Chiết khấu cao, giao hàng tận nơi tại Đà Nẵng & Toàn quốc.
                                </p>
                                <div class="pt-1 flex items-center gap-3">
                                    <a href="#bao-gia-section" class="px-4 py-2 bg-brand-gold text-gray-900 font-bold text-xs rounded-lg hover:bg-yellow-500 transition shadow">
                                        Nhận Báo Giá Sỉ & Lẻ
                                    </a>
                                    <a href="#lien-he-section" class="px-4 py-2 bg-white/15 border border-white/40 text-white font-semibold text-xs rounded-lg hover:bg-white/25 transition">
                                        Xem Địa Chỉ Cửa Hàng
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 flex items-center justify-center gap-3 h-full py-5">
                                <div class="w-40 lg:w-44 h-48 lg:h-56 rounded-xl overflow-hidden border-2 border-brand-gold/70 shadow-lg bg-white p-1 rotate-[2deg]">
                                    <img src="https://lh3.googleusercontent.com/d/14zj_MpiGJw6qROZslH0wpL8T3BdhOAb8" onerror="this.src='https://drive.google.com/thumbnail?id=14zj_MpiGJw6qROZslH0wpL8T3BdhOAb8&sz=w800'" alt="Combo Quà Tặng Cao Cấp" class="w-full h-full object-cover rounded-lg">
                                </div>
                                <div class="w-40 lg:w-44 h-48 lg:h-56 rounded-xl overflow-hidden border-2 border-brand-gold/70 shadow-lg bg-white p-1 rotate-[-3deg]">
                                    <img src="https://lh3.googleusercontent.com/d/1ScfiWwu9ZR8HdzRiAiR4gsY1HL6oFdGH" onerror="this.src='https://drive.google.com/thumbnail?id=1ScfiWwu9ZR8HdzRiAiR4gsY1HL6oFdGH&sz=w800'" alt="Nước Hoa Charme Chính Hãng" class="w-full h-full object-cover rounded-lg">
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2: PHIÊN BẢN ĐIỆN THOẠI RIÊNG BIỆT (Mobile < 768px - Chữ nhỏ gọn nằm trọn trong ảnh) -->
                        <div class="flex md:hidden w-full h-full bg-gradient-to-br from-[#3A191A] to-[#8B1E20] text-white items-center justify-between px-4 py-3">
                            <div class="w-[62%] pr-2 space-y-1.5">
                                <span class="inline-block px-2 py-0.5 rounded bg-brand-gold text-gray-900 text-[10px] font-bold">
                                    HOTLINE: 0932.046.022
                                </span>
                                <h2 class="font-heading font-bold text-[13px] sm:text-[15px] leading-snug text-white">
                                    SET QUÀ TẶNG & COMBO NƯỚC HOA CHARME GIÁ TỐT
                                </h2>
                                <p class="text-[11px] text-gray-200 leading-tight">
                                    Thiết kế hộp quà theo ngân sách, in logo doanh nghiệp, miễn phí gói quà đẹp.
                                </p>
                                <div class="pt-1">
                                    <a href="#bao-gia-section" class="inline-block px-3 py-1 bg-brand-gold text-gray-900 font-bold text-[11px] rounded shadow">
                                        Nhận Báo Giá
                                    </a>
                                </div>
                            </div>
                            <div class="w-[36%] h-[86%] rounded-lg overflow-hidden border border-brand-gold bg-white p-0.5 shrink-0">
                                <img src="https://lh3.googleusercontent.com/d/14zj_MpiGJw6qROZslH0wpL8T3BdhOAb8" onerror="this.src='https://drive.google.com/thumbnail?id=14zj_MpiGJw6qROZslH0wpL8T3BdhOAb8&sz=w600'" alt="Combo Quà Tặng" class="w-full h-full object-cover rounded">
                            </div>
                        </div>

                    </div>

                </div>

                <!-- Nút điều hướng Slider -->
                <button onclick="changeSlide(-1)" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 text-white hover:bg-brand flex items-center justify-center transition" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 text-white hover:bg-brand flex items-center justify-center transition" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Dấu chấm chỉ mục Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" id="dot0" class="w-5 h-2 rounded-full bg-brand-gold transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot1" class="w-2 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu hiển thị đẹp trên Máy Tính & Điện Thoại, chữ nhỏ gọn không gãy dòng)
    =========================================== -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-gray-200 shadow-sm">
                <div class="flex items-center justify-between mb-3">
                    <h2 class="font-heading font-bold text-sm sm:text-base text-brand uppercase tracking-wide flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-brand-gold"></i>
                        Danh Mục Quà Tặng & Nước Hoa
                    </h2>
                    <span class="text-[11px] text-gray-500">Chọn danh mục để lọc nhanh</span>
                </div>

                <!-- Lưới danh mục: 2 hàng gọn đẹp trên điện thoại và máy tính, tên danh mục chữ nhỏ gọn không tràn -->
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 lg:grid-cols-10 gap-2">
                    <button onclick="selectCategory('Nước Hoa Charme', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-spray-can-sparkles text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Nước Hoa Charme</span>
                    </button>

                    <button onclick="selectCategory('Set Quà Tặng', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-gifts text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Set Quà Tặng</span>
                    </button>

                    <button onclick="selectCategory('Quà Sinh Nhật', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-cake-candles text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Quà Sinh Nhật</span>
                    </button>

                    <button onclick="selectCategory('Quà 8/3 & 20/10', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-spa text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Quà 8/3 & 20/10</span>
                    </button>

                    <button onclick="selectCategory('Quà Tặng 20/11', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-chalkboard-user text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Quà Tặng 20/11</span>
                    </button>

                    <button onclick="selectCategory('Valentine & Noel', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-heart text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Valentine & Noel</span>
                    </button>

                    <button onclick="selectCategory('Bình Giữ Nhiệt In Logo', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-bottle-water text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Bình Giữ Nhiệt</span>
                    </button>

                    <button onclick="selectCategory('Ly Tách & Sổ Tay', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-mug-hot text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Ly Tách & Sổ Tay</span>
                    </button>

                    <button onclick="selectCategory('Tiện Ích Văn Phòng', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-briefcase text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Tiện Ích Văn Phòng</span>
                    </button>

                    <button onclick="selectCategory('all', event)" class="group p-2 rounded-lg border border-gray-100 bg-brand-light/40 hover:bg-brand hover:text-white transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-white text-brand flex items-center justify-center shadow-sm mb-1.5 group-hover:scale-105 transition">
                            <i class="fa-solid fa-table-cells-large text-sm"></i>
                        </div>
                        <span class="text-[11px] font-semibold whitespace-nowrap">Xem Tất Cả</span>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH SÁCH SẢN PHẨM THỰC TẾ TRANG CHỦ
         - Điện thoại: 2 cột (grid-cols-2)
         - Máy tính: 5 cột (lg:grid-cols-5) chuẩn Flatsome 1500px
         - Góc trên bên trái: % giảm giá chuẩn Flatsome
         - Không có nhãn dán rườm rà khác
         - Tên sản phẩm hiển thị trọn vẹn không bị cắt chữ (...)
    =========================================== -->
    <section id="san-pham-section" class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 id="currentCategoryHeading" class="section-title-main text-base sm:text-lg md:text-xl uppercase">
                    SẢN PHẨM QUÀ TẶNG & NƯỚC HOA CHARME NỔI BẬT
                </h2>
                <div class="flex items-center gap-2 text-xs">
                    <span class="text-gray-500">Sắp xếp:</span>
                    <select id="sortSelect" onchange="sortProducts(this.value)" class="border border-gray-200 rounded px-2.5 py-1 bg-white text-xs focus:outline-none focus:border-brand">
                        <option value="default">Mặc định</option>
                        <option value="price-asc">Giá: Thấp đến Cao</option>
                        <option value="price-desc">Giá: Cao đến Thấp</option>
                    </select>
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên điện thoại, 4 cột tablet, 5 cột desktop 1500px -->
            <div id="productGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Được render tự động từ danh sách 15 ảnh sản phẩm thực tế Google Drive -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION GIỚI THIỆU CỬA HÀNG THỰC TẾ TẠI 154 NGUYỄN PHƯỚC NGUYÊN, ĐÀ NẴNG
         (Sử dụng ảnh cửa hàng thực tế: 1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j)
    =========================================== -->
    <section class="py-6">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border border-gray-200 p-4 sm:p-6 shadow-sm">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <div class="lg:col-span-5">
                        <div class="rounded-xl overflow-hidden border-2 border-brand-gold/40 shadow-md bg-gray-100 aspect-[4/3]">
                            <img src="https://lh3.googleusercontent.com/d/1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j"
                                 onerror="this.src='https://drive.google.com/thumbnail?id=1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j&sz=w1000'"
                                 alt="Cửa hàng Quà Tặng Đẹp & Nước Hoa Charme Chính Hãng 154 Nguyễn Phước Nguyên Đà Nẵng"
                                 class="w-full h-full object-cover">
                        </div>
                    </div>
                    <div class="lg:col-span-7 space-y-3">
                        <span class="text-xs font-bold uppercase tracking-wider text-brand-gold">Về Chúng Tôi • quatangdanang.com</span>
                        <h2 class="font-heading font-bold text-lg sm:text-xl md:text-2xl text-brand">
                            SHOP QUÀ TẶNG ĐẸP TẠI ĐÀ NẴNG - NƯỚC HOA CHARME CHÍNH HÃNG HUỲNH LÀI
                        </h2>
                        <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                            Tọa lạc tại <strong>154 Nguyễn Phước Nguyên, Phường An Khê, TP. Đà Nẵng</strong>, <strong>quatangdanang.com</strong> là địa chỉ uy tín chuyên cung cấp các dòng <strong>Nước hoa Charme chính hãng</strong> và các <strong>Set quà tặng thiết kế tinh tế</strong> dành cho mọi dịp lễ đặc biệt: Quà tặng Sinh nhật, Valentine 14/2, Quốc tế Phụ nữ 8/3, Phụ nữ Việt Nam 20/10, Ngày Nhà giáo Việt Nam 20/11, Giáng sinh Noel và Quà Tết Doanh nghiệp.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs">
                            <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-brand-light/60">
                                <i class="fa-solid fa-certificate text-brand mt-0.5"></i>
                                <div>
                                    <strong class="block text-gray-800">Cam Kết Chính Hãng 100%</strong>
                                    <span class="text-gray-600">Nước hoa Charme đầy đủ tem chống giả, bảo hành hương thơm chuẩn hãng.</span>
                                </div>
                            </div>
                            <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-brand-light/60">
                                <i class="fa-solid fa-box-open text-brand mt-0.5"></i>
                                <div>
                                    <strong class="block text-gray-800">Đóng Gói Sang Trọng & Tinh Tế</strong>
                                    <span class="text-gray-600">Tặng kèm túi, hộp quà, thiệp viết tay và in ấn logo doanh nghiệp theo yêu cầu.</span>
                                </div>
                            </div>
                        </div>
                        <div class="pt-2 flex flex-wrap items-center gap-3 text-xs font-semibold">
                            <span class="px-3 py-1.5 rounded bg-gray-100 text-gray-800">
                                <i class="fa-solid fa-location-dot text-brand mr-1"></i> 154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng
                            </span>
                            <span class="px-3 py-1.5 rounded bg-gray-100 text-gray-800">
                                <i class="fa-solid fa-phone text-brand mr-1"></i> Hotline/Zalo: 0932.046.022
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
    =========================================== -->
    <section id="bao-gia-section" class="py-6">
        <div class="flatsome-container">
            <div class="bg-gradient-to-r from-brand to-brand-dark rounded-xl p-5 sm:p-8 text-white shadow-sm">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <div class="lg:col-span-5 space-y-3">
                        <span class="inline-block px-3 py-1 rounded bg-brand-gold text-gray-900 font-bold text-xs">
                            HỖ TRỢ TƯ VẤN NHANH 24/7
                        </span>
                        <h2 class="font-heading font-bold text-lg sm:text-xl md:text-2xl leading-snug">
                            ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ QUÀ TẶNG
                        </h2>
                        <p class="text-xs sm:text-sm text-gray-100 leading-relaxed">
                            Bạn cần đặt Set quà tặng cá nhân, quà tặng người thương, thầy cô hay báo giá sỉ Quà tặng Doanh nghiệp in logo (Bình giữ nhiệt, Ly sứ, Sổ tay, Nước hoa Charme)? Hãy để lại thông tin, shop sẽ liên hệ qua Zalo/SĐT <strong>0932.046.022</strong> ngay!
                        </p>
                        <ul class="space-y-1.5 text-xs text-gray-100">
                            <li><i class="fa-solid fa-check text-brand-gold mr-2"></i>Thiết kế set quà theo đúng ngân sách yêu cầu (từ 150k - 2.000k+)</li>
                            <li><i class="fa-solid fa-check text-brand-gold mr-2"></i>Miễn phí thiệp chúc mừng & gói quà thẩm mỹ</li>
                            <li><i class="fa-solid fa-check text-brand-gold mr-2"></i>Giao hàng hỏa tốc nội thành Đà Nẵng trong 1 - 2 giờ</li>
                        </ul>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-gray-800 rounded-xl p-4 sm:p-6 shadow-md space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Họ và tên của bạn *</label>
                                    <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="qPhone" required placeholder="Nhập số điện thoại..." class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-brand">
                                </div>
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Danh mục quà quan tâm</label>
                                    <select id="qCategory" class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-brand bg-white">
                                        <option value="Nước Hoa Charme Chính Hãng">Nước Hoa Charme Chính Hãng</option>
                                        <option value="Set Quà Sinh Nhật / Valentine / Noel">Set Quà Sinh Nhật / Valentine / Noel</option>
                                        <option value="Quà Tặng 8/3 & 20/10 Cho Nữ">Quà Tặng 8/3 & 20/10 Cho Nữ</option>
                                        <option value="Quà Tặng Thầy Cô 20/11">Quà Tặng Thầy Cô 20/11</option>
                                        <option value="Quà Tặng Doanh Nghiệp In Logo">Quà Tặng Doanh Nghiệp In Logo (Bình giữ nhiệt, Ly, Sổ)</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-gray-700 mb-1">Số lượng dự kiến & Ngân sách</label>
                                    <input type="text" id="qBudget" placeholder="VD: 1 set 400k hoặc 50 phần quà công ty..." class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-brand">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-gray-700 mb-1">Ghi chú lời chúc hoặc yêu cầu chi tiết</label>
                                <textarea id="qNote" rows="2" placeholder="Nhập yêu cầu tư vấn mùi hương nước hoa Charme, màu hộp quà, in logo..." class="w-full px-3 py-2 text-xs border border-gray-300 rounded-lg focus:outline-none focus:border-brand"></textarea>
                            </div>
                            <button type="submit" class="w-full py-2.5 bg-brand hover:bg-brand-dark text-white font-bold text-xs sm:text-sm rounded-lg transition shadow">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                            </button>
                            <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-green-50 border border-green-200 text-green-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
    =========================================== -->
    <section id="tin-tuc-section" class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl uppercase">
                    TIN TỨC & CẨM NANG CHỌN QUÀ TẶNG ĐÀ NẴNG
                </h2>
                <span class="text-xs text-gray-500">Kinh nghiệm chọn quà & Nước hoa Charme</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1XNHCfv398xj1rqLM5_QqhcWa6cnAmxWw" onerror="this.src='https://drive.google.com/thumbnail?id=1XNHCfv398xj1rqLM5_QqhcWa6cnAmxWw&sz=w600'" alt="Top Nước Hoa Charme Nữ Được Yêu Thích Nhất" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Nước Hoa Charme Đà Nẵng</span>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-800 mt-1 leading-snug">
                                Top 5 Mùi Hương Nước Hoa Charme Chính Hãng Làm Quà Tặng Sinh Nhật, 8/3 & 20/10 Tinh Tế Nhất
                            </h3>
                            <p class="text-xs text-gray-500 mt-1.5 leading-relaxed">
                                Bí quyết chọn mùi hương Charme Good Girl, Charme So Sexy, Charme Adore lưu hương lâu từ 8-12 giờ làm quà tặng phái đẹp.
                            </p>
                        </div>
                        <a href="#bao-gia-section" class="mt-3 inline-flex items-center text-xs font-semibold text-brand hover:underline">
                            Tư vấn mùi hương <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1DK58DGpgmS7kXJPHzgTA1Zo7pkGAvHHp" onerror="this.src='https://drive.google.com/thumbnail?id=1DK58DGpgmS7kXJPHzgTA1Zo7pkGAvHHp&sz=w600'" alt="Set Quà Tặng Thầy Cô 20/11 Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Quà Tặng Dịp Lễ</span>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-800 mt-1 leading-snug">
                                Gợi Ý Các Set Quà Tặng Thầy Cô Ngày Nhà Giáo Việt Nam 20/11 Ý Nghĩa & Trang Trọng Tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-gray-500 mt-1.5 leading-relaxed">
                                Kết hợp sổ tay bìa da, bút ký, bình giữ nhiệt và nước hoa Charme cao cấp gửi trọn tấm lòng tri ân đến thầy cô giáo.
                            </p>
                        </div>
                        <a href="#san-pham-section" onclick="selectCategory('Quà Tặng 20/11', event)" class="mt-3 inline-flex items-center text-xs font-semibold text-brand hover:underline">
                            Xem mẫu quà 20/11 <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/1tRTz5fM1BLo_Dy6-6pLONOkb9ahx6QR3" onerror="this.src='https://drive.google.com/thumbnail?id=1tRTz5fM1BLo_Dy6-6pLONOkb9ahx6QR3&sz=w600'" alt="Quà Tặng Valentine và Noel Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Quà Tặng Tình Yêu</span>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-800 mt-1 leading-snug">
                                Xu Hướng Hộp Quà Hoa Sáp Kèm Nước Hoa & Gấu Bông Cho Dịp Valentine 14/2 Và Giáng Sinh Noel
                            </h3>
                            <p class="text-xs text-gray-500 mt-1.5 leading-relaxed">
                                Thiết kế hộp quà sang trọng, ngọt ngào kèm thiệp viết tay giúp bạn ghi điểm tuyệt đối trong mắt người thương.
                            </p>
                        </div>
                        <a href="#san-pham-section" onclick="selectCategory('Valentine & Noel', event)" class="mt-3 inline-flex items-center text-xs font-semibold text-brand hover:underline">
                            Xem hộp quà Valentine <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="https://lh3.googleusercontent.com/d/19_AjfAL5PWEAy1GXn7g2mwc2Del49nbI" onerror="this.src='https://drive.google.com/thumbnail?id=19_AjfAL5PWEAy1GXn7g2mwc2Del49nbI&sz=w600'" alt="Giải Pháp Quà Tặng Doanh Nghiệp Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] text-brand font-semibold">Quà Tặng Doanh Nghiệp</span>
                            <h3 class="font-bold text-xs sm:text-sm text-gray-800 mt-1 leading-snug">
                                Giải Pháp Quà Tặng Doanh Nghiệp Trọn Gói: Bình Giữ Nhiệt, Ly Sứ, Sổ Tay & Set Quà In Logo Tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-gray-500 mt-1.5 leading-relaxed">
                                Tư vấn thiết kế bộ Giftset tri ân khách hàng, nhân viên và đối tác đồng bộ nhận diện thương hiệu với chi phí tối ưu.
                            </p>
                        </div>
                        <a href="#bao-gia-section" class="mt-3 inline-flex items-center text-xs font-semibold text-brand hover:underline">
                            Nhận báo giá doanh nghiệp <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC ĐỒNG HÀNH
    =========================================== -->
    <section class="py-5">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border border-gray-200 p-4 sm:p-5 shadow-sm">
                <div class="section-title-container mb-4">
                    <h2 class="section-title-main text-sm sm:text-base md:text-lg uppercase">
                        ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
                    </h2>
                    <span class="text-xs text-gray-500">Hợp tác cung cấp quà tặng & phân phối chính hãng</span>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-3 items-center">
                    <div class="h-16 rounded-lg border border-gray-200 bg-gray-50 flex flex-col items-center justify-center p-2 text-center">
                        <span class="font-heading font-extrabold text-sm text-brand">CHARME PERFUME</span>
                        <span class="text-[10px] text-gray-500">Đại Lý Chính Hãng</span>
                    </div>
                    <div class="h-16 rounded-lg border border-gray-200 bg-gray-50 flex flex-col items-center justify-center p-2 text-center">
                        <span class="font-heading font-extrabold text-sm text-gray-700">ANSGIFT STYLE</span>
                        <span class="text-[10px] text-gray-500">Giftset Doanh Nghiệp</span>
                    </div>
                    <div class="h-16 rounded-lg border border-gray-200 bg-gray-50 flex flex-col items-center justify-center p-2 text-center">
                        <span class="font-heading font-extrabold text-sm text-emerald-700">VIETCOMBANK</span>
                        <span class="text-[10px] text-gray-500">Đối Tác Quà Tặng</span>
                    </div>
                    <div class="h-16 rounded-lg border border-gray-200 bg-gray-50 flex flex-col items-center justify-center p-2 text-center">
                        <span class="font-heading font-extrabold text-sm text-amber-600">SUN GROUP</span>
                        <span class="text-[10px] text-gray-500">Khách Hàng Sự Kiện</span>
                    </div>
                    <div class="h-16 rounded-lg border border-gray-200 bg-gray-50 flex flex-col items-center justify-center p-2 text-center">
                        <span class="font-heading font-extrabold text-sm text-blue-700">FPT DA NANG</span>
                        <span class="text-[10px] text-gray-500">Đối Tác Quà Dịp Lễ</span>
                    </div>
                    <div class="h-16 rounded-lg border border-gray-200 bg-gray-50 flex flex-col items-center justify-center p-2 text-center">
                        <span class="font-heading font-extrabold text-sm text-red-600">VIETTEL POST</span>
                        <span class="text-[10px] text-gray-500">Đối Tác Giao Vận</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐƯA FANPAGE FACEBOOK & GOOGLE MAP RA NGOÀI TRANG CHỦ
         (Địa chỉ: 154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng | Fanpage: nuochoacharmechinhhanghuynhlai)
    =========================================== -->
    <section id="lien-he-section" class="py-6">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl uppercase">
                    BẢN ĐỒ GOOGLE MAPS & FANPAGE CHÍNH THỨC TRÊN TRANG CHỦ
                </h2>
                <span class="text-xs text-gray-500">154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng • ĐT: 0932.046.022</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- CỘT GOOGLE MAP TRỰC TIẾP TRÊN TRANG CHỦ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-gray-200 p-4 shadow-sm flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                        <div>
                            <h3 class="font-heading font-bold text-sm sm:text-base text-brand flex items-center gap-1.5">
                                <i class="fa-solid fa-map-location-dot"></i>
                                Địa Chỉ Cửa Hàng Trên Google Maps
                            </h3>
                            <p class="text-xs text-gray-600 mt-0.5">154 Nguyễn Phước Nguyên, Phường An Khê, Quận Thanh Khê, TP. Đà Nẵng</p>
                        </div>
                        <a href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJiS_VnwUZQjERFUci8I-eGVs" target="_blank" rel="noopener" class="px-3 py-1.5 rounded-lg bg-brand text-white text-xs font-semibold hover:bg-brand-dark transition shrink-0">
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i> Chỉ Đường Google Maps
                        </a>
                    </div>
                    <div class="w-full h-[290px] sm:h-[330px] rounded-lg overflow-hidden border border-gray-200 bg-gray-100">
                        <iframe
                            title="Google Map 154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng"
                            src="https://maps.google.com/maps?q=154%20Nguy%E1%BB%85n%20Ph%C6%B0%E1%BB%9Bc%20Nguy%C3%AAn,%20An%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- CỘT FANPAGE FACEBOOK TRỰC TIẾP TRÊN TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-gray-200 p-4 shadow-sm flex flex-col justify-between">
                    <div class="mb-3">
                        <h3 class="font-heading font-bold text-sm sm:text-base text-[#1877F2] flex items-center gap-1.5">
                            <i class="fa-brands fa-facebook"></i>
                            Fanpage Facebook Chính Thức
                        </h3>
                        <p class="text-xs text-gray-600 mt-0.5">Nước Hoa Charme Chính Hãng & Shop Quà Tặng Đẹp Đà Nẵng - Huỳnh Lài</p>
                    </div>

                    <!-- Khung Fanpage trực quan + Plugin Facebook -->
                    <div class="border border-gray-200 rounded-xl overflow-hidden bg-gray-50 flex-1 flex flex-col justify-between">
                        <div class="relative h-36 bg-gradient-to-r from-brand to-brand-dark overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j" onerror="this.src='https://drive.google.com/thumbnail?id=1He2rmqV11n3DVoL77lRp_QYOT2h6VW2j&sz=w800'" alt="Fanpage Cover" class="w-full h-full object-cover opacity-65">
                            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent flex items-end p-3.5">
                                <div class="flex items-center gap-3">
                                    <img src="https://lh3.googleusercontent.com/d/1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq" onerror="this.src='https://drive.google.com/thumbnail?id=1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq&sz=w200'" alt="Avatar Fanpage" class="w-14 h-14 rounded-full border-2 border-white object-cover bg-white shrink-0">
                                    <div class="text-white">
                                        <a href="https://www.facebook.com/nuochoacharmechinhhanghuynhlai" target="_blank" rel="noopener" class="font-bold text-sm hover:underline line-clamp-1">
                                            Nước Hoa Charme Chính Hãng - Huỳnh Lài
                                        </a>
                                        <p class="text-[11px] text-gray-200">Shop Quà Tặng Đẹp Đà Nẵng • Theo dõi trang để cập nhật mẫu mới</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="p-3.5 space-y-2.5 text-xs text-gray-700">
                            <p class="leading-relaxed">
                                <i class="fa-solid fa-circle-check text-[#1877F2] mr-1"></i> Cập nhật hàng ngày các mẫu <strong>Set quà tặng Sinh nhật, Valentine, 8/3, 20/10, 20/11, Noel</strong> và bảng mùi <strong>Nước hoa Charme chính hãng</strong> mới nhất.
                            </p>
                            <div class="grid grid-cols-3 gap-2 pt-1">
                                <img src="https://lh3.googleusercontent.com/d/1YvPoV2arQoUzBAgwXuwFgeGJWFuFXR4K" onerror="this.src='https://drive.google.com/thumbnail?id=1YvPoV2arQoUzBAgwXuwFgeGJWFuFXR4K&sz=w300'" alt="Ảnh Fanpage 1" class="w-full h-16 object-cover rounded border border-gray-200">
                                <img src="https://lh3.googleusercontent.com/d/1m0OXOUdAWdkFRopK9R_npocEdhF1HjrZ" onerror="this.src='https://drive.google.com/thumbnail?id=1m0OXOUdAWdkFRopK9R_npocEdhF1HjrZ&sz=w300'" alt="Ảnh Fanpage 2" class="w-full h-16 object-cover rounded border border-gray-200">
                                <img src="https://lh3.googleusercontent.com/d/1AXLIbHVONNqqXouTWsmlrNGCz9MzlW0T" onerror="this.src='https://drive.google.com/thumbnail?id=1AXLIbHVONNqqXouTWsmlrNGCz9MzlW0T&sz=w300'" alt="Ảnh Fanpage 3" class="w-full h-16 object-cover rounded border border-gray-200">
                            </div>
                        </div>

                        <div class="p-3 bg-white border-t border-gray-200 flex flex-wrap items-center justify-between gap-2">
                            <a href="https://www.facebook.com/nuochoacharmechinhhanghuynhlai" target="_blank" rel="noopener" class="flex-1 py-2 px-3 bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs rounded-lg text-center transition">
                                <i class="fa-brands fa-facebook-f mr-1"></i> Ghé Thăm Fanpage
                            </a>
                            <a href="https://www.facebook.com/nuochoacharmechinhhanghuynhlai" target="_blank" rel="noopener" class="flex-1 py-2 px-3 bg-brand-light text-brand border border-brand/20 hover:bg-brand hover:text-white font-bold text-xs rounded-lg text-center transition">
                                <i class="fa-brands fa-facebook-messenger mr-1"></i> Nhắn Tin Tư Vấn
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN ANSGIFT & FLATSOME
    =========================================== -->
    <footer class="bg-[#221617] text-gray-300 pt-10 pb-6 border-t-4 border-brand-gold mt-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                
                <!-- Cột 1: Thông tin cửa hàng -->
                <div class="lg:col-span-4 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 rounded-lg bg-brand flex items-center justify-center border border-brand-gold">
                            <i class="fa-solid fa-gift text-brand-gold text-base"></i>
                        </div>
                        <span class="font-heading font-extrabold text-base text-white">
                            QUATANGDANANG<span class="text-brand-gold">.COM</span>
                        </span>
                    </div>
                    <p class="text-xs text-gray-300 leading-relaxed">
                        Shop Quà Tặng Đẹp Tại Đà Nẵng - Chuyên quà tặng sinh nhật, Valentine, Noel, 20/10, 8/3, 20/11, Set quà tặng doanh nghiệp in logo & Đại lý Nước hoa Charme Chính hãng Huỳnh Lài.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><i class="fa-solid fa-location-dot text-brand-gold mr-2"></i><strong>Địa chỉ:</strong> 154 Nguyễn Phước Nguyên, Phường An Khê, TP. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-brand-gold mr-2"></i><strong>Hotline / Zalo:</strong> <a href="tel:0932046022" class="text-white font-bold hover:text-brand-gold">0932.046.022</a></li>
                        <li><i class="fa-solid fa-globe text-brand-gold mr-2"></i><strong>Website:</strong> quatangdanang.com</li>
                        <li><i class="fa-brands fa-facebook text-brand-gold mr-2"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/nuochoacharmechinhhanghuynhlai" target="_blank" rel="noopener" class="underline hover:text-white">fb.com/nuochoacharmechinhhanghuynhlai</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm (Theo mẫu ANSGIFT + Shop) -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="font-heading font-bold text-xs uppercase tracking-wider text-brand-gold">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#san-pham-section" onclick="selectCategory('Nước Hoa Charme', event)" class="hover:text-white transition">Nước Hoa Charme Chính Hãng</a></li>
                        <li><a href="#san-pham-section" onclick="selectCategory('Set Quà Tặng', event)" class="hover:text-white transition">Set Quà Tặng Cao Cấp</a></li>
                        <li><a href="#san-pham-section" onclick="selectCategory('Quà Sinh Nhật', event)" class="hover:text-white transition">Quà Tặng Sinh Nhật</a></li>
                        <li><a href="#san-pham-section" onclick="selectCategory('Quà 8/3 & 20/10', event)" class="hover:text-white transition">Quà Tặng Ngày Phụ Nữ 8/3 & 20/10</a></li>
                        <li><a href="#san-pham-section" onclick="selectCategory('Quà Tặng 20/11', event)" class="hover:text-white transition">Quà Tặng Thầy Cô 20/11</a></li>
                        <li><a href="#san-pham-section" onclick="selectCategory('Valentine & Noel', event)" class="hover:text-white transition">Quà Tặng Valentine & Noel</a></li>
                        <li><a href="#san-pham-section" onclick="selectCategory('Bình Giữ Nhiệt In Logo', event)" class="hover:text-white transition">Bình Giữ Nhiệt & Ly Sứ In Logo</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Điều khoản & Chính sách (Giống web mẫu ANSGIFT) -->
                <div class="lg:col-span-2 space-y-2.5">
                    <h4 class="font-heading font-bold text-xs uppercase tracking-wider text-brand-gold">CHÍNH SÁCH HỖ TRỢ</h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#bao-gia-section" class="hover:text-white transition">Chính sách đặt quà sỉ</a></li>
                        <li><a href="#bao-gia-section" class="hover:text-white transition">Chính sách đổi trả & bảo hành</a></li>
                        <li><a href="#bao-gia-section" class="hover:text-white transition">Chính sách giao hàng Đà Nẵng</a></li>
                        <li><a href="#bao-gia-section" class="hover:text-white transition">Hướng dẫn thanh toán</a></li>
                        <li><a href="#bao-gia-section" class="hover:text-white transition">Bảo mật thông tin</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Đăng ký nhận ưu đãi -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="font-heading font-bold text-xs uppercase tracking-wider text-brand-gold">NHẬN ƯU ĐÃI & MẪU QUÀ MỚI</h4>
                    <p class="text-xs text-gray-400">Để lại SĐT để nhận каталог mẫu hộp quà lễ & bảng mùi nước hoa Charme ưu đãi mới nhất.</p>
                    <form onsubmit="event.preventDefault(); showToast('Cảm ơn bạn! Shop sẽ gửi ưu đãi qua Zalo 0932.046.022.'); this.reset();" class="flex gap-1.5">
                        <input type="tel" required placeholder="Số điện thoại Zalo..." class="w-full px-3 py-2 text-xs rounded bg-white/10 border border-white/20 text-white placeholder-gray-400 focus:outline-none focus:border-brand-gold">
                        <button type="submit" class="px-3.5 py-2 bg-brand-gold text-gray-900 font-bold text-xs rounded hover:bg-yellow-500 transition shrink-0">
                            Đăng Ký
                        </button>
                    </form>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-xs text-gray-400 gap-2">
                <p>© 2026 <strong>quatangdanang.com</strong> - Shop Quà Tặng Đẹp Đà Nẵng & Nước Hoa Charme Chính Hãng Huỳnh Lài.</p>
                <p>Địa chỉ: 154 Nguyễn Phước Nguyên, An Khê, Đà Nẵng • ĐT: 0932.046.022</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả Máy tính và Điện thoại, không gây tràn viền
    =========================================== -->
    <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/nuochoacharmechinhhanghuynhlai" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#1877F2] text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg hover:scale-105 transition"
           title="Chat Facebook Fanpage">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-sm shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Chat Zalo 0932.046.022 -->
        <a href="https://zalo.me/0932046022" target="_blank" rel="noopener"
           class="flex items-center gap-2 bg-[#0068FF] text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg hover:scale-105 transition"
           title="Chat Zalo 0932.046.022">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[10px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Zalo Tư Vấn</span>
        </a>

        <!-- Nút Hotline 0932.046.022 -->
        <a href="tel:0932046022"
           class="floating-pulse flex items-center gap-2 bg-brand text-white pl-3 pr-4 py-2 rounded-full shadow-lg border border-brand-gold hover:bg-brand-dark transition"
           title="Gọi Hotline 0932.046.022">
            <span class="w-7 h-7 rounded-full bg-brand-gold text-gray-900 flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <div class="flex flex-col leading-tight">
                <span class="text-[10px] text-brand-gold font-semibold">Hotline 24/7</span>
                <span class="text-xs font-extrabold whitespace-nowrap">0932.046.022</span>
            </div>
        </a>

    </div>

    <!-- ==========================================
         MODAL GIỎ HÀNG & ĐẶT HÀNG NHANH
    =========================================== -->
    <div id="cartModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-gray-200 flex flex-col max-h-[90vh]">
            <div class="p-4 bg-brand text-white flex items-center justify-between">
                <h3 class="font-heading font-bold text-sm uppercase flex items-center gap-2">
                    <i class="fa-solid fa-bag-shopping text-brand-gold"></i> Giỏ Hàng Quà Tặng Của Bạn
                </h3>
                <button onclick="closeCartModal()" class="text-white hover:text-gray-200">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div id="cartItemsContainer" class="p-4 overflow-y-auto flex-1 space-y-3 text-xs">
                <!-- Danh sách sản phẩm trong giỏ -->
            </div>
            <div class="p-4 bg-gray-50 border-t border-gray-200 space-y-3">
                <div class="flex items-center justify-between text-sm font-bold">
                    <span>Tổng cộng tạm tính:</span>
                    <span id="cartTotalPrice" class="text-brand text-base">0₫</span>
                </div>
                <div class="grid grid-cols-2 gap-2">
                    <a href="https://zalo.me/0932046022" target="_blank" rel="noopener" class="py-2.5 px-3 bg-[#0068FF] text-white text-center rounded-lg font-bold text-xs hover:bg-blue-700 transition">
                        Chốt Đơn Qua Zalo
                    </a>
                    <button onclick="closeCartModal(); document.getElementById('bao-gia-section').scrollIntoView({behavior:'smooth'});" class="py-2.5 px-3 bg-brand text-white text-center rounded-lg font-bold text-xs hover:bg-brand-dark transition">
                        Điền Thông Tin Giao Hàng
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- Thông báo Toast gọn nhẹ (Không dùng alert) -->
    <div id="toastBox" class="fixed bottom-5 left-4 z-50 hidden bg-gray-900 text-white text-xs font-medium px-4 py-2.5 rounded-lg shadow-lg border-l-4 border-brand-gold"></div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM THỰC TẾ, SLIDER, LỌC DANH MỤC
    =========================================== -->
    <script>
        /* Danh sách 15 sản phẩm lấy trực tiếp từ 15 file ảnh thực tế Google Drive của Shop Quà Tặng Đẹp Đà Nẵng & Nước Hoa Charme Huỳnh Lài kết hợp danh mục ANSGIFT */
        const productsData = [
            {
                id: 1,
                name: "Set Quà Tặng Nước Hoa Charme Chính Hãng Kèm Hoa Sáp Thơm Cao Cấp Đà Nẵng",
                category: "Nước Hoa Charme",
                price: 450000,
                oldPrice: 550000,
                discount: 18,
                driveId: "1L45nhPVXg4gW80n5TREl7ogVuSCA9VGq"
            },
            {
                id: 2,
                name: "Hộp Quà Tặng Sinh Nhật & Valentine Nước Hoa Charme Kết Hợp Hoa Hồng Sáp Sang Trọng",
                category: "Quà Sinh Nhật",
                price: 390000,
                oldPrice: 480000,
                discount: 19,
                driveId: "1EW3ma5CeH0OIzPID31RN3Iq7VYxd2WLg"
            },
            {
                id: 3,
                name: "Set Quà Tặng 8/3 & 20/10 Cao Cấp Dành Tặng Phái Đẹp - Combo Nước Hoa & Phụ Kiện",
                category: "Quà 8/3 & 20/10",
                price: 468000,
                oldPrice: 560000,
                discount: 16,
                driveId: "14zj_MpiGJw6qROZslH0wpL8T3BdhOAb8"
            },
            {
                id: 4,
                name: "Nước Hoa Nữ Charme Good Girl Chính Hãng Lưu Hương Lâu 12 Giờ - Quà Tặng Tinh Tế",
                category: "Nước Hoa Charme",
                price: 520000,
                oldPrice: 650000,
                discount: 20,
                driveId: "1ScfiWwu9ZR8HdzRiAiR4gsY1HL6oFdGH"
            },
            {
                id: 5,
                name: "Combo Hộp Quà Tặng Thầy Cô 20/11 Tri Ân Ý Nghĩa - Nước Hoa Charme & Thiệp Chúc Mừng",
                category: "Quà Tặng 20/11",
                price: 420000,
                oldPrice: 500000,
                discount: 16,
                driveId: "1XNHCfv398xj1rqLM5_QqhcWa6cnAmxWw"
            },
            {
                id: 6,
                name: "Set Quà Tặng Doanh Nghiệp & Đồng Nghiệp Nữ Pause & Bloom Gift Set Thiết Kế Đẹp",
                category: "Set Quà Tặng",
                price: 443000,
                oldPrice: 520000,
                discount: 15,
                driveId: "1DK58DGpgmS7kXJPHzgTA1Zo7pkGAvHHp"
            },
            {
                id: 7,
                name: "Hộp Quà Tặng Valentine 14/2 & Giáng Sinh Noel Ngọt Ngào Cho Người Thương Tại Đà Nẵng",
                category: "Valentine & Noel",
                price: 380000,
                oldPrice: 450000,
                discount: 16,
                driveId: "1tRTz5fM1BLo_Dy6-6pLONOkb9ahx6QR3"
            },
            {
                id: 8,
                name: "Nước Hoa Nam Charme Iris / Giò Chính Hãng Lịch Lãm - Quà Tặng Sinh Nhật Cho Nam",
                category: "Nước Hoa Charme",
                price: 490000,
                oldPrice: 590000,
                discount: 17,
                driveId: "1-seLv1RSSy_x4C1bgZXGUsXPTPEJSbHr"
            },
            {
                id: 9,
                name: "Set Quà Tặng 3 Món Bình Giữ Nhiệt, Khăn Choàng & Sổ Tay In Logo Theo Yêu Cầu",
                category: "Bình Giữ Nhiệt In Logo",
                price: 468000,
                oldPrice: 550000,
                discount: 15,
                driveId: "19_AjfAL5PWEAy1GXn7g2mwc2Del49nbI"
            },
            {
                id: 10,
                name: "Hộp Quà Tặng Phụ Nữ 20/10 & 8/3 Kèm Nước Hoa Charme Mini Và Hoa Sáp Thơm",
                category: "Quà 8/3 & 20/10",
                price: 320000,
                oldPrice: 380000,
                discount: 16,
                driveId: "1rwLeu0ANlZhjazOmoWGdc3XccgSqqdyo"
            },
            {
                id: 11,
                name: "Set Quà Tặng Cảm Ơn & Chúc Mừng Sinh Nhật Kèm Ly Sứ Cao Cấp Và Hộp Quà Nơ Lụa",
                category: "Ly Tách & Sổ Tay",
                price: 350000,
                oldPrice: 420000,
                discount: 17,
                driveId: "1YvPoV2arQoUzBAgwXuwFgeGJWFuFXR4K"
            },
            {
                id: 12,
                name: "Combo Quà Tặng Nhà Giáo 20/11 Sang Trọng - Hộp Quà Nước Hoa Charme Chính Hãng",
                category: "Quà Tặng 20/11",
                price: 480000,
                oldPrice: 580000,
                discount: 17,
                driveId: "1m0OXOUdAWdkFRopK9R_npocEdhF1HjrZ"
            },
            {
                id: 13,
                name: "Set Quà Tặng Văn Phòng Cao Cấp & Trâm Cài Áo Thanh Lịch Dành Tặng Đối Tác, Cô Giáo",
                category: "Tiện Ích Văn Phòng",
                price: 393000,
                oldPrice: 460000,
                discount: 15,
                driveId: "1AXLIbHVONNqqXouTWsmlrNGCz9MzlW0T"
            },
            {
                id: 14,
                name: "Hộp Quà Tặng Đặc Biệt Noel & Năm Mới Kết Hợp Nước Hoa Charme Queen Chính Hãng",
                category: "Valentine & Noel",
                price: 550000,
                oldPrice: 680000,
                discount: 19,
                driveId: "1B8Z_jjWL89LvA_03cZ43k1yxWgkCgIfg"
            },
            {
                id: 15,
                name: "Giftset Quà Tặng Doanh Nghiệp & Sinh Nhật Trọn Gói Thiết Kế Riêng Tại Đà Nẵng",
                category: "Set Quà Tặng",
                price: 410000,
                oldPrice: 490000,
                discount: 16,
                driveId: "1XNHCfv398xj1rqLM5_QqhcWa6cnAmxWw"
            }
        ];

        let activeCategory = 'all';
        let currentSearchQuery = '';
        let cart = [];

        function formatVND(amount) {
            return amount.toLocaleString('vi-VN') + '₫';
        }

        /* Render lưới sản phẩm chuẩn Flatsome:
           - Góc trên bên trái có vòng tròn giảm giá -XX%
           - Không gắn các nhãn dán thừa khác ở trang chủ
           - Tên sản phẩm hiển thị đầy đủ không bị cắt hay tràn
        */
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list || list.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full bg-white rounded-xl p-8 text-center border border-gray-200">
                        <p class="text-sm text-gray-600 font-medium">Không tìm thấy sản phẩm phù hợp với từ khóa. Vui lòng thử danh mục khác hoặc liên hệ Zalo <strong>0932.046.022</strong>.</p>
                    </div>
                `;
                return;
            }

            grid.innerHTML = list.map(item => {
                const primaryImg = `https://lh3.googleusercontent.com/d/${item.driveId}`;
                const fallbackImg = `https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800`;
                return `
                    <div class="product-box group">
                        <!-- Box Image với % Giảm giá góc trên bên trái chuẩn Flatsome -->
                        <div class="relative aspect-square w-full bg-gray-100 overflow-hidden">
                            <div class="badge-circle-sale">-${item.discount}%</div>
                            <img src="${primaryImg}"
                                 onerror="this.onerror=null; this.src='${fallbackImg}';"
                                 alt="${item.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>

                        <!-- Box Text: Tên sản phẩm đầy đủ không bị tràn hay thiếu chữ -->
                        <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                            <div>
                                <div class="text-[10px] sm:text-[11px] text-gray-400 font-medium mb-1">${item.category}</div>
                                <h3 class="product-title">${item.name}</h3>
                            </div>

                            <div class="pt-2 mt-1 border-t border-gray-100">
                                <div class="flex items-baseline gap-1.5 flex-wrap mb-2">
                                    <del class="text-[11px] sm:text-xs text-gray-400">${formatVND(item.oldPrice)}</del>
                                    <span class="text-xs sm:text-sm font-extrabold text-brand">${formatVND(item.price)}</span>
                                </div>
                                <button onclick="addToCart(${item.id})" class="w-full py-1.5 px-2 bg-brand-light hover:bg-brand text-brand hover:text-white border border-brand/25 rounded text-[11px] sm:text-xs font-bold transition flex items-center justify-center gap-1">
                                    <i class="fa-solid fa-cart-plus text-[11px]"></i>
                                    <span>Thêm vào giỏ</span>
                                </button>
                            </div>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function getFilteredProducts() {
            return productsData.filter(p => {
                const matchCat = (activeCategory === 'all') || (p.category === activeCategory);
                const matchQuery = !currentSearchQuery || p.name.toLowerCase().includes(currentSearchQuery.toLowerCase()) || p.category.toLowerCase().includes(currentSearchQuery.toLowerCase());
                return matchCat && matchQuery;
            });
        }

        function selectCategory(cat, event) {
            if (event) {
                document.querySelectorAll('.cat-pill').forEach(el => el.classList.remove('active'));
                if (event.currentTarget && event.currentTarget.classList.contains('cat-pill')) {
                    event.currentTarget.classList.add('active');
                }
            }
            activeCategory = cat;
            const heading = document.getElementById('currentCategoryHeading');
            heading.textContent = (cat === 'all')
                ? 'SẢN PHẨM QUÀ TẶNG & NƯỚC HOA CHARME NỔI BẬT'
                : 'DANH MỤC: ' + cat.toUpperCase();
            renderProducts(getFilteredProducts());
        }

        function filterProductsBySearch(query) {
            currentSearchQuery = query.trim();
            renderProducts(getFilteredProducts());
        }

        function sortProducts(mode) {
            let list = [...getFilteredProducts()];
            if (mode === 'price-asc') list.sort((a, b) => a.price - b.price);
            if (mode === 'price-desc') list.sort((a, b) => b.price - a.price);
            renderProducts(list);
        }

        /* Giỏ hàng */
        function addToCart(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;
            const existing = cart.find(i => i.id === productId);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...product, qty: 1 });
            }
            updateCartUI();
            showToast(`Đã thêm "${product.name}" vào giỏ hàng!`);
        }

        function updateCartUI() {
            const count = cart.reduce((sum, item) => sum + item.qty, 0);
            document.getElementById('cartCountBadge').textContent = count;

            const container = document.getElementById('cartItemsContainer');
            const totalEl = document.getElementById('cartTotalPrice');

            if (cart.length === 0) {
                container.innerHTML = `<p class="text-center text-gray-500 py-6">Giỏ hàng của bạn đang trống. Hãy chọn mẫu quà yêu thích nhé!</p>`;
                totalEl.textContent = '0₫';
                return;
            }

            let total = 0;
            container.innerHTML = cart.map(item => {
                total += item.price * item.qty;
                return `
                    <div class="flex items-center justify-between gap-2 border-b border-gray-100 pb-2.5">
                        <img src="https://lh3.googleusercontent.com/d/${item.driveId}" onerror="this.src='https://drive.google.com/thumbnail?id=${item.driveId}&sz=w200'" class="w-12 h-12 rounded object-cover border border-gray-200 shrink-0" alt="${item.name}">
                        <div class="flex-1 min-w-0">
                            <p class="font-semibold text-gray-800 text-xs leading-snug">${item.name}</p>
                            <p class="text-brand font-bold text-xs mt-0.5">${formatVND(item.price)} x ${item.qty}</p>
                        </div>
                        <button onclick="removeFromCart(${item.id})" class="text-gray-400 hover:text-red-600 p-1">
                            <i class="fa-solid fa-trash-can"></i>
                        </button>
                    </div>
                `;
            }).join('');
            totalEl.textContent = formatVND(total);
        }

        function removeFromCart(productId) {
            cart = cart.filter(i => i.id !== productId);
            updateCartUI();
        }

        function openCartModal() {
            updateCartUI();
            const modal = document.getElementById('cartModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeCartModal() {
            const modal = document.getElementById('cartModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Menu điện thoại */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const overlay = document.getElementById('mobileMenuOverlay');
            const isOpen = !drawer.classList.contains('-translate-x-full');
            if (isOpen) {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            } else {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            }
        }

        /* Slider 2 Banner Tự Trượt Kích Thước Bằng Nhau */
        let currentSlideIndex = 0;
        let slideInterval;

        function showSlide(index) {
            const slides = document.querySelectorAll('.banner-slide');
            const dot0 = document.getElementById('dot0');
            const dot1 = document.getElementById('dot1');

            currentSlideIndex = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentSlideIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            if (currentSlideIndex === 0) {
                dot0.className = 'w-5 h-2 rounded-full bg-brand-gold transition-all';
                dot1.className = 'w-2 h-2 rounded-full bg-white/60 transition-all';
            } else {
                dot0.className = 'w-2 h-2 rounded-full bg-white/60 transition-all';
                dot1.className = 'w-5 h-2 rounded-full bg-brand-gold transition-all';
            }
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlideIndex + 1);
            }, 4800);
        }

        /* Xử lý Form Yêu cầu & Báo giá trang chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i> Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá danh mục <strong>${category}</strong> của bạn đã được ghi nhận. Shop sẽ liên hệ SĐT/Zalo <strong>${phone}</strong> từ số Hotline <strong>0932.046.022</strong> trong ít phút!`;
            msgBox.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        function showToast(message) {
            const toast = document.getElementById('toastBox');
            toast.textContent = message;
            toast.classList.remove('hidden');
            clearTimeout(window.toastTimer);
            window.toastTimer = setTimeout(() => {
                toast.classList.add('hidden');
            }, 3000);
        }

        /* Khởi chạy khi tải trang */
        window.onload = function () {
            renderProducts(productsData);
            resetSlideTimer();
        };
    </script>
</body>
</html>
