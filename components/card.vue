<template>
  <div class="card card-side bg-base-100 shadow-xl">
    <figure>
      <img src="https://api.lorem.space/image/movie?w=200&h=280" alt="Movie" />
    </figure>
    <div class="card-body">
      <h2 class="card-title">{{ title }}</h2>
      <p>{{ content }}</p>
      <div class="justify-end card-actions">
        <button class="btn btn-primary">Lire</button>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Card",
  props: {
    title: String,
    content: String,
  },
};
</script>
