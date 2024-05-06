<template>
  <div>
    <h2 class="uppercase text-xs font-semibold text-gray-400 mb-6">
      Mes dernières Réalisations
    </h2>
    <div class="space-y-4 mt-8">
      <h2
        class="text-base font-semibold font-display tracking-tight text-gray-800 dark:text-gray-100 group-hover:text-primary-600"
      >
        Firmware Rust no std sur ESP32 avec communication Lorawan 
      </h2>
      <div class="relative z-10 mt-2 text-sm text-gray-600 dark:text-gray-400">
        <p>Firmware pour ESP32 basé sur ESP-HAL (no std) et embassy</p>
        <p>Gestion communication Lorawan</p>
        <p>Gestion deep sleep</p>
      </div>
    </div>
    <div class="space-y-4 mt-8">
      <h2
        class="text-base font-semibold font-display tracking-tight text-gray-800 dark:text-gray-100 group-hover:text-primary-600"
      >
        Intégration du GPU Vivante sur IMX6
      </h2>
      <div class="relative z-10 mt-2 text-sm text-gray-600 dark:text-gray-400">
        <p>Intégration driver GPU Yocto</p>
        <p>Benchmark du GPU</p>
      </div>
    </div>
    <div class="space-y-4 mt-8">
      <h2
        class="text-base font-semibold font-display tracking-tight text-gray-800 dark:text-gray-100 group-hover:text-primary-600"
      >
        BSP Yocto Raspberry PI4 avec lecture de vidéos 4k
      </h2>
      <div class="relative z-10 mt-2 text-sm text-gray-600 dark:text-gray-400">
        <p>Création d'un BSP sur la dernière version Yocto LTS</p>
        <p>Environnement de compilation sous Docker</p>
        <p>
          Configuration pour une machine Raspberry PI 4, Kernel 64bits 6.1 LTS
        </p>
        <p>Intégration d'un système de mise à jour OTA (u-boot, RAUC)</p>
        <p>Optimisation pour la lecture de vidéos 4K sur HDMI via GPU</p>
      </div>
    </div>
    <div class="space-y-4 mt-8">
      <h2
        class="text-base font-semibold font-display tracking-tight text-gray-800 dark:text-gray-100 group-hover:text-primary-600"
      >
        BSP Yocto Raspberry Compute Module 4, custom hardware
      </h2>
      <div class="relative z-10 mt-2 text-sm text-gray-600 dark:text-gray-400">
        <p>Création d'un BSP sur la dernière version Yocto LTS</p>
        <p>Environnement de compilation sous Docker</p>
        <p>
          Configuration pour une machine Raspberry CM4, Kernel 64bits 6.1 LTS
        </p>
        <p>Intégration d'un système de mise à jour OTA (u-boot, RAUC)</p>
        <p>Customisation du kernel pour une custom carrier board</p>
        <p>Dockerisation de l'applicatif</p>
      </div>
    </div>
    <div class="flex items-center justify-center mt-6 text-sm">
      <UButton
        label="Tous les projets &rarr;"
        to="/projects"
        variant="link"
        color="gray"
      />
    </div>
  </div>
</template>

<script lang="ts" setup></script>
