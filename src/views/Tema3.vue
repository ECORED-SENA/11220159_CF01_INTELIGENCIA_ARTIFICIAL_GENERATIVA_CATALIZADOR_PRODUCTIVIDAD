<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 3
        h1 Configuración técnica, gobernanza de datos y marco normativo en Colombia
      .color___box_1
        .px-5
          .row.justify-content-center.align-items-center.mb-5
            .col-xl.mb-4.mb-lg-0
              .box___style_2.fit___box_9(data-aos="fade-right")
                p.mb-0 La implementación efectiva de la inteligencia artificial generativa (IAG) en las organizaciones no se limita a la interacción con una interfaz conversacional. Este proceso requiere una configuración técnica rigurosa y un marco sólido de gobernanza de datos que garantice integridad, privacidad y uso ético de la información corporativa.
            .col-xl-auto.col-md-9(data-aos="fade-left")
              figure
                img(src="@/assets/curso/temas/t3/img1.png", alt="alt").m-auto
          p.mb-5 En entornos empresariales y productivos, resulta indispensable establecer protocolos técnicos y administrativos orientados a mitigar riesgos de seguridad, proteger activos digitales y asegurar el cumplimiento normativo aplicable en Colombia.
          #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 3.1 Configuración inicial, registro y niveles de permisos
          p.mb-5 El proceso de configuración inicial de herramientas como ChatGPT, Claude o Copilot debe desarrollarse bajo criterios de trazabilidad, control de acceso y administración segura de la información. Estas configuraciones permiten supervisar las acciones realizadas dentro de la plataforma y reducir riesgos asociados al uso indebido de datos sensibles. En esta etapa, se identifican los principales componentes técnicos:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Registro y autenticación
                      p.mb-0 Se recomienda priorizar sistemas de Inicio de Sesión Único (#[i Single Sign-On] [SSO]) empresariales, con el fin de centralizar la gestión de identidades y garantizar que únicamente el personal autorizado acceda a las herramientas de IA.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img2.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Gestión de permisos
                      p.mb-0 Es fundamental establecer niveles de acceso diferenciados. No todos los colaboradores requieren las mismas capacidades de procesamiento ni acceso a información sensible. Se deben definir roles como administrador, editor y usuario final para controlar recursos, acciones permitidas y acceso a registros de actividad (#[i logs]).
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img3.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Ajustes de interfaz y localización
                      p.mb-0 La configuración de idioma y región trasciende la preferencia del usuario. Estos parámetros influyen en la interpretación de unidades de medida, formatos de fecha y matices lingüísticos técnicos que el modelo aplicará durante la generación de resultados.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img4.png', alt='' style="max-width: 500px").m-auto
      .row.justify-content-center.align-items-center.mb-0
        .col-xl.mb-4.mb-lg-0
          .box___style_3.fit___box_10(data-aos="fade-right")
            p.mb-0 La correcta configuración de estos elementos fortalece la seguridad operativa y permite una administración más eficiente de los recursos tecnológicos basados en IA. Además, facilita procesos de auditoría, seguimiento de actividades y cumplimiento de políticas internas de protección de datos.
        .col-xl-auto.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t3/img5.jpg', alt='').m-auto
        .col-xl
          figure.mb-2.d-none.d-xl-block(data-aos="fade-left")
            img(src='@/assets/curso/temas/t3/img6.svg', alt='' style="width: 75px")
          p.mb-0 En el contexto colombiano, estas prácticas deben articularse con principios de gobernanza digital, protección de datos personales y ciberseguridad organizacional, especialmente cuando las plataformas procesan información sensible, estratégica o confidencial.
      .color___box_1
        .px-5
          Separador
          #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 3.2 Gestión de privacidad y Almacenamiento de la información
          p.mb-5 La gobernanza de datos en inteligencia artificial generativa (IAG) requiere un ecosistema técnico, legal y organizacional que garantice el control del ciclo de vida de la información. En este contexto, el aprendiz debe comprender y aplicar configuraciones de privacidad orientadas a evitar que datos sensibles sean utilizados para el reentrenamiento de modelos públicos.
          .row.align-items-center.mb-5
            .col-xl.mb-4.mb-lg-0
              .box___style_1.fit___box_3(data-aos="fade-right")
                p.mb-0 La protección de la información no depende únicamente de la herramienta tecnológica, sino también de las políticas de uso, almacenamiento y tratamiento de datos implementadas por la organización. A continuación, se presentan los principales componentes asociados a la gestión de privacidad y almacenamiento:
            .col-xl-auto.d-none.d-xl-block(data-aos="fade-left")
              figure
                img(src="@/assets/curso/temas/t3/img7.jpg", alt="").m-auto
          .row.justify-content-center.mb-5
            .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="fade-right")
              .box___style_h4_p.h-100
                h4.mb-0.text-center.fit___h4_card Políticas de privacidad y RGPD
                .box___card_p
                  p.mb-0 En el contexto internacional, el Reglamento General de Protección de Datos (RGPD) constituye uno de los principales referentes normativos. Las plataformas de IA deben cumplir principios de licitud, transparencia, minimización y tratamiento adecuado de los datos personales.
            .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .box___style_h4_p.h-100
                h4.mb-0.text-center.fit___h4_card Soberanía de datos y almacenamiento
                .box___card_p
                  p.mb-0 Es fundamental determinar si los #[i prompts] y respuestas se almacenan en nubes públicas, privadas o infraestructuras locales. Para información de alta sensibilidad, se recomienda desactivar historiales de entrenamiento o utilizar versiones empresariales con cláusulas de protección de propiedad intelectual.
            .col-xl-4.col-md-9(data-aos="fade-left")
              .box___style_h4_p.h-100
                h4.mb-0.text-center.fit___h4_card Anonimización proactiva
                .box___card_p
                  p.mb-0 Antes de suministrar información a un LLM, se recomienda reemplazar nombres, identificadores únicos y datos personales por términos genéricos. Esta práctica reduce riesgos de exposición y fortalece la confidencialidad organizacional y de los clientes.
          p.mb-0 La correcta administración de estos componentes fortalece la seguridad digital, reduce riesgos de fuga de información y facilita el cumplimiento de políticas de protección de datos tanto nacionales como internacionales.
          Separador
          #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 3.3 Protocolos de uso ético y responsabilidad corporativa
          p.mb-5 La ética aplicada a la inteligencia artificial no constituye un concepto abstracto, sino un requisito técnico, jurídico y corporativo indispensable para la implementación responsable de sistemas inteligentes. Los desarrollos basados en IA deben incorporar mecanismos orientados a prevenir sesgos discriminatorios, minimizar riesgos de desinformación y garantizar transparencia en la interacción con los usuarios. Entre los principales protocolos de uso ético y responsabilidad corporativa, se destacan los siguientes:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Identificación de sesgos y alucinaciones
                      p.mb-0 Las organizaciones deben implementar mecanismos de supervisión para detectar sesgos automatizados y respuestas incorrectas generadas por la IA. La validación humana especializada continúa siendo obligatoria, especialmente cuando las decisiones afectan derechos o condiciones de terceros.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img8.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Transparencia e información al usuario
                      p.mb-0 Conforme a lineamientos regulatorios y políticas públicas relacionadas con IA, los sistemas deben permitir que el usuario identifique claramente que interactúa con una inteligencia artificial y pueda interpretar críticamente los resultados generados.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img9.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Protocolo de abstención
                      p.mb-0 La IA debe configurarse para aplicar un “silencio estratégico”, indicando explícitamente cuando no dispone de información suficiente o cuando las fuentes recuperadas presentan inconsistencias. Este enfoque reduce el riesgo de fabricación de respuestas y fortalece la confiabilidad del sistema.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img10.png', alt='' style="max-width: 500px").m-auto
      .color___box_1
        .px-5
          p.mb-0 La incorporación de protocolos éticos en sistemas de IAG fortalece la confianza institucional, mejora la trazabilidad de los procesos y contribuye a una adopción tecnológica alineada con principios de responsabilidad social y protección de derechos. En el contexto corporativo, la supervisión humana continúa siendo un componente irreemplazable para garantizar decisiones seguras, transparentes y técnicamente verificables.
          Separador
          #t_3_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 3.4 Marco normativo y de política pública de IA en Colombia
          .row.justify-content-center.align-items-center.mb-5
            .col-xl.mb-4.mb-lg-0
              .box___style_1.fit___box_11(data-aos="fade-right")
                p.mb-0 Para que el sector productivo colombiano integre la inteligencia artificial (IA) como motor de competitividad y transformación digital, resulta indispensable que dicha adopción se realice bajo el marco de los instrumentos de política pública y los regímenes de protección de datos vigentes.
            .col-xl-auto.col-md-9(data-aos="fade-left")
              figure
                img(src="@/assets/curso/temas/t3/img11.png", alt="alt").m-auto
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
            .bloque-texto-g__img(
              :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t3/img12.jpg')})` }")
            .bloque-texto-g__texto.p-4
              p.mb-0 En este contexto, el Estado colombiano ha definido una hoja de ruta estratégica orientada a fortalecer la soberanía digital, promover la innovación tecnológica y garantizar la protección de los derechos ciudadanos dentro del ecosistema de inteligencia artificial generativa (IAG).
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img9.svg" style="max-width: 60px").m-auto
            .col
              h3 Política nacional de Inteligencia Artificial (CONPES 4144)
          p.mb-5 El documento CONPES 4144 de 2025 constituye uno de los principales referentes de la estrategia estatal para posicionar a Colombia como una economía basada en el conocimiento y el aprovechamiento responsable de la IA.
          .row.align-items-center.mb-5
            .col-xl.mb-4.mb-lg-0
              .box___style_1.fit___box_3(data-aos="fade-right")
                p.mb-0 Su objetivo principal consiste en desarrollar capacidades para la investigación, desarrollo, adopción y uso ético y sostenible de sistemas de inteligencia artificial en el país (Departamento Nacional de Planeación, República de Colombia, 2025). La política se estructura en seis ejes estratégicos fundamentales que orientan la implementación nacional de la IA:
            .col-xl-auto.d-none.d-xl-block(data-aos="fade-left")
              figure
                img(src="@/assets/curso/temas/t3/img13.jpg", alt="").m-auto
          .bg___carrusel
            .px-5
              .row.align-items-center.mb-5
                .col-xl-4(data-aos="fade-right")
                  figure.d-none.d-xl-block
                    img(src='@/assets/curso/temas/t3/img14.png', alt='' style="max-width: 350px").m-auto
                .col-xl-8(data-aos="fade-left")
                  SlyderF(columnas="col-lg-6 col-xl-6")
                    .tarjeta.color-acento-botones.p-4
                      .row.justify-content-center.mb-3
                        .col-8
                          img(src='@/assets/curso/temas/t3/img15.svg' style="max-width: 90px").m-auto
                      h4.mb-3.estilo-text Ética y gobernanza
                      p.mb-0.text-center Fortalecimiento de mecanismos orientados a garantizar un uso responsable de la IA, alineado con derechos humanos, transparencia y protección de la ciudadanía.
                    .tarjeta.color-acento-botones.p-4
                      .row.justify-content-center.mb-3
                        .col-8
                          img(src='@/assets/curso/temas/t3/img16.svg' style="max-width: 90px").m-auto
                      h4.mb-3.estilo-text Datos e infraestructura
                      p.mb-0.text-center Optimización de recursos tecnológicos, capacidades de cómputo e interoperabilidad de plataformas estatales y organizacionales.
                    .tarjeta.color-acento-botones.p-4
                      .row.justify-content-center.mb-3
                        .col-8
                          img(src='@/assets/curso/temas/t3/img17.svg' style="max-width: 90px").m-auto
                      h4.mb-3.estilo-text Investigación, Desarrollo e Innovación (I+D+i)
                      p.mb-0.text-center Impulso a la generación de conocimiento científico y desarrollo de soluciones tecnológicas nacionales basadas en IA.
                    .tarjeta.color-acento-botones.p-4
                      .row.justify-content-center.mb-3
                        .col-8
                          img(src='@/assets/curso/temas/t3/img18.svg' style="max-width: 90px").m-auto
                      h4.mb-3.estilo-text Capacidades y talento digital
                      p.mb-0.text-center Formación de talento humano en competencias relacionadas con inteligencia artificial, ciencia de datos y transformación digital.
                    .tarjeta.color-acento-botones.p-4
                      .row.justify-content-center.mb-3
                        .col-8
                          img(src='@/assets/curso/temas/t3/img19.svg' style="max-width: 90px").m-auto
                      h4.mb-3.estilo-text Mitigación de riesgos
                      p.mb-0.text-center Definición de medidas orientadas a prevenir impactos negativos, asimetrías tecnológicas y posibles escenarios de discriminación o exclusión.
                    .tarjeta.color-acento-botones.p-4
                      .row.justify-content-center.mb-3
                        .col-8
                          img(src='@/assets/curso/temas/t3/img20.svg' style="max-width: 90px").m-auto
                      h4.mb-3.estilo-text Uso y adopción
                      p.mb-0.text-center Promoción de la implementación de IA en entidades públicas, organizaciones privadas y sectores estratégicos del territorio nacional.
              .color___box_2
                .px-5
                  .row.align-items-center.mb-5
                    .col-xl.mb-4.mb-lg-0
                      p El horizonte de implementación de esta política se proyecta hasta el año 2030, con inversiones orientadas a cerrar brechas tecnológicas y fortalecer el posicionamiento de Colombia como referente regional en inteligencia artificial responsable.
                      p.mb-0 La comprensión de estos lineamientos resulta fundamental para el profesional que interactúa con sistemas de IA, ya que permite integrar criterios técnicos, éticos y regulatorios dentro de los procesos de innovación y transformación digital organizacional.
                    .col-xl-auto.d-none.d-xl-block(data-aos="fade-left")
                      figure
                        img(src="@/assets/curso/temas/t3/img21.png", alt="").m-auto
                  .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
                    .col-lg-auto
                      figure
                        img(src="@/assets/curso/temas/t1/img9.svg" style="max-width: 60px").m-auto
                    .col
                      h3 Régimen general de protección de datos personales (Ley 1581 de 2012)
                  p.mb-5 El tratamiento de la información realizado por sistemas de inteligencia artificial en Colombia está sujeto al cumplimiento estricto de la Ley 1581 de 2012. Esta normativa desarrolla el derecho constitucional de #[i Habeas Data], permitiendo que los ciudadanos conozcan, actualicen, rectifiquen y controlen la información recolectada sobre ellos en bases de datos (República de Colombia, 2012).
                  .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
                    .bloque-texto-g__img(
                      :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t3/img22.jpg')})` }")
                    .bloque-texto-g__texto.p-4
                      p.mb-0 En el contexto de la inteligencia artificial generativa (IAG), esta ley adquiere especial relevancia debido al procesamiento masivo de datos que realizan los algoritmos y modelos de lenguaje. Para implementar soluciones de IA en el sector productivo, es indispensable aplicar los principios rectores establecidos por la normativa colombiana de protección de datos personales. A continuación, se presentan los principales principios aplicables al despliegue técnico de sistemas de IA:
                  .bg___slider.mb-5
                    .px-5
                      .ajuste-slider(data-aos="zoom-in")
                        SlyderA(tipo="b")
                          .row.justify-content-center.align-items-center
                            .col-xl-6.mb-4
                              h4 Legalidad y finalidad
                              p.mb-0 El tratamiento de datos mediante algoritmos debe desarrollarse conforme a actividades autorizadas legalmente y responder a finalidades legítimas previamente informadas al titular de los datos.
                            .col-xl-6
                              figure
                                img(src='@/assets/curso/temas/t3/img23.png', alt='' style="max-width: 500px").m-auto
                          .row.justify-content-center.align-items-center
                            .col-xl-6.mb-4
                              h4 Veracidad y calidad
                              p.mb-0 La información procesada por sistemas de IA debe ser completa, exacta, verificable y actualizada. Se prohíbe el tratamiento de datos parciales, inexactos o que induzcan a error.
                            .col-xl-6
                              figure
                                img(src='@/assets/curso/temas/t3/img24.png', alt='' style="max-width: 500px").m-auto
                          .row.justify-content-center.align-items-center
                            .col-xl-6.mb-4
                              h4 Transparencia
                              p.mb-0 El titular tiene derecho a conocer la existencia, uso y tratamiento de sus datos personales en cualquier momento, incluyendo información sobre los sistemas que los procesan.
                            .col-xl-6
                              figure
                                img(src='@/assets/curso/temas/t3/img25.png', alt='' style="max-width: 500px").m-auto
                          .row.justify-content-center.align-items-center
                            .col-xl-6.mb-4
                              h4 Seguridad y confidencialidad
                              p.mb-0 Las organizaciones deben implementar medidas técnicas y administrativas, como cifrado, control de accesos y anonimización, para prevenir adulteración, pérdida, filtración o acceso no autorizado a la información.
                            .col-xl-6
                              figure
                                img(src='@/assets/curso/temas/t3/img26.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 La aplicación de estos principios fortalece la confianza en los sistemas de IA y contribuye a una gestión responsable de los datos dentro de las organizaciones.
      .row.align-items-center.mb-5
        .col-xl.mb-4.mb-lg-0
          .box___style_1.fit___box_3.fit___box_12(data-aos="fade-right")
            p.mb-0 En ambientes corporativos, el cumplimiento de la Ley 1581 de 2012 no solo representa una obligación jurídica, sino también un componente estratégico de gobernanza digital, ciberseguridad y protección reputacional. Asimismo, garantiza que la adopción de tecnologías de IA se alinee con los derechos fundamentales de los ciudadanos y con estándares adecuados de tratamiento ético de la información.
        .col-xl-auto.d-none.d-xl-block(data-aos="fade-left")
          figure
            img(src="@/assets/curso/temas/t3/img27.jpg", alt="").m-auto
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img9.svg" style="max-width: 60px").m-auto
        .col
          h3 Sinergia entre política y Ley para la productividad
      p.mb-0 La integración de la IA bajo el marco del #[b CONPES 4144] y la #[b Ley 1581] permite mitigar riesgos críticos como la #[b vulneración de la privacidad] y la #[b distorsión de la veracidad]. El aprendiz debe reconocer que la protección de datos no es una barrera para la innovación, sino un habilitador de confianza digital, la cual es esencial para que las empresas y ciudadanos adopten estas tecnologías de manera masiva y segura.

</template>

<script>
export default {
  name: 'Tema3',
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
