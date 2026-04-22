<html lang="en" class="scroll-smooth"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>xabbir | YouTube Monetization &amp; AdSense Expert</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://code.iconify.design/iconify-icon/1.0.7/iconify-icon.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
        }

        /* Custom subtle animations */
        @keyframes fade-in-up {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animate-fade-in-up {
            animation: fade-in-up 0.8s cubic-bezier(0.16, 1, 0.3, 1) forwards;
            opacity: 0;
        }

        .delay-100 { animation-delay: 100ms; }
        .delay-200 { animation-delay: 200ms; }
        .delay-300 { animation-delay: 300ms; }

        /* Hide default details marker */
        details > summary {
            list-style: none;
        }
        details > summary::-webkit-details-marker {
            display: none;
        }
        details[open] summary ~ * {
            animation: fade-in-up 0.3s ease-out;
        }
    </style>
</head>
<body class="bg-slate-950 text-slate-300 antialiased selection:bg-purple-500/30 selection:text-purple-200 relative overflow-x-hidden">

    <!-- Background Ambient Glow -->
    <div class="fixed top-0 left-1/2 -translate-x-1/2 w-[80vw] h-[50vh] bg-gradient-to-b from-blue-900/20 to-purple-900/20 blur-[100px] rounded-full pointer-events-none -z-10"></div>

    <!-- Header -->
    <header class="fixed top-0 inset-x-0 z-50 border-b border-white/5 bg-slate-950/60 backdrop-blur-md">
        <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
            <a href="#" class="text-xl font-medium tracking-tighter text-white">xabbir</a>
            <nav class="hidden md:flex items-center gap-8 text-sm font-normal">
                <a href="#services" class="hover:text-white transition-colors">Services</a>
                <a href="#case-studies" class="hover:text-white transition-colors">Results</a>
                <a href="#testimonials" class="hover:text-white transition-colors">Testimonials</a>
                <a href="#faq" class="hover:text-white transition-colors">FAQ</a>
            </nav>
            <a href="#contact" class="hidden md:inline-flex items-center justify-center gap-2 px-4 py-2 text-sm font-medium text-white bg-white/5 border border-white/10 rounded-full hover:bg-white/10 transition-colors">
                Contact Me
            </a>
            <!-- Mobile Menu Icon (Visual Only) -->
            <button class="md:hidden text-white">
                <iconify-icon icon="solar:hamburger-menu-linear" stroke-width="1.5" width="24"></iconify-icon>
            </button>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 md:pt-48 md:pb-32 px-6 max-w-6xl mx-auto text-center flex flex-col items-center">
            <div class="inline-flex items-center gap-2 px-3 py-1 mb-8 rounded-full border border-purple-500/30 bg-purple-500/10 text-purple-300 text-xs font-medium animate-fade-in-up">
                <span class="w-2 h-2 rounded-full bg-purple-500 animate-pulse"></span>
                Accepting new clients
            </div>
            
            <h1 class="text-4xl md:text-6xl lg:text-7xl font-semibold tracking-tight text-white mb-6 max-w-4xl animate-fade-in-up delay-100 leading-tight">
                Unlock your YouTube channel's <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-400">full earning potential.</span>
            </h1>
            
            <p class="text-base md:text-lg text-slate-400 max-w-2xl mb-10 animate-fade-in-up delay-200">
                Expert solutions for YouTube Monetization, AdSense Step 2 errors, and Reused Content strikes. Get monetized faster and start generating revenue safely.
            </p>
            
            <div class="flex flex-col sm:flex-row items-center gap-4 animate-fade-in-up delay-300 w-full sm:w-auto">
                <a href="https://wa.me/+916000029609" target="_blank" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 px-6 py-3 text-sm font-medium text-white bg-gradient-to-r from-blue-600 to-purple-600 rounded-full hover:shadow-lg hover:shadow-purple-500/25 transition-all hover:-translate-y-0.5">
                    <iconify-icon icon="solar:phone-calling-linear" stroke-width="1.5" width="20"></iconify-icon>
                    Chat on WhatsApp
                </a>
                <a href="mailto:contact@xabbir.com" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 px-6 py-3 text-sm font-medium text-white bg-white/5 border border-white/10 rounded-full hover:bg-white/10 transition-colors">
                    <iconify-icon icon="solar:letter-linear" stroke-width="1.5" width="20"></iconify-icon>
                    Email Me
                </a>
            </div>
        </section>

        <!-- Logos / Trust (Optional) -->
        <section class="border-y border-white/5 bg-white/[0.02]">
            <div class="max-w-6xl mx-auto px-6 py-8 flex flex-col md:flex-row items-center justify-center gap-8 md:gap-16 opacity-50 grayscale hover:grayscale-0 transition-all duration-500">
                <div class="flex items-center gap-2 font-medium tracking-tight text-lg text-white">
                    <iconify-icon icon="solar:play-circle-linear" stroke-width="1.5" width="24"></iconify-icon> YouTube Partners
                </div>
                <div class="flex items-center gap-2 font-medium tracking-tight text-lg text-white">
                    <iconify-icon icon="solar:shield-check-linear" stroke-width="1.5" width="24"></iconify-icon> 100% Secure
                </div>
                <div class="flex items-center gap-2 font-medium tracking-tight text-lg text-white">
                    <iconify-icon icon="solar:medal-star-linear" stroke-width="1.5" width="24"></iconify-icon> Top Rated Expert
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-24 px-6 max-w-6xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
                <div class="order-2 lg:order-1 relative">
                    <div class="aspect-square rounded-2xl border border-white/10 bg-gradient-to-br from-slate-800 to-slate-900 flex items-center justify-center relative overflow-hidden">
                        <!-- Abstract representation of the expert -->
                        <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGNpcmNsZSBjeD0iMiIgY3k9IjIiIHI9IjIiIGZpbGw9InJnYmEoMjU1LDI1NSwyNTUsMC4wNSkiLz48L3N2Zz4=')] [mask-image:radial-gradient(ellipse_at_center,black_50%,transparent_100%)]"></div>
                        <iconify-icon icon="solar:user-circle-linear" class="text-white/20" stroke-width="1" width="120"></iconify-icon>
                    </div>
                    <!-- Stat badge -->
                    <div class="absolute -bottom-6 -right-6 bg-slate-900 border border-white/10 p-4 rounded-xl shadow-xl flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-blue-500/20 text-blue-400 flex items-center justify-center">
                            <iconify-icon icon="solar:graph-up-linear" stroke-width="1.5" width="24"></iconify-icon>
                        </div>
                        <div>
                            <div class="text-xl font-semibold text-white tracking-tight">500+</div>
                            <div class="text-xs text-slate-400">Channels Monetized</div>
                        </div>
                    </div>
                </div>
                
                <div class="order-1 lg:order-2">
                    <h2 class="text-3xl md:text-4xl font-semibold tracking-tight text-white mb-6">Behind the strategy.</h2>
                    <p class="text-slate-400 mb-6 leading-relaxed">
                        I'm xabbir, a specialized YouTube strategist focusing strictly on the technical and policy aspects of channel growth. Dealing with YouTube support can be a nightmare of automated responses. I bridge that gap.
                    </p>
                    <p class="text-slate-400 mb-8 leading-relaxed">
                        With years of navigating YouTube's complex monetization policies, AdSense intricacies, and copyright laws, I provide precise, actionable solutions to get your channel out of limbo and back to earning revenue. No guesswork, just proven methods.
                    </p>
                    
                    <ul class="space-y-4">
                        <li class="flex items-start gap-3 text-sm text-slate-300">
                            <iconify-icon icon="solar:check-circle-linear" class="text-purple-400 shrink-0 mt-0.5" stroke-width="1.5" width="18"></iconify-icon>
                            <span>Direct communication via WhatsApp for fast updates.</span>
                        </li>
                        <li class="flex items-start gap-3 text-sm text-slate-300">
                            <iconify-icon icon="solar:check-circle-linear" class="text-purple-400 shrink-0 mt-0.5" stroke-width="1.5" width="18"></iconify-icon>
                            <span>100% compliance with YouTube TOS (White-hat only).</span>
                        </li>
                        <li class="flex items-start gap-3 text-sm text-slate-300">
                            <iconify-icon icon="solar:check-circle-linear" class="text-purple-400 shrink-0 mt-0.5" stroke-width="1.5" width="18"></iconify-icon>
                            <span>Confidential and secure handling of your channel data.</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-24 px-6 max-w-6xl mx-auto relative">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-semibold tracking-tight text-white mb-4">Specialized Services</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Targeted solutions to overcome YouTube's most frustrating hurdles.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Service 1 -->
                <div class="bg-white/[0.02] border border-white/5 rounded-2xl p-6 hover:bg-white/[0.04] hover:border-white/10 transition-all group">
                    <div class="w-12 h-12 rounded-lg bg-blue-500/10 text-blue-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <iconify-icon icon="solar:dollar-minimalistic-linear" stroke-width="1.5" width="24"></iconify-icon>
                    </div>
                    <h3 class="text-lg font-medium text-white mb-2 tracking-tight">Monetization Approval</h3>
                    <p class="text-sm text-slate-400">Complete channel audit and restructuring to ensure swift approval when you hit the 1k/4k threshold.</p>
                </div>

                <!-- Service 2 -->
                <div class="bg-white/[0.02] border border-white/5 rounded-2xl p-6 hover:bg-white/[0.04] hover:border-white/10 transition-all group">
                    <div class="w-12 h-12 rounded-lg bg-purple-500/10 text-purple-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <iconify-icon icon="solar:refresh-circle-linear" stroke-width="1.5" width="24"></iconify-icon>
                    </div>
                    <h3 class="text-lg font-medium text-white mb-2 tracking-tight">Reused Content Fix</h3>
                    <p class="text-sm text-slate-400">Demonetized? I identify problematic videos, guide the editing process, and craft the perfect appeal video.</p>
                </div>

                <!-- Service 3 -->
                <div class="bg-white/[0.02] border border-white/5 rounded-2xl p-6 hover:bg-white/[0.04] hover:border-white/10 transition-all group">
                    <div class="w-12 h-12 rounded-lg bg-emerald-500/10 text-emerald-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <iconify-icon icon="solar:danger-triangle-linear" stroke-width="1.5" width="24"></iconify-icon>
                    </div>
                    <h3 class="text-lg font-medium text-white mb-2 tracking-tight">AdSense Step 2 Errors</h3>
                    <p class="text-sm text-slate-400">Resolving duplicate accounts, identity verification failures, and linking issues to get your payments flowing.</p>
                </div>

                <!-- Service 4 -->
                <div class="bg-white/[0.02] border border-white/5 rounded-2xl p-6 hover:bg-white/[0.04] hover:border-white/10 transition-all group">
                    <div class="w-12 h-12 rounded-lg bg-rose-500/10 text-rose-400 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
                        <iconify-icon icon="solar:shield-warning-linear" stroke-width="1.5" width="24"></iconify-icon>
                    </div>
                    <h3 class="text-lg font-medium text-white mb-2 tracking-tight">Copyright Strikes</h3>
                    <p class="text-sm text-slate-400">Assistance with counter-notifications and managing false claims to protect your channel's standing.</p>
                </div>
            </div>
        </section>

        <!-- Case Studies -->
        <section id="case-studies" class="py-24 border-y border-white/5 bg-slate-900/30">
            <div class="max-w-6xl mx-auto px-6">
                <div class="flex flex-col md:flex-row justify-between items-end mb-12 gap-6">
                    <div>
                        <h2 class="text-3xl md:text-4xl font-semibold tracking-tight text-white mb-4">Proven Results</h2>
                        <p class="text-slate-400 max-w-xl">Real channels, real issues, resolved efficiently.</p>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Case 1 -->
                    <div class="p-6 rounded-2xl border border-white/5 bg-slate-950 flex flex-col justify-between">
                        <div class="mb-6">
                            <div class="flex items-center gap-2 text-xs font-medium text-purple-400 mb-4 uppercase tracking-wider">
                                Gaming Channel • 250k Subs
                            </div>
                            <h3 class="text-xl font-medium text-white mb-2 tracking-tight">Reused Content Demonetization</h3>
                            <p class="text-sm text-slate-400">Channel lost monetization due to repetitive gameplay footage without commentary.</p>
                        </div>
                        
                        <div class="grid grid-cols-2 gap-4 border-t border-white/5 pt-6">
                            <div>
                                <div class="text-xs text-slate-500 mb-1">Before</div>
                                <div class="text-rose-400 text-sm font-medium flex items-center gap-1">
                                    <iconify-icon icon="solar:close-circle-linear"></iconify-icon> Demonetized
                                </div>
                            </div>
                            <div>
                                <div class="text-xs text-slate-500 mb-1">After (14 Days)</div>
                                <div class="text-emerald-400 text-sm font-medium flex items-center gap-1">
                                    <iconify-icon icon="solar:check-circle-linear"></iconify-icon> Remonetized
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Case 2 -->
                    <div class="p-6 rounded-2xl border border-white/5 bg-slate-950 flex flex-col justify-between">
                        <div class="mb-6">
                            <div class="flex items-center gap-2 text-xs font-medium text-blue-400 mb-4 uppercase tracking-wider">
                                Vlogger • 50k Subs
                            </div>
                            <h3 class="text-xl font-medium text-white mb-2 tracking-tight">AdSense Step 2 Error</h3>
                            <p class="text-sm text-slate-400">Stuck for 3 months due to an old, forgotten AdSense account causing a duplicate error.</p>
                        </div>
                        
                        <div class="grid grid-cols-2 gap-4 border-t border-white/5 pt-6">
                            <div>
                                <div class="text-xs text-slate-500 mb-1">Before</div>
                                <div class="text-rose-400 text-sm font-medium flex items-center gap-1">
                                    <iconify-icon icon="solar:close-circle-linear"></iconify-icon> Step 2 Failed
                                </div>
                            </div>
                            <div>
                                <div class="text-xs text-slate-500 mb-1">After (48 Hours)</div>
                                <div class="text-emerald-400 text-sm font-medium flex items-center gap-1">
                                    <iconify-icon icon="solar:check-circle-linear"></iconify-icon> Linked &amp; Active
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials -->
        <section id="testimonials" class="py-24 px-6 max-w-6xl mx-auto">
             <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-semibold tracking-tight text-white mb-4">Client Success</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Don't just take my word for it.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Testimonial 1 -->
                <div class="p-6 rounded-2xl bg-white/[0.02] border border-white/5">
                    <iconify-icon icon="solar:quote-left-linear" class="text-white/10 mb-4" width="32"></iconify-icon>
                    <p class="text-sm text-slate-300 mb-6 leading-relaxed">"I was stuck with a reused content strike for months and YouTube support was useless. xabbir audited my channel, told me exactly what to delete, and helped me script the appeal. Monetized within a week."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-8 h-8 rounded-full bg-gradient-to-br from-blue-500 to-purple-500 flex items-center justify-center text-xs font-medium text-white">M</div>
                        <div>
                            <div class="text-sm font-medium text-white">Tech Reviewer</div>
                            <div class="text-xs text-slate-500">120k Subscribers</div>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="p-6 rounded-2xl bg-white/[0.02] border border-white/5">
                    <iconify-icon icon="solar:quote-left-linear" class="text-white/10 mb-4" width="32"></iconify-icon>
                    <p class="text-sm text-slate-300 mb-6 leading-relaxed">"T
