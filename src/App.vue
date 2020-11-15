<template>
  <div id="app">
    <header>
      <figure>
        <img src="./assets/logo.png" alt="logo">
        <figcaption>
          <span>Juan</span>
          <span> Kaenel</span>
        </figcaption>
      </figure>
      <nav>
        <button>
          <!-- Botón hamburguesa, traído desde vue add fontawesome, despúes  configuro /plugins/fontawesome.js -->
          <fa :icon="['fas', 'bars']"></fa>
        </button>
      </nav>
    </header>
    <section class="nav-content">
        <button class="nav-content__button">Home</button>
        <button class="nav-content__button">About</button>
        <button class="nav-content__button">Contact</button>
      </section>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style lang="scss" src="@/assets/css/components/header.scss">

</style>
