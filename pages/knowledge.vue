<template>
  <main class="min-h-screen">
    <AppHeader class="mb-16" title="Compétences" :description="description" />

    <div class="space-y-4 mt-8">
      <h2
        class="text-base font-semibold font-display tracking-tight text-gray-800 dark:text-gray-100 group-hover:text-primary-600"
      >
        Software
      </h2>
      <li>Langages : C, Python, Bash</li>
      <li>Versioning : Git, Svn</li>
      <li>Outils Linux : Yocto, Buildroot, Docker, Trace32</li>
      <li>Outils Cloud : Docker, Gitlab, Azure Devops, Ansible</li>
      <li>Outils Firmware : STM32Cube, ESP IDF</li>
    </div>

    <div class="space-y-4 mt-8">
      <h2
        class="text-base font-semibold font-display tracking-tight text-gray-800 dark:text-gray-100 group-hover:text-primary-600"
      >
        Hardware
      </h2>
      <li>Cibles : STM32MP1, Raspberry, IMX, ESP32, STM32x</li>
      <li>
        Outils de mesure : oscilloscope, analyseur logique, multimètre, ...
      </li>
      <li>Radio : WIFI, BLE, Bluetooth, LTE, LTEm, Zigbee</li>
      <li>Lecture de schémas électroniques</li>
    </div>
  </main>
</template>

<script setup>
const description = "Détail de mes compétences en développement embarqué.";
useSeoMeta({
  title: "Compétences | Pierrick Curt",
  description,
});
</script>
