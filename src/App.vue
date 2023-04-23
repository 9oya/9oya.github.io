<script setup>
import HomeHeader from './components/home/HomeHeader.vue'
import HomeBody from './components/home/HomeBody.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <HomeHeader msg="eido9oya.com" />
    </div>
  </header>

  <main>
    <HomeBody />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

main {
  padding: 2.0rem;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
