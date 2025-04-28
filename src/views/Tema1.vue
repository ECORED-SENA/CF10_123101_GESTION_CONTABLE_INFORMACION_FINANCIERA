<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5.overflow-hidden
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Inventarios


    .row.align-items-stretch.mb-5
      .col-lg-7.order-2.order-lg-1
        .bg-color-2.p-4.h-100
          p.mt-xl-4 Antes de hablar del registro de compras y ventas, es importante enfocarse en el tema de los inventarios para la venta, producción o prestación de servicios, toda vez que constituyen la fuente generadora de ingresos para la empresa y por tanto requieren de un tratamiento especial.

      .col-lg-5.order-1.order-lg-2
        figure
          img(src="@/assets/curso/tema1/1.png", alt="").mb-4.mb-lg-0

    #t_1_1.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 1.1  Política contable

    p.mb-4 Dentro del manual de políticas contables establecido por la empresa, es de especial importancia el capítulo correspondiente a los inventarios, pues a través de este se establecen los lineamientos a seguir para la determinación del sistema y método de valuación de los inventarios y su correspondiente tratamiento en las diferentes operaciones.

    .row.mb-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema1/2.svg", alt="", style="max-width: 400px").mx-auto.mb-4

      .col-lg-8
        p.mb-4 De igual forma, la política contable de inventarios debe establecer los gastos correlacionados en una venta, donde lo principal corresponde al costo de venta, pues permite determinar el resultado de la operación.

        .bg-color-3.p-4.mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Otro aspecto fundamental que debe incluirse en la política de inventarios es el establecimiento de los precios de venta, pues la sección 13 de NIIF para Pymes (2009) requiere que se haga una comparación entre el costo de adquisición y los egresos necesarios para ponerlo en condiciones de venta y el precio de venta neto estimado, para determinar los costos de venta del inventario.

        .row.align-items-center
          .col-lg-auto.d-none.d-lg-block
            img(src="@/assets/curso/tema1/4.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Además de las compras, ventas de inventarios y las devoluciones que de estas se desprenden, también hacen parte de las políticas contables, los traslados entre bodegas y los procesos para el tratamiento de deterioros, y bajas de inventarios.


    .row.mb-5
      .col-lg-7
        
        p.mb-4 En la política contable de inventarios se debe establecer el sistema de inventarios a utilizar, el cual puede ser:

        .tarjeta.bg-color-4.p-4
          ul.lista-ul--color
            li.mb-3.d-flex.mb-2
              i.fas.fa-chevron-right
              p.mb-0 Una NIIF se aplica específicamente a una transacción y las políticas contables aplicadas a esa partida se determinarán con dicha NIIF.
            li.mb-3.d-flex.mb-2 
              i.fas.fa-chevron-right
              p.mb-0 En las NIIF se establecen políticas contables sobre las que el IASB (International Accounting Standards Board (Junta de Normas Internacionales de Contabilidad) ha llegado a la conclusión de que dan lugar a estados financieros con información relevante y fiable sobre las transacciones.
            li.mb-3.d-flex.mb-2
              i.fas.fa-chevron-right
              p.mb-0 Las NIIF se acompañan de guías que ayudan a las entidades a aplicar sus requerimientos.
            li.mb-3.d-flex.mb-2
              i.fas.fa-chevron-right
              p.mb-0 En ausencia de una NIIF que sea aplicable específicamente a una transacción, la gerencia deberá usar su juicio en el desarrollo y aplicación de una política contable, a fin de suministrar información que sea: relevante, fiable, fidedigna, neutral, prudente y que reflejen la esencia económica de las transacciones y no simplemente su forma legal.
            li.mb-3.d-flex
              i.fas.fa-chevron-right
              p.mb-0 La gerencia se referirá a las fuentes para considerar su aplicabilidad; como los requerimientos de temas relacionados y las definiciones, reconocimiento y medición para los elementos de los estados financieros.

      .col-lg-5.d-none.d-lg-block
        figure
          img(src="@/assets/curso/tema1/5.png", alt="").mb-4.mb-lg-0

    p.mb-5 Por otro lado, es importante tener en cuenta los siguientes aspectos contemplados por la NIC 2 para el correspondiente diseño de la política contable de los inventarios:

    .bg-full-width.bg-fondo-1
      .px-4.px-md-5.pb-5

        .carousel-bg

          .row.justify-content-center.align-items-center.my-5

            .col-lg-3.d-none.d-lg-block(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/6.png', style="max-width: 100%", alt='').m-auto

            .col-lg-8

              SlyderF.mb-5(columnas="col-lg-6")(data-aos="zoom-in-up")
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-1.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Deben ser considerados como activos poseídos para ser vendidos en el curso normal de la operación.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-2.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Identificados como elementos del proceso de producción con destino a ser vendido.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-3.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Establecidos como materiales o suministros que serán consumidos en el proceso de producción o en la prestación de servicios.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-4.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Valor neto realizable es el precio estimado de venta de un activo en el curso normal de la operación menos los costos estimados para terminar su producción y los necesarios para llevar a cabo la venta.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-5.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Valor razonable es el precio que se recibiría por vender un activo o que se pagaría por transferir un pasivo en una transacción ordenada entre participantes del mercado en la fecha de la medición.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-6.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center Entre los inventarios también se incluyen los bienes comprados y almacenados para su reventa, entre los que se encuentran, por ejemplo, las mercaderías adquiridas por un minorista para la reventa a sus clientes, y también los terrenos u otras propiedades de inversión que se tienen para ser vendidos a terceros.
                .tarjeta.bg-color-white.p-4.h-100.shadow-app.text-center
                  img(src='@/assets/curso/tema1/icono-7.svg' alt='AvatarTop' style="max-width: 90px").mx-auto.mb-3
                  p.text-center También son inventarios los productos terminados o en curso de fabricación mantenidos por la entidad, así como los materiales y suministros para ser usados en el proceso productivo.


    Separador
    
    #t_1_2.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 1.2  Concepto, tipos de inventario, valuación de inventarios

    p.mb-5 De conformidad con la NIC 2, se definen los diferentes tipos de costos, de la siguiente manera:


    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white.p-4.tarjeta
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-1.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Los inventarios se medirán al costo o al valor neto realizable, según cuál sea menor.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-2.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p El costo de los inventarios comprenderá todos los costos derivados de su adquisición, transformación, así como otros costos en los que se haya incurrido para darles su condición y ubicación actuales.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-3.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p El costo de adquisición de los inventarios comprenderá el precio de compra, los aranceles de importación y otros impuestos (que no sean recuperables posteriormente de las autoridades fiscales) y transporte, manejo y otros costos directamente atribuibles a la adquisición de mercaderías, materiales y servicios. Los descuentos comerciales, las rebajas y otras partidas similares se deducirán para determinar el costo de adquisición.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-4.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Los costos de transformación de los inventarios comprenderán aquellos costos relacionados con las unidades de producción, tales como la materia prima directa, la mano de obra directa y los costos indirectos de producción.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/slider-5.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              p Son costos indirectos fijos de producción los que permanecen relativamente constantes, con independencia del volumen de producción, tales como la depreciación y mantenimiento de los edificios y equipos de la fábrica y los activos por derecho de uso utilizados en el proceso de producción.


    p.mb-4.d-none.d-lg-block De acuerdo con la sección 13 de NIIF para Pymes (2009), los inventarios son activos:

    .row.mb-5.justify-content-center
      .col-lg-10
        .bg-color-3
          .row.align-items-center
            .col-lg-4
              figure
                img(src="@/assets/curso/tema1/7.svg", style="max-width: 295px").mx-auto.my-4.my-lg-0
            .col-lg-8
              .p-4
                p.mb-4.d-lg-none De acuerdo con la sección 13 de NIIF para Pymes (2009), los inventarios son activos:

                .bg-color-white.p-3.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 Poseídos para ser vendidos en el curso normal del negocio.

                .bg-color-white.p-3.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 En proceso de producción con vistas a esa venta.

                .bg-color-white.p-3.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 En forma de materiales o suministros, para ser consumidos en el proceso productivo.

                .bg-color-white.p-3.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 En la prestación de un servicio.



    p.mb-4 La necesidad de controlar los inventarios requiere la aplicación de un sistema que permita determinar el costo de existencia y el costo de venta; es así como se debe elegir entre dos opciones, el sistema periódico y el sistema permanente.

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.bg-color-5.text-white.p-5
        figure.mb-4
          img(src='@/assets/curso/tema1/8.svg', alt='', style="max-width: 85px")
          
        p.text-white.mb-4 El sistema de inventarios periódico tiene las siguientes características:

        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span a
            | Se hace conteo físico para hallar el costo de existencia.
          li 
            .lista-ol--cuadro__vineta
              span b
            | Solo al cierre del ejercicio se halla el costo de venta.
          li 
            .lista-ol--cuadro__vineta
              span c
            | Solo hay un método de valuación "Juego de Inventarios".
          li 
            .lista-ol--cuadro__vineta
              span d
            | El kárdex solo mueve unidades sin costos.

      .col-md.tarjeta.bg-color-6.p-5

        figure.mb-4
          img(src='@/assets/curso/tema1/9.svg', alt='', style="max-width: 85px")
          
        p.mb-4 El sistema de inventarios permanente tiene las siguientes características:

        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span a
            | Se hace conteo físico por control y no para hallar costos.
          li 
            .lista-ol--cuadro__vineta
              span b
            | Costos de venta y existencia se hallan en cualquier momento.
          li 
            .lista-ol--cuadro__vineta
              span c
            | Se debe elegir uno entre varios métodos de valuación "Promedio ponderado, Primeras en Entrar Primeras en Salir".
          li 
            .lista-ol--cuadro__vineta
              span d
            | El kárdex mueve tanto unidades como costos.


    p.mb-4 A continuación, se presenta un ejercicio utilizando el método de valuación por Promedio Ponderado, el cual emplea la media aritmética para determinar el costo unitario, de la siguiente manera:

    figure
      img(src='@/assets/curso/tema1/formula1.svg', alt='Fórmula del costo unitario: Costo unitario (COS.UND) es igual al costo total (COS.TAL) dividido entre la cantidad de unidades (UND).', style="max-width: 295px").mx-auto.mb-5


    .row.justify-content-center
      .col-lg-10
        p.mb-4 #[strong Ejemplo:] la empresa realiza en el mes las siguientes operaciones de su producto de inventarios "Camiseta" (todas las operaciones se hacen de contado).

        .row
          .col-lg-5
            figure
              img(src='@/assets/curso/tema1/10.svg', alt='', style="max-width: 400px").mx-auto.mb-4
          .col-lg-7
            .titulo-sexto.color-acento-contenido
              h5 Tabla 1.
              span Movimiento de inventario de camisetas
            .tabla-a.color-acento-contenido.mb-3
              table
                thead
                  tr
                    th.bg-color-acento-contenido.text-center(style="width: 20%")  Paso  
                    th.bg-color-acento-contenido.text-center  Descripción del movimiento

                tbody
                  tr.bg-color-white
                    td.text-center 0
                    td Inventario inicial: 80 camisetas a $5.000 c/u
                  tr.bg-color-7
                    td.text-center 1
                    td Compra: 120 camisetas a $5.500 c/u
                  tr.bg-color-white
                    td.text-center 2
                    td Compra: 100 camisetas a $6.000 c/u
                  tr.bg-color-7
                    td.text-center 3
                    td Devolución: 10 camisetas de la compra anterior
                  tr.bg-color-white
                    td.text-center 4
                    td Venta: 190 camisetas a #[span.text-red $15.000 c/u]
                  tr.bg-color-7
                    td.text-center 5
                    td Devolución: 10 camisetas de la venta anterior
                  tr.bg-color-white
                    td.text-center 6
                    td Compra: 90 camisetas a $6.500 c/u
                  tr.bg-color-7
                    td.text-center 7
                    td Venta: 100 camisetas a #[span.text-red $15.000 c/u]


    .bg-full-width.bg-fondo-2
      .p-4.p-md-5
        p.mb-4 El kárdex quedará así:

        .titulo-sexto.color-acento-contenido
          h5 Tabla 2.
          span Registro de inventario bajo el método de Promedio Ponderado.


        .bloque-tabla-responsive
          .tabla-a.color-acento-contenido.mb-5
            table
              thead
                tr
                  th.text-center.bg-color-acento-contenido(colspan="9") Promedio ponderado
                tr
                  th.text-center.bg-color-acento-contenido(style="width: 5%") F
                  th.text-center.bg-color-acento-contenido Concepto
                  th.text-center.bg-color-acento-contenido Unidades entrantes
                  th.text-center.bg-color-acento-contenido Costo total entradas
                  th.text-center.bg-color-acento-contenido Unidades salientes
                  th.text-center.bg-color-acento-contenido Costo total salidas
                  th.text-center.bg-color-acento-contenido Unidades en saldo
                  th.text-center.bg-color-acento-contenido Costo unitario saldo
                  th.text-center.bg-color-acento-contenido Costo total saldo

              tbody
                tr.bg-color-white
                  td.text-center 0
                  td Inventario inicial
                  td.text-center -
                  td.text-center -
                  td.text-center -
                  td.text-center -
                  td.text-center 80
                  td.text-center 5.000
                  td.text-center 400.000
                tr.bg-color-7
                  td.text-center 1
                  td Compra
                  td.text-center 120
                  td.text-center 660.000
                  td.text-center -
                  td.text-center -
                  td.text-center 200
                  td.text-center 5.300
                  td.text-center 1.060.000
                tr.bg-color-white
                  td.text-center 2
                  td Compra
                  td.text-center 100
                  td.text-center 600.000
                  td.text-center -
                  td.text-center -
                  td.text-center 300
                  td.text-center 5.533
                  td.text-center 1.660.000
                tr.bg-color-7
                  td.text-center 3
                  td Devolución compra 2
                  td.text-center -
                  td.text-center -
                  td.text-center 10
                  td.text-center 60.000
                  td.text-center 290
                  td.text-center 5.517
                  td.text-center 1.600.000
                tr.bg-color-white
                  td.text-center 4
                  td Venta
                  td.text-center -
                  td.text-center -
                  td.text-center 190
                  td.text-center 1.048.276
                  td.text-center 100
                  td.text-center 5.517
                  td.text-center 551.724
                tr.bg-color-7
                  td.text-center 5
                  td Devolución venta 4
                  td.text-center 10
                  td.text-center 55.172
                  td.text-center -
                  td.text-center -
                  td.text-center 110
                  td.text-center 5.517
                  td.text-center 606.897
                tr.bg-color-white
                  td.text-center 6
                  td Compra
                  td.text-center 90
                  td.text-center 585.000
                  td.text-center -
                  td.text-center -
                  td.text-center 200
                  td.text-center 5.959
                  td.text-center 1.191.897
                tr.bg-color-7
                  td.text-center 7
                  td Venta
                  td.text-center -
                  td.text-center -
                  td.text-center 100
                  td.text-center 595.948
                  td.text-center 100
                  td.text-center 5.959
                  td.text-center 595.948

        p.mb-5 Contablemente quedará así:

        .row.justify-content-center
          .col-lg-10

            #tablas3y4

            .row.mb-5
              .col-lg-6
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 3.
                  span Cuenta 1435 - Inventario de mercancías
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 0
                        td.text-center 400.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 1
                        td.text-center 660.000
                        td.text-center -
                      tr.bg-color-white
                        td.text-center 2
                        td.text-center 600.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 3
                        td.text-center -
                        td.text-center 60.000
                      tr.bg-color-white
                        td.text-center 4
                        td.text-center -
                        td.text-center 1.048.276
                      tr.bg-color-7
                        td.text-center 5
                        td.text-center 55.172
                        td.text-center -
                      tr.bg-color-white
                        td.text-center 6
                        td.text-center 585.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 7
                        td.text-center -
                        td.text-center 595.948
                      tr.bg-color-white
                        td.text-center #[strong Totales]
                        td.text-center #[strong 2.300.172]
                        td.text-center #[strong 1.704.224]
                      tr.bg-color-7
                        td.text-center #[strong Saldo]
                        td.text-center -
                        td.text-center #[strong 595.949]

              .col-lg-6
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 4.
                  span Cuenta 11 - Efectivo
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 3
                        td.text-center 60.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 4
                        td.text-center 2.850.000
                        td.text-center -
                      tr.bg-color-white
                        td.text-center 7
                        td.text-center 1.500.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 1
                        td.text-center -
                        td.text-center 660.000
                      tr.bg-color-white
                        td.text-center 2
                        td.text-center -
                        td.text-center 600.000
                      tr.bg-color-7
                        td.text-center 6
                        td.text-center -
                        td.text-center 585.000
                      tr.bg-color-white
                        td.text-center #[strong Totales]
                        td.text-center #[strong 4.410.000]
                        td.text-center #[strong 1.995.000]
                      tr.bg-color-7
                        td.text-center #[strong Saldo]
                        td.text-center -
                        td.text-center #[strong 2.415.000]  

            #tablas5y6
            .row.mb-5
              .col-lg-6
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 5.
                  span Cuenta 4135 - Ventas
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 4
                        td.text-center 2.850.000
                      tr.bg-color-7
                        td.text-center 7
                        td.text-center 1.500.000
                      tr.bg-color-white
                        td.text-center #[strong Totales]
                        td.text-center #[strong 4.350.000]

              .col-lg-6
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 6.
                  span Cuenta 4175 - Devoluciones en ventas
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                    tbody
                      tr.bg-color-white
                        td.text-center 5
                        td.text-center 150.000
                      tr.bg-color-7
                        td.text-center #[strong Totales]
                        td.text-center #[strong 150.000]

    
    .bg-full-width.bg-fondo-3
      .p-4.p-md-5
        p.mb-5 A continuación, se muestra el mismo ejercicio, pero ahora por el método de Primera en Entrar Primeras en Salir (PEPS), cuyo objetivo es mantener los costos más recientes.

        .row.justify-content-center
          .col-lg-10
            p.mb-4 #[strong Ejemplo:] la empresa realiza en el mes, las siguientes operaciones de su producto de inventarios “Camiseta” (todas las operaciones se hacen de contado).

            .row.mb-5
              .col-lg-4.d-none.d-lg-block
                figure
                  img(src='@/assets/curso/tema1/11.png', alt='', style="max-width: 295px").mx-auto.mb-4
              .col-lg-8
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 7.
                  span Detalle de movimientos de inventario de camisetas

                #tabla7
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center(style="width: 20%") Paso
                        th.bg-color-acento-contenido.text-center Descripción del movimiento
                    tbody
                      tr.bg-color-white
                        td.text-center 0
                        td Inventario inicial: 80 camisetas a $5.000 c/u
                      tr.bg-color-7
                        td.text-center 1
                        td Compra: 120 camisetas a $5.500 c/u
                      tr.bg-color-white
                        td.text-center 2
                        td Compra: 100 camisetas a $6.000 c/u
                      tr.bg-color-7
                        td.text-center 3
                        td Devolución: 10 camisetas de la compra anterior
                      tr.bg-color-white
                        td.text-center 4
                        td Venta: 190 camisetas a $15.000 c/u
                      tr.bg-color-7
                        td.text-center 5
                        td Devolución: 10 camisetas de la venta anterior
                      tr.bg-color-white
                        td.text-center 6
                        td Compra: 90 camisetas a $6.500 c/u
                      tr.bg-color-7
                        td.text-center 7
                        td Venta: 100 camisetas a $15.000 c/u

        p.mb-5 El kárdex quedará así:


        .titulo-sexto.color-acento-contenido
          h5 Tabla 8.
          span PEPS: Primeras en Entrar, Primeras en Salir

        .bloque-tabla-responsive
          .tabla-a.color-acento-contenido.mb-5
            table
              thead
                tr
                  th.colspan-9.text-center.bg-color-acento-contenido(colspan="9") PEPS : PRIMERAS EN ENTRAS PRIMERAS EN SALIR
                tr
                  th.text-center.bg-color-acento-contenido(style="width: 5%") F
                  th.text-center.bg-color-acento-contenido(style="width: 20%") Concepto
                  th.text-center.bg-color-acento-contenido Unidades entrantes
                  th.text-center.bg-color-acento-contenido Costo total entradas
                  th.text-center.bg-color-acento-contenido Unidades salientes
                  th.text-center.bg-color-acento-contenido Costo total salidas
                  th.text-center.bg-color-acento-contenido Unidades en saldo
                  th.text-center.bg-color-acento-contenido Costo unitario saldo
                  th.text-center.bg-color-acento-contenido Costo total saldo

              tbody
                tr.bg-color-white
                  td.text-center 0
                  td Inv. Ini
                  td.text-center -
                  td.text-center -
                  td.text-center -
                  td.text-center -
                  td.text-center 80
                  td.text-center 5.000
                  td.text-center 400.000

                tr.bg-color-7
                  td.text-center 1
                  td Compra
                  td.text-center 120
                  td.text-center 660.000
                  td.text-center -
                  td.text-center -
                  td.text-center 200
                  td.text-center 5.300
                  td.text-center 1.060.000

                tr.bg-color-white
                  td.text-center 2
                  td Compra
                  td.text-center 100
                  td.text-center 600.000
                  td.text-center -
                  td.text-center -
                  td.text-center 300
                  td.text-center 5.533
                  td.text-center 1.660.000

                tr.bg-color-7
                  td.text-center 3
                  td D.Com.2
                  td.text-center -
                  td.text-center -
                  td.text-center 10
                  td.text-center 60.000
                  td.text-center 290
                  td.text-center 5.517
                  td.text-center 1.600.000

                tr.bg-color-white
                  td.text-center 4
                  td Venta
                  td.text-center -
                  td.text-center -
                  td.text-center 190
                  td.text-center 1.048.276
                  td.text-center 100
                  td.text-center 5.517
                  td.text-center 551.724

                tr.bg-color-7
                  td.text-center 5
                  td D.Ven.4
                  td.text-center 10
                  td.text-center 55.172
                  td.text-center -
                  td.text-center -
                  td.text-center 110
                  td.text-center 5.517
                  td.text-center 606.897

                tr.bg-color-white
                  td.text-center 6
                  td Compra
                  td.text-center 90
                  td.text-center 585.000
                  td.text-center -
                  td.text-center -
                  td.text-center 200
                  td.text-center 5.959
                  td.text-center 1.191.897

                tr.bg-color-7
                  td.text-center 7
                  td Venta
                  td.text-center -
                  td.text-center -
                  td.text-center 100
                  td.text-center 595.948
                  td.text-center 100
                  td.text-center 5.959
                  td.text-center 595.948

        p.mb-5 Contablemente quedará así:

        .row.justify-content-center
          .col-lg-10

            #tablas9y10
            .row.mb-5
              .col-lg-6
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 9.
                  span Cuenta 1435 - Inventario de mercancías (PEPS)
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 0
                        td.text-center 400.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 1
                        td.text-center 660.000
                        td.text-center -
                      tr.bg-color-white
                        td.text-center 2
                        td.text-center 600.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 5
                        td.text-center 55.000
                        td.text-center -
                      tr.bg-color-white
                        td.text-center 6
                        td.text-center 585.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 3
                        td.text-center -
                        td.text-center 60.000
                      tr.bg-color-white
                        td.text-center 4
                        td.text-center -
                        td.text-center 1.005.000
                      tr.bg-color-7
                        td.text-center 7
                        td.text-center -
                        td.text-center 590.000
                      tr.bg-color-white
                        td.text-center #[strong Totales]
                        td.text-center #[strong 2.300.000]
                        td.text-center #[strong 1.655.000]
                      tr.bg-color-7
                        td.text-center #[strong Saldo final]
                        td.text-center -
                        td.text-center #[strong 645.000]

              .col-lg-6
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 10.
                  span Cuenta 11 - Efectivo
                .tabla-a.color-acento-contenido.mb-3
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 3
                        td.text-center 60.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 4
                        td.text-center 2.850.000
                        td.text-center -
                      tr.bg-color-white
                        td.text-center 7
                        td.text-center 1.500.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 1
                        td.text-center -
                        td.text-center 660.000
                      tr.bg-color-white
                        td.text-center 2
                        td.text-center -
                        td.text-center 600.000
                      tr.bg-color-7
                        td.text-center 5
                        td.text-center -
                        td.text-center 150.000
                      tr.bg-color-white
                        td.text-center 6
                        td.text-center -
                        td.text-center 585.000
                      tr.bg-color-7
                        td.text-center #[strong Totales]
                        td.text-center #[strong 4.410.000]
                        td.text-center #[strong 1.995.000]
                      tr.bg-color-white
                        td.text-center #[strong Saldo final]
                        td.text-center -
                        td.text-center #[strong 2.415.000]


            #tablas11-12-13
            .row
              .col-xl-4
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 11.
                  span Cuenta 4135 - Ventas
                .tabla-a.color-acento-contenido.mb-3.mb-xl-0
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 4
                        td.text-center 2.850.000
                      tr.bg-color-7
                        td.text-center 7
                        td.text-center 1.500.000
                      tr.bg-color-white
                        td.text-center #[strong Totales]
                        td.text-center #[strong 4.350.000]

              .col-xl-4
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 12.
                  span Cuenta 4175 - Devoluciones en ventas
                .tabla-a.color-acento-contenido.mb-3.mb-xl-0
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                    tbody
                      tr.bg-color-white
                        td.text-center 5
                        td.text-center 150.000
                      tr.bg-color-7
                        td.text-center #[strong Totales]
                        td.text-center #[strong 150.000]

              .col-xl-4
                .titulo-sexto.color-acento-contenido
                  h5 Tabla 13.
                  span Cuenta (posiblemente 6135) - Costo de ventas
                .tabla-a.color-acento-contenido.mb-3.mb-xl-0
                  table
                    thead
                      tr
                        th.bg-color-acento-contenido.text-center Fecha
                        th.bg-color-acento-contenido.text-center Débito
                        th.bg-color-acento-contenido.text-center Crédito
                    tbody
                      tr.bg-color-white
                        td.text-center 4
                        td.text-center 1.005.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center 5
                        td.text-center -
                        td.text-center 55.000
                      tr.bg-color-white
                        td.text-center 7
                        td.text-center 590.000
                        td.text-center -
                      tr.bg-color-7
                        td.text-center #[strong Totales]
                        td.text-center #[strong 1.595.000]
                        td.text-center #[strong 55.000]
                      tr.bg-color-white
                        td.text-center #[strong Saldo final]
                        td.text-center -
                        td.text-center #[strong 1.540.000]

    Separador

    #t_1_3.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 1.3 Medición, reconocimiento con impuestos y retenciones

    p.mb-4 La medición de los inventarios consiste en determinar el valor por el cual serán reconocidos en los estados financieros. La NIC 2, hace referencia de las técnicas para la medición inicial y posterior del costo de los inventarios, tales como el método del costo estándar o el método de los minoristas, los cuales podrán ser utilizadas por conveniencia siempre que el resultado de aplicarlas se aproxime al costo.

    .row.justify-content-center
      .col-lg-9
        .row.align-items-center.mb-4
          .col-lg-auto.d-none.d-lg-block
            img(src="@/assets/curso/tema1/12.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Los costos estándares tendrán en cuenta los niveles normales de materias primas, suministros, mano de obra, eficiencia y utilización de la capacidad. Estos se revisarán de forma regular y, si es necesario, se cambiarán en función de las condiciones actuales.


        .bg-color-4.mb-5(data-aos="fade-up")
          .row.justify-content-center.align-items-center
            .col-xxl-auto.d-xl-none.d-xxl-block.col-12
              figure
                img(src='@/assets/curso/tema1/14.png', alt='')
            .col-xxl.col-12
              .p-4
                p.mb-0(data-aos="fade-up") El método de los minoristas se utiliza a menudo, en el sector comercial al por menor para la medición de inventarios cuando hay un gran número de artículos que rotan velozmente, que tienen márgenes similares y para los cuales resulta impracticable usar otros métodos de cálculo de costos. Cuando se emplea este método, el costo de los inventarios se determinará deduciendo, del precio de venta del artículo en cuestión, un porcentaje apropiado de margen bruto. El porcentaje aplicado tendrá en cuenta la parte de los inventarios que se han marcado por debajo de su precio de venta original. A menudo se utiliza un porcentaje promedio para cada sección o departamento comercial.
        


      .col-lg-3.d-none.d-xl-block
        figure
          img(src="@/assets/curso/tema1/13.png", alt='', style="max-width: 305px").mx-auto.mb-4


    p.mb-5 De acuerdo con la sección 13 de NIIF para Pymes (2009), una entidad medirá los inventarios al importe menor entre el costo y el precio de venta estimado menos los costos de terminación y venta. Una entidad incluirá en el costo de los inventarios todos los costos de compra, costos de transformación y otros costos incurridos para darles su condición y ubicación actuales. Se puede usar dos o más columnas para diagramar el texto, estos elementos pueden presentar contenedores que permitan diferenciar ideas o conceptos.

    .row.justify-content-center.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema1/15.png", alt='', style="max-width: 502px").mx-auto.mb-4

      .col-lg-7

        .row.align-items-center.mb-4
          .col-lg-auto.d-none.d-lg-block
            img(src="@/assets/curso/tema1/16.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 De acuerdo con la sección 13 de NIIF para Pymes (2009), cuando los inventarios se vendan, la entidad reconocerá el importe en libros de estos como un costo (gasto) en el período en el que se reconozcan los correspondientes ingresos de actividades ordinarias.

        p.mb-4 En el proceso de compra se debe reconocer el impuesto a las ventas descontable y practicar las correspondientes retenciones sobre los impuestos a la renta, a industria y comercio e incluso a las ventas; dependiendo de las obligaciones tributarias y características fiscales del comprador y el proveedor.

        .bg-color-2.p-4
          p.mb-0 Por otro lado, en el proceso de ventas se debe reconocer el impuesto a las ventas generado, al igual que los correspondientes anticipos por retenciones de los impuestos a la renta, de industria y comercio e incluso a las ventas; dependiendo de las obligaciones tributarias y características fiscales del vendedor y el cliente.


    p.mb-5 A continuación, se muestra un ejercicio de reconocimiento de las operaciones de compra y venta de inventarios incluido los impuestos y las retenciones.

    LineaTiempoD.color-secundario
      div(numero="1" titulo="Gira anticipo a proveedores por $ 5.000.000") 
        .row.justify-content-center
          .col-lg-10
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 14.
              span Registro contable del giro de anticipo a proveedores por $5.000.000
            .tabla-a.color-acento-contenido.mb-3
              table
                thead
                  tr
                    th.bg-color-acento-contenido.text-center Ele
                    th.bg-color-acento-contenido.text-center Cuenta
                    th.bg-color-acento-contenido.text-center Debe
                    th.bg-color-acento-contenido.text-center Haber
                tbody
                  tr.bg-color-white
                    td.text-center AC
                    td Anticipo a proveedores
                    td.text-center 5.000.000
                    td.text-center -
                  tr.bg-color-7
                    td.text-center AC
                    td Efectivo y equivalentes al efectivo
                    td.text-center -
                    td.text-center 5.000.000

      div(numero="2" titulo="Compra inventarios") 
        p Compra inventarios para la venta por $19.500.000 más IVA 19%, menos retefuente 2,5% y reteica 0,4%. Legaliza el anticipo y el. saldo a crédito.
        .row.justify-content-center
          .col-lg-10
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 15.
              span Registro contable de la legalización del anticipo y saldo a crédito con sus respectivas retenciones
            .tabla-a.color-acento-contenido.mb-3
              table
                thead
                  tr
                    th.bg-color-acento-contenido.text-center Ele
                    th.bg-color-acento-contenido.text-center Cuenta
                    th.bg-color-acento-contenido.text-center Debe
                    th.bg-color-acento-contenido.text-center Haber
                tbody
                  tr.bg-color-white
                    td.text-center AC
                    td Inv. Mercancías
                    td.text-center 19.500.000
                    td.text-center -
                  tr.bg-color-7
                    td.text-center PS
                    td IVA Descontable
                    td.text-center 3.705.000
                    td.text-center -
                  tr.bg-color-white
                    td.text-center PS
                    td Retefuente 2,5%
                    td.text-center -
                    td.text-center 487.500
                  tr.bg-color-7
                    td.text-center PS
                    td Reteica 0,4%
                    td.text-center -
                    td.text-center 78.000
                  tr.bg-color-white
                    td.text-center AC
                    td Anticipo a proveedores
                    td.text-center -
                    td.text-center 5.000.000
                  tr.bg-color-7
                    td.text-center PS
                    td Proveedores
                    td.text-center -
                    td.text-center 17.639.500

      div(numero="3" titulo="Devolución inventarios") 
        p Devuelve a su proveedor inventarios por $ 1.500.000 incluido IVA 19 %
        .row.justify-content-center
          .col-lg-10

            #Tabla16
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 16.
              span Registro contable por compra de inventario con retenciones y saldo a crédito
            .tabla-a.color-acento-contenido.mb-3
              table
                thead
                  tr
                    th.bg-color-acento-contenido.text-center Ele
                    th.bg-color-acento-contenido.text-center Cuenta
                    th.bg-color-acento-contenido.text-center Debe
                    th.bg-color-acento-contenido.text-center Haber
                tbody
                  tr.bg-color-white
                    td.text-center AC
                    td Inventarios para la venta
                    td.text-center -
                    td.text-center 1.260.504
                  tr.bg-color-7
                    td.text-center PS
                    td IVA Descontable
                    td.text-center -
                    td.text-center 239.496
                  tr.bg-color-white
                    td.text-center PS
                    td Retefuente 2,5%
                    td.text-center 31.513
                    td.text-center -
                  tr.bg-color-7
                    td.text-center PS
                    td Reteica 0,4%
                    td.text-center 5.042
                    td.text-center -
                  tr.bg-color-white
                    td.text-center PS
                    td Cuentas por Pagar – Proveedores
                    td.text-center 1.463.445
                    td.text-center -

      div(numero="4" titulo="Venta de inventarios") 
        p Vende inventarios por un precio de $ 11.500.000 incluido IVA 19 %, menos: retefuente 2,5 %, reteiva 15 % y reteica 0,4 %. Le pagan el 40 % y el saldo a crédito (65 % Gasto de Venta)
        .row.justify-content-center
          .col-lg-10

            #Tabla17
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 17.
              span Registro contable de la venta de inventarios, anticipos de retención y reconocimiento del costo de venta
            .tabla-a.color-acento-contenido.mb-3
              table
                thead
                  tr
                    th.bg-color-acento-contenido.text-center Ele
                    th.bg-color-acento-contenido.text-center Cuenta
                    th.bg-color-acento-contenido.text-center Debe
                    th.bg-color-acento-contenido.text-center Haber
                tbody
                  tr.bg-color-white
                    td.text-center IN
                    td Venta de inventarios
                    td.text-center -
                    td.text-center 9.663.866
                  tr.bg-color-7
                    td.text-center PS
                    td IVA Generado
                    td.text-center -
                    td.text-center 1.836.134
                  tr.bg-color-white
                    td.text-center AC
                    td Anticipo Retefuente 2,5%
                    td.text-center 241.597
                    td.text-center -
                  tr.bg-color-7
                    td.text-center AC
                    td Anticipo Reteiva 15%
                    td.text-center 275.420
                    td.text-center -
                  tr.bg-color-white
                    td.text-center AC
                    td Anticipo Reteica 0,4%
                    td.text-center 38.655
                    td.text-center -
                  tr.bg-color-7
                    td.text-center AC
                    td Cuentas por cobrar Clientes
                    td.text-center 10.944.328
                    td.text-center -
                  tr.bg-color-white
                    td.text-center AC
                    td Cuentas por cobrar Clientes
                    td.text-center -
                    td.text-center 4.377.731
                  tr.bg-color-7
                    td.text-center AC
                    td Efectivo y equivalentes al efectivo
                    td.text-center 4.377.731
                    td.text-center -
                  tr.bg-color-white.text-red
                    td.text-center GA
                    td Gasto de venta
                    td.text-center 6.281.513
                    td.text-center -
                  tr.bg-color-7.text-red
                    td.text-center AC
                    td Inventarios para la venta
                    td.text-center -
                    td.text-center 6.281.513


      div(numero="5" titulo="Devolución de mercancía") 
        p El cliente le devuelve mercancías por $850.000 más IVA 19%, (65% Gasto  Devolución en Venta)
        .row.justify-content-center
          .col-lg-10

            #Tabla18
            .titulo-sexto.color-acento-contenido.mb-3
              h5 Tabla 18.
              span Registro contable por devolución en ventas con retenciones y reversión del costo de venta
            .tabla-a.color-acento-contenido.mb-3
              table
                thead
                  tr
                    th.bg-color-acento-contenido.text-center Ele
                    th.bg-color-acento-contenido.text-center Cuenta
                    th.bg-color-acento-contenido.text-center Debe
                    th.bg-color-acento-contenido.text-center Haber
                tbody
                  tr.bg-color-white
                    td.text-center IN
                    td Devoluciones en venta
                    td.text-center 850.000
                    td.text-center -
                  tr.bg-color-7
                    td.text-center PS
                    td IVA Generado
                    td.text-center 161.500
                    td.text-center .
                  tr.bg-color-white
                    td.text-center AC
                    td Anticipo Retefuente 2,5%
                    td.text-center -
                    td.text-center 21.250
                  tr.bg-color-7
                    td.text-center AC
                    td Anticipo Reteiva 15%
                    td.text-center -
                    td.text-center 24.225
                  tr.bg-color-white
                    td.text-center AC
                    td Anticipo Reteica 0,4%
                    td.text-center -
                    td.text-center 3.400
                  tr.bg-color-7
                    td.text-center AC
                    td Cuentas por cobrar Clientes
                    td.text-center -
                    td.text-center 962.625
                  tr.bg-color-white
                    td.text-center GA
                    td Gasto de venta
                    td.text-center -
                    td.text-center 552.500
                  tr.bg-color-7.text-red
                    td.text-center AC
                    td Inventarios para la venta
                    td.text-center 552.500
                    td.text-center -


    Separador

    #t_1_4.titulo-segundo.color-acento-contenido.mb-5(data-aos="flip-up")
      h2 1.4 Presentación y revelación

    p.mb-5 La presentación de los inventarios hace referencia a cómo se reflejan en los estados financieros.

    .row.mb-5.justify-content-center.mb-4
      .col-lg-11
        .bg-color-2
          .row.align-items-center
            .col-lg-4.d-none.d-lg-block
              figure
                img(src="@/assets/curso/tema1/17.svg").mx-auto.my-4.my-lg-0
            .col-lg-8
              .p-4
                p.mb-4 De acuerdo con la sección 13 de NIIF para Pymes 8 (2009), una entidad revelará la siguiente información:

                .bg-color-white.p-2.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 Las políticas contables adoptadas para la medición de los inventarios, incluyendo la fórmula del costo utilizado.
                .bg-color-white.p-2.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 El importe total en libros de los inventarios, y los importes parciales según la clasificación apropiada para la entidad.
                .bg-color-white.p-2.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 El importe de los inventarios reconocidos como gasto durante el período.
                .bg-color-white.p-2.mb-2
                  ul.lista-ul--color.mb-0
                    li.d-flex.mb-0
                      i.fas.fa-chevron-right
                      p.mb-0 Las pérdidas por deterioro del valor reconocidas o revertidas en el resultado de acuerdo con la sección 27 de NIIF para Pymes “Deterioro del Valor de los Activos”(2009).

    p El importe total en libros de los inventarios pignorados en garantía de pasivos.

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
