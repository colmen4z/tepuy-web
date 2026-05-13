<template>
    <header class="bg-white/80 backdrop-blur-md sticky top-0 z-50 border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <NuxtLink to="/" class="flex items-center gap-2 font-bold text-xl tracking-tight">
                <span>Tepuy Innovations</span>
            </NuxtLink>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-gray-500">
            <NuxtLink 
                to="/" 
                class="hover:text-slate-900 transition-colors pb-1 px-1 border-b-2 border-transparent"
                active-class="text-slate-900 !border-[#00D95A]"
            >
                Inicio
            </NuxtLink>

            <NuxtLink 
                to="/services" 
                class="hover:text-slate-900 transition-colors pb-1 px-1 border-b-2 border-transparent"
                active-class="text-slate-900 !border-[#00D95A]"
            >
                Servicios
            </NuxtLink>

            <NuxtLink 
                to="/contacts" 
                class="hover:text-slate-900 transition-colors pb-1 px-1 border-b-2 border-transparent"
                active-class="text-slate-900 !border-[#00D95A]"
            >
                Contactos
            </NuxtLink>

            </nav>
            <div>
                <NuxtLink to="/contacts" class="bg-black hover:bg-slate-800 text-white text-xs font-bold px-5 py-3 rounded-md tracking-wide transition-all shadow-sm cursor-pointer">Empieza aqui</NuxtLink>
            </div>
        </div>
    </header>
</template>