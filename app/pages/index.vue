<template>
  <section class="relative min-h-[500px] md:min-h-[600px] flex items-center overflow-hidden bg-white">
    
    <div class="absolute inset-0 z-0">
      <img 
        src="/img/tepuykukenan.jpg" 
        alt="Desarrollo de Tecnología" 
        class="w-full h-full object-cover object-right lg:object-center opacity-42"
      />
    </div>

    <div class="absolute inset-0 bg-gradient-to-r from-white via-white/90 sm:via-white/80 to-white/10 md:to-transparent z-10"></div>

    <div class="max-w-7xl mx-auto px-6 py-12 md:py-20 w-full relative z-20 grid grid-cols-1 lg:grid-cols-12">
      
      <div class="lg:col-span-7 space-y-6">
        <h1 class="text-5xl md:text-6xl font-black text-slate-900 tracking-tight leading-[1.1]">
          Elevamos tus negocios con 
          <span class="inline-block bg-slate-900 text-[#fcaa1c] px-4 py-1 mt-2 transform -skew-x-2">
            Tecnologia
          </span>
        </h1>

        <p class="text-gray-600 text-sm md:text-base max-w-lg leading-relaxed font-normal">
          Diseñamos arquitecturas SaaS escalables y landing pages de alto rendimiento con la precisión de ingeniería de Tepuy Innovations. Desde la idea conceptual hasta el lanzamiento al mercado.
        </p>

        <div class="flex flex-wrap gap-4 pt-4">
          <NuxtLink to="/contacts" class="cursor-pointer bg-[#00D95A] hover:bg-[#00bc4d] text-slate-950 font-bold text-sm px-6 py-3.5 rounded-sm transition-colors shadow-md">
            Empieza tu proyecto
          </NuxtLink>
          <NuxtLink to="/services" class="cursor-pointer bg-white hover:bg-gray-50 text-slate-900 font-bold text-sm px-6 py-3.5 rounded-sm border-2 border-slate-900 transition-colors">
            Ver servicios
          </NuxtLink>
        </div>
      </div>

    </div>
  </section>
</template>