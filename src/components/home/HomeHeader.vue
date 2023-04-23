<script setup>
defineProps({
    msg: {
        type: String,
        required: true
    }
})
</script>

<template>
    <div class="greetings">
        <h1 class="blue"><a href="https://9oya.github.io/">{{ msg }}</a></h1>
      <h3>
          Let's build great things together.
      </h3>
  </div>
</template>

<style scoped>
.greetings h1 {
    text-align: center;
    font-weight: 500;
    font-size: 2.6rem;
    top: -10px;
}
.greetings h3 {
    text-align: center;
    font-size: 1.2rem;
}
</style>