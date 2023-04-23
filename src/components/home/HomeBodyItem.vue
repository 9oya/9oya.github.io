<template>
  <div class="item">
      <div class="details">
          <h3>
              <slot name="heading"></slot>
          </h3>
          <div class="desc">
              <slot name="description"></slot>
          </div>
          <div class="info">
              <slot name="info"></slot>
          </div>
      </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.details {
    flex: 1;
    margin-left: 1rem;
}
.info {
    margin-top: 1rem;
    font-size: 0.8rem;
    color: var(--color-text);
}
.desc {
    margin-top: 1rem;
    font-size: 0.9rem;
    color: var(--color-text);
}
h3 {
    font-size: 1.2rem;
    font-weight: 500;
    margin-bottom: 0.4rem;
    color: var(--color-heading);
}
</style>