<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Mon portfolio</h1>
      <p class="lead">
        Voici mes projets et des infos sur moi !
      </p>
      <RouterLink to="/about" class="btn btn-primary btn-lg"
        >En savoir plus sur moi</RouterLink
      >
    </div>
  </div>
</template>