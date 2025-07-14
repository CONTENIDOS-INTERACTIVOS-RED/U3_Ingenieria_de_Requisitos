<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.px-4.px-md-5.pt-4.pt-md-5.mb-5

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-4.tarjeta.p-3.h-100(data-aos="fade-left")
          p(data-aos="fade-left") En el desarrollo de software, la calidad de los requisitos es crucial para el éxito del proyecto. La unidad se enfoca en dos procesos claves: la validación y la verificación de requisitos. Estas actividades garantizan que los requisitos expresen fielmente las necesidades del cliente y estén formulados con precisión, sin errores ni ambigüedades. Aplicarlas correctamente, asegura que el sistema cumpla con las expectativas desde su concepción.
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/intro/1.png" data-aos="zoom-in")
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-2.tarjeta.p-3.h-100(data-aos="fade-left")
          p(data-aos="fade-left") El objetivo es que el estudiante aprenda a identificar y aplicar métodos de validación y verificación, realizar revisiones efectivas con el cliente y diseñar pruebas de aceptación. Estas competencias permiten construir sistemas más confiables, reducir errores en etapas avanzadas y mejorar la comunicación entre los actores involucrados en el proyecto.
    
    .bg-full-width.bg-color-3.mb-0
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 La unidad tiene un enfoque práctico, utilizando casos reales y ejercicios aplicados para mostrar cómo se implementan estos procesos en la industria. Se estructura en tres ejes: métodos de validación, revisión con el cliente y pruebas de aceptación. Se espera del estudiante una participación activa y crítica, consolidando sus conocimientos y fortaleciendo su aprendizaje autónomo y colaborativo.

</template>
