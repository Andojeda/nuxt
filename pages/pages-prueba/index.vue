<template>
    <div class="container">
        <Logo />
        <h1 class="title">
            Carpeta de pruebas
        </h1>
        <NuxtLink to="/"> <el-button type="primary"> Inicio </el-button> </NuxtLink> <hr>
      <BaseButton />       <hr>
      <NuxtLink to="/prueba2"> <el-button type="danger"> Prueba 2 </el-button> </NuxtLink>
    </div>
</template>


<script>
export default {}
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
