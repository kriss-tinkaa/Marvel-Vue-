<template>
     <header>
      <nav class="navbar navbar-dark bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand">Marvel</a>
          <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Search..." aria-label="Search">
            <button class="btn btn-light" type="submit">Все</button>
          </form>
        </div>
      </nav>
    </header>
</template>

<script>
    export default {
        name: "AppHeader",
        data() {
            return {
            }
        },
    }
</script>

<style scoped>

</style>
