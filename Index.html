<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elite Terminal | Multi-Asset Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root { --accent: #00ff88; --bg: #06080a; --side: #0f1115; }
        body { background: var(--bg); color: #e5e7eb; font-family: 'Inter', sans-serif; overflow: hidden; }
        .sidebar-item { transition: 0.3s; cursor: pointer; border-radius: 12px; }
        .sidebar-item:hover, .sidebar-item.active { background: rgba(0, 255, 136, 0.1); color: var(--accent); }
        .glass-panel { background: #111418; border: 1px solid #1f2226; border-radius: 20px; }
        .stake-btn { background: #1f2226; border: 1px solid #2d3139; transition: 0.2s; }
        .stake-btn:active { transform: scale(0.9); background: #2d3139; }
        .feature-page { display: none; height: calc(100vh - 40px); overflow-y: auto; }
        .feature-page.active { display: block; }
    </style>
</head>
<body class="flex h-screen p-2 md:p-4 gap-4">

    <aside class="w-20 md:w-64 glass-panel flex flex-col p-4 gap-2">
        <div class="flex items-center gap-3 px-2 mb-8 mt-2">
            <div class="w-8 h-8 bg-[#00ff88] rounded-lg flex items-center justify-center text-black font-black">$</div>
            <span class="hidden md:block font-black tracking-tighter uppercase italic text-lg">Elite <span class="text-[#00ff88]">Hub</span></span>
        </div>

        <nav class="flex flex-col gap-1">
            <div onclick="showPage('dashboard')" class="sidebar-item active p-3 flex items-center gap-4"><i class="fas fa-th-large w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Dashboard</span></div>
            <div onclick="showPage('builder')" class="sidebar-item p-3 flex items-center gap-4"><i class="fas fa-tools w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Bot Builder</span></div>
            <div onclick="showPage('copy')" class="sidebar-item p-3 flex items-center gap-4"><i class="fas fa-users w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Copy Trader</span></div>
            <div onclick="showPage('markets')" class="sidebar-item p-3 flex items-center gap-4"><i class="fas fa-chart-line w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Markets</span></div>
            <div onclick="showPage('charts')" class="sidebar-item p-3 flex items-center gap-4"><i class="fas fa-wave-square w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Live Charts</span></div>
            <div onclick="showPage('signals')" class="sidebar-item p-3 flex items-center gap-4"><i class="fas fa-satellite-dish w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Signals</span></div>
            <div onclick="showPage('premium')" class="sidebar-item p-3 flex items-center gap-4"><i class="fas fa-crown w-5"></i><span class="hidden md:block text-xs font-bold uppercase">Premium Bots</span></div>
        </nav>
        
        <div class="mt-auto p-2 border-t border-gray-800">
            <button onclick="login()" class="w-full bg-white text-black py-2 rounded-lg font-black text-[10px] uppercase">Login</button>
        </div>
    </aside>

    <main class="flex-1 overflow-hidden">
        
        <div id="dashboard" class="feature-page active space-y-6">
            <div class="glass-panel p-6 flex justify-between items-center border-t-4 border-[#00ff88]">
                <div>
                    <h2 class="text-xl font-black uppercase italic">Dollar <span class="text-[#00ff88]">Printer</span></h2>
                    <p class="text-[9px] text-gray-500 font-bold uppercase">Total Balance: <span id="balance" class="text-white">$0.00</span></p>
                </div>
                <div class="flex gap-2">
                    <button class="bg-red-500/10 text-red-500 px-4 py-2 rounded-lg text-[10px] font-black uppercase">Stop All</button>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="glass-panel p-6">
                    <h3 class="text-[10px] font-black text-[#00ff88] uppercase mb-6 tracking-widest">Active Printer Engine</h3>
                    
                    <div class="space-y-6">
                        <div class="bg-black p-4 rounded-xl border border-gray-800">
                            <label class="text-[9px] text-gray-500 font-bold uppercase block mb-3 text-center">Active Stake Adjustment</label>
                            <div class="flex items-center justify-between gap-4">
                                <button onclick="adjustStake(-0.1)" class="stake-btn w-12 h-12 rounded-xl flex items-center justify-center text-xl font-bold">-</button>
                                <input id="stake" type="number" value="0.35" class="bg-transparent text-center text-2xl font-black text-white w-full outline-none">
                                <button onclick="adjustStake(0.1)" class="stake-btn w-12 h-12 rounded-xl flex items-center justify-center text-xl font-bold">+</button>
                            </div>
                        </div>

                        <div class="grid grid-cols-2 gap-4">
                            <div class="bg-black p-3 rounded-xl border border-gray-800">
                                <label class="text-[9px] text-gray-500 font-bold uppercase">Recovery</label>
                                <input id="mart" type="number" value="11" class="w-full bg-transparent font-bold text-white outline-none">
                            </div>
                            <div class="bg-black p-3 rounded-xl border border-gray-800">
                                <label class="text-[9px] text-gray-500 font-bold uppercase">Strategy</label>
                                <select id="strat" class="w-full bg-transparent font-bold text-[#00ff88] outline-none text-xs">
                                    <option>Digit Differ</option>
                                    <option>Over/Under</option>
                                </select>
                            </div>
                        </div>

                        <button onclick="startBot()" class="w-full bg-[#00ff88] text-black font-black py-5 rounded-2xl uppercase tracking-widest text-sm shadow-lg shadow-[#00ff88]/20">Start Printing $</button>
                    </div>
                </div>

                <div class="glass-panel p-6 flex flex-col h-full min-h-[400px]">
                    <h3 class="text-[10px] font-black text-gray-500 uppercase mb-4 tracking-widest">Transaction Journal</h3>
                    <div id="journal" class="flex-1 overflow-y-auto font-mono text-[10px] space-y-2 text-gray-400">
                        <div>> Terminal established. Awaiting connection...</div>
                    </div>
                </div>
            </div>
        </div>

        <div id="builder" class="feature-page">
            <div class="glass-panel p-12 text-center">
                <i class="fas fa-tools text-6xl text-[#00ff88] mb-6"></i>
                <h2 class="text-2xl font-black uppercase italic">Bot Builder <span class="text-[#00ff88]">Pro</span></h2>
                <p class="text-gray-500 max-w-md mx-auto mt-4 font-medium">Drag and drop blocks to create your own automated dollar printing strategy.</p>
                <button class="mt-8 bg-white text-black px-8 py-3 rounded-xl font-black uppercase text-xs">Open Workspace</button>
            </div>
        </div>

        <div id="copy" class="feature-page"><div class="glass-panel p-12 text-center text-gray-500 uppercase font-black tracking-widest">Copy Trader Module Linked</div></div>
        <div id="markets" class="feature-page"><div class="glass-panel p-12 text-center text-gray-500 uppercase font-black tracking-widest">Multi-Market Terminal Linked</div></div>
        <div id="signals" class="feature-page"><div class="glass-panel p-12 text-center text-gray-500 uppercase font-black tracking-widest">Live Signal Feed Active</div></div>

    </main>

    <script>
        const APP_ID = '124737';

        function showPage(pageId) {
            // Hide all pages
            document.querySelectorAll('.feature-page').forEach(p => p.classList.remove('active'));
            // Deactivate all sidebar items
            document.querySelectorAll('.sidebar-item').forEach(i => i.classList.remove('active'));
            
            // Show selected
            document.getElementById(pageId).classList.add('active');
            // Highlight sidebar
            event.currentTarget.classList.add('active');
        }

        function adjustStake(val) {
            let s = document.getElementById('stake');
            let current = parseFloat(s.value);
            s.value = (current + val).toFixed(2);
            if(s.value < 0.35) s.value = 0.35;
        }

        function login() { window.location.href = `https://oauth.deriv.com/oauth2/authorize?app_id=${APP_ID}&l=en&brand=deriv`; }
        
        function addLog(m) {
            const j = document.getElementById('journal');
            j.innerHTML = `<div>[${new Date().toLocaleTimeString()}] ${m}</div>` + j.innerHTML;
        }

        // Logic for bot activation would go here similar to previous versions
    </script>
</body>
</html>
