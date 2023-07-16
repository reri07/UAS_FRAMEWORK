<script>
  export default {};
</script>
<template>
  <div id="app">
    <NuxtLayout :name="layout">
      <NuxtPage />
    </NuxtLayout>
    <slot />
  </div>
</template>
