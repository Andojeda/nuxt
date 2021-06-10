<template>
    <div class="container fondo">
        <div>
            <Logo />
            <h1 class="title">
                Prueba 1
            </h1>
      <NuxtLink to="/"> Inicio </NuxtLink> <hr>
      <NuxtLink to="/prueba2"> Prueba 2 </NuxtLink> <hr>
      <NuxtLink to="/pages-prueba/"> Prueba Carpeta 3 </NuxtLink>
        </div>
    </div>
</template>

<script>
export default {
    layout: 'prueba1'
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
