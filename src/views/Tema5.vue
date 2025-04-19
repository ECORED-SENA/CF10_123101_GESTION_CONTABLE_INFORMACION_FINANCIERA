<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Gastos


    .tarjeta.bg-color-2.p-4.mb-5
      .row.align-items-center
        .col-lg-auto
          img(src="@/assets/curso/tema5/1.svg", style="max-width: 90px").mx-auto
        .col-lg
          p.mb-0 Los gastos representan disminuciones en los beneficios económicos de una entidad durante un periodo contable, ya sea por salidas de activos o por aumentos en los pasivos. Incluyen tanto erogaciones derivadas de actividades ordinarias, como el costo de ventas, salarios y depreciaciones, como también pérdidas.


    .video.mb-5
      iframe(width="560" height="315" src="https://www.youtube.com/embed/G5MSAfnArWU?si=89UaGniZkIwghAFO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)


</template>

<script>
export default {
  name: 'Tema5',
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
