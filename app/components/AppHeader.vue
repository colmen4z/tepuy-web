<script setup lang="ts">
import { ref } from 'vue'

const navLinks = [
  { to: '/', label: 'Inicio' },
  { to: '/services', label: 'Servicios' },
  { to: '/contacts', label: 'Contactos' }
]
</script>

<template>
  <header class="bg-white/80 backdrop-blur-md sticky top-0 z-50 border-b border-gray-100 flex flex-col">
    
    <div class="max-w-7xl w-full mx-auto px-6 h-20 flex items-center justify-between">
      
      <NuxtLink to="/" class="flex items-center gap-2 font-bold text-xl tracking-tight">
        <img src="~/assets/img/logo1.png" width="175" alt="Tepuy Innovations Logo">
      </NuxtLink>

      <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-gray-500">
        <NuxtLink 
          v-for="link in navLinks" 
          :key="link.to"
          :to="link.to" 
          class="hover:text-slate-900 transition-colors pb-1 px-1 border-b-2 border-transparent"
          active-class="text-slate-900 !border-[#0FA36B]"
        >
          {{ link.label }}
        </NuxtLink>
      </nav>

      <div>
        <NuxtLink to="/contacts" class="bg-slate-900 hover:bg-slate-800 text-white text-xs font-bold px-4 py-2.5 md:px-5 md:py-3 rounded-md tracking-wide transition-all shadow-sm cursor-pointer whitespace-nowrap">
          Empieza aqui
        </NuxtLink>
      </div>

    </div>

    <nav class="md:hidden flex items-center justify-around w-full border-t border-gray-50 h-12 bg-white/50 px-4">
      <NuxtLink 
        v-for="link in navLinks" 
        :key="link.to"
        :to="link.to" 
        class="text-xs font-bold tracking-wide text-gray-500 pb-1 px-2 border-b-2 border-transparent transition-all"
        active-class="text-slate-900 !border-[#0FA36B]"
      >
        {{ link.label }}
      </NuxtLink>
    </nav>

  </header>
</template>