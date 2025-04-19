<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row
      .col-lg-3
        figure
          img(src="@/assets/curso/intro/1.png", data-aos="zoom-in", style="max-width: 292px").mx-auto.mb-4.mb-lg-0

      .col-lg-9

        .row.align-items-center.mb-4
          .col-lg-auto.d-none.d-lg-block
            img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 En el presente componente podrá conocer los conceptos referentes a los inventarios destinados para la venta, así mismo, le permite aplicar los sistemas de inventarios, sus correspondientes métodos de valuación; al igual que los instrumentos financieros utilizados en operaciones de compra y venta de inventarios, con la respectiva carga impositiva, de acuerdo con la normatividad y políticas contables vigentes.
    
        .bg-color-1.mb-5(data-aos="fade-up")
          .row.justify-content-center.align-items-center
            .col-lg
              .p-4
                p.mb-0(data-aos="fade-up") #[strong Nota aclaratoria:] las tablas que se toman como referencia en los ejemplos de cada uno de los temas desarrollados, elaboradas mediante el programa Excel son derivadas de estos ejercicios, la elaboración es propia del autor del presente componente, por lo tanto, no se numeran y no se establece un nombre específico.
            .col-lg-auto.d-none.d-xl-block
              figure
                img(src='@/assets/curso/intro/3.svg', alt='')

    

</template>

<script>
export default {
  name: 'Introduccion',
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
