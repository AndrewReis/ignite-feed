<template>
  <header class="header">
    <img src="../assets/ignite-logo.svg" alt="Ignite Logo">
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
  .header {
    background: var(--gray-800);
    display: flex;
    justify-content: center;
    padding: 1.25rem 0;
  }

  .header img {
    height: 2rem;
  }
</style>