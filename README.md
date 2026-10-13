HTML
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>佳立彩藝有限公司 | In Color - 精密表面塗裝與點膠工藝</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;600;700&family=Noto+Sans+TC:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Space Grotesk', 'Noto Sans TC', sans-serif; background-color: #0b0f19; color: #f3f4f6; }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between selection:bg-blue-500 selection:text-white">

    <!-- Header / Nav -->
    <header class="border-b border-gray-800 bg-gray-950/80 backdrop-blur sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-3 h-3 bg-blue-500 rounded-full animate-pulse"></div>
                <span class="text-xl font-bold tracking-wider text-white">IN COLOR <span class="text-blue-400 font-light text-sm">佳立彩藝</span></span>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm text-gray-400 font-medium">
                <a href="#services" class="hover:text-white transition">核心工藝</a>
                <a href="#precision" class="hover:text-white transition">物理極限與品質</a>
                <a href="#contact" class="hover:text-white transition">業務聯絡</a>
            </nav>
            <a href="#contact" class="bg-blue-600 hover:bg-blue-500 text-white px-5 py-2.5 rounded-lg text-sm font-semibold transition shadow-lg shadow-blue-600/20">
                立即洽詢
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative overflow-hidden py-24 md:py-32 border-b border-gray-900">
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="max-w-3xl">
                <div class="inline-flex items-center space-x-2 bg-blue-950/60 border border-blue-800/60 px-3.5 py-1.5 rounded-full text-blue-400 text-xs font-semibold uppercase tracking-wider mb-6">
                    <span>Precision Surface Finishing</span>
                </div>
                <h1 class="text-4xl md:text-6xl font-bold tracking-tight text-white leading-tight mb-6">
                    拒絕空談，用手藝與參數<br><span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-indigo-300">定義表面工藝的極致。</span>
                </h1>
                <p class="text-lg text-gray-400 mb-10 leading-relaxed font-light">
                    深耕台灣在地，專注於環氧樹脂點膠、特種漆料調配、精密表面塗裝與微觀填墨入色。不玩虛浮口號，用最扎實的工匠手感與良率，為您的產品賦予完美靈魂。
                </p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="#services" class="bg-white text-gray-950 hover:bg-gray-200 px-8 py-4 rounded-xl font-semibold text-center transition">
                        探索核心工藝
                    </a>
                    <a href="#contact" class="border border-gray-700 hover:border-gray-500 text-white px-8 py-4 rounded-xl font-semibold text-center transition">
                        聯絡我們 (INCOLOR)
                    </a>
                </div>
            </div>
        </div>
        <div class="absolute right-0 top-1/2 -translate-y-1/2 w-96 h-96 bg-blue-600/10 rounded-full blur-3xl pointer-events-none"></div>
    </section>

    <!-- Services Grid -->
    <section id="services" class="py-24 bg-gray-950">
        <div class="max-w-7xl mx-auto px-6">
            <div class="mb-16">
                <h2 class="text-2xl md:text-3xl font-bold text-white mb-3">核心專業項目</h2>
                <p class="text-gray-400 text-sm">以第一性原理把關每一道化學與物理表面工序。</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-gray-900/60 border border-gray-800 p-8 rounded-2xl hover:border-blue-500/50 transition">
                    <div class="w-10 h-10 bg-blue-600/20 border border-blue-500/30 rounded-xl flex items-center justify-center text-blue-400 font-bold mb-6">01</div>
                    <h3 class="text-xl font-bold text-white mb-3">精密點膠與填墨入色</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        針對服飾配件、金屬飾品與精密電子零件，提供高精度的環氧樹脂點膠與填墨入色，確保邊緣俐落、無溢膠、附著力達最高標準。
                    </p>
                </div>
                <!-- Card 2 -->
                <div class="bg-gray-900/60 border border-gray-800 p-8 rounded-2xl hover:border-blue-500/50 transition">
                    <div class="w-10 h-10 bg-blue-600/20 border border-blue-500/30 rounded-xl flex items-center justify-center text-blue-400 font-bold mb-6">02</div>
                    <h3 class="text-xl font-bold text-white mb-3">特種漆料調配與點漆</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        結合老師傅數十年調色手感與精準參數，應對 AC 漆、PU 漆及各類特種化學塗料，精準還原色彩與特殊視覺質感。
                    </p>
                </div>
                <!-- Card 3 -->
                <div class="bg-gray-900/60 border border-gray-800 p-8 rounded-2xl hover:border-blue-500/50 transition">
                    <div class="w-10 h-10 bg-blue-600/20 border border-blue-500/30 rounded-xl flex items-center justify-center text-blue-400 font-bold mb-6">03</div>
                    <h3 class="text-xl font-bold text-white mb-3">表面塗裝與美學加工</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        專注於表面質感處理與化學塗層防護，從工件前處理到最終烘烤固化，嚴格把關每一件成品的物理穩定度。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Footer -->
    <footer id="contact" class="bg-gray-900 border-t border-gray-800 py-16">
        <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12">
            <div>
                <h3 class="text-2xl font-bold text-white mb-4">佳立彩藝有限公司 (In Color)</h3>
                <p class="text-gray-400 text-sm mb-6 leading-relaxed">
                    少說廢話，做就對了。我們用最高標準的工藝良率與實體執行力，期待與各界優秀夥伴合作。
                </p>
                <div class="text-sm text-gray-300 space-y-2">
                    <p><span class="text-gray-500">地址：</span>桃園市龜山區</p>
                    <p><span class="text-gray-500">網域：</span>www.incolor.com.tw</p>
                </div>
            </div>
            <div class="bg-gray-950 p-8 rounded-2xl border border-gray-800 flex flex-col justify-between">
                <div>
                    <h4 class="text-lg font-bold text-white mb-2">準備好升級您的產品表面工藝了嗎？</h4>
                    <p class="text-gray-400 text-sm mb-6">直接將您的需求與規格傳給我們，我們用實體成果說話。</p>
                </div>
                <div class="bg-blue-950/40 border border-blue-800/40 p-4 rounded-xl text-blue-300 text-sm font-medium text-center">
                    聯絡信箱 / 專線洽詢：請透過現有老客戶對接或直接與我們聯繫
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-6 mt-12 pt-8 border-t border-gray-800/60 text-center text-xs text-gray-500">
            &copy; 2026 佳立彩藝有限公司 (In Color). All Rights Reserved. Powered by AI & First Principles.
        </div>
    </footer>

</body>
</html>
