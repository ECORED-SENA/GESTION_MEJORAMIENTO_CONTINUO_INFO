<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Calidad: gestión del mejoramiento continuo
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Calidad: gestión del mejoramiento continuo
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 12110085
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 1 mes
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/yWRltmZDqgk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenido al programa formativo Calidad: gestión del mejoramiento continuo, a través del cual adquirirá elementos teóricos y prácticos para aplicar diferentes herramientas disponibles en el logro del mejoramiento continuo de la empresa.
      br
      br
      |El SENA ofrece este programa que incluye las temáticas de técnicas de análisis de la información, acciones de mejora continua, diagnóstico organizacional, normatividad empresarial, indicadores de gestión, informes de resultados, entre otros.

      br
      br
      |Buscando cumplir con el Plan Nacional de Desarrollo hacia un pacto por Colombia, con legalidad, emprendimiento y equidad para todos, que pretende incrementar los recursos de ciencia y tecnología para impulsar sectores que promuevan la productividad, la competitividad, la sostenibilidad y la equidad, en su estrategia de articular programas de fortalecimiento empresarial. 

      br
      br
      |Esta formación se encuentra dirigida a gerentes, directores, supervisores y partes interesadas pertenecientes a cualquier actividad económica, con el fin de ayudar en la implementación de un mejoramiento continuo organizacional.

      br
      br
      |Se espera que disfrute esta formación.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p Este programa de formación complementaria va dirigido a gerentes, directores, supervisores y partes interesadas de la empresa pertenecientes a cualquier actividad económica que pretendan tener un mejoramiento organizacional de forma técnica y estratégica para ser más sostenibles, competitivas e innovadoras en el tiempo, teniendo como herramientas básicas la autogestión y autocorrección de fallas organizacionales, estando en coherencia con el Plan Nacional de Desarrollo hacia un Pacto por Colombia, con legalidad, emprendimiento y equidad para todos, que pretende incrementar los recursos en ciencia y tecnología para impulsar el crecimiento de emprendimientos nuevos e innovadores, en su objetivo de fortalecer las capacidades técnicas de los sectores y territorios que promuevan la productividad, la competitividad, la sostenibilidad y la equidad, en su estrategia de articular los programas de fortalecimiento empresarial para que los empresarios accedan a una oferta que corresponda con sus necesidades.
      br
      br
      |El programa ayuda a detectar las fallas y la formulación de las posibles soluciones, teniendo en cuenta las opciones que el medio ofrece y la viabilidad de aplicación en la empresa y la validación de las propuestas que correspondan a los requerimientos técnicos que se deriven de la naturaleza de la organización y de la normatividad vigente.
      br
      br
      |Este programa pretende que las empresas tengan la posibilidad de crear estrategias para lograr un mejoramiento continuo en todos sus procesos, característica particular de este programa y que es muy importante para que una organización sea productiva y sostenible en el tiempo. 



  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar
    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | Elaborar propuesta de solución con base en metodologías y procedimiento técnico.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso
    p.mb-5 Conocimientos empresariales y trabajo en equipo.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Estrategia metodológica
    p Centrada en la construcción de autonomía para garantizar la calidad en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales, soportadas en la utilización de las Tecnologías de la Información y la Comunicación - TIC, integradas en ambientes abiertos y pluritecnológicos, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra, a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:

    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | El instructor – Tutor.
        li 
          i.fas.fa-angle-right
          | El entorno.
        li 
          i.fas.fa-angle-right
          | Las TIC.
        li 
          i.fas.fa-angle-right
          | El trabajo colaborativo.

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
