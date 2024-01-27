<script setup></script>

<template>
  <div>
    <div class="mb-6 flex items-center gap-3">
      <div
        class="flex-none rounded-full p-1 text-primary-500 bg-primary-500/10"
      >
        <div class="h-1.5 w-1.5 rounded-full bg-current"></div>
      </div>
      <h2 class="uppercase text-xs font-semibold text-gray-400">
        Me contacter
      </h2>
    </div>

    <form
      name="contact"
      method="POST"
      data-netlify="true"
      netlify-honeypot="bot-field"
    >
      <input
        type="hidden"
        name="form-name"
        value="contact"
        data-netlify="true"
        netlify-honeypot="bot-field"
      />
      <p>
        <UInput
          type="text"
          name="name"
          placeholder="Nom Prénom"
          class="flex-1 mt-4"
          size="lg"
        />
      </p>
      <p>
        <UInput
          type="email"
          name="email"
          placeholder="Email"
          class="flex-1 mt-4"
          size="lg"
        />
      </p>
      <p>
        <UTextarea name="message" class="flex-1 mt-4" size="lg" />
      </p>
      <UButton
        type="submit"
        label="Envoyer &rarr;"
        class="mt-4"
        size="lg"
        color="black"
      />
    </form>
  </div>
</template>
