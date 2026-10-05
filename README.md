[code_artifact (5).html](https://github.com/user-attachments/files/33044371/code_artifact.5.html)
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>월드검품소 - 최상의 품질을 위한 타협 없는 기준</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Custom Tailwind Configuration -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            800: '#1e3a5f',
                            900: '#0f172a',
                        },
                        brand: {
                            blue: '#2563eb',
                            light: '#f8fafc',
                        }
                    },
                    fontFamily: {
                        sans: ['"Pretendard"', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    
    <style>
        @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
        html { scroll-behavior: smooth; }
        body { font-family: 'Pretendard', sans-serif; }
    </style>
</head>
<body class="text-gray-800 bg-white antialiased">

    <nav class="fixed w-full z-50 top-0 bg-white shadow-sm border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center cursor-pointer" onclick="window.scrollTo(0,0)">
                    <i class="fa-solid fa-check-double text-brand-blue text-2xl mr-2"></i>
                    <span class="text-2xl font-extrabold text-navy-900 tracking-tight">월드검품소</span>
                </div>
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#home" class="text-gray-600 hover:text-brand-blue font-semibold transition">Home</a>
                    <a href="#about" class="text-gray-600 hover:text-brand-blue font-semibold transition">About</a>
                    <a href="#services" class="text-gray-600 hover:text-brand-blue font-semibold transition">Services</a>
                    <a href="#export" class="text-gray-600 hover:text-brand-blue font-semibold transition">Global Export</a>
                    <a href="#contact" class="bg-navy-900 text-white hover:bg-navy-800 px-6 py-2.5 rounded-full font-semibold transition shadow-md">Contact Us</a>
                </div>
            </div>
        </div>
    </nav>

    <section id="home" class="pt-32 pb-20 lg:pt-48 lg:pb-32 bg-brand-light relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-navy-900 mb-6 leading-tight tracking-tight">
                성공적인 비즈니스를 위한<br>
                <span class="text-brand-blue">완벽한 품질 컨트롤</span>
            </h1>
            <p class="text-lg md:text-xl text-gray-600 mb-10 max-w-2xl mx-auto leading-relaxed">
                수년간 축적된 노하우와 철저한 검품 시스템으로<br class="hidden md:block">
                고객님의 소중한 브랜드 가치를 높여드립니다.
            </p>
            <a href="#contact" class="inline-block bg-navy-900 text-white text-lg font-semibold px-8 py-4 rounded-full hover:bg-navy-800 transition shadow-lg transform hover:-translate-y-1">
                의뢰 상담하기
            </a>
        </div>
        <!-- Decorative Background -->
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 rounded-full bg-blue-100 opacity-50 blur-3xl"></div>
    </section>

    <section id="about" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center gap-12 lg:gap-20">
                <!-- Image Container -->
                <div class="w-full lg:w-1/2">
                    <div class="rounded-2xl overflow-hidden shadow-2xl relative">
                        <img src="u7118764141____--ar_9151_--edit_httpss.mj.runqAAIzKYEtwE_--v__de90c36d-1013-4e89-b4f2-61fb30025d20_2 (1).jpg" 
                             alt="월드검품소 작업장 환경" 
                             class="w-full h-[400px] object-cover hover:scale-105 transition-transform duration-700">
                    </div>
                </div>
                <!-- Text Container -->
                <div class="w-full lg:w-1/2">
                    <h4 class="text-brand-blue font-bold tracking-wider uppercase mb-2">About Us</h4>
                    <h2 class="text-3xl md:text-4xl font-bold text-navy-900 mb-6">Apparel Inspection</h2>
                    <p class="text-gray-600 leading-relaxed text-lg mb-6">
                        월드검품소는 다년간의 검품 노하우를 바탕으로, 의류 검품에 가장 최적화된 밝고 청결한 작업 환경을 구축하고 있습니다. 전문 검품 인력이 투입되어 미세한 불량 하나까지 놓치지 않고 완벽하게 선별합니다.
                    </p>
                    <p class="text-gray-600 leading-relaxed text-lg">
                        단순한 불량 체크를 넘어 출고 전 최종 마감까지 책임지며, 최상의 퀄리티로 제품이 유통될 수 있도록 꼼꼼하게 관리합니다.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-24 bg-brand-light">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h4 class="text-brand-blue font-bold tracking-wider uppercase mb-2">Our Services</h4>
                <h2 class="text-3xl md:text-4xl font-bold text-navy-900 mb-4">체계적인 3단계 검품 시스템</h2>
                <p class="text-gray-500 text-lg">타협 없는 기준으로 진행되는 월드검품소만의 프로세스입니다.</p>
            </div>
            
            <!-- 3 Column Grid -->
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Step 1 -->
                <div class="bg-white p-10 rounded-2xl shadow-sm border border-gray-100 hover:shadow-xl transition-all duration-300 text-center group">
                    <div class="w-20 h-20 bg-blue-50 text-brand-blue rounded-full flex items-center justify-center text-3xl font-black mx-auto mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">1</div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-4">외관 및 오염 검사</h3>
                    <p class="text-gray-600 leading-relaxed">원단의 이색, 미세한 오염, 스크래치 등 외부적인 결함을 밝은 조명 아래서 꼼꼼하게 확인합니다.</p>
                </div>
                <!-- Step 2 -->
                <div class="bg-white p-10 rounded-2xl shadow-sm border border-gray-100 hover:shadow-xl transition-all duration-300 text-center group">
                    <div class="w-20 h-20 bg-blue-50 text-brand-blue rounded-full flex items-center justify-center text-3xl font-black mx-auto mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">2</div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-4">봉제 상태 검사</h3>
                    <p class="text-gray-600 leading-relaxed">땀수, 땀뜀, 봉제선 틀어짐, 실밥 처리 등 전체적인 의류의 완성도와 봉제 퀄리티를 엄격하게 체크합니다.</p>
                </div>
                <!-- Step 3 -->
                <div class="bg-white p-10 rounded-2xl shadow-sm border border-gray-100 hover:shadow-xl transition-all duration-300 text-center group">
                    <div class="w-20 h-20 bg-blue-50 text-brand-blue rounded-full flex items-center justify-center text-3xl font-black mx-auto mb-6 group-hover:bg-brand-blue group-hover:text-white transition-colors">3</div>
                    <h3 class="text-2xl font-bold text-navy-900 mb-4">포장 및 최종 확인</h3>
                    <p class="text-gray-600 leading-relaxed">메인 라벨 및 케어 라벨 부착 상태, 폴리백 포장 등 바이어에게 출고되기 전 마지막 상태를 완벽하게 점검합니다.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="export" class="py-24 bg-navy-900 text-white relative">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center relative z-10">
            <h4 class="text-brand-blue font-bold tracking-wider uppercase mb-2">Global Export</h4>
            <h2 class="text-3xl md:text-4xl font-bold mb-8">해외시장을 만족시키는 하이엔드 퀄리티</h2>
            <p class="text-gray-300 text-lg md:text-xl leading-relaxed">
                월드검품소는 가장 까다로운 해외 바이어들의 기준까지 완벽하게 충족시키는 정밀한 검품 서비스를 제공하고 있습니다. 글로벌 스탠다드에 맞춘 철저한 품질 관리 시스템을 통해 고객사의 성공적인 해외 수출과 안정적인 비즈니스를 든든하게 지원합니다.
            </p>
        </div>
    </section>

    <section id="contact" class="py-24 bg-white text-center">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h4 class="text-brand-blue font-bold tracking-wider uppercase mb-2">Contact Us</h4>
            <h2 class="text-3xl md:text-4xl font-bold text-navy-900 mb-4">빠르고 간편한 상담 문의</h2>
            <p class="text-gray-600 text-lg mb-12">스마트폰 카메라로 아래 QR코드를 스캔하여 카카오톡으로 편하게 문의주세요.</p>
            
            <div class="inline-block bg-white p-6 rounded-3xl shadow-[0_20px_50px_rgba(0,0,0,0.1)] border border-gray-100 transform transition-transform hover:-translate-y-2">
                <img src="월드검품소 카톡프로필.jpg" alt="월드검품소 카카오톡 상담" class="w-72 sm:w-80 h-auto rounded-2xl mx-auto block">
                <div class="mt-6 flex items-center justify-center space-x-2">
                    <div class="w-8 h-8 bg-yellow-400 rounded-full flex items-center justify-center">
                        <i class="fa-solid fa-comment text-brown-900 text-sm"></i>
                    </div>
                    <p class="text-gray-900 font-bold text-xl">카카오톡 채널: 월드검품소</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-white pt-20 pb-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
                
                <!-- Company Info & Naver Blog -->
                <div class="space-y-6">
                    <div class="flex items-center">
                        <i class="fa-solid fa-check-double text-brand-blue text-2xl mr-2"></i>
                        <span class="text-3xl font-extrabold tracking-tight text-white">월드검품소</span>
                    </div>
                    <p class="text-gray-400 text-lg leading-relaxed max-w-md">
                        최상의 품질을 향한 타협 없는 기준.<br>월드검품소가 고객님의 브랜드를 더욱 가치 있게 만들어 드립니다.
                    </p>
                    <div>
                        <a href="https://blog.naver.com/world_bomun" target="_blank" rel="noopener noreferrer" class="inline-flex items-center space-x-2 bg-gray-800 hover:bg-[#03C75A] text-gray-300 hover:text-white px-5 py-3 rounded-lg transition-colors border border-gray-700 hover:border-[#03C75A] group shadow-sm">
                            <span class="font-black text-[#03C75A] group-hover:text-white text-lg">N</span>
                            <span class="font-medium">네이버 블로그 방문하기</span>
                        </a>
                    </div>
                </div>

                <!-- Contact Info -->
                <div class="bg-gray-800/50 p-8 rounded-2xl">
                    <h3 class="text-xl font-bold mb-6 border-b border-gray-700 pb-4">Contact Info</h3>
                    <ul class="space-y-5 text-gray-300">
                        <li class="flex items-start">
                            <i class="fa-solid fa-map-location-dot mt-1 mr-4 text-brand-blue w-5 text-center"></i>
                            <span class="leading-relaxed">서울특별시 성북구 지봉로 178<br>세경빌딩 2층 월드검품소</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fa-solid fa-phone mr-4 text-brand-blue w-5 text-center"></i>
                            <span class="font-medium">010-7378-8322</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fa-solid fa-envelope mr-4 text-brand-blue w-5 text-center"></i>
                            <span>lux7101@naver.com</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fa-solid fa-clock mr-4 text-brand-blue w-5 text-center"></i>
                            <span>평일 09:30 - 18:00</span>
                        </li>
                    </ul>
                </div>
            </div>

            <!-- Copyright -->
            <div class="border-t border-gray-800 pt-8 text-center text-gray-500 text-sm">
                <p>&copy; 2026 월드검품소. All rights reserved.</p>
            </div>
        </div>
    </footer>

</body>
</html>
