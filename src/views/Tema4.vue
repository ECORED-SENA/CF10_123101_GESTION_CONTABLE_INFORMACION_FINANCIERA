<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Instrumentos Financieros - Clientes y otras cuentas por cobrar


    .row.mb-5
      .col-lg-6
        .bg-color-3.mb-5(data-aos="fade-up")
          .row.justify-content-center.align-items-center
            
            .col-lg
              .p-4
                p.mb-0(data-aos="fade-up") Dentro de los instrumentos financieros activos de carácter básico, generados a partir de un contrato sobresalen las cuentas comerciales por cobrar a clientes, de conformidad con la sección 11 de las NIIF para Pymes (2009).


            .col-lg-auto
              figure
                img(src='@/assets/curso/tema4/1.svg', alt='')



      .col-lg-6
        .tarjeta.bg-color-4.p-4.mb-4(data-aos="fade-up")
          p.mb-0 Si bien dentro de los activos como instrumentos financieros se identifican entre otros el efectivo y equivalentes al efectivo y las inversiones; son las cuentas comerciales por cobrar a clientes generadas a partir de la operación de venta de inventarios.

        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema4/2.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Las cuentas comerciales por cobrar se generan a partir de la venta de inventarios a crédito a un cliente; quien puede tratarse de una persona natural o jurídica que se convierten en un deudor comercial a partir de la entrega de los inventarios, sin restricciones a la propiedad de estos.

        

    #t_4_1.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 4.1 Política contable

    .row.mb-5
      .col-lg-7
        .tarjeta.bg-color-2.p-4.mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema4/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La NIC 8 (2018), establece que las políticas no necesitan ser aplicadas cuando el efecto de su utilización no sea significativo. Sin embargo, no es adecuado dejar de aplicar las NIIF, con el fin de alcanzar una presentación particular de la posición financiera, rendimiento financiero o flujos de efectivo de la entidad.


        p.mb-0 Las NIIF se acompañan de guías de cumplimiento obligatorio que ayudan a las entidades a aplicar sus requerimientos.


      .col-lg-5
        figure
          img(src="@/assets/curso/tema4/4.png", data-aos="zoom-in") 


    .row.mb-5.justify-content-center.mb-4
      .col-lg-10

        .bg-color-8.p-4
          .row.align-items-center
            .col-lg-4.d-none.d-lg-block
              figure
                img(src="@/assets/curso/tema4/5.svg").mx-auto.my-4.my-lg-0

            .col-lg-8

              p.mb-4 En ausencia de una NIIF que sea aplicable específicamente a una transacción o a otros hechos o condiciones, la gerencia deberá usar su juicio en el desarrollo y aplicación de una política contable, a fin de suministrar información que sea:

              .bg-color-white.p-2.mb-2
                ul.lista-ul--color.mb-0
                  li.d-flex.mb-0
                    i.fas.fa-chevron-right
                    p.mb-0 Relevante para las necesidades de toma de decisiones económicas de los usuarios.

              .bg-color-white.p-2.mb-2
                ul.lista-ul--color.mb-0
                  li.d-flex.mb-0
                    i.fas.fa-chevron-right
                    p.mb-0 Fiable, en el sentido de que los estados financieros presenten de forma fidedigna la situación financiera, el rendimiento financiero y los flujos de efectivo de la entidad; reflejen la esencia económica de las transacciones, otros eventos y condiciones, y no simplemente su forma legal; sean neutrales, es decir, libres de prejuicios o sesgos; sean prudentes; y estén completos.

  
    .row.mb-4
      .col-lg-7
        p.mb-4 De acuerdo con la sección 11 de NIIF para Pymes (2009), dentro de la elección de la política contable se consideran entre los instrumentos financieros de deuda, los préstamos por cobrar a terceros y las cuentas de origen comercial por cobrar a clientes.

        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema4/2.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 La entidad revelará, en el resumen de las políticas contables, la base de medición utilizada para instrumentos financieros de cuentas comerciales por cobrar a clientes, que considere relevantes para la comprensión de los estados financieros.

      .col-lg-5
        figure
          img(src="@/assets/curso/tema4/6.svg", data-aos="zoom-in") 

    Separador



</template>

<script>
export default {
  name: 'Tema4',
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
