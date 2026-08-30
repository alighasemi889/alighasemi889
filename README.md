<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>alighasemi889 • GitHub</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;700&display=swap');
    body { font-family: 'Vazirmatn', sans-serif; }
    .hero-bg {
      background: linear-gradient(135deg, #0a0a0a, #1a1a2e, #16213e);
    }
    .nav-link { position: relative; transition: all 0.3s; }
    .nav-link:after {
      content: ''; position: absolute; width: 0; height: 2px;
      bottom: -2px; left: 0; background: linear-gradient(to right, #22c55e, #eab308);
      transition: width 0.4s ease;
    }
    .nav-link:hover:after { width: 100%; }
    .shimmer { animation: shimmer 3s infinite linear; }
    @keyframes shimmer { 0% { background-position: -200% 50%; } 100% { background-position: 200% 50%; } }
    .typewriter { overflow: hidden; border-right: 3px solid #22c55e; white-space: nowrap; animation: typing 4s steps(40, end) forwards, blink 0.7s step-end infinite; }
    @keyframes typing { from { width: 0 } to { width: 100% } }
    @keyframes blink { 50% { border-color: transparent } }
  </style>
</head>
<body class="hero-bg text-white min-h-screen">
  <!-- NAV -->
  <nav class="fixed top-0 left-0 right-0 z-50 bg-black/90 backdrop-blur-lg border-b border-green-500/30">
    <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <div class="w-12 h-12 bg-gradient-to-br from-green-400 to-emerald-500 rounded-2xl flex items-center justify-center text-3xl shadow-lg">
          💻
        </div>
        <span class="text-3xl font-bold tracking-tighter shimmer">alighasemi889</span>
      </div>
      <div class="hidden md:flex gap-8 text-lg font-medium">
        <a href="#" class="nav-link text-white hover:text-green-400">خانه</a>
        <a href="#" class="nav-link text-white hover:text-green-400">پروژه‌ها</a>
        <a href="#" class="nav-link text-white hover:text-green-400">درباره</a>
      </div>
      <div class="flex items-center gap-4">
        <button onclick="alert('این رید تمپلیه‌ایه! برای اولین صفحه گیت‌هابت آماده‌ست 💥')" 
                class="px-6 py-3 bg-green-500 hover:bg-green-600 rounded-2xl font-semibold flex items-center gap-2">
          <i class="fas fa-sign-in-alt"></i> ورود
        </button>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <section class="pt-20 min-h-screen flex items-center">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
      <div class="space-y-8">
        <div class="inline-flex items-center gap-2 bg-green-500/10 text-green-400 px-6 py-2 rounded-3xl text-sm font-medium">
          <div class="w-3 h-3 bg-green-400 rounded-full animate-pulse"></div>
          741 فالوور
        </div>
        
        <h1 class="text-7xl md:text-8xl font-black leading-none tracking-tighter">
          سلام<br>من <span class="text-green-400">علی</span>
        </h1>
        
        <div class="text-4xl font-semibold text-gray-300">
          <span class="text-green-400">Software Engineering</span> | 
          <span class="text-amber-400">React Developer</span> | 
          <span class="text-amber-400">Cybersecurity Enthusiast</span>
        </div>

        <p class="text-xl text-gray-300 max-w-md">
          برنامه‌نویس فول‌استک با تمرکز روی امنیت سایبری. 
          همیشه در حال ساخت پروژه‌های شیک و حرفه‌ای.
        </p>

        <div class="flex flex-wrap gap-4">
          <button onclick="document.getElementById('login-modal').classList.remove('hidden')" 
                  class="px-10 py-5 bg-gradient-to-r from-green-500 to-emerald-600 hover:from-green-600 hover:to-emerald-700 rounded-3xl text-xl font-semibold shadow-2xl shadow-green-500/30 transition-all flex items-center gap-3">
            شروع کنیم؟
            <i class="fas fa-arrow-left"></i>
          </button>
          
          <a href="https://ali-ghasemi-portfolio.vercel.app/" target="_blank"
             class="px-10 py-5 border-2 border-green-400 hover:bg-green-400 hover:text-black rounded-3xl text-xl font-semibold transition-all flex items-center gap-3">
            <i class="fas fa-external-link-alt"></i>
            لینکدون
          </a>
        </div>

        <div class="flex gap-8 pt-8 text-sm">
          <div>
            <div class="text-4xl font-bold text-green-400">741</div>
            <div class="text-gray-400">فالوور</div>
          </div>
          <div>
            <div class="text-4xl font-bold text-green-400">2.2k</div>
            <div class="text-gray-400">فالوینگ</div>
          </div>
        </div>
      </div>

      <!-- تصویر -->
      <div class="relative hidden md:block">
        <div class="absolute -inset-10 bg-gradient-to-br from-green-400/10 to-transparent rounded-[4rem] -rotate-6"></div>
        <img src="https://picsum.photos/id/1015/800/900" alt="علی غسمی" 
             class="relative z-10 rounded-3xl shadow-2xl border-8 border-green-500/30 rotate-6 hover:rotate-0 transition-transform" />
      </div>
    </div>
  </section>

  <!-- پروژه‌های pinned -->
  <section class="py-24 bg-black/60">
    <div class="max-w-7xl mx-auto px-6">
      <div class="flex justify-between items-end mb-12">
        <h2 class="text-5xl font-bold">پروژه‌های پین شده</h2>
      </div>
      <div class="grid md:grid-cols-4 gap-8">
        <div class="bg-gray-900 rounded-3xl overflow-hidden card-hover">
          <img src="https://picsum.photos/id/133/600/400" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="font-bold text-2xl">Calculator</h3>
            <p class="text-gray-400 text-sm">TypeScript</p>
          </div>
        </div>
        <div class="bg-gray-900 rounded-3xl overflow-hidden card-hover">
          <img src="https://picsum.photos/id/201/600/400" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="font-bold text-2xl">techblog</h3>
            <p class="text-gray-400 text-sm">React + Tailwind • AI, Programming, Cybersecurity</p>
          </div>
        </div>
        <div class="bg-gray-900 rounded-3xl overflow-hidden card-hover">
          <img src="https://picsum.photos/id/29/600/400" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="font-bold text-2xl">promptkit</h3>
            <p class="text-gray-400 text-sm">React + Tailwind</p>
          </div>
        </div>
        <div class="bg-gray-900 rounded-3xl overflow-hidden card-hover">
          <img src="https://picsum.photos/id/201/600/400" class="w-full h-48 object-cover" />
          <div class="p-6">
            <h3 class="font-bold text-2xl">personal-blog</h3>
            <p class="text-gray-400 text-sm">React, Vite, Tailwind</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black border-t border-green-500/20 py-16">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <div class="text-4xl font-bold mb-2">alighasemi889</div>
      <p class="text-gray-400">Founder of CodeMaster • Software Engineering | React Developer | Cybersecurity Enthusiast</p>
      <div class="mt-8 flex justify-center gap-8 text-2xl">
        <a href="https://github.com/alighasemi889" class="hover:text-green-400"><i class="fab fa-github"></i></a>
        <a href="https://ali-ghasemi-portfolio.vercel.app/" target="_blank" class="hover:text-green-400"><i class="fas fa-globe"></i></a>
      </div>
      <p class="mt-12 text-xs text-gray-500">© ۲۰۲۶ علی غسمی • GitHub Profile Red</p>
    </div>
  </footer>

  <!-- MODAL -->
  <div id="login-modal" class="hidden fixed inset-0 bg-black/90 flex items-center justify-center z-[999]">
    <div class="bg-gray-900 rounded-3xl p-10 w-full max-w-md">
      <h2 class="text-4xl font-bold text-center mb-8">ورود به گیت‌هاب</h2>
      <button onclick="alert('ورود موفقیت‌آمیز! 🎉\n(این رید تمپلیه‌ایه، تو خودت کد رو بری داخل HTML و تویگش کنی)')"
              class="w-full py-5 bg-green-500 hover:bg-green-600 rounded-3xl text-xl font-bold transition">
        ورود
      </button>
    </div>
  </div>

  <script>
    console.log('%cاولین صفحه گیت‌هابت آماده‌ست! 🔥', 'color:#22c55e; font-size:14px; font-weight:bold');
  </script>
</body>
</html>
