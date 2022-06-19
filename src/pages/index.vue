<template>
  <Header />
  <div class="wrapper">
    <Sidebar />
    <main>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quo vero sit ex pariatur corrupti voluptate accusamus dolore eaque rerum assumenda recusandae ducimus voluptatum eos ratione repellat, neque architecto id alias!
      </p>
    </main>
  </div>
</template>

<script>
import Header from '../components/Header.vue';
import Sidebar from '../components/Sidebar.vue';
export default {
  components: {
    Header,
    Sidebar
  }
}
</script>

<style scoped>
  .wrapper {
    max-width: 70rem;
    margin: 2rem auto;
    padding: 0 1rem;
    display: grid;
    grid-template-columns: 256px 1fr;
    gap: 2rem;
    align-items: flex-start;
  }
</style>