<template>
  <div class="group bg-white p-8 rounded-2xl border border-gray-100 hover:border-[#00D95A] transition-all duration-300 shadow-sm hover:shadow-xl">
    <div class="w-12 h-12 bg-slate-900 rounded-lg flex items-center justify-center mb-6 group-hover:scale-110 transition-transform">
      <slot name="icon"></slot>
    </div>
    <h3 class="text-xl font-bold text-slate-900 mb-3">{{ title }}</h3>
    <p class="text-gray-500 text-sm leading-relaxed mb-6">
      {{ description }}
    </p>
    <ul class="space-y-2">
      <li v-for="item in features" :key="item" class="flex items-center text-xs text-slate-700 font-medium">
        <span class="w-1.5 h-1.5 bg-[#00D95A] rounded-full mr-2"></span>
        {{ item }}
      </li>
    </ul>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  description: String,
  features: Array
})
</script>