<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN | xaydunghuynguyen.com</title>
    <meta name="description" content="CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN - Chuyên Thiết kế Kiến trúc, Thi công Xây dựng trọn gói, Hoàn thiện Nội thất Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tại Đà Nẵng. Hotline: 0931.944.991.">
    <meta name="keywords" content="xaydunghuynguyen.com, xây dựng Huy Nguyễn, thiết kế kiến trúc Đà Nẵng, thi công nhà phố Đà Nẵng, thi công nội thất Đà Nẵng, xây nhà trọn gói Đà Nẵng">

    <!-- Ảnh thumbnail logo hiển thị khi chia sẻ link website (Zalo, Facebook, Messenger) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://xaydunghuynguyen.com/">
    <meta property="og:site_name" content="xaydunghuynguyen.com">
    <meta property="og:title" content="CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN">
    <meta property="og:description" content="Thiết kế Kiến trúc - Xây dựng trọn gói - Thi công Nội thất uy tín tại Đà Nẵng. Địa chỉ: K28/12a Nguyễn Thế Lộc, P. An Hải, TP Đà Nẵng. Hotline: 0931.944.991.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w1000">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w1000">
    <meta property="og:image:alt" content="Logo Công ty TNHH Kiến Trúc Xây Dựng Nội Thất Huy Nguyễn">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN">
    <meta name="twitter:description" content="Thiết kế Kiến trúc - Xây dựng trọn gói - Thi công Nội thất tại Đà Nẵng. Hotline: 0931.944.991.">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w1000">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w256">

    <!-- Font Inter chuẩn hiện đại & dễ đọc -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            primary: '#183153',     /* Xanh navy kiến trúc chủ đạo */
                            dark: '#0F213B',        /* Xanh đậm phần chân trang & top bar */
                            accent: '#C98F2B',      /* Vàng đồng sang trọng theo tông logo xây dựng */
                            accentHover: '#B07A1F',
                            light: '#F6F7F9',
                            border: '#E5E7EB',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền & lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1F2937;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang giao diện máy tính bằng 95% màn hình */
        .ux-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .ux-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }
        @media (min-width: 1024px) {
            .ux-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Dropdown menu chuẩn Flatsome trên máy tính */
        .nav-item {
            position: relative;
        }
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Hiệu ứng chuyển slide banner mượt mà */
        .banner-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .banner-slide {
            width: 50%;
            flex-shrink: 0;
            position: relative;
            overflow: hidden;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes phoneRing {
            0%, 100% { transform: rotate(0deg) scale(1); }
            15% { transform: rotate(-12deg) scale(1.06); }
            30% { transform: rotate(12deg) scale(1.06); }
            45% { transform: rotate(-8deg) scale(1.04); }
            60% { transform: rotate(8deg) scale(1.04); }
            75% { transform: rotate(0deg) scale(1); }
        }
        .animate-ring {
            animation: phoneRing 2.2s infinite;
        }

        /* Ẩn thanh cuộn phụ trên tab danh mục điện thoại nhưng vẫn vuốt mượt */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hình ảnh thẻ sản phẩm tỷ lệ đồng đều, dễ tái tạo trên UX Builder */
        .card-img-wrap {
            aspect-ratio: 4 / 3;
            overflow: hidden;
            background-color: #F3F4F6;
        }
        .card-img-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }
        .project-card:hover .card-img-wrap img {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <!-- ==================== 1. TOP BAR THÔNG TIN (CHUẨN FLATSOME) ==================== -->
    <div class="bg-brand-dark text-gray-200 text-xs border-b border-white/10">
        <div class="ux-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0931944991" class="hover:text-brand-accent transition flex items-center gap-1.5 whitespace-nowrap">
                    <i class="fa-solid fa-phone text-brand-accent text-[11px]"></i>
                    <span class="font-medium">0931.944.991</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-brand-accent text-[11px]"></i>
                    <span>K28/12a Nguyễn Thế Lộc, P. An Hải, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3">
                <span class="hidden md:inline text-gray-300">xaydunghuynguyen.com</span>
                <a href="https://www.facebook.com/profile.php?id=61574562676786" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook" class="hover:text-brand-accent transition">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="https://zalo.me/0931944991" target="_blank" rel="noopener noreferrer" aria-label="Zalo Huy Nguyễn" class="hover:text-brand-accent transition font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- ==================== 2. HEADER CHÍNH (LOGO GỌN NHỎ + DANH MỤC 1 HÀNG, KHÔNG NÚT GỌI NGAY) ==================== -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-gray-200 shadow-sm w-full">
        <div class="ux-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo công ty chỉnh gọn nhỏ lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0">
                <img
                    src="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w400"
                    data-drive-id="1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA"
                    alt="Logo Công ty Kiến trúc Xây dựng Nội thất Huy Nguyễn"
                    onerror="handleDriveImageError(this, 'HUY NGUYEN')"
                    class="h-10 sm:h-11 md:h-12 w-auto max-w-[140px] object-contain rounded"
                >
                <div class="leading-tight hidden sm:block">
                    <div class="text-xs xl:text-sm font-extrabold text-brand-primary tracking-tight whitespace-nowrap">HUY NGUYỄN</div>
                    <div class="text-[10px] text-brand-accent font-semibold tracking-wide whitespace-nowrap">KIẾN TRÚC • XÂY DỰNG • NỘI THẤT</div>
                </div>
            </a>

            <!-- Danh mục trên máy tính: chữ nhỏ gọn, viết liền không xuống dòng tên danh mục -->
            <nav aria-label="Danh mục chính" class="hidden lg:flex flex-wrap items-center justify-end gap-x-3.5 xl:gap-x-5 gap-y-1">
                <a href="#trang-chu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-brand-primary hover:text-brand-accent transition py-1.5 whitespace-nowrap">Trang chủ</a>
                <a href="#gioi-thieu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 whitespace-nowrap">Giới thiệu</a>

                <!-- Dropdown Công trình thực tế -->
                <div class="nav-item">
                    <a href="#cong-trinh-thuc-te" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 inline-flex items-center gap-1 whitespace-nowrap">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] text-gray-400"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-gray-100 py-2">
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho')" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Văn phòng</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterProjects('noi-that')" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Nội thất hoàn thiện</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Lĩnh vực hoạt động -->
                <div class="nav-item">
                    <a href="#dich-vu" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 inline-flex items-center gap-1 whitespace-nowrap">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px] text-gray-400"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-gray-100 py-2">
                            <a href="#dich-vu" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#dich-vu" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Thi công phần thô</a>
                            <a href="#dich-vu" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Thi công hoàn thiện</a>
                            <a href="#dich-vu" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 whitespace-nowrap">Dự án Đà Nẵng</a>

                <!-- Dropdown Báo giá -->
                <div class="nav-item">
                    <a href="#bao-gia" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 inline-flex items-center gap-1 whitespace-nowrap">
                        <span>Báo giá</span>
                        <i class="fa-solid fa-chevron-down text-[9px] text-gray-400"></i>
                    </a>
                    <div class="nav-dropdown absolute right-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-gray-100 py-2">
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-gray-700 hover:bg-brand-light hover:text-brand-accent whitespace-nowrap">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#tin-tuc" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 whitespace-nowrap">Tin tức</a>
                <a href="#doi-tac" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 whitespace-nowrap">Đối tác</a>
                <a href="#lien-he" class="text-[12px] xl:text-[13px] font-semibold uppercase text-gray-700 hover:text-brand-accent transition py-1.5 whitespace-nowrap">Liên hệ</a>
            </nav>

            <!-- Nút mở menu trên điện thoại & máy tính bảng -->
            <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-gray-200 text-brand-primary hover:bg-brand-light transition">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu trượt gọn đẹp cho điện thoại -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-gray-100 shadow-lg w-full">
            <div class="ux-container py-3 flex flex-col divide-y divide-gray-100">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-semibold text-brand-primary">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Giới thiệu</a>
                <a href="#dich-vu" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Công trình thực tế</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Dự án Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Báo giá &amp; Tư vấn</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Tin tức</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Đối tác</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 text-sm font-medium text-gray-700">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- ==================== 3. BANNER TỰ TRƯỢT 2 ẢNH BẰNG NHAU, CHỮ CÁCH XA VIỀN ==================== -->
        <section class="w-full bg-brand-dark py-3 sm:py-4">
            <div class="ux-container">
                <div id="hero-slider" class="relative w-full overflow-hidden rounded-xl shadow-md bg-brand-dark">
                    <!-- Track chứa đúng 2 banner kích thước bằng nhau -->
                    <div id="banner-track" class="banner-track">

                        <!-- SLIDE 1 -->
                        <div class="banner-slide h-[290px] sm:h-[360px] md:h-[440px] lg:h-[500px]">
                            <img
                                src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                                data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                alt="Thiết kế kiến trúc và thi công xây dựng trọn gói Huy Nguyễn"
                                onerror="handleDriveImageError(this, 'HUY NGUYEN ARCHITECTURE')"
                                class="absolute inset-0 w-full h-full object-cover object-center"
                            >
                            <!-- Lớp phủ giúp chữ sắc nét hoàn toàn -->
                            <div class="absolute inset-0 bg-gradient-to-r from-[#0F213B]/90 via-[#183153]/75 to-[#0F213B]/45"></div>

                            <!-- Vùng nội dung cách xa 4 viền banner, đảm bảo không mất chữ trên mobile và PC -->
                            <div class="relative z-10 h-full w-full flex items-center">
                                <div class="w-full px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-12">
                                    <div class="max-w-2xl">
                                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-wider text-brand-accent mb-2">
                                            CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN
                                        </p>
                                        <h1 class="text-lg sm:text-2xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3">
                                            KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG &amp; ĐẲNG CẤP
                                        </h1>
                                        <p class="text-xs sm:text-sm md:text-base text-gray-200 leading-relaxed mb-5 max-w-xl">
                                            Chuyên Thiết kế Kiến trúc, Xây nhà trọn gói và Thi công Nội thất Nhà phố, Biệt thự, Căn hộ, Khách sạn tại TP. Đà Nẵng.
                                        </p>
                                        <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                            <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-semibold transition shadow">
                                                <span>Nhận báo giá miễn phí</span>
                                                <i class="fa-solid fa-arrow-right text-[11px]"></i>
                                            </a>
                                            <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                                                <span>Xem công trình</span>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- SLIDE 2 -->
                        <div class="banner-slide h-[290px] sm:h-[360px] md:h-[440px] lg:h-[500px]">
                            <img
                                src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                                data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                alt="Thi công chuẩn tiến độ và hoàn thiện nội thất cao cấp tại Đà Nẵng"
                                onerror="handleDriveImageError(this, 'HUY NGUYEN INTERIOR')"
                                class="absolute inset-0 w-full h-full object-cover object-center"
                            >
                            <div class="absolute inset-0 bg-gradient-to-r from-[#0F213B]/90 via-[#183153]/75 to-[#0F213B]/45"></div>

                            <!-- Vùng nội dung cách xa 4 viền banner -->
                            <div class="relative z-10 h-full w-full flex items-center">
                                <div class="w-full px-10 sm:px-14 md:px-20 lg:px-24 py-8 sm:py-12">
                                    <div class="max-w-2xl">
                                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-wider text-brand-accent mb-2">
                                            XAYDUNGHUYNGUYEN.COM • HOTLINE 0931.944.991
                                        </p>
                                        <h2 class="text-lg sm:text-2xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3">
                                            THI CÔNG CHUẨN KỸ THUẬT — BÀN GIAO ĐÚNG TIẾN ĐỘ
                                        </h2>
                                        <p class="text-xs sm:text-sm md:text-base text-gray-200 leading-relaxed mb-5 max-w-xl">
                                            Cam kết vật tư chính hãng, báo giá minh bạch không phát sinh, giám sát chặt chẽ từng hạng mục và bảo hành dài hạn.
                                        </p>
                                        <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                            <a href="#du-an-da-nang" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-semibold transition shadow">
                                                <span>Dự án tại Đà Nẵng</span>
                                                <i class="fa-solid fa-arrow-right text-[11px]"></i>
                                            </a>
                                            <a href="#lien-he" class="inline-flex items-center gap-2 px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs sm:text-sm font-semibold transition">
                                                <span>Liên hệ khảo sát</span>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng trượt banner gọn gàng -->
                    <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Dấu chấm chỉ báo 2 slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Chuyển tới ảnh 1" class="w-6 h-2 rounded-full bg-brand-accent transition-all"></button>
                        <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Chuyển tới ảnh 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 4. DỊCH VỤ TIÊU BIỂU (3 KHỐI GIỐNG WEB MẪU FLATSOME) ==================== -->
        <section id="dich-vu" class="py-10 sm:py-14 bg-white">
            <div class="ux-container">
                <div class="text-center mb-8">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase tracking-tight">Dịch vụ tiêu biểu</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                    <!-- Dịch vụ 1: THIẾT KẾ -->
                    <a href="#form-bao-gia" class="group block rounded-xl overflow-hidden border border-gray-200 bg-white shadow-sm hover:shadow-md transition">
                        <div class="card-img-wrap relative">
                            <img
                                src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w900"
                                data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                alt="Thiết kế kiến trúc nội thất Huy Nguyễn"
                                onerror="handleDriveImageError(this, 'THIET KE KIEN TRUC')"
                            >
                        </div>
                        <div class="p-4 sm:p-5 text-center">
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary group-hover:text-brand-accent transition uppercase">THIẾT KẾ</h3>
                            <p class="text-xs sm:text-sm text-gray-600 mt-2 leading-relaxed">
                                Thiết kế Kiến trúc, Mặt tiền, Kết cấu &amp; Phối cảnh 3D Nội thất tối ưu ánh sáng, thông gió và công năng sử dụng.
                            </p>
                        </div>
                    </a>

                    <!-- Dịch vụ 2: THI CÔNG -->
                    <a href="#form-bao-gia" class="group block rounded-xl overflow-hidden border border-gray-200 bg-white shadow-sm hover:shadow-md transition">
                        <div class="card-img-wrap relative">
                            <img
                                src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                                data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                                alt="Thi công phần thô và xây nhà trọn gói Huy Nguyễn"
                                onerror="handleDriveImageError(this, 'THI CONG XAY DUNG')"
                            >
                        </div>
                        <div class="p-4 sm:p-5 text-center">
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary group-hover:text-brand-accent transition uppercase">THI CÔNG</h3>
                            <p class="text-xs sm:text-sm text-gray-600 mt-2 leading-relaxed">
                                Thi công Phần thô, Thi công Hoàn thiện và Xây dựng Trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng.
                            </p>
                        </div>
                    </a>

                    <!-- Dịch vụ 3: NỘI THẤT -->
                    <a href="#form-bao-gia" class="group block rounded-xl overflow-hidden border border-gray-200 bg-white shadow-sm hover:shadow-md transition">
                        <div class="card-img-wrap relative">
                            <img
                                src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w900"
                                data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                                alt="Thi công nội thất trọn gói Huy Nguyễn"
                                onerror="handleDriveImageError(this, 'THI CONG NOI THAT')"
                            >
                        </div>
                        <div class="p-4 sm:p-5 text-center">
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary group-hover:text-brand-accent transition uppercase">NỘI THẤT</h3>
                            <p class="text-xs sm:text-sm text-gray-600 mt-2 leading-relaxed">
                                Sản xuất &amp; lắp đặt Nội thất gỗ công nghiệp An Cường, gỗ tự nhiên chuẩn bản vẽ 3D, bền đẹp và tinh tế từng chi tiết.
                            </p>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- ==================== 5. GIỚI THIỆU CÔNG TY & THẾ MẠNH (CHUẨN WEB MẪU) ==================== -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-light border-y border-gray-200/80">
            <div class="ux-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10 sm:mb-12">
                    <div class="lg:col-span-7">
                        <p class="text-xs font-bold uppercase tracking-wider text-brand-accent mb-1.5">Về chúng tôi</p>
                        <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary leading-snug mb-4">
                            CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN
                        </h2>
                        <p class="text-sm sm:text-[15px] text-gray-700 leading-relaxed mb-3">
                            <strong>HUY NGUYỄN</strong> chuyên Thiết kế Kiến trúc – Thi công Xây dựng – Hoàn thiện Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực Đà Nẵng và miền Trung.
                        </p>
                        <p class="text-sm sm:text-[15px] text-gray-700 leading-relaxed mb-5">
                            Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu, chúng tôi mang đến giải pháp thi công đồng bộ từ khâu tư vấn ý tưởng, xin phép xây dựng đến bàn giao chìa khóa trao tay, đảm bảo tiêu chuẩn: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – THẨM MỸ</strong>.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-3">
                            <div class="bg-white rounded-lg p-3.5 border border-gray-200 text-center">
                                <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">100%</div>
                                <div class="text-xs text-gray-600 mt-0.5 font-medium">Vật tư chuẩn cam kết</div>
                            </div>
                            <div class="bg-white rounded-lg p-3.5 border border-gray-200 text-center">
                                <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">5 Năm</div>
                                <div class="text-xs text-gray-600 mt-0.5 font-medium">Bảo hành kết cấu</div>
                            </div>
                            <div class="col-span-2 sm:col-span-1 bg-white rounded-lg p-3.5 border border-gray-200 text-center">
                                <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">24/7</div>
                                <div class="text-xs text-gray-600 mt-0.5 font-medium">Tư vấn &amp; hỗ trợ</div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-5">
                        <div class="rounded-xl overflow-hidden shadow-md border border-gray-200 bg-white">
                            <img
                                src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000"
                                data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                                alt="Công trình thực tế của Công ty Xây dựng Huy Nguyễn Đà Nẵng"
                                onerror="handleDriveImageError(this, 'XAY DUNG HUY NGUYEN')"
                                class="w-full h-64 sm:h-80 object-cover"
                            >
                        </div>
                    </div>
                </div>

                <!-- 6 Thế mạnh của chúng tôi -->
                <div class="text-center mb-7">
                    <h3 class="text-lg sm:text-xl md:text-2xl font-extrabold text-brand-primary uppercase">Thế mạnh của chúng tôi</h3>
                    <div class="w-14 h-1 bg-brand-accent mx-auto mt-2 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                    <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-compass-drafting text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-primary mb-1">Đội ngũ KTS &amp; kỹ sư chuyên nghiệp</h4>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp cùng đội ngũ kỹ sư hiện trường và thợ lành nghề giàu kinh nghiệm.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-layer-group text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-primary mb-1">Cập nhật xu hướng thiết kế mới</h4>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">Ứng dụng vật liệu hiện đại, giải pháp kiến trúc thông minh và tối ưu chi phí vận hành công trình.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-clipboard-check text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-primary mb-1">Giám sát tiến độ chuẩn xác</h4>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">Báo cáo hình ảnh thi công hằng ngày giúp chủ đầu tư dễ dàng theo dõi tiến độ dù ở xa.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-shield-halved text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-primary mb-1">Bảo hành công trình lâu dài</h4>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">Chính sách hậu mãi chu đáo, kiểm tra định kỳ và hỗ trợ xử lý nhanh chóng khi khách hàng cần.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-primary mb-1">Giá cả hợp lý &amp; minh bạch</h4>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">Dự toán bóc tách khối lượng rõ ràng từng hạng mục, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
                        <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-headset text-lg"></i>
                        </div>
                        <div>
                            <h4 class="text-sm sm:text-[15px] font-bold text-brand-primary mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                            <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">Khảo sát thực tế tận nơi, tư vấn công năng, phong thủy và lập phương án sơ bộ hoàn toàn miễn phí.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 6. CÔNG TRÌNH THỰC TẾ (9 ẢNH THỰC TẾ TỪ DRIVE - 2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN) ==================== -->
        <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase">Công trình thi công thực tế</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-gray-600 mt-2.5 max-w-2xl mx-auto">
                        Hình ảnh thi công thực tế các hạng mục phần thô, hoàn thiện kiến trúc và nội thất do đội ngũ Huy Nguyễn trực tiếp triển khai.
                    </p>
                </div>

                <!-- Thanh lọc danh mục nhỏ gọn, viết liền không xuống dòng tên danh mục -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7" role="tablist" aria-label="Danh mục công trình thực tế">
                    <button type="button" onclick="filterProjects('all')" data-cat="all" class="filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-primary text-white">Tất cả</button>
                    <button type="button" onclick="filterProjects('nha-pho')" data-cat="nha-pho" class="filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-light text-gray-700 hover:bg-gray-200">Nhà phố</button>
                    <button type="button" onclick="filterProjects('biet-thu')" data-cat="biet-thu" class="filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-light text-gray-700 hover:bg-gray-200">Biệt thự</button>
                    <button type="button" onclick="filterProjects('khach-san-can-ho')" data-cat="khach-san-can-ho" class="filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-light text-gray-700 hover:bg-gray-200">Khách sạn – Căn hộ</button>
                    <button type="button" onclick="filterProjects('van-phong')" data-cat="van-phong" class="filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-light text-gray-700 hover:bg-gray-200">Văn phòng</button>
                    <button type="button" onclick="filterProjects('noi-that')" data-cat="noi-that" class="filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-light text-gray-700 hover:bg-gray-200">Nội thất</button>
                </div>

                <!-- Lưới công trình thực tế: chia đúng 2 cột trên điện thoại, 3 cột trên máy tính, tên hiển thị trọn vẹn -->
                <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Được render bằng JavaScript từ dữ liệu 9 ảnh thực tế chuẩn xác -->
                </div>
            </div>
        </section>

        <!-- ==================== 7. CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH TỪ DRIVE - 2 CỘT TRÊN MOBILE) ==================== -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-light border-y border-gray-200/80">
            <div class="ux-container">
                <div class="text-center mb-7">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase">Các dự án tiêu biểu tại Đà Nẵng</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-gray-600 mt-2.5 max-w-2xl mx-auto">
                        Tổng hợp các công trình thiết kế và thi công trọn gói do Kiến Trúc Xây Dựng Nội Thất Huy Nguyễn thực hiện tại các quận Sơn Trà, Hải Châu, Ngũ Hành Sơn, Cẩm Lệ và Hòa Xuân.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 3 cột trên tablet, 5 cột gọn đẹp trên màn hình máy tính 95% -->
                <div id="danang-projects-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Được render bằng JavaScript từ 10 ảnh dự án Đà Nẵng -->
                </div>
            </div>
        </section>

        <!-- ==================== 8. DANH MỤC BÁO GIÁ THAM KHẢO (THEO DANH MỤC WEB MẪU) ==================== -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-white">
            <div class="ux-container">
                <div class="text-center mb-8">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase">Bảng giá dịch vụ xây dựng</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-gray-600 mt-2.5 max-w-2xl mx-auto">
                        Đơn giá tham khảo rõ ràng theo từng gói dịch vụ. Liên hệ trực tiếp hotline <strong>0931.944.991</strong> để nhận bảng dự toán chi tiết theo diện tích thực tế.
                    </p>
                </div>

                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="rounded-xl border border-gray-200 bg-white p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent transition shadow-sm">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-brand-light text-brand-accent flex items-center justify-center mb-3">
                                <i class="fa-solid fa-pen-ruler text-lg"></i>
                            </div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary leading-snug mb-2">Báo giá Thiết kế Kiến trúc</h3>
                            <p class="text-base sm:text-lg font-extrabold text-brand-accent mb-3">Từ 150.000đ/m²</p>
                            <ul class="text-xs sm:text-sm text-gray-600 space-y-1.5 mb-4">
                                <li>• Hồ sơ kiến trúc &amp; kết cấu</li>
                                <li>• Hồ sơ điện nước M&amp;E</li>
                                <li>• Phối cảnh 3D mặt tiền</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectProjectType('Thiết kế Kiến trúc – Nội thất')" class="block w-full text-center py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-semibold transition">Yêu cầu báo giá</a>
                    </div>

                    <div class="rounded-xl border border-gray-200 bg-white p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent transition shadow-sm">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-brand-light text-brand-accent flex items-center justify-center mb-3">
                                <i class="fa-solid fa-trowel-bricks text-lg"></i>
                            </div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary leading-snug mb-2">Báo giá Thi công Phần thô</h3>
                            <p class="text-base sm:text-lg font-extrabold text-brand-accent mb-3">Từ 3.600.000đ/m²</p>
                            <ul class="text-xs sm:text-sm text-gray-600 space-y-1.5 mb-4">
                                <li>• Vật tư phần thô chính hãng</li>
                                <li>• Nhân công xây tô &amp; ốp lát</li>
                                <li>• Bảo hành kết cấu 5 năm</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectProjectType('Thi công phần thô')" class="block w-full text-center py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-semibold transition">Yêu cầu báo giá</a>
                    </div>

                    <div class="rounded-xl border border-gray-200 bg-white p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent transition shadow-sm">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-brand-light text-brand-accent flex items-center justify-center mb-3">
                                <i class="fa-solid fa-paint-roller text-lg"></i>
                            </div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary leading-snug mb-2">Báo giá Thi công Hoàn thiện</h3>
                            <p class="text-base sm:text-lg font-extrabold text-brand-accent mb-3">Từ 2.500.000đ/m²</p>
                            <ul class="text-xs sm:text-sm text-gray-600 space-y-1.5 mb-4">
                                <li>• Sơn nước, gạch ốp lát, trần</li>
                                <li>• Cửa nhôm kính &amp; thiết bị</li>
                                <li>• Vệ sinh công nghiệp bàn giao</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectProjectType('Thi công hoàn thiện')" class="block w-full text-center py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-semibold transition">Yêu cầu báo giá</a>
                    </div>

                    <div class="rounded-xl border border-brand-accent/60 bg-brand-light/40 p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent transition shadow-sm">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-brand-accent/15 text-brand-accent flex items-center justify-center mb-3">
                                <i class="fa-solid fa-house-circle-check text-lg"></i>
                            </div>
                            <h3 class="text-sm sm:text-base font-bold text-brand-primary leading-snug mb-2">Báo giá Thi công Trọn gói</h3>
                            <p class="text-base sm:text-lg font-extrabold text-brand-accent mb-3">Từ 5.800.000đ/m²</p>
                            <ul class="text-xs sm:text-sm text-gray-600 space-y-1.5 mb-4">
                                <li>• Chìa khóa trao tay đồng bộ</li>
                                <li>• Miễn phí hồ sơ xin phép XD</li>
                                <li>• Cam kết không phát sinh</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="selectProjectType('Xây nhà trọn gói')" class="block w-full text-center py-2 px-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-semibold transition">Yêu cầu báo giá</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ==================== -->
        <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-primary text-white">
            <div class="ux-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <div class="lg:col-span-5">
                        <p class="text-xs font-bold uppercase tracking-wider text-brand-accent mb-2">Tư vấn &amp; Dự toán miễn phí</p>
                        <h2 class="text-2xl sm:text-3xl font-extrabold leading-snug mb-4">
                            ĐĂNG KÝ NHẬN BÁO GIÁ XÂY DỰNG &amp; NỘI THẤT
                        </h2>
                        <p class="text-sm text-gray-200 leading-relaxed mb-6">
                            Để lại thông tin công trình dự kiến của anh/chị. Đội ngũ kỹ sư và kiến trúc sư của <strong>Huy Nguyễn</strong> sẽ liên hệ khảo sát và gửi bảng khái toán chi tiết nhanh nhất.
                        </p>
                        <div class="space-y-3 text-sm text-gray-100">
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-phone-volume text-brand-accent w-5"></i>
                                <span>Hotline / Zalo: <a href="tel:0931944991" class="font-bold text-white hover:text-brand-accent">0931.944.991</a></span>
                            </div>
                            <div class="flex items-start gap-3">
                                <i class="fa-solid fa-location-dot text-brand-accent w-5 mt-1"></i>
                                <span>K28/12a Nguyễn Thế Lộc, Phường An Hải, TP Đà Nẵng</span>
                            </div>
                            <div class="flex items-center gap-3">
                                <i class="fa-solid fa-globe text-brand-accent w-5"></i>
                                <span>xaydunghuynguyen.com</span>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7">
                        <form id="quote-form" onsubmit="submitQuoteForm(event)" class="bg-white text-gray-800 rounded-xl p-5 sm:p-7 shadow-xl">
                            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary uppercase mb-4">Thông tin yêu cầu tư vấn</h3>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label for="q-name" class="block text-xs font-semibold text-gray-700 mb-1">Họ và tên *</label>
                                    <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-brand-accent focus:ring-1 focus:ring-brand-accent">
                                </div>
                                <div>
                                    <label for="q-phone" class="block text-xs font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input id="q-phone" name="phone" type="tel" required placeholder="VD: 0931 944 991" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-brand-accent focus:ring-1 focus:ring-brand-accent">
                                </div>
                                <div>
                                    <label for="q-type" class="block text-xs font-semibold text-gray-700 mb-1">Loại công trình</label>
                                    <select id="q-type" name="type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-brand-accent">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Thi công nội thất">Thi công nội thất</option>
                                        <option value="Thiết kế Kiến trúc – Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                                        <option value="Thi công phần thô">Thi công phần thô</option>
                                        <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                                        <option value="Xây nhà trọn gói">Xây nhà trọn gói</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-budget" class="block text-xs font-semibold text-gray-700 mb-1">Mức đầu tư dự kiến</label>
                                    <select id="q-budget" name="budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 bg-white focus:outline-none focus:border-brand-accent">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ - 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ - 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                                <div class="sm:col-span-2">
                                    <label for="q-note" class="block text-xs font-semibold text-gray-700 mb-1">Diện tích đất / Yêu cầu chi tiết</label>
                                    <textarea id="q-note" name="note" rows="3" placeholder="VD: Diện tích 5x20m, xây 3 tầng tại Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-gray-300 focus:outline-none focus:border-brand-accent focus:ring-1 focus:ring-brand-accent"></textarea>
                                </div>
                            </div>

                            <!-- Thông báo gửi form thành công (không dùng alert) -->
                            <div id="quote-feedback" class="hidden mt-3.5 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>

                            <button type="submit" class="mt-4 w-full py-3 px-6 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm uppercase tracking-wide transition shadow">
                                Gửi yêu cầu tư vấn &amp; báo giá
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 10. TIN TỨC & BÀI VIẾT TRANG CHỦ ==================== -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
            <div class="ux-container">
                <div class="text-center mb-8">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase">Tin tức &amp; Cẩm nang xây dựng</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                </div>

                <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="articles-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Được render bằng JavaScript -->
                </div>
            </div>
        </section>

        <!-- ==================== 11. DANH MỤC CÁC ĐỐI TÁC ==================== -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-brand-light border-y border-gray-200/80">
            <div class="ux-container">
                <div class="text-center mb-7">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase">Đối tác &amp; Nhà cung cấp vật tư</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-gray-600 mt-2">
                        Hợp tác cùng các thương hiệu vật liệu xây dựng và nội thất hàng đầu Việt Nam.
                    </p>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">HÒA PHÁT</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Thép xây dựng</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">AN CƯỜNG</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Gỗ nội thất</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">DULUX</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Sơn nước cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">JOTUN</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Sơn ngoại thất</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">XINGFA</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Nhôm kính</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">TOTO</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Thiết bị vệ sinh</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">CADIVI</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Dây cáp điện</span>
                    </div>
                    <div class="bg-white rounded-xl border border-gray-200 p-3.5 flex flex-col items-center justify-center text-center h-20 hover:border-brand-accent transition">
                        <span class="text-sm font-extrabold text-brand-primary tracking-tight">SÔNG GIANH</span>
                        <span class="text-[10px] text-gray-500 mt-0.5">Xi măng PCB40</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== 12. GOOGLE MAP & FANPAGE FACEBOOK TRÊN TRANG CHỦ ==================== -->
        <section id="lien-he" class="py-10 sm:py-14 bg-white">
            <div class="ux-container">
                <div class="text-center mb-8">
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary uppercase">Bản đồ &amp; Kết nối Fanpage</h2>
                    <div class="w-16 h-1 bg-brand-accent mx-auto mt-2.5 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Cột Google Maps trụ sở K28/12a Nguyễn Thế Lộc, P. An Hải, TP Đà Nẵng -->
                    <div class="lg:col-span-7 flex flex-col rounded-xl border border-gray-200 overflow-hidden bg-white shadow-sm">
                        <div class="px-4 sm:px-5 py-3.5 bg-brand-light border-b border-gray-200 flex flex-wrap items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
                                <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
                                <span>Văn phòng: K28/12a Nguyễn Thế Lộc, P. An Hải, TP Đà Nẵng</span>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=K28%2F12a+Nguy%E1%BB%85n+Th%E1%BA%BF+L%E1%BB%99c,+An+H%E1%BA%A3i,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-accent hover:underline whitespace-nowrap">
                                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px] ml-0.5"></i>
                            </a>
                        </div>
                        <div class="w-full h-[300px] sm:h-[360px] flex-1 bg-gray-100">
                            <iframe
                                title="Bản đồ Công ty TNHH Kiến trúc Xây dựng Nội thất Huy Nguyễn tại Đà Nẵng"
                                src="https://maps.google.com/maps?q=K28%2F12a%20Nguy%E1%BB%85n%20Th%E1%BA%BF%20L%E1%BB%99c,%20An%20H%E1%BA%A3i,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột Fanpage Facebook chính thức -->
                    <div class="lg:col-span-5 flex flex-col rounded-xl border border-gray-200 overflow-hidden bg-white shadow-sm">
                        <div class="px-4 sm:px-5 py-3.5 bg-brand-light border-b border-gray-200 flex items-center justify-between gap-2">
                            <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
                                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                                <span>Fanpage Facebook chính thức</span>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=61574562676786" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-[#1877F2] hover:underline whitespace-nowrap">
                                Theo dõi trang
                            </a>
                        </div>

                        <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between gap-4">
                            <!-- Thẻ nhận diện Fanpage đẹp, luôn hiển thị rõ trên mọi trình duyệt -->
                            <div class="rounded-xl border border-gray-200 overflow-hidden bg-white">
                                <div class="relative h-28 bg-brand-primary overflow-hidden">
                                    <img
                                        src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                                        data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                        alt="Ảnh bìa Fanpage Kiến trúc Xây dựng Nội thất Huy Nguyễn"
                                        onerror="handleDriveImageError(this, 'FANPAGE HUY NGUYEN')"
                                        class="w-full h-full object-cover opacity-55"
                                    >
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                            <img
                                                src="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w200"
                                                data-drive-id="1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA"
                                                alt="Avatar Fanpage Huy Nguyễn"
                                                onerror="handleDriveImageError(this, 'HN')"
                                                class="w-full h-full object-contain"
                                            >
                                        </div>
                                        <div class="min-w-0">
                                            <div class="text-xs sm:text-sm font-bold text-white leading-snug">CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN</div>
                                            <div class="text-[11px] text-gray-200">Kiến trúc • Xây dựng • Nội thất Đà Nẵng</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="p-3.5 text-xs sm:text-sm text-gray-600 leading-relaxed">
                                    Cập nhật hình ảnh tiến độ thi công thực tế hàng ngày, các mẫu thiết kế nhà phố, biệt thự, căn hộ mới nhất và chương trình ưu đãi xây nhà trọn gói tại Đà Nẵng.
                                </div>
                            </div>

                            <!-- Nhúng Facebook Page Plugin chuẩn -->
                            <div class="w-full overflow-hidden rounded-lg border border-gray-100 bg-gray-50">
                                <iframe
                                    title="Fanpage Facebook Kiến trúc Xây dựng Nội thất Huy Nguyễn"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61574562676786&tabs=&width=420&height=130&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    class="w-full h-[130px] border-0 overflow-hidden"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>

                            <div class="grid grid-cols-2 gap-2.5">
                                <a href="https://www.facebook.com/profile.php?id=61574562676786" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs sm:text-sm font-semibold transition">
                                    <i class="fa-brands fa-facebook"></i>
                                    <span>Xem Fanpage</span>
                                </a>
                                <a href="https://zalo.me/0931944991" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg bg-[#0068FF] hover:bg-[#0055D4] text-white text-xs sm:text-sm font-semibold transition">
                                    <i class="fa-solid fa-comments"></i>
                                    <span>Chat Zalo ngay</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==================== 13. CHÂN TRANG (FOOTER CHUẨN FLATSOME) ==================== -->
    <footer class="bg-brand-dark text-gray-300 border-t border-white/10">
        <div class="ux-container py-10 sm:py-12">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-8">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="bg-white rounded-lg p-1.5 shrink-0">
                            <img
                                src="https://drive.google.com/thumbnail?id=1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA&sz=w300"
                                data-drive-id="1Lx-Kh-_k5K1ykviPjM0neUGJNESY6fWA"
                                alt="Logo Huy Nguyễn"
                                onerror="handleDriveImageError(this, 'HUY NGUYEN')"
                                class="h-10 w-auto object-contain"
                            >
                        </div>
                        <div class="text-sm font-extrabold text-white leading-snug">
                            CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-gray-300">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-accent mt-1 w-4"></i>
                            <span><strong>Trụ sở:</strong> K28/12a Nguyễn Thế Lộc, Phường An Hải, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-accent w-4"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0931944991" class="text-white hover:text-brand-accent font-semibold">0931.944.991</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-brand-accent w-4"></i>
                            <span><strong>Website:</strong> xaydunghuynguyen.com</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-building-columns text-brand-accent w-4"></i>
                            <span><strong>Mã số thuế:</strong> 0402270285</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">Lĩnh vực hoạt động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#dich-vu" class="hover:text-brand-accent transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#dich-vu" class="hover:text-brand-accent transition">Thi công phần thô</a></li>
                        <li><a href="#dich-vu" class="hover:text-brand-accent transition">Thi công hoàn thiện</a></li>
                        <li><a href="#dich-vu" class="hover:text-brand-accent transition">Thi công xây nhà trọn gói</a></li>
                        <li><a href="#dich-vu" class="hover:text-brand-accent transition">Sản xuất &amp; thi công nội thất</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Công trình tiêu biểu -->
                <div class="lg:col-span-2">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">Công trình</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="hover:text-brand-accent transition">Nhà phố hiện đại</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="hover:text-brand-accent transition">Biệt thự sang trọng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san-can-ho')" class="hover:text-brand-accent transition">Khách sạn – Căn hộ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="hover:text-brand-accent transition">Văn phòng công ty</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-accent transition">Dự án tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div class="lg:col-span-2">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">Hỗ trợ</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#bao-gia" class="hover:text-brand-accent transition">Bảng báo giá</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-accent transition">Đăng ký tư vấn</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-accent transition">Tin tức xây dựng</a></li>
                        <li><a href="#doi-tac" class="hover:text-brand-accent transition">Đối tác vật tư</a></li>
                        <li><a href="https://www.facebook.com/profile.php?id=61574562676786" target="_blank" rel="noopener noreferrer" class="hover:text-brand-accent transition">Fanpage Facebook</a></li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="bg-[#091527] py-4 border-t border-white/10">
            <div class="ux-container flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-gray-400 text-center sm:text-left">
                <div>Copyright 2026 © CÔNG TY TNHH KIẾN TRÚC XÂY DỰNG NỘI THẤT HUY NGUYỄN.</div>
                <div>xaydunghuynguyen.com • Hotline: 0931.944.991</div>
            </div>
        </div>
    </footer>

    <!-- ==================== 14. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE - TƯƠNG THÍCH MOBILE & PC) ==================== -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/profile.php?id=61574562676786" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook Huy Nguyễn" class="group flex items-center gap-2 rounded-full bg-[#1877F2] hover:bg-[#1465CC] text-white shadow-lg px-3 py-2.5 sm:px-3.5 transition">
            <i class="fa-brands fa-facebook-f text-base w-5 text-center"></i>
            <span class="hidden md:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0931944991" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0931.944.991" class="group flex items-center gap-2 rounded-full bg-[#0068FF] hover:bg-[#0055D4] text-white shadow-lg px-3 py-2.5 sm:px-3.5 transition">
            <span class="font-extrabold text-[11px] w-5 text-center leading-none">Zalo</span>
            <span class="hidden md:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0931944991" aria-label="Gọi Hotline 0931.944.991" class="group flex items-center gap-2 rounded-full bg-gradient-to-r from-red-600 to-rose-600 hover:from-red-700 hover:to-rose-700 text-white shadow-xl px-3 py-2.5 sm:px-4 transition ring-2 ring-white/80">
            <i class="fa-solid fa-phone-volume text-base w-5 text-center animate-ring"></i>
            <span class="hidden sm:inline text-xs sm:text-sm font-extrabold pr-0.5 whitespace-nowrap">0931.944.991</span>
        </a>

        <!-- Nút cuộn lên đầu trang -->
        <button id="scroll-top-btn" type="button" onclick="window.scrollTo({top: 0, behavior: 'smooth'})" aria-label="Lên đầu trang" class="hidden w-10 h-10 rounded-full bg-brand-primary/90 hover:bg-brand-accent text-white shadow-md items-center justify-center transition">
            <i class="fa-solid fa-chevron-up text-xs"></i>
        </button>
    </div>

    <!-- ==================== 15. MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT ==================== -->
    <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm p-3 sm:p-6 flex items-center justify-center" onclick="closeModalOnBackdrop(event)">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl">
            <div class="sticky top-0 bg-white border-b border-gray-200 px-4 sm:px-5 py-3 flex items-center justify-between gap-3">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand-primary leading-snug"></h3>
                <button type="button" onclick="closeDetailModal()" aria-label="Đóng" class="w-8 h-8 rounded-lg bg-gray-100 hover:bg-gray-200 text-gray-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5">
                <div class="rounded-lg overflow-hidden bg-gray-100 mb-4">
                    <img id="modal-img" src="" alt="" class="w-full max-h-[420px] object-contain mx-auto bg-gray-50">
                </div>
                <p id="modal-meta" class="text-xs font-semibold text-brand-accent mb-2"></p>
                <p id="modal-desc" class="text-sm text-gray-700 leading-relaxed mb-5"></p>
                <div class="flex flex-wrap items-center gap-2.5">
                    <a href="#form-bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-semibold transition">
                        <i class="fa-solid fa-calculator"></i>
                        <span>Nhận báo giá mẫu tương tự</span>
                    </a>
                    <a href="tel:0931944991" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-semibold transition">
                        <i class="fa-solid fa-phone"></i>
                        <span>Gọi 0931.944.991</span>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ TƯƠNG TÁC, DỮ LIỆU & ẢNH DRIVE ==================== -->
    <script>
        /**
         * Hàm dự phòng khi tải ảnh từ Google Drive:
         * Bước 1: Thử link lh3.googleusercontent.com/d/{ID}
         * Bước 2: Nếu vẫn lỗi, hiển thị ảnh placeholder gọn đẹp theo màu thương hiệu
         */
        function handleDriveImageError(img, labelText) {
            try {
                const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);
                const driveId = img.getAttribute('data-drive-id');
                if (step === 0 && driveId) {
                    img.setAttribute('data-fallback-step', '1');
                    img.src = 'https://lh3.googleusercontent.com/d/' + driveId;
                } else if (step <= 1) {
                    img.setAttribute('data-fallback-step', '2');
                    const encoded = encodeURIComponent(labelText || 'Huy Nguyen');
                    img.src = 'https://placehold.co/800x600/183153/C98F2B?text=' + encoded;
                }
            } catch (err) {
                console.error('Lỗi xử lý ảnh dự phòng:', err);
            }
        }

        /**
         * Tạo URL ảnh Google Drive chuẩn độ nét cao
         */
        function getDriveThumb(id, size) {
            return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w' + (size || 900);
        }

        /* ==================== DỮ LIỆU 9 ẢNH CÔNG TRÌNH THỰC TẾ TỪ GOOGLE DRIVE ==================== */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng',
                location: 'TP. Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng thiết kế mặt tiền hiện đại, tối ưu thông gió tự nhiên và ánh sáng giếng trời, thi công trọn gói chuẩn tiến độ bởi đội ngũ kỹ sư Huy Nguyễn.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Thi Công Phần Thô & Kết Cấu Bê Tông Cốt Thép',
                location: 'Khu vực Sơn Trà, Đà Nẵng',
                desc: 'Hạng mục thi công phần thô chuẩn kỹ thuật với thép Hòa Phát, bê tông thương phẩm kiểm định mác chuẩn, đảm bảo độ bền kết cấu và chống thấm tuyệt đối.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                title: 'Thiết Kế & Thi Công Mặt Tiền Biệt Thự Phố',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Biệt thự phố phong cách kiến trúc tinh tế, kết hợp hệ cửa nhôm kính Xingfa cao cấp cùng mảng xanh ban công tạo không gian sống đẳng cấp.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ',
                title: 'Thi Công Hoàn Thiện Căn Hộ Cho Thuê Cao Cấp',
                location: 'Phường An Hải, Đà Nẵng',
                desc: 'Tòa nhà căn hộ cho thuê thiết kế tối ưu diện tích khai thác, hệ thống điện nước M&E đồng bộ, PCCC tiêu chuẩn và vật liệu hoàn thiện bền bỉ.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                category: 'noi-that',
                categoryLabel: 'Nội thất',
                title: 'Thi Công Hoàn Thiện Nội Thất Phòng Khách Sang Trọng',
                location: 'TP. Đà Nẵng',
                desc: 'Không gian phòng khách hoàn thiện nội thất gỗ công nghiệp chống ẩm An Cường, hệ đèn LED âm trần ấm áp, thi công sắc nét theo đúng bản vẽ 3D.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ',
                title: 'Thiết Kế & Thi Công Khách Sạn Mini Hiện Đại',
                location: 'Khu vực Biển Mỹ Khê, Đà Nẵng',
                desc: 'Công trình khách sạn quy mô tối ưu chi phí đầu tư, kiến trúc mặt tiền nổi bật thu hút khách du lịch và nội thất phòng nghỉ tiện nghi.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                category: 'noi-that',
                categoryLabel: 'Nội thất',
                title: 'Thi Công Tủ Bếp & Không Gian Phòng Ăn Hiện Đại',
                location: 'Hòa Xuân, Đà Nẵng',
                desc: 'Hệ tủ bếp chữ L mặt đá nhân tạo cao cấp kết hợp phụ kiện thông minh, bố trí khoa học giúp không gian bếp luôn gọn gàng, dễ vệ sinh.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                title: 'Thiết Kế & Thi Công Văn Phòng Làm Việc Chuyên Nghiệp',
                location: 'Quận Hải Châu, Đà Nẵng',
                desc: 'Thi công cải tạo và hoàn thiện nội thất văn phòng hiện đại, không gian mở tăng khả năng tương tác và thể hiện rõ bản sắc thương hiệu doanh nghiệp.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                title: 'Thi Công Cải Tạo & Hoàn Thiện Biệt Thự Sân Vườn',
                location: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Hoàn thiện kiến trúc ngoại thất và cảnh quan sân vườn biệt thự với vật liệu đá tự nhiên, gỗ nhựa ngoài trời chịu nắng gió khí hậu biển miền Trung.'
            }
        ];

        /* ==================== DỮ LIỆU 10 ẢNH DỰ ÁN TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE ==================== */
        const daNangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố 3 Tầng Khu Đô Thị Hòa Xuân, Đà Nẵng',
                location: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng',
                desc: 'Dự án thiết kế và thi công trọn gói nhà phố 3 tầng diện tích 100m² tại Khu đô thị sinh thái Hòa Xuân, bàn giao chìa khóa trao tay đúng tiến độ.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Căn Hộ Dịch Vụ Biển Sơn Trà, TP Đà Nẵng',
                location: 'Sơn Trà, TP Đà Nẵng',
                desc: 'Công trình căn hộ dịch vụ cao cấp gần biển Mỹ Khê, thiết kế tối ưu số lượng phòng cho thuê và công năng vận hành tiết kiệm điện năng.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Biệt Thự Hiện Đại Phường An Hải, Đà Nẵng',
                location: 'Phường An Hải, TP Đà Nẵng',
                desc: 'Biệt thự thiết kế không gian mở sang trọng với vật liệu chống ăn mòn muối biển, thi công kỹ lưỡng từ phần móng đến hoàn thiện nội thất.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố Kết Hợp Kinh Doanh Hải Châu, Đà Nẵng',
                location: 'Hải Châu, TP Đà Nẵng',
                desc: 'Giải pháp thiết kế nhà ở kết hợp mặt bằng kinh doanh tầng trệt thông thoáng, phân tách lối đi hợp lý và bảo đảm sự riêng tư cho gia đình.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Khách Sạn Boutique Mỹ Khê, Ngũ Hành Sơn',
                location: 'Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Thi công hoàn thiện kiến trúc và nội thất khách sạn boutique phong cách trẻ trung, đáp ứng tiêu chuẩn lưu trú du lịch tại Đà Nẵng.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Hoàn Thiện Nội Thất Căn Hộ Ven Sông Hàn',
                location: 'Sông Hàn, TP Đà Nẵng',
                desc: 'Gói thiết kế và thi công nội thất căn hộ view sông Hàn với tông màu trung tính sang trọng, vật liệu gỗ An Cường và ánh sáng tinh tế.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Nhà Phố 2 Mặt Tiền Khu Nam Việt Á, Đà Nẵng',
                location: 'Nam Việt Á, Ngũ Hành Sơn',
                desc: 'Công trình nhà phố góc 2 mặt tiền nổi bật với hình khối kiến trúc khỏe khoắn, ban công rộng đón gió mát quanh năm.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Thi Công Văn Phòng Đường Nguyễn Văn Linh',
                location: 'Nguyễn Văn Linh, Đà Nẵng',
                desc: 'Thi công hoàn thiện không gian văn phòng làm việc, phòng họp kính cách âm và khu vực lễ tân chuyên nghiệp ngay trung tâm thành phố.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Biệt Thự Phố Khu Đô Thị Phước Lý, Cẩm Lệ',
                location: 'Phước Lý, Cẩm Lệ, Đà Nẵng',
                desc: 'Dự án xây dựng trọn gói biệt thự phố hiện đại với sân đỗ ô tô rộng rãi, phòng khách thông tầng và nội thất đồng bộ.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Thi Công Trọn Gói Homestay Biển Đà Nẵng',
                location: 'Sơn Trà, TP Đà Nẵng',
                desc: 'Thiết kế và thi công homestay phong cách nghỉ dưỡng gần gũi thiên nhiên, tối ưu chi phí đầu tư và mang lại trải nghiệm thư giãn cho du khách.'
            }
        ];

        /* ==================== DỮ LIỆU BÀI VIẾT TRANG CHỦ ==================== */
        const articlesData = [
            {
                imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '18/11/2026',
                title: 'Kinh nghiệm xây nhà trọn gói tại Đà Nẵng tối ưu chi phí',
                excerpt: 'Tổng hợp các bước chuẩn bị hồ sơ thiết kế, lựa chọn vật tư và kiểm soát tiến độ để tránh phát sinh khi xây dựng tổ ấm.',
                content: 'Để xây nhà trọn gói tại Đà Nẵng đạt chất lượng cao và không phát sinh chi phí, chủ đầu tư cần chuẩn bị kỹ 4 yếu tố: (1) Lập hồ sơ thiết kế kiến trúc - kết cấu - điện nước chi tiết ngay từ đầu; (2) Bóc tách bảng dự toán chủng loại vật tư rõ ràng từng thương hiệu; (3) Ký hợp đồng minh bạch tiến độ thanh toán theo giai đoạn nghiệm thu; (4) Lựa chọn nhà thầu có trụ sở, đội ngũ kỹ sư giám sát trực tiếp và chính sách bảo hành lâu dài.'
            },
            {
                imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '12/11/2026',
                title: 'Hướng dẫn quy trình bảo dưỡng bê tông móng đúng chuẩn kỹ thuật',
                excerpt: 'Bảo dưỡng bê tông đúng cách trong 7 ngày đầu quyết định trực tiếp đến cường độ chịu lực và khả năng chống nứt của ngôi nhà.',
                content: 'Bê tông móng sau khi đổ cần được giữ ẩm liên tục để quá trình thủy hóa xi măng diễn ra hoàn toàn. Trong 24 giờ đầu, cần che phủ tránh nắng gắt hoặc mưa lớn trực tiếp. Từ ngày thứ 2 đến ngày thứ 7, tiến hành tưới nước giữ ẩm đều đặn 3-4 lần/ngày, đặc biệt trong điều kiện thời tiết nắng gió miền Trung.'
            },
            {
                imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                date: '05/11/2026',
                title: 'Thiết kế nội thất nhà phố: Bố trí công năng & ánh sáng tự nhiên',
                excerpt: 'Cách kết hợp giếng trời, vật liệu gỗ sáng màu và nội thất đa năng giúp nhà phố diện tích vừa vẫn rộng rãi, thoáng mát.',
                content: 'Nhà phố thường có chiều ngang từ 4m đến 5m và chiều sâu dài, do đó việc bố trí giếng trời giữa nhà kết hợp cầu thang thoáng và nội thất tối giản là chìa khóa giúp không gian luôn tràn ngập ánh sáng tự nhiên, lưu thông gió tốt và tiết kiệm điện năng.'
            },
            {
                imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                date: '28/10/2026',
                title: '03 lưu ý quan trọng chủ đầu tư cần biết trước khi khởi công',
                excerpt: 'Từ thủ tục xin giấy phép xây dựng, khảo sát địa chất nền móng đến dự trù ngân sách hoàn thiện nội thất đồng bộ.',
                content: 'Trước khi khởi công xây dựng tại TP. Đà Nẵng, chủ đầu tư cần hoàn tất hồ sơ xin phép xây dựng theo đúng mật độ và khoảng lùi quy hoạch, kiểm tra hiện trạng các công trình liền kề để có biện pháp thi công móng an toàn, đồng thời dự trù ngân sách cho phần nội thất rời nhằm đưa công trình vào sử dụng ngay sau khi bàn giao.'
            }
        ];

        /* ==================== RENDER CÔNG TRÌNH THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT MOBILE) ==================== */
        function renderConstructionProjects(filterCat) {
            const container = document.getElementById('construction-grid');
            if (!container) return;

            const filtered = filterCat === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.category === filterCat);

            container.innerHTML = filtered.map((item) => `
                <article
                    onclick="openDetailModal('${item.title.replace(/'/g, "\\'")}', '${getDriveThumb(item.id, 1200)}', '${item.id}', '${item.categoryLabel} • ${item.location}', '${item.desc.replace(/'/g, "\\'")}')"
                    class="project-card cursor-pointer rounded-xl overflow-hidden border border-gray-200 bg-white shadow-sm hover:shadow-md transition flex flex-col"
                >
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveThumb(item.id, 800)}"
                            data-drive-id="${item.id}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, '${item.categoryLabel}')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-[13px] sm:text-sm md:text-[15px] font-bold text-brand-primary leading-snug break-words hover:text-brand-accent transition">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-gray-500 mt-1.5">
                            ${item.categoryLabel} • ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== LỌC DANH MỤC CÔNG TRÌNH ==================== */
        function filterProjects(category) {
            renderConstructionProjects(category);
            const buttons = document.querySelectorAll('.filter-tab');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat') === category) {
                    btn.className = 'filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-primary text-white';
                } else {
                    btn.className = 'filter-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap transition bg-brand-light text-gray-700 hover:bg-gray-200';
                }
            });
        }

        /* ==================== RENDER 10 DỰ ÁN ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT MOBILE) ==================== */
        function renderDaNangProjects() {
            const container = document.getElementById('danang-projects-grid');
            if (!container) return;

            container.innerHTML = daNangProjects.map((item) => `
                <article
                    onclick="openDetailModal('${item.title.replace(/'/g, "\\'")}', '${getDriveThumb(item.id, 1200)}', '${item.id}', 'Dự án tại Đà Nẵng • ${item.location}', '${item.desc.replace(/'/g, "\\'")}')"
                    class="project-card cursor-pointer rounded-xl overflow-hidden border border-gray-200 bg-white shadow-sm hover:shadow-md transition flex flex-col"
                >
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveThumb(item.id, 700)}"
                            data-drive-id="${item.id}"
                            alt="${item.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, 'DU AN DA NANG')"
                        >
                    </div>
                    <div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-primary leading-snug break-words hover:text-brand-accent transition">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-gray-500 mt-1.5 flex items-start gap-1">
                            <i class="fa-solid fa-location-dot text-brand-accent text-[10px] mt-0.5 shrink-0"></i>
                            <span class="break-words">${item.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== RENDER BÀI VIẾT TRANG CHỦ ==================== */
        function renderArticles() {
            const container = document.getElementById('articles-grid');
            if (!container) return;

            container.innerHTML = articlesData.map((art) => `
                <article
                    onclick="openDetailModal('${art.title.replace(/'/g, "\\'")}', '${getDriveThumb(art.imgId, 1000)}', '${art.imgId}', 'Tin tức xây dựng • Ngày đăng: ${art.date}', '${art.content.replace(/'/g, "\\'")}')"
                    class="project-card cursor-pointer rounded-xl overflow-hidden border border-gray-200 bg-white shadow-sm hover:shadow-md transition flex flex-col"
                >
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveThumb(art.imgId, 700)}"
                            data-drive-id="${art.imgId}"
                            alt="${art.title}"
                            loading="lazy"
                            onerror="handleDriveImageError(this, 'TIN TUC XAY DUNG')"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-gray-500 mb-1">${art.date}</div>
                            <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary leading-snug break-words hover:text-brand-accent transition mb-1.5">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-gray-600 leading-relaxed hidden sm:block">
                                ${art.excerpt}
                            </p>
                        </div>
                        <span class="inline-flex items-center gap-1 text-xs font-semibold text-brand-accent mt-2.5">
                            Xem chi tiết <i class="fa-solid fa-angle-right text-[10px]"></i>
                        </span>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== ĐIỀU KHIỂN SLIDER 2 BANNER TỰ TRƯỢT + VUỐT CẢM ỨNG ==================== */
        let currentSlide = 0;
        const totalSlides = 2;
        let slideTimer = null;

        function updateSliderUI() {
            const track = document.getElementById('banner-track');
            if (track) {
                track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';
            }
            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById('dot-' + i);
                if (dot) {
                    if (i === currentSlide) {
                        dot.className = 'w-6 h-2 rounded-full bg-brand-accent transition-all';
                    } else {
                        dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                    }
                }
            }
        }

        function nextSlide() {
            currentSlide = (currentSlide + 1) % totalSlides;
            updateSliderUI();
            resetSlideTimer();
        }

        function prevSlide() {
            currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
            updateSliderUI();
            resetSlideTimer();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateSliderUI();
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(function () {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSliderUI();
            }, 5200);
        }

        /* Hỗ trợ vuốt cảm ứng trái/phải trên điện thoại cho banner */
        function initBannerTouchSwipe() {
            const slider = document.getElementById('hero-slider');
            if (!slider) return;
            let startX = 0;
            slider.addEventListener('touchstart', function (e) {
                startX = e.touches[0].clientX;
            }, { passive: true });
            slider.addEventListener('touchend', function (e) {
                const endX = e.changedTouches[0].clientX;
                const diff = startX - endX;
                if (Math.abs(diff) > 45) {
                    if (diff > 0) nextSlide();
                    else prevSlide();
                }
            }, { passive: true });
        }

        /* ==================== MENU MOBILE ==================== */
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        if (mobileMenuBtn && mobileMenu) {
            mobileMenuBtn.addEventListener('click', function () {
                mobileMenu.classList.toggle('hidden');
            });
        }

        function closeMobileMenu() {
            if (mobileMenu) mobileMenu.classList.add('hidden');
        }

        /* ==================== FORM BÁO GIÁ & CHỌN NHANH GÓI DỊCH VỤ ==================== */
        function selectProjectType(typeName) {
            const selectEl = document.getElementById('q-type');
            if (selectEl) {
                for (let i = 0; i < selectEl.options.length; i++) {
                    if (selectEl.options[i].value === typeName) {
                        selectEl.selectedIndex = i;
                        break;
                    }
                }
            }
        }

        function submitQuoteForm(event) {
            event.preventDefault();
            try {
                const name = document.getElementById('q-name').value.trim();
                const phone = document.getElementById('q-phone').value.trim();
                const type = document.getElementById('q-type').value;
                const budget = document.getElementById('q-budget').value;
                const feedback = document.getElementById('quote-feedback');

                if (!name || !phone) {
                    feedback.className = 'mt-3.5 p-3.5 rounded-lg bg-red-50 border border-red-200 text-red-700 text-xs sm:text-sm font-medium';
                    feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư liên hệ tư vấn.';
                    return;
                }

                feedback.className = 'mt-3.5 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium';
                feedback.innerHTML = 'Cảm ơn <strong>' + name + '</strong>! Yêu cầu báo giá <strong>' + type + '</strong> (ngân sách: ' + budget + ') đã được ghi nhận. Kỹ sư Huy Nguyễn sẽ liên hệ qua số <strong>' + phone + '</strong> trong thời gian sớm nhất, hoặc gọi ngay hotline <strong>0931.944.991</strong>.';
                document.getElementById('quote-form').reset();
            } catch (err) {
                console.error('Lỗi gửi form báo giá:', err);
            }
        }

        /* ==================== MODAL XEM CHI TIẾT ==================== */
        function openDetailModal(title, imgUrl, driveId, meta, desc) {
            const modal = document.getElementById('detail-modal');
            const mTitle = document.getElementById('modal-title');
            const mImg = document.getElementById('modal-img');
            const mMeta = document.getElementById('modal-meta');
            const mDesc = document.getElementById('modal-desc');

            mTitle.textContent = title;
            mMeta.textContent = meta;
            mDesc.textContent = desc;
            mImg.removeAttribute('data-fallback-step');
            mImg.setAttribute('data-drive-id', driveId);
            mImg.onerror = function () { handleDriveImageError(mImg, title); };
            mImg.src = imgUrl;
            mImg.alt = title;

            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            const modal = document.getElementById('detail-modal');
            if (modal) modal.classList.add('hidden');
            document.body.style.overflow = '';
        }

        function closeModalOnBackdrop(event) {
            if (event.target.id === 'detail-modal') {
                closeDetailModal();
            }
        }

        /* ==================== NÚT CUỘN LÊN ĐẦU TRANG ==================== */
        window.addEventListener('scroll', function () {
            const btn = document.getElementById('scroll-top-btn');
            if (!btn) return;
            if (window.scrollY > 360) {
                btn.classList.remove('hidden');
                btn.classList.add('flex');
            } else {
                btn.classList.add('hidden');
                btn.classList.remove('flex');
            }
        });

        /* ==================== KHỞI TẠO KHI TẢI TRANG ==================== */
        window.addEventListener('DOMContentLoaded', function () {
            renderConstructionProjects('all');
            renderDaNangProjects();
            renderArticles();
            updateSliderUI();
            resetSlideTimer();
            initBannerTouchSwipe();
        });
    </script>
</body>
</html>
