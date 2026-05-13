<template>
    <div class="min-h-screen bg-[#F8F9FA] flex flex-col font-sans antialiased text-[#0F172A]">
        <AppHeader />
        <main class="flex-grow">
            <slot />
        </main>
        <AppFooter />
    </div>
</template>
