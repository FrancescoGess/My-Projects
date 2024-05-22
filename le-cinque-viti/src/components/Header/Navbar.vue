<script setup>
import { ref } from 'vue'


</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
      <!-- <img src="/src/assets/img/logo.webp" alt=""> -->
      <a class="navbar-brand" href="#">Le cinque viti</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll"
        aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Chi siamo</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">
              Shop
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
              <li><a class="dropdown-item" href="#">I nostri vini</a></li>
              <li><a class="dropdown-item" href="#">Merchandise abbigliamento</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Prodotti in arrivo</a></li>
            </ul>
          </li>
        </ul>
        <form class="d-flex">
          <input class="search" type="search" placeholder="Cerca" aria-label="Search">
          <button class="btn" type="submit">Cerca</button>
        </form>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>

nav {
  background-color: rgb(119, 11, 3);
  position: fixed;
  width: 100%;

  .btn {
    color: white;
  }

  .btn:hover {
    color: black;
  }

  .dropdown-menu{
    background-color:  rgb(148, 69, 5);
  }

  .search{
    border-radius: 5%;
    border: none;
  }
}
</style>
