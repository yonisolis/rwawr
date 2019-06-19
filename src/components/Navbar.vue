<template>
<nav class="navbar navbar-light bg-light">
  <a class="navbar-brand">hola</a>
  <form class="form-inline" v-on:submit.prevent="search">
    <input v-model="titlesearch" class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
  </form>
</nav>
</template>

<script>
export default {
  name: 'Navbar'
}

</script>
