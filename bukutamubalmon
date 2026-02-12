<!doctype html>
<html lang="id" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Buku Tamu - Balai Monitor SFR Kelas II Palu</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Geist:wght@400;500;600;700&amp;family=Space+Grotesk:wght@400;500;600;700&amp;display=swap" rel="stylesheet">
  <style>
        * { font-family: 'Geist', 'Space Grotesk', sans-serif; }
        
        /* 2026 Modern Design */
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);
        }
        
        .fade-in { animation: fadeIn 0.6s ease-out; }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(15px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .glass-effect {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .gradient-text {
            background: linear-gradient(135deg, #0ea5e9 0%, #06b6d4 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .glow-effect {
            box-shadow: 0 0 30px rgba(14, 165, 233, 0.2);
        }
        
        .input-modern {
            background: rgba(255, 255, 255, 0.5);
            border: 2px solid rgba(14, 165, 233, 0.2);
            transition: all 0.3s ease;
        }
        
        .input-modern:focus {
            background: rgba(255, 255, 255, 0.9);
            border-color: #0ea5e9;
            box-shadow: 0 0 20px rgba(14, 165, 233, 0.3);
        }
        
        .btn-modern {
            background: linear-gradient(135deg, #0ea5e9 0%, #06b6d4 100%);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .btn-modern:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(14, 165, 233, 0.4);
        }
        
        .btn-modern::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: left 0.5s;
        }
        
        .btn-modern:hover::before {
            left: 100%;
        }
        
        .card-hover {
            transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
        }
        
        .card-hover:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(14, 165, 233, 0.15);
        }
        
        .toast-enter { animation: slideIn 0.4s cubic-bezier(0.34, 1.56, 0.64, 1); }
        .toast-exit { animation: slideOut 0.4s ease-in forwards; }
        
        @keyframes slideIn {
            from { transform: translateY(-120%); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        
        @keyframes slideOut {
            from { transform: translateY(0); opacity: 1; }
            to { transform: translateY(-120%); opacity: 0; }
        }
        
        .pulse-icon {
            animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
        
        /* Smooth scrolling */
        html {
            scroll-behavior: smooth;
        }
        
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: rgba(14, 165, 233, 0.1);
        }
        
        ::-webkit-scrollbar-thumb {
            background: linear-gradient(180deg, #0ea5e9, #06b6d4);
            border-radius: 4px;
        }
    </style>
  <style>body { box-sizing: border-box; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/element_sdk.js" type="text/javascript"></script>
 </head>
 <body class="h-full bg-slate-950 overflow-auto">
  <div id="app-wrapper" class="w-full min-h-full py-12 px-4 md:px-6"><!-- Toast Container -->
   <div id="toast-container" class="fixed top-4 left-1/2 transform -translate-x-1/2 z-50"></div><!-- Animated Background Elements -->
   <div class="fixed inset-0 -z-10 overflow-hidden">
    <div class="absolute top-20 left-10 w-72 h-72 bg-cyan-500 rounded-full mix-blend-multiply filter blur-3xl opacity-10 animate-pulse"></div>
    <div class="absolute bottom-20 right-10 w-72 h-72 bg-blue-500 rounded-full mix-blend-multiply filter blur-3xl opacity-10 animate-pulse" style="animation-delay: 2s;"></div>
   </div><!-- Header -->
   <header class="text-center mb-12 fade-in">
    <div class="inline-flex items-center justify-center relative">
     <div class="absolute inset-0 bg-gradient-to-r from-cyan-500 to-blue-500 rounded-2xl blur-lg opacity-30"></div>
     <div class="relative w-24 h-24 bg-white rounded-2xl flex items-center justify-center shadow-2xl">
      <svg class="w-14 h-14 text-transparent bg-gradient-to-r from-cyan-600 to-blue-600 bg-clip-text" viewbox="0 0 24 24" fill="currentColor"><path d="M12 21v-8.25M15.75 21v-8.25M8.25 21v-8.25M3 9l9-6 9 6m-1.5 12V10.332A48.36 48.36 0 0012 9.75c-2.551 0-5.056.2-7.5.582V21M3 21h18M12 6.75h.008v.008H12V6.75z" />
      </svg>
     </div>
    </div>
    <h1 class="text-3xl md:text-4xl font-bold text-white mt-8 mb-2 tracking-tight">BALAI MONITOR SFR KELAS II PALU</h1>
   </header><!-- Main Card -->
   <main class="max-w-2xl mx-auto fade-in" style="animation-delay: 0.1s;">
    <div class="glass-effect rounded-3xl overflow-hidden card-hover glow-effect"><!-- Card Header with Gradient -->
     <div class="relative h-32 bg-gradient-to-br from-cyan-500 to-blue-600 overflow-hidden">
      <div class="absolute inset-0 opacity-10">
       <div class="absolute top-0 right-0 w-40 h-40 bg-white rounded-full -mr-20 -mt-20"></div>
       <div class="absolute bottom-0 left-0 w-32 h-32 bg-white rounded-full -ml-16 -mb-16"></div>
      </div>
      <div class="relative h-full flex items-center px-6 md:px-8">
       <div>
        <h2 class="text-2xl md:text-3xl font-bold text-white flex items-center gap-3">
         <svg class="w-8 h-8" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
         </svg> Pendaftaran Tamu</h2>
        <p class="text-cyan-100 text-sm mt-1">Isi data di bawah dengan lengkap dan akurat</p>
       </div>
      </div>
     </div><!-- Form -->
     <form id="guest-form" class="p-6 md:p-10 space-y-6"><!-- Nama -->
      <div class="group"><label for="nama" class="block text-sm font-semibold text-slate-800 mb-3"> <span class="flex items-center gap-2"> <span class="w-1.5 h-1.5 bg-gradient-to-r from-cyan-500 to-blue-600 rounded-full"></span> Nama Lengkap </span> </label> <input type="text" id="nama" name="nama" required placeholder="Masukkan nama lengkap Anda" class="w-full px-5 py-3.5 input-modern rounded-xl text-slate-900 placeholder-slate-400 font-medium focus:outline-none">
      </div><!-- Alamat -->
      <div class="group"><label for="alamat" class="block text-sm font-semibold text-slate-800 mb-3"> <span class="flex items-center gap-2"> <span class="w-1.5 h-1.5 bg-gradient-to-r from-cyan-500 to-blue-600 rounded-full"></span> Alamat </span> </label> <textarea id="alamat" name="alamat" rows="3" required placeholder="Masukkan alamat lengkap Anda" class="w-full px-5 py-3.5 input-modern rounded-xl text-slate-900 placeholder-slate-400 font-medium resize-none focus:outline-none"></textarea>
      </div><!-- Grid 2 Kolom -->
      <div class="grid md:grid-cols-2 gap-6"><!-- Instansi -->
       <div class="group"><label for="instansi" class="block text-sm font-semibold text-slate-800 mb-3"> <span class="flex items-center gap-2"> <span class="w-1.5 h-1.5 bg-gradient-to-r from-cyan-500 to-blue-600 rounded-full"></span> Instansi / Perusahaan </span> </label> <input type="text" id="instansi" name="instansi" required placeholder="Nama instansi" class="w-full px-5 py-3.5 input-modern rounded-xl text-slate-900 placeholder-slate-400 font-medium focus:outline-none">
       </div><!-- Jenis Keperluan -->
       <div class="group"><label for="keperluan" class="block text-sm font-semibold text-slate-800 mb-3"> <span class="flex items-center gap-2"> <span class="w-1.5 h-1.5 bg-gradient-to-r from-cyan-500 to-blue-600 rounded-full"></span> Jenis Keperluan </span> </label>
        <div class="relative"><select id="keperluan" name="keperluan" required class="w-full px-5 py-3.5 input-modern rounded-xl text-slate-900 font-medium appearance-none bg-white focus:outline-none cursor-pointer"> <option value="" disabled selected>Pilih keperluan</option> <option value="Asistensi dan Konsultasi">Asistensi dan Konsultasi</option> <option value="Pengajuan Perizinan Frekuensi">Pengajuan Perizinan Frekuensi</option> <option value="Pengaduan Gangguan">Pengaduan Gangguan</option> <option value="Kunjungan Dinas">Kunjungan Dinas</option> <option value="Kerjasama">Kerjasama</option> <option value="Lainnya">Lainnya</option> </select>
         <div class="absolute inset-y-0 right-0 flex items-center pr-4 pointer-events-none">
          <svg class="w-5 h-5 text-cyan-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
          </svg>
         </div>
        </div>
       </div>
      </div><!-- Grid 2 Kolom -->
      <div class="grid md:grid-cols-2 gap-6"><!-- Telepon/WA -->
       <div class="group"><label for="telepon" class="block text-sm font-semibold text-slate-800 mb-3"> <span class="flex items-center gap-2"> <span class="w-1.5 h-1.5 bg-gradient-to-r from-cyan-500 to-blue-600 rounded-full"></span> Nomor Telepon / WA </span> </label>
        <div class="relative">
         <div class="absolute inset-y-0 left-0 flex items-center pl-4 pointer-events-none">
          <svg class="w-5 h-5 text-cyan-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
          </svg>
         </div><input type="tel" id="telepon" name="telepon" required placeholder="08123456789" pattern="[0-9]*" inputmode="numeric" class="w-full pl-12 pr-5 py-3.5 input-modern rounded-xl text-slate-900 placeholder-slate-400 font-medium focus:outline-none">
        </div>
       </div><!-- Tanggal Kunjungan -->
       <div class="group"><label for="tanggal" class="block text-sm font-semibold text-slate-800 mb-3"> <span class="flex items-center gap-2"> <span class="w-1.5 h-1.5 bg-gradient-to-r from-cyan-500 to-blue-600 rounded-full"></span> Tanggal Kunjungan </span> </label>
        <div class="relative">
         <div class="absolute inset-y-0 left-0 flex items-center pl-4 pointer-events-none">
          <svg class="w-5 h-5 text-cyan-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z" />
          </svg>
         </div><input type="date" id="tanggal" name="tanggal" required class="w-full pl-12 pr-5 py-3.5 input-modern rounded-xl text-slate-900 font-medium focus:outline-none">
        </div>
       </div>
      </div><!-- Submit Button -->
      <div class="pt-4"><button type="submit" id="submit-btn" class="w-full btn-modern text-white font-bold py-4 px-6 rounded-xl flex items-center justify-center gap-2 text-lg shadow-lg">
        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
        </svg><span>Simpan Data</span> </button>
      </div><!-- Success Message -->
      <div id="success-message" class="hidden p-5 bg-gradient-to-r from-green-50 to-emerald-50 border-l-4 border-green-500 rounded-xl">
       <p class="text-green-700 font-semibold flex items-center gap-3">
        <svg class="w-6 h-6 flex-shrink-0" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
        </svg><span>Data berhasil disimpan! Terima kasih telah mendaftar. ✨</span></p>
      </div>
     </form>
    </div>
   </main><!-- Footer -->
   <footer class="text-center mt-12 fade-in" style="animation-delay: 0.2s;">
    <p class="text-slate-500 text-sm font-medium">© 2026 Balai Monitor SFR Kelas II Palu</p>
    <p class="text-slate-600 text-xs mt-2">Kementerian Komunikasi dan Digital Republik Indonesia</p>
   </footer>
  </div>
  <script>
        // Toast notification function
        function showToast(message, type = 'success') {
            const container = document.getElementById('toast-container');
            const toast = document.createElement('div');
            
            const bgColor = type === 'success' 
                ? 'bg-gradient-to-r from-green-500 to-emerald-500' 
                : 'bg-gradient-to-r from-blue-500 to-cyan-500';
            
            toast.className = `toast-enter px-6 py-3 rounded-xl shadow-xl flex items-center gap-3 ${bgColor} text-white font-medium backdrop-blur-sm`;
            
            const icon = '<svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/></svg>';
            
            toast.innerHTML = `${icon}<span>${message}</span>`;
            container.appendChild(toast);

            setTimeout(() => {
                toast.classList.remove('toast-enter');
                toast.classList.add('toast-exit');
                setTimeout(() => toast.remove(), 400);
            }, 3500);
        }

        // Form submission handler
        function handleSubmit(e) {
            e.preventDefault();

            const successMsg = document.getElementById('success-message');
            const btn = document.getElementById('submit-btn');
            
            // Show loading state
            btn.disabled = true;
            btn.innerHTML = '<svg class="w-6 h-6 animate-spin" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15"/></svg>';
            
            // Simulate processing
            setTimeout(() => {
                showToast('✓ Data berhasil disimpan!', 'success');
                successMsg.classList.remove('hidden');
                document.getElementById('guest-form').reset();
                
                btn.disabled = false;
                btn.innerHTML = '<svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" /></svg><span>Simpan Data</span>';
                
                setTimeout(() => {
                    successMsg.classList.add('hidden');
                }, 5000);
            }, 1200);
        }

        // Setup form handler
        document.getElementById('guest-form').addEventListener('submit', handleSubmit);
    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9ccd33c2d55cd8da',t:'MTc3MDkxMTAxMi4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
