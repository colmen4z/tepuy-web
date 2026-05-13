<script setup lang="ts">
const formData = reactive({
	name: '',
	company: '',
	email: '',
	type: 'saas',
	details: '',
});

const handleLogin = async () => {
	try {
		await new Promise((resolve) => setTimeout(resolve, 2000));
		console.log('Datos enviados con exito: ', formData);
	} catch (error) {
		console.log(error)
	}
};
</script>

<template>
  <div class="py-16 md:py-24">
    <div class="max-w-7xl mx-auto px-6 grid grid-cols-1 lg:grid-cols-12 gap-16 items-start">
      
      <div class="lg:col-span-5 space-y-8">
        <div>
          <div class="inline-block bg-slate-900 text-[#0FA36B] text-[10px] font-bold tracking-widest uppercase px-3 py-1 rounded mb-4">
            Nuestros Contactos
          </div>
          <h1 class="text-4xl md:text-5xl font-black text-slate-900 tracking-tight mb-4">
            Conectemos tu <br />
            Próximo Proyecto.
          </h1>
          <p class="text-gray-500 text-sm md:text-base leading-relaxed">
            ¿Tienes una idea para un SaaS o necesitas una landing page de alto rendimiento? Nuestro equipo está listo para analizar tus requerimientos.
          </p>
        </div>

        <div class="space-y-6 pt-4">
          
          <div class="flex items-start gap-4">
            <div class="w-10 h-10 bg-slate-900 rounded-lg flex items-center justify-center flex-shrink-0 text-[#0FA36B]">
            	<Icon name="material-symbols:mail-outline" />
            </div>
            <div>
              <h3 class="text-sm font-bold text-slate-900 uppercase tracking-wider">Correo electronico</h3>
              <p class="text-sm text-gray-500 mt-1">tepuyinnovations@gmail.com</p>
              <p class="text-sm text-gray-500 mt-1">tepuy.innovations@outlook.com</p>
            </div>
          </div>

          <div class="flex items-start gap-4">
            <div class="w-10 h-10 bg-slate-900 rounded-lg flex items-center justify-center flex-shrink-0 text-[#0FA36B]">
              <Icon name="mdi:instagram" />
            </div>
            <div>
              <h3 class="text-sm font-bold text-slate-900 uppercase tracking-wider">Instagram</h3>
              <p class="text-sm text-gray-500 mt-1">tepuyinnovations</p>
            </div>
          </div>
        </div>
      </div>

      <div class="lg:col-span-7 bg-white p-8 md:p-10 rounded-2xl border border-gray-100 shadow-xl relative overflow-hidden">
        
        <div class="absolute top-0 right-0 w-32 h-32 bg-[#00D95A]/5 blur-3xl pointer-events-none"></div>

        <form @submit.prevent="handleLogin" class="space-y-6">
          
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
            <div class="space-y-2">
              <label for="name" class="text-xs font-bold uppercase tracking-wider text-slate-700">Tu Nombre</label>
              <input
              	v-model="formData.name"
                type="text" 
                id="name" 
                required
                placeholder="..."
                class="w-full px-4 py-3 bg-gray-50 rounded-lg text-sm border border-gray-200 text-slate-900 focus:outline-none focus:border-[#0FA36B] focus:bg-white transition-colors"
              />
            </div>
            <div class="space-y-2">
              <label for="company" class="text-xs font-bold uppercase tracking-wider text-slate-700">Empresa <span class="text-gray-400 font-normal">(Opcional)</span></label>
              <input
              	v-model="formData.company"
                type="text" 
                id="company" 
                placeholder="..."
                class="w-full px-4 py-3 bg-gray-50 rounded-lg text-sm border border-gray-200 text-slate-900 focus:outline-none focus:border-[#0FA36B] focus:bg-white transition-colors"
              />
            </div>
          </div>

          <div class="space-y-2">
            <label for="email" class="text-xs font-bold uppercase tracking-wider text-slate-700">Correo Electrónico</label>
            <input
              v-model="formData.email"
              type="email" 
              id="email" 
              required
              placeholder="..."
              class="w-full px-4 py-3 bg-gray-50 rounded-lg text-sm border border-gray-200 text-slate-900 focus:outline-none focus:border-[#0FA36B] focus:bg-white transition-colors"
            />
          </div>

          <div class="space-y-2">
            <label for="project_type" class="text-xs font-bold uppercase tracking-wider text-slate-700">¿En qué podemos ayudarte?</label>
            <select 
              v-model="formData.type"
              id="project_type"
              class="w-full px-4 py-3 bg-gray-50 rounded-lg text-sm border border-gray-200 text-slate-900 focus:outline-none focus:border-[#0FA36B] focus:bg-white transition-colors appearance-none"
            >
              <option value="saas">Desarrollo de SaaS</option>
              <option value="landing">Landing Page</option>
              <option value="mobile">Desarrollo Mobile</option>
              <option value="other">Otro</option>
            </select>
          </div>

          <div class="space-y-2">
            <label for="message" class="text-xs font-bold uppercase tracking-wider text-slate-700">Detalles del Proyecto</label>
            <textarea
              v-model="formData.details"
              id="message" 
              rows="4" 
              required
              placeholder="Cuéntanos brevemente sobre tu idea, objetivos o stacks tecnológicos requeridos..."
              class="w-full px-4 py-3 bg-gray-50 rounded-lg text-sm border border-gray-200 text-slate-900 focus:outline-none focus:border-[#0FA36B] focus:bg-white transition-colors resize-none"
            ></textarea>
          </div>

          <button 
            type="submit" 
            class="cursor-pointer w-full bg-slate-900 hover:bg-slate-800 text-[#0FA36B] font-bold text-xs uppercase tracking-widest py-4 rounded-lg transition-colors shadow-md flex items-center justify-center gap-2"
          >
            <span>Enviar</span>
            <Icon name="weui:arrow-filled" style="width: 22px; height: 22px;" />
          </button>

        </form>
      </div>

    </div>
  </div>
</template>