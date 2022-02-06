<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 La composición digital 
    #t_1_1.titulo-segundo.color-secundario
      h2 1.1 Tipos de composición 
    #t_1_2.titulo-segundo.color-secundario
      h2 1.2 Reglas de la composición digital
    #t_1_3.titulo-segundo.color-secundario
      h2 1.3 Técnicas de composición 
    #t_1_4.titulo-segundo.color-secundario
      h2 1.4 Software de composición 
    
  
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
