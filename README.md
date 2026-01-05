<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UH 2.0 | 氫能航空投資數據分析</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Noto+Sans+TC:wght@300;400;700&display=swap');
        
        body {
            font-family: 'Inter', 'Noto Sans TC', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
        }

        .hero-section {
            background: linear-gradient(135deg, #0f172a 0%, #1e40af 100%);
            color: white;
            padding: 80px 20px;
        }

        .data-card {
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1);
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
        }

        .data-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1);
            border-color: #3b82f6;
        }

        .tag {
            background: #e0f2fe;
            color: #0369a1;
            padding: 2px 10px;
            border-radius: 9999px;
            font-size: 0.75rem;
            font-weight: 600;
        }

        .reveal { opacity: 0; transform: translateY(20px); transition: all 0.6s ease-out; }
        .reveal.active { opacity: 1; transform: translateY(0); }
    </style>
</head>
<body>

    <nav class="bg-white border-b border-slate-200 py-4 px-8 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <span class="text-2xl font-bold text-blue-600">項目詳解</span>
                <div class="hidden md:flex space-x-6 text-sm font-medium text-slate-600 ml-10">
                    <a href="#" class="hover:text-blue-600">首頁</a>
                    <a href="#" class="text-blue-600">投融資事件</a>
                    <a href="#" class="hover:text-blue-600">公司庫</a>
                </div>
            </div>
            <button class="bg-blue-600 text-white px-4 py-2 rounded text-sm font-bold">登入/註冊</button>
        </div>
    </nav>

    <header class="hero-section text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">液態氫航空系統：<br>重新定義 eVTOL 的航程極限</h1>
            <p class="text-blue-100 text-lg md:text-xl mb-10 max-w-2xl mx-auto font-light">
                提供 LH2 儲存與燃料電池動力系統，專為電動垂直起降飛行器（eVTOL）打造。
            </p>
            <div class="flex justify-center space-x-4">
                <div class="bg-white/20 p-4 rounded-xl backdrop-blur-md">
                    <div class="text-3xl font-bold">130k €</div>
                    <div class="text-xs text-blue-200">月度預算 (Phase 1)</div>
                </div>
                <div class="bg-white/20 p-4 rounded-xl backdrop-blur-md">
                    <div class="text-3xl font-bold">10+ 人</div>
                    <div class="text-xs text-blue-200">核心團隊</div>
                </div>
            </div>
        </div>
    </header>

    <main class="max-w-7xl mx-auto py-16 px-6">
        
        <div class="grid md:grid-cols-3 gap-8 mb-16">
            <div class="data-card p-8 reveal">
                <div class="flex justify-between items-start mb-6">
                    <div class="bg-blue-100 p-3 rounded-lg text-blue-600 text-2xl"><i class="fas fa-bolt"></i></div>
                    <span class="tag">能源密度優勢</span>
                </div>
                <h3 class="text-xl font-bold mb-3">為何選擇液態氫 (LH2)?</h3>
                <p class="text-slate-500 text-sm leading-relaxed">
                    電池太重，氣態氫體積太大。對 eVTOL 而言，僅需數十公斤 LH2 即可實現所需的任務續航。
                </p>
            </div>

            <div class="data-card p-8 reveal">
                <div class="flex justify-between items-start mb-6">
                    <div class="bg-emerald-100 p-3 rounded-lg text-emerald-600 text-2xl"><i class="fas fa-plane-departure"></i></div>
                    <span class="tag">已驗證 TRL 6-7</span>
                </div>
                <h3 class="text-xl font-bold mb-3">實證數據 (Proof of Work)</h3>
                <p class="text-slate-500 text-sm leading-relaxed">
                    曾成功飛行測試 1 MW 氫電動力系統，並驗證了模塊化低蒸發 LH2 儲存技術。
                </p>
            </div>

            <div class="data-card p-8 reveal">
                <div class="flex justify-between items-start mb-6">
                    <div class="bg-orange-100 p-3 rounded-lg text-orange-600 text-2xl"><i class="fas fa-industry"></i></div>
                    <span class="tag">供應鏈整合</span>
                </div>
                <h3 class="text-xl font-bold mb-3">產業化路徑</h3>
                <p
