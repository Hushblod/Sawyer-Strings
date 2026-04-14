<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sawyer Strings | Vibrant Skill</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0a0a0a;
            color: #ffffff;
        }

        .neon-border {
            border: 1px solid #39FF14;
            box-shadow: 0 0 10px rgba(57, 255, 20, 0.2);
        }

        .neon-text {
            color: #39FF14;
        }

        .btn-primary {
            background-color: #39FF14;
            color: #000;
            transition: all 0.3s ease;
        }

        .btn-primary:hover {
            background-color: #32d912;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(57, 255, 20, 0.4);
        }

        .gallery-card:hover img {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="antialiased">

    <nav class="fixed w-full z-50 bg-black/80 backdrop-blur-md border-b border-white/10">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-black tracking-tighter uppercase">
                SAWYER<span class="neon-text">STRINGS</span>
            </div>
            <div class="hidden md:flex space-x-8 text-sm font-bold uppercase tracking-widest text-gray-400">
                <a href="#home" class="hover:text-white transition">Home</a>
                <a href="#services" class="hover:text-white transition">Services</a>
                <a href="#pricing" class="hover:text-white transition">Pricing</a>
                <a href="#gallery" class="hover:text-white transition">Gallery</a>
                <a href="#contact" class="hover:text-white transition">Order</a>
            </div>
            <a href="#contact" class="btn-primary px-5 py-2 rounded text-xs font-black uppercase tracking-tighter">Order Now</a>
        </div>
    </nav>

    <section id="home" class="relative h-screen flex items-center justify-center pt-20">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-green-900/10 via-black to-black"></div>
        <div class="relative z-10 text-center px-6">
            <h2 class="text-xs md:text-sm font-bold tracking-[0.3em] uppercase neon-text mb-4">Precision. Feel. Vibrant Skill.</h2>
            <h1 class="text-5xl md:text-8xl font-black uppercase leading-none mb-6">
                Custom Lacrosse <br><span class="text-transparent bg-clip-text bg-gradient-to-r from-white to-gray-500">Stringing</span>
            </h1>
            <p class="max-w-xl mx-auto text-gray-400 text-lg mb-10">
                Game-ready pockets designed for control, consistency, and performance. Built for players who demand more from their gear.
            </p>
            <div class="flex flex-col md:flex-row gap-4 justify-center">
                <a href="#contact" class="btn-primary px-10 py-4 rounded font-black uppercase text-sm">Start Your Build</a>
                <a href="#gallery" class="border border-white/20 hover:bg-white/10 px-10 py-4 rounded font-black uppercase text-sm transition">View Work</a>
            </div>
        </div>
    </section>

    <section id="services" class="py-24 bg-[#0f0f0f]">
        <div class="max-w-7xl mx-auto px-6">
            <div class="mb-16">
                <h3 class="text-3xl font-black uppercase italic">Services</h3>
                <div class="w-20 h-1 bg-[#39FF14] mt-2"></div>
            </div>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="p-8 bg-black border border-white/5 rounded-xl hover:border-[#39FF14]/50 transition">
                    <i data-lucide="crosshair" class="neon-text mb-4"></i>
                    <h4 class="font-bold text-xl mb-2 uppercase">Custom Pocket</h4>
                    <p class="text-gray-500 text-sm">Full custom stringing tailored to your specific position and playstyle.</p>
                </div>
                <div class="p-8 bg-black border border-white/5 rounded-xl hover:border-[#39FF14]/50 transition">
                    <i data-lucide="refresh-cw" class="neon-text mb-4"></i>
                    <h4 class="font-bold text-xl mb-2 uppercase">Mesh Refresh</h4>
                    <p class="text-gray-500 text-sm">Swap out old, bagged-out mesh for fresh performance pieces.</p>
                </div>
                <div class="p-8 bg-black border border-white/5 rounded-xl hover:border-[#39FF14]/50 transition">
                    <i data-lucide="sliders" class="neon-text mb-4"></i>
                    <h4 class="font-bold text-xl mb-2 uppercase">Adjustments</h4>
                    <p class="text-gray-500 text-sm">Fine-tuning of whip, tension, and throw for your current setup.</p>
                </div>
                <div class="p-8 bg-black border border-white/5 rounded-xl hover:border-[#39FF14]/50 transition">
                    <i data-lucide="wrench" class="neon-text mb-4"></i>
                    <h4 class="font-bold text-xl mb-2 uppercase">Repairs</h4>
                    <p class="text-gray-500 text-sm">Sidewall replacements and top-string reinforcements.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="py-24">
        <div class="max-w-4xl mx-auto px-6">
            <div class="text-center mb-16">
                <h3 class="text-3xl font-black uppercase italic">Transparent Pricing</h3>
                <p class="text-gray-500 mt-2">Professional labor. No hidden fees.</p>
            </div>
            <div class="space-y-4">
                <div class="flex justify-between items-center p-6 bg-white/5 rounded-lg border-l-4 border-[#39FF14]">
                    <span class="font-bold uppercase tracking-wider">Basic Stringing</span>
                    <span class="text-xl font-black neon-text">$25 – $35</span>
                </div>
                <div class="flex justify-between items-center p-6 bg-white/5 rounded-lg border-l-4 border-[#39FF14]">
                    <span class="font-bold uppercase tracking-wider">Custom Pocket Build</span>
                    <span class="text-xl font-black neon-text">$40 – $60</span>
                </div>
                <div class="flex justify-between items-center p-6 bg-white/5 rounded-lg border-l-4 border-[#39FF14]">
                    <span class="font-bold uppercase tracking-wider">Mesh + Full Stringing</span>
                    <span class="text-xl font-black neon-text">$60 – $80</span>
                </div>
                <div class="flex justify-between items-center p-6 bg-white/5 rounded-lg border-l-4 border-gray-600">
                    <span class="font-bold uppercase tracking-wider">Quick Fix / Adjust</span>
                    <span class="text-xl font-black text-gray-400">$10 – $20</span>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="py-24 bg-[#0f0f0f]">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h3 class="text-3xl font-black uppercase italic mb-12 text-left">Gallery</h3>
            <div class="grid md:grid-cols-3 gap-4">
                <div class="aspect-square bg-zinc-900 flex items-center justify-center rounded overflow-hidden gallery-card">
                    <p class="text-zinc-700 font-bold uppercase">Work Image 01</p>
                </div>
                <div class="aspect-square bg-zinc-900 flex items-center justify-center rounded overflow-hidden gallery-card">
                    <p class="text-zinc-700 font-bold uppercase">Work Image 02</p>
                </div>
                <div class="aspect-square bg-zinc-900 flex items-center justify-center rounded overflow-hidden gallery-card">
                    <p class="text-zinc-700 font-bold uppercase">Work Image 03</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-24">
        <div class="max-w-3xl mx-auto px-6">
            <div class="bg-white/5 p-10 rounded-2xl border border-white/10">
                <h3 class="text-3xl font-black uppercase italic mb-2">Order Your Pocket</h3>
                <p class="text-gray-400 mb-8">Ready to level up? Fill out the details below.</p>
                <form class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="flex flex-col">
                        <label class="text-xs font-bold uppercase text-gray-500 mb-2">Name</label>
                        <input type="text" class="bg-black border border-white/10 p-3 rounded focus:outline-none focus:border-[#39FF14] text-white">
                    </div>
                    <div class="flex flex-col">
                        <label class="text-xs font-bold uppercase text-gray-500 mb-2">Head Type</label>
                        <input type="text" placeholder="e.g. Maverik Kinetik 3" class="bg-black border border-white/10 p-3 rounded focus:outline-none focus:border-[#39FF14] text-white">
                    </div>
                    <div class="flex flex-col">
                        <label class="text-xs font-bold uppercase text-gray-500 mb-2">Pocket Type</label>
                        <select class="bg-black border border-white/10 p-3 rounded focus:outline-none focus:border-[#39FF14] text-white">
                            <option>Low</option>
                            <option>Mid</option>
                            <option>High</option>
                        </select>
                    </div>
                    <div class="flex flex-col">
                        <label class="text-xs font-bold uppercase text-gray-500 mb-2">Mesh Preference</label>
                        <input type="text" placeholder="e.g. Hero 3.0" class="bg-black border border-white/10 p-3 rounded focus:outline-none focus:border-[#39FF14] text-white">
                    </div>
                    <div class="md:col-span-2 flex flex-col">
                        <label class="text-xs font-bold uppercase text-gray-500 mb-2">Notes</label>
                        <textarea rows="4" class="bg-black border border-white/10 p-3 rounded focus:outline-none focus:border-[#39FF14] text-white"></textarea>
                    </div>
                    <button type="submit" class="md:col-span-2 btn-primary py-4 font-black uppercase tracking-widest mt-4">Submit Order</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="py-12 border-t border-white/10 text-center">
        <div class="text-xl font-black uppercase tracking-tighter mb-4">
            SAWYER<span class="neon-text">STRINGS</span>
        </div>
        <div class="flex justify-center space-x-6 mb-8 text-gray-400">
            <a href="#" class="hover:text-[#39FF14] transition"><i data-lucide="instagram"></i></a>
            <a href="#" class="hover:text-[#39FF14] transition"><i data-lucide="mail"></i></a>
        </div>
        <p class="text-xs text-gray-600 uppercase tracking-widest italic">&copy; 2026 Sawyer Strings. Built on Vibrant Skill.</p>
    </footer>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();
    </script>
</body>
</html>
