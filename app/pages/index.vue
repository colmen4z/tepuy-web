<template>
  <section class="relative min-h-[500px] md:min-h-[600px] flex items-center overflow-hidden bg-white">
    <div class="absolute inset-0 z-0">
      <img 
        src="/img/tepuykukenan.jpg" 
        alt="Desarrollo de Tecnología" 
        class="w-full h-full object-cover object-right lg:object-center opacity-75"
      />
    </div>
    <div class="absolute inset-0 bg-gradient-to-r from-white via-white/90 sm:via-white/80 to-white/10 md:to-transparent z-10"></div>
    <div class="max-w-7xl mx-auto px-6 py-12 md:py-20 w-full relative z-20 grid grid-cols-1 lg:grid-cols-12">
      <div class="lg:col-span-7 space-y-6">
        <h1 class="text-5xl md:text-6xl font-black text-slate-900 tracking-tight leading-[1.1]">
          Elevamos tu negocio con 
          <span class="inline-block bg-slate-900 text-[#0FA36B] px-4 py-1 mt-2 transform -skew-x-2">
            Tecnologia
          </span>
        </h1>
        <p class="text-gray-600 text-sm md:text-base max-w-lg leading-relaxed font-normal">
          Diseñamos arquitecturas SaaS escalables y landing pages de alto rendimiento con la precisión de ingeniería de Tepuy Innovations. Desde la idea conceptual hasta el lanzamiento al mercado.
        </p>
        <div class="flex flex-wrap gap-4 pt-4">
          <NuxtLink to="/contacts" class="cursor-pointer bg-[#0FA36B] hover:bg-[#09754c] text-slate-950 hover:text-white font-bold text-sm px-6 py-3.5 rounded-sm transition-colors shadow-md">
            Empieza tu proyecto
          </NuxtLink>
          <NuxtLink to="/services" class="cursor-pointer bg-white hover:bg-gray-50 text-slate-900 font-bold text-sm px-6 py-3.5 rounded-sm border-2 border-slate-900 transition-colors">
            Ver servicios
          </NuxtLink>
        </div>
      </div>
    </div>
  </section>
  <section class="bg-slate-50 py-16 md:py-24 border-y border-gray-100">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
      <div class="lg:col-span-5 space-y-4">
        <div class="inline-block bg-slate-900 text-[#0FA36B] text-[10px] font-bold tracking-widest uppercase px-3 py-1 rounded">
          Sobre Nosotros
        </div>
        <h2 class="text-3xl md:text-4xl font-black text-slate-900 tracking-tight leading-tight">
          Ingeniería inspirada en la solidez de nuestras raíces.
        </h2>
        <p class="text-gray-600 text-sm md:text-base leading-relaxed">
          En <span class="font-bold text-slate-900">Tepuy Innovations</span> fusionamos la robustez de las grandes estructuras con la agilidad del desarrollo moderno. Nos apasiona transformar ideas complejas en soluciones digitales de alto impacto.
        </p>
      </div>
      <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-3 gap-6 w-full">
        <div class="bg-white p-6 rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-shadow">
          <div class="w-10 h-10 bg-slate-900 rounded-lg flex items-center justify-center text-[#0FA36B] mb-4">
            <Icon name="mingcute:light-line" style="color: #0FA36B; width: 22px; height: 22px;" />
          </div>
          <h3 class="font-bold text-slate-900 text-base mb-2">Innovación</h3>
          <p class="text-gray-500 text-xs leading-relaxed">
            Implementamos tecnologías de vanguardia para asegurar que tu software no solo funcione hoy, sino que lidere mañana.
          </p>
        </div>
        <div class="bg-white p-6 rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-shadow">
          <div class="w-10 h-10 bg-slate-900 rounded-lg flex items-center justify-center text-[#0FA36B] mb-4">
            <Icon name="octicon:graph-16" style="color: #0FA36B; width: 22px; height: 22px;" />
          </div>
          <h3 class="font-bold text-slate-900 text-base mb-2">Escalabilidad</h3>
          <p class="text-gray-500 text-xs leading-relaxed">
            Diseñamos arquitecturas preparadas para soportar el crecimiento de tu negocio sin comprometer el rendimiento.
          </p>
        </div>
        <div class="bg-white p-6 rounded-xl border border-gray-100 shadow-sm hover:shadow-md transition-shadow">
          <div class="w-10 h-10 bg-slate-900 rounded-lg flex items-center justify-center text-[#0FA36B] mb-4">
            <Icon name="lsicon:shield-outline" style="color: #0FA36B; width: 22px; height: 22px;" />
          </div>
          <h3 class="font-bold text-slate-900 text-base mb-2">Precisión</h3>
          <p class="text-gray-500 text-xs leading-relaxed">
            Cuidamos cada detalle del backend y frontend mediante metodologías de ingeniería estrictas y limpias.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="py-16 md:py-24 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <div class="text-center max-w-2xl mx-auto mb-16 space-y-3">
        <div class="inline-block bg-slate-900 text-[#0FA36B] text-[10px] font-bold tracking-widest uppercase px-3 py-1 rounded">
          Metodología
        </div>
        <h2 class="text-3xl md:text-4xl font-black text-slate-900 tracking-tight">Nuestro Camino al Éxito</h2>
        <p class="text-gray-500 text-sm">Llevamos tu idea desde el concepto hasta producción siguiendo estándares estrictos de calidad.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 relative">
        <div class="space-y-4">
          <div class="text-4xl font-black text-[#0FA36B] font-mono">01</div>
          <h3 class="text-lg font-bold text-slate-900">Descubrimiento y Arquitectura</h3>
          <p class="text-gray-500 text-sm leading-relaxed">Analizamos tus requerimientos lógicos y diseñamos la estructura de base de datos y flujos óptimos.</p>
        </div>
        <div class="space-y-4 border-t md:border-t-0 md:border-l border-gray-100 pt-6 md:pt-0 md:pl-8">
          <div class="text-4xl font-black text-[#0FA36B] font-mono">02</div>
          <h3 class="text-lg font-bold text-slate-900">Desarrollo e Integración</h3>
          <p class="text-gray-500 text-sm leading-relaxed">Escribimos código limpio, modular y tipado. Implementamos interfaces interactivas y APIs robustas.</p>
        </div>
        <div class="space-y-4 border-t md:border-t-0 md:border-l border-gray-100 pt-6 md:pt-0 md:pl-8">
          <div class="text-4xl font-black text-[#0FA36B] font-mono">03</div>
          <h3 class="text-lg font-bold text-slate-900">Despliegue y Monitoreo</h3>
          <p class="text-gray-500 text-sm leading-relaxed">Configuramos entornos de producción optimizados en servidores seguros asegurando funcionamiento ideal.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="max-w-7xl mx-auto px-6 mb-16 md:mb-24">
    <div class="bg-slate-900 rounded-3xl p-8 md:p-16 text-center relative overflow-hidden shadow-xl">
      <div class="absolute -top-24 -right-24 w-72 h-72 bg-[#0FA36B] opacity-10 blur-[100px] pointer-events-none"></div>
      
      <div class="max-w-2xl mx-auto space-y-6 relative z-10">
        <h2 class="text-3xl md:text-5xl font-black text-white tracking-tight leading-tight">
          ¿Listo para construir algo <br class="hidden sm:inline"/> extraordinario?
        </h2>
        <p class="text-gray-400 text-sm md:text-base font-normal max-w-md mx-auto">
          Hablemos sobre tu infraestructura, tus objetivos de conversión y cómo podemos ayudarte a lanzar tu próximo producto digital.
        </p>
        <div class="pt-4">
          <NuxtLink to="/contacts" class="inline-block bg-[#0FA36B] hover:bg-[#09754c] text-slate-950 hover:text-white font-bold text-sm px-8 py-4 rounded-md transition-colors shadow-md">
            Empieza aqui
          </NuxtLink>
        </div>
      </div>
    </div>
  </section>
</template>