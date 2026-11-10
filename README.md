!DOCTYPE html>
<html lang="bn" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ওবায়দুল্লাহ টেলিকম - সেরা সেকেন্ড হ্যান্ড মোবাইল ও পেশাদার সার্ভিসিং সেন্টার</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Hind Siliguri for Bengali -->
    <link href="https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#0b0f19',
                            card: '#151c2e',
                            cyan: '#00f2fe',
                            blue: '#4facfe',
                            purple: '#7f00ff',
                            accent: '#3b82f6'
                        }
                    },
                    fontFamily: {
                        sans: ['Hind Siliguri', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Hind Siliguri', sans-serif;
            background-color: #0b0f19;
            color: #f3f4f6;
            overflow-x: hidden;
        }
        /* Custom Glassmorphism Styling */
        .glass-card {
            background: rgba(21, 28, 46, 0.7);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .glass-nav {
            background: rgba(11, 15, 25, 0.85);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);
        }
        .neon-glow-cyan {
            box-shadow: 0 0 25px rgba(0, 242, 254, 0.35);
        }
        .neon-glow-purple {
            box-shadow: 0 0 25px rgba(127, 0, 255, 0.35);
        }
        .text-gradient {
            background: linear-gradient(135deg, #00f2fe 0%, #4facfe 50%, #00c6ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .text-gradient-purple {
            background: linear-gradient(135deg, #a855f7 0%, #ec4899 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gradient-btn {
            background: linear-gradient(90deg, #00f2fe 0%, #4facfe 100%);
            transition: all 0.3s ease;
        }
        .gradient-btn:hover {
            opacity: 0.9;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px -10px rgba(0, 242, 254, 0.5);
        }
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0b0f19;
        }
        ::-webkit-scrollbar-thumb {
            background: #1e293b;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #00f2fe;
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-cyan selection:text-black">

    <!-- Background Ambient Glow Lights -->
    <div class="fixed top-0 left-1/4 w-96 h-96 bg-brand-cyan/10 rounded-full blur-[120px] pointer-events-none -z-10"></div>
    <div class="fixed bottom-1/3 right-1/4 w-96 h-96 bg-brand-purple/10 rounded-full blur-[140px] pointer-events-none -z-10"></div>

    <!-- 1. Header / Navigation -->
    <header class="fixed top-0 left-0 w-full z-50 glass-nav transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand Logo -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="w-12 h-12 rounded-xl bg-gradient-to-tr from-brand-cyan to-brand-blue flex items-center justify-center text-black font-bold text-2xl shadow-lg transform group-hover:rotate-6 transition-all duration-300">
                        <i class="fa-solid fa-mobile-screen-button"></i>
                    </div>
                    <div>
                        <span class="text-2xl font-extrabold tracking-wide text-white block">ওবায়দুল্লাহ <span class="text-gradient">টেলিকম</span></span>
                        <span class="text-xs text-gray-400 font-medium block">মোবাইল সেলস ও সার্ভিসিং</span>
                    </div>
                </a>

                <!-- Desktop Nav Links -->
                <nav class="hidden md:flex items-center gap-8">
                    <a href="#home" class="text-gray-300 hover:text-brand-cyan font-medium transition-colors">হোম</a>
                    <a href="#used-phones" class="text-gray-300 hover:text-brand-cyan font-medium transition-colors">সেকেন্ড হ্যান্ড ফোন</a>
                    <a href="#servicing" class="text-gray-300 hover:text-brand-cyan font-medium transition-colors">সার্ভিসিং</a>
                    <a href="#estimator" class="text-gray-300 hover:text-brand-cyan font-medium transition-colors">খরচ গণনাকারী</a>
                    <a href="#features" class="text-gray-300 hover:text-brand-cyan font-medium transition-colors">কেন আমরা</a>
                    <a href="#contact" class="text-gray-300 hover:text-brand-cyan font-medium transition-colors">যোগাযোগ</a>
                </nav>

                <!-- Call Action & Mobile Menu Toggle -->
                <div class="flex items-center gap-4">
                    <a href="tel:+8801700000000" class="hidden sm:inline-flex items-center gap-2 px-5 py-2.5 rounded-full gradient-btn text-black font-bold text-sm shadow-md">
                        <i class="fa-solid fa-phone"></i>
                        <span>কল করুন</span>
                    </a>

                    <!-- Mobile Menu Button -->
                    <button id="mobileMenuBtn" class="md:hidden text-gray-300 hover:text-white focus:outline-none p-2">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Drawer -->
        <div id="mobileMenu" class="hidden md:hidden glass-card border-t border-gray-800 px-4 pt-4 pb-6 space-y-3">
            <a href="#home" class="mobile-nav-link block px-3 py-2 rounded-lg text-base font-medium text-gray-200 hover:bg-gray-800">হোম</a>
            <a href="#used-phones" class="mobile-nav-link block px-3 py-2 rounded-lg text-base font-medium text-gray-200 hover:bg-gray-800">সেকেন্ড হ্যান্ড ফোন</a>
            <a href="#servicing" class="mobile-nav-link block px-3 py-2 rounded-lg text-base font-medium text-gray-200 hover:bg-gray-800">সার্ভিসিং</a>
            <a href="#estimator" class="mobile-nav-link block px-3 py-2 rounded-lg text-base font-medium text-gray-200 hover:bg-gray-800">খরচ গণনাকারী</a>
            <a href="#features" class="mobile-nav-link block px-3 py-2 rounded-lg text-base font-medium text-gray-200 hover:bg-gray-800">কেন আমরা</a>
            <a href="#contact" class="mobile-nav-link block px-3 py-2 rounded-lg text-base font-medium text-gray-200 hover:bg-gray-800">যোগাযোগ</a>
            <a href="tel:+8801700000000" class="flex items-center justify-center gap-2 w-full py-3 mt-4 rounded-xl gradient-btn text-black font-bold">
                <i class="fa-solid fa-phone"></i>
                <span>কল করুন (+8801700000000)</span>
            </a>
        </div>
    </header>

    <!-- 2. Hero Section -->
    <section id="home" class="pt-32 pb-20 md:pt-40 md:pb-28 relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                
                <!-- Left Text Content -->
                <div class="space-y-6 text-center md:text-left">
                    <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-brand-cyan/10 border border-brand-cyan/30 text-brand-cyan text-sm font-semibold">
                        <span class="w-2 h-2 rounded-full bg-brand-cyan animate-ping"></span>
                        ১০০% খাঁটি ও সেরা কন্ডিশন গ্যারান্টি
                    </div>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black leading-tight text-white">
                        আপনার বিশ্বস্ত মোবাইল <br class="hidden sm:inline">
                        <span class="text-gradient">ক্রয়-বিক্রয়</span> ও 
                        <span class="text-gradient-purple">সার্ভিসিং</span> সেন্টার
                    </h1>

                    <p class="text-gray-300 text-lg md:text-xl max-w-xl leading-relaxed">
                        আইফোন, শাওমি, রিয়েলমি, অপ্পো, ভিভো সহ সব ব্যান্ডের সাশ্রয়ী সেকেন্ড হ্যান্ড ফোন কিনুন এবং অভিজ্ঞ টেকনিশিয়ান দ্বারা উন্নত প্রযুক্তিতে যেকোনো ফোন মেরামত করুন।
                    </p>

                    <!-- CTA Action Buttons -->
                    <div class="flex flex-col sm:flex-row items-center justify-center md:justify-start gap-4 pt-4">
                        <a href="#used-phones" class="w-full sm:w-auto px-8 py-4 rounded-xl gradient-btn text-black font-bold text-lg flex items-center justify-center gap-3">
                            <i class="fa-solid fa-shop"></i>
                            <span>ফোন সংগ্রহ দেখুন</span>
                        </a>
                        <a href="#servicing" class="w-full sm:w-auto px-8 py-4 rounded-xl glass-card border border-brand-cyan/40 text-white font-bold text-lg hover:border-brand-cyan transition-all flex items-center justify-center gap-3">
                            <i class="fa-solid fa-wrench text-brand-cyan"></i>
                            <span>সার্ভিস বুক করুন</span>
                        </a>
                    </div>

                    <!-- Highlights Stats -->
                    <div class="grid grid-cols-3 gap-4 pt-8 border-t border-gray-800">
                        <div>
                            <p class="text-2xl sm:text-3xl font-extrabold text-white text-gradient">২৫০০+</p>
                            <p class="text-xs sm:text-sm text-gray-400">হ্যাপি কাস্টমার</p>
                        </div>
                        <div>
                            <p class="text-2xl sm:text-3xl font-extrabold text-white text-gradient-purple">১০০%</p>
                            <p class="text-xs sm:text-sm text-gray-400">জেনুইন পার্টস</p>
                        </div>
                        <div>
                            <p class="text-2xl sm:text-3xl font-extrabold text-white text-gradient">১০ মি:</p>
                            <p class="text-xs sm:text-sm text-gray-400">দ্রুত চেকআপ</p>
                        </div>
                    </div>
                </div>

                <!-- Right Visual Banner Card -->
                <div class="relative flex justify-center">
                    <div class="w-full max-w-md glass-card rounded-3xl p-6 border border-white/10 relative z-10 shadow-2xl overflow-hidden">
                        <div class="absolute top-0 right-0 -mr-16 -mt-16 w-48 h-48 bg-brand-cyan/20 rounded-full blur-3xl"></div>
                        
                        <!-- Floating Badge -->
                        <div class="absolute top-8 right-8 bg-black/60 backdrop-blur-md px-3 py-1.5 rounded-lg border border-brand-cyan/40 flex items-center gap-2 text-xs font-semibold text-brand-cyan">
                            <i class="fa-solid fa-shield-halved"></i> ৭ দিনের টেস্ট গ্যারান্টি
                        </div>

                        <!-- Phone Showcase Mock Graphic -->
                        <div class="my-6 py-8 flex justify-center items-center relative">
                            <div class="w-48 h-96 bg-gray-900 border-4 border-gray-700 rounded-[40px] shadow-2xl relative overflow-hidden flex flex-col items-center justify-between p-3 transform hover:scale-105 transition-transform duration-500">
                                <!-- Phone Notch -->
                                <div class="w-20 h-4 bg-gray-800 rounded-b-xl z-20"></div>
                                <!-- Display Content -->
                                <div class="w-full h-full bg-gradient-to-b from-slate-900 via-indigo-950 to-slate-900 rounded-[28px] absolute top-0 left-0 flex flex-col items-center justify-center p-4 text-center">
                                    <i class="fa-solid fa-mobile-screen text-5xl text-brand-cyan mb-3 animate-pulse"></i>
                                    <span class="text-xs text-gray-300 font-semibold">Obaidullah Telecom</span>
                                    <span class="text-[10px] text-brand-blue mt-1">Premium Servicing</span>
                                </div>
                            </div>

                            <!-- Decorative Floating Elements -->
                            <div class="absolute -left-4 bottom-12 glass-card p-3 rounded-2xl border border-white/20 flex items-center gap-3 shadow-xl animate-bounce" style="animation-duration: 4s;">
                                <div class="w-10 h-10 rounded-xl bg-purple-600/30 flex items-center justify-center text-purple-400">
                                    <i class="fa-solid fa-unlock text-lg"></i>
                                </div>
                                <div>
                                    <p class="text-xs font-bold text-white">FRP & Lock Unlocking</p>
                                    <p class="text-[10px] text-gray-400">তাত্ক্ষণিক সমাধান</p>
                                </div>
                            </div>
                        </div>

                        <div class="bg-gray-900/80 rounded-2xl p-4 border border-gray-800">
                            <div class="flex items-center justify-between text-sm">
                                <span class="text-gray-300 font-medium">বিশেষ সুবিধা:</span>
                                <span class="text-brand-cyan font-bold">ক্যাশ অন ডেলিভারি / শপ পিকআপ</span>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- 3. Supported Brands Carousel / Grid Banner -->
    <section class="py-10 bg-slate-950/60 border-y border-gray-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <p class="text-center text-xs sm:text-sm font-semibold tracking-wider text-gray-400 uppercase mb-8">
                আমরা আপনার পছন্দের সকল ব্র্যান্ড নিয়ে কাজ করি
            </p>
            <div class="grid grid-cols-3 sm:grid-cols-5 lg:grid-cols-9 gap-4 items-center justify-center">
                <!-- Apple -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <i class="fa-brands fa-apple text-3xl text-gray-300 group-hover:text-white transition-colors"></i>
                    <span class="text-xs text-gray-400 mt-2 font-medium">iPhone</span>
                </div>
                <!-- Xiaomi -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-xl font-bold text-orange-500 group-hover:scale-110 transition-transform">mi</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">Redmi/Xiaomi</span>
                </div>
                <!-- Samsung -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-black text-blue-500 tracking-tighter group-hover:scale-105 transition-transform">SAMSUNG</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">Samsung</span>
                </div>
                <!-- Realme -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-extrabold text-yellow-400 lowercase">realme</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">Realme</span>
                </div>
                <!-- Vivo -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-bold text-blue-400 lowercase">vivo</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">Vivo</span>
                </div>
                <!-- OPPO -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-bold text-emerald-400">oppo</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">OPPO</span>
                </div>
                <!-- Tecno -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-bold text-cyan-400">TECNO</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">Tecno</span>
                </div>
                <!-- Infinix -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-bold text-green-400">Infinix</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">Infinix</span>
                </div>
                <!-- POCO -->
                <div class="glass-card p-3 sm:p-4 rounded-xl flex flex-col items-center justify-center hover:border-brand-cyan transition-all group">
                    <span class="text-base font-black text-yellow-500">POCO</span>
                    <span class="text-xs text-gray-400 mt-2 font-medium">POCO</span>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Second-Hand Mobile Collection Section (Interactive Filter) -->
    <section id="used-phones" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">
                    ধামাকা <span class="text-gradient">সেকেন্ড হ্যান্ড মোবাইল</span> স্টক
                </h2>
                <p class="text-gray-400 mt-3 text-base sm:text-lg">
                    প্রতিটি ফোন সম্পূর্ণ টেস্ট করা, একদম ফ্রেশ কন্ডিশন ও মানি-ব্যাক ওয়ারেন্টি সহ শতভাগ নিশ্চিত ক্যাশ মেমোতে দেওয়া হয়।
                </p>
            </div>

            <!-- Brand Filter Tabs -->
            <div class="flex items-center justify-start md:justify-center gap-2 overflow-x-auto pb-4 mb-10 scrollbar-none">
                <button onclick="filterPhones('all')" class="filter-btn active-tab px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap bg-brand-cyan text-black shadow-lg">
                    সব ফোন
                </button>
                <button onclick="filterPhones('iphone')" class="filter-btn px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap glass-card text-gray-300 hover:text-white hover:border-brand-cyan">
                    Apple iPhone
                </button>
                <button onclick="filterPhones('xiaomi')" class="filter-btn px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap glass-card text-gray-300 hover:text-white hover:border-brand-cyan">
                    Xiaomi / Redmi
                </button>
                <button onclick="filterPhones('samsung')" class="filter-btn px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap glass-card text-gray-300 hover:text-white hover:border-brand-cyan">
                    Samsung
                </button>
                <button onclick="filterPhones('realme')" class="filter-btn px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap glass-card text-gray-300 hover:text-white hover:border-brand-cyan">
                    Realme
                </button>
                <button onclick="filterPhones('vivo')" class="filter-btn px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap glass-card text-gray-300 hover:text-white hover:border-brand-cyan">
                    Vivo / OPPO
                </button>
                <button onclick="filterPhones('tecno')" class="filter-btn px-5 py-2.5 rounded-xl font-semibold text-sm transition-all whitespace-nowrap glass-card text-gray-300 hover:text-white hover:border-brand-cyan">
                    Tecno / Infinix
                </button>
            </div>

            <!-- Phone Cards Grid -->
            <div id="phoneGrid" class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                
                <!-- Phone Card 1: iPhone 13 Pro -->
                <div class="phone-card glass-card rounded-2xl p-5 border border-gray-800 hover:border-brand-cyan transition-all duration-300 flex flex-col justify-between group" data-category="iphone">
                    <div>
                        <div class="relative bg-slate-900 rounded-xl p-6 mb-4 flex justify-center items-center overflow-hidden">
                            <span class="absolute top-3 left-3 bg-emerald-500/20 text-emerald-400 text-xs font-bold px-2.5 py-1 rounded-md border border-emerald-500/30">
                                Mint Condition (৯৯%)
                            </span>
                            <i class="fa-solid fa-mobile-screen-button text-7xl text-gray-600 group-hover:scale-110 group-hover:text-brand-cyan transition-all duration-300 py-6"></i>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold text-brand-cyan bg-brand-cyan/10 px-2.5 py-1 rounded-md">Apple</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-battery-full text-green-400"></i> Battery Health 87%</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mt-2">iPhone 13 Pro (128GB)</h3>
                        <p class="text-xs text-gray-400 mt-1">Waterproof, Full Fresh, USA Variant</p>
                        
                        <div class="mt-4 pt-3 border-t border-gray-800 grid grid-cols-2 gap-2 text-xs text-gray-300">
                            <div><i class="fa-solid fa-microchip text-brand-cyan"></i> RAM: 6 GB</div>
                            <div><i class="fa-solid fa-hard-drive text-brand-cyan"></i> ROM: 128 GB</div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-gray-800/80 flex items-center justify-between">
                        <div>
                            <span class="text-xs text-gray-400 block">ধামাকা মূল্য</span>
                            <span class="text-xl font-extrabold text-white">৳ ৬৮,৫০০</span>
                        </div>
                        <button onclick="openBookingModal('iPhone 13 Pro (128GB)', '৳ ৬৮,৫০০')" class="px-4 py-2 rounded-lg gradient-btn text-black font-bold text-sm">
                            অর্ডার করুন
                        </button>
                    </div>
                </div>

                <!-- Phone Card 2: Redmi Note 12 -->
                <div class="phone-card glass-card rounded-2xl p-5 border border-gray-800 hover:border-brand-cyan transition-all duration-300 flex flex-col justify-between group" data-category="xiaomi">
                    <div>
                        <div class="relative bg-slate-900 rounded-xl p-6 mb-4 flex justify-center items-center overflow-hidden">
                            <span class="absolute top-3 left-3 bg-blue-500/20 text-blue-400 text-xs font-bold px-2.5 py-1 rounded-md border border-blue-500/30">
                                Super Fresh
                            </span>
                            <i class="fa-solid fa-mobile-screen text-7xl text-gray-600 group-hover:scale-110 group-hover:text-brand-cyan transition-all duration-300 py-6"></i>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold text-orange-400 bg-orange-400/10 px-2.5 py-1 rounded-md">Xiaomi</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-box text-yellow-400"></i> সাথে চার্জার পাবে</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mt-2">Redmi Note 12 4G</h3>
                        <p class="text-xs text-gray-400 mt-1">Super AMOLED, 120Hz Refresh</p>
                        
                        <div class="mt-4 pt-3 border-t border-gray-800 grid grid-cols-2 gap-2 text-xs text-gray-300">
                            <div><i class="fa-solid fa-microchip text-brand-cyan"></i> RAM: 8 GB</div>
                            <div><i class="fa-solid fa-hard-drive text-brand-cyan"></i> ROM: 128 GB</div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-gray-800/80 flex items-center justify-between">
                        <div>
                            <span class="text-xs text-gray-400 block">ধামাকা মূল্য</span>
                            <span class="text-xl font-extrabold text-white">৳ ১৪,২০০</span>
                        </div>
                        <button onclick="openBookingModal('Redmi Note 12 4G', '৳ ১৪,২০০')" class="px-4 py-2 rounded-lg gradient-btn text-black font-bold text-sm">
                            অর্ডার করুন
                        </button>
                    </div>
                </div>

                <!-- Phone Card 3: Samsung Galaxy A54 -->
                <div class="phone-card glass-card rounded-2xl p-5 border border-gray-800 hover:border-brand-cyan transition-all duration-300 flex flex-col justify-between group" data-category="samsung">
                    <div>
                        <div class="relative bg-slate-900 rounded-xl p-6 mb-4 flex justify-center items-center overflow-hidden">
                            <span class="absolute top-3 left-3 bg-emerald-500/20 text-emerald-400 text-xs font-bold px-2.5 py-1 rounded-md border border-emerald-500/30">
                                Official Phone
                            </span>
                            <i class="fa-solid fa-mobile text-7xl text-gray-600 group-hover:scale-110 group-hover:text-brand-cyan transition-all duration-300 py-6"></i>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold text-blue-400 bg-blue-400/10 px-2.5 py-1 rounded-md">Samsung</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-shield text-emerald-400"></i> ৫ মাস ওয়ারেন্টি বাকি</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mt-2">Samsung Galaxy A54 5G</h3>
                        <p class="text-xs text-gray-400 mt-1">Awesome Lime, Camera Phone</p>
                        
                        <div class="mt-4 pt-3 border-t border-gray-800 grid grid-cols-2 gap-2 text-xs text-gray-300">
                            <div><i class="fa-solid fa-microchip text-brand-cyan"></i> RAM: 8 GB</div>
                            <div><i class="fa-solid fa-hard-drive text-brand-cyan"></i> ROM: 256 GB</div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-gray-800/80 flex items-center justify-between">
                        <div>
                            <span class="text-xs text-gray-400 block">ধামাকা মূল্য</span>
                            <span class="text-xl font-extrabold text-white">৳ ২৭,৯০০</span>
                        </div>
                        <button onclick="openBookingModal('Samsung Galaxy A54 5G', '৳ ২৭,৯০০')" class="px-4 py-2 rounded-lg gradient-btn text-black font-bold text-sm">
                            অর্ডার করুন
                        </button>
                    </div>
                </div>

                <!-- Phone Card 4: Realme GT Neo 3 -->
                <div class="phone-card glass-card rounded-2xl p-5 border border-gray-800 hover:border-brand-cyan transition-all duration-300 flex flex-col justify-between group" data-category="realme">
                    <div>
                        <div class="relative bg-slate-900 rounded-xl p-6 mb-4 flex justify-center items-center overflow-hidden">
                            <span class="absolute top-3 left-3 bg-purple-500/20 text-purple-400 text-xs font-bold px-2.5 py-1 rounded-md border border-purple-500/30">
                                Gaming Beast
                            </span>
                            <i class="fa-solid fa-mobile-screen-button text-7xl text-gray-600 group-hover:scale-110 group-hover:text-brand-cyan transition-all duration-300 py-6"></i>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold text-yellow-400 bg-yellow-400/10 px-2.5 py-1 rounded-md">Realme</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-bolt text-yellow-400"></i> 80W Fast Charge</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mt-2">Realme GT Neo 3</h3>
                        <p class="text-xs text-gray-400 mt-1">Dimensity 8100 5G Processor</p>
                        
                        <div class="mt-4 pt-3 border-t border-gray-800 grid grid-cols-2 gap-2 text-xs text-gray-300">
                            <div><i class="fa-solid fa-microchip text-brand-cyan"></i> RAM: 8 GB</div>
                            <div><i class="fa-solid fa-hard-drive text-brand-cyan"></i> ROM: 128 GB</div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-gray-800/80 flex items-center justify-between">
                        <div>
                            <span class="text-xs text-gray-400 block">ধামাকা মূল্য</span>
                            <span class="text-xl font-extrabold text-white">৳ ২২,৫০০</span>
                        </div>
                        <button onclick="openBookingModal('Realme GT Neo 3', '৳ ২২,৫০০')" class="px-4 py-2 rounded-lg gradient-btn text-black font-bold text-sm">
                            অর্ডার করুন
                        </button>
                    </div>
                </div>

                <!-- Phone Card 5: Vivo V27 5G -->
                <div class="phone-card glass-card rounded-2xl p-5 border border-gray-800 hover:border-brand-cyan transition-all duration-300 flex flex-col justify-between group" data-category="vivo">
                    <div>
                        <div class="relative bg-slate-900 rounded-xl p-6 mb-4 flex justify-center items-center overflow-hidden">
                            <span class="absolute top-3 left-3 bg-emerald-500/20 text-emerald-400 text-xs font-bold px-2.5 py-1 rounded-md border border-emerald-500/30">
                                Fresh Like New
                            </span>
                            <i class="fa-solid fa-mobile-screen text-7xl text-gray-600 group-hover:scale-110 group-hover:text-brand-cyan transition-all duration-300 py-6"></i>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold text-blue-400 bg-blue-400/10 px-2.5 py-1 rounded-md">Vivo</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-camera text-brand-cyan"></i> Aura Light Portrait</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mt-2">Vivo V27 5G</h3>
                        <p class="text-xs text-gray-400 mt-1">Curved 3D Display, Magic Blue</p>
                        
                        <div class="mt-4 pt-3 border-t border-gray-800 grid grid-cols-2 gap-2 text-xs text-gray-300">
                            <div><i class="fa-solid fa-microchip text-brand-cyan"></i> RAM: 12 GB</div>
                            <div><i class="fa-solid fa-hard-drive text-brand-cyan"></i> ROM: 256 GB</div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-gray-800/80 flex items-center justify-between">
                        <div>
                            <span class="text-xs text-gray-400 block">ধামাকা মূল্য</span>
                            <span class="text-xl font-extrabold text-white">৳ ২৫,০০০</span>
                        </div>
                        <button onclick="openBookingModal('Vivo V27 5G', '৳ ২৫,০০০')" class="px-4 py-2 rounded-lg gradient-btn text-black font-bold text-sm">
                            অর্ডার করুন
                        </button>
                    </div>
                </div>

                <!-- Phone Card 6: Tecno Camon 20 Pro -->
                <div class="phone-card glass-card rounded-2xl p-5 border border-gray-800 hover:border-brand-cyan transition-all duration-300 flex flex-col justify-between group" data-category="tecno">
                    <div>
                        <div class="relative bg-slate-900 rounded-xl p-6 mb-4 flex justify-center items-center overflow-hidden">
                            <span class="absolute top-3 left-3 bg-amber-500/20 text-amber-400 text-xs font-bold px-2.5 py-1 rounded-md border border-amber-500/30">
                                বাজেট সেরা ফোন
                            </span>
                            <i class="fa-solid fa-mobile-screen-button text-7xl text-gray-600 group-hover:scale-110 group-hover:text-brand-cyan transition-all duration-300 py-6"></i>
                        </div>
                        <div class="flex items-center justify-between">
                            <span class="text-xs font-semibold text-cyan-400 bg-cyan-400/10 px-2.5 py-1 rounded-md">Tecno</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-box text-yellow-400"></i> ফুল বক্স ও ক্যাশমেমো</span>
                        </div>
                        <h3 class="text-xl font-bold text-white mt-2">Tecno Camon 20 Pro</h3>
                        <p class="text-xs text-gray-400 mt-1">64MP RGBW OIS Lens</p>
                        
                        <div class="mt-4 pt-3 border-t border-gray-800 grid grid-cols-2 gap-2 text-xs text-gray-300">
                            <div><i class="fa-solid fa-microchip text-brand-cyan"></i> RAM: 8 GB</div>
                            <div><i class="fa-solid fa-hard-drive text-brand-cyan"></i> ROM: 256 GB</div>
                        </div>
                    </div>
                    <div class="mt-6 pt-4 border-t border-gray-800/80 flex items-center justify-between">
                        <div>
                            <span class="text-xs text-gray-400 block">ধামাকা মূল্য</span>
                            <span class="text-xl font-extrabold text-white">৳ ১৫,৮০০</span>
                        </div>
                        <button onclick="openBookingModal('Tecno Camon 20 Pro', '৳ ১৫,৮০০')" class="px-4 py-2 rounded-lg gradient-btn text-black font-bold text-sm">
                            অর্ডার করুন
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- 5. Mobile Repair & Servicing Section -->
    <section id="servicing" class="py-20 bg-slate-950/70 border-t border-gray-800 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-brand-cyan font-semibold text-sm tracking-wide uppercase">বিশেষজ্ঞ সমাধান</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-1">
                    মোবাইল <span class="text-gradient-purple">সার্ভিসিং ও লকিং</span> সলিউশন
                </h2>
                <p class="text-gray-400 mt-3 text-base sm:text-lg">
                    যে কোনো জটিল হার্ডওয়্যার ও সফটওয়্যার সমস্যা তাত্ক্ষণিক সমাধান করুন অভিজ্ঞ টেকনিশিয়ানের মাধ্যমে।
                </p>
            </div>

            <!-- Servicing Grid -->
            <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- Service 1 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 hover:border-brand-purple/60 transition-all duration-300 group">
                    <div class="w-14 h-14 rounded-2xl bg-purple-600/20 border border-purple-500/30 flex items-center justify-center text-purple-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-lock-open"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">FRP ও কান্ট্রি লক আনলক</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        গুগল অ্যাকাউন্ট FRP, আইক্লাউড, শিয়াওমি মি-অ্যাকাউন্ট ও যে কোনো কান্ট্রি লক ১০০% সেফ উপায়ে আনলক করা হয়।
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> অনলাইন ও অফলাইন সার্ভিস</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> ডাটা না হারিয়ে লক রিমুভ (নির্দিষ্ট মডেলে)</li>
                    </ul>
                </div>

                <!-- Service 2 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 hover:border-brand-cyan/60 transition-all duration-300 group">
                    <div class="w-14 h-14 rounded-2xl bg-cyan-600/20 border border-cyan-500/30 flex items-center justify-center text-brand-cyan text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-display"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">ডিসপ্লে ও টাচ চেঞ্জ</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        অরিজিনাল OLED/AMOLED ডিসপ্লে প্রতিস্থাপন এবং গ্লাস চেঞ্জিং সুনির্দিষ্ট ভ্যাকুয়াম মেশিনে করা হয়।
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> ১০০% অরিজিনাল কালার ও টাচ রেসপন্স</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> ৩০ থেকে ৪৫ মিনিটের মধ্যে সার্ভিস</li>
                    </ul>
                </div>

                <!-- Service 3 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 hover:border-blue-500/60 transition-all duration-300 group">
                    <div class="w-14 h-14 rounded-2xl bg-blue-600/20 border border-blue-500/30 flex items-center justify-center text-blue-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-microchip"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">মাদারবোর্ড ও CPU/IC রিবেলিং</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        ডেড মাদারবোর্ড সচল করা, CPU রিবেলিং, ওয়াটার ড্যামেজ প্রবলেম ও পাওয়ার আইসি প্রফেশনাল মাইক্রোস্কোপে মেরামত।
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> অ্যাডভান্সড মাইক্রো সোল্ডারিং</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> সলিউশন নো-ফিক্স নো-ফি পলিসি</li>
                    </ul>
                </div>

                <!-- Service 4 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 hover:border-emerald-500/60 transition-all duration-300 group">
                    <div class="w-14 h-14 rounded-2xl bg-emerald-600/20 border border-emerald-500/30 flex items-center justify-center text-emerald-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">সফটওয়্যার ফ্ল্যাশিং ও আপডেট</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        ফোন লোগো হ্যাং হয়ে থাকা, অটো রিস্টার্ট মারার সমস্যা, বা গ্লোবাল রম ফ্ল্যাশ সমাধান করা হয়।
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> লেটেস্ট অফিসিয়াল রম ইনস্টলেশন</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> নেটওয়ার্ক ও আইএমইআই (IMEI) ফিক্স</li>
                    </ul>
                </div>

                <!-- Service 5 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 hover:border-amber-500/60 transition-all duration-300 group">
                    <div class="w-14 h-14 rounded-2xl bg-amber-600/20 border border-amber-500/30 flex items-center justify-center text-amber-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-battery-three-quarters"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">অরিজিনাল ব্যাটারি ও চার্জিং</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        দ্রুত চার্জ শেষ হওয়া বা ফুল ওঠা ব্যাটারি পরিবর্তন এবং চার্জিং পোর্ট সকেট রিপেয়ার করা হয়।
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> হাই-ক্যাপাসিটি ব্যাটারি ব্যাকআপ</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> ৬ মাসের রিপ্লেসমেন্ট ওয়ারেন্টি</li>
                    </ul>
                </div>

                <!-- Service 6 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 hover:border-rose-500/60 transition-all duration-300 group">
                    <div class="w-14 h-14 rounded-2xl bg-rose-600/20 border border-rose-500/30 flex items-center justify-center text-rose-400 text-2xl mb-6 group-hover:scale-110 transition-transform">
                        <i class="fa-solid fa-database"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-2">ডেটা রিকভারি ও স্পিকার সমাধান</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        নষ্ট ফোন থেকে হারিয়ে যাওয়া গুরুত্বপূর্ণ ডেটা উদ্ধার এবং স্পিকার, মাউথ স্পিকার মেরামত।
                    </p>
                    <ul class="mt-4 space-y-2 text-xs text-gray-300">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> শতভাগ গোপনীয়তা বজায় রাখা</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-brand-cyan"></i> পরিষ্কার ক্লিয়ার সাউন্ড ফিক্স</li>
                    </ul>
                </div>

            </div>
            
            <!-- Quick Service Booking Callout Banner -->
            <div class="mt-12 glass-card rounded-2xl p-8 border border-brand-cyan/30 flex flex-col md:flex-row items-center justify-between gap-6">
                <div>
                    <h4 class="text-2xl font-bold text-white">ফোনে সমস্যা হচ্ছে? সরাসরি কল দিয়ে পরামর্শ নিন</h4>
                    <p class="text-gray-300 mt-1">আমাদের দক্ষ টেকনিশিয়ান ফ্রিতে পরামর্শ দেবেন আপনার ফোনের সমস্যার সমাধানে।</p>
                </div>
                <a href="https://wa.me/8801700000000" target="_blank" class="px-6 py-3.5 rounded-xl bg-emerald-500 hover:bg-emerald-600 text-black font-bold flex items-center gap-3 transition-colors shrink-0">
                    <i class="fa-brands fa-whatsapp text-xl"></i>
                    <span>হোয়াটসঅ্যাপে কথা বলুন</span>
                </a>
            </div>

        </div>
    </section>

    <!-- 6. Interactive Price / Repair Cost Estimator Tool -->
    <section id="estimator" class="py-20 relative">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="glass-card rounded-3xl p-6 sm:p-10 border border-brand-cyan/20 relative overflow-hidden">
                <div class="text-center mb-8">
                    <span class="text-xs font-bold text-brand-cyan uppercase tracking-widest bg-brand-cyan/10 px-3 py-1 rounded-full">স্বয়ংক্রিয় টুল</span>
                    <h2 class="text-3xl font-extrabold text-white mt-2">সার্ভিসিং ও আনলক খরচ হিসাব করুন</h2>
                    <p class="text-gray-400 text-sm mt-1">আপনার ফোনের ব্র্যান্ড এবং সমস্যা সিলেক্ট করে আনুমানিক সার্ভিস চার্জ জেনে নিন</p>
                </div>

                <div class="grid sm:grid-cols-2 gap-6">
                    <!-- Brand Select -->
                    <div>
                        <label class="block text-sm font-semibold text-gray-300 mb-2">ফোনের ব্র্যান্ড নির্বাচন করুন</label>
                        <select id="estBrand" class="w-full bg-slate-900 border border-gray-700 text-white rounded-xl px-4 py-3 focus:outline-none focus:border-brand-cyan">
                            <option value="iphone">Apple iPhone</option>
                            <option value="xiaomi">Xiaomi / Redmi / POCO</option>
                            <option value="samsung">Samsung</option>
                            <option value="realme">Realme</option>
                            <option value="vivo">Vivo / OPPO</option>
                            <option value="tecno">Tecno / Infinix</option>
                        </select>
                    </div>

                    <!-- Issue Select -->
                    <div>
                        <label class="block text-sm font-semibold text-gray-300 mb-2">সমস্যা / কাজের ধরণ</label>
                        <select id="estIssue" class="w-full bg-slate-900 border border-gray-700 text-white rounded-xl px-4 py-3 focus:outline-none focus:border-brand-cyan">
                            <option value="display">ডিসপ্লে / টাচ পরিবর্তন (Display)</option>
                            <option value="frp">FRP / গুগল লক / পিন আনলক (FRP)</option>
                            <option value="battery">নতুন অরিজিনাল ব্যাটারি (Battery)</option>
                            <option value="board">মাদারবোর্ড / CPU রিবেলিং (Motherboard)</option>
                            <option value="flash">সফটওয়্যার ফ্ল্যাশ / লোগো হ্যাং (Flashing)</option>
                        </select>
                    </div>
                </div>

                <!-- Calculate Action Button -->
                <div class="mt-8 text-center">
                    <button onclick="calculateEstimate()" class="w-full sm:w-auto px-8 py-3.5 rounded-xl gradient-btn text-black font-bold text-base shadow-lg">
                        <i class="fa-solid fa-calculator mr-2"></i> খরচ ও সময় হিসাব করুন
                    </button>
                </div>

                <!-- Dynamic Estimate Result Display Box -->
                <div id="estimateResult" class="hidden mt-8 p-6 rounded-2xl bg-slate-900/90 border border-brand-cyan/40 text-center animate-fade-in">
                    <p class="text-xs text-gray-400 uppercase tracking-wide">আনুমানিক সার্ভিসিং খরচ ও সময়</p>
                    <p id="estPriceRange" class="text-3xl font-black text-brand-cyan my-2">৳ ৫০০ - ৳ ১,২০০</p>
                    <div id="estTimeDisplay" class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-brand-purple/20 border border-brand-purple/40 text-purple-300 text-xs font-semibold mb-3">
                        <i class="fa-solid fa-clock"></i> <span id="estTimeText">সময়: ৩০-৪৫ মিনিট</span>
                    </div>
                    <p class="text-xs text-gray-300">
                        *পার্টসের ব্র্যান্ড বা মডেলে সামান্য পরিবর্তন হতে পারে। সরাসরি আমাদের দোকানে এলে নিখুঁত চেকআপ দেওয়া হবে।
                    </p>
                    <div class="mt-4">
                        <a id="estWhatsappLink" href="#" target="_blank" class="inline-flex items-center justify-center gap-2 px-5 py-2.5 rounded-xl bg-emerald-500 hover:bg-emerald-600 text-black font-bold text-sm transition-colors">
                            <i class="fa-brands fa-whatsapp text-lg"></i> এই সেবার জন্য হোয়াটসঅ্যাপে মেসেজ দিন
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- 7. Why Choose Us / Features -->
    <section id="features" class="py-20 bg-slate-950/50 border-t border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">
                    কেন বেছে নেবেন <span class="text-gradient">ওবায়দুল্লাহ টেলিকম?</span>
                </h2>
                <p class="text-gray-400 mt-2">আমরা প্রতিটি গ্রাহককে সেরা অভিজ্ঞতা দিতে প্রতিশ্রুতিবদ্ধ</p>
            </div>

            <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Card 1 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 text-center hover:border-brand-cyan transition-all">
                    <div class="w-12 h-12 rounded-xl bg-brand-cyan/20 text-brand-cyan flex items-center justify-center text-2xl mx-auto mb-4">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">১০০% গ্যারান্টি</h3>
                    <p class="text-xs text-gray-400">প্রতিটি সেকেন্ড হ্যান্ড ফোনে পাবেন ক্যাশ মেমো ও টেস্ট ওয়ারেন্টি সুবিধা।</p>
                </div>

                <!-- Card 2 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 text-center hover:border-brand-cyan transition-all">
                    <div class="w-12 h-12 rounded-xl bg-purple-500/20 text-purple-400 flex items-center justify-center text-2xl mx-auto mb-4">
                        <i class="fa-solid fa-user-gear"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">অভিজ্ঞ টেকনিশিয়ান</h3>
                    <p class="text-xs text-gray-400">অত্যাধুনিক মেশিন দিয়ে নিখুঁত মোবাইল সার্ভিসিংয়ের দীর্ঘ অভিজ্ঞতা।</p>
                </div>

                <!-- Card 3 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 text-center hover:border-brand-cyan transition-all">
                    <div class="w-12 h-12 rounded-xl bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-2xl mx-auto mb-4">
                        <i class="fa-solid fa-bolt"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">দ্রুত ডেলিভারি</h3>
                    <p class="text-xs text-gray-400">অধিকাংশ ডিসপ্লে ও লক আনলকের কাজ সামনে বসিয়ে দ্রুত শেষ করা হয়।</p>
                </div>

                <!-- Card 4 -->
                <div class="glass-card p-6 rounded-2xl border border-gray-800 text-center hover:border-brand-cyan transition-all">
                    <div class="w-12 h-12 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-2xl mx-auto mb-4">
                        <i class="fa-solid fa-hand-holding-dollar"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">সাশ্রয়ী মূল্য</h3>
                    <p class="text-xs text-gray-400">বাজারের সেরা ও একদম ন্যায্য মূল্যে ফোন ক্রয় এবং সার্ভিসিং সার্ভিস।</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 8. Contact & Shop Location Section -->
    <section id="contact" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-start">
                
                <!-- Left: Shop Address Details -->
                <div class="space-y-8">
                    <div>
                        <span class="text-brand-cyan font-semibold text-sm">যোগাযোগ করুন</span>
                        <h2 class="text-3xl sm:text-4xl font-black text-white mt-1">আমাদের দোকানে আমন্ত্রণ রইলো</h2>
                        <p class="text-gray-400 mt-3 text-sm sm:text-base leading-relaxed">
                            যেকোনো প্রয়োজনে সরাসরি আমাদের শপে চলে আসুন অথবা কল দিয়ে বুকিং দিন।
                        </p>
                    </div>

                    <div class="space-y-4">
                        <!-- Location -->
                        <div class="glass-card p-4 rounded-xl flex items-start gap-4 border border-gray-800">
                            <div class="w-10 h-10 rounded-lg bg-brand-cyan/20 text-brand-cyan flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="text-white font-bold text-base">দোকানের ঠিকানা</h4>
                                <p class="text-gray-300 text-sm">আব্দুল লতিফ প্লাজা, দোকান নং ৪ (২য় তলা), পুরান থানা রোড, কিশোরগঞ্জ সদর, কিশোরগঞ্জ।</p>
                            </div>
                        </div>

                        <!-- Phone -->
                        <div class="glass-card p-4 rounded-xl flex items-start gap-4 border border-gray-800">
                            <div class="w-10 h-10 rounded-lg bg-purple-500/20 text-purple-400 flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="text-white font-bold text-base">হটলাইন নম্বর</h4>
                                <p class="text-gray-300 text-sm">+880 1700-000000, +880 1900-000000</p>
                            </div>
                        </div>

                        <!-- Hours -->
                        <div class="glass-card p-4 rounded-xl flex items-start gap-4 border border-gray-800">
                            <div class="w-10 h-10 rounded-lg bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="text-white font-bold text-base">খোলা থাকার সময়</h4>
                                <p class="text-gray-300 text-sm">প্রতিদিন সকাল ৯:০০ টা থেকে রাত ১০:০০ টা পর্যন্ত (শুক্রবার খোলা)</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right: Quick Message Form -->
                <div class="glass-card rounded-3xl p-6 sm:p-8 border border-gray-800">
                    <h3 class="text-2xl font-bold text-white mb-2">মেসেজ বা বুকিং পাঠান</h3>
                    <p class="text-gray-400 text-xs mb-6">আপনার প্রয়োজন বা জিজ্ঞাসা লিখে আমাদের কাছে পাঠান</p>

                    <form id="contactForm" onsubmit="handleFormSubmit(event)" class="space-y-4">
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-1">আপনার নাম</label>
                            <input type="text" required placeholder="উদাহরণ: মো: আরিফুল ইসলাম" class="w-full bg-slate-900 border border-gray-700 text-white rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-brand-cyan">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-1">মোবাইল নম্বর</label>
                            <input type="tel" required placeholder="017XXXXXXXX" class="w-full bg-slate-900 border border-gray-700 text-white rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-brand-cyan">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-1">সেবার ধরণ</label>
                            <select class="w-full bg-slate-900 border border-gray-700 text-white rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-brand-cyan">
                                <option>সেকেন্ড হ্যান্ড ফোন কিনতে চাই</option>
                                <option>ফোন মেরামত / সার্ভিসিং করব</option>
                                <option>ফোন আনলক করতে চাই (FRP/Country Lock)</option>
                                <option>অন্যান্য তথ্য</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-gray-300 mb-1">বিস্তারিত বিবরণ</label>
                            <textarea rows="3" placeholder="আপনার ফোনের মডেল ও সমস্যার কথা লিখুন..." class="w-full bg-slate-900 border border-gray-700 text-white rounded-xl px-4 py-3 text-sm focus:outline-none focus:border-brand-cyan"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3.5 rounded-xl gradient-btn text-black font-bold text-base shadow-lg">
                            মেসেজ পাঠান
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-gray-800 bg-slate-950 py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center justify-between gap-6 text-center md:text-left">
                <div>
                    <span class="text-xl font-extrabold text-white">ওবায়দুল্লাহ <span class="text-gradient">টেলিকম</span></span>
                    <p class="text-xs text-gray-400 mt-1">বিশ্বস্ত সেকেন্ড হ্যান্ড মোবাইল ও প্রফেশনাল সার্ভিসিং সেন্টার।</p>
                </div>
                
                <!-- Social Links -->
                <div class="flex items-center gap-4">
                    <a href="#" class="w-9 h-9 rounded-full bg-gray-800 hover:bg-brand-cyan hover:text-black text-gray-300 flex items-center justify-center transition-colors">
                        <i class="fa-brands fa-facebook-f"></i>
                    </a>
                    <a href="#" class="w-9 h-9 rounded-full bg-gray-800 hover:bg-emerald-500 hover:text-black text-gray-300 flex items-center justify-center transition-colors">
                        <i class="fa-brands fa-whatsapp"></i>
                    </a>
                    <a href="#" class="w-9 h-9 rounded-full bg-gray-800 hover:bg-red-500 hover:text-white text-gray-300 flex items-center justify-center transition-colors">
                        <i class="fa-brands fa-youtube"></i>
                    </a>
                </div>
            </div>

            <div class="mt-8 pt-6 border-t border-gray-800/60 text-center text-xs text-gray-400">
                &copy; ২০২৬ শান টেলিকম। সর্বস্বত্ব সংরক্ষিত। 
            </div>
        </div>
    </footer>

    <!-- Interactive Phone Booking Modal -->
    <div id="bookingModal" class="fixed inset-0 bg-black/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="glass-card max-w-md w-full rounded-2xl p-6 border border-brand-cyan/40 relative animate-fade-in">
            <button onclick="closeBookingModal()" class="absolute top-4 right-4 text-gray-400 hover:text-white text-xl">
                <i class="fa-solid fa-xmark"></i>
            </button>
            
            <h3 class="text-xl font-bold text-white mb-1">ফোন অর্ডার / বুকিং</h3>
            <p id="modalPhoneTitle" class="text-sm text-brand-cyan font-semibold">iPhone 13 Pro</p>
            <p id="modalPhonePrice" class="text-xs text-gray-300 mb-4">মূল্য: ৳ ৬৮,৫০০</p>

            <form onsubmit="handleModalSubmit(event)" class="space-y-3">
                <div>
                    <label class="block text-xs text-gray-300 mb-1">আপনার নাম</label>
                    <input type="text" required placeholder="আপনার নাম লিখুন" class="w-full bg-slate-900 border border-gray-700 text-white rounded-lg px-3 py-2 text-sm focus:outline-none focus:border-brand-cyan">
                </div>
                <div>
                    <label class="block text-xs text-gray-300 mb-1">মোবাইল নম্বর</label>
                    <input type="tel" required placeholder="017XXXXXXXX" class="w-full bg-slate-900 border border-gray-700 text-white rounded-lg px-3 py-2 text-sm focus:outline-none focus:border-brand-cyan">
                </div>
                <div>
                    <label class="block text-xs text-gray-300 mb-1">ডেলিভারি / শপ পিকআপ</label>
                    <select class="w-full bg-slate-900 border border-gray-700 text-white rounded-lg px-3 py-2 text-sm focus:outline-none focus:border-brand-cyan">
                        <option>দোকানে এসে নেব (Shop Pickup)</option>
                        <option>হোম ডেলিভারি (কুরিয়ার মাধ্যমে)</option>
                    </select>
                </div>
                <button type="submit" class="w-full py-3 rounded-xl gradient-btn text-black font-bold text-sm mt-2">
                    কনফার্ম অর্ডার করুন
                </button>
            </form>
        </div>
    </div>

    <!-- Notification Toast Box -->
    <div id="toast" class="fixed bottom-6 right-6 z-50 hidden bg-emerald-500 text-black font-bold px-5 py-3 rounded-xl shadow-2xl flex items-center gap-2">
        <i class="fa-solid fa-circle-check"></i>
        <span id="toastMsg">আপনার মেসেজ সফলভাবে জমা হয়েছে!</span>
    </div>

    <!-- JavaScript Logic -->
    <script>
        // 1. Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // 2. Phone Category Filter Tabs
        function filterPhones(category) {
            const cards = document.querySelectorAll('.phone-card');
            const buttons = document.querySelectorAll('.filter-btn');

            buttons.forEach(btn => {
                btn.classList.remove('bg-brand-cyan', 'text-black', 'shadow-lg');
                btn.classList.add('glass-card', 'text-gray-300');
            });

            event.currentTarget.classList.remove('glass-card', 'text-gray-300');
            event.currentTarget.classList.add('bg-brand-cyan', 'text-black', 'shadow-lg');

            cards.forEach(card => {
                if (category === 'all' || card.dataset.category === category) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
        }

        // 3. Price Estimator Tool Logic
        function calculateEstimate() {
            const brand = document.getElementById('estBrand').value;
            const issue = document.getElementById('estIssue').value;
            const resultBox = document.getElementById('estimateResult');
            const priceText = document.getElementById('estPriceRange');
            const timeText = document.getElementById('estTimeText');
            const waLink = document.getElementById('estWhatsappLink');

            let min = 500;
            let max = 1500;
            let time = "৩০-৪৫ মিনিট";

            if (issue === 'display') {
                if (brand === 'iphone') { min = 3500; max = 18000; time = "১ - ২ ঘণ্টা"; }
                else if (brand === 'samsung') { min = 2200; max = 12000; time = "৪৫ - ৬০ মিনিট"; }
                else { min = 1500; max = 4500; time = "৩০ - ৪৫ মিনিট"; }
            } else if (issue === 'frp') {
                if (brand === 'iphone') { min = 2000; max = 8000; time = "২ - ২৪ ঘণ্টা"; }
                else { min = 500; max = 1800; time = "২০ - ৩০ মিনিট"; }
            } else if (issue === 'battery') {
                if (brand === 'iphone') { min = 1800; max = 4500; time = "৩০ - ৪৫ মিনিট"; }
                else { min = 800; max = 2200; time = "২০ - ৩০ মিনিট"; }
            } else if (issue === 'board') {
                min = 1500; max = 6000; time = "১ - ৩ দিন (চেকআপ সাপেক্ষে)";
            } else if (issue === 'flash') {
                min = 400; max = 1200; time = "২০ - ৪০ মিনিট";
            }

            priceText.innerText = `৳ ${min.toLocaleString('bn-BD')} - ৳ ${max.toLocaleString('bn-BD')}`;
            timeText.innerText = `আনুমানিক সময়: ${time}`;
            waLink.href = `https://wa.me/8801700000000?text=আসসালামু%20আলাইকুম%20ওবায়দুল্লাহ%20টেলিকম,%20আমার%20${brand}%20ফোনের%20${issue}%20সমস্যার%20সার্ভিসিং%20বুকিং%20করতে%20চাই।`;
            
            resultBox.classList.remove('hidden');
        }

        // 4. Modal Logic
        const modal = document.getElementById('bookingModal');
        function openBookingModal(phoneName, price) {
            document.getElementById('modalPhoneTitle').innerText = phoneName;
            document.getElementById('modalPhonePrice').innerText = 'মূল্য: ' + price;
            modal.classList.remove('hidden');
        }
        function closeBookingModal() {
            modal.classList.add('hidden');
        }

        // 5. Toast Notification System
        function showToast(message) {
            const toast = document.getElementById('toast');
            document.getElementById('toastMsg').innerText = message;
            toast.classList.remove('hidden');
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 4000);
        }

        function handleFormSubmit(e) {
            e.preventDefault();
            showToast('আপনার অনুরোধ জমা হয়েছে! আমরা খুব শীঘ্রই যোগাযোগ করব।');
            e.target.reset();
        }

        function handleModalSubmit(e) {
            e.preventDefault();
            closeBookingModal();
            showToast('বুকিং সম্পন্ন হয়েছে! আমাদের টিম আপনার সাথে যোগাযোগ করবে।');
            e.target.reset();
        }
    </script>
</body>
</html>
