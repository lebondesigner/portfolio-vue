<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="jumbotron">
    <div class="container">
      <h1 class="display-4">Mon portfolio</h1>
      <p class="lead">Voici mes projets et des infos sur moi !</p>

      <div class="d-flex justify-content-evenly flex-wrap">
        <div class="col-12 col-md-5 col-lg-3 col-xl-2 card mb-4">
          <img src="/img/logo1.jpg" class="card-img-top" alt="projet 1" />
          <div class="card-body">
            <h5 class="card-title">"Les ChaChoux"</h5>
            <p class="card-text">Logo pour un bar à chats.</p>
          </div>
        </div>

        <div class="col-12 col-md-5 col-lg-3 col-xl-2 card mb-4">
          <img src="/img/visuel5.jpg" class="card-img-top" alt="projet 1" />
          <div class="card-body">
            <h5 class="card-title">"Newsletter"</h5>
            <p class="card-text">
              Newsletter pour une entreprise qui créé des ambiances dans des
              pièces de maisons et qui organise des rangements de sorte à avoir
              un espace optimal.
            </p>
          </div>
        </div>
      </div>

      <RouterLink to="/projets" class="btn btn-primary btn-lg"
        >Voir plus de projets</RouterLink
      >
    </div>
  </div>
</template>
