<template>
  <footer class="bg-white border-t border-gray-100 pt-16 pb-8">
    <div class="max-w-7xl mx-auto px-6">
      
      <div class="grid grid-cols-1 md:grid-cols-12 gap-10 pb-12 border-b border-gray-100">
        
        <div class="md:col-span-4 space-y-4">
          <NuxtLink to="/" class="flex items-center gap-2 font-bold text-lg tracking-tight text-slate-900">
            <span>Tepuy Innovations</span>
          </NuxtLink>
          <p class="text-xs text-gray-500 leading-relaxed max-w-sm">
            Elevamos tu negocio con tecnologia.
          </p>
        </div>

        <div class="md:col-span-3 space-y-4">
          <h4 class="text-xs font-bold uppercase tracking-widest text-slate-900">Navegación</h4>
          <ul class="space-y-2.5 text-xs">
            <li>
              <NuxtLink to="/" class="text-gray-500 hover:text-[#0FA36B] transition-colors">Inicio</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/services" class="text-gray-500 hover:text-[#0FA36B] transition-colors">Servicios</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/contacts" class="text-gray-500 hover:text-[#0FA36B] transition-colors">Contactos</NuxtLink>
            </li>
          </ul>
        </div>

        <div class="md:col-span-3 space-y-4">
          <h4 class="text-xs font-bold uppercase tracking-widest text-slate-900">Soluciones</h4>
          <ul class="space-y-2.5 text-xs text-gray-500">
            <li class="hover:text-slate-900 transition-colors cursor-default">Desarrollo de SaaS</li>
            <li class="hover:text-slate-900 transition-colors cursor-default">Landing Pages</li>
            <li class="hover:text-slate-900 transition-colors cursor-default">Desarrollo Mobile</li>
            <li class="hover:text-slate-900 transition-colors cursor-default">CI/CD</li>
          </ul>
        </div>

      </div>

      <div class="pt-8 flex flex-col sm:flex-row justify-between items-center gap-4 text-[11px] text-gray-400 font-medium">
        
        <div>
          <p>2026 Tepuy Innovations.</p>
        </div>

      </div>

    </div>
  </footer>
</template>