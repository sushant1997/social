<template>
  <Nav></Nav>
  <main class="px-8 py-6 bg-gray-100">
    <RouterView />
  </main>
</template>

<script>
import Nav from './components/Nav.vue';
export default {
  components: {
    Nav
  }
}
</script>
