<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Registro de compras y ventas en la gestión contable',
      titulo: 'Cuestionario',
      introduccion:
        'Identificar los conceptos clave relacionados con la política contable, medición, reconocimiento, presentación y revelación de las operaciones comerciales de compras y ventas.',
      barajarPreguntas: true,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto:
            '¿Cuál es el objetivo principal del componente formativo "Registro de Compras y Ventas"?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Aplicar estrategias de mercadeo en las ventas.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Afianzar el conocimiento en el registro contable de operaciones de compra y venta.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto:
                'Analizar el flujo de efectivo en las operaciones comerciales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Interpretar estados financieros consolidados.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 2,
          texto:
            '¿Qué establece la NIC 2 con respecto al valor neto realizable?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Es el valor contable ajustado por inflación.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Es el precio de compra más gastos de comercialización.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Es el precio estimado de venta menos los costos de terminación y venta.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Es el valor fiscal determinado por la DIAN.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 3,
          texto:
            '¿Cuál es una característica del sistema de inventarios periódico?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Permite conocer los costos en cualquier momento.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Solo se determina el costo de venta al final del ejercicio.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Utiliza métodos de valuación como PEPS y Promedio.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Incluye el control de costos y unidades en el kardex.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 4,
          texto:
            '¿Qué incluye el costo de adquisición de inventarios según la NIC 2?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Solo el precio de compra.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Precio de compra, aranceles, transporte y manejo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Descuentos por pronto pago y costos indirectos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Únicamente el valor neto de la factura.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 5,
          texto: '¿Qué ocurre cuando se devuelven inventarios a un proveedor?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Se genera un ingreso operativo.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Se reduce el valor del inventario y del IVA descontable.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Se incrementan las cuentas por pagar.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Se afecta el gasto por ventas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 6,
          texto:
            'Según la NIIF para Pymes, ¿cuándo se reconoce el ingreso por ventas?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Cuando se recibe el pago.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Cuando se firma el contrato.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto:
                'Cuando se transfieren los riesgos y beneficios al cliente.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Cuando se factura la operación.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 7,
          texto:
            '¿Qué representan las cuentas por pagar en el contexto de instrumentos financieros?',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Pasivos generados por compras a crédito.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Ganancias acumuladas de ejercicios anteriores.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Gastos por amortización de activos.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Activos financieros disponibles para la venta.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 8,
          texto: '¿Qué se entiende por deterioro de cartera?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Reconocimiento anticipado de la pérdida en cuentas por cobrar.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Aumento del valor contable de los activos.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Valor del impuesto de renta generado por ventas.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Reestructuración del pasivo a largo plazo.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 9,
          texto:
            '¿Qué base de contabilización se usa para reconocer gastos según la NIIF para Pymes?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Base de caja.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Base de devengo.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Valor razonable actualizado.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Costo histórico corregido.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 10,
          texto:
            '¿Cuál es uno de los elementos que debe revelar una entidad respecto a los inventarios?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'La antigüedad de las cuentas por pagar.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'La fórmula del costo utilizada para su medición.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'El valor de mercado proyectado a futuro.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'El precio de venta final del producto.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 11,
          texto:
            'El sistema de inventarios permanente permite conocer el costo de venta en cualquier momento.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 12,
          texto:
            'La NIIF 15 regula el tratamiento contable de los instrumentos financieros.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 13,
          texto:
            'En el método PEPS se venden primero las unidades más antiguas.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 14,
          texto: 'El gasto de venta debe reconocerse como ingreso diferido.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
        {
          id: 15,
          texto:
            'Las políticas contables deben aplicarse de forma uniforme a transacciones similares.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Falso.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Verdadero.',
              esCorrecta: true,
            },
          ],
          mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
          mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
        },
      ],
      mensaje_final_aprobado: '¡Excelente! Ha superado la actividad.',
      mensaje_final_reprobado:
        'Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
