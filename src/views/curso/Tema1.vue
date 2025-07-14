<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'1. Métodos de validación'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
  
      .row.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/1.png", data-aos="zoom-in")
        .col-lg-8.order-lg-1
          p.mb-5(data-aos="fade-left") Los métodos de validación constituyen un conjunto de técnicas y estrategias destinadas a comprobar que el sistema desarrollado cumple con los requisitos especificados desde el inicio del proyecto. A través de estos métodos, se verifica que el producto de <em>software</em> se alinea con las necesidades del usuario y las condiciones de aceptación acordadas.
      
          .bg-color-1.p-4(data-aos="fade-left")
            .row.align-items-start
              .col-lg-auto
                img(src="@/assets/curso/tema5/2.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 La validación no se enfoca únicamente en encontrar errores técnicos, sino en confirmar que el sistema es funcional, útil y aceptable para el cliente. Para ello, se emplean procedimientos como la revisión de documentos, las inspecciones formales, la ejecución de pruebas controladas y la interacción directa con el cliente. La correcta aplicación de estos métodos garantiza que el <em>software</em> entrega valor y que está listo para ser implementado en un entorno real.
  
      #t_1_1.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.1] Concepto y objetivos de la validación de requisitos
      
      .bg-color-3.mb-5(data-aos="fade-up")
        .row.justify-content-center.align-items-center
          .col-lg-auto.mb-3.mb-lg-0
            figure
              img(src='@/assets/curso/tema5/3.png', alt='')
          .col-lg
            .p-4
              p.mb-0.text-white(data-aos="fade-up") La validación de requisitos es un proceso fundamental dentro del desarrollo de <em>software</em> que busca asegurar que las necesidades y expectativas del cliente, hayan sido correctamente comprendidas, documentadas y traducidas en especificaciones funcionales y no funcionales. A diferencia de la verificación, que se centra en comprobar si el producto se ha construido correctamente, la validación se enfoca en evaluar si el producto construido es el correcto para el usuario.
      
      .titulo-figura.mb-4
        h5 Tabla 1.
        span Comparación entre verificación y validación
      .tabla-a.color-acento-botones.mb-5
        table
          thead
            tr.text-center
              th.bg-color-6.text-white.text-center Verificación
              th.bg-color-6.text-white.text-center Validación
          tbody.bg-color-7
            tr
              td Evalúa si el sistema fue construido correctamente.
              td Evalúa si el sistema correcto fue construido.
            tr
              td Se enfoca en especificaciones técnicas.
              td Se enfoca en necesidades y expectativas del usuario.
            tr
              td Incluye revisiones, pruebas unitarias y de integración.
              td Incluye pruebas de aceptación, simulaciones y prototipos.
            tr
              td Ocurre típicamente durante el desarrollo.
              td Ocurre al final de cada iteración o al final del desarrollo.
      
      h2(data-aos="fade-left") Objetivos específicos de la validación de requisitos
      p.mb-5 Además de su propósito general, la validación de requisitos cumple con una serie de objetivos específicos que fortalecen la calidad del producto y del proceso de desarrollo. Estos objetivos se detallan a continuación:
  
      .row.align-items-start.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/4.png", alt="").mb-4.mb-lg-0
        .col-lg-8.order-lg-1
      
          AcordionA(tipo="b")
            .div(titulo="Confirmar la conformidad con las expectativas del cliente")
              p Verifica que los requisitos reflejan con precisión lo que el usuario espera del sistema.
      
            .div(titulo="Detectar errores en los requisitos antes del desarrollo")
              p Identifica defectos conceptuales tempranamente, evitando que avancen a fases más costosas de corregir.
      
            .div(titulo="Reducir riesgos del proyecto")
              p Minimiza la posibilidad de implementar funcionalidades innecesarias o dejar de lado aspectos esenciales.
      
            .div(titulo="Facilitar la comunicación entre las partes interesadas")
              p Promueve el diálogo entre clientes, analistas y desarrolladores para asegurar interpretaciones compartidas del sistema deseado.
            .div(titulo="Aumentar la trazabilidad")
              p Permite establecer vínculos entre requisitos, casos de uso, pruebas y componentes del sistema, facilitando el seguimiento y control del proyecto.
      
      .row.mb-5
        .col-lg-3.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/5.svg", data-aos="zoom-in")
        .col-lg-9
          h2.mb-5(data-aos="fade-left") Ejemplo práctico
      
          .bg-color-2.p-4(data-aos="fade-left")
            p.mb-0 En el desarrollo de una aplicación bancaria móvil, un requisito funcional establece que: “El usuario debe poder consultar su saldo en tiempo real”. Durante la validación con el cliente, se identifica que la frase “en tiempo real” puede interpretarse de diferentes formas: ¿significa actualización automática cada segundo, al hacer login, o tras pulsar un botón? Este análisis permite reformular el requisito como: “El usuario podrá consultar el saldo actualizado al momento de realizar la consulta desde la pantalla principal, presionando el botón Actualizar”. Esta aclaración evita errores de interpretación, en el desarrollo posterior.
  
      #t_1_2.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.2] Técnicas formales e informales de validación
      
      .row.mb-5
        .col-lg-5.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/6.png", data-aos="zoom-in")
        .col-lg-7.order-lg-1
          .bg-color-4.p-4.h-100(data-aos="fade-left")
            .row.align-items-start
              .col-lg-auto
                img(src="@/assets/curso/tema5/7.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 En el proceso de validación de requisitos se emplean técnicas formales e informales, cada una con un propósito específico. La elección de una u otra depende del tipo de proyecto, la madurez del equipo de desarrollo y la complejidad de los requisitos. Ambas técnicas son complementarias y, cuando se aplican correctamente, permiten lograr una validación más robusta y eficiente.
      
      h2(data-aos="fade-left") Técnicas informales de validación
      p.mb-5 Las técnicas informales se caracterizan por su bajo rigor estructural y se basan en la interpretación directa, revisión subjetiva o discusión abierta de los requisitos. Son comunes en proyectos ágiles o en las etapas tempranas del desarrollo, dado que permiten detectar ambigüedades u omisiones sin recurrir a herramientas matemáticas o métodos formales. Ejemplos:
  
      .bg-full-width.bg-color-5
        .px-4.px-md-5.pb-md-3
          .row.justify-content-center.align-items-stretch.mb-5
            .col-lg-3.mb-4(data-aos="zoom-in-up")
              .custom-image-card-2.h-100
                img.custom-image-card__image(src="@/assets/curso/tema5/8.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Revisiones por pares
                  p.mb-0 Reuniones entre analistas, diseñadores o programadores que revisan los requisitos de forma colaborativa para identificar errores o contradicciones.
            .col-lg-3.mb-4(data-aos="zoom-in-down")
              .custom-image-card-2.h-100
                img.custom-image-card__image(src="@/assets/curso/tema5/9.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Entrevistas y sesiones de <em>feedback</em> con el cliente
                  p.mb-0 Interacción directa para verificar si los requisitos representan las necesidades reales del usuario.
            .col-lg-3.mb-4(data-aos="zoom-in-down")
              .custom-image-card-2.h-100
                img.custom-image-card__image(src="@/assets/curso/tema5/10.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Prototipos de baja fidelidad
                  p.mb-0 Representaciones visuales simples (<em>wireframes</em>, maquetas) que permiten validar requisitos funcionales, especialmente los relacionados con interfaces.
            .col-lg-3.mb-4(data-aos="zoom-in-down")
              .custom-image-card-2.h-100
                img.custom-image-card__image(src="@/assets/curso/tema5/11.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Listas de verificación (<em>checklists</em>)
                  p.mb-0 Guías simples que orientan la revisión de aspectos como claridad, completitud y viabilidad.
      
      .row.mb-5
        .col-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/12.svg", data-aos="zoom-in")
        .col-lg-10
          .bg-color-1.p-5(data-aos="fade-left")
            p.mb-0 <b>Ejemplo práctico</b>. Durante una revisión por pares, un analista detecta que el requisito “el sistema enviará notificaciones importantes” era ambiguo. Se reformula como “notificaciones sobre fallos de seguridad, interrupciones de servicio y actualizaciones críticas del sistema”.
      
      h2(data-aos="fade-left") Técnicas formales de validación
      p.mb-5 Las técnicas formales emplean modelos matemáticos, lógicos o simbólicos, para verificar la consistencia, corrección y completitud de los requisitos. Aunque más complejas, ofrecen mayor garantía de precisión, especialmente en sistemas críticos (aviación, medicina, control industrial). Ejemplos:
  
      .bg-full-width.bg-color-7
        .px-4.px-md-5
          .row.justify-content-center.align-items-center
            .col-lg-12
              .row.justify-content-center.align-items-center
                .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0
                  ul.lista-ul--color
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 <b>Especificación formal</b>. Uso de lenguajes como Z, B o VDM, para expresar los requisitos sin ambigüedades y validar su consistencia.
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 <b>Modelos basados en lógica temporal</b>. Verifican el comportamiento de sistemas reactivos o concurrentes, a lo largo del tiempo.
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 <b>Verificación asistida por herramientas</b>. Utilización de programas que comprueban automáticamente la lógica de los requisitos y detectan errores o incoherencias.
                .col-lg-5(data-aos="zoom-in")
                  img.img-fluid(src='@/assets/curso/tema5/13.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
      
      .bg-full-width.bg-color-14.mb-5
        .px-4.px-md-5.py-4
          p.mb-0 Ejemplo práctico. En el desarrollo del <em>software</em> de un marcapasos, se emplean especificaciones formales para definir el ritmo de pulsaciones y la respuesta ante fallos. Gracias a este enfoque, se detecta una contradicción entre dos reglas de temporización que podría haber provocado un mal funcionamiento del dispositivo.
  
      #t_1_3.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.3] Revisión con el cliente como técnica de validación
      
      .row.mb-5
        .col-lg-5.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/14.png", data-aos="zoom-in")
        .col-lg-7
          .bg-color-2.px-5.py-4.h-100(data-aos="fade-left")
            p.mb-0 La revisión con el cliente es una técnica esencial en la validación de requisitos, puesto que garantiza que las especificaciones recogidas durante la fase de análisis realmente reflejen las necesidades, expectativas y restricciones del usuario final. A diferencia de las validaciones internas, realizadas dentro del equipo de desarrollo, esta técnica involucra directamente al cliente o usuario, promoviendo un enfoque colaborativo y centrado en el valor de negocio.
      
      h2(data-aos="fade-left") Propósito y ventajas de la revisión con el cliente
      p.mb-5 El objetivo principal es confirmar la alineación entre los requisitos documentados y los objetivos reales del cliente. Durante este proceso, los <em>stakeholders</em> evalúan si los requerimientos son:
  
      .row.mb-5
        .col-lg-4.mb-3.mb-lg-0.order-lg-2
          figure
            img(src="@/assets/curso/tema5/15.png", data-aos="zoom-in")
        .col-lg-8.order-lg-1
          .bg-color-4.p-5(data-aos="fade-left")
            ul.lista-ul--color.mb-0
              li.mb-2.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Comprensibles.
              li.mb-2.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Correctos
              li.mb-2.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Completos.
              li.mb-2.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 Adecuados para alcanzar el resultado esperado del sistema o producto.
      
      .row.mb-5
        .col-lg-4.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/16.png", data-aos="zoom-in")
        .col-lg-8
          p Los beneficios claves son:
          .bg-color-10.p-5(data-aos="fade-left")
            ul.lista-ul--color.mb-0
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Detección temprana de errores o malentendidos</b>, lo cual reduce los costos de corrección en etapas posteriores.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Fortalecimiento de la confianza y la comunicación</b> entre el cliente y el equipo de desarrollo.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 <b>Refinamiento y ajuste de requisitos</b>, según nuevas prioridades o cambios en el entorno.
      
      h2(data-aos="fade-left") Modalidades de revisión con el cliente
      p.mb-5 A continuación se presentan las formas más comunes de llevar a cabo esta técnica, dependiendo del contexto del proyecto y del modelo de desarrollo adoptado:
  
      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema5/17.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Reuniones presenciales o virtuales
                p El cliente participa en sesiones donde se presentan requisitos en lenguaje natural o diagramas (casos de uso, prototipos) para opinar y sugerir cambios.
      
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema5/18.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Demostraciones funcionales
                p Común en metodologías ágiles; se muestran entregables funcionales (por ejemplo, al final de un sprint) para validar que cumplen con los requisitos.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5.order-2
                figure
                  img(src="@/assets/curso/tema5/19.png")
              .col-lg-7.order-1.mb-3.mb-lg-0
                h5 Revisión de prototipos
                p Se utilizan maquetas o prototipos navegables para que el cliente interactúe y valide la experiencia de uso prevista.
      
      .row.mb-5
        .col-lg-4.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/20.png", data-aos="zoom-in")
        .col-lg-8
          .bg-color-9.p-5.bordes(data-aos="fade-left")
            p.mb-0 <b>Ejemplo práctico</b>. Una empresa de logística contrata a un equipo de desarrollo para construir un sistema de gestión de envíos. Durante la fase de análisis, se establece que el sistema debe permitir al cliente rastrear sus paquetes en tiempo real.
      
          .bg-color-1.p-4(data-aos="fade-left")
            p.mb-0 Posteriormente, el equipo convoca una sesión de revisión con el gerente de operaciones. Al revisar el requisito, el cliente aclara que también es necesario generar alertas automáticas cuando los envíos se retrasen más de 30 minutos. Gracias a esta retroalimentación, el equipo incorpora este detalle crítico en los requisitos antes de avanzar al diseño.
      
      #t_1_4.titulo-segundo(data-aos="flip-up")
        h2 #[span 1.4] Prototipado y simulación para validar requisitos
      
      p.mb-5 El prototipado y la simulación, son herramientas críticas dentro del proceso de validación de requisitos, porque permiten a los equipos de desarrollo y a los clientes visualizar y experimentar las características y comportamientos del sistema, antes de que este sea completamente desarrollado. Esto es vital para garantizar que los requisitos capturados reflejan correctamente las necesidades y expectativas de los usuarios finales.
  
      .titulo-figura.mb-4
        h5 Figura 1.
        span Prototipo de App
      div.bg-color-info.p-5.mb-5
        .row.justify-content-center.align-items-center
          .col-lg-10
            figure
              img(src="@/assets/curso/tema5/21.png", data-aos="zoom-in")
            figcaption.mt-2.text-center.mb-4 Nota. Doonamis. (2022). Proceso de creación de un prototipo de app [Imagen]. Doonamis
      
      h2.mb-5(data-aos="fade-left") Prototipado: una representación tangible de los requisitos
  
      .row.mb-5
        .col-lg-4.order-lg-2.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/22.png", data-aos="zoom-in")
        .col-lg-8.order-lg-1
          p(data-aos="fade-left") El prototipado y la simulación, son técnicas complementarias para validar requisitos, que permiten detectar errores, facilitar la comprensión del sistema y mejorar la comunicación entre los <em>stakeholders</em>. Estas técnicas ofrecen representaciones tempranas, tangibles o funcionales, del producto final, permitiendo una retroalimentación oportuna antes del desarrollo completo.
      
          .bg-color-2.p-4(data-aos="fade-left")
            .row.align-items-start
              .col-lg-auto
                img(src="@/assets/curso/tema5/23.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 El prototipado consiste en crear modelos preliminares del sistema, que pueden ir desde bocetos en papel hasta simulaciones digitales completas. Su propósito principal es ofrecer una experiencia cercana a la interacción final con el producto, para facilitar la comprensión, identificar errores y obtener retroalimentación temprana.
      
      .titulo-figura.mb-4
        h5 Tabla 2.
        span Tipo de prototipo
      .tabla-a.color-acento-botones.mb-5
        table
          thead
            tr.text-center
              th.bg-color-6.text-white.text-center Tipo de prototipo
              th.bg-color-6.text-white.text-center Características
              th.bg-color-6.text-white.text-center Ejemplo
          tbody.bg-color-7
            tr
              td Baja fidelidad.
              td Bocetos, diagramas o <em>wireframes</em> que muestran estructura y navegación sin detalles visuales ni funcionalidad completa.
              td Dibujo manual de una pantalla de inicio de sesión.
            tr
              td Alta fidelidad.
              td Simulan el diseño visual y la interacción real, usando herramientas como Figma, Adobe XD o Axure. Permiten navegación e ingreso de datos.
              td Prototipo interactivo con formularios funcionales y transiciones realistas.
  
      .row.mb-5
        .col-lg-5.mb-3.mb-lg-0
          figure
            img(src="@/assets/curso/tema5/24.png", data-aos="zoom-in")
        .col-lg-7
          .bg-color-3.text-white.p-4.h-100(data-aos="fade-left")
            p.mb-0 <b>Ejemplo práctico</b>. Un equipo desarrolla una aplicación móvil para reservas de restaurantes. Comienza con un prototipo en papel mostrando pantallas principales: selección de restaurante, menú y confirmación de reserva. Luego, tras la validación con el cliente, crean un prototipo digital navegable que simula el flujo completo. Esto permite al cliente experimentar la reserva e identificar mejoras, como filtros por tipo de cocina.
  
      h2(data-aos="fade-left") Simulación: imitando el comportamiento real del sistema
      p.mb-5 La simulación va más allá del diseño visual y busca replicar el comportamiento, lógica y respuesta del sistema, frente a distintos escenarios. Es especialmente útil para validar requisitos funcionales y no funcionales, como rendimiento, manejo de errores o secuencias de procesos.
  
      .titulo-figura.mb-4
        h5 Tabla 3.
        span Simulaciones
      .tabla-a.color-acento-botones.mb-5
        table
          thead
            tr.text-center
              th.bg-color-6.text-white.text-center Aplicación de la simulación
              th.bg-color-6.text-white.text-center Finalidad
          tbody.bg-color-7
            tr
              td Simulación de procesos empresariales.
              td Validar flujos de trabajo y decisiones operativas.
            tr
              td Simulación de sistemas en tiempo real.
              td Evaluar requisitos de rendimiento y tiempos de respuesta.
            tr
              td Simulación de escenarios de usuario.
              td Verificar experiencia y usabilidad ante distintas condiciones.
      
      p.mb-5 <b>Ejemplo práctico</b>. En un proyecto para automatizar un <em>call center</em>, se simula el flujo de llamadas, decisiones de enrutamiento y tiempos de espera. Esta simulación revela cuellos de botella que afectan la experiencia del usuario, permitiendo ajustar los requisitos antes del desarrollo. Las ventajas y desafíos del prototipado y la simulación son: 
  
      .bg-full-width.bg-fondo-3.mb-5
        .px-4.px-md-5
          .row.justify-content-center.align-items-center
            .col-lg-8
              ImagenInfografica.color-secundario
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/tema5/25.svg', alt='', style="max-width: 1106px;").mx-auto
      
                .bg-color-white.box-shadow.p-3(x="53%" y="46.5%" numero="+")
                  h5 Ventajas
                  ul.lista-ul--color
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Detección temprana de errores y malentendidos.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Mejora de la comunicación entre las partes interesadas.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Facilita consenso y decisiones basadas en experiencias concretas.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Aumento de la satisfacción del cliente al involucrarlo activamente.
      
                .bg-color-white.box-shadow.p-3(x="46%" y="22%" numero="+")
                  h5 Desafíos
                  ul.lista-ul--color
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Costo y tiempo requeridos para prototipos de alta fidelidad.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Riesgo de confusión entre prototipo y producto final.
                    li.mb-0.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Posible resistencia a cambios tras la retroalimentación.
      
      p.mb-5 Las recomendaciones para una implementación efectiva, son:
  
      .bg-color-2.bordes-1.mb-5
        .px-4.px-md-5
          .row.justify-content-center.align-items-center
            .col-lg-12
              .row.justify-content-center.align-items-center
                .col-lg-9(data-aos="fade-left").mb-3.mb-lg-0
                  ul.lista-ul--color
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Comenzar con prototipos de baja fidelidad para recopilar retroalimentación rápida y económica.
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Evolucionar progresivamente a prototipos de alta fidelidad y simulaciones, conforme se clarifican los requisitos.
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Utilizar herramientas digitales accesibles para su creación (ejemplo, Figma, Axure, Simul8).
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Planificar sesiones de revisión con clientes y usuarios finales.
                    li.mb-3.d-flex
                      i.far.fa-arrow-alt-circle-right
                      p.mb-0 Documentar los cambios en los requisitos derivados del proceso de validación.
  
                .col-lg-3(data-aos="zoom-in")
                  img.img-fluid(src='@/assets/curso/tema5/26.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
  
      .bg-full-width.bg-color-8.mb-0
        .px-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-8.order-2.text-white
              h2.mb-4(data-aos="flip-up") Pruebas de aceptación como mecanismo de validación
              p.mb-4(data-aos="fade-right") Se invita a leer el documento <b>Pruebas de aceptación como mecanismo de validación</b>, donde se aborda el papel fundamental de las pruebas de aceptación, dentro del proceso de validación de requisitos en el desarrollo de <em>software</em>. 
      
              a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_8.pdf')" target="_blank")(data-aos="flip-up")
                .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p <strong>Anexo. </strong> Pruebas de aceptación como mecanismo de validación.
      
            .col-lg-4.order-1.mb-3.mb-lg-0
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema5/27.png', alt='')
  
  
      .bg-full-width.border-top.color-primario
        .p-4.p-md-5
          h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
          .row.material-complementario
            .col-12.col-md-6.col-lg-7
              p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
  
              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://open.umn.edu/opentextbooks/textbooks/1423 " target="_blank" rel="noopener noreferrer") Celi-Párraga, R. J., Boné-Andrade, M. F., Mora-Olivero, A. P. & Sarmiento-Saavedra, J. C. (2023). Ingeniería del <em>software</em> I: Requerimientos y Modelado del <em>software</em>. Editorial Grupo AEA. 
              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://www.ctr.unican.es/asignaturas/is1/IEEE830_esp.pdf" target="_blank" rel="noopener noreferrer") Institute of Electrical and Electronics Engineers. (1998). Especificaciones de los requisitos del <em>software</em>. IEEE.  
  
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=73fuqZ78uhg " target="_blank" rel="noopener noreferrer") Elite <em>software</em> Engineering. (2021). 03 - Ingeniería de Requerimientos - Recolección de requerimientos [video]. YouTube. 

  
  
  
  
            .col-12.col-md-6.col-lg-3.offset-lg-1
              figure
                img(src='@/assets/componentes/material-complementario.svg', alt='')
  
  </template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
