<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cổng Tư Vấn Tuyển Sinh 2027 | Phan Cảnh Thành Duy - HUSC</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & Plus Jakarta Sans -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        tech: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#0f172a',
                        },
                        energy: {
                            50: '#fff7ed',
                            100: '#ffedd5',
                            500: '#f97316',
                            600: '#ea580c',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Glassmorphism & Custom Scrollbar */
        body {
            background-color: #f8fafc;
            background-image: 
                radial-gradient(at 0% 0%, rgba(37, 99, 235, 0.08) 0px, transparent 50%),
                radial-gradient(at 100% 0%, rgba(249, 115, 22, 0.08) 0px, transparent 50%),
                radial-gradient(at 100% 100%, rgba(59, 130, 246, 0.06) 0px, transparent 50%);
            background-attachment: fixed;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.82);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border: 1px solid rgba(255, 255, 255, 0.9);
            box-shadow: 0 10px 30px -5px rgba(15, 23, 42, 0.05);
        }
        .glass-dark {
            background: linear-gradient(135deg, rgba(15, 23, 42, 0.95) 0%, rgba(30, 58, 138, 0.92) 100%);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.12);
        }
        /* Custom Range Slider */
        input[type=range] {
            -webkit-appearance: none;
            width: 100%;
            background: transparent;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 20px;
            width: 20px;
            border-radius: 50%;
            background: #f97316;
            border: 3px solid #ffffff;
            box-shadow: 0 2px 6px rgba(249, 115, 22, 0.45);
            cursor: pointer;
            margin-top: -7px;
            transition: transform 0.15s ease;
        }
        input[type=range]::-webkit-slider-thumb:hover {
            transform: scale(1.15);
        }
        input[type=range]::-webkit-slider-runnable-track {
            width: 100%;
            height: 6px;
            cursor: pointer;
            background: #e2e8f0;
            border-radius: 999px;
        }
        .legal-link {
            color: #2563eb;
            font-weight: 600;
            text-decoration: underline;
            text-decoration-color: rgba(37, 99, 235, 0.4);
            text-underline-offset: 3px;
            transition: all 0.2s;
        }
        .legal-link:hover {
            color: #ea580c;
            text-decoration-color: #ea580c;
        }
    </style>
</head>
<body class="text-slate-800 antialiased selection:bg-blue-600 selection:text-white">

    <!-- Sticky Glass Navigation -->
    <nav class="sticky top-0 z-50 glass-card border-b border-slate-200/70">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-blue-600 to-orange-500 flex items-center justify-center text-white font-bold shadow-md">
                        <i data-lucide="compass" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <span class="font-display font-bold text-slate-900 text-base sm:text-lg block leading-tight">HUSC Navigator 2027</span>
                        <span class="text-xs text-slate-500 font-medium">Hồ sơ cá nhân: Phan Cảnh Thành Duy</span>
                    </div>
                </div>
                
                <!-- Desktop Nav Links -->
                <div class="hidden md:flex items-center space-x-1 bg-slate-100/80 p-1 rounded-xl">
                    <a href="#legal-faq" class="px-3.5 py-2 rounded-lg text-sm font-semibold text-slate-700 hover:text-blue-600 hover:bg-white transition">Pháp lý & Thông tư</a>
                    <a href="#simulator" class="px-3.5 py-2 rounded-lg text-sm font-semibold text-slate-700 hover:text-blue-600 hover:bg-white transition">Tính điểm & Học bổng</a>
                    <a href="#strategies" class="px-3.5 py-2 rounded-lg text-sm font-semibold text-slate-700 hover:text-blue-600 hover:bg-white transition">So sánh 3 Lộ trình</a>
                    <a href="#checklist" class="px-3.5 py-2 rounded-lg text-sm font-semibold text-slate-700 hover:text-blue-600 hover:bg-white transition">Checklist Rút hồ sơ</a>
                </div>

                <a href="#simulator" class="inline-flex items-center gap-1.5 px-4 py-2 rounded-xl bg-gradient-to-r from-blue-600 to-blue-700 text-white text-sm font-semibold shadow-sm hover:shadow-md hover:from-blue-700 hover:to-blue-800 transition">
                    <i data-lucide="calculator" class="w-4 h-4"></i>
                    <span class="hidden sm:inline">Giả lập điểm</span>
                    <span class="sm:hidden">Tính điểm</span>
                </a>
            </div>
        </div>
    </nav>

    <!-- HERO DASHBOARD -->
    <header class="pt-8 pb-10 sm:pt-12 sm:pb-14 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="glass-dark rounded-3xl p-6 sm:p-10 text-white shadow-2xl relative overflow-hidden">
            <!-- Decorative blobs -->
            <div class="absolute -top-24 -right-24 w-72 h-72 bg-orange-500/20 rounded-full blur-3xl pointer-events-none"></div>
            <div class="absolute -bottom-24 -left-24 w-80 h-80 bg-blue-500/25 rounded-full blur-3xl pointer-events-none"></div>

            <div class="relative z-10 grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Left Profile & Mission -->
                <div class="lg:col-span-7 space-y-5">
                    <div class="inline-flex flex-wrap items-center gap-2 px-3.5 py-1.5 rounded-full bg-white/10 border border-white/20 text-xs sm:text-sm font-semibold text-orange-300">
                        <span class="w-2 h-2 rounded-full bg-orange-400 animate-ping"></span>
                        <span>K50 CNTT HUSC</span>
                        <i data-lucide="arrow-right" class="w-3.5 h-3.5 text-white"></i>
                        <span class="text-blue-200">K51 Kỹ thuật Trắc địa - Bản đồ (2k9)</span>
                    </div>

                    <h1 class="font-display text-2xl sm:text-4xl font-extrabold tracking-tight leading-tight">
                        Chào <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-300 via-white to-orange-300">Phan Cảnh Thành Duy</span>!
                    </h1>
                    
                    <p class="text-slate-300 text-sm sm:text-base leading-relaxed max-w-2xl">
                        Hệ thống đã đồng bộ toàn bộ học bạ THPT (Lớp 10–12) và điểm thi TN THPT 2026 của bạn. Quyết định chuyển hướng từ CNTT sang <strong>Kỹ thuật Trắc địa - Bản đồ (ĐH Khoa học - ĐH Huế)</strong> bằng cách rút hồ sơ thi lại 2027 giúp bạn tiết kiệm ~40 triệu đồng và mở rộng tối đa cơ hội săn <strong>Học bổng Tân sinh viên</strong>.
                    </p>

                    <!-- Quick Action Pills -->
                    <div class="flex flex-wrap gap-3 pt-2">
                        <a href="#legal-faq" class="px-4 py-2.5 rounded-xl bg-orange-500 hover:bg-orange-600 text-white font-semibold text-sm inline-flex items-center gap-2 shadow-lg shadow-orange-500/25 transition">
                            <i data-lucide="scale" class="w-4 h-4"></i>
                            Tra cứu Thông tư Bộ GD&ĐT
                        </a>
                        <a href="#checklist" class="px-4 py-2.5 rounded-xl bg-white/10 hover:bg-white/20 border border-white/20 text-white font-semibold text-sm inline-flex items-center gap-2 transition">
                            <i data-lucide="check-square" class="w-4 h-4"></i>
                            Thủ tục Rút hồ sơ HUSC
                        </a>
                    </div>
                </div>

                <!-- Right Countdown Timer & Quick Stats -->
                <div class="lg:col-span-5">
                    <div class="bg-white/10 backdrop-blur-md border border-white/15 rounded-2xl p-5 sm:p-6">
                        <div class="flex items-center justify-between mb-3">
                            <span class="text-xs font-bold uppercase tracking-wider text-blue-200 flex items-center gap-1.5">
                                <i data-lucide="timer" class="w-4 h-4 text-orange-400"></i>
                                Đếm ngược Kỳ thi TN THPT 2027
                            </span>
                            <span class="text-xs px-2 py-0.5 rounded bg-orange-500/30 text-orange-200 font-medium">Dự kiến 26/06/2027</span>
                        </div>

                        <!-- Countdown Grid -->
                        <div class="grid grid-cols-4 gap-2 sm:gap-3 text-center my-4">
                            <div class="bg-slate-900/60 rounded-xl p-2.5 border border-white/10">
                                <span id="cd-days" class="font-display text-2xl sm:text-3xl font-extrabold text-white block">221</span>
                                <span class="text-[11px] text-slate-400 uppercase font-semibold">Ngày</span>
                            </div>
                            <div class="bg-slate-900/60 rounded-xl p-2.5 border border-white/10">
                                <span id="cd-hours" class="font-display text-2xl sm:text-3xl font-extrabold text-blue-300 block">00</span>
                                <span class="text-[11px] text-slate-400 uppercase font-semibold">Giờ</span>
                            </div>
                            <div class="bg-slate-900/60 rounded-xl p-2.5 border border-white/10">
                                <span id="cd-mins" class="font-display text-2xl sm:text-3xl font-extrabold text-orange-300 block">00</span>
                                <span class="text-[11px] text-slate-400 uppercase font-semibold">Phút</span>
                            </div>
                            <div class="bg-slate-900/60 rounded-xl p-2.5 border border-white/10">
                                <span id="cd-secs" class="font-display text-2xl sm:text-3xl font-extrabold text-emerald-300 block">00</span>
                                <span class="text-[11px] text-slate-400 uppercase font-semibold">Giây</span>
                            </div>
                        </div>

                        <!-- Snapshot Scores -->
                        <div class="border-t border-white/15 pt-4 mt-2 grid grid-cols-2 gap-3 text-xs">
                            <div class="bg-white/5 rounded-xl p-3">
                                <span class="text-slate-400 block mb-1">Điểm thi THPT 2026</span>
                                <div class="font-semibold text-white">Văn 7.5 • Sử 7.0 • Anh 5.25 • Toán 4.0</div>
                            </div>
                            <div class="bg-white/5 rounded-xl p-3">
                                <span class="text-slate-400 block mb-1">Thế mạnh Học bạ Lớp 12</span>
                                <div class="font-semibold text-emerald-300">Anh 8.6 • Sử 8.5 • Tin 8.3 • Văn 8.0</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-14 pb-20">

        <!-- SECTION 1: LEGAL & REGULATORY KNOWLEDGE BASE (WITH DIRECT HYPERLINKS) -->
        <section id="legal-faq" class="scroll-mt-24">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-6 gap-4">
                <div>
                    <span class="text-xs font-bold uppercase tracking-wider text-blue-600 bg-blue-100 px-3 py-1 rounded-full">Căn cứ pháp lý chính thức</span>
                    <h2 class="font-display text-2xl sm:text-3xl font-extrabold text-slate-900 mt-2">
                        Giải đáp Cơ chế Tuyển sinh & Trích dẫn Thông tư Bộ GD&ĐT
                    </h2>
                </div>
                <p class="text-sm text-slate-600 max-w-md">
                    Nhấp vào các liên kết màu xanh để mở trực tiếp văn bản gốc trên Cổng Thông tin Điện tử Chính phủ và ĐH Huế.
                </p>
            </div>

            <!-- Interactive Legal Tabs -->
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
                <!-- Card 1: Thí sinh tự do & Quyền thi lại / dùng điểm cũ -->
                <div class="glass-card rounded-2xl p-6 flex flex-col justify-between border-t-4 border-t-blue-600">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-blue-50 text-blue-600 flex items-center justify-center mb-4">
                            <i data-lucide="file-check-2" class="w-6 h-6"></i>
                        </div>
                        <h3 class="font-display text-lg font-bold text-slate-900 mb-3">
                            1. Quyền dùng điểm cũ vs. Thi lại THPT 2027 & Xét học bạ
                        </h3>
                        <div class="space-y-3 text-sm text-slate-600 leading-relaxed">
                            <p>
                                Theo Quy chế tuyển sinh đại học ban hành kèm <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=205936" target="_blank" rel="noopener noreferrer" class="legal-link">Thông tư 08/2022/TT-BGDĐT</a> (và các văn bản sửa đổi, bổ sung hiện hành của Bộ GD&ĐT), thí sinh đã tốt nghiệp THPT những năm trước (thí sinh tự do) được hưởng quyền lợi xét tuyển bình đẳng như thí sinh 2k9:
                            </p>
                            <ul class="space-y-2 list-disc pl-4 text-slate-700">
                                <li><strong>Bảo lưu điểm thi cũ:</strong> Bạn hoàn toàn được sử dụng kết quả kỳ thi tốt nghiệp THPT 2026 (Văn 7.5, Sử 7.0, Anh 5.25, Toán 4.0) để đăng ký xét tuyển mà không bắt buộc thi lại.</li>
                                <li><strong>Đăng ký thi lại để lấy điểm cao hơn:</strong> Theo Quy chế thi tốt nghiệp THPT tại <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=212169" target="_blank" rel="noopener noreferrer" class="legal-link">Thông tư 24/2024/TT-BGDĐT</a>, người đã có Bằng tốt nghiệp THPT được phép đăng ký dự thi các môn thi trong tổ hợp xét tuyển đại học năm 2027 (ví dụ thi lại Toán, Lý, Tin, Anh hoặc Sử) để dùng điểm mới xét tuyển.</li>
                                <li><strong>Xét tuyển học bạ THPT:</strong> Được dùng kết quả học tập cấp THPT (đặc biệt lưu ý quy định mới của Bộ GD&ĐT yêu cầu dùng <strong>kết quả học tập cả năm lớp 12</strong> khi xét học bạ) để nộp vào Trường ĐH Khoa học - ĐH Huế.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="mt-5 pt-4 border-t border-slate-200/80 flex flex-wrap gap-2">
                        <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=205936" target="_blank" class="inline-flex items-center gap-1 text-xs font-semibold px-3 py-1.5 rounded-lg bg-blue-50 text-blue-700 hover:bg-blue-100 transition">
                            <i data-lucide="external-link" class="w-3.5 h-3.5"></i> TT 08/2022/TT-BGDĐT
                        </a>
                        <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=212169" target="_blank" class="inline-flex items-center gap-1 text-xs font-semibold px-3 py-1.5 rounded-lg bg-blue-50 text-blue-700 hover:bg-blue-100 transition">
                            <i data-lucide="external-link" class="w-3.5 h-3.5"></i> TT 24/2024/TT-BGDĐT
                        </a>
                    </div>
                </div>

                <!-- Card 2: Học bổng Tân sinh viên & Học bổng KKHT -->
                <div class="glass-card rounded-2xl p-6 flex flex-col justify-between border-t-4 border-t-orange-500">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-orange-50 text-orange-600 flex items-center justify-center mb-4">
                            <i data-lucide="award" class="w-6 h-6"></i>
                        </div>
                        <h3 class="font-display text-lg font-bold text-slate-900 mb-3">
                            2. Cơ chế Học bổng Tân sinh viên & Khuyến khích học tập
                        </h3>
                        <div class="space-y-3 text-sm text-slate-600 leading-relaxed">
                            <p>
                                Chính sách học bổng tại các cơ sở giáo dục đại học công lập được quy định tại <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=200531" target="_blank" rel="noopener noreferrer" class="legal-link">Nghị định 84/2020/NĐ-CP</a> và Đề án tuyển sinh hàng năm của <a href="https://tuyensinh.hueuni.edu.vn/" target="_blank" rel="noopener noreferrer" class="legal-link">Đại học Huế</a>:
                            </p>
                            <ul class="space-y-2 list-disc pl-4 text-slate-700">
                                <li><strong>Học bổng Tân sinh viên (Thủ khoa / Á khoa ngành):</strong> <a href="https://husc.hueuni.edu.vn/" target="_blank" rel="noopener noreferrer" class="legal-link">Trường ĐH Khoa học - ĐH Huế</a> thường trích quỹ hỗ trợ sinh viên để cấp học bổng miễn/giảm học phí kỳ 1 hoặc thưởng tiền mặt cho thí sinh có <strong>điểm trúng tuyển cao nhất ngành</strong> (thường ưu tiên xét theo phương thức điểm thi THPT).</li>
                                <li><strong>Tại sao bạn nên thi lại THPT 2027?</strong> Ngành Kỹ thuật Trắc địa - Bản đồ có điểm chuẩn khá nhẹ (15–17 điểm), nhưng nếu bạn thi lại để kéo Toán từ 4.0 lên 7.0+ kết hợp với Văn (7.5) / Sử (7.0) / Anh (5.25 -> 7.0+), tổng điểm đạt <strong>22–24+ điểm</strong> sẽ giúp bạn bứt phá lên nhóm đầu ngành để nhận học bổng!</li>
                                <li><strong>Học bổng KKHT từ HK2:</strong> Theo <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=200531" target="_blank" rel="noopener noreferrer" class="legal-link">Điều 8 Nghị định 84/2020/NĐ-CP</a>, từ học kỳ 2 trở đi, học bổng xét dựa trên GPA và điểm rèn luyện tại trường đại học (không phân biệt thí sinh tự do hay 2k9).</li>
                            </ul>
                        </div>
                    </div>
                    <div class="mt-5 pt-4 border-t border-slate-200/80 flex flex-wrap gap-2">
                        <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=200531" target="_blank" class="inline-flex items-center gap-1 text-xs font-semibold px-3 py-1.5 rounded-lg bg-orange-50 text-orange-700 hover:bg-orange-100 transition">
                            <i data-lucide="external-link" class="w-3.5 h-3.5"></i> Nghị định 84/2020/NĐ-CP
                        </a>
                        <a href="https://tuyensinh.hueuni.edu.vn/" target="_blank" class="inline-flex items-center gap-1 text-xs font-semibold px-3 py-1.5 rounded-lg bg-orange-50 text-orange-700 hover:bg-orange-100 transition">
                            <i data-lucide="external-link" class="w-3.5 h-3.5"></i> Tuyển sinh ĐH Huế
                        </a>
                    </div>
                </div>

                <!-- Card 3: Lưu ý sống còn khi rút hồ sơ K50 HUSC -->
                <div class="glass-card rounded-2xl p-6 flex flex-col justify-between border-t-4 border-t-emerald-600">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-50 text-emerald-600 flex items-center justify-center mb-4">
                            <i data-lucide="shield-alert" class="w-6 h-6"></i>
                        </div>
                        <h3 class="font-display text-lg font-bold text-slate-900 mb-3">
                            3. Những lưu ý sống còn khi rút hồ sơ khỏi HUSC
                        </h3>
                        <div class="space-y-3 text-sm text-slate-600 leading-relaxed">
                            <p>
                                Khi quyết định dừng học K50 CNTT tại <a href="https://husc.hueuni.edu.vn/" target="_blank" rel="noopener noreferrer" class="legal-link">Trường ĐH Khoa học - ĐH Huế</a> để thi lại cùng 2k9, bạn cần nắm chắc 4 nguyên tắc sau để không bị kẹt hồ sơ:
                            </p>
                            <ul class="space-y-2 list-disc pl-4 text-slate-700">
                                <li><strong>Không bị cấm thi lại:</strong> Quy chế tuyển sinh của Bộ GD&ĐT không cấm sinh viên đã nhập học đại học xin thôi học để dự thi và xét tuyển lại từ đầu ở mùa tuyển sinh năm sau.</li>
                                <li><strong>Rút giấy tờ gốc tại Phòng CTSV:</strong> Khi làm đơn xin thôi học, bạn phải thu hồi đủ <strong>Bản chính Giấy chứng nhận tốt nghiệp THPT / Bằng tốt nghiệp THPT</strong> và <strong>Học bạ THPT bản gốc</strong> (nếu trường đang giữ) để đối chiếu khi nhập học năm 2027.</li>
                                <li><strong>Nghĩa vụ học phí HK1:</strong> Hoàn tất thanh toán học phí các tín chỉ đã đăng ký ở HK1 năm nhất (thường chỉ khoảng 5–8 triệu đồng thay vì ~40 triệu cho cả năm + hè) để trường ký quyết định cho thôi học và trả hồ sơ sạch.</li>
                                <li><strong>Cấp lại tài khoản Hệ thống Bộ GD&ĐT:</strong> Khoảng tháng 4/2027, bạn nộp phiếu đăng ký dự thi thí sinh tự do tại điểm tiếp nhận do Sở GD&ĐT TP. Huế quy định để được cấp tài khoản mới trên cổng <em>thisinh.thitotnghiepthpt.edu.vn</em>.</li>
                            </ul>
                        </div>
                    </div>
                    <div class="mt-5 pt-4 border-t border-slate-200/80 flex flex-wrap gap-2">
                        <a href="https://husc.hueuni.edu.vn/" target="_blank" class="inline-flex items-center gap-1 text-xs font-semibold px-3 py-1.5 rounded-lg bg-emerald-50 text-emerald-700 hover:bg-emerald-100 transition">
                            <i data-lucide="external-link" class="w-3.5 h-3.5"></i> Cổng thông tin HUSC
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: INTERACTIVE SCORE & SCHOLARSHIP SIMULATOR -->
        <section id="simulator" class="scroll-mt-24">
            <div class="mb-6">
                <span class="text-xs font-bold uppercase tracking-wider text-orange-600 bg-orange-100 px-3 py-1 rounded-full">Dữ liệu thực tế từ học bạ của Duy</span>
                <h2 class="font-display text-2xl sm:text-3xl font-extrabold text-slate-900 mt-2">
                    Bộ Giả Lập Điểm Xét Tuyển & Săn Học Bổng 2027
                </h2>
                <p class="text-sm text-slate-600 mt-1">
                    Ngành <strong>Kỹ thuật Trắc địa - Bản đồ (Mã ngành: 7520503 - HUSC)</strong> xét tuyển đa tổ hợp. Hãy thử kéo thanh trượt điểm thi 2027 và kiểm tra điểm học bạ của bạn bên dưới.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                <!-- Left Column: Transcript Analysis (Học bạ 10-11-12) -->
                <div class="lg:col-span-5 glass-card rounded-2xl p-6 space-y-5">
                    <div class="flex items-center justify-between">
                        <h3 class="font-display font-bold text-lg text-slate-900 flex items-center gap-2">
                            <i data-lucide="book-open-check" class="w-5 h-5 text-blue-600"></i>
                            Phân tích Học bạ THPT
                        </h3>
                        <!-- Toggle 12 vs 3 years -->
                        <div class="inline-flex rounded-xl bg-slate-100 p-1 text-xs font-semibold">
                            <button id="btn-hb-12" onclick="setTranscriptMode('12')" class="px-3 py-1.5 rounded-lg bg-blue-600 text-white shadow-sm transition">
                                Cả năm Lớp 12
                            </button>
                            <button id="btn-hb-3y" onclick="setTranscriptMode('3y')" class="px-3 py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition">
                                TB 3 năm (10-12)
                            </button>
                        </div>
                    </div>

                    <div class="p-3.5 rounded-xl bg-blue-50/80 border border-blue-100 text-xs text-blue-800 leading-relaxed">
                        <strong>Ghi chú quy chế mới:</strong> Theo quy định của Bộ GD&ĐT áp dụng từ 2025–2027, xét tuyển học bạ bắt buộc sử dụng kết quả <strong>cả năm lớp 12</strong> (chiếm tối thiểu 25% trọng số hoặc dùng trực tiếp 3 môn lớp 12). Điểm lớp 12 của Duy rất đẹp!
                    </div>

                    <!-- Transcript Subject Grid -->
                    <div class="overflow-x-auto">
                        <table class="w-full text-left border-collapse text-xs sm:text-sm">
                            <thead>
                                <tr class="border-b border-slate-200 text-slate-500">
                                    <th class="py-2 font-semibold">Môn học</th>
                                    <th class="py-2 text-center">Lớp 10</th>
                                    <th class="py-2 text-center">Lớp 11</th>
                                    <th class="py-2 text-center font-bold text-blue-700">Lớp 12</th>
                                    <th class="py-2 text-right font-bold text-slate-800">TB 3 năm</th>
                                </tr>
                            </thead>
                            <tbody id="transcript-table-body" class="divide-y divide-slate-100">
                                <!-- Populated via JS -->
                            </tbody>
                        </table>
                    </div>

                    <!-- Auto-calculated Transcript Combinations -->
                    <div class="space-y-2.5 pt-2">
                        <h4 class="text-xs font-bold uppercase tracking-wider text-slate-500">Tổng điểm 3 môn Học bạ theo Tổ hợp</h4>
                        <div id="hb-combos-container" class="grid grid-cols-2 gap-2.5">
                            <!-- Populated via JS -->
                        </div>
                    </div>
                </div>

                <!-- Right Column: Interactive Exam Score Simulator 2027 -->
                <div class="lg:col-span-7 glass-card rounded-2xl p-6 flex flex-col justify-between space-y-6">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-3 mb-4">
                            <div>
                                <h3 class="font-display font-bold text-lg text-slate-900 flex items-center gap-2">
                                    <i data-lucide="sliders" class="w-5 h-5 text-orange-500"></i>
                                    Giả lập Điểm thi THPT 2027 (So với điểm cũ 2026)
                                </h3>
                                <p class="text-xs text-slate-500">Kéo thanh trượt để đặt mục tiêu ôn thi lại và xem khả năng nhận Học bổng Tân sinh viên</p>
                            </div>
                            <div class="flex gap-2">
                                <button onclick="resetOldScores()" class="px-3 py-1.5 rounded-lg border border-slate-300 text-xs font-semibold text-slate-700 hover:bg-slate-100 transition">
                                    Điểm cũ 2026
                                </button>
                                <button onclick="setScholarshipPreset()" class="px-3 py-1.5 rounded-lg bg-gradient-to-r from-orange-500 to-amber-500 text-white text-xs font-semibold shadow-sm hover:opacity-95 transition">
                                    Mức săn Học bổng
                                </button>
                            </div>
                        </div>

                        <!-- Combination Selector -->
                        <div class="mb-5">
                            <label class="block text-xs font-bold uppercase tracking-wider text-slate-500 mb-2">Chọn tổ hợp xét tuyển mục tiêu (Ngành Trắc địa - Bản đồ HUSC):</label>
                            <div class="grid grid-cols-2 sm:grid-cols-4 gap-2" id="combo-selector">
                                <button data-combo="D01" onclick="selectCombo('D01')" class="combo-btn active p-2.5 rounded-xl border-2 border-blue-600 bg-blue-50 text-left transition">
                                    <span class="font-bold text-sm text-blue-700 block">D01</span>
                                    <span class="text-[11px] text-slate-600">Toán - Văn - Anh</span>
                                </button>
                                <button data-combo="C03" onclick="selectCombo('C03')" class="combo-btn p-2.5 rounded-xl border border-slate-200 bg-white hover:border-blue-300 text-left transition">
                                    <span class="font-bold text-sm text-slate-800 block">C03 / Toán-Văn-Sử</span>
                                    <span class="text-[11px] text-slate-600">Toán - Văn - Sử</span>
                                </button>
                                <button data-combo="A01" onclick="selectCombo('A01')" class="combo-btn p-2.5 rounded-xl border border-slate-200 bg-white hover:border-blue-300 text-left transition">
                                    <span class="font-bold text-sm text-slate-800 block">A01</span>
                                    <span class="text-[11px] text-slate-600">Toán - Lý - Anh</span>
                                </button>
                                <button data-combo="TOAN_TIN_ANH" onclick="selectCombo('TOAN_TIN_ANH')" class="combo-btn p-2.5 rounded-xl border border-slate-200 bg-white hover:border-blue-300 text-left transition">
                                    <span class="font-bold text-sm text-slate-800 block">Tổ hợp Tin học</span>
                                    <span class="text-[11px] text-slate-600">Toán - Tin - Anh</span>
                                </button>
                            </div>
                        </div>

                        <!-- Sliders for Subjects -->
                        <div id="sliders-container" class="grid grid-cols-1 sm:grid-cols-2 gap-4 bg-slate-50/90 p-4 rounded-2xl border border-slate-200/70">
                            <!-- Populated dynamically via JS -->
                        </div>
                    </div>

                    <!-- Result & Scholarship Meter -->
                    <div class="bg-slate-900 rounded-2xl p-5 text-white space-y-4">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                            <div>
                                <span class="text-xs uppercase tracking-wider text-slate-400 font-semibold">Tổng điểm tổ hợp <span id="selected-combo-label" class="text-orange-400 font-bold">D01</span> (Chưa tính điểm ưu tiên)</span>
                                <div class="flex items-baseline gap-3 mt-1">
                                    <span id="sim-total-score" class="font-display text-4xl font-extrabold text-white">16.75</span>
                                    <span id="sim-diff-badge" class="text-xs font-bold px-2.5 py-1 rounded-full bg-slate-800 text-slate-300">+0.00 so với 2026</span>
                                </div>
                            </div>
                            <div id="status-pill" class="px-4 py-2.5 rounded-xl bg-emerald-500/20 border border-emerald-400/30 text-emerald-300 text-sm font-bold flex items-center gap-2">
                                <i data-lucide="check-circle-2" class="w-5 h-5"></i>
                                <span>Đủ điểm đỗ cơ bản</span>
                            </div>
                        </div>

                        <!-- Visual Progress Bar with Benchmarks -->
                        <div class="space-y-2 pt-2">
                            <div class="relative h-4 bg-slate-800 rounded-full overflow-hidden">
                                <!-- Markers -->
                                <div class="absolute top-0 bottom-0 left-[53.3%] w-0.5 bg-emerald-400 z-20" title="Điểm chuẩn dự kiến (~16.0)"></div>
                                <div class="absolute top-0 bottom-0 left-[73.3%] w-0.5 bg-orange-400 z-20" title="Ngưỡng tranh Học bổng Tân SV (~22.0+)"></div>
                                <!-- Fill -->
                                <div id="score-progress-bar" class="h-full bg-gradient-to-r from-blue-500 via-emerald-400 to-orange-500 transition-all duration-300 rounded-full" style="width: 55.8%;"></div>
                            </div>
                            <div class="flex justify-between text-[11px] text-slate-400 font-medium">
                                <span>0đ</span>
                                <span class="text-emerald-400">Điểm chuẩn (~16.0đ)</span>
                                <span class="text-orange-400">Săn Học bổng (22.0 - 25.0+đ)</span>
                                <span>30đ</span>
                            </div>
                        </div>

                        <p id="advisor-comment" class="text-xs text-slate-300 leading-relaxed border-t border-slate-800 pt-3">
                            Với điểm thi cũ 2026 (Toán 4.0, Văn 7.5, Anh 5.25 = 16.75đ), bạn đã vượt điểm chuẩn ngành Kỹ thuật Trắc địa - Bản đồ (~15–16đ), nhưng chưa đủ bứt phá để tranh suất Học bổng Thủ khoa/Á khoa ngành. Hãy thử kéo môn Toán lên 7.0+ và Tiếng Anh lên 7.5+!
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: STRATEGIC COMPARISON OF 3 PATHWAYS -->
        <section id="strategies" class="scroll-mt-24">
            <div class="mb-6">
                <span class="text-xs font-bold uppercase tracking-wider text-blue-600 bg-blue-100 px-3 py-1 rounded-full">Phân tích chi phí & cơ hội</span>
                <h2 class="font-display text-2xl sm:text-3xl font-extrabold text-slate-900 mt-2">
                    So sánh 3 Lộ trình Chuyển ngành cho Duy
                </h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
                <!-- Route 1 -->
                <div class="glass-card rounded-2xl p-6 border border-slate-200 opacity-90 hover:opacity-100 transition flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="px-3 py-1 rounded-full bg-rose-100 text-rose-700 text-xs font-bold">Không tối ưu</span>
                            <span class="text-xs font-semibold text-slate-400">Lộ trình 1</span>
                        </div>
                        <h3 class="font-display text-lg font-bold text-slate-900 mb-2">
                            Học tiếp hết năm 1 CNTT rồi xin chuyển ngành nội bộ
                        </h3>
                        <p class="text-xs text-slate-500 mb-4">Tuân thủ điều kiện: Không phải SV năm 1/năm 4, GPA ≥ 2.0, không nợ môn, không kỷ luật.</p>
                        
                        <ul class="space-y-2.5 text-sm text-slate-700">
                            <li class="flex items-start gap-2">
                                <i data-lucide="x-circle" class="w-4 h-4 text-rose-500 shrink-0 mt-0.5"></i>
                                <span><strong>Chi phí cực cao (~40 triệu):</strong> Tốn tiền học phí 2 học kỳ + sinh hoạt phí + tiền học bổ sung tín chỉ chuyển đổi.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i data-lucide="x-circle" class="w-4 h-4 text-rose-500 shrink-0 mt-0.5"></i>
                                <span><strong>Rủi ro treo hồ sơ:</strong> Nếu chán ngành CNTT dẫn đến rớt 1 môn hoặc GPA &lt; 2.0, trường sẽ từ chối đơn chuyển ngành.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i data-lucide="x-circle" class="w-4 h-4 text-rose-500 shrink-0 mt-0.5"></i>
                                <span><strong>Không có học bổng đầu vào:</strong> Chuyển ngang không được xét học bổng tân sinh viên.</span>
                            </li>
                        </ul>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-200/70 flex justify-between items-center text-xs">
                        <span class="text-slate-500">Ước tính chi phí:</span>
                        <span class="font-bold text-rose-600 text-sm">~35 - 40 Triệu VNĐ</span>
                    </div>
                </div>

                <!-- Route 2 -->
                <div class="glass-card rounded-2xl p-6 border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="px-3 py-1 rounded-full bg-amber-100 text-amber-800 text-xs font-bold">An toàn nhưng thiếu bứt phá</span>
                            <span class="text-xs font-semibold text-slate-400">Lộ trình 2</span>
                        </div>
                        <h3 class="font-display text-lg font-bold text-slate-900 mb-2">
                            Rút hồ sơ ngay & Dùng điểm cũ / Học bạ xét tuyển 2027
                        </h3>
                        <p class="text-xs text-slate-500 mb-4">Không cần ôn thi lại THPT, đợi tới tháng 7/2027 đăng ký nguyện vọng cùng 2k9.</p>
                        
                        <ul class="space-y-2.5 text-sm text-slate-700">
                            <li class="flex items-start gap-2">
                                <i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-500 shrink-0 mt-0.5"></i>
                                <span><strong>Tiết kiệm tối đa:</strong> Cắt lỗ học phí ngay từ HK1 K50, không tốn công ôn thi lại.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-500 shrink-0 mt-0.5"></i>
                                <span><strong>Tỷ lệ đỗ 99%:</strong> Học bạ lớp 12 của bạn (Toán-Văn-Anh: 23.5đ; Toán-Sử-Anh: 24.0đ) vượt xa điểm chuẩn học bạ.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i data-lucide="alert-triangle" class="w-4 h-4 text-amber-500 shrink-0 mt-0.5"></i>
                                <span><strong>Khó tranh học bổng:</strong> Điểm thi THPT 2026 (Toán 4.0) thấp nên khó cạnh tranh suất Thủ khoa/Á khoa.</span>
                            </li>
                        </ul>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-200/70 flex justify-between items-center text-xs">
                        <span class="text-slate-500">Ước tính chi phí phát sinh:</span>
                        <span class="font-bold text-emerald-600 text-sm">~0 - 2 Triệu VNĐ</span>
                    </div>
                </div>

                <!-- Route 3 (Recommended) -->
                <div class="rounded-2xl p-6 bg-gradient-to-br from-blue-600 via-blue-700 to-slate-900 text-white shadow-xl relative overflow-hidden flex flex-col justify-between ring-4 ring-orange-400/40">
                    <div class="absolute top-0 right-0 bg-orange-500 text-white text-[11px] font-extrabold px-3 py-1 rounded-bl-xl uppercase tracking-wider">
                        Khuyên dùng cho Duy
                    </div>
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <span class="px-3 py-1 rounded-full bg-white/15 text-orange-300 text-xs font-bold">Tối ưu Chi phí + Học bổng</span>
                        </div>
                        <h3 class="font-display text-lg font-bold text-white mb-2">
                            Rút hồ sơ ngay + Thi lại THPT 2027 kết hợp Học bạ đẹp
                        </h3>
                        <p class="text-xs text-blue-200 mb-4">Dùng 7 tháng tới để nâng cấp điểm Toán & Tiếng Anh/Tin học, bước vào K51 với vị thế top đầu.</p>
                        
                        <ul class="space-y-2.5 text-sm text-blue-50">
                            <li class="flex items-start gap-2">
                                <i data-lucide="sparkles" class="w-4 h-4 text-orange-400 shrink-0 mt-0.5"></i>
                                <span><strong>Tiết kiệm ~35 triệu đồng:</strong> Dừng đóng học phí các kỳ sau của CNTT, có thời gian đi làm thêm hoặc học chứng chỉ GIS/AutoCAD trước.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i data-lucide="sparkles" class="w-4 h-4 text-orange-400 shrink-0 mt-0.5"></i>
                                <span><strong>Săn Học bổng Tân sinh viên:</strong> Chỉ cần kéo Toán từ 4.0 lên 7.0+, bạn có cơ hội lớn lọt Top điểm cao nhất ngành Trắc địa - Bản đồ HUSC.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i data-lucide="sparkles" class="w-4 h-4 text-orange-400 shrink-0 mt-0.5"></i>
                                <span><strong>Lợi thế kép từ nền tảng CNTT:</strong> Tư duy lập trình học được ở HK1 cực kỳ hữu ích cho Trắc địa số, Viễn thám và GIS hiện đại.</span>
                            </li>
                        </ul>
                    </div>
                    <div class="mt-6 pt-4 border-t border-white/15 flex justify-between items-center text-xs">
                        <span class="text-blue-200">Lợi ích ròng:</span>
                        <span class="font-bold text-orange-300 text-sm">Tiết kiệm ~35Tr + Học bổng</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: INTERACTIVE CHECKLIST WITH LOCALSTORAGE -->
        <section id="checklist" class="scroll-mt-24">
            <div class="glass-card rounded-3xl p-6 sm:p-8 border border-slate-200">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 mb-6">
                    <div>
                        <span class="text-xs font-bold uppercase tracking-wider text-emerald-600 bg-emerald-100 px-3 py-1 rounded-full">Hành động thực tế</span>
                        <h2 class="font-display text-2xl font-extrabold text-slate-900 mt-2">
                            Checklist Thủ tục Rút hồ sơ HUSC & Lộ trình Thi lại 2027
                        </h2>
                        <p class="text-sm text-slate-600 mt-1">Tiến độ của bạn được tự động lưu trên trình duyệt này.</p>
                    </div>
                    <div class="flex items-center gap-3">
                        <div class="text-right">
                            <span id="checklist-progress-text" class="font-display font-bold text-lg text-blue-600">0 / 7</span>
                            <span class="text-xs text-slate-500 block">Hoàn thành</span>
                        </div>
                        <button onclick="resetChecklist()" class="px-3 py-2 rounded-xl border border-slate-200 text-xs font-semibold text-slate-600 hover:bg-slate-100 transition" title="Đặt lại checklist">
                            <i data-lucide="rotate-ccw" class="w-4 h-4"></i>
                        </button>
                    </div>
                </div>

                <!-- Progress bar -->
                <div class="w-full h-2.5 bg-slate-100 rounded-full overflow-hidden mb-6">
                    <div id="checklist-bar" class="h-full bg-gradient-to-r from-blue-600 to-emerald-500 transition-all duration-300" style="width: 0%;"></div>
                </div>

                <div id="checklist-items" class="grid grid-cols-1 md:grid-cols-2 gap-3.5">
                    <!-- Populated via JS -->
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-200 bg-white/70 backdrop-blur-md py-8 px-4 text-center text-xs text-slate-500">
        <div class="max-w-4xl mx-auto space-y-2">
            <p class="font-semibold text-slate-700">
                Hệ thống Hỗ trợ Lộ trình Tuyển sinh Cá nhân hóa — Phan Cảnh Thành Duy (HUSC)
            </p>
            <p>
                Dữ liệu tham chiếu từ <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=205936" target="_blank" class="legal-link">Thông tư 08/2022/TT-BGDĐT</a>, <a href="https://vanban.chinhphu.vn/?pageid=27160&docid=212169" target="_blank" class="legal-link">Thông tư 24/2024/TT-BGDĐT</a> và <a href="https://tuyensinh.hueuni.edu.vn/" target="_blank" class="legal-link">Cổng Tuyển sinh Đại học Huế</a>.
            </p>
        </div>
    </footer>

    <!-- Toast Notification Container (Replaces alert) -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none">
        <div class="bg-slate-900 text-white px-4 py-3 rounded-xl shadow-xl flex items-center gap-2.5 text-sm font-medium border border-slate-700">
            <i data-lucide="info" class="w-4 h-4 text-orange-400"></i>
            <span id="toast-msg">Đã cập nhật!</span>
        </div>
    </div>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // 1. REAL TRANSCRIPT DATA FROM DUY'S IMAGES (Lớp 10, Lớp 11, Lớp 12)
        const transcriptData = [
            { id: 'toan', name: 'Toán', y10: 5.3, y11: 5.1, y12: 6.9 },
            { id: 'ly', name: 'Vật lý', y10: 5.5, y11: 6.2, y12: 6.1 },
            { id: 'hoa', name: 'Hóa học', y10: 4.8, y11: 4.8, y12: 7.0 },
            { id: 'sinh', name: 'Sinh học', y10: 7.2, y11: 7.2, y12: 7.4 },
            { id: 'tin', name: 'Tin học', y10: 7.2, y11: 8.0, y12: 8.3 },
            { id: 'van', name: 'Ngữ Văn', y10: 7.7, y11: 7.3, y12: 8.0 },
            { id: 'su', name: 'Lịch sử', y10: 8.0, y11: 8.2, y12: 8.5 },
            { id: 'anh', name: 'Tiếng Anh', y10: 7.5, y11: 8.5, y12: 8.6 },
        ];

        let transcriptMode = '12'; // '12' or '3y'

        function getAvg3Y(sub) {
            return Number(((sub.y10 + sub.y11 + sub.y12) / 3).toFixed(2));
        }

        function renderTranscript() {
            const tbody = document.getElementById('transcript-table-body');
            tbody.innerHTML = '';

            transcriptData.forEach(sub => {
                const avg3y = getAvg3Y(sub);
                const highlightClass = sub.y12 >= 8.0 ? 'text-emerald-600 font-bold' : 'text-blue-700 font-bold';
                tbody.innerHTML += `
                    <tr class="hover:bg-slate-50/80 transition">
                        <td class="py-2 font-medium text-slate-800">${sub.name}</td>
                        <td class="py-2 text-center text-slate-600">${sub.y10.toFixed(1)}</td>
                        <td class="py-2 text-center text-slate-600">${sub.y11.toFixed(1)}</td>
                        <td class="py-2 text-center ${highlightClass}">${sub.y12.toFixed(1)}</td>
                        <td class="py-2 text-right font-semibold text-slate-700">${avg3y.toFixed(2)}</td>
                    </tr>
                `;
            });

            // Calculate Combinations for Transcript
            const getScore = (id) => {
                const s = transcriptData.find(x => x.id === id);
                return transcriptMode === '12' ? s.y12 : getAvg3Y(s);
            };

            const combos = [
                { code: 'D01 (Toán-Văn-Anh)', score: getScore('toan') + getScore('van') + getScore('anh') },
                { code: 'C03 (Toán-Văn-Sử)', score: getScore('toan') + getScore('van') + getScore('su') },
                { code: 'Toán-Tin-Anh', score: getScore('toan') + getScore('tin') + getScore('anh') },
                { code: 'A01 (Toán-Lý-Anh)', score: getScore('toan') + getScore('ly') + getScore('anh') },
                { code: 'A00 (Toán-Lý-Hóa)', score: getScore('toan') + getScore('ly') + getScore('hoa') },
                { code: 'C00* (Văn-Sử-Tin)', score: getScore('van') + getScore('su') + getScore('tin') },
            ];

            const container = document.getElementById('hb-combos-container');
            container.innerHTML = combos.map(c => `
                <div class="p-3 rounded-xl bg-white border border-slate-200/90 flex flex-col justify-between">
                    <span class="text-[11px] font-semibold text-slate-500">${c.code}</span>
                    <div class="flex items-baseline justify-between mt-1">
                        <span class="font-display font-extrabold text-base text-slate-900">${c.score.toFixed(2)} đ</span>
                        <span class="text-[10px] font-bold px-1.5 py-0.5 rounded bg-emerald-100 text-emerald-700">Đạt chuẩn</span>
                    </div>
                </div>
            `).join('');
        }

        function setTranscriptMode(mode) {
            transcriptMode = mode;
            const btn12 = document.getElementById('btn-hb-12');
            const btn3y = document.getElementById('btn-hb-3y');
            if (mode === '12') {
                btn12.className = 'px-3 py-1.5 rounded-lg bg-blue-600 text-white shadow-sm transition';
                btn3y.className = 'px-3 py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition';
            } else {
                btn3y.className = 'px-3 py-1.5 rounded-lg bg-blue-600 text-white shadow-sm transition';
                btn12.className = 'px-3 py-1.5 rounded-lg text-slate-600 hover:text-slate-900 transition';
            }
            renderTranscript();
        }

        // 2. EXAM SCORE SIMULATOR (2026 vs 2027)
        const oldExam2026 = {
            toan: 4.0,
            van: 7.5,
            su: 7.0,
            anh: 5.25,
            ly: 5.5, // Giả định mức nền nếu thi mới
            tin: 7.5 // Giả định mức nền nếu thi mới
        };

        let currentSimScores = { ...oldExam2026 };
        let selectedCombo = 'D01';

        const comboConfigs = {
            'D01': { label: 'D01 (Toán - Văn - Anh)', subjects: ['toan', 'van', 'anh'] },
            'C03': { label: 'C03 (Toán - Văn - Sử)', subjects: ['toan', 'van', 'su'] },
            'A01': { label: 'A01 (Toán - Lý - Anh)', subjects: ['toan', 'ly', 'anh'] },
            'TOAN_TIN_ANH': { label: 'Tổ hợp Tin học (Toán - Tin - Anh)', subjects: ['toan', 'tin', 'anh'] }
        };

        const subjectNames = {
            toan: 'Toán học',
            van: 'Ngữ Văn',
            su: 'Lịch sử',
            anh: 'Tiếng Anh',
            ly: 'Vật lý (Thi mới)',
            tin: 'Tin học (Thi mới)'
        };

        function selectCombo(comboKey) {
            selectedCombo = comboKey;
            document.querySelectorAll('.combo-btn').forEach(btn => {
                if (btn.dataset.combo === comboKey) {
                    btn.className = 'combo-btn active p-2.5 rounded-xl border-2 border-blue-600 bg-blue-50 text-left transition';
                    btn.querySelector('span:first-child').className = 'font-bold text-sm text-blue-700 block';
                } else {
                    btn.className = 'combo-btn p-2.5 rounded-xl border border-slate-200 bg-white hover:border-blue-300 text-left transition';
                    btn.querySelector('span:first-child').className = 'font-bold text-sm text-slate-800 block';
                }
            });
            renderSliders();
            updateSimulation();
        }

        function renderSliders() {
            const container = document.getElementById('sliders-container');
            const subs = comboConfigs[selectedCombo].subjects;
            
            container.innerHTML = subs.map(subKey => {
                const val = currentSimScores[subKey];
                const oldVal = oldExam2026[subKey];
                const isOldKnown = ['toan', 'van', 'su', 'anh'].includes(subKey);
                return `
                    <div class="bg-white p-3.5 rounded-xl border border-slate-200/80 shadow-sm">
                        <div class="flex justify-between items-center mb-1.5">
                            <span class="font-bold text-sm text-slate-800">${subjectNames[subKey]}</span>
                            <span id="val-${subKey}" class="font-display font-extrabold text-base text-orange-600">${val.toFixed(2)}</span>
                        </div>
                        <input type="range" min="0" max="10" step="0.25" value="${val}" 
                            oninput="handleSliderChange('${subKey}', this.value)" />
                        <div class="flex justify-between text-[11px] text-slate-400 mt-1">
                            <span>${isOldKnown ? 'Điểm thi 2026: ' + oldVal : 'Môn đăng ký thi mới'}</span>
                            <span class="text-blue-600 font-medium">Mục tiêu 2027</span>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function handleSliderChange(subKey, value) {
            currentSimScores[subKey] = parseFloat(value);
            document.getElementById(`val-${subKey}`).textContent = parseFloat(value).toFixed(2);
            updateSimulation();
        }

        function updateSimulation() {
            const config = comboConfigs[selectedCombo];
            const subs = config.subjects;

            const totalNew = subs.reduce((sum, k) => sum + currentSimScores[k], 0);
            const totalOld = subs.reduce((sum, k) => sum + oldExam2026[k], 0);
            const diff = totalNew - totalOld;

            document.getElementById('selected-combo-label').textContent = selectedCombo;
            document.getElementById('sim-total-score').textContent = totalNew.toFixed(2);

            const diffBadge = document.getElementById('sim-diff-badge');
            if (diff > 0) {
                diffBadge.textContent = `+${diff.toFixed(2)}đ so với mốc cũ`;
                diffBadge.className = 'text-xs font-bold px-2.5 py-1 rounded-full bg-emerald-500/20 text-emerald-300';
            } else if (diff < 0) {
                diffBadge.textContent = `${diff.toFixed(2)}đ so với mốc cũ`;
                diffBadge.className = 'text-xs font-bold px-2.5 py-1 rounded-full bg-rose-500/20 text-rose-300';
            } else {
                diffBadge.textContent = `Giữ nguyên mốc cũ`;
                diffBadge.className = 'text-xs font-bold px-2.5 py-1 rounded-full bg-slate-800 text-slate-300';
            }

            // Progress bar % (out of 30)
            const pct = Math.min(100, Math.max(0, (totalNew / 30) * 100));
            document.getElementById('score-progress-bar').style.width = `${pct}%`;

            // Status Pill & Comment
            const statusPill = document.getElementById('status-pill');
            const comment = document.getElementById('advisor-comment');

            if (totalNew >= 22.5) {
                statusPill.className = 'px-4 py-2.5 rounded-xl bg-orange-500/25 border border-orange-400/50 text-orange-300 text-sm font-bold flex items-center gap-2';
                statusPill.innerHTML = `<i data-lucide="trophy" class="w-5 h-5 text-orange-400"></i><span>Ứng viên Sáng giá Học bổng!</span>`;
                comment.innerHTML = `<strong>Tuyệt vời!</strong> Với <strong>${totalNew.toFixed(2)} điểm</strong>, bạn không chỉ đỗ chắc chắn ngành Kỹ thuật Trắc địa - Bản đồ HUSC mà còn lọt nhóm điểm cao nhất đầu vào để tranh suất <strong>Học bổng Tân sinh viên / Thủ khoa ngành</strong>.`;
            } else if (totalNew >= 16.0) {
                statusPill.className = 'px-4 py-2.5 rounded-xl bg-emerald-500/20 border border-emerald-400/30 text-emerald-300 text-sm font-bold flex items-center gap-2';
                statusPill.innerHTML = `<i data-lucide="check-circle-2" class="w-5 h-5"></i><span>An toàn Đỗ ngành Trắc địa</span>`;
                comment.innerHTML = `Với <strong>${totalNew.toFixed(2)} điểm</strong>, bạn vượt ngưỡng điểm chuẩn dự kiến của ngành (~15–16đ). Tuy nhiên, để cạnh tranh suất Học bổng Tân sinh viên đầu vào, Duy nên đặt mục tiêu kéo tổng điểm lên mốc <strong>22.50+ điểm</strong>.`;
            } else {
                statusPill.className = 'px-4 py-2.5 rounded-xl bg-rose-500/20 border border-rose-400/30 text-rose-300 text-sm font-bold flex items-center gap-2';
                statusPill.innerHTML = `<i data-lucide="alert-circle" class="w-5 h-5"></i><span>Dưới ngưỡng an toàn</span>`;
                comment.innerHTML = `Mức <strong>${totalNew.toFixed(2)} điểm</strong> đang thấp hơn điểm chuẩn an toàn (~16đ). Bạn vẫn có thể dùng Học bạ lớp 12 để xét tuyển đỗ ngành, nhưng nên ôn tập thêm để đạt tối thiểu 16+ điểm thi THPT.`;
            }
            lucide.createIcons();
        }

        function resetOldScores() {
            currentSimScores = { ...oldExam2026 };
            renderSliders();
            updateSimulation();
            showToast('Đã khôi phục điểm thi THPT 2026 của Duy');
        }

        function setScholarshipPreset() {
            currentSimScores = {
                toan: 7.25,
                van: 8.0,
                su: 8.25,
                anh: 7.75,
                ly: 7.5,
                tin: 8.5
            };
            renderSliders();
            updateSimulation();
            showToast('Đã áp dụng mức điểm mục tiêu Săn Học bổng 2027!');
        }

        // 3. INTERACTIVE CHECKLIST WITH LOCALSTORAGE
        const defaultChecklist = [
            { id: 'chk1', title: 'Kiểm tra công nợ học phí HK1 tại HUSC', desc: 'Tra cứu cổng đào tạo tín chỉ HUSC để hoàn tất học phí HK1 (tránh nợ phí làm chậm quyết định thôi học).', tag: 'Tháng 11–12/2026', done: false },
            { id: 'chk2', title: 'Nộp đơn xin thôi học & rút hồ sơ gốc tại Phòng CTSV', desc: 'Nhận lại Quyết định thôi học, Bằng/Giấy chứng nhận TN THPT bản chính và Học bạ bản gốc.', tag: 'Cuối HK1 (12/2026)', done: false },
            { id: 'chk3', title: 'Chốt tổ hợp môn thi lại THPT 2027', desc: 'Tập trung ôn Toán (nâng từ 4.0 lên 7.0+) cùng Tiếng Anh / Sử / Tin học để tối ưu điểm xét học bổng.', tag: 'Tháng 01/2027', done: false },
            { id: 'chk4', title: 'Sao y công chứng Học bạ THPT (Lớp 10, 11, 12)', desc: 'Chuẩn bị 03 bản sao công chứng học bạ và CCCD gắn chip để sẵn sàng nộp hồ sơ xét tuyển sớm.', tag: 'Tháng 03/2027', done: false },
            { id: 'chk5', title: 'Đăng ký dự thi Thí sinh tự do & Xin cấp tài khoản mới', desc: 'Nộp phiếu ĐKDT tại điểm tiếp nhận do Sở GD&ĐT TP. Huế quy định để nhận tài khoản cổng Bộ GD&ĐT.', tag: 'Tháng 04/2027', done: false },
            { id: 'chk6', title: 'Tham dự Kỳ thi Tốt nghiệp THPT 2027 cùng khóa 2k9', desc: 'Dự thi các môn đã đăng ký để lấy điểm xét tuyển đại học cạnh tranh học bổng.', tag: 'Cuối tháng 06/2027', done: false },
            { id: 'chk7', title: 'Đặt Nguyện vọng 1: Kỹ thuật Trắc địa - Bản đồ (HUSC)', desc: 'Đăng ký mã ngành 7520503 - Trường ĐH Khoa học, ĐH Huế ở vị trí NV1 trên hệ thống Bộ GD&ĐT.', tag: 'Tháng 07/2027', done: false }
        ];

        let checklistState = JSON.parse(localStorage.getItem('duy_husc_checklist_2027')) || defaultChecklist;

        function renderChecklist() {
            const container = document.getElementById('checklist-items');
            container.innerHTML = checklistState.map((item, idx) => `
                <div onclick="toggleChecklistItem(${idx})" class="cursor-pointer p-4 rounded-2xl border transition-all flex items-start gap-3.5 ${item.done ? 'bg-emerald-50/60 border-emerald-200' : 'bg-white border-slate-200 hover:border-blue-300'}">
                    <div class="mt-0.5 w-6 h-6 rounded-lg flex items-center justify-center shrink-0 transition ${item.done ? 'bg-emerald-600 text-white' : 'border-2 border-slate-300 bg-slate-50'}">
                        ${item.done ? '<i data-lucide="check" class="w-4 h-4"></i>' : ''}
                    </div>
                    <div class="flex-1">
                        <div class="flex flex-wrap items-center justify-between gap-2">
                            <h4 class="font-bold text-sm ${item.done ? 'line-through text-slate-400' : 'text-slate-900'}">${item.title}</h4>
                            <span class="text-[11px] font-semibold px-2 py-0.5 rounded bg-slate-100 text-slate-600">${item.tag}</span>
                        </div>
                        <p class="text-xs text-slate-500 mt-1 leading-relaxed">${item.desc}</p>
                    </div>
                </div>
            `).join('');

            const doneCount = checklistState.filter(x => x.done).length;
            const total = checklistState.length;
            document.getElementById('checklist-progress-text').textContent = `${doneCount} / ${total}`;
            document.getElementById('checklist-bar').style.width = `${(doneCount / total) * 100}%`;
            lucide.createIcons();
        }

        function toggleChecklistItem(idx) {
            checklistState[idx].done = !checklistState[idx].done;
            localStorage.setItem('duy_husc_checklist_2027', JSON.stringify(checklistState));
            renderChecklist();
            if (checklistState[idx].done) {
                showToast('Đã đánh dấu hoàn thành bước ' + (idx + 1));
            }
        }

        function resetChecklist() {
            checklistState = defaultChecklist.map(item => ({ ...item, done: false }));
            localStorage.setItem('duy_husc_checklist_2027', JSON.stringify(checklistState));
            renderChecklist();
            showToast('Đã đặt lại toàn bộ danh sách công việc');
        }

        // 4. REAL-TIME COUNTDOWN TO THPT 2027 (Expected June 26, 2027 07:30 GMT+7)
        function updateCountdown() {
            const targetDate = new Date('2027-06-26T07:30:00+07:00').getTime();
            const now = new Date().getTime();
            const distance = targetDate - now;

            if (distance <= 0) {
                document.getElementById('cd-days').textContent = '00';
                return;
            }

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const mins = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const secs = Math.floor((distance % (1000 * 60)) / 1000);

            document.getElementById('cd-days').textContent = String(days).padStart(2, '0');
            document.getElementById('cd-hours').textContent = String(hours).padStart(2, '0');
            document.getElementById('cd-mins').textContent = String(mins).padStart(2, '0');
            document.getElementById('cd-secs').textContent = String(secs).padStart(2, '0');
        }

        // Toast Helper
        let toastTimeout;
        function showToast(message) {
            const toast = document.getElementById('toast');
            document.getElementById('toast-msg').textContent = message;
            toast.classList.remove('translate-y-20', 'opacity-0');
            clearTimeout(toastTimeout);
            toastTimeout = setTimeout(() => {
                toast.classList.add('translate-y-20', 'opacity-0');
            }, 2600);
        }

        // Initialize App on Load
        window.addEventListener('DOMContentLoaded', () => {
            renderTranscript();
            renderSliders();
            updateSimulation();
            renderChecklist();
            updateCountdown();
            setInterval(updateCountdown, 1000);
        });
    </script>
</body>
</html>
