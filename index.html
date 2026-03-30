<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ReviewPositive | Sistema Oficial 4K</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;900&family=Inter:wght@300;400;700&display=swap');
        
        :root { --neon: #bc13fe; --dark: #050508; --gold: #ffcc00; --bg-card: rgba(10, 10, 15, 0.98); --red: #ff4444; }
        
        body { 
            background: #030305; 
            color: #e2e8f0; 
            font-family: 'Inter', sans-serif; 
            background-image: radial-gradient(circle at 50% 50%, #110a24 0%, #030305 100%); 
            min-height: 100vh; margin: 0; overflow-x: hidden;
        }

        /* LOGIN & REGISTRO */
        .neon-text { color: #bc13fe; text-shadow: 0 0 15px rgba(188, 19, 254, 0.6); font-family: 'Orbitron', sans-serif; }
        .glass { background: rgba(10, 10, 15, 0.95); backdrop-filter: blur(25px); border: 1px solid rgba(188, 19, 254, 0.2); border-radius: 20px; box-shadow: 0 20px 50px rgba(0,0,0,0.9); }
        
        .input-quantum { 
            background: rgba(0, 0, 0, 0.7); border: 1px solid rgba(188, 19, 254, 0.1); 
            color: white; padding: 0.7rem; border-radius: 10px; outline: none; width: 100%; font-size: 0.75rem;
        }
        .input-quantum:focus { border-color: var(--neon); box-shadow: 0 0 15px rgba(188, 19, 254, 0.2); }

        .btn-purple { 
            background: linear-gradient(135deg, #bc13fe 0%, #6a0dad 100%); width: 100%; 
            padding: 0.75rem; border-radius: 10px; font-weight: 900; text-transform: uppercase; 
            font-family: 'Orbitron', sans-serif; font-size: 0.65rem; letter-spacing: 2px; cursor: pointer; border: none; color: white; transition: 0.3s;
        }
        .btn-purple:hover { box-shadow: 0 0 25px rgba(188, 19, 254, 0.5); transform: translateY(-1px); }

        /* ESTRELLAS */
        #stars-container { position: fixed; inset: 0; z-index: -1; pointer-events: none; }
        .star { position: absolute; background: white; border-radius: 50%; box-shadow: 0 0 8px white; animation: floatUp linear infinite; }
        @keyframes floatUp { from { transform: translateY(100vh) scale(0.5); opacity: 0; } 50% { opacity: 0.8; } to { transform: translateY(-10vh) scale(1.2); opacity: 0; } }

        /* SIDEBAR */
        .sidebar { width: 260px; background: rgba(5, 5, 8, 0.9); backdrop-filter: blur(15px); border-right: 1px solid rgba(188, 19, 254, 0.1); padding: 30px; display: flex; flex-direction: column; height: 100vh; position: fixed; z-index: 50; }
        .nav-item { padding: 12px 20px; cursor: pointer; border-radius: 10px; margin-bottom: 8px; transition: 0.2s; color: #666; font-size: 0.85rem; font-weight: 600; }
        .nav-item:hover, .nav-item.active { background: rgba(188, 19, 254, 0.08); color: white; border-left: 3px solid var(--neon); }

        .main-content { margin-left: 260px; padding: 40px; width: calc(100% - 260px); }
        .view { display: none; max-width: 1000px; margin: 0 auto; animation: fadeIn 0.4s ease; }
        .view.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }

        /* DASHBOARD */
        .stat-card { background: rgba(20,20,30,0.6); padding: 40px; border-radius: 24px; border: 1px solid rgba(255,255,255,0.03); text-align: center; }
        .stat-val-big { font-size: 4rem; font-weight: 900; letter-spacing: -2px; font-family: 'Orbitron'; }

        /* ACTIVIDAD TABS */
        .tab-btn { padding: 10px 20px; cursor: pointer; color: #555; font-weight: bold; font-size: 0.75rem; border-bottom: 2px solid transparent; transition: 0.3s; }
        .tab-btn.active { color: var(--neon); border-color: var(--neon); }
        .status-table { width: 100%; border-collapse: separate; border-spacing: 0 8px; }
        .status-table td { background: rgba(255,255,255,0.02); padding: 15px; font-size: 0.8rem; }
        .status-table tr td:first-child { border-radius: 10px 0 0 10px; }
        .status-table tr td:last-child { border-radius: 0 10px 10px 0; text-align: right; }

        .badge { padding: 4px 10px; border-radius: 5px; font-size: 9px; font-weight: 800; text-transform: uppercase; }
        .b-pend { color: var(--gold); background: rgba(255, 204, 0, 0.1); border: 1px solid var(--gold); }
        .b-ok { color: #00ff88; background: rgba(0, 255, 136, 0.1); border: 1px solid #00ff88; }
        .b-fail { color: var(--red); background: rgba(255, 68, 68, 0.1); border: 1px solid var(--red); }

        #register-screen, #app-panel-wrapper { display: none; }
    </style>
</head>
<body>

    <div id="stars-container"></div>

    <div id="auth-wrapper" class="flex items-center justify-center h-screen">
        <div id="auth-screen" class="glass p-10 text-center w-full max-w-[340px]">
            <h1 class="text-lg font-black neon-text mb-1 uppercase tracking-tighter">REVIEWPOSITIVE</h1>
            <p class="text-gray-600 text-[6px] font-bold uppercase tracking-[0.5em] mb-8 italic">Panel de Trabajo</p>
            <div class="space-y-3 mb-6">
                <input type="email" id="l-email" placeholder="CORREO" class="input-quantum">
                <input type="password" id="l-pass" placeholder="CLAVE" class="input-quantum">
                <button onclick="login()" class="btn-purple mt-2">ENTRAR</button>
            </div>
            <button onclick="showScreen('register-screen')" class="text-gray-600 text-[7px] font-bold uppercase hover:text-[#bc13fe] underline">Registrar Nuevo Worker</button>
        </div>

        <div id="register-screen" class="glass p-10 text-center w-full max-w-[340px]">
            <h2 class="text-lg font-black neon-text mb-8 uppercase tracking-tighter">REGISTRO</h2>
            <div class="space-y-3 mb-6">
                <input type="text" id="r-nick" placeholder="APODO" class="input-quantum">
                <input type="email" id="r-email" placeholder="CORREO" class="input-quantum">
                <input type="password" id="r-pass" placeholder="CLAVE" class="input-quantum">
                <button onclick="register()" class="btn-purple mt-2">CREAR CUENTA</button>
            </div>
            <button onclick="showScreen('auth-screen')" class="text-gray-600 text-[7px] font-bold uppercase underline">Volver al inicio</button>
        </div>
    </div>

    <div id="app-panel-wrapper">
        <div class="sidebar">
            <div class="neon-text text-sm font-black mb-12 text-center italic tracking-widest">REVIEWPOSITIVE</div>
            <div class="nav-item active" onclick="nav('v-dash', this)">🏠 DASHBOARD</div>
            <div class="nav-item" onclick="nav('v-tasks', this)">📋 TAREAS</div>
            <div class="nav-item" onclick="nav('v-history', this)">📊 MI ACTIVIDAD</div>
            <div class="nav-item" onclick="nav('v-wallet', this)">💰 CAJERO</div>
            <button onclick="location.reload()" class="mt-auto text-red-500 text-[8px] font-black uppercase tracking-widest opacity-40 hover:opacity-100">Cerrar Sesión</button>
        </div>

        <div class="main-content">
            <div id="v-dash" class="view active">
                <p class="text-[9px] text-gray-500 font-bold mb-1 tracking-[0.3em]">TRABAJADOR VERIFICADO</p>
                <h1 class="text-4xl font-black mb-10 uppercase italic tracking-tighter" id="uName">WORKER</h1>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="stat-card" style="border-top: 4px solid var(--gold);">
                        <span class="text-[9px] text-gray-500 font-bold uppercase tracking-widest block mb-4">Saldo Retirable</span>
                        <div id="saldo" class="stat-val-big text-yellow-500 italic">$0.00</div>
                    </div>
                    <div class="stat-card" style="border-top: 4px solid var(--neon);">
                        <span class="text-[9px] text-gray-500 font-bold uppercase tracking-widest block mb-4">En Revisión</span>
                        <div id="val-pend" class="stat-val-big neon-text italic">$0.00</div>
                    </div>
                </div>
            </div>

            <div id="v-tasks" class="view">
                <h2 class="text-2xl font-black mb-8 italic uppercase">Trabajos Disponibles</h2>
                <div id="tasks-container" class="space-y-4">
                    <div class="glass p-8 flex flex-col md:flex-row justify-between items-center border-l-4 border-[#bc13fe]" id="t1">
                        <div>
                            <p class="font-bold text-lg mb-1">Google Maps: Reseña 5 Estrellas</p>
                            <a href="#" class="text-[#bc13fe] text-[10px] font-bold underline">🔗 VER NEGOCIO</a>
                        </div>
                        <div class="flex items-center gap-4 mt-4 md:mt-0">
                            <div class="text-yellow-500 font-black text-xl italic">$0.50</div>
                            <div class="flex gap-2">
                                <input type="text" id="workLink1" placeholder="URL de la reseña..." class="input-quantum w-[180px]">
                                <button onclick="enviarTask(1, 'Google Maps', 0.50)" class="btn-purple !w-auto px-6">SUBIR</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="v-history" class="view">
                <h2 class="text-2xl font-black mb-6 italic uppercase">Seguimiento</h2>
                <div class="flex gap-4 mb-6 border-b border-white/5">
                    <div class="tab-btn active" onclick="tabHistory('pend', this)">PENDIENTES</div>
                    <div class="tab-btn" onclick="tabHistory('ok', this)">APROBADAS</div>
                    <div class="tab-btn" onclick="tabHistory('fail', this)">RECHAZADAS</div>
                </div>
                <div id="hist-pend-view" class="h-view">
                    <table class="status-table"><tbody id="hist-pend"></tbody></table>
                </div>
                <div id="hist-ok-view" class="h-view hidden">
                    <table class="status-table"><tbody id="hist-ok"></tbody></table>
                </div>
                <div id="hist-fail-view" class="h-view hidden">
                    <table class="status-table"><tbody id="hist-fail"></tbody></table>
                </div>
            </div>

            <div id="v-wallet" class="view">
                <h2 class="text-2xl font-black mb-8 italic uppercase text-center">Cajero de Retiros</h2>
                <div class="glass p-10 max-w-[480px] mx-auto border-t-4 border-yellow-500">
                    <div class="mb-5">
                        <label class="text-[9px] text-gray-500 font-bold block mb-2 tracking-widest">MÉTODO DE COBRO</label>
                        <select id="w-method" class="input-quantum">
                            <option>USDT - Red Aptos</option>
                            <option>USDT - Red Plasma</option>
                            <option>Binance Pay</option>
                            <option>Bybit Pay</option>
                            <option>Zinli</option>
                        </select>
                    </div>
                    <div class="mb-5">
                        <label class="text-[9px] text-gray-500 font-bold block mb-2 tracking-widest">DATOS DE PAGO</label>
                        <input type="text" id="w-data" placeholder="ID / Billetera / Correo" class="input-quantum">
                    </div>
                    <div class="mb-8">
                        <label class="text-[9px] text-gray-500 font-bold block mb-2 tracking-widest">MONTO A RETIRAR (USD)</label>
                        <input type="number" id="w-amount" placeholder="Min. $5.00" class="input-quantum font-bold text-yellow-500">
                    </div>
                    <button onclick="processWithdraw()" class="btn-purple py-4 !text-[10px]">Solicitar Pago</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        const stars = document.getElementById('stars-container');
        for (let i = 0; i < 60; i++) {
            let s = document.createElement('div');
            s.className = 'star';
            s.style.left = Math.random() * 100 + 'vw';
            s.style.width = s.style.height = (Math.random() * 2 + 1) + 'px';
            s.style.animationDuration = (Math.random() * 8 + 4) + 's';
            stars.appendChild(s);
        }

        let userData = { saldo: 0, pending: 0 };

        function showScreen(id) {
            document.getElementById('auth-screen').style.display = 'none';
            document.getElementById('register-screen').style.display = 'none';
            document.getElementById(id).style.display = 'block';
        }

        function register() {
            const nick = document.getElementById('r-nick').value;
            const email = document.getElementById('r-email').value;
            const pass = document.getElementById('r-pass').value;
            if(!nick || !email || !pass) return alert("Faltan datos.");
            userData = { nick, email, pass, saldo: 0, pending: 0 };
            localStorage.setItem('rp_user_v24_' + email, JSON.stringify(userData));
            abrirPanel();
        }

        function login() {
            const email = document.getElementById('l-email').value;
            const pass = document.getElementById('l-pass').value;
            const saved = localStorage.getItem('rp_user_v24_' + email);
            if(saved) {
                const data = JSON.parse(saved);
                if(data.pass === pass) { userData = data; abrirPanel(); }
                else alert("Clave Incorrecta");
            } else alert("Correo No Registrado");
        }

        function abrirPanel() {
            document.getElementById('uName').innerText = userData.nick;
            document.getElementById('saldo').innerText = "$" + userData.saldo.toFixed(2);
            document.getElementById('val-pend').innerText = "$" + (userData.pending || 0).toFixed(2);
            document.getElementById('auth-wrapper').style.display = 'none';
            document.getElementById('app-panel-wrapper').style.display = 'block';
        }

        function nav(id, el) {
            document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
            document.querySelectorAll('.nav-item').forEach(i => i.classList.remove('active'));
            document.getElementById(id).classList.add('active');
            el.classList.add('active');
        }

        function enviarTask(id, type, price) {
            const link = document.getElementById('workLink'+id).value;
            if(!link) return alert("Pega el enlace");
            
            userData.pending = (userData.pending || 0) + price;
            document.getElementById('val-pend').innerText = "$" + userData.pending.toFixed(2);
            
            const card = document.getElementById('t'+id);
            card.style.transition = "0.5s";
            card.style.opacity = "0";
            card.style.transform = "scale(0.9)";
            setTimeout(() => card.remove(), 500);

            const row = `<tr><td>${type}</td><td><a href="${link}" class="text-white/40 underline">Ver URL</a></td><td><span class="badge b-pend">PENDIENTE</span></td><td>$${price.toFixed(2)}</td></tr>`;
            document.getElementById('hist-pend').innerHTML = row + document.getElementById('hist-pend').innerHTML;
            localStorage.setItem('rp_user_v24_' + userData.email, JSON.stringify(userData));
        }

        function tabHistory(type, el) {
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            document.querySelectorAll('.h-view').forEach(v => v.classList.add('hidden'));
            el.classList.add('active');
            document.getElementById('hist-'+type+'-view').classList.remove('hidden');
        }

        function processWithdraw() {
            const amt = parseFloat(document.getElementById('w-amount').value);
            if(isNaN(amt) || amt < 5) return alert("Mínimo $5.00");
            if(amt > userData.saldo) return alert("Saldo insuficiente");
            alert("Solicitud procesada");
        }
    </script>
</body>
</html>
