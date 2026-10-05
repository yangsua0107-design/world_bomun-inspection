
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>월드검품소 | World Inspection</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
        
        body {
            font-family: 'Pretendard', sans-serif;
            scroll-behavior: smooth;
        }
        
        .fade-in-up {
            animation: fadeInUp 0.8s ease-out forwards;
            opacity: 0;
            transform: translateY(20px);
        }

        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .delay-100 { animation-delay: 0.1s; }
        .delay-200 { animation-delay: 0.2s; }
    </style>
</head>
<body class="bg-white text-gray-800 antialiased overflow-x-hidden">

    <!-- 상단 네비게이션 바 (잘림 현상 해결) -->
    <nav class="fixed w-full z-50 top-0 bg-white shadow-md transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex-shrink-0 flex items-center cursor-pointer" onclick="window.scrollTo(0,0)">
                    <i class="fas fa-check-double text-blue-900 text-3xl mr-2"></i>
                    <span class="font-bold text-xl md:text-2xl text-blue-900 tracking-tight">월드검품소</span>
                </div>
                <!-- 메뉴 간격(space-x) 및 폰트 사이즈 반응형 적용 -->
                <div class="hidden md:flex space-x-4 lg:space-x-8 items-center">
                    <a href="#home" class="text-gray-600 hover:text-blue-900 font-medium text-sm lg:text-base transition duration-300 whitespace-nowrap">Home</a>
                    <a href="#about" class="text-gray-600 hover:text-blue-900 font-medium text-sm lg:text-base transition duration-300 whitespace-nowrap">About</a>
                    <a href="#services" class="text-gray-600 hover:text-blue-900 font-medium text-sm lg:text-base transition duration-300 whitespace-nowrap">Services</a>
                    <a href="#global" class="text-gray-600 hover:text-blue-900 font-medium text-sm lg:text-base transition duration-300 whitespace-nowrap">Global Export</a>
                    <a href="#contact" class="bg-blue-900 text-white px-4 lg:px-6 py-2 rounded-full font-medium hover:bg-blue-800 transition duration-300 shadow-sm text-sm lg:text-base whitespace-nowrap">Contact Us</a>
                </div>
                <!-- Mobile menu button -->
                <div class="md:hidden flex items-center">
                    <button class="text-gray-600 hover:text-blue-900 focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <section id="home" class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 bg-blue-50 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-blue-900 leading-tight mb-6 fade-in-up">
                성공적인 비즈니스를 위한<br>
                <span class="text-blue-600">완벽한 품질 컨트롤</span>
            </h1>
            <p class="text-lg md:text-xl text-gray-600 mb-10 max-w-2xl mx-auto fade-in-up delay-100">
                수년간 축적된 노하우와 철저한 검품 시스템으로<br class="hidden md:block">
                고객님의 소중한 브랜드 가치를 높여드립니다.
            </p>
            <div class="flex justify-center space-x-4 fade-in-up delay-200">
                <a href="#contact" class="bg-blue-900 text-white px-8 py-3 rounded-full font-semibold text-lg hover:bg-blue-800 transition duration-300 shadow-lg whitespace-nowrap">의뢰 상담하기</a>
            </div>
        </div>
        <!-- Background decoration -->
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 rounded-full bg-blue-100 opacity-50 blur-3xl"></div>
        <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 rounded-full bg-blue-200 opacity-50 blur-3xl"></div>
    </section>

    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center gap-12">
                <div class="lg:w-1/2 w-full">
                    <img src="inspection.jpg" alt="월드검품소 작업장 환경" class="rounded-2xl shadow-xl w-full object-cover aspect-[4/3]">
                </div>
                <div class="lg:w-1/2 w-full space-y-6">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 border-b-2 border-blue-900 pb-2 inline-block">Apparel Inspection</h2>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        월드검품소는 다년간의 검품 노하우를 바탕으로, 의류 검품에 가장 최적화된 밝고 청결한 작업 환경을 구축하고 있습니다. 
                        전문 검품 인력이 투입되어 미세한 불량 하나까지 놓치지 않고 완벽하게 선별합니다.
                    </p>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        단순한 불량 체크를 넘어 출고 전 최종 마감까지 책임지며, 최상의 퀄리티로 제품이 유통될 수 있도록 꼼꼼하게 관리합니다.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">체계적인 3단계 검품 시스템</h2>
                <p class="text-gray-500 text-lg">타협 없는 기준으로 진행되는 월드검품소만의 프로세스입니다.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- 1단계 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition duration-300 border border-gray-100 text-center">
                    <div class="w-16 h-16 bg-blue-100 text-blue-900 rounded-full flex items-center justify-center text-2xl font-bold mx-auto mb-6">1</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">외관 및 오염 검사</h3>
                    <p class="text-gray-600">원단의 이색, 미세한 오염, 스크래치 등 외부적인 결함을 밝은 조명 아래서 꼼꼼하게 확인합니다.</p>
                </div>
                
                <!-- 2단계 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition duration-300 border border-gray-100 text-center">
                    <div class="w-16 h-16 bg-blue-100 text-blue-900 rounded-full flex items-center justify-center text-2xl font-bold mx-auto mb-6">2</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">봉제 상태 검사</h3>
                    <p class="text-gray-600">땀수, 땀뜀, 봉제선 틀어짐, 실밥 처리 등 전체적인 의류의 완성도와 봉제 퀄리티를 엄격하게 체크합니다.</p>
                </div>

                <!-- 3단계 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition duration-300 border border-gray-100 text-center">
                    <div class="w-16 h-16 bg-blue-100 text-blue-900 rounded-full flex items-center justify-center text-2xl font-bold mx-auto mb-6">3</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">포장 및 최종 확인</h3>
                    <p class="text-gray-600">메인 라벨 및 케어 라벨 부착 상태, 폴리백 포장 등 바이어에게 출고되기 전 마지막 상태를 완벽하게 점검합니다.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="global" class="py-20 bg-white">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">해외시장을 만족시키는 하이엔드 퀄리티</h2>
            <p class="text-gray-600 text-lg leading-relaxed">
                월드검품소는 가장 까다로운 일본 바이어들의 기준까지 완벽하게 충족시키는 정밀한 검품 서비스를 제공하고 있습니다. 
                글로벌 스탠다드에 맞춘 철저한 품질 관리 시스템을 통해 고객사의 성공적인 해외 수출과 안정적인 비즈니스를 든든하게 지원합니다.
            </p>
        </div>
    </section>

    <section id="contact" class="py-20 bg-blue-900">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">빠르고 간편한 상담 문의</h2>
            <p class="text-blue-200 mb-10 text-lg">스마트폰 카메라로 QR코드를 스캔하여 카카오톡으로 편하게 문의주세요.</p>
            
            <div class="bg-white p-8 rounded-3xl shadow-2xl inline-block max-w-sm w-full mx-auto transform hover:scale-105 transition-transform duration-300">
                <img src="kakao.jpg" alt="월드검품소 카카오톡 QR코드" class="w-full h-auto rounded-xl block">
                <p class="mt-6 text-gray-800 font-bold text-xl">카카오톡 채널: 월드검품소</p>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-white py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-2 gap-12">
            
            <!-- Company Intro & Blog Link -->
            <div>
                <h3 class="text-2xl font-bold mb-4 flex items-center tracking-tight">
                    <i class="fas fa-check-double text-blue-500 mr-2"></i>
                    월드검품소
                </h3>
                <p class="text-gray-400 mb-6 leading-relaxed max-w-md">
                    최상의 품질을 향한 타협 없는 기준. 월드검품소가 고객님의 브랜드를 더욱 가치 있게 만들어 드립니다. 의뢰 상담 및 견적 문의를 환영합니다.
                </p>
                <a href="https://blog.naver.com/world_bomun" target="_blank" rel="noopener noreferrer" class="inline-flex items-center px-4 py-2 bg-gray-800 hover:bg-[#03C75A] text-gray-300 hover:text-white text-sm font-medium rounded-lg transition-colors border border-gray-700 hover:border-[#03C75A] group shadow-sm">
                    <span class="font-black text-[#03C75A] group-hover:text-white mr-2 text-base">N</span>
                    <span>네이버 블로그 바로가기</span>
                </a>
            </div>

            <!-- Contact Info -->
            <div>
                <h4 class="text-lg font-bold mb-6 text-gray-100 border-b border-gray-700 pb-2 inline-block">Contact Info</h4>
                <ul class="text-gray-400 space-y-4">
                    <li class="flex items-start">
                        <span class="text-gray-200 font-semibold w-24 flex-shrink-0">위치</span>
                        <span>서울특별시 성북구 지봉로 178 세경빌딩2층 월드검품소</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-gray-200 font-semibold w-24 flex-shrink-0">전화번호</span>
                        <span>010-7378-8322</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-gray-200 font-semibold w-24 flex-shrink-0">이메일</span>
                        <span>lux7101@naver.com</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-gray-200 font-semibold w-24 flex-shrink-0">시간</span>
                        <span>평일09:30 - 18:00</span>
                    </li>
                </ul>
            </div>
            
        </div>
        
        <div class="max-w-7xl mx-auto px-4 mt-12 pt-8 border-t border-gray-800 text-center text-gray-500 text-sm">
            &copy; 2026 월드검품소. All rights reserved.
        </div>
    </footer>

</body>
</html>
