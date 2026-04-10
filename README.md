<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>PKS SMANDA | Recruitment 2026</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #3b82f6;
            --primary-glow: rgba(59, 130, 246, 0.5);
            --bg-dark: #020617;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg-dark);
            background-image: 
                radial-gradient(circle at 50% -20%, #1e293b 0%, transparent 50%),
                radial-gradient(circle at 0% 100%, #0f172a 0%, transparent 40%);
            min-height: 100vh;
            color: #f1f5f9;
            overflow-x: hidden;
        }

        .font-outfit { font-family: 'Outfit', sans-serif; }

        .glass-container {
            background: rgba(15, 23, 42, 0.75);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.6);
        }

        /* Hero Logo Animation */
        .logo-glow {
            position: relative;
        }
        .logo-glow::after {
            content: '';
            position: absolute;
            inset: -10px;
            background: var(--primary);
            filter: blur(25px);
            opacity: 0.2;
            z-index: -1;
            border-radius: 2rem;
        }

        .input-field {
            width: 100%;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 1.1rem 1.25rem;
            border-radius: 1.25rem;
            color: #ffffff;
            font-weight: 600;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        /* Fix for blurry/dark select options */
        select.input-field {
            color: #ffffff;
            background-image: none;
        }

        select.input-field option {
            background-color: #0f172a; 
            color: #ffffff;
            padding: 12px;
            font-size: 14px;
        }

        .input-field:focus {
            outline: none;
            border-color: var(--primary);
            background: rgba(255, 255, 255, 0.08);
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.2);
        }

        .input-label {
            display: block;
            font-size: 0.7rem;
            font-weight: 800;
            color: #64748b;
            text-transform: uppercase;
            letter-spacing: 0.2em;
            margin-bottom: 0.6rem;
            margin-left: 0.25rem;
        }

        .btn-action {
            background: linear-gradient(135deg, #3b82f6 0%, #2563eb 100%);
            position: relative;
            overflow: hidden;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .btn-action::before {
            content: '';
            position: absolute;
            top: 0; left: -100%;
            width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: 0.5s;
        }

        .btn-action:hover::before { left: 100%; }

        .btn-action:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px -5px rgba(37, 99, 235, 0.5);
        }

        .card-session {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.06);
            border-radius: 1.5rem;
            padding: 1.25rem;
            transition: all 0.3s ease;
        }

        .card-session:hover {
            background: rgba(255, 255, 255, 0.05);
            border-color: var(--primary);
            transform: scale(1.02);
        }

        .hidden-section { display: none !important; }
        
        @keyframes reveal {
            from { opacity: 0; transform: translateY(20px) scale(0.95); }
            to { opacity: 1; transform: translateY(0) scale(1); }
        }
        .animate-reveal { animation: reveal 0.6s cubic-bezier(0.16, 1, 0.3, 1) forwards; }
    </style>
</head>
<body class="flex items-center justify-center p-6 min-h-screen">

    <div id="app" class="w-full max-w-md">
        
        <!-- SECTION 1: LANDING PAGE -->
        <div id="landingPage" class="animate-reveal flex flex-col items-center py-10">
            <!-- Badge -->
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-sky-500/10 border border-sky-500/20 mb-8">
                <span class="relative flex h-2 w-2">
                    <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-sky-400 opacity-75"></span>
                    <span class="relative inline-flex rounded-full h-2 w-2 bg-sky-500"></span>
                </span>
                <span class="text-[10px] font-black text-sky-400 tracking-[0.2em] uppercase">Pendaftaran Dibuka</span>
            </div>

            <!-- Logo Area -->
            <div class="logo-glow w-28 h-28 bg-slate-900 border border-white/10 rounded-[2.5rem] flex items-center justify-center mb-10 transform -rotate-6">
                <div class="w-16 h-16 bg-gradient-to-br from-sky-400 to-blue-600 rounded-2xl flex items-center justify-center shadow-lg shadow-blue-500/20 rotate-6">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-9 w-9 text-white" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M12 1L3 5v6c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V5l-9-4zm-2 16l-4-4 1.41-1.41L10 14.17l6.59-6.59L18 9l-8 8z"/>
                    </svg>
                </div>
            </div>

            <!-- Typography -->
            <div class="text-center mb-10">
                <h2 class="font-outfit text-sm font-medium text-sky-400 tracking-[0.5em] mb-3 uppercase">Patroli Keamanan Sekolah</h2>
                <h1 class="font-outfit text-6xl font-black tracking-tighter text-white mb-2 leading-none">
                    SMANDA<span class="text-sky-500 text-7xl">.</span>
                </h1>
                <p class="text-slate-500 text-xs font-semibold tracking-[0.2em] uppercase">Generasi Emas 2026</p>
            </div>

            <!-- Action Button -->
            <button onclick="showSchedule()" class="btn-action w-full py-5 rounded-[1.5rem] text-white font-black text-sm tracking-[0.2em] flex items-center justify-center gap-3 group">
                MULAI REGISTRASI
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 transform group-hover:translate-x-1 transition-transform" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
                </svg>
            </button>
            
            <p class="mt-8 text-slate-600 text-[10px] font-bold tracking-widest uppercase">Tap untuk melihat timeline pendaftaran</p>
        </div>

        <!-- SECTION 2: TIMELINE -->
        <div id="schedulePage" class="hidden-section animate-reveal">
            <div class="glass-container rounded-[2.5rem] p-8 border-t-sky-500/30 border-t-2">
                <div class="flex items-center justify-between mb-8">
                    <div>
                        <h2 class="text-2xl font-black text-white uppercase tracking-tight">Timeline</h2>
                        <p class="text-[10px] font-bold text-sky-500 tracking-widest uppercase">Jadwal Seleksi</p>
                    </div>
                    <button onclick="goBackToHome()" class="w-10 h-10 flex items-center justify-center rounded-xl border border-white/10 bg-white/5 hover:bg-white/10 transition-colors">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-slate-400" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd" /></svg>
                    </button>
                </div>

                <div class="space-y-4">
                    <!-- GELOMBANG 1 -->
                    <div class="card-session flex items-center justify-between group">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-full bg-sky-500/10 border border-sky-500/20 flex items-center justify-center font-black text-sky-400 text-xs">01</div>
                            <div>
                                <h3 class="text-white font-bold text-sm">Gelombang I</h3>
                                <p class="text-[10px] font-medium text-slate-500 uppercase">Pendaftaran Administrasi</p>
                            </div>
                        </div>
                        <span class="text-right font-black text-sky-400 text-[10px] tracking-tighter uppercase">5-6 Jun</span>
                    </div>

                    <!-- GELOMBANG 2 -->
                    <div class="card-session flex items-center justify-between group">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-full bg-sky-500/10 border border-sky-500/20 flex items-center justify-center font-black text-sky-400 text-xs">02</div>
                            <div>
                                <h3 class="text-white font-bold text-sm">Gelombang II</h3>
                                <p class="text-[10px] font-medium text-slate-500 uppercase">Pendaftaran Administrasi</p>
                            </div>
                        </div>
                        <span class="text-right font-black text-sky-400 text-[10px] tracking-tighter uppercase">6-7 Jun</span>
                    </div>

                    <!-- GELOMBANG 3 -->
                    <div class="card-session flex items-center justify-between group">
                        <div class="flex items-center gap-4">
                            <div class="w-10 h-10 rounded-full bg-sky-500/10 border border-sky-500/20 flex items-center justify-center font-black text-sky-400 text-xs">03</div>
                            <div>
                                <h3 class="text-white font-bold text-sm">Gelombang III</h3>
                                <p class="text-[10px] font-medium text-slate-500 uppercase">Pendaftaran Administrasi</p>
                            </div>
                        </div>
                        <span class="text-right font-black text-sky-400 text-[10px] tracking-tighter uppercase">7-8 Jun</span>
                    </div>

                    <div class="mt-8 p-6 rounded-2xl bg-gradient-to-br from-amber-500/10 to-orange-500/5 border border-amber-500/20 text-center relative overflow-hidden">
                        <div class="relative z-10">
                            <p class="text-amber-500 text-[10px] font-black uppercase tracking-[0.2em] mb-2">Final Announcement</p>
                            <p class="text-white font-black text-2xl tracking-tight">10 JUNI 2026</p>
                        </div>
                    </div>
                </div>

                <button onclick="startRegistration()" class="btn-action w-full py-5 rounded-[1.25rem] text-white font-black text-sm mt-10 tracking-[0.1em] uppercase">
                    LANJUT KE BIODATA
                </button>
            </div>
        </div>

        <!-- SECTION 3: FORMULIR -->
        <div id="registrationContent" class="hidden-section animate-reveal">
            <div class="glass-container rounded-[2.5rem] p-8">
                <div class="flex items-center gap-5 mb-10">
                    <button onclick="showSchedule()" class="w-12 h-12 flex items-center justify-center rounded-2xl border border-white/10 bg-white/5 hover:bg-white/10 transition-all">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-slate-400" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd" /></svg>
                    </button>
                    <div>
                        <h2 class="text-xl font-black text-white uppercase tracking-tight">Biodata</h2>
                        <p class="text-[10px] font-bold text-slate-500 uppercase tracking-widest">Informasi Dasar</p>
                    </div>
                </div>

                <form id="registrationForm" class="space-y-6">
                    <div>
                        <label class="input-label">Nama Lengkap</label>
                        <input type="text" id="nama" required placeholder="NAMA SESUAI IJAZAH" class="input-field placeholder:text-slate-700 uppercase">
                    </div>

                    <div>
                        <label class="input-label">Asal Sekolah</label>
                        <input type="text" id="asal" required placeholder="SMP ASAL" class="input-field placeholder:text-slate-700 uppercase">
                    </div>

                    <div class="grid grid-cols-2 gap-4">
                        <div>
                            <label class="input-label">Tingkat</label>
                            <div class="relative">
                                <select id="tingkatKelas" class="input-field cursor-pointer appearance-none">
                                    <option value="X">KELAS X</option>
                                    <option value="XI">KELAS XI</option>
                                    <option value="XII">KELAS XII</option>
                                </select>
                                <div class="absolute right-4 top-1/2 -translate-y-1/2 pointer-events-none text-sky-500">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" /></svg>
                                </div>
                            </div>
                        </div>
                        <div>
                            <label class="input-label">Fase</label>
                            <div class="relative">
                                <select id="nomorKelas" class="input-field cursor-pointer appearance-none"></select>
                                <div class="absolute right-4 top-1/2 -translate-y-1/2 pointer-events-none text-sky-500">
                                    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 20 20" fill="currentColor"><path fill-rule="evenodd" d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" clip-rule="evenodd" /></svg>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div>
                        <label class="input-label">WhatsApp</label>
                        <div class="flex gap-3">
                            <div class="w-20 flex items-center justify-center bg-white/5 border border-white/10 rounded-2xl text-white font-bold text-xs">
                                +62
                            </div>
                            <input type="tel" id="hp" required placeholder="8XXXXXXXXX" class="input-field">
                        </div>
                    </div>

                    <div class="pt-4">
                        <button type="submit" id="btnSubmit" class="btn-action w-full py-5 rounded-2xl text-white font-black text-sm tracking-[0.2em] flex items-center justify-center gap-3">
                            <span id="btnText">KIRIM SEKARANG</span>
                            <div id="loader" class="hidden animate-spin h-4 w-4 border-2 border-white border-t-transparent rounded-full"></div>
                        </button>
                    </div>
                </form>
            </div>
        </div>

        <!-- SECTION 4: SUCCESS -->
        <div id="successContainer" class="hidden-section animate-reveal text-center">
            <div class="glass-container rounded-[3rem] p-12">
                <div class="w-24 h-24 bg-emerald-500/10 border border-emerald-500/20 rounded-full flex items-center justify-center mx-auto mb-8">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-emerald-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7" /></svg>
                </div>
                <h2 class="text-3xl font-black text-white mb-3 uppercase tracking-tight">Terdaftar!</h2>
                <p id="successMsg" class="text-slate-400 text-sm font-medium mb-12 leading-relaxed px-2"></p>
                <button onclick="window.location.reload()" class="w-full py-4 rounded-2xl border border-white/10 text-white font-bold uppercase text-[10px] tracking-[0.3em] hover:bg-white/5 transition-all">Selesai</button>
            </div>
        </div>
    </div>

    <script>
        const DISCORD_WEBHOOK_URL = "https://discord.com/api/webhooks/1491752038428708997/v5KJ3POK6iQbxBTDnWc1ew2VFJqUrXmkaf8a9-1JDSH_7gm38vwacIulSVwnb4ugCN_m";

        const sections = {
            home: document.getElementById('landingPage'),
            schedule: document.getElementById('schedulePage'),
            form: document.getElementById('registrationContent'),
            success: document.getElementById('successContainer')
        };

        function hideAll() { Object.values(sections).forEach(s => s.classList.add('hidden-section')); }
        function goBackToHome() { hideAll(); sections.home.classList.remove('hidden-section'); }
        function showSchedule() { hideAll(); sections.schedule.classList.remove('hidden-section'); }
        function startRegistration() { hideAll(); sections.form.classList.remove('hidden-section'); }

        const tingkatKelas = document.getElementById('tingkatKelas');
        const nomorKelas = document.getElementById('nomorKelas');

        function updateFaseOptions() {
            const tingkat = tingkatKelas.value;
            const fasePrefix = (tingkat === 'XI' || tingkat === 'XII') ? 'F' : 'E';
            const max = (tingkat === 'XI' || tingkat === 'XII') ? 11 : 10;
            nomorKelas.innerHTML = '';
            for (let i = 1; i <= max; i++) {
                const opt = document.createElement('option');
                opt.value = `${fasePrefix}${i}`;
                opt.textContent = `FASE ${fasePrefix}${i}`;
                nomorKelas.appendChild(opt);
            }
        }

        window.addEventListener('DOMContentLoaded', updateFaseOptions);
        tingkatKelas.addEventListener('change', updateFaseOptions);

        document.getElementById('registrationForm').addEventListener('submit', async (e) => {
            e.preventDefault();
            const btnSubmit = document.getElementById('btnSubmit');
            const btnText = document.getElementById('btnText');
            const loader = document.getElementById('loader');

            btnSubmit.disabled = true;
            btnText.textContent = "SEDANG MENGIRIM...";
            loader.classList.remove('hidden');

            const noUrut = (parseInt(localStorage.getItem('pks_smanda_count') || "0") + 1).toString().padStart(2, '0');
            const rawPhone = document.getElementById('hp').value.replace(/\D/g, ''); 
            const phone = "62" + (rawPhone.startsWith('0') ? rawPhone.substring(1) : rawPhone);
            
            const payload = {
                nama: document.getElementById('nama').value.trim().toUpperCase(),
                asal: document.getElementById('asal').value.trim().toUpperCase(),
                kelas: `${tingkatKelas.value} ${nomorKelas.value}`,
                whatsapp: phone,
                no_urut: noUrut
            };

            const embed = {
                username: "PKS SMANDA SYSTEM",
                embeds: [{
                    title: `📋 DATA CALON BARU [#${payload.no_urut}]`,
                    color: 2327019,
                    fields: [
                        { name: "NAMA LENGKAP", value: `**${payload.nama}**`, inline: false },
                        { name: "KELAS / FASE", value: payload.kelas, inline: true },
                        { name: "ASAL SEKOLAH", value: payload.asal, inline: true },
                        { name: "HUBUNGI", value: `[Buka WhatsApp](https://wa.me/${payload.whatsapp})`, inline: false }
                    ],
                    footer: { text: "Recruitment System • Smanda 2026" },
                    timestamp: new Date().toISOString()
                }]
            };

            try {
                await fetch(DISCORD_WEBHOOK_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(embed)
                });
                localStorage.setItem('pks_smanda_count', noUrut);
                document.getElementById('successMsg').innerHTML = `Halo <b>${payload.nama.split(' ')[0]}</b>, datamu berhasil dikirim dengan nomor antrean <b>#${payload.no_urut}</b>. Mohon tunggu kabar dari kami melalui WhatsApp.`;
                hideAll();
                sections.success.classList.remove('hidden-section');
            } catch (err) {
                alert("Gagal mengirim data. Cek koneksi internetmu.");
            } finally {
                btnSubmit.disabled = false;
                btnText.textContent = "KIRIM SEKARANG";
                loader.classList.add('hidden');
            }
        });
    </script>
</body>
</html>
