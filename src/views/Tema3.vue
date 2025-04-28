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
                p.mb-0(data-aos="fade-up") Para el tema en estudio, los ingresos de actividades ordinarias surgen en el curso del desarrollo del objeto social principal de la empresa y adoptan una gran variedad de nombres, tales como ventas, comisiones, intereses, dividendos, regalías y alquileres.
        

    #t_3_1.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 3.1 Política contable

    p.mb-5 Los ingresos por actividades ordinarias surgen en el curso del desarrollo del objeto social principal de la empresa y adoptan una gran variedad de nombres, tales como ventas, comisiones, intereses, dividendos, regalías y alquileres.


    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En el manual de políticas contables correspondiente a los ingresos, la empresa identifica aquellos generados por actividades ordinarias, estableciendo los lineamientos para su reconocimiento en las diferentes formas y medios de pago.
          br
          br
          | De igual forma las políticas contables en torno a los ingresos, establecen la presentación de los mismos en los estados financieros, reflejando de forma separada los de operaciones ordinarias de aquellos de operaciones extraordinarias.

    Separador

    #t_3_2.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 3.2 Medición, reconocimiento con impuestos y retenciones

    p.mb-5 La entidad medirá los ingresos de actividades ordinarias al valor razonable de la contraprestación recibida o por recibir, el cual tiene en cuenta el importe de descuentos comerciales, descuentos por pronto pago y rebajas por volumen de ventas que sean practicados por la entidad.

    .row.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema3/4.svg", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-7

        .row.align-items-center.mb-4
          .col-lg-auto.d-none.d-lg-block
            img(src="@/assets/curso/tema3/5.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Se incluirá en los ingresos por actividades ordinarias solamente las entradas brutas de beneficios económicos recibidos y por recibir por parte de la entidad, actuando por cuenta propia.

        .bg-color-3.p-4.tarjeta
          p(data-aos="fade-left").mb-0 No se incluirá en los ingresos por actividades ordinarias, los importes recibidos por cuenta de terceras ni el impuesto sobre las ventas.


    .row.mb-5.justify-content-center
      .col-lg-10
        p.mb-0 La entidad reconocerá ingresos por actividades ordinarias procedentes de la venta de inventarios, cuando se cumplan las siguientes condiciones:
    


    .bg-full-width.bg-fondo-5.mb-5
      .px-4.px-md-5
        .row.justify-content-center
          .col-lg-10
            .carousel-bg

              SlyderF.mb-5(columnas="col-lg-4")(data-aos="zoom-in-up")
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema3/icono-1.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center La entidad ha transferido al comprador los riesgos y ventajas, derivados de la propiedad de los bienes.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema3/icono-2.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center La entidad no conserva ninguna restricción sobre la propiedad y el control de los bienes vendidos.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema3/icono-3.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center El importe de los ingresos de actividades ordinarias puede medirse con fiabilidad.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema3/icono-4.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Sea probable que la entidad obtenga los beneficios económicos asociados con la transacción.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema3/icono-5.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Los costos incurridos, o por incurrir, en relación con la transacción pueden ser medidos con fiabilidad.


            .row.mb-5
              .col-lg-7
                p(data-aos="fade-left") El impuesto al valor agregado, generado en la operación de venta en actividades ordinarias se medirá sobre la base del precio de venta aceptado por el cliente, en la tarifa establecida por la norma fiscal vigente.
            
                .bg-color-2.p-4(data-aos="fade-left").mb-4
                  p.mb-0 En cuanto a los anticipos por retenciones en la fuente sobre los impuestos a la renta, a las ventas y a industria y comercio; que aplique o aplicará el cliente de acuerdo con su condición fiscal, se medirán de forma independiente sobre las bases establecidas por la norma fiscal.

                p.mb-0 A continuación, se muestra un ejercicio de reconocimiento de los ingresos por actividades ordinarias:
            
              .col-lg-5.d-none.d-lg-block
                figure
                  img(src="@/assets/curso/tema3/6.png", data-aos="zoom-in")
            
            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Vende inventarios de contado por un valor de $ 12.900.000 incluido IVA 19 %, menos: retefuente 2,5 % y reteica 0,6 %. #[span.text-red (60 % Gasto de Venta)].


            .row.mb-5
              .col-lg-4.d-none.d-lg-block
                figure
                  img(src="@/assets/curso/tema3/7.png", data-aos="zoom-in")
              .col-lg-8
                .titulo-sexto.color-acento-contenido.mb-3
                  h5 Tabla 20.
                  span Registro contable por venta de inventarios, anticipos de retención, recaudo y reconocimiento del costo de venta
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center ELE
                        th.bg-color-acento-contenido.text-center Cuenta
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center IN
                        td Venta de inventarios
                        td.text-center -
                        td.text-center 10.840.336
                      tr.bg-color-7
                        td.text-center PS
                        td IVA Generado
                        td.text-center -
                        td.text-center 2.059.664
                      tr.bg-color-white
                        td.text-center AC
                        td Anticipo Retefuente 2,5%
                        td.text-center 271.008
                        td.text-center -
                      tr.bg-color-7
                        td.text-center AC
                        td Anticipo Reteica 0,6%
                        td.text-center 65.042
                        td.text-center -
                      tr.bg-color-white
                        td.text-center AC
                        td Cuentas por cobrar Clientes
                        td.text-center 12.563.950
                        td.text-center -
                      tr.bg-color-7
                        td.text-center AC
                        td Cuentas por cobrar Clientes
                        td.text-center -
                        td.text-center 12.563.950
                      tr.bg-color-white
                        td.text-center AC
                        td Efectivo y equivalentes al efectivo
                        td.text-center 12.563.950
                        td.text-center -
                      tr.bg-color-7.text-red
                        td.text-center GA
                        td Gasto de venta
                        td.text-center 6.504.202
                        td.text-center -
                      tr.bg-color-white.text-red
                        td.text-center AC
                        td Inventarios para la venta
                        td.text-center -
                        td.text-center 6.504.202


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Su cliente le devuelve inventarios por $ 1.000.000 más IVA.  #[span.text-red (60 % Gasto Devolución de Venta)].




            .row
              .col-lg-4.d-none.d-lg-block
                figure
                  img(src="@/assets/curso/tema3/8.png", data-aos="zoom-in")
              .col-lg-8
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 21.
                  span Registro contable por devolución en ventas con retenciones y reversión del costo de venta
                .tabla-a.color-acento-contenido
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center ELE
                        th.bg-color-acento-contenido.text-center Cuenta
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center IN
                        td Devoluciones en Venta
                        td.text-center 1.000.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center PS
                        td IVA Generado
                        td.text-center 190.000
                        td.text-center -
                      tr.bg-color-white
                        td.text-center AC
                        td Anticipo Retefuente 2,5%
                        td.text-center -
                        td.text-center -
                      tr.bg-color-7
                        td.text-center AC
                        td Anticipo Reteica 0,6%
                        td.text-center -
                        td.text-center 25.000
                      tr.bg-color-white
                        td.text-center AC
                        td Efectivo y equivalentes al efectivo
                        td.text-center -
                        td.text-center 6.000
                      tr.bg-color-7.text-red
                        td.text-center GA
                        td Gasto de venta
                        td.text-center -
                        td.text-center 1.159.000
                      tr.bg-color-white.text-red
                        td.text-center AC
                        td Inventarios para la venta
                        td.text-center 600.000
                        td.text-center 600.000


    Separador

    #t_3_3.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 3.3 Presentación y revelación

    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-4.mb-4(data-aos="zoom-in-up")
        .tarjeta.bg-color-2.px-4.py-4.h-100
          img.d-block.mb-3(
            src="@/assets/curso/tema3/9.svg"
            alt=""
            style="width: 90px"
          )
          p.mb-0 Los estados financieros deben reflejar de forma separada los ingresos por operaciones de actividades ordinarias de aquellos originados por actividades extraordinarias.


      .col-lg-3.d-none.d-lg-block
        figure.px-lg-3
          img(src="@/assets/curso/tema3/10.png", data-aos="zoom-in")

      .col-lg-5
        .bg-color-4.p-4.mb-4
          p.mb-0 De igual forma, los estados financieros reflejarán por separado aquellas operaciones que disminuyen el valor de ingresos, como es el caso de las devoluciones en ventas.

        p.mb-0 Por otro lado, la entidad revelará en notas a los estados financieros las políticas contables adoptadas para el reconocimiento de los ingresos de actividades ordinarias, mostrándolas de forma separada de aquellas actividades extraordinarias.
    

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
