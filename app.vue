<template>
  <div>
    <Navbar />
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">

  useHead({
    title: 'Boilerplate'
  })

  const config = useRuntimeConfig();

  console.log('SERVER_KEY_EXAMPLE: ' + config.serverKeyExample);
  console.log('PUBLIC_KEY_EXAMPLE: ' + config.public.publicKeyExample);

</script>
