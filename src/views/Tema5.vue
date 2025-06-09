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
      iframe(width="560" height="315" src="https://www.youtube.com/embed/cNY5EcAetB0?si=SDR8GVXRqyqLcgNV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)



    .bg-full-width.bg-fondo-8
      .px-4.px-md-5
        p.mb-5 A continuación, se muestra un ejercicio de reconocimiento de diferentes tipos de gastos.

        .row.mb-5.justify-content-center
          .col-lg-10

            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Causa nómina del Auxiliar Contable así: Básico: $1.000.000, Días trabajados: 30, H.E.D.O: 15. Descuento por libranza $100.000, Arl nivel: I.


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla26.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 26.
                    span Registro contable de nómina y prestaciones sociales

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 510506 Sueldo
                          td.text-center 1.000.000
                          td.text-center -
                        tr.bg-color-7
                          td 510527 Auxilio transporte
                          td.text-center 108.254
                          td.text-center -
                        tr.bg-color-white
                          td 510515 Horas extras
                          td.text-center 78.125
                          td.text-center -
                        tr.bg-color-7
                          td 237005 Aportes salud
                          td.text-center -
                          td.text-center -
                        tr.bg-color-white
                          td 238030 Aportes pensión
                          td.text-center -
                          td.text-center 43.125
                        tr.bg-color-7
                          td 237030 Libranzas
                          td.text-center -
                          td.text-center 43.125
                        tr.bg-color-white
                          td 250505 Salarios por pagar
                          td.text-center -
                          td.text-center 1.000.129
                        tr.bg-color-7
                          td 510570 Aportes pensión
                          td.text-center 129.375
                          td.text-center -
                        tr.bg-color-white
                          td 510568 Aportes ARL
                          td.text-center 5.628
                          td.text-center -
                        tr.bg-color-7
                          td 510572 Aportes CCF
                          td.text-center 43.125
                          td.text-center -
                        tr.bg-color-white
                          td 238030 Aportes PENSIÓN
                          td.text-center -
                          td.text-center 129.375
                        tr.bg-color-7
                          td 237006 Aportes ARL
                          td.text-center -
                          td.text-center 5.628
                        tr.bg-color-white
                          td 237010 Aportes parafiscales
                          td.text-center -
                          td.text-center 43.125
                        tr.bg-color-7
                          td 510530 Cesantías
                          td.text-center 98.825
                          td.text-center -
                        tr.bg-color-white
                          td 510533 Intereses cesantías
                          td.text-center 11.864
                          td.text-center -
                        tr.bg-color-7
                          td 510536 Prima servicios
                          td.text-center 98.825
                          td.text-center -
                        tr.bg-color-white
                          td 510539 Vacaciones
                          td.text-center 49.472
                          td.text-center -
                        tr.bg-color-7
                          td 251010 Cesantías
                          td.text-center -
                          td.text-center 98.825
                        tr.bg-color-white
                          td 251515 Intereses cesantías
                          td.text-center -
                          td.text-center 11.864
                        tr.bg-color-7
                          td 252020 Prima servicios
                          td.text-center -
                          td.text-center 98.825
                        tr.bg-color-white
                          td 252525 Vacaciones
                          td.text-center -
                          td.text-center 49.472
                        tr.bg-color-7
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 1.623.493
                          td.text-center.fw-bold 1.623.493


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Causa honorarios de Abogado por $1.500.000, menos retefuente 10%.


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla27.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 27.
                    span Registro contable por causación de honorarios de abogado con retención del 10 %

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 511030 Asesoría jurídica
                          td.text-center 1.500.000
                          td.text-center -
                        tr.bg-color-7
                          td 236515 Retefuente honorarios
                          td.text-center -
                          td.text-center 150.000
                        tr.bg-color-white
                          td 233525 Honorarios
                          td.text-center -
                          td.text-center 1.350.000
                        tr.bg-color-7
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 1.500.000
                          td.text-center.fw-bold 1.500.000


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Causa el impuesto de Industria y Comercio por $1.850.000, menos retenciones que le practicaron por $620.000.


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla28.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 28.
                    span Registro contable por causación del impuesto de Industria y Comercio con retención aplicada

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 511505 Industria y comercio
                          td.text-center 1.850.000
                          td.text-center -
                        tr.bg-color-7
                          td 135518 ICA Retenido
                          td.text-center -
                          td.text-center 620.000
                        tr.bg-color-white
                          td 241205 Impuesto ICA
                          td.text-center -
                          td.text-center 1.230.000
                        tr.bg-color-7
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 1.850.000
                          td.text-center.fw-bold 1.850.000


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 4
                | Causa alquiler de equipos industriales por $2.000.000, menos retefuente 4% y reteica 1%.


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla29.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 29.
                    span Registro contable por causación de alquiler de equipos industriales con retención del 4 % y reteica del 1 %

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 512015 Maquinaria y equipo
                          td.text-center 2.000.000
                          td.text-center -
                        tr.bg-color-7
                          td 236525 Retefuente servicios
                          td.text-center -
                          td.text-center 80.000
                        tr.bg-color-white
                          td 236805 Reteica servicios
                          td.text-center -
                          td.text-center 20.000
                        tr.bg-color-7
                          td 233540 Arrendamientos
                          td.text-center -
                          td.text-center 1.900.000
                        tr.bg-color-white
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 2.000.000
                          td.text-center.fw-bold 2.000.000


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 5
                | Paga fletes por transportes de materiales por $1.000.000, menos retefuente 1%


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla30.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 30.
                    span Pago de transporte por $1.000.000 con retención del 1 %

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 513550 Transportes fletes
                          td.text-center 1.000.000
                          td.text-center -
                        tr.bg-color-7
                          td 236525 Retefuente servicios
                          td.text-center -
                          td.text-center 10.000
                        tr.bg-color-white
                          td 233545 Transportes fletes
                          td.text-center -
                          td.text-center 990.000
                        tr.bg-color-7
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 1.000.000
                          td.text-center.fw-bold 1.000.000


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 6
                | Causa mantenimiento de equipos de cómputo por $500.000, menos retefuente 6% y reteica 1%.


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla31.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 31.
                    span Causación de mantenimiento de equipos de cómputo por $500.000 con retención del 1 % y reteica del 1 %

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 514525 Equipos computación
                          td.text-center 500.000
                          td.text-center -
                        tr.bg-color-7
                          td 236525 Retefuente servicios
                          td.text-center -
                          td.text-center 30.000
                        tr.bg-color-white
                          td 236805 Reteica servicios
                          td.text-center -
                          td.text-center 5.000
                        tr.bg-color-7
                          td 233535 Servicio mantenimiento
                          td.text-center -
                          td.text-center 465.000
                        tr.bg-color-white
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 500.000
                          td.text-center.fw-bold 500.000


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 7
                | Legaliza anticipo para peajes por $500.000, soportados en $350.000


            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla32.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 32.
                    span Legalización de anticipo pagado en cheque por $250.000, agregando gasto de $12.000

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 515595 Otros - peajes
                          td.text-center 350.000
                          td.text-center -
                        tr.bg-color-7
                          td 110505 Caja general
                          td.text-center 150.000
                          td.text-center -
                        tr.bg-color-white
                          td 133015 Anticipo a trabajadores
                          td.text-center -
                          td.text-center 500.000
                        tr.bg-color-7
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 500.000
                          td.text-center.fw-bold 500.000

            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 8
                | Deprecia el primer mes por línea recta, computadores adquiridos en $5.000.000;  con un tiempo estimado de vida útil de 2 años, sin cuota de salvamento.

            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla33.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 33.
                    span Registro de seguro de prima por compra anticipada de bienes por $200.000

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 516020 Equipos de computo
                          td.text-center 208.333
                          td.text-center -
                        tr.bg-color-7
                          td 159220 Depreciación Eq.computo
                          td.text-center -
                          td.text-center 208.333
                        tr.bg-color-white
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 208.333
                          td.text-center.fw-bold 208.333


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 9
                | Reembolsa la caja menor, así: $60.000 en servicio de acueducto, $50.000 en elementos de aseo y $40.000 en papelería.

            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla34.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 34.
                    span Desembolso de caja menor por elementos de aseo y cafetería por $120.000

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 513525 Acueducto y alcantarillado
                          td.text-center 60.000
                          td.text-center -
                        tr.bg-color-7
                          td 519525 Elementos de aseo
                          td.text-center 50.000
                          td.text-center -
                        tr.bg-color-white
                          td 519530 Útiles papelería fotocopias
                          td.text-center 40.000
                          td.text-center -
                        tr.bg-color-7
                          td 111005 Bancos moneda nacional
                          td.text-center -
                          td.text-center 150.000
                        tr.bg-color-white
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 150.000
                          td.text-center.fw-bold 150.000


            ol.lista-ol--cuadro.mb-5
              li 
                .lista-ol--cuadro__vineta
                  span 10
                | Paga publicidad radial por $450.000

            .row.mb-5.justify-content-center
              .col-lg-10

                #Tabla35.mb-4.bloque-tabla-responsive
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 35.
                    span Pago de publicidad radial por $450.000

                  .tabla-a.color-acento-contenido.mb-3
                    table
                      thead
                        tr
                          th.bg-color-acento-contenido.text-center Cuenta
                          th.bg-color-acento-contenido.text-center Debe
                          th.bg-color-acento-contenido.text-center Haber
                      tbody
                        tr.bg-color-white
                          td 520560 Publicidad, propaganda
                          td.text-center 450.000
                          td.text-center -
                        tr.bg-color-7
                          td 111005 Bancos moneda nacional
                          td.text-center -
                          td.text-center 450.000
                        tr.bg-color-white
                          td.fw-bold SUMAS IGUALES
                          td.text-center.fw-bold 450.000
                          td.text-center.fw-bold 450.000

    Separador

    #tema5-1.titulo-segundo.color-acento-contenido
      h2 5.1 Política contable

    p.mb-5 Para la incorporación de las políticas contables de los gastos la entidad debe fundamentarse en la hipótesis del devengo. De conformidad con la sección 2 de NIIF para Pymes (2009), la base contable de acumulación o devengo establece que:


    .bg-color-2.mb-4(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto
          figure
            img(src='@/assets/curso/tema5/2.png', alt='')
        .col-lg
          .p-4
            .bg-color-white.p-2.mb-2
              ul.lista-ul--color.mb-0
                li.d-flex.mb-0
                  i.fas.fa-chevron-right
                  p.mb-0 Una entidad elaborará sus estados financieros, excepto en lo relacionado con la información sobre flujos de efectivo, utilizando la base contable de acumulación (o devengo). 

            .bg-color-white.p-2.mb-2
              ul.lista-ul--color.mb-0
                li.d-flex.mb-0
                  i.fas.fa-chevron-right
                  p.mb-0 De acuerdo con la base contable de acumulación (o devengo), las partidas se reconocerán como gastos cuando satisfagan las definiciones de dicha partida.

            .bg-color-white.p-2.mb-2
              ul.lista-ul--color.mb-0
                li.d-flex.mb-0
                  i.fas.fa-chevron-right
                  p.mb-0 Por otro lado, las políticas contables establecen que el reconocimiento de los gastos procede directamente del reconocimiento y la medición de activos y pasivos. 

            .bg-color-white.p-2.mb-2
              ul.lista-ul--color.mb-0
                li.d-flex.mb-0
                  i.fas.fa-chevron-right
                  p.mb-0 Una entidad reconocerá gastos en el estado del resultado cuando haya surgido un decremento en los beneficios económicos futuros, relacionado con un decremento en un activo o un incremento en un pasivo que pueda medirse con fiabilidad.

    Separador

    #tema5-2.titulo-segundo.color-acento-contenido
      h2 5.2 Presentación y revelación

    .row.mb-5
      .col-lg-8
        p.mb-4 Al igual que los ingresos, los gastos serán presentados en el estado de resultados de conformidad con lo establecido por la sección 5 de NIIF para Pymes (2009).

        p.mb-4 Una entidad presentará un desglose de gastos, utilizando una clasificación basada en la naturaleza o en la función de los gastos dentro de la entidad, lo que proporcione una información que sea fiable y más relevante.

      .col-lg-4.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema5/3.svg', alt='')



    .row.justify-content-center.align-items-stretch.mb-4
      .col-lg-4.mb-4.d-none.d-lg-block
        figure
          img(src='@/assets/curso/tema5/4.svg', alt='')

      .col-lg-4.mb-4
        .tarjeta--boton.bg-color-8.p-4.text-center.h-100(data-aos="flip-up")
          img(src='@/assets/curso/tema5/5.svg', alt='', style="max-width: 90px").mx-auto.mb-4
          h4.text-center.mb-4 Desglose por naturaleza de los gastos
          p.text-center Según este método de clasificación, los gastos se agrupan en el estado del resultado integral de acuerdo con su naturaleza (por ejemplo, depreciación, compras de materiales, costos de transporte, beneficios a los empleados y costos de publicidad) y no los redistribuirá entre las diferentes funciones dentro de la entidad.

      .col-lg-4.mb-4
        .tarjeta--boton.bg-color-8.p-4.text-center.h-100(data-aos="flip-up")
          img(src='@/assets/curso/tema5/6.svg', alt='', style="max-width: 90px").mx-auto.mb-4
          h4.text-center.mb-4 Desglose por función de los gastos
          p.text-center Según este método de clasificación, los gastos se agruparán de acuerdo con su función como parte del costo de las ventas o, por ejemplo, de los costos de actividades de distribución o administración. Como mínimo una entidad revelará, según este método, su costo de ventas de forma separada de otros gastos.



    .row.align-items-center
      .col-lg-auto.d-none.d-lg-block
        img(src="@/assets/curso/tema5/7.svg", style="max-width: 90px").mx-auto
      .col-lg
        p.mb-0 Por otro lado, la entidad revelará en notas a los estados financieros las políticas contables adoptadas para el reconocimiento de los gastos incurridos para actividades ordinarias, mostrándolos de forma separada de aquellos gastos incurridos de forma extraordinaria.


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
