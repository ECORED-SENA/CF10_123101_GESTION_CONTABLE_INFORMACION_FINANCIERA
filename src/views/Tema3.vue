<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5.overflow-hidden
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Ingresos


    .tarjeta.bg-color-2.p-4.mb-5
      .row.align-items-center
        .col-lg-auto
          img(src="@/assets/curso/tema3/1.svg", style="max-width: 90px").mx-auto
        .col-lg
          p.mb-0 El término de ingresos puede tener diferentes interpretaciones, las cuales coinciden en que generan un incremento patrimonial, como consecuencia de incrementos de activos y/o disminución de pasivos.


    p.mb-5 De conformidad con la NIIF 15 (2009), es fundamental tener presente en la política contable los siguientes aspectos, frente a la presentación de los ingresos en los estados financieros:



    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white.p-4.tarjeta
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-1.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Cuando una de las partes de un contrato haya cumplido, una entidad presentará el contrato en el estado de situación financiera como un activo del contrato o un pasivo del contrato.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-2.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Si un cliente paga una contraprestación, o una entidad tiene un derecho incondicional a recibir un importe como contraprestación antes de que la entidad transfiera un bien o servicio al cliente, la entidad presentará el contrato como un pasivo del contrato cuando el pago se realice o sea exigible.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-3.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Si una entidad realiza el desempeño mediante la transferencia de bienes o servicios al cliente antes de que el cliente pague la contraprestación o antes de que sea exigible el pago, la entidad presentará el contrato como un activo del contrato, excluyendo de esta partida los importes presentados como cuentas por cobrar.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-4.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Una cuenta por cobrar es el derecho incondicional de una entidad a recibir una contraprestación.


    p.mb-5 Como un elemento de los estados financieros los ingresos incluyen tanto los generados por actividades ordinarias como los de actividades extraordinarias.

    .row.mb-5.justify-content-center
      .col-lg-10
        .bg-color-4.mb-5(data-aos="fade-up")
          .row.justify-content-center.align-items-center
            .col-lg-auto
              figure
                img(src='@/assets/curso/tema3/2.svg', alt='')
            .col-lg
              .p-4
                p.mb-0(data-aos="fade-up") Para el tema en estudio, los ingresos de actividades ordinarias surgen en el curso de las del desarrollo del objeto social principal de la empresa y adoptan una gran variedad de nombres, tales como ventas, comisiones, intereses, dividendos, regalías y alquileres.
        

    #t_3_1.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 3.1 Política contable

    p.mb-5 Los ingresos por actividades ordinarias surgen en el curso de las del desarrollo del objeto social principal de la empresa y adoptan una gran variedad de nombres, tales como ventas, comisiones, intereses, dividendos, regalías y alquileres.


    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En el manual de políticas contables correspondiente a los ingresos, la empresa identifica aquellos generados por actividades ordinarias, estableciendo los lineamientos para su reconocimiento en las diferentes formas y medios de pago.
          br
          br
          | De igual forma las políticas contables en torno a los ingresos, establecen la presentación de los mismos en los estados financieros reflejando de forma separada los de operaciones ordinarias, de aquellos de operaciones extraordinarias.

    Separador

    #t_3_2.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 3.2 Medición, reconocimiento con impuestos y retenciones

    p.mb-5 La entidad medirá los ingresos de actividades ordinarias al valor razonable de la contraprestación recibida o por recibir, el cual tiene en cuenta el importe de descuentos comerciales, descuentos por pronto pago y rebajas por volumen de ventas que sean practicados por la entidad.


</template>

<script>
export default {
  name: 'Tema3',
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
