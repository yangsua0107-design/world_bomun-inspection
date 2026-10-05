[code_artifact (3).html](https://github.com/user-attachments/files/33043677/code_artifact.3.html)
<!DOCTYPE html>
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
        .delay-300 { animation-delay: 0.3s; }
    </style>
</head>
<body class="bg-white text-gray-800 antialiased">

    <nav class="fixed w-full z-50 top-0 bg-white shadow-md transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex-shrink-0 flex items-center cursor-pointer" onclick="window.scrollTo(0,0)">
                    <i class="fas fa-check-double text-blue-900 text-3xl mr-2"></i>
                    <span class="font-bold text-2xl text-blue-900 tracking-tight">월드검품소</span>
                </div>
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#home" class="text-gray-600 hover:text-blue-900 font-medium transition duration-300">Home</a>
                    <a href="#about" class="text-gray-600 hover:text-blue-900 font-medium transition duration-300">About</a>
                    <a href="#services" class="text-gray-600 hover:text-blue-900 font-medium transition duration-300">Services</a>
                    <a href="#global" class="text-gray-600 hover:text-blue-900 font-medium transition duration-300">Global Export</a>
                    <a href="#contact" class="bg-blue-900 text-white px-6 py-2 rounded-full font-medium hover:bg-blue-800 transition duration-300">Contact Us</a>
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
                완벽한 품질의 완성,<br>
                <span class="text-blue-600">월드검품소</span>가 함께합니다.
            </h1>
            <p class="text-lg md:text-xl text-gray-600 mb-10 max-w-2xl mx-auto fade-in-up delay-100">
                수십 년의 노하우와 철저한 시스템으로 당신의 브랜드 가치를 지킵니다. 최고 수준의 의류 품질 관리를 경험해보세요.
            </p>
            <div class="flex justify-center space-x-4 fade-in-up delay-200">
                <a href="#services" class="bg-blue-900 text-white px-8 py-3 rounded-full font-semibold text-lg hover:bg-blue-800 transition duration-300 shadow-lg">서비스 알아보기</a>
                <a href="#contact" class="bg-white text-blue-900 border-2 border-blue-900 px-8 py-3 rounded-full font-semibold text-lg hover:bg-blue-50 transition duration-300">상담 문의</a>
            </div>
        </div>
        <!-- 배경 장식용 패턴 -->
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 rounded-full bg-blue-100 opacity-50 blur-3xl"></div>
        <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 rounded-full bg-blue-200 opacity-50 blur-3xl"></div>
    </section>

    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center gap-12">
                <div class="lg:w-1/2">
                    <img src="u7118764141____--ar_9151_--edit_httpss.mj.runqAAIzKYEtwE_--v__de90c36d-1013-4e89-b4f2-61fb30025d20_2.jpg" alt="Apparel Inspection" class="rounded-2xl shadow-xl w-full object-cover h-[400px]">
                </div>
                <div class="lg:w-1/2 space-y-6">
                    <h4 class="text-blue-600 font-bold uppercase tracking-wider">About Us</h4>
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900">신뢰할 수 있는 의류 검품 파트너</h2>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        월드검품소는 고객의 소중한 제품이 최종 소비자에게 최상의 상태로 전달될 수 있도록 엄격하고 세밀한 검품 서비스를 제공합니다. 작은 불량 하나도 놓치지 않는 장인정신과 체계적인 데이터 관리 시스템을 통해, 국내외 수많은 패션 브랜드들의 든든한 품질 관리 파트너로 자리매김하고 있습니다.
                    </p>
                    <ul class="space-y-4 pt-4">
                        <li class="flex items-center text-gray-700">
                            <i class="fas fa-check-circle text-blue-600 mr-3 text-xl"></i>
                            <span class="font-medium">수십 년 경력의 전문 검품 요원 보유</span>
                        </li>
                        <li class="flex items-center text-gray-700">
                            <i class="fas fa-check-circle text-blue-600 mr-3 text-xl"></i>
                            <span class="font-medium">최신식 검침기 및 측정 장비 도입</span>
                        </li>
                        <li class="flex items-center text-gray-700">
                            <i class="fas fa-check-circle text-blue-600 mr-3 text-xl"></i>
                            <span class="font-medium">고객 맞춤형 리포트 및 신속한 피드백 제공</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h4 class="text-blue-600 font-bold uppercase tracking-wider mb-2">Our Services</h4>
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">체계적인 3단계 검품 시스템</h2>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition-shadow duration-300 border border-gray-100 group">
                    <div class="w-14 h-14 bg-blue-100 rounded-lg flex items-center justify-center mb-6 group-hover:bg-blue-900 transition-colors duration-300">
                        <i class="fas fa-search text-2xl text-blue-900 group-hover:text-white transition-colors duration-300"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">외관 검사 (Visual)</h3>
                    <p class="text-gray-600">오염, 이염, 봉제 불량, 원단 스크래치 등 제품의 외관상 결함을 꼼꼼하게 육안으로 검수합니다.</p>
                </div>
                
                <!-- Service 2 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition-shadow duration-300 border border-gray-100 group">
                    <div class="w-14 h-14 bg-blue-100 rounded-lg flex items-center justify-center mb-6 group-hover:bg-blue-900 transition-colors duration-300">
                        <i class="fas fa-magnet text-2xl text-blue-900 group-hover:text-white transition-colors duration-300"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">검침 (Needle Detection)</h3>
                    <p class="text-gray-600">고감도 컨베이어 검침기를 통과시켜 의류 내 잔류할 수 있는 부러진 바늘이나 금속 이물질을 완벽히 차단합니다.</p>
                </div>

                <!-- Service 3 (치수 검사 제거 후 포장만 남김) -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-xl transition-shadow duration-300 border border-gray-100 group">
                    <div class="w-14 h-14 bg-blue-100 rounded-lg flex items-center justify-center mb-6 group-hover:bg-blue-900 transition-colors duration-300">
                        <i class="fas fa-box-open text-2xl text-blue-900 group-hover:text-white transition-colors duration-300"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">포장 (Packaging)</h3>
                    <p class="text-gray-600">택 작업, 폴리백 포장, 박스 패킹 등 지정된 가이드라인에 맞춘 완벽한 완성 포장 출고를 지원합니다.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="global" class="py-20 bg-blue-900 text-white relative overflow-hidden">
        <div class="absolute right-0 top-0 opacity-10">
            <i class="fas fa-globe-asia text-[400px] transform translate-x-1/4 -translate-y-1/4"></i>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="lg:w-2/3">
                <h4 class="text-blue-300 font-bold uppercase tracking-wider mb-2">Global Export Standards</h4>
                <h2 class="text-3xl md:text-4xl font-bold mb-6">해외시장을 만족시키는<br>하이엔드 퀄리티 컨트롤</h2>
                <p class="text-blue-100 text-lg mb-8 leading-relaxed max-w-2xl">
                    글로벌 바이어가 요구하는 극도로 세밀하고 까다로운 검품 기준(AQL)을 완벽하게 충족합니다. 
                    수많은 해외 수출 브랜드들의 지정 검품소로 활약하며 쌓아온 독보적인 데이터와 노하우로, 
                    귀사의 글로벌 진출에 든든한 날개가 되어 드립니다.
                </p>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 bg-white text-center">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h4 class="text-blue-600 font-bold uppercase tracking-wider mb-2">Contact Us</h4>
            <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-6">상담 문의</h2>
            <p class="text-gray-600 text-lg mb-10">
                빠르고 편리한 카카오톡 상담을 이용해보세요.<br>
                아래 이미지를 확인하시고 QR코드를 스캔하시면 카카오톡 채널로 연결됩니다.
            </p>
            <div class="flex justify-center">
                <div class="inline-block max-w-sm hover:scale-105 transition-transform duration-300 shadow-2xl rounded-[32px] overflow-hidden border border-gray-100">
                    <img src="월드검품소 카톡프로필.jpg" alt="월드검품소 카카오톡 QR코드" class="w-full h-auto block">
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-900 text-white pt-20 pb-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12 mb-16">
                
                <!-- 회사 정보 -->
                <div class="lg:col-span-2">
                    <div class="flex items-center mb-6">
                        <i class="fas fa-check-double text-blue-400 text-3xl mr-2"></i>
                        <span class="font-bold text-2xl tracking-tight">월드검품소</span>
                    </div>
                    <p class="text-gray-400 mb-6 max-w-md">
                        최상의 품질을 향한 타협 없는 기준. 월드검품소가 고객님의 브랜드를 더욱 가치 있게 만들어 드립니다. 의뢰 상담 및 견적 문의를 환영합니다.
                    </p>
                    <a href="https://blog.naver.com/world_bomun" target="_blank" rel="noopener noreferrer" class="inline-flex items-center px-4 py-2 bg-gray-800 hover:bg-[#03C75A] text-gray-300 hover:text-white text-sm font-medium rounded-lg transition-colors border border-gray-700 hover:border-[#03C75A] group shadow-sm">
                        <span class="font-black text-[#03C75A] group-hover:text-white mr-2 text-base">N</span>
                        <span>네이버 블로그 방문하기</span>
                    </a>
                </div>

                <!-- 연락처 -->
                <div>
                    <h3 class="text-lg font-bold mb-6 border-b border-gray-700 pb-2">Contact Info</h3>
                    <ul class="space-y-4 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 mr-3 text-blue-400 w-5 text-center"></i>
                            <span>서울특별시 성북구 지봉로 178<br>세경빌딩2층 월드검품소</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone mt-1 mr-3 text-blue-400 w-5 text-center"></i>
                            <span>010-7378-8322</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope mt-1 mr-3 text-blue-400 w-5 text-center"></i>
                            <span>lux7101@naver.com</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-clock mt-1 mr-3 text-blue-400 w-5 text-center"></i>
                            <span>평일 09:30 - 18:00</span>
                        </li>
                    </ul>
                </div>

                <!-- 빠른 링크 -->
                <div>
                    <h3 class="text-lg font-bold mb-6 border-b border-gray-700 pb-2">Quick Links</h3>
                    <ul class="space-y-3 text-gray-400">
                        <li><a href="#home" class="hover:text-white transition-colors"><i class="fas fa-chevron-right text-xs mr-2 text-blue-400"></i>Home</a></li>
                        <li><a href="#about" class="hover:text-white transition-colors"><i class="fas fa-chevron-right text-xs mr-2 text-blue-400"></i>About Us</a></li>
                        <li><a href="#services" class="hover:text-white transition-colors"><i class="fas fa-chevron-right text-xs mr-2 text-blue-400"></i>Services</a></li>
                        <li><a href="#global" class="hover:text-white transition-colors"><i class="fas fa-chevron-right text-xs mr-2 text-blue-400"></i>Global Export</a></li>
                        <li><a href="#contact" class="hover:text-white transition-colors"><i class="fas fa-chevron-right text-xs mr-2 text-blue-400"></i>Contact</a></li>
                    </ul>
                </div>
            </div>

            <div class="border-t border-gray-800 pt-8 text-center text-gray-500 text-sm">
                <p>&copy; 2026 World Inspection. All rights reserved.</p>
            </div>
        </div>
    </footer>

</body>
</html>
