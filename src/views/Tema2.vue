<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Capacitación de usuarios
    
    .row.bgFondoUnosyCerosAzul.mt-4.justify-content-center.p-5
      .col-md-10
        img(src='@/assets/curso/tema2/reunionVirtual.jpg')
        p.mt-5.mb-4 La tecnología cambia a pasos agigantados, esto se puede ver reflejado en la creación y nuevas versiones de   programas, por lo cual la clave es saber cómo capacitar a los empleados sobre los nuevos sistemas o tecnología que se implementan, y hay que hacerlo de manera efectiva y eficaz para lograr una correcta transferencia del conocimiento.

    .titulo-segundo.color-acento-botones.mb-4
      #t_2_1_Tec.h2 2.1 Técnicas
      
    SlyderA
      .row.bgFondoPantalla.p-5.m-5
        .col-md-12.mb-4.mb-md-0.p-5
          h3.mt-4.mb-4.ms-4 Los instructores deben conocer muy bien el software
          .row
            .col-md-6.p-2
              p.p-2.ms-4 Los formadores deben ser expertos en el manejo del programa, esto transmite confianza y entusiasmo a los usuarios de la capacitación.
              p.ms-2.mb-2.me-2.ms-4 Al diseñar la capacitación debe contar con personal profesional en la materia, los cuales tengan facilidad de expresión y buen manejo del público.   
            .col-md-6.p-2
              figure
                img(src='@/assets/template/tema2/reunion.jpg', alt='Los instructores deben conocer muy bien el software')
      .row.bgFondoPantalla.p-5.m-5
        .col-md-12.mb-4.mb-md-0.p-5
          h3.mt-4.mb-4.ms-4 Los instructores deben conocer muy bien el software
          .row
            .col-md-6.p-2
              p.p-2.ms-4 Si la capacitación es de manera virtual o con video tutoriales asegurase de contratar personas expertas en la creación de estos recursos ya que la presentación y la calidad es muy importante. 
            .col-md-6.p-2
              figure
                img(src='@/assets/template/tema2/PC.jpg', alt='Los instructores deben conocer muy bien el software')

      .row.bgFondoPantalla.p-5.m-5
        .col-md-12.mb-4.mb-md-0.p-5
          h3.mt-4.mb-4.ms-4 Hacer de la formación una prioridad
          .row
            .col-md-6.p-2
              p.p-2.ms-4 Hay que establecer acuerdos con los jefes de personal o con los propietarios de las empresas para establecer la capacitación de manera obligatoria, esto evita problemas inconvenientes a futuro como volver a agendar capacitaciones y problemas por incorrecto manejo de software o aplicación.
            .col-md-6.p-2
              figure
                img(src='@/assets/template/tema2/manosPC.jpg', alt='Hacer de la formación una prioridad')

      .row.bgFondoPantalla.p-5.m-5
        .col-md-12.mb-4.mb-md-0.p-5
          h3.mt-4.mb-4.ms-4 Utilizar incentivos en la capacitación
          .row
            .col-md-6.p-2
              p.p-2.ms-4 Los incentivos motivan y comprometen a los participantes creando un ambiente cálido en el proceso de capacitación, la clave es conocer bien a los empleados por intermedio de los jefes, para algunos vasta con un reconocimiento verbal por su dedicación, para otros puede ser un buen refrigerio o golosinas, también se puede hablar con los dueños de la empresa para que los usuarios puedan ser recompensados con hora libres.
            .col-md-6.p-2
              figure
                img(src='@/assets/template/tema2/estudiantes.jpg', alt='Utilizar incentivos en la capacitación')

      .row.bgFondoPantalla.p-5.m-5
        .col-md-12.mb-4.mb-md-0.p-5
          h3.mt-4.mb-4.ms-4 Elegir un formato adecuado para la capacitación
          .row
            .col-md-6.p-2
              p.p-2.ms-4 En la mayoría de casos las capacitaciones o conferencias son de manera magistral y de poco tiempo, lo cual no es efectivo para ayudar a los usuarios a desarrollar sus nuevas habilidades y que los aplique con eficacia, hay que ser creativos, didácticos y utilizar pausas activas para evitar el desgaste de los usuarios, buscando la aplicabilidad del aprendizaje. 
            .col-md-6.p-2
              figure
                img(src='@/assets/template/tema2/presentacion.jpg', alt='Elegir un formato adecuado para la capacitación')



</template>

<script>
export default {
  name: 'Tema2',
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
