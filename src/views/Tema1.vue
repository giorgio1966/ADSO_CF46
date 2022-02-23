<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    //- Muestras
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1  Documentación de procesos de implantación
    .row.mt-5.mb-5.bgAcentoBotones
      .col-5
          img(src='@/assets/curso/tema1/imagen1.jpg')
      .col-7.mt-4
        .row
          .col-12.bgBlanco.Neg-Der50.p-2
            .cajon.mb-4
              span.mb-0.text-small La documentación en el proceso de implementación es fundamental, porque permite realizar modificaciones necesarias al proyecto sin grandes complicaciones, debido a que en estos documentos se registra todo lo que ocurre en este proceso desde las especificaciones hasta las actas de entrega, además de ser un instrumento para comunicar los detalles no tan obvios del sistema. La documentación es el registro de todos los pasos necesarios para completar un proceso, en esta parte es muy importante el "cómo" se realizan; el desarrollo de software es esencialmente un grupo de procesos interrelacionados, por lo cual es importante llevar una correcta documentación de los procesos en los formatos establecidos.
    .titulo-segundo.color-acento-botones
      #manTec.h2 1.1 Manuales Técnicos
    .bloque-texto-b.color-acento-botones.p-2
      .bloque-texto-b__texto
        i.fas.fa-quote-left.text-primario
        h2.mb-0 Según el Ministerio TIC (2018), en este documento está plasmada toda la información del proyecto de software, con una descripción bien detallada sobre las características técnicas y físicas de cada elemento; este manual va dirigido al administrador del sistema y otros ingenieros para que puedan hacer un respectivo mantenimiento en caso de que sea necesario; estos deben contener como mínimo los elementos relacionados a continuación:
        i.fas.fa-quote-right.text-primario

    LineaTiempoD.color-primario.mt-5
      .row(numero="1" titulo="Nombre del sistema")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Nombre completo del sistema de información.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/nombreSis.svg', alt='Nombre del sistema')

      .row(numero="2" titulo="Sigla")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Sigla o nombre corto bajo el cual se conoce el sistema de información. Si aplica

        .col-md-2
          figure
            img(src='@/assets/template/tema1/siglas.svg', alt='Siglas')
      
      .row(numero="3" titulo="Descripción del sistema")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Descripción funcional del sistema y los servicios que presta.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/descripSis.svg', alt='Descripción del sistema')

      .row(numero="4" titulo="Versión")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Versión actual y en producción del sistema de información.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/version.svg', alt='Versión')

      .row(numero="5" titulo="Categoria")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Indique la categoría del sistema, de acuerdo con la clasificación del Marco de Referencia de Arquitectura Empresarial para la Gestión de TI en el Estado: • Sistema misional • Sistema de apoyo. • Portales digitales. • Sistema de direccionamiento estratégico

        .col-md-2
          figure
            img(src='@/assets/template/tema1/categoria.svg', alt='Categoria')

      .row(numero="6" titulo="Fabricante")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Compañía que construyó el sistema de información o nombre del desarrollado.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/fabricante.svg', alt='Fabricante')

      .row(numero="7" titulo="Fecha de vencimiento del soporte")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Indique la fecha hasta la cual se tiene el contrato de mantenimiento o soporte 
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/fechaVen.svg', alt='Fecha de vencimiento')

      .row(numero="8" titulo="Sistema operativo")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Sistema(s) operativos(o) sobre los cuales funciona actualmente el sistema de información.

        .col-md-2
          figure
            img(src='@/assets/template/tema1/sisOper.svg', alt='Sistema operativo')
      
      .row(numero="9" titulo="Lenguaje de programación")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Lenguajes de programación y frameworks sobre los cuales fue construido el sistema de información. Ejemplos: Java 7, C#.Net framework 4.5, php 5.3, etc.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/lenguaje.svg', alt='Lenguaje de programación')

      .row(numero="10" titulo="Plataforma de base de datos")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Ejemplo: Oracle, SQL server, Postgres, MySQL, entre otros.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/basedatos.svg', alt='Base de datos')

      .row(numero="11" titulo="Documentación técnica y funcional")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Indique la ubicación (URL) de la documentación detallada técnica y funcional del sistema (Arquitectura, manuales, diseños, etc..)
 
        .col-md-2
          figure
            img(src='@/assets/template/tema1/docum.svg', alt='Documentación técnica y funcional')
     
      .row(numero="12" titulo="Arquitectura tecnológica")
        .col-md-7.mb-4.mb-md-0
          p.ms-5 Stand Alone, web, cliente servidor, app móvil, software as a service (nube), etc.w.
      
        .col-md-2
          figure
            img(src='@/assets/template/tema1/arquitectura.svg', alt='Arquitectura tecnológica')

    .titulo-segundo.color-acento-botones.mb-4
      #manUser.h2 1.2 Manuales de usuario
    
    .row.mt-5.mb-5
      .col-5
        img(src='@/assets/curso/tema1/imagen1.jpg')
      .col-7
        .row.mb-2.bgPrimario
          .col-12
            p.mb-0.text-small El manual de usuario es el documento que facilita a las personas utilizar un software de manera sencilla y clara, además de brindar acceso a todas las funcionalidades que este posee. La documentación técnica es muy importante en el ciclo de vida de los sistemas de información, además de ser un entregable obligatorio de parte de los programadores. 
        .row.mb-2.bgAcentoBotones
          .col-12
            .row
             .col-1
               i.fas.fa-quote-left.Text-grande.text-primario
            .row
              .col-1
              .col-10
                p.ms-5 - Según Mintic (2018)
                p.mt-2.mb-2.ms-5 Los sistemas de información deben contar con la documentación de usuario, técnica y de operación actualizada, que facilite la transferencia de conocimiento a los usuarios y a los servicios de soporte tecnológico. 
            .row
              .col-11
              .col-1
                p.i.fas.fa-quote-right.Text-grande.text-primario
        .row
          .col-12
            p Un manual de usuario se debe adecuar a la empresa que solicita el producto, los usuarios lo leen para encontrar consejos prácticos sobre cómo utilizar la solución de software o superar un problema cuando estos ocurren.
    p.mb-4  Para realizar un manual de usuario hay que tener en cuenta algunos consejos:

  SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
    .tarjeta.bgBlanco.p-4
      .row.justify-content-center.mb-3
        .col-8
          img(src='@/assets/componentes/tema1/pc.svg' alt='AvatarTop')
      p.text-center Crear el manual de usuario, se deben escribir las instrucciones de forma clara y sencilla evitando palabras muy técnicas, mostrando todo lo que el usuario necesita saber, el diseño debe ser amigable y debe tener ayudas visuales.

    .tarjeta.bgBlanco.p-4
      .row.justify-content-center.mb-3
        .col-8
          img(src='@/assets/componentes/tema1/libro.svg' alt='AvatarTop')
      p.text-center Probar el manual, con personas que no conozcan el producto, con estas pruebas se puede enriquecer el manual, entrevistar a todos los desarrolladores, ellos conocen el producto mejor que nadie y pueden señalar las cosas que puede haber pasado por alto.

    .tarjeta.bgBlanco.p-4
      .row.justify-content-center.mb-3
        .col-8
          img(src='@/assets/componentes/tema1/hojas.svg' alt='AvatarTop')
      p.text-center Mantener la documentación actualizada: Cuando hagan modificaciones en el producto, es necesario tener todo actualizado;  la documentación electrónica tiene una gran ventaja sobre la impresa,  incluso los documentos impresión pueden actualizarse para descargarlos   del sitio web de la empresa. 

    .tarjeta.bgBlanco.p-4
      .row.justify-content-center.mb-3
        .col-8
          img(src='@/assets/componentes/tema1/tabla.svg' alt='AvatarTop')
      p.text-center Planificar la información que se desea incluir, enfocarse en que se está ayudando al usuario de manera objetiva, también se debe tener en cuenta que otros recursos se pone a disposición del usuario y quienes son los responsables de elaborar el documento y de su aprobación.

    .tarjeta.bgBlanco.p-4
      .row.justify-content-center.mb-3
        .col-8
          img(src='@/assets/componentes/tema1/hojas2.svg' alt='AvatarTop')
      p.text-center Seleccionar el formato para crear el manual puede ser, .doc, .txt  ,html, .pdf, .csv, .xls etc;  por lo general la mayoría de manuales se imprimen pero es recomendable tener una versión electrónica en el sitio web, si no lo tiene, debe pensar en donde puede alojar esta información ya que en la actualidad la gran mayoría de personas acceden a la información desde su dispositivo móvil o Smart Phone. 

    .tarjeta.bgBlanco.p-4
      .row.justify-content-center.mb-3
        .col-8
          img(src='@/assets/componentes/tema1/pc2.svg' alt='AvatarTop')
      p.text-center Tener en cuenta a los lectores, el tipo de población a la cual está dirigida la solución informática. 


</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
