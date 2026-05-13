<template>
	<div class="py-16 md:py-24">
    <section class="max-w-7xl mx-auto px-6">
      <div class="max-w-3xl mb-16">
        <div class="inline-block bg-slate-900 text-[#0FA36B] text-[10px] font-bold tracking-widest uppercase px-3 py-1 rounded mb-4">
          Nuestras Soluciones
        </div>
        <h1 class="text-4xl md:text-5xl font-black text-slate-900 mb-6 tracking-tight">
          Ingeniería de Precisión para
          Productos Digitales.
        </h1>
        <p class="text-gray-500 text-lg leading-relaxed">
          No solo escribimos código; construimos los cimientos de tu próximo gran éxito. Nos especializamos en escalar ideas complejas mediante arquitecturas software robustas.
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        
        <ServiceCard 
          title="SaaS" 
          description="Estructuras en la nube diseñadas para soportar miles de usuarios concurrentes con latencia mínima."
          :features="['Multi-tenancy segura', 'Escalado horizontal', 'Microservicios']"
        >
          <template #icon>
          	<Icon name="fluent-mdl2:system" style="color: #0FA36B; width: 22px; height: 22px;" />
          </template>
        </ServiceCard>

        <ServiceCard 
          title="Landing Pages" 
          description="Diseños optimizados psicológicamente para convertir visitantes en clientes potenciales de forma masiva."
          :features="['Optimización de Core Web Vitals', 'A/B Testing', 'Copywriting persuasivo']"
        >
          <template #icon>
          	<Icon name="icon-park-outline:web-page" style="color: #0FA36B; width: 22px; height: 22px;" />
          </template>
        </ServiceCard>

        <ServiceCard 
          title="Desarrollo Mobile" 
          description="Aplicaciones nativas e híbridas que ofrecen una experiencia de usuario fluida y reactiva."
          :features="['Responsive', 'Integración de APIs', 'Modo Offline']"
        >
          <template #icon>
          	<Icon name="roentgen:phone" style="color: #0FA36B; width: 22px; height: 22px;" />
          </template>
        </ServiceCard>

        <ServiceCard 
          title="Seguridad e Infraestructura" 
          description="Auditorías de seguridad y despliegues automatizados (CI/CD) para mantener tu producto siempre vivo."
          :features="['Docker & Kubernetes', 'SSL Avanzado', 'Monitoreo 24/7']"
        >
          <template #icon>
          	<Icon name="mdi:clock-fast" style="color: #0FA36B; width: 22px; height: 22px;" />
          </template>
        </ServiceCard>

        <ServiceCard 
          title="Prototipado UI/UX" 
          description="Diseñamos interfaces que tus usuarios amarán usar, priorizando la accesibilidad y la estética tech."
          :features="['Design Systems', 'Prototipos en Figma', 'User Journey Maps']"
        >
          <template #icon>
          	<Icon name="tdesign:component-layout-filled" style="color: #0FA36B; width: 22px; height: 22px;" />
          </template>
        </ServiceCard>

      </div>
    </section>

    <section class="max-w-7xl mx-auto px-6 mt-24">
      <div class="bg-slate-900 rounded-3xl p-12 text-center relative overflow-hidden">
        <div class="absolute top-0 right-0 w-64 h-64 bg-[#00D95A] opacity-10 blur-[100px]"></div>
        <h2 class="text-3xl md:text-4xl font-bold text-white mb-6">¿Listo para hacer tu web realidad?</h2>
        <NuxtLink to="/contacts" class="bg-[#0FA36B] mt-4 text-black font-bold px-8 py-4 rounded-md hover:bg-white transition-colors cursor-pointer">
          Hablemos de tu proyecto
        </NuxtLink>
      </div>
    </section>
  </div>
</template>