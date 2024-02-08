<template>
  <div class="space-y-6">
    <NuxtImg
      src="/avatar.png"
      alt="Pierrick Curt"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px"
      placeholder
      format="webp"
    />
    <h1
      class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100"
    >
      Bonjour !
    </h1>
    <p class="text-gray-900 dark:text-gray-400 text-justify">
      Je suis Pierrick, freelance en développement embarqué basé à Lyon.
      Passionné par l'IoT, j'ai créé l'entreprise curtcircuit pour vous
      accompagner à développer ou améliorer vos produits. Avec une bonne
      maitrise du matériel, je développe vos propres BSP Linux embarqués, ou les
      firmwares de vos microcontroleurs.
    </p>
    <p class="text-gray-900 dark:text-gray-400 text-justify">
      Je développe également des produits d'IoT open source, le premier produit
      étant une box domotique MAPIO. Pour en savoir plus rendez-vous sur le site
      de l'entreprise:
      <a href="https://iotheque.com" target="_blank" class="underline"
        >IOTheque</a
      >
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Pierrick Curt",
  description:
    "Je suis Pierrick, développeur IOT Linux embarqué et microcontroleurs.",
});
</script>
