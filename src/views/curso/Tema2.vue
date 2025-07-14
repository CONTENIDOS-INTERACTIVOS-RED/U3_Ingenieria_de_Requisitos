<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'2. Revisión con el cliente'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
  
      .bg-color-13.mb-5(data-aos="fade-up")
        .row.justify-content-center.align-items-center
          .col-lg-auto.mb-3.mb-lg-0
            figure
              img(src='@/assets/curso/tema6/1.png', alt='')
          .col-lg
            .p-4
              p.mb-0(data-aos="fade-up") La revisión con el cliente es una práctica clave en la validación de requisitos, debido a que permite confirmar que las expectativas del usuario han sido correctamente interpretadas y documentadas. A través de este proceso, el cliente participa activamente en el análisis de los requisitos, aportando observaciones y sugerencias que ayudan a detectar ambigüedades, inconsistencias o carencias antes de avanzar a etapas más costosas del desarrollo.
      
      p.mb-5 Esta interacción fortalece la comunicación entre las partes, reduce el riesgo de errores y asegura que el producto final responda fielmente, a las necesidades reales del usuario.
  
      #t_2_1.titulo-segundo(data-aos="flip-up")
        h2 #[span 2.1] Importancia de la revisión con el cliente
      
      p.mb-5 La revisión con el cliente no debe verse como una simple instancia de retroalimentación, sino como un mecanismo estratégico que garantiza que el sistema refleje la visión, prioridades y necesidades del usuario final. Dado que el cliente posee el conocimiento más profundo del dominio del problema, su participación activa permite:
  
      .bg-full-width.bg-color-10.mb-5
        .px-4.px-md-5
          .row.justify-content-center.align-items-center
            .col-lg-12
              .row.justify-content-center.align-items-center
                .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                  ul.lista-ul--color
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Detectar desviaciones entre lo que se ha documentado y lo que realmente se espera.
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Mejorar la exactitud y relevancia funcional de los requisitos.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Identificar errores de interpretación o ambigüedades en fases tempranas.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Priorizar funcionalidades, según el valor de negocio.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Evitar retrabajos costosos en fases avanzadas.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Fomentar la transparencia y la confianza mutua en el equipo de trabajo.
                .col-lg-5(data-aos="zoom-in")
                  img.img-fluid(src='@/assets/curso/tema6/2.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
      
      p.mb-5 Este proceso transforma al cliente en un colaborador activo, incrementando su compromiso y satisfacción con el resultado final. Los ejemplos concretos son: 
  
      .bg-full-width.bg-color-12
        .p-4.p-md-5
          div.row.justify-content-center.align-items-stretch.mb-5
            div.col-lg-4.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/3.svg" alt="" style="width: 90px")
                h5.text-center Clínica odontológica
                p.mb-0.text-center Se detecta la ausencia de la función de reagendamiento de citas. Se incluye a tiempo, mejorando la gestión de pacientes.
          
            div.col-lg-4.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/4.svg" alt="" style="width: 90px")
                h5.text-center Tienda en línea
                p.mb-0.text-center El cliente solicita incluir compra como invitado para facilitar conversiones.
          
            div.col-lg-4.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(src="@/assets/curso/tema6/5.svg" alt="" style="width: 90px")
                h5.text-center Aplicación educativa
                p.mb-0.text-center Se observa la necesidad de acceso diferenciado entre docentes y estudiantes, clave para la gestión de contenidos.
  
      #t_2_2.titulo-segundo(data-aos="flip-up")
        h2 #[span 2.2] Tipos de revisión con el cliente
      
      .row.mb-5
        .col-lg-5.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema6/6.png", data-aos="zoom-in")
        .col-lg-7
          .bg-color-3.text-white.p-4.h-100(data-aos="fade-left")
            p.mb-0 La revisión con el cliente puede llevarse a cabo mediante diversas modalidades, adaptadas al contexto del proyecto, al grado de avance del desarrollo y al tipo de producto. Cada tipo tiene como objetivo asegurar que los requisitos definidos representan fielmente las expectativas del cliente y se alinean con las necesidades del negocio. La diversidad de enfoques permite combinar métodos informales y flexibles con otros más estructurados y rigurosos, garantizando así una validación completa y contextualizada.
      
      .row.align-items-start.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema6/7.png", alt="").mb-4.mb-lg-0
        .col-lg-8.order-lg-1
      
          AcordionA(tipo="b")
            .div(titulo="Revisión informal o conversacional")
              p Se realiza mediante reuniones breves, llamadas o correos no estructurados, ideales en etapas iniciales para aclarar aspectos generales. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: en una videollamada, el cliente comenta que la interfaz está sobrecargada visualmente, lo que lleva a ajustes importantes de diseño.
      
            .div(titulo="Revisión estructurada o formal")
              p Sigue una agenda definida, con documentación previa y criterios de validación claros. Se registra en actas y se realiza en etapas clave. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: durante la revisión formal del documento de requisitos, el cliente aprueba o rechaza funcionalidades mediante un formulario de control de cambios.
      
            .div(titulo="Revisión técnica con el cliente")
              p Incluye discusiones sobre aspectos funcionales y tecnológicos, y requiere conocimientos técnicos del cliente o validación de restricciones específicas. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: el cliente revisa el modelo de base de datos para confirmar que representa fielmente las operaciones de inventario.
      
      .row.align-items-start.mb-5
        .col-lg-4.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema6/8.png", alt="").mb-4.mb-lg-0
        .col-lg-8
      
          AcordionA(tipo="b")
            .div(titulo="Revisión mediante prototipos")
              p Usa maquetas o versiones preliminares del sistema para validar diseño y usabilidad.  
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: en un prototipo navegable para reservas de hotel, el cliente sugiere reposicionar el botón de “Confirmar” para mejorar su visibilidad.
      
            .div(titulo="Revisión iterativa en ágil")
              p Se lleva a cabo al final de cada sprint en metodologías ágiles. El cliente evalúa el incremento entregado y da retroalimentación inmediata. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: al revisar el registro de usuarios, el cliente propone simplificar el formulario.
      
            .div(titulo="Revisión de aceptación")
              p Se hace al final del desarrollo para verificar el cumplimiento de todos los requisitos. Es la base para la aprobación formal del sistema.  
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: el cliente valida la generación de informes PDF con los filtros acordados y firma el acta de aceptación.
      
      .bg-full-width.bg-color-8.mb-5
        .px-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-8.text-white
              h2.mb-4(data-aos="flip-up") Técnicas para facilitar la revisión
              p.mb-4(data-aos="fade-right") Se invita a leer el documento <b>Técnicas para facilitar la revisión</b>, donde se aborda la importancia de emplear métodos estructurados y comunicativos para validar requisitos con el cliente durante el desarrollo de sistemas. 
      
              a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_9.pdf')" target="_blank")(data-aos="flip-up")
                .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p <strong>Anexo. </strong> Técnicas para facilitar la revisión.
      
            .col-lg-4.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema6/9.png', alt='')
      
      #t_2_3.titulo-segundo(data-aos="flip-up")
        h2 #[span 2.3] Roles y responsabilidades en la revisión
      
      .row.mb-5
        .col-lg-4.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema6/10.png", data-aos="zoom-in")
        .col-lg-8
          .bg-color-1.p-4.mb-5(data-aos="fade-left")
            .row.align-items-start
              .col-lg-auto
                img(src="@/assets/curso/tema6/11.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 La revisión con el cliente no es solo una conversación informal, sino una actividad organizada que involucra a distintos actores, cada uno con funciones específicas. Una correcta asignación de roles y responsabilidades, es fundamental para asegurar que la revisión de requisitos se lleve a cabo de manera efectiva, completa y alineada con los objetivos del proyecto.
          p(data-aos="fade-left") Aunque estos roles pueden variar, según el tipo de proyecto o estructura del equipo, los siguientes son los más comunes:
      
      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema6/12.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Cliente o representante del cliente
                p Se encarga de verificar que los requisitos respondan a sus necesidades reales, detectar errores o vacíos y aprobar o pedir ajustes. 
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Ejemplo</b>: en un sistema de facturación electrónica, el cliente detecta la ausencia de reportes mensuales y solicita su incorporación como funcionalidad clave.
      
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema6/13.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Analista de requisitos
                p Facilita la revisión, presenta documentos, orienta la discusión y garantiza que los requisitos sean claros, completos y verificables.
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Ejemplo</b>: ante una ambigüedad, el analista sugiere una redacción alternativa y gestiona su validación en el momento.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema6/14.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Líder o gerente de proyecto
                p Supervisa el proceso de revisión según cronograma y recursos, y evalúa el impacto de los cambios. 
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Ejemplo</b>: al solicitar una nueva funcionalidad que requiere dos semanas adicionales, el líder comunica el impacto y ajusta el plan con el cliente.
      
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema6/15.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Equipo técnico
                p Resuelve dudas técnicas, evalúa la viabilidad de los requisitos y anticipa restricciones. 
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Ejemplo</b>: un arquitecto de <em>software</em> advierte que subir archivos de 1 GB es costoso, y propone una alternativa más eficiente.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema6/16.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Usuario final o representante operativo
                p Aporta una visión práctica sobre la usabilidad y funcionalidad en el trabajo diario. 
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Ejemplo</b>: un operador de <em>call center</em> comenta que el flujo de atención es lento; su aporte permite reducir el número de clics necesarios.
      
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema6/17.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Representante de calidad o auditor
                p Verifica el cumplimiento de normas, registra evidencias y garantiza la trazabilidad.
                ul.lista-ul--color
                  li.mb-0.d-flex
                    i.far.fa-arrow-alt-circle-right
                    p.mb-0 <b>Ejemplo</b>: en un proyecto financiero, el auditor asegura que los requisitos aprobados cuenten con firma digital y estén almacenados conforme a la norma ISO.
      
      #t_2_4.titulo-segundo(data-aos="flip-up")
        h2 #[span 2.4] Herramientas y buenas prácticas
      
      p.mb-5 Una revisión con el cliente verdaderamente eficaz, requiere tanto una estructura metodológica clara como el uso de herramientas adecuadas y la adopción de buenas prácticas. Estos elementos aseguran que el proceso de validación sea eficiente, colaborativo y trazable, evitando malentendidos y promoviendo decisiones bien fundamentadas.
  
      .bg-full-width.bg-color-8.mb-0
        .px-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-8.order-2.text-white
              h2.mb-4(data-aos="flip-up") Invitación a revisar el documento SRS
              p.mb-4(data-aos="fade-right") Para conocer cómo se estructura un <b>Documento de Especificación de Requisitos de <em>software</em> (SRS)</b>, se invita a revisar el video explicativo. Este recurso detalla secciones clave como la introducción, la descripción general, los requisitos específicos y los anexos, destacando su papel fundamental en el éxito de los proyectos de <em>software</em>.
  

            .col-lg-4.order-1.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema6/18.png', alt='')

      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/3q6KziMQ1Kk?si=iAaDT9A8Z7qRxroE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
      h2(data-aos="fade-left") Herramientas para facilitar la revisión con el cliente
      p.mb-5 Las herramientas tecnológicas cumplen una función clave al organizar la información, centralizar el seguimiento de observaciones y promover la colaboración entre las partes involucradas.
  
      .row.align-items-start.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema6/19.png", alt="").mb-4.mb-lg-0
        .col-lg-8.order-lg-1
      
          AcordionA(tipo="b")
            .div(titulo="Documentos compartidos (Google Docs, Microsoft Word en línea)")
              p Permiten comentarios en tiempo real sobre los documentos de requisitos. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: durante una sesión remota, el cliente comenta directamente una sección ambigua; el analista responde y ajusta el texto al instante.
      
            .div(titulo="Plataformas de gestión de requisitos (Jama <em>software</em>, IBM DOORS, Jira + plugins)")
              p Estructuran, versionan y vinculan requisitos con pruebas de aceptación.
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: el cliente identifica que el requisito “RQT-15” no está vinculado a una prueba y solicita agregarla antes de su aprobación.
      
            .div(titulo="Sistemas de videoconferencia (Zoom, Microsoft Teams, Google Meet)")
              p Facilitan reuniones remotas mediante pantalla compartida, grabación y pizarras colaborativas. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: el analista presenta un prototipo, el cliente propone reorganizar botones y se deja registro en la grabación.
      
            .div(titulo="Herramientas de prototipado (Figma, Balsamiq, Adobe XD)")
              p Permiten validar visualmente requisitos e interacciones antes del desarrollo. 
              ul.lista-ul--color
                li.mb-0.d-flex
                  i.far.fa-arrow-alt-circle-right
                  p.mb-0 <b>Ejemplo</b>: al explorar un prototipo en Figma, el cliente nota la falta de una opción de envío y pide incluirla.
      
      h2(data-aos="fade-left") Buenas prácticas para una revisión efectiva
      p.mb-5 A continuación, se exponen las buenas prácticas para una revisión efectiva, destacando los elementos claves que garantizan claridad, participación y seguimiento en el proceso de validación de requisitos.
  
      .bg-full-width.bg-color-5.mb-5
        .p-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-6.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema6/20.svg", data-aos="zoom-in")
            .col-lg-6
              p(data-aos="fade-left").mb-4 Para conocer sobre los fundamentos de la innovación estratégica, lo invitamos a escuchar el siguiente podcast.
      
              TarjetaAudio.color-acento-botones.bg-color-white.mb-3(
                texto="Revisión de requisitos: buenas prácticas esenciales"
                tiempo
                :audio="require('../../assets/curso/podcast/podcast1.mp3')"
              )
          
      .bg-full-width.bg-color-8.mb-0
        .px-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-8.text-white
              h2.mb-4(data-aos="flip-up") Pruebas de aceptación de requisitos
              p.mb-4(data-aos="fade-right") Se invita a leer el documento <b>Pruebas de aceptación de requisitos</b>, donde se aborda detalladamente el proceso de validación de un sistema frente a los requerimientos y expectativas del cliente.  
      
              a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_11.pdf')" target="_blank")(data-aos="flip-up")
                .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p <strong>Anexo. </strong> Pruebas de aceptación de requisitos.
      
            .col-lg-4.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema6/21.png', alt='')
  
  
  
  
  
      
  
      .bg-full-width.border-top.actividad.bg-color-actividad
        .p-4.p-md-5
          #Actividad                
            <Actividad :cuestionario="cuestionario"/>
  
      .bg-full-width.border-top.color-primario
        .p-4.p-md-5
          h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
          .row.material-complementario
            .col-12.col-md-6.col-lg-7
              p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.


              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://www.ctr.unican.es/asignaturas/is1/IEEE830_esp.pdf" target="_blank" rel="noopener noreferrer") Institute of Electrical and Electronics Engineers. (1998). Especificaciones de los requisitos del <em>software</em>. IEEE.  
  
  
              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/274611https://elibro.net/es/lc/tecnologicadeloriente/titulos/304 pener noreferrer") Zapata Jaramillo, C. M. (2006). Alineación entre metas organizacionales y elicitación de requisitos del <em>software</em>. Red Dyna. 
  
  
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=TRp3ZkjKtj8 " target="_blank" rel="noopener noreferrer") Elite <em>software</em> Engineering. (2021). 02 - Ingeniería de Requerimientos - Priorizar a través de los tipos y niveles de requerimientos [video]. YouTube. 
  
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=y8zboz9AI_k " target="_blank" rel="noopener noreferrer") Garcia, C. (2020). Especificación de Requerimientos de <em>software</em> (E.R.S.) [video]. YouTube. 
  
  
            .col-12.col-md-6.col-lg-3.offset-lg-1
              figure
                img(src='@/assets/componentes/material-complementario.svg', alt='')
  
  </template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema6',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Ingeniería de Requisitos',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál de los siguientes métodos se utiliza comúnmente para validar que los requisitos cumplen con las necesidades del usuario?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              { id: 'a', texto: 'Modelado de datos.', esCorrecta: false },
              { id: 'b', texto: 'Diseño de interfaces.', esCorrecta: false },
              { id: 'c', texto: 'Revisión con el cliente.', esCorrecta: true },
              { id: 'd', texto: 'Codificación temprana.', esCorrecta: false },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué se espera lograr en una reunión de revisión de requisitos con el cliente?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Ajustar el presupuesto del proyecto.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Revisar el rendimiento del sistema.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Verificar la completitud y claridad de los requisitos.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Evaluar la arquitectura técnica.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál de las siguientes afirmaciones sobre las pruebas de aceptación es correcta?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Se realizan durante la fase de planificación del proyecto.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Son ejecutadas por los desarrolladores como parte del control de calidad.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Verifican que el sistema cumple con los requisitos definidos por el cliente.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Evalúan el rendimiento interno del sistema bajo carga.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué método de validación consiste en simular el uso del sistema por parte del cliente antes de su implementación final?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              { id: 'a', texto: 'Inspección de código.', esCorrecta: false },
              { id: 'b', texto: 'Prototipado.', esCorrecta: true },
              { id: 'c', texto: 'Integración continua.', esCorrecta: false },
              { id: 'd', texto: 'Prueba unitaria.', esCorrecta: false },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué característica distingue a las pruebas de aceptación respecto a otras pruebas?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Son realizadas exclusivamente por el equipo de desarrollo.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Se centran en el rendimiento del sistema.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'Se basan en los requisitos definidos por el cliente.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Se ejecutan durante el diseño del software.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
