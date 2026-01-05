<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UH 2.0 | 氫能航空動力專家</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;700&display=swap');
        body { font-family: 'Noto Sans TC', sans-serif; background-color: #f8fafc; color: #1e293b; scroll-behavior: smooth; }
        .hero-bg { background: linear-gradient(135deg, #0f172a 0%, #1e40af 100%); position: relative; overflow: hidden; }
        .data-card { background: white; border-radius: 16px; border: 1px solid #e2e8f0; transition: all 0.3s ease; }
        .data-card:hover { transform: translateY(-5px); box-shadow: 0 15px 30px -10px rgba(0,0,0,0.1); border-color: #3b82f6; }
        .reveal { opacity: 0; transform: translateY(30px); transition: all 0.8s ease-out; }
        .reveal.active { opacity: 1; transform: translateY(0); }
        .highlight { color: #3b82f6; font-weight: bold; }
    </style>
</head>
<body>

    <nav class="bg-white/80 backdrop-blur-md border-b sticky top-0 z-50 px-8 py-4">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <span class="text-xl font-bold tracking-tight text-slate-800">UH 2.0 <span class="text-blue-600">Aviation</span></span>
            <div class="space-x-8 text-sm font-medium">
                <a href="#vision" class="hover:text-blue-600">核心願景</a>
                <a href="#tech" class="hover:text-blue-600">技術實力</a>
                <a href="#market" class="hover:text-blue-600">市場路徑</a>
            </div>
        </div>
    </nav>

    <header id="vision" class="hero-bg text-white py-24 px-6 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-5xl md:text-6xl font-bold mb-8 leading-tight">
                引領下一代 <span class="text-blue-400">液態氫</span> <br>eVTOL 動力革命
            </h1>
            <p class="text-xl text-blue-100 mb-12 font-light">
                我們致力於為 eVTOL（電動空中出租車）提供 LH2 儲存與燃料電池動力系統 [cite: 3]。
            </p>
            <div class="flex flex-wrap justify-center gap-6">
                <div class="bg-white/10 px-6 py-3 rounded-full border border-white/20">TRL 6-7 技術驗證 [cite: 12]</div>
                <div class="bg-white/10 px-6 py-3 rounded-full border border-white/20">專注高增長 eVTOL 市場 [cite: 3]</div>
            </div>
        </div>
    </header>

    <section class="py-20 px-6 max-w-4xl mx-auto text-center reveal">
        <h2 class="text-3xl font-bold mb-6">為什麼是現在？為什麼是液態氫？</h2>
        <p class="text-lg text-slate-600 leading-relaxed">
            對於實際的航程需求，電池過重，而氣態氫體積過於龐大 [cite: 7]。<br>
            對於 eVTOL 而言，僅需 <span class="highlight">數十公斤的液態氫 (LH2)</span> 即可達成任務所需的續航時間 [cite: 8]。
        </p>
    </section>

    <section id="tech" class="py-16 px-6 max-w-7xl mx-auto grid md:grid-cols-3 gap-8">
        <div class="data-card p-8 reveal">
            <div class="text-blue-600 text-3xl mb-6"><i class="fas fa-microchip"></i></div>
            <h3 class="text-xl font-bold mb-4">1. 已驗證的動力系統</h3>
            <p class="text-slate-500 text-sm mb-6">
                我們曾成功改裝並飛行測試了 <span class="highlight">1 MW 氫電動力系統</span>（Dash 8-300 測試平台）[cite: 15, 17]。
            </p>
            <button onclick="toggleInfo('tech1')" class="text-blue-600 text-sm font-bold hover:underline">查看詳情</button>
            <div id="tech1" class="hidden mt-4 text-xs bg-slate-50 p-4 rounded-lg text-slate-500">
                驗證內容包含模塊化 LH2 儲存、輕量化鋁合金真空絕緣技術，以及每模塊達 200kg 的儲存潛力 [cite: 18]。
            </div>
        </div>

        <div class="data-card p-8 reveal">
            <div class="text-emerald-600 text-3xl mb-6"><i class="fas fa-chart-line"></i></div>
            <h3 class="text-xl font-bold mb-4">2. 鎖定領先市場</h3>
            <p class="text-slate-500 text-sm mb-6">
                中國是全球 eVTOL 領導市場，已有億航 (EHang) 獲得商業營運證書 [cite: 52]。
            </p>
            <button onclick="toggleInfo('tech2')" class="text-blue-600 text-sm font-bold hover:underline">市場數據</button>
            <div id="tech2" class="hidden mt-4 text-xs bg-slate-50 p-4 rounded-lg text-slate-500">
                2035 年全球市場規模預計突破 <span class="highlight">400 億美元</span> [cite: 53]。中國「京鴻」DF600 已證明氫能飛機能實現 800-1,000 公里航程 [cite: 55, 60]。
            </div>
        </div>

        <div class="data-card p-8 reveal">
            <div class="text-orange-600 text-3xl mb-6"><i class="fas fa-boxes"></i></div>
            <h3 class="text-xl font-bold mb-4">3. 商業模式與路徑</h3>
            <p class="text-slate-500 text-sm mb-6">
                我們銷售 <span class="highlight">轉向鑰匙 (Turnkey) 系統套件</span>，包含儲存模組與動力系統 [cite: 38, 39, 40]。
            </p>
            <button onclick="toggleInfo('tech3')" class="text-blue-600 text-sm font-bold hover:underline">執行計畫</button>
            <div id="tech3" class="hidden mt-4 text-xs bg-slate-50 p-4 rounded-lg text-slate-500">
                Phase 1: 於圖盧茲重組 10 人核心團隊 [cite: 29]。<br>
                Phase 2: 透過中國供應鏈實現大規模生產 [cite: 33]。
            </div>
        </div>
    </section>

    <section class="py-16 px-6 reveal">
        <div class="max-w-3xl mx-auto bg-blue-50 border-l-4 border-blue-600 p-8 rounded-r-2xl">
            <p class="text-lg text-blue-800 italic leading-relaxed">
                「哥們，跟你分享一個核心觀點：我們這次不走大型客機認證的老路（那是 1.0 失敗的原因）。UH 2.0 是要利用我們已經做出來的 TRL 6-7 技術，直接對接中國那些急需航程解決方案的 eVTOL 廠商，這才是技術落地的最快路徑。」
            </p>
        </div>
    </section>

    <section id="market" class="py-24 text-center px-6 reveal">
        <h2 class="text-3xl font-bold mb-8">準備好見證航空能源的未來了嗎？</h2>
        <button onclick="openModal()" class="bg-blue-600 hover:bg-blue-700 text-white text-lg px-12 py-4 rounded-full font-bold shadow-lg transition transform hover:scale-105">
            我懂了
        </button>
    </section>

    <div id="modal" class="fixed inset-0 bg-slate-900/80 hidden items-center justify-center z-[100] p-4 backdrop-blur-sm">
        <div class="bg-white p-8 md:p-12 rounded-3xl max-w-lg w-full text-center">
            <div class="w-20 h-20 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-6 text-3xl">
                <i class="fas fa-rocket"></i>
            </div>
            <h4 class="text-2xl font-bold mb-4">核心投資提醒</h4>
            <p class="text-slate-600 mb-8 text-left">
                UH 2.0 的核心在於：<br>
                1. <span class="font-bold text-slate-800">避開漫長認證</span>，優先服務 eVTOL 市場 [cite: 26, 32]。<br>
                2. <span class="font-bold text-slate-800">利用中國製造</span>，解決液態氫低溫儲罐的產能問題 [cite: 36]。<br>
                3. <span class="font-bold text-slate-800">技術領先</span>，我們是少數擁有 1 MW 級實際飛行測試經驗的團隊 [cite: 15, 17]。
            </p>
            <button onclick="closeModal()" class="w-full py-4 bg-slate-900 text-white rounded-xl font-bold">開啟合作討論</button>
        </div>
    </div>

    <script>
        // 滾動動畫處理
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) entry.target.classList.add('active');
            });
        }, { threshold: 0.1 });
        document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

        // 詳解切換
        function toggleInfo(id) {
            const el = document.getElementById(id);
            el.classList.toggle('hidden');
        }

        // 彈窗處理
        const modal = document.getElementById('modal');
        function openModal() { modal.style.display = 'flex'; }
        function closeModal() { modal.style.display = 'none'; }
    </script>
</body>
</html>
