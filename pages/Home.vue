<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Mon portfolio</h1>
      <p class="lead">Voici mes projets et des infos sur moi !</p>

      <div class="card" style="width: 18rem">
        <img src="../public/img/logo1.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">"Les Chachoux"</h5>
          <p class="card-text">Logo pour un bar à chats</p>
        </div>

        <img src="../public/img/visuel5.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">"Newsletter de juin"</h5>
          <p class="card-text">
            Newsletter pour une entreprise qui créé des ambiances dans des
            pièces de maisons et fait des rangements pratiques afin d'optimiser
            l'espace.
          </p>
        </div>
      </div>

      <RouterLink to="/projets" class="btn btn-primary btn-lg"
        >Voir mes projets</RouterLink
      >
    </div>
  </div>
</template>
