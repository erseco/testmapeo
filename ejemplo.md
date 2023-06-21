Eres un coordinadores del Servicio de Perfeccionamiento del profesorado, estás adaptando los diseños de los cursos de formacion del profesorado existentes, te voy a indicar el marco de referencia para la competencia digital docente en formato YAML y el diseño de un curso también en formato YAML, quiero que analices el curso e identifiques cuales de las 6 áreas y qué niveles (A1, A2 o B1) cumple cada una de las áreas que se consiguen alcanzar. Para contribuir a una determinado nivel de un área se deben alcanzar al menos el 80% de los indicadores de logro.
Indica las áreas como en este ejemplo:

------------------------------------------------------------------------------------
| Area   | Nivel | Justificación                                                   |
---------|--------------------------------------------------------------------------
| Area 1 |   A1  | porque conoce..                                                 |
| Area 2 |   A2  | porque utiliza...                                               |
| Area 3 |   A1  | porque conoce..                                                 |
| Area 4 |       |                                                                 |
| Area 5 |       |                                                                 |
| Area 6 |       |                                                                 |
------------------------------------------------------------------------------------

Marco de referencia de la competencia digital docente:

marco_referencia_competencia_digital_docente:
  - area: 1
    titulo: Compromiso profesional
    competencias:
    - competencia: 1.1
      titulo: Comunicación organizativa
      descripcion: Utilizar las tecnologías digitales establecidas por las Administraciones Educativas o, en su caso, por los titulares del centro, para aplicar las estrategias de comunicación organizativa entre los agentes de la comunidad educativa y de estos con terceros, contribuyendo a la mejora de dichas estrategias y a la proyección de la imagen institucional de la organización
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación en entornos controlados de las tecnologías digitales propuestas por las Administraciones Educativas (AAEE) o los titulares del centro para mejorar la comunicación y la proyección de la imagen institucional de la organización
          niveles:
            - nivel: A1
              titulo: Conocimiento general de las tecnologías de comunicación más utilizadas en los contextos educativos y comprensión de su finalidad
              indicadores_logro:
                - indicador: 1
                  titulo: "Se comunica empleando las normas básicas de la etiqueta digital mediante tecnologías digitales: correo electrónico, foros, chat, sistemas de videoconferencia, etc"
                - indicador: 2
                  titulo: "Utiliza cada una de las herramientas de forma correcta adaptándolas al contexto comunicativo"
                - indicador: 3
                  titulo: "Conoce las características, funcionalidades, opciones de accesibilidad y limitaciones de las herramientas de comunicación, así como la normativa aplicada a su uso en el ámbito educativo"
              afirmaciones_desempeño: Utilizo tecnologías digitales para la comunicación en función del contexto
              ejemplos:
                - Empleo las funcionalidades de los sistemas de videoconferencias en las actividades de comunicación síncronas con otras personas
                - Utilizo las normas básicas de etiqueta en la comunicación digital (uso de mayúsculas, emoticonos, etc.)
                - Selecciono herramientas síncronas o asíncronas en función de la finalidad comunicativa y de la disponibilidad horaria de mis interlocutores.              
            - nivel: A2
              titulo: Iniciación en el uso de las tecnologías digitales determinadas por la Administración Educativa (AE) o titulares del centro educativo en situaciones de comunicación organizativa
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce y aplica, bajo supervisión, las políticas de uso aceptable de las herramientas de comunicación organizativa establecidas por la AE o los titulares del centro"
                - indicador: 2
                  titulo: "Emplea, con el asesoramiento de otros docentes y garantizando la accesibilidad, las tecnologías digitales establecidas por la AE o los titulares del centro en un contexto real de comunicación en el ámbito educativo"
              afirmaciones_desempeño: Utilizo, de forma guiada, las herramientas de comunicación establecidas por la AE o los titulares del centro siguiendo las políticas de uso aceptable
        - etapa: B
          titulo: Integración de las tecnologías digitales para la comunicación establecidas por la AE o por los titulares del centro en el desempeño profesional
          niveles:
            - nivel: B1
              titulo: Adopción de las estrategias de comunicación organizativa del centro educativo a través de tecnologías digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Se comunica de forma autónoma y convencional con los agentes de la comunidad educativa empleando, en cada caso, la herramienta digital más adecuada de entre las establecidas por la AE o los titulares del centro para ese fin"
                - indicador: 2
                  titulo: "Aplica las políticas de uso aceptable de las herramientas de comunicación organizativa establecidas por la AE o los titulares del centro"
              afirmaciones_desempeño: Utilizo de forma correcta, autónoma y selectiva las herramientas de comunicación establecidas por la AE o los titulares del centro
    - competencia: 1.2
      titulo: Participación, colaboración y coordinación profesional
      descripcion: Utilizar las tecnologías digitales para participar en los órganos colegiados de gobierno y de coordinación docente del centro, para coordinarse con los integrantes de los equipos docentes, de los servicios de orientación y apoyo educativo, así como para colaborar con profesorado de otros centros, educadores y miembros de otras instituciones en el desarrollo de planes y proyectos específicos promovidos desde el centro educativo
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada de las tecnologías digitales para la participación en los órganos de gobierno y de coordinación docente
          niveles:
            - nivel: A1
              titulo: Conocimiento teórico/práctico del uso de las tecnologías de colaboración
              indicadores_logro:
                - indicador: 1
                  titulo: "Identifica las funcionalidades, condiciones de seguridad, protección de datos y privacidad, características técnicas (accesibilidad, interoperabilidad,...) de distintas plataformas de colaboración con el fin de seleccionar una que se adecue a la finalidad con la que se desea emplear"
                - indicador: 2
                  titulo: "Utiliza distintas plataformas de colaboración con aplicación profesional para su uso personal"
              afirmaciones_desempeño: Conozco las posibilidades y limitaciones de plataformas de colaboración utilizadas en contextos educativos y las uso en proyectos personales
            - nivel: A2
              titulo: Participación formal en los órganos de coordinación docente del centro empleando, de forma guiada, las tecnologías digitales establecidas por la AE o los titulares del centro
              indicadores_logro:
                - indicador: 1
                  titulo: Utiliza, de forma guiada, las distintas plataformas de participación y coordinación docentes establecidas por la AE o los titulares del centro
              afirmaciones_desempeño: Participo, mediante tecnologías digitales, en los órganos de coordinación y de gobierno de forma guiada
        - etapa: B
          titulo: Utilización de las tecnologías digitales del centro para la participación y coordinación docente y transferencia de las estrategias de colaboración al desarrollo de proyectos institucionales
          niveles:
            - nivel: B1
              titulo: Uso convencional y autónomo de las tecnologías digitales establecidas por la AE o los titulares del centro para la participación y colaboración docente
              indicadores_logro:
                - indicador: 1
                  titulo: "Emplea, de forma autónoma, las tecnologías digitales y aplica los protocolos establecidos por la AE o por los titulares del centro para llevar a cabo las tareas administrativas ligadas a las funciones docentes, para participar en los órganos colegiados de gobierno y de coordinación docente y con los servicios institucionales externos"
                - indicador: 2
                  titulo: "Adopta las estrategias de colaboración mediante tecnologías digitales propuestas por el centro en los distintos procesos de coordinación y participación interna"
              afirmaciones_desempeño: Utilizo las tecnologías digitales establecidas por la AE o por los titulares del centro siguiendo los protocolos y estrategias propuestas para llevar a cabo las tareas administrativas y para participar en los órganos colegiados de gobierno y en los de coordinación docente
    - competencia: 1.3
      titulo: Práctica reflexiva
      descripcion: Reflexionar, de modo individual y colectivo, sobre la práctica pedagógica digital que se desarrolla en el aula y en el centro con la finalidad de aplicar las mejoras identificadas a través de este proceso
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada de modelos de análisis, reflexión y evaluación, tanto individual como conjunta, del uso de las tecnologías en la práctica docente
          niveles:
            - nivel: A1
              titulo: Conocimiento de herramientas y modelos para llevar a cabo un análisis reflexivo del uso de las tecnologías digitales en la práctica docente
              indicadores_logro:
                - indicador: 1
                  titulo: "Distingue distintos modelos de prácticas pedagógicas digitales y analiza teóricamente sus ventajas e inconvenientes"
                - indicador: 2
                  titulo: "Conoce instrumentos de apoyo para reflexionar de forma crítica sobre la práctica docente, tanto de forma individual como colectiva"
              afirmaciones_desempeño: Identifico prácticas pedagógicas digitales y me posiciono, de forma justificada, con respecto a su aplicación en el aula
            - nivel: A2
              titulo: Práctica reflexiva tutelada
              indicadores_logro:
                - indicador: 1
                  titulo: Reflexiona, de forma individual o colectiva, asesorado por profesorado de su centro o por expertos externos, sobre aspectos técnicos o metodológicos concretos de su práctica docente digital que haya considerado relevantes
              afirmaciones_desempeño: Analizo, con el asesoramiento de otro docente o de un formador, algún aspecto técnico o metodológico relevante de las prácticas pedagógicas digitales tuteladas que he llevado a cabo teniendo en cuenta tanto el proceso desarrollado como los resultados obtenidos
        - etapa: B
          titulo: Análisis y aplicación de las prácticas pedagógicas digitales en el aula
          niveles:
            - nivel: B1
              titulo: Análisis y reflexión individual sobre la aplicación personal de las metodologías y tecnologías digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Identifica problemas en su práctica pedagógica con tecnologías digitales y los resuelve adoptando soluciones estandarizadas aportadas por otros docentes"
                - indicador: 2
                  titulo: "Examina la implementación de los métodos de integración de las tecnologías digitales que ha llevado a cabo en su práctica docente, analizando el proceso desarrollado, los resultados obtenidos y el modo en el que ha reaccionado a situaciones imprevistas"
              afirmaciones_desempeño: Identifico los problemas que se me presentan y analizo la respuesta que he dado ante situaciones imprevistas para reelaborar mi práctica pedagógica digital empleando soluciones que me aportan otros docentes o que recojo de Internet
    - competencia: 1.4
      titulo: Desarrollo profesional digital continuo
      descripcion: Desarrollar de forma continuada las competencias profesionales docentes a través de medios digitales. Mantener actualizada la competencia digital docente
      etapas:
        - etapa: A
          titulo: Participación en actividades formativas para la aplicación práctica de los modelos teóricos de desarrollo profesional sobre o a través de las tecnologías digitales
          niveles:
            - nivel: A1
              titulo: Construcción de modelos docentes de referencia e identificación de las necesidades formativas para su concreción en la práctica
              indicadores_logro:
                - indicador: 1
                  titulo: Identifica sus necesidades de desarrollo profesional para aplicar en la práctica, mediante las tecnologías digitales, su formación teórica
              afirmaciones_desempeño: Empleo las tecnologías digitales para identificar y reflexionar, de forma teórica, sobre las habilidades pedagógicas que caracterizan a un buen docente, en especial su competencia digital, para tenerlo como referente en mi desarrollo profesional continuo (DPC)
            - nivel: A2
              titulo: Participación en actividades formativas vinculadas con la práctica inicial contextualizada en el centro y en el propio desempeño profesional sobre y/o a través de las tecnologías digitales
              indicadores_logro:
                - indicador: 1
                  titulo: Aprovecha las oportunidades de aprendizaje en su centro y las que obtiene a través de la red para su desarrollo profesional
              afirmaciones_desempeño: Identifico, con ayuda de otros compañeros y/o expertos, mis necesidades de formación para el desarrollo de mi práctica profesional sobre y a través de las tecnologías digitales
        - etapa: B
          titulo: Selección y participación en actividades de desarrollo profesional docente adaptadas a sus necesidades sobre o a través de las tecnologías digitales
          niveles:
            - nivel: B1
              titulo: Actualización y desarrollo profesional a través de tecnologías digitales o sobre su uso educativo empleando recursos elaborados por expertos
              indicadores_logro:
                - indicador: 1
                  titulo: "Participa en actividades de formación para el desarrollo profesional docente dirigidas por expertos, en línea o presenciales, en las que se utilicen recursos digitales para su desarrollo"
                - indicador: 2
                  titulo: "Participa en cursos dirigidos al desarrollo de la competencia digital docente"
                - indicador: 3
                  titulo: "Utiliza los recursos de Internet para el aprendizaje autodeterminado en el ámbito profesional"
              afirmaciones_desempeño: Participo en actividades formativas dirigidas o diseñadas por expertos vinculadas con mis ámbitos de mejora sobre la competencia digital y/o a través de medios digitales
    - competencia: 1.5
      titulo: Protección de datos personales, privacidad, seguridad y bienestar digital
      descripcion: Proteger los datos personales, las comunicaciones y el acceso a los dispositivos, dentro del ámbito educativo, para evitar los riesgos y amenazas que afecten a los derechos y garantías digitales de todos los miembros de la comunidad educativa contemplados en la normativa vigente. Utilizar de manera responsable, segura y saludable las tecnologías digitales para evitar riesgos laborales, personales y en el entorno y para garantizar el bienestar físico, psicológico y social del alumnado al utilizar las tecnologías digitales
      etapas:
        - etapa: A
          titulo: Conocimiento de las medidas sobre protección de datos, privacidad, seguridad, derechos digitales y bienestar digital aplicadas en el ámbito educativo
          niveles:
            - nivel: A1
              titulo: Conocimiento general de medidas para proteger los datos personales, la privacidad, la seguridad, los derechos digitales y el bienestar al utilizar las tecnologías digitales en contextos educativos
              indicadores_logro:
                - indicador: 1
                  titulo: "Reconoce los riesgos y amenazas de la actividad digital y utiliza medidas de carácter general para proteger los datos personales y el acceso a los dispositivos en el ámbito profesional"
                - indicador: 2
                  titulo: "Conoce medidas generales para garantizar la protección de datos y la seguridad del alumnado y de los menores en entornos digitales"
                - indicador: 3
                  titulo: "Aplica medidas para garantizar el bienestar físico y psicológico y el cuidado del entorno en el uso de las tecnologías digitales"
              afirmaciones_desempeño: Conozco las medidas para proteger los datos personales, la privacidad, la seguridad, los derechos digitales y el bienestar al utilizar las tecnologías digitales en contextos educativos, especialmente con menores, y las normas básicas de protección de la salud física y psicológica y del medio ambiente
            - nivel: A2
              titulo: Conocimiento y aplicación, de forma guiada, de las medidas de protección de los datos personales y la privacidad, así como de las de seguridad y salvaguarda de los derechos digitales y el bienestar al utilizar las tecnologías digitales en contextos educativos reales
              indicadores_logro:
                - indicador: 1
                  titulo: "Contextualiza y cumple las medidas establecidas por la AE o los titulares del centro para la protección de los datos personales, la privacidad y la garantía de derechos digitales de toda la comunidad educativa con el asesoramiento de otros docentes del centro"
                - indicador: 2
                  titulo: "Reconoce los riesgos y amenazas de la actividad digital y cumple las medidas de seguridad y prevención establecidas por el centro educativo, en el plan digital, con el apoyo de los responsables del centro"
                - indicador: 3
                  titulo: "Identifica los riesgos y amenazas para la salud física y psicológica del alumnado asociada al uso de las tecnologías digitales y cumple con las pautas establecidas por el centro para la creación de un entorno saludable"
              afirmaciones_desempeño: Conozco y aplico, con el asesoramiento de otros docentes, las medidas establecidas por la AE o los titulares del centro para la protección de los datos personales, la privacidad y la garantía de derechos digitales de toda la comunidad educativa, así como las medidas incluidas en el plan digital del centro para garantizar el bienestar digital
        - etapa: B
          titulo: Adopción y evaluación de las medidas sobre protección de datos, privacidad, seguridad, derechos digitales y bienestar digital aplicadas en el centro educativo
          niveles:
            - nivel: B1
              titulo: Uso sistemático y autónomo de las medidas establecidas para proteger los datos personales y la privacidad, así como las medidas de seguridad y salvaguarda de los derechos digitales y el bienestar al utilizar las tecnologías digitales en el centro educativo
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, de manera autónoma, las medidas propuestas por la AE o los titulares del centro para proteger los datos personales propios y ajenos"
                - indicador: 2
                  titulo: "Aplica las medidas de prevención e identifica situaciones en las que se hayan podido vulnerar los derechos personales y digitales o en las que se haya puesto en peligro la seguridad física y psicológica de cualquier miembro de la comunidad educativa como consecuencia del uso de las tecnologías digitales y actúa frente a ellas aplicando el protocolo establecido en el centro"
                - indicador: 3
                  titulo: "Realiza un uso racional de las tecnologías digitales encaminado a reducir el impacto en el medioambiente aplicando las políticas de uso de las tecnologías establecidas en el centro"
              afirmaciones_desempeño: Cumplo, de forma autónoma y sistemática, las medidas para proteger los datos personales y la privacidad, así como las medidas de seguridad y salvaguarda de los derechos digitales y el bienestar al utilizar las tecnologías digitales en mi desempeño docente
  - area: 2
    titulo: Contenidos digitales
    competencias:
    - competencia: 2.1
      titulo: Búsqueda y selección de contenidos digitales
      descripcion: Localizar, evaluar y seleccionar contenidos digitales de calidad para apoyar y mejorar la enseñanza y el aprendizaje. Considerar, de forma específica, el objetivo de aprendizaje, el contexto, el enfoque pedagógico, el tipo de licencia y aspectos técnicos que garanticen la accesibilidad universal, la usabilidad y la interoperabilidad
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación tutelada de criterios de calidad para seleccionar contenidos digitales adecuados y seguros y uso de estrategias de búsqueda y organización eficiente
          niveles:
            - nivel: A1
              titulo: Conocimiento teórico de los criterios para la selección de contenidos digitales y aplicación práctica de estrategias de búsqueda y organización
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los criterios didácticos, técnicos (licencias, accesibilidad, adecuación a la edad del alumnado y a la consecución de los objetivos) y científicos (fiabilidad de las fuentes, rigor, etc.) para la selección de contenidos de calidad"
                - indicador: 2
                  titulo: "Utiliza buscadores que facilitan la neutralidad de los resultados obtenidos, aplica estrategias eficientes de búsqueda y conoce la función de los metadatos en la recuperación de contenidos"
                - indicador: 3
                  titulo: "Utiliza algún sistema de organización de recursos (aplicaciones, extensiones del navegador, etc.)"
              afirmaciones_desempeño: Conozco teóricamente los criterios de calidad y los requisitos que debe reunir un contenido digital de calidad y los aplico en la práctica para su búsqueda y selección. Organizo y estructuro los resultados de mis búsquedas empleando distintos tipos de herramientas
            - nivel: A2
              titulo: Identificación, con asesoramiento, de los criterios relevantes para la búsqueda y selección de contenidos digitales ajustados a un contexto educativo real
              indicadores_logro:
                - indicador: 1
                  titulo: "Identifica, con asesoramiento, los requisitos que debe cumplir un contenido digital para ajustarse a una situación concreta de aprendizaje y aplica los criterios correspondientes para su búsqueda y selección, incluyendo la compatibilidad con las plataformas virtuales establecidas por la AE o los titulares del centro"
                - indicador: 2
                  titulo: "Conoce el funcionamiento y utiliza los repositorios de contenidos institucionales y los empleados por el centro educativo"
              afirmaciones_desempeño: Establezco, con apoyo y asesoramiento, los requisitos que debe cumplir un contenido digital para su utilización en un contexto específico de aprendizaje y aplico estrategias eficaces de búsqueda y localización tanto en Internet como en los repositorios determinados por el centro o por la AE
        - etapa: B
          titulo: Búsqueda y selección de contenidos educativos digitales orientados a su uso en el proceso de enseñanza y aprendizaje a partir de criterios de calidad y de un análisis riguroso del contexto concreto en el que se van a emplear
          niveles:
            - nivel: B1
              titulo: Uso convencional y autónomo de los motores de búsqueda, repositorios de contenidos y BBDD para su aplicación educativa en un contexto (nivel, materia, competencia, tema, etc.) y una situación de aprendizaje concretos (refuerzo, ampliación o profundización)
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica de forma autónoma criterios didácticos, técnicos y científicos en la búsqueda y selección de contenidos educativos digitales que se ajusten a una situación concreta de aprendizaje (por ejemplo, refuerzo, ampliación o profundización)"
                - indicador: 2
                  titulo: "Utiliza búsquedas que permiten localizar distintos formatos de contenido (audio, vídeo, imágenes, web, etc.) seleccionando aquellos que favorecen la motivación, la implicación y la participación de todo el alumnado en una misma actividad"
                - indicador: 3
                  titulo: "Utiliza de forma sistemática algún sistema de organización y catalogación de los contenidos educativos digitales seleccionados para uso propio o dentro del equipo docente del que forma parte"
              afirmaciones_desempeño: Adopto, de forma autónoma, estrategias de búsqueda y selección de contenidos educativos digitales para disponer, a través de un catálogo organizado (propio o del centro), de aquellos que mejor se adaptan al contexto concreto en el que se van a emplear
    - competencia: 2.2
      titulo: Creación y modificación de contenidos digitales
      descripcion: Modificar y adaptar los contenidos educativos digitales respetando las condiciones de uso (obras derivadas y limitaciones recogidas en los derechos de propiedad intelectual) establecidas por cada licencia. Crear nuevos contenidos educativos digitales de forma individual o en colaboración con otros profesionales dentro de entornos seguros. Considerar, de modo específico, el objetivo de aprendizaje, el contexto, el enfoque pedagógico y los destinatarios al diseñar y crear o modificar los contenidos digitales. Seleccionar las herramientas digitales de autor, para la creación y modificación de contenidos, teniendo en cuenta las características técnicas y de accesibilidad y los términos de uso y la política de privacidad
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación, con ayuda y en entornos controlados, de los criterios didácticos, disciplinares y técnicos para la modificación y creación de contenidos digitales respetando la normativa sobre propiedad intelectual
          niveles:
            - nivel: A1
              titulo: Conocimiento, comprensión y aplicación teórica de los criterios didácticos, disciplinares y técnicos y el uso de herramientas de autor para la edición y creación de contenidos digitales de calidad respetando la normativa vigente sobre propiedad intelectual
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los criterios didácticos, disciplinares y técnicos (adecuación a la edad del alumnado y a la consecución de los objetivos, accesibilidad, etc.) y los aplica de forma genérica en la edición y creación de contenidos digitales"
                - indicador: 2
                  titulo: "Conoce y comprende los tipos de licencias existentes y los términos que recoge cada una de ellas para la edición y creación de contenidos digitales respetando los derechos de autor (transformación) y de propiedad intelectual y utiliza alguna norma internacional para las citas y referencias"
                - indicador: 3
                  titulo: "Utiliza herramientas de autor generales para la creación y edición de contenidos digitales (ofimáticas, editor de audio, imágenes, vídeo, etc.) y las específicas de las materias que imparte (editor de ecuaciones, partituras, editor de texto para diversos alfabetos, …)"
              afirmaciones_desempeño: Conozco, comprendo y aplico de forma general los criterios didácticos, disciplinares y técnicos para la modificación y creación de contenidos digitales de calidad, empleando distintas herramientas de autor, y respeto la normativa sobre propiedad intelectual
            - nivel: A2
              titulo: Aplicación, en entornos controlados o con ayuda, de los criterios didácticos, disciplinares y técnicos en la edición y creación de contenidos digitales de calidad para utilizarlos con un grupo de alumnos concreto
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, con ayuda, los criterios didácticos (adecuación a la edad del alumnado y a la consecución de los objetivos, accesibilidad, etc.), disciplinares y técnicos para la edición y creación de contenidos digitales dirigidos a un grupo de alumnos concreto"
                - indicador: 2
                  titulo: "Utiliza un sistema de referencias empleando, si fuera posible, las funcionalidades disponibles en las herramientas de autor proporcionadas por el centro o por la AE"
                - indicador: 3
                  titulo: "Utiliza, de forma tutelada, las herramientas de autor proporcionadas por la AE o los titulares del centro para la creación de contenidos digitales, o aquellas que generen formatos compatibles con las plataformas autorizadas en el centro"
              afirmaciones_desempeño: Aplico, con asesoramiento o ayuda, los criterios didácticos, disciplinares y técnicos para la modificación y creación de recursos digitales para utilizarlos con un grupo de alumnos en concreto, empleando las herramientas de autor proporcionadas por la AE o titulares del centro y respetando la normativa sobre propiedad intelectual
        - etapa: B
          titulo: Modificación de contenidos educativos digitales ya existentes e integración de contenidos de diversas procedencias -incluidos algunos elementos de creación propia- en unidades y secuencias de aprendizaje estructuradas
          niveles:
            - nivel: B1
              titulo: Adopción de los criterios didácticos, disciplinares y técnicos para la modificación de elementos integrados en contenidos educativos digitales estructurados ya existentes con objeto de adecuarlos a una situación de aprendizaje y alumnado concretos
              indicadores_logro:
                - indicador: 1
                  titulo: "Analiza la idoneidad de contenidos educativos digitales ya existentes aplicando de forma autónoma criterios didácticos, disciplinares y técnicos para adaptarlos a una situación de aprendizaje concreta"
                - indicador: 2
                  titulo: "Incluye una licencia compatible con la de la obra original al modificar contenidos educativos digitales cuya licencia autoriza obras derivadas"
                - indicador: 3
                  titulo: "Utiliza las herramientas de autor para la edición de contenidos educativos digitales sustituyendo o modificando algunos de sus elementos, incluyendo sus metadatos"
              afirmaciones_desempeño: Modifico, de forma autónoma, contenidos educativos digitales ya existentes, cuya licencia así lo autorice, para adaptarlos a las características de mi alumnado atendiendo a criterios didácticos, disciplinares y técnicos y respetando los derechos de autor. Sé utilizar las funcionalidades de las herramientas de autor que permiten incluir metadatos en los contenidos educativos digitales
    - competencia: 2.3
      titulo: Protección, gestión y compartición de contenidos digitales
      descripcion: Catalogar los contenidos educativos digitales y ponerlos a disposición de la comunidad educativa y del colectivo profesional utilizando entornos seguros. Proteger eficazmente los contenidos digitales. Respetar y aplicar correctamente la normativa sobre propiedad intelectual y derechos de autor en la gestión y compartición de contenidos digitales
      etapas:
        - etapa: A
          titulo: Conocimiento y respeto de la normativa sobre propiedad intelectual y derechos de autor y uso tutorizado con fines educativos de sistemas de catalogación y de plataformas para la compartición de contenidos digitales
          niveles:
            - nivel: A1
              titulo: Conocimiento y respeto de la normativa sobre propiedad intelectual y derechos de autor, así como sobre los procedimientos de catalogación digital y las funcionalidades básicas de las plataformas para compartir con fines educativos contenidos digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce y utiliza entornos digitales seguros para la compartición de contenidos con fines educativos, analizando sus políticas de uso"
                - indicador: 2
                  titulo: "Conoce los distintos tipos de permisos que se pueden otorgar en entornos digitales a la hora de compartir contenidos en contextos educativos"
                - indicador: 3
                  titulo: "Conoce y aplica la normativa sobre propiedad intelectual y derechos de autor (reproducción, distribución y comunicación pública), así como los distintos tipos de licencias y las condiciones asociadas a cada una de ellas"
                - indicador: 4
                  titulo: "Conoce y aplica de forma general los sistemas de catalogación y las funcionalidades que las herramientas de autor ofrecen para incluir metadatos en los diferentes formatos de archivos"
              afirmaciones_desempeño: Conozco y respeto la normativa sobre propiedad intelectual y derechos de autor, así como las condiciones establecidas en los distintos tipos de licencias; sé utilizar las funcionalidades de algunas de las plataformas y herramientas de autor para la publicación de contenidos digitales e incluir metadatos que los identifiquen para su catalogación
            - nivel: A2
              titulo: Aplicación de los procedimientos de publicación, compartición y catalogación de contenidos con la ayuda de un mentor en los CMS, repositorios, BBDD y CLMS ofrecidos por la AE o por el titular del centro
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica en entornos controlados o contextos específicos la compartición, gestión e intercambio seguro de recursos utilizando los formatos y estándares apropiados"
                - indicador: 2
                  titulo: "Aplica, con ayuda de un mentor, el sistema de catalogación establecido por la AE o por el titular del centro en sus plataformas y servicios para indizar contenidos educativos digitales introduciendo metadatos y empleando las etiquetas adecuadas"
                - indicador: 3
                  titulo: "Selecciona, con ayuda de un mentor, los roles y permisos de los CMS, repositorios, bases de datos (BBDD) y CLMS del centro para compartir de forma selectiva los contenidos educativos digitales con los distintos agentes de la comunidad educativa"
              afirmaciones_desempeño: Aplico las medidas de seguridad establecidas, con ayuda de otros docentes, en la compartición, gestión e intercambio de contenidos educativos digitales configurando de forma selectiva los accesos en entornos controlados e identificando los contenidos empleando los sistemas establecidos por la AE o titular del centro para la catalogación y etiquetado
        - etapa: B
          titulo: Uso de sistemas de catalogación y de plataformas de gestión, intercambio y compartición de contenidos educativos digitales
          niveles:
            - nivel: B1
              titulo: Adopción de estándares para la publicación y catalogación de contenidos educativos digitales y uso convencional y autónomo de los CMS, repositorios, BBDD y CLMS
              indicadores_logro:
                - indicador: 1
                  titulo: "Adopta el sistema de catalogación e inserción de metadatos establecido por la AE o por el titular del centro para la identificación e indización de los contenidos educativos digitales"
                - indicador: 2
                  titulo: "Emplea, de forma convencional y autónoma, los repositorios de contenidos digitales educativos establecidos por la AE o por el titular del centro para compartir de forma segura y selectiva dichos contenidos con los diferentes agentes de su comunidad educativa"
                - indicador: 3
                  titulo: "Utiliza formatos estandarizados para la compartición de contenidos educativos digitales"
              afirmaciones_desempeño: Utilizo los entornos digitales señalados en el plan digital del centro para compartir los contenidos en función de sus destinatarios y de su finalidad, adoptando estrategias adecuadas para la compartición, gestión e intercambio de contenidos educativos digitales
  - area: 3
    titulo: Enseñanza y aprendizaje
    competencias:
    - competencia: 3.1
      titulo: Enseñanza
      descripcion: Integrar en las programaciones didácticas el uso de las tecnologías digitales, de forma creativa, segura y crítica para mejorar la eficacia de las prácticas docentes. Gestionar y coordinar adecuadamente las intervenciones didácticas digitales, asegurando el funcionamiento de los dispositivos, recursos y servicios durante la implementación de la programación didáctica. Desarrollar y experimentar con nuevos formatos y métodos pedagógicos para la enseñanza y para el aprendizaje
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada para la integración de los recursos digitales en la práctica docente de forma planificada
          niveles:
            - nivel: A1
              titulo: Inclusión de las tecnologías digitales en la programación didáctica
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce distintos modelos pedagógicos y de integración de las tecnologías digitales, coherentes con dichos modelos, para desempeñar la función docente"
                - indicador: 2
                  titulo: "Integra de forma selectiva (adecuación a los objetivos, contenidos, alumnado, etc.) recursos digitales en el diseño de una programación didáctica"
                - indicador: 3
                  titulo: "Conoce las características básicas de distintos recursos educativos digitales y sus posibilidades de uso en la práctica docente y los utiliza en situaciones simuladas presenciales o en línea"
              afirmaciones_desempeño: Conozco los recursos digitales, los selecciono en función de los objetivos de aprendizaje y de las características del contexto educativo, los integro en la programación didáctica siguiendo modelos teóricos concretos y los habilito para su uso
            - nivel: A2
              titulo: Diseño de la programación didáctica e implementación en el aula, de forma guiada, utilizando las tecnologías digitales disponibles en el centro
              indicadores_logro:
                - indicador: 1
                  titulo: "Integra de forma selectiva (adecuación a los objetivos, aprendizajes, alumnado, etc.) los recursos digitales disponibles en el centro en la programación didáctica con ayuda de otros docentes, siguiendo el modelo pedagógico recogido en el proyecto educativo"
                - indicador: 2
                  titulo: "Aplica las programaciones didácticas en su práctica docente resolviendo, con ayuda, aquellos problemas que puedan surgir a la hora de utilizar las tecnologías digitales durante su desarrollo"
              afirmaciones_desempeño: Aplico la programación didáctica usando los recursos tecnológicos disponibles en el centro con apoyo de otros docentes y resuelvo problemas sencillos que puedan surgir durante el desarrollo de la clase
        - etapa: B
          titulo: Gestión autónoma y adaptación creativa de las intervenciones didácticas empleando recursos digitales
          niveles:
            - nivel: B1
              titulo: Uso autónomo, en la práctica docente, de las tecnologías digitales incorporadas en la programación didáctica
              indicadores_logro:
                - indicador: 1
                  titulo: "Integra de forma selectiva los recursos digitales disponibles en el centro en la programación didáctica siguiendo el modelo pedagógico recogido en el proyecto educativo"
                - indicador: 2
                  titulo: "Adopta un uso convencional y autónomo de los recursos digitales disponibles en el centro seleccionándolos en función de sus características y del contexto educativo y de la modalidad de enseñanza (presencial, en línea, a distancia, híbrida o mixta)"
                - indicador: 3
                  titulo: "Valora, durante su uso, la idoneidad de los recursos digitales empleados habitualmente para la consecución de los objetivos de aprendizaje por parte del alumnado"
                - indicador: 4
                  titulo: "Resuelve los problemas más comunes que se puedan presentar en su práctica docente al integrar las tecnologías digitales y afronta los imprevistos con soluciones alternativas"
              afirmaciones_desempeño: Empleo de forma autónoma, en el desarrollo de las clases, los recursos digitales del centro incorporados en la programación didáctica resolviendo los problemas habituales que puedan surgir y gestionando adecuadamente situaciones imprevistas
    - competencia: 3.2
      titulo: Orientación y apoyo en el aprendizaje
      descripcion: Utilizar las tecnologías y servicios digitales, cumpliendo con las medidas de seguridad y protección de datos, para mejorar la interacción individual y colectiva con el alumnado, dentro y fuera de las sesiones de aprendizaje. Emplear las tecnologías digitales para ofrecer orientación y asistencia pertinente y específica. Desarrollar y experimentar nuevas vías y formatos para ofrecer orientación y apoyo, respetando los derechos digitales de todo el alumnado y evitando cualquier tipo de discriminación o sesgo
      etapas:
        - etapa: A
          titulo: Conocimiento y comprensión del uso de las tecnologías digitales para apoyar y orientar al alumnado durante los procesos de aprendizaje
          niveles:
            - nivel: A1
              titulo: Conocimiento de las tecnologías digitales para la comunicación e interacción en situaciones de enseñanza y aprendizaje y sistemas de monitorización de la participación del alumnado con el fin de prestarle apoyo en este proceso
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce un repertorio variado de tecnologías digitales que permiten interactuar y comunicarse para ofrecer apoyo y retroalimentación selectiva al alumnado en su proceso de aprendizaje y comprende los principios básicos de su funcionamiento y los criterios pedagógicos con los que se deben utilizar"
                - indicador: 2
                  titulo: "Conoce algunas herramientas y recursos digitales de monitorización que permiten detectar las necesidades de apoyo del alumnado durante el proceso de aprendizaje"
                - indicador: 3
                  titulo: "Identifica, desde el punto de vista teórico, los problemas de aprendizaje más frecuentes que se pueden dar a la hora de alcanzar un determinado objetivo de aprendizaje y propone soluciones empleando tecnologías digitales"
                - indicador: 4
                  titulo: "Aplica la normativa sobre protección de datos a la hora de seleccionar tecnologías de comunicación, interacción y monitorización en contextos didácticos"
              afirmaciones_desempeño: Conozco la utilidad y funcionamiento de diversas tecnologías digitales (comunicación, interacción y monitorización) para ofrecer apoyo y orientación al alumnado durante su aprendizaje, tanto de forma individual como colectiva
            - nivel: A2
              titulo: Uso, con asesoramiento, de las tecnologías digitales de comunicación, interacción y monitorización, disponibles en el centro, para orientar y reconducir los procesos de aprendizaje del alumnado
              indicadores_logro:
                - indicador: 1
                  titulo: "Selecciona en función del contexto didáctico y utiliza, con ayuda, las tecnologías digitales de comunicación e interacción proporcionadas por la AE o los titulares del centro para prestar apoyo al alumnado en los procesos de enseñanza-aprendizaje en entornos virtuales o en situaciones presenciales"
                - indicador: 2
                  titulo: "Configura y emplea, con el asesoramiento de otros docentes, las tecnologías digitales proporcionadas por la A. E. o por los titulares del centro para recibir información sobre el aprendizaje del alumnado durante el proceso"
                - indicador: 3
                  titulo: "Incluye, con el asesoramiento y supervisión de otros docentes, orientaciones tanto para la realización de cada tarea como para apoyar los aspectos que puedan presentar mayor dificultad durante el aprendizaje de su alumnado empleando tecnologías digitales"
                - indicador: 4
                  titulo: "Aplica, con ayuda, los protocolos relacionados con la protección de datos y derechos y garantías digitales establecidos por la AE o los titulares del centro al utilizar con su alumnado las tecnologías digitales para la comunicación, interacción o monitorización"
              afirmaciones_desempeño: Utilizo, con el apoyo de otros docentes, las tecnologías digitales (comunicación, interacción y monitorización) proporcionadas por la AE o los titulares del centro para ofrecer apoyo y orientación a mi alumnado durante el proceso de aprendizaje, tanto de forma individual como colectiva
        - etapa: B
          titulo: Uso autónomo y adaptación a nuevos contextos de las tecnologías digitales para ofrecer apoyo y orientación al alumnado durante los procesos de aprendizaje
          niveles:
            - nivel: B1
              titulo: Integración, de forma autónoma, de las tecnologías digitales para comunicarse, interactuar y monitorizar el proceso de aprendizaje con el fin de ofrecer información, orientación y apoyo
              indicadores_logro:
                - indicador: 1
                  titulo: "Interactúa con su alumnado, de forma autónoma y ajustada a sus características y a la situación educativa para ofrecer apoyo y orientación durante el aprendizaje, a través de las tecnologías digitales proporcionadas por la AE o los titulares del centro educativo"
                - indicador: 2
                  titulo: "Utiliza las tecnologías digitales del centro para obtener retroalimentación inmediata sobre la actividad del alumnado y sobre las dificultades que ha encontrado en el proceso de aprendizaje con el fin de intervenir cuando sea necesario"
                - indicador: 3
                  titulo: "Dispone de un procedimiento para incluir las tecnologías digitales, de forma sistemática y adecuada a las características de su alumnado, con el fin de ayudar a superar las dificultades que puedan surgir durante el proceso de adquisición de un aprendizaje concreto"
                - indicador: 4
                  titulo: "Aplica, de forma autónoma, los protocolos relacionados con la protección de datos y derechos y garantías digitales establecidos por la AE o los titulares del centro al utilizar con su alumnado las tecnologías digitales para la comunicación, interacción o monitorización"
              afirmaciones_desempeño: Integro en mi práctica docente las tecnologías digitales proporcionadas por la AE o por los titulares del centro que me permiten monitorizar, apoyar y reconducir los aprendizajes de mi alumnado durante el proceso, siguiendo los protocolos sobre protección de datos establecidos en el plan digital del centro
    - competencia: 3.3
      titulo: Aprendizaje entre iguales
      descripcion: Seleccionar y utilizar tecnologías digitales seguras para mejorar el aprendizaje del alumnado a través de la colaboración. Proporcionar estrategias al alumnado para utilizar las tecnologías digitales de comunicación y cooperación con el fin de enriquecer los procesos de aprendizaje y desarrollar su capacidad de aprender a aprender entre iguales
      etapas:
        - etapa: A
          titulo: Conocimiento y uso guiado de tecnologías digitales para promover el aprendizaje entre iguales
          niveles:
            - nivel: A1
              titulo: Conocimiento teórico de los criterios didácticos para la utilización de herramientas digitales de colaboración en el aula
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce diversos modelos teóricos y estrategias de aprendizaje entre iguales y los criterios pedagógicos y de seguridad para la selección de las tecnologías digitales que permitirían desarrollarlos"
                - indicador: 2
                  titulo: "Utiliza, en contextos formativos, algunas herramientas digitales que potencian el aprendizaje entre iguales y las configura de forma que se adecúen al objetivo fijado"
              afirmaciones_desempeño: Conozco diversos modelos pedagógicos para desarrollar el aprendizaje entre iguales y el modo en el que las tecnologías digitales permiten implementarlos y enriquecerlos en contextos formativos
            - nivel: A2
              titulo: Aplicación guiada de estrategias para potenciar el aprendizaje entre iguales empleando de forma segura tecnologías digitales
              indicadores_logro:
                - indicador: 1
                  titulo: Diseña e implementa, con ayuda de otros docentes, actividades o situaciones de aprendizaje entre iguales empleando, a partir del análisis de sus funcionalidades, las tecnologías digitales de colaboración disponibles en el centro, aplicando los protocolos de protección y seguridad de su uso
              afirmaciones_desempeño: Diseño e implemento, con ayuda de otros docentes, actividades de carácter colaborativo o cooperativo para potenciar el aprendizaje entre iguales empleando las tecnologías digitales disponibles en el centro, proporcionadas por la AE o por sus titulares
        - etapa: B
          titulo: Integración en la práctica docente de las tecnologías digitales para promover y desarrollar el aprendizaje entre iguales
          niveles:
            - nivel: B1
              titulo: Aplicación de las tecnologías digitales para implementar, en el aula, las actividades de aprendizaje entre iguales incluidas en la programación didáctica
              indicadores_logro:
                - indicador: 1
                  titulo: "Configura, de forma autónoma, las funcionalidades de las tecnologías digitales proporcionadas por la AE o por los titulares del centro que son más apropiadas para implementar o apoyar las actividades de aprendizaje entre iguales adaptadas a las características de su alumnado"
                - indicador: 2
                  titulo: "Proporciona a su alumnado orientaciones e instrucciones contextualizadas que les facilitan el desarrollo de actividades de aprendizaje entre iguales dentro del aula, usando tecnologías digitales"
              afirmaciones_desempeño: Configuro el uso de las tecnologías digitales para que mi alumnado pueda desarrollar las actividades programadas de aprendizaje entre iguales, incluyendo orientaciones para su adecuada utilización
    - competencia: 3.4
      titulo: Aprendizaje autorregulado
      descripcion: Utilizar las tecnologías digitales para favorecer en el alumnado la metacognición, a través de la reflexión sobre el propio aprendizaje y el desarrollo de las acciones estratégicas para planificar, supervisar, contrastar ideas, solicitar ayuda y documentar los procesos de aprendizaje realizados
      etapas:
        - etapa: A
          titulo: Conocimiento teórico y utilización práctica de las tecnologías digitales aplicadas al aprendizaje autorregulado en situaciones educativas
          niveles:
            - nivel: A1
              titulo: Conocimiento teórico y utilización práctica de las tecnologías digitales en situaciones de aprendizaje autorregulado
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los fundamentos teóricos del aprendizaje autorregulado (estrategias de cognición, metacognición, pensamiento y técnicas de estudio) e identifica las tecnologías digitales que pueden emplearse en contextos educativos para el desarrollo del aprendizaje autónomo"
                - indicador: 2
                  titulo: "Conoce y utiliza las tecnologías digitales para gestionar y organizar el propio aprendizaje"
              afirmaciones_desempeño: Conozco los fundamentos teóricos del aprendizaje autorregulado y el modo en que, a partir de mi propia experiencia formativa, las tecnologías digitales pueden contribuir a su progresivo desarrollo
            - nivel: A2
              titulo: Aplicación, con asesoramiento, de las tecnologías digitales disponibles en el centro para desarrollar el aprendizaje autorregulado del alumnado
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce las tecnologías digitales proporcionadas por la AE o los titulares del centro que podrían ser empleadas por el alumnado para el desarrollo del aprendizaje autorregulado"
                - indicador: 2
                  titulo: "Incorpora, con asesoramiento, actividades en las que se aplican estrategias de aprendizaje autorregulado mediante tecnologías digitales en las sesiones lectivas"
              afirmaciones_desempeño: Incorporo en mi práctica docente, con apoyo, tareas que permiten que el alumnado aplique diversas estrategias de aprendizaje autorregulado utilizando las tecnologías digitales del centro
        - etapa: B
          titulo: Integración en el proceso de enseñanza-aprendizaje de las estrategias de aprendizaje autorregulado empleando las tecnologías digitales en función del contexto de aprendizaje
          niveles:
            - nivel: B1
              titulo: Adopción e implementación autónoma de actividades y tareas que requieren el uso de tecnologías digitales para mejorar el aprendizaje autorregulado del alumnado
              indicadores_logro:
                - indicador: 1
                  titulo: "Implementa en el aula, de forma autónoma, las tareas adaptadas al grado de desarrollo madurativo de su alumnado que le permiten la planificación, la documentación, registro y consulta de su aprendizaje mediante el uso de las tecnologías digitales"
                - indicador: 2
                  titulo: "Incorpora, de forma sistemática y en función del contexto educativo, actividades de reflexión cognitiva y metacognitiva del alumnado utilizando tecnologías digitales"
              afirmaciones_desempeño: Incorporo en la programación e implemento de forma autónoma en el aula actividades adaptadas a la madurez de mi alumnado que incentivan su reflexión cognitiva y metacognitiva y le facilitan la planificación y gestión de su aprendizaje empleando las tecnologías digitales del centro
  - area: 4
    titulo: Evaluación y retroalimentación
    competencias:
    - competencia: 4.1
      titulo: Estrategias de evaluación
      descripcion: Utilizar las tecnologías digitales para el diseño de los medios e instrumentos de evaluación diagnóstica, formativa y sumativa e implementarlos cumpliendo con las medidas de seguridad y protección de datos personales. Mejorar la diversidad e idoneidad de los formatos y enfoques de evaluación
      etapas:
        - etapa: A
          titulo: Conocimiento teórico y uso guiado de las tecnologías digitales para evaluar los procesos de enseñanza y aprendizaje
          niveles:
            - nivel: A1
              titulo: Conocimiento de las técnicas, medios e instrumentos para la evaluación de los procesos de enseñanza y aprendizaje empleando tecnologías digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce y configura las herramientas digitales más comunes atendiendo a las distintas funciones de la evaluación de la enseñanza y el aprendizaje (diagnóstica, formativa y sumativa)"
                - indicador: 2
                  titulo: "Diseña actividades de evaluación en las que el alumnado emplea medios digitales para llevarlas a cabo"
                - indicador: 3
                  titulo: Conoce la normativa sobre protección de datos personales y el modo en que afecta a los procesos de recogida de información empleando tecnologías digitales
              afirmaciones_desempeño: Conozco el uso que se puede hacer de las tecnologías digitales para apoyar la evaluación diagnóstica, formativa y sumativa de los procesos de enseñanza y aprendizaje en función de las técnicas e instrumentos seleccionados y adoptando medidas para proteger los datos personales
            - nivel: A2
              titulo: Uso tutelado de las tecnologías digitales proporcionadas por las AAEE o por los titulares del centro para la evaluación diagnóstica, formativa y sumativa de los procesos de enseñanza y aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: Aplica, de forma guiada, las tecnologías digitales de evaluación proporcionadas por la AE o los titulares del centro para la recogida de información sobre los indicadores fijados en la programación didáctica
                - indicador: 2
                  titulo: Usa, de forma tutelada, las tecnologías digitales del centro para diseñar un repertorio diversificado de medios (actitudes, producciones y desempeños del alumnado) que le permitan hacer un adecuado seguimiento del aprendizaje y detectar posibles necesidades del alumnado
                - indicador: 3
                  titulo: Diseña y utiliza, con ayuda de otros docentes, algún instrumento de evaluación de su práctica docente empleando las tecnologías digitales del centro
                - indicador: 4
                  titulo: Conoce y aplica bajo supervisión el protocolo de protección de datos del centro en los procedimientos de evaluación en los que se hace uso de las tecnologías digitales
              afirmaciones_desempeño: Utilizo, de forma tutelada y siguiendo el protocolo de seguridad establecido por la AE o los titulares del centro, las herramientas digitales proporcionadas para llevar a cabo la evaluación de los procesos de enseñanza y aprendizaje contemplados en la programación didáctica
        - etapa: B
          titulo: Aplicación autónoma y adaptación a nuevos contextos de los medios e instrumentos digitales de evaluación de los procesos de enseñanza y aprendizaje
          niveles:
            - nivel: B1
              titulo: Utilización de las tecnologías digitales de evaluación disponibles en el centro de forma autónoma
              indicadores_logro:
                - indicador: 1
                  titulo: "Utiliza de forma autónoma las plataformas digitales de evaluación proporcionadas por la AE o los titulares del centro"
                - indicador: 2
                  titulo: "Diversifica las técnicas, los medios y los instrumentos de evaluación del aprendizaje de su alumnado y de su práctica docente empleando, de forma autónoma, las tecnologías digitales del centro"
                - indicador: 3
                  titulo: Aplica de forma autónoma los protocolos de seguridad y protección de datos personales del centro en los procesos de evaluación
              afirmaciones_desempeño: Utilizo las tecnologías digitales de evaluación del centro, de forma autónoma, siguiendo los protocolos establecidos sobre protección de datos personales
    - competencia: 4.2
      titulo: Analíticas y evidencias de aprendizaje
      descripcion: Generar, almacenar, validar, seleccionar, analizar e interpretar las evidencias digitales sobre la actividad, el rendimiento y el progreso del alumnado con el fin de mejorar el proceso de enseñanza y el aprendizaje, respetando la normativa vigente en cuanto a protección de datos
      etapas:
        - etapa: A
          titulo: Conocimiento de los medios digitales para la gestión e interpretación de los datos procedentes de la evaluación educativa bajo criterios éticos y pedagógicos y aplicación tutelada de los procedimientos
          niveles:
            - nivel: A1
              titulo: Conocimiento del uso de las tecnologías digitales para obtener, tratar, visualizar, analizar e interpretar los datos recogidos en la evaluación de los procesos de enseñanza y aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: "Comprende los conceptos y procedimientos básicos de análisis estadístico y usa las tecnologías digitales para tratarlos y visualizarlos"
                - indicador: 2
                  titulo: "Conoce los estándares comunes de interoperabilidad y las técnicas, instrumentos y medios para la validación, importación/exportación almacenamiento y agregación de datos"
                - indicador: 3
                  titulo: "Determina, en situaciones hipotéticas, las variables relevantes para evaluar una situación de enseñanza y aprendizaje a través de la obtención de datos mediante tecnologías digitales"
                - indicador: 4
                  titulo: "Conoce la normativa aplicable a la protección de datos personales a la hora de recoger métricas de aprendizaje y de interacciones en plataformas"
              afirmaciones_desempeño: Conozco, de forma teórica, el procedimiento a seguir para recabar, tratar, almacenar, analizar e interpretar datos obtenidos mediante el uso de tecnologías digitales para la evaluación de los procesos de enseñanza y aprendizaje y la normativa sobre protección de datos personales aplicable en este ámbito
            - nivel: A2
              titulo: Aplicación tutelada de los conocimientos sobre análisis de datos para la evaluación de los procesos de enseñanza y aprendizaje generados mediante los programas del centro
              indicadores_logro:
                - indicador: 1
                  titulo: Utiliza, con el asesoramiento de otros docentes, las tecnologías digitales proporcionadas por la AE o los titulares del centro para obtener, importar/exportar, almacenar, tratar, visualizar e interpretar los datos relacionados con la evaluación del proceso de enseñanza y aprendizaje
                - indicador: 2
                  titulo: Selecciona, con la guía de otros profesionales, los datos que pueden ser relevantes para evaluar un proceso de enseñanza o aprendizaje concreto empleando las tecnologías digitales del centro
                - indicador: 3
                  titulo: Aplica, bajo supervisión, los protocolos de seguridad y protección de datos establecidos para el uso de las tecnologías digitales en los tratamientos de datos vinculados a la evaluación de los procesos de enseñanza y aprendizaje
              afirmaciones_desempeño: Utilizo, con el apoyo de otro profesorado, las tecnologías digitales facilitadas por la AE o los titulares del centro para gestionar e interpretar los datos relacionados con la evaluación de los procesos de enseñanza y aprendizaje aplicando los protocolos de seguridad y protección de datos personales
        - etapa: B
          titulo: Uso autónomo de las tecnologías digitales de análisis de datos del centro, en los procesos de evaluación de la enseñanza y el aprendizaje, y transferencia de su aplicación a nuevas estrategias educativas
          niveles:
            - nivel: B1
              titulo: Uso autónomo de las tecnologías digitales del centro para gestionar e interpretar los datos en los procesos de enseñanza y aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: Utiliza las tecnologías digitales proporcionadas por la AE o los titulares del centro para obtener, importar/exportar, almacenar, tratar, visualizar e interpretar los datos relacionados con la evaluación del proceso de enseñanza y aprendizaje
                - indicador: 2
                  titulo: Selecciona los datos que pueden ser relevantes para evaluar un proceso de enseñanza o aprendizaje concreto empleando las tecnologías digitales del centro
                - indicador: 3
                  titulo: Aplica de forma autónoma los protocolos de protección de datos y de seguridad del centro para los tratamientos de datos vinculados a los procesos de evaluación
              afirmaciones_desempeño: Empleo de forma autónoma y aplicando los protocolos de protección de datos las tecnologías digitales facilitadas por la AE o por los titulares del centro para recabar, almacenar, tratar estadísticamente e interpretar los datos sobe la evaluación de los procesos de enseñanza y aprendizaje
    - competencia: 4.3
      titulo: Retroalimentación y toma de decisiones
      descripcion: Utilizar las tecnologías digitales para ofrecer retroalimentación al alumnado respetando la privacidad y seguridad de la información aportada. Adaptar las estrategias de enseñanza y proporcionar refuerzo específico a partir de los datos obtenidos. Informar al alumnado y a las familias y facilitar la comprensión de las evidencias de aprendizaje aportadas por las tecnologías digitales para que sean utilizadas en la toma de decisiones
      etapas:
        - etapa: A
          titulo: Conocimiento de las tecnologías digitales empleadas para informar sobre los procesos de evaluación y orientar en consecuencia la enseñanza y el aprendizaje
          niveles:
            - nivel: A1
              titulo: Conocimiento teórico del uso de las tecnologías digitales para informar sobre los procesos de evaluación y orientar la enseñanza y el aprendizaje a partir de dichas valoraciones
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los criterios pedagógicos, didácticos, técnicos y éticos que han de aplicarse a la hora de seleccionar las tecnologías digitales empleadas para, en función de su finalidad y destinatarios, elaborar y transmitir la información, tanto cuantitativa como cualitativa, sobre la evaluación"
                - indicador: 2
                  titulo: "Conoce la normativa sobre protección de datos, privacidad y derechos digitales que afecta a los tratamientos de datos de la evaluación académica"
              afirmaciones_desempeño: Conozco las posibilidades que ofrecen las tecnologías digitales para informar sobre los distintos procesos de evaluación al alumnado y a las familias y para proporcionar retroalimentación que permita mejorar el aprendizaje y adaptar la práctica docente
            - nivel: A2
              titulo: Selección y uso tutelado de las tecnologías digitales del centro para tomar decisiones, a partir de los datos obtenidos en el proceso de evaluación, y ofrecer retroalimentación, información y orientaciones sobre la enseñanza y el aprendizaje en función de su finalidad y destinatarios
              indicadores_logro:
                - indicador: 1
                  titulo: "Utiliza, con apoyo y bajo supervisión, las tecnologías digitales proporcionadas por la AE o por los titulares del centro para tomar decisiones sobre la enseñanza y el aprendizaje a partir de los datos obtenidos en los procesos de evaluación"
                - indicador: 2
                  titulo: "Aplica, con asesoramiento, criterios pedagógicos, didácticos, éticos y técnicos a la hora de seleccionar las tecnologías digitales para informar y ofrecer retroalimentación y orientaciones al alumnado y las familias sobre el proceso de aprendizaje"
                - indicador: 3
                  titulo: "Emplea, bajo la guía de otros docentes, el protocolo del centro a la hora de utilizar las tecnologías digitales para informar sobre los procesos de evaluación y de ofrecer o planificar orientaciones y adaptaciones que mejoren la enseñanza y el aprendizaje"
              afirmaciones_desempeño: Empleo, con la ayuda de otros docentes, las tecnologías digitales facilitadas por la AE o por los titulares del centro para informar y ofrecer retroalimentación sobre los procesos de evaluación aplicando los protocolos establecidos
        - etapa: B
          titulo: Uso autónomo de las tecnologías digitales del centro para tomar decisiones y ofrecer retroalimentación, información y orientaciones sobre el desarrollo de los procesos de enseñanza y aprendizaje a partir de los datos obtenidos en los procesos de evaluación
          niveles:
            - nivel: B1
              titulo: Uso autónomo y selectivo de las tecnologías digitales del centro para ofrecer retroalimentación, informar y orientar la enseñanza y el aprendizaje a partir de los datos obtenidos en los distintos procesos de evaluación
              indicadores_logro:
                - indicador: 1
                  titulo: "Emplea de forma autónoma criterios pedagógicos, didácticos, técnicos, éticos y de materia para tomar decisiones sobre la orientación de los procesos de enseñanza y aprendizaje fundadas en los datos obtenidos mediante el uso de las tecnologías digitales en los distintos procesos de evaluación"
                - indicador: 2
                  titulo: "Comunica al centro, al equipo docente y de apoyo, al alumnado y a sus familias, según proceda, los resultados de los distintos procesos de evaluación a través de las tecnologías digitales siguiendo los protocolos establecidos por la AE o por los titulares del centro"
                - indicador: 3
                  titulo: "Aplica los protocolos de protección de datos personales y seguridad establecidos por la AE y por el centro en el uso de las tecnologías digitales para el tratamiento de los informes relativos a la evaluación"
              afirmaciones_desempeño: Aplico los protocolos y empleo de forma autónoma las tecnologías digitales proporcionadas por la AE o los titulares del centro para tomar decisiones, ofrecer retroalimentación, informar y orientar los procesos de enseñanza y aprendizaje a partir de los datos obtenidos en los procesos de evaluación
  - area: 5
    titulo: Empoderamiento del alumnado
    competencias:
    - competencia: 5.1
      titulo: Accesibilidad e inclusión
      descripcion: Emplear las tecnologías digitales para facilitar el aprendizaje de todo el alumnado eliminando las barreras contextuales para su presencia, participación y progreso. Garantizar la accesibilidad física, sensorial y cognitiva a los recursos digitales. Adoptar medidas que promuevan la equidad y permitan reducir o compensar la brecha digital y el impacto de las desigualdades socioculturales y económicas en el aprendizaje
      etapas:
        - etapa: A
          titulo: Conocimiento de las soluciones tecnológicas existentes para lograr la accesibilidad universal e incorporación de las mismas en la práctica educativa
          niveles:
            - nivel: A1
              titulo: Conocimiento del uso pedagógico de las tecnologías digitales para facilitar la accesibilidad e inclusión de todo el alumnado
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce el funcionamiento de los recursos tecnológicos existentes en el ámbito educativo para facilitar la accesibilidad universal y el modo de integrar su uso en la práctica educativa"
                - indicador: 2
                  titulo: "Comprende los efectos positivos y negativos a la hora de incluir las tecnologías digitales en la enseñanza y el aprendizaje"
                - indicador: 3
                  titulo: "Conoce los principios de accesibilidad universal y la aplicación pedagógica de las tecnologías digitales para la inclusión de todo el alumnado, así como la normativa vigente al respecto"
              afirmaciones_desempeño: Conozco los principios de accesibilidad universal y el uso pedagógico de las tecnologías digitales para la inclusión de todo el alumnado, así como la normativa vigente al respecto
            - nivel: A2
              titulo: Utilización con ayuda de los principios de accesibilidad universal e inclusión en su práctica docente mediante tecnologías digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Selecciona y utiliza, en entornos controlados o con asesoramiento, opciones básicas de accesibilidad con la tecnología presente en el centro"
                - indicador: 2
                  titulo: "Conoce los protocolos y medidas para reducir la brecha digital adoptados en el centro y/o por la AE y los aplica con la guía de otros docentes"
              afirmaciones_desempeño: Selecciono y utilizo, en entornos controlados o con asesoramiento, las opciones básicas de accesibilidad de las tecnologías digitales del centro y colaboro en la aplicación de las medidas previstas para compensar la brecha digital del alumnado escolarizado
        - etapa: B
          titulo: Aplicación de soluciones de accesibilidad universal al utilizar las tecnologías digitales en la práctica docente para responder a la diversidad de alumnado
          niveles:
            - nivel: B1
              titulo: Adopción de un uso convencional y autónomo de las tecnologías digitales proporcionadas por la AE o por los titulares del centro, respetando los principios de accesibilidad e inclusión
              indicadores_logro:
                - indicador: 1
                  titulo: "Utiliza de forma autónoma las opciones de accesibilidad de la tecnología del centro, seleccionando aquellas más adecuadas para su alumnado"
                - indicador: 2
                  titulo: "Colabora en la implementación de las medidas adoptadas por la AE, y por el centro para compensar la brecha digital y promover la inclusión educativa de todo el alumnado en el uso de las tecnologías digitales"
              afirmaciones_desempeño: Conozco, selecciono, configuro y uso, en mi práctica docente, las tecnologías digitales de mi centro de manera que facilito el acceso de mi alumnado a la educación, compensando las desigualdades existentes
    - competencia: 5.2
      titulo: Atención a las diferencias personales en el aprendizaje
      descripcion: Utilizar las tecnologías digitales para atender las diferencias del alumnado, garantizando sus derechos digitales, de forma que todos puedan alcanzar los objetivos de aprendizaje
      etapas:
        - etapa: A
          titulo: Conocimiento de los recursos digitales para responder a las necesidades individuales de aprendizaje del alumnado bajo criterios éticos y pedagógicos
          niveles:
            - nivel: A1
              titulo: Conocimiento teórico de las funcionalidades de las tecnologías digitales para responder a las necesidades individuales del alumnado y de los criterios pedagógicos para su uso
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los criterios pedagógicos que han de aplicarse al utilizar las tecnologías digitales para atender a los distintos tipos de necesidades de aprendizaje del alumnado"
                - indicador: 2
                  titulo: "Configura funcionalidades básicas en plataformas de aprendizaje para desarrollar distintas estrategias pedagógicas de personalización de los procesos de aprendizaje"
                - indicador: 3
                  titulo: "Comprende, en términos generales, los principios del funcionamiento de las tecnologías digitales que emplean desarrollos de inteligencia artificial (IA) y conoce la normativa aplicable y los riesgos éticos y pedagógicos que puede entrañar su utilización"
              afirmaciones_desempeño: Conozco y comprendo el funcionamiento de las tecnologías digitales que permiten responder a las necesidades individuales de aprendizaje, así como los criterios éticos y pedagógicos que deben guiar su uso
            - nivel: A2
              titulo: Uso supervisado de las tecnologías digitales del centro para responder a las necesidades personales de aprendizaje del alumnado
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los recursos digitales disponibles en el centro y los utiliza con ayuda para atender a las necesidades personales de aprendizaje del alumnado aplicando un repertorio variado de estrategias siguiendo criterios éticos y pedagógicos"
                - indicador: 2
                  titulo: "Identifica y comprende, asesorado por otros profesionales, los algoritmos que emplean las tecnologías digitales proporcionadas por la AE o por los titulares del centro, que utilizan datos del alumnado, para personalizar de forma automatizada los procesos de aprendizaje"
              afirmaciones_desempeño: Comprendo el funcionamiento y utilizo, con ayuda, las tecnologías digitales proporcionadas por la AE o por los titulares del centro que permiten dar respuesta a las necesidades personales de aprendizaje siguiendo criterios éticos y pedagógicos
        - etapa: B
          titulo: Uso de los recursos digitales y diseño de estrategias para dar respuesta a las necesidades del alumnado siguiendo criterios éticos y pedagógicos con objeto de que alcance los objetivos de aprendizaje
          niveles:
            - nivel: B1
              titulo: Utilización autónoma de las tecnologías digitales en el desempeño docente para responder a la diversidad de necesidades de aprendizaje del alumnado
              indicadores_logro:
                - indicador: 1
                  titulo: "Utiliza los recursos digitales disponibles en su centro para incorporarlos de forma selectiva e inclusiva en su programación didáctica"
                - indicador: 2
                  titulo: "Identifica los parámetros y modelos pedagógicos asociados a las tecnologías digitales proporcionadas por la A. E. o por los titulares del centro para dar respuestas personalizadas en los procesos de aprendizaje y el uso que se realiza de la IA para ofrecer estas respuestas"
              afirmaciones_desempeño: Utilizo de forma autónoma las tecnologías digitales proporcionadas por la AE o por los titulares del centro que permiten generar respuestas de aprendizaje personalizadas en un mismo contexto de enseñanza bajo criterios éticos y pedagógicos
    - competencia: 5.3
      titulo: Compromiso activo del alumnado con su propio aprendizaje
      descripcion: Integrar las tecnologías digitales en estrategias pedagógicas que promuevan el compromiso activo del alumnado con una materia, convirtiéndole en protagonista de su propio aprendizaje e incentivando el desarrollo de operaciones cognitivas complejas y de competencias transversales, como el pensamiento crítico o la creatividad
      etapas:
        - etapa: A
          titulo: Conocimiento teórico y uso tutelado de las tecnologías digitales para favorecer el compromiso activo del alumnado y el desarrollo de las competencias transversales y de operaciones cognitivas complejas
          niveles:
            - nivel: A1
              titulo: Conocimiento y comprensión teórica del modo en que las tecnologías digitales pueden favorecer el compromiso activo del alumnado con su aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce estrategias pedagógicas y usos de la tecnología digital vinculados a la materia, área o enseñanza de su especialidad que permiten promover el desarrollo de operaciones cognitivas complejas y de competencias transversales por parte del alumnado"
                - indicador: 2
                  titulo: "Aplica criterios didácticos en el análisis de las tecnologías digitales vinculadas a la materia y área de su especialidad para determinar cuáles podrían ser empleadas por el alumnado"
                - indicador: 3
                  titulo: "Identifica las características de las tecnologías digitales que permiten introducir elementos para estimular la motivación y el compromiso del alumnado con su aprendizaje"
              afirmaciones_desempeño: Conozco y comprendo cómo las tecnologías digitales favorecen el compromiso activo y la responsabilidad del alumnado en su propio aprendizaje, estimulando su motivación, desarrollando competencias transversales y resolviendo tareas que impliquen el uso de operaciones cognitivas complejas
            - nivel: A2
              titulo: Utilización de estrategias pedagógicas para desarrollar el compromiso activo del alumnado con su aprendizaje basadas en el uso de las tecnologías digitales en entornos controlados o de forma guiada
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, con apoyo y en función del contexto, de las características concretas del alumnado, del objetivo de aprendizaje y de los recursos digitales disponibles en el centro, las tecnologías digitales para que su alumnado desarrolle operaciones cognitivas complejas y competencias transversales en el aprendizaje de una materia o área concreta"
                - indicador: 2
                  titulo: "Selecciona con ayuda de otros docentes, de entre las tecnologías digitales disponibles en el centro, aquellas que pueden ser empleadas por el alumnado en su área o materia de forma progresivamente autónoma"
                - indicador: 3
                  titulo: "Emplea, de forma guiada, las tecnologías digitales del centro para incentivar la motivación y compromiso activo de su alumnado con los objetivos de aprendizaje del área o materia"
              afirmaciones_desempeño: Utilizo y promuevo, por parte de mi alumnado, el uso de las tecnologías digitales disponibles en el centro para aplicar estrategias pedagógicas que permitan la motivación, el compromiso activo del estudiante en sus aprendizajes y el desarrollo de competencias transversales, con el apoyo de otros docentes
        - etapa: B
          titulo: Uso autónomo e integración de las tecnologías digitales para favorecer el compromiso activo del alumnado con su aprendizaje en las distintas áreas y materias y en el desarrollo de las competencias transversales
          niveles:
            - nivel: B1
              titulo: Adopción de un uso convencional y autónomo de las tecnologías digitales que permiten incrementar la motivación, el protagonismo y la responsabilidad del alumnado en su aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, de forma autónoma, estrategias didácticas que, gracias al uso de las tecnologías digitales, promueven el desarrollo de operaciones cognitivas complejas y de las competencias transversales de su alumnado relacionadas con el área o materia"
                - indicador: 2
                  titulo: "Implementa estrategias pedagógicas basadas en la usabilidad y condiciones de acceso de las tecnologías digitales disponibles en el centro para que su alumnado las utilice de una forma progresivamente autónoma en los distintos aprendizajes"
                - indicador: 3
                  titulo: "Emplea, de forma autónoma, los recursos digitales proporcionados por la AE o los titulares del centro que estimulan la motivación y el compromiso con el aprendizaje del alumnado que tiene a su cargo"
              afirmaciones_desempeño: Aplico, de forma autónoma, las tecnologías digitales del centro para incentivar el compromiso activo de mi alumnado motivándole, dándole protagonismo y responsabilidad en el proceso de aprendizaje y apoyándole en un uso progresivamente autónomo de las mismas en un determinado campo de estudio para desarrollar operaciones cognitivas complejas y competencias transversales
  - area: 6
    titulo: Desarrollo de la competencia digital del alumnado
    competencias:
    - competencia: 6.1
      titulo: Alfabetización mediática y en el tratamiento de la información y de los datos
      descripcion: Diseñar, implementar e integrar, en los procesos de enseñanza y aprendizaje, propuestas pedagógicas para el desarrollo y evaluación de la competencia digital del alumnado en alfabetización mediática y en el tratamiento de la información y de los datos
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada de las estrategias pedagógicas para integrar, en los procesos de enseñanza y aprendizaje, los aspectos curriculares de la competencia digital sobre alfabetización mediática y en tratamiento de información y datos del alumnado
          niveles:
            - nivel: A1
              titulo: Conocimiento y comprensión teórica de los aspectos técnicos implicados en la alfabetización mediática y en el tratamiento de información y datos y de los criterios didácticos para su enseñanza y aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce y comprende el funcionamiento de los navegadores, motores de búsqueda, servicios en línea y dispositivos IoT (internet de las cosas) en los procesos de búsqueda, tratamiento y recuperación de la información y de los datos"
                - indicador: 2
                  titulo: "Conoce los criterios didácticos que debe aplicar para que el alumnado sea competente en la búsqueda, selección, evaluación y procesamiento de información y datos relevantes, pertinentes y fiables y el modo en que dicha competencia está integrada en el currículo o plan de estudios"
              afirmaciones_desempeño: Comprendo los principios básicos aplicados en los desarrollos tecnológicos de búsqueda y recuperación de datos e información digital y conozco el modo en que la competencia en alfabetización mediática y en el tratamiento de información y datos está contemplada en el currículo y los criterios didácticos para su desarrollo
            - nivel: A2
              titulo: Aplicación, de forma guiada en contextos reales, de procesos de enseñanza y aprendizaje relativos a la alfabetización mediática y en tratamiento de la información y de los datos
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, con la ayuda de otros docentes, propuestas didácticas para integrar los contenidos, actividades y dinámicas que permiten desarrollar la competencia en alfabetización mediática y en el tratamiento de la información y datos del alumnado, adecuándolos al currículo, al proyecto educativo y al plan digital del centro"
                - indicador: 2
                  titulo: "Contextualiza los conocimientos técnicos sobre gestión de contenidos y configuración de herramientas de búsqueda y tratamiento de la información en el uso de las tecnologías digitales proporcionadas por la AE o los titulares del centro"
              afirmaciones_desempeño: Aplico, de forma guiada, las estrategias didácticas recogidas en la programación y en el plan digital para que el alumnado aprenda a buscar, evaluar y administrar la información y los datos en los entornos digitales proporcionados por la AE o por los titulares del centro
        - etapa: B
          titulo: Diseño e integración de situaciones de aprendizaje para desarrollar la competencia digital del alumnado en tratamiento de la información y de los datos
          niveles:
            - nivel: B1
              titulo: Integración de los aspectos curriculares relativos a la alfabetización del alumnado en el tratamiento de la información y de los datos en los procesos de enseñanza y aprendizaje de forma autónoma
              indicadores_logro:
                - indicador: 1
                  titulo: "Integra en su práctica docente situaciones de aprendizaje en las que el alumnado debe desarrollar diferentes estrategias para la búsqueda, evaluación, selección y organización de la información y de los datos"
                - indicador: 2
                  titulo: "Selecciona, de entre las tecnologías proporcionadas por la AE o por los titulares del centro, las más adecuadas para que el alumnado desarrolle su competencia en tratamiento de la información y de los datos"
              afirmaciones_desempeño: Pongo en práctica diferentes estrategias didácticas para que el alumnado desarrolle su capacidad para buscar, evaluar y administrar la información y los datos procedentes de entornos digitales, adecuando las tecnologías empleadas a sus características
    - competencia: 6.2
      titulo: Comunicación, colaboración y ciudadanía digital
      descripcion: Diseñar, implementar e integrar, en los procesos de enseñanza y aprendizaje, propuestas pedagógicas para el desarrollo y evaluación de la competencia digital del alumnado en la comunicación y colaboración, empleando tecnologías y respetando la etiqueta digital, así como para la construcción de una ciudadanía e identidad digital responsables
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación, en entornos controlados, de propuestas pedagógicas para integrar en los procesos de enseñanza y aprendizaje los aspectos curriculares de la competencia digital del alumnado sobre comunicación y colaboración y sobre ciudadanía e identidad digital
          niveles:
            - nivel: A1
              titulo: Conocimiento y comprensión teórica de los aspectos implicados en los procesos de comunicación y colaboración en entornos digitales y de los criterios didácticos para que el alumnado aprenda a emplear estas herramientas y a construir su ciudadanía e identidad digital de forma responsable y segura
              indicadores_logro:
                - indicador: 1
                  titulo: "Comprende el funcionamiento técnico de los sistemas de comunicación y colaboración en entornos digitales para proteger la imagen digital propia y ajena"
                - indicador: 2
                  titulo: "Conoce y comprende las teorías sociológicas y psicológicas que sustentan los diseños de las redes sociales (RRSS) y las plataformas de comunicación y cómo afectan a la conducta de sus usuarios y usuarias"
                - indicador: 3
                  titulo: "Conoce los criterios didácticos que debe aplicar para que el alumnado sea competente a la hora de colaborar, comunicarse y participar en entornos digitales y el modo en que dicha competencia está integrada en el currículo o plan de estudios"
              afirmaciones_desempeño: Comprendo los principios psico-sociológicos y técnicos básicos aplicados en los desarrollos tecnológicos de comunicación y colaboración en entornos digitales y el modo en que la competencia para emplearlos de forma responsable y segura está contemplada en el currículo y los criterios didácticos para su desarrollo
            - nivel: A2
              titulo: Aplicación de propuestas didácticas, de forma guiada, para el desarrollo de las competencias del alumnado para comunicarse, colaborar y participar en entornos digitales, construyendo, de forma progresiva y responsable, su identidad y ciudadanía digital
              indicadores_logro:
                - indicador: 1
                  titulo: "Contextualiza, con ayuda, sus conocimientos técnicos sobre la configuración y uso de las RRSS abiertas para su utilización en situaciones de enseñanza y aprendizaje empleando las plataformas de comunicación y colaboración proporcionadas por la AE o los titulares del centro"
                - indicador: 2
                  titulo: "Conoce las ventajas y los problemas asociados al uso de las plataformas de comunicación, colaboración y participación y aborda ambos aspectos, con ayuda, en actividades de sensibilización de su alumnado"
                - indicador: 3
                  titulo: "Aplica, con la ayuda de otros docentes, propuestas didácticas para integrar los contenidos, actividades y dinámicas que permiten desarrollar el concepto de ciudadanía e identidad digital en su alumnado"
              afirmaciones_desempeño: Aplico, de forma guiada, las estrategias didácticas recogidas en la programación y en el plan digital del centro para que el alumnado aprenda a comunicarse, colaborar y participar de modo seguro y responsable en los entornos digitales
        - etapa: B
          titulo: Diseño e integración de situaciones de aprendizaje para desarrollar la competencia digital del alumnado para la comunicación, colaboración y participación ciudadana y para la creación de su identidad digital
          niveles:
            - nivel: B1
              titulo: Integración de los aspectos curriculares relativos al desarrollo de la competencia digital del alumnado para la comunicación y la colaboración y para el ejercicio de la ciudadanía y la construcción de la identidad digital en los procesos de enseñanza y aprendizaje de forma autónoma
              indicadores_logro:
                - indicador: 1
                  titulo: "Integra en los procesos de enseñanza y aprendizaje situaciones dirigidas a que el alumnado desarrolle su competencia para comunicarse y colaborar empleando tecnologías digitales, ejercer una ciudadanía activa y gestionar de forma responsable su identidad digital"
                - indicador: 2
                  titulo: "Selecciona, de entre las tecnologías proporcionadas por la AE o por los titulares del centro, las más adecuadas para que el alumnado desarrolle su competencia digital para colaborar, comunicarse y participar"
              afirmaciones_desempeño: Pongo en práctica diferentes estrategias didácticas para que el alumnado desarrolle su capacidad para la comunicación, la colaboración, para el ejercicio de la ciudadanía y para la construcción responsable de su identidad digital, adecuando las tecnologías y propuestas empleadas a sus características
    - competencia: 6.3
      titulo: Creación de contenidos digitales
      descripcion: Diseñar, implementar e integrar, en los procesos de enseñanza y aprendizaje, propuestas pedagógicas para el desarrollo y evaluación de la competencia digital del alumnado en la creación y reelaboración de contenidos digitales, incluyendo la programación y los contenidos o funcionalidades para crearlos o editarlos de las tecnologías emergentes, aplicando los derechos de autoría y de propiedad intelectual
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada de las estrategias pedagógicas para integrar en los procesos de enseñanza y aprendizaje los aspectos curriculares de la competencia digital del alumnado para la creación de contenidos digitales
          niveles:
            - nivel: A1
              titulo: Conocimiento y comprensión teórica de los aspectos técnicos implicados en el desarrollo de la competencia digital del alumnado para crear contenidos digitales y de los criterios didácticos para su enseñanza y aprendizaje
              indicadores_logro:
                - indicador: 1
                  titulo: "Utiliza las herramientas de autor más habituales, incluyendo las que hacen uso de IA e IoT en la creación de contenidos digitales"
                - indicador: 2
                  titulo: "Conoce y aplica criterios científicos, técnicos, estéticos y de accesibilidad para determinar la calidad de los contenidos digitales"
                - indicador: 3
                  titulo: "Conoce y aplica la normativa sobre los derechos de autoría y de propiedad intelectual"
                - indicador: 4
                  titulo: "Conoce los criterios didácticos que debe aplicar en la selección de propuestas educativas para que el alumnado sea competente a la hora de crear contenidos digitales y el modo en que dicha competencia está integrada en el currículo o plan de estudios"
              afirmaciones_desempeño: Aplico criterios científicos, técnicos, estéticos y de accesibilidad para determinar la calidad de los contenidos digitales, utilizo las herramientas de autor más habituales y conozco los criterios didácticos que se deben emplear en los procesos de enseñanza y aprendizaje para que el alumnado desarrolle su competencia en la creación de contenidos digitales
            - nivel: A2
              titulo: Aplicación, de forma guiada en contextos reales, de procesos de enseñanza y aprendizaje para desarrollar la competencia del alumnado en la creación de contenidos digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, con la ayuda de otros docentes, propuestas didácticas que permiten desarrollar la competencia para la creación de contenidos digitales adecuándolos al currículo, al proyecto educativo y al plan digital del centro"
                - indicador: 2
                  titulo: "Contextualiza los conocimientos técnicos sobre la creación de contenidos digitales a las herramientas de autor proporcionadas por la AE o los titulares del centro que van a ser empleadas por su alumnado"
                - indicador: 3
                  titulo: "Aplica, con asesoramiento, a las situaciones de enseñanza y aprendizaje el uso por parte de su alumnado de criterios científicos, técnicos, estéticos y de accesibilidad a la creación de contenidos"
              afirmaciones_desempeño: Aplico, de forma guiada, las estrategias didácticas recogidas en la programación y en el plan digital para que el alumnado aprenda a crear contenidos digitales de calidad utilizando las herramientas de autor proporcionadas por la AE o por los titulares del centro
        - etapa: B
          titulo: Diseño e integración de situaciones de aprendizaje para desarrollar la competencia digital del alumnado en la creación de contenidos digitales
          niveles:
            - nivel: B1
              titulo: Integración en los procesos de enseñanza y aprendizaje, de forma autónoma, de los aspectos curriculares relativos al desarrollo de la competencia del alumnado en la creación de contenidos digitales
              indicadores_logro:
                - indicador: 1
                  titulo: "Integra en su práctica docente actividades de aprendizaje que permiten que el alumnado exprese y transmita sus ideas de manera creativa, mediante el uso de herramientas digitales adecuadas, respetando las reglas y licencias de derechos de autor"
                - indicador: 2
                  titulo: "Promueve que el alumnado evalúe sus propios contenidos digitales aplicando de forma reflexiva criterios científicos, estéticos, técnicos y de accesibilidad y formulando propuestas de mejora"
                - indicador: 3
                  titulo: "Selecciona, de entre las tecnologías proporcionadas por la AE o por los titulares del centro, las más adecuadas para que el alumnado desarrolle su competencia en la elaboración de contenidos digitales"
              afirmaciones_desempeño: Pongo en práctica diferentes estrategias didácticas para que el alumnado desarrolle su capacidad para transmitir sus ideas y desarrollar contenidos digitales de manera creativa, adecuando las tecnologías proporcionadas por la AE o por los titulares del centro a sus características
    - competencia: 6.4
      titulo: Uso responsable y bienestar digital
      descripcion: Diseñar, implementar e integrar, en los procesos de enseñanza y aprendizaje, propuestas pedagógicas para el desarrollo y evaluación de la competencia digital del alumnado en el uso seguro, responsable, crítico, saludable y sostenible de las tecnologías digitales
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada de las estrategias pedagógicas para integrar en los procesos de enseñanza y aprendizaje los aspectos curriculares de la competencia digital del alumnado sobre el uso seguro, responsable, crítico, saludable y sostenible a la hora de utilizar las tecnologías digitales
          niveles:
            - nivel: A1
              titulo: Conocimiento y comprensión teórica de los aspectos implicados en la utilización responsable y saludable de las tecnologías digitales y de los criterios didácticos para que el alumnado adquiera hábitos de uso seguro y adopte decisiones reflexivas
              indicadores_logro:
                - indicador: 1
                  titulo: Conoce los criterios didácticos que debe aplicar para que el alumnado desarrolle su competencia en seguridad y bienestar digital adquiriendo los conocimientos, hábitos de uso y valores a ella asociados y el modo en que dicha competencia está integrada en el currículo o plan de estudios
                - indicador: 2
                  titulo: "Conoce y comprende las teorías sociológicas y psicológicas que explican las conductas asociadas a los riesgos para el bienestar físico y emocional más habituales en el uso de Internet y cómo transmitir su comprensión a través de los diseños didácticos"
                - indicador: 3
                  titulo: "Conoce los derechos digitales de los ciudadanos de la UE y la normativa sobre protección de datos personales, las implicaciones legales y éticas del uso de las tecnologías digitales, así como las medidas pedagógicas que debe adoptar para que el alumnado desarrolle un ejercicio efectivo de estos derechos"
              afirmaciones_desempeño: Poseo los conocimientos didácticos, técnicos, normativos, psicológicos y sociológicos necesarios para integrar en los procesos de enseñanza y aprendizaje el desarrollo de la competencia del alumnado para un uso responsable y seguro de las tecnologías digitales
            - nivel: A2
              titulo: Aplicación de propuestas didácticas, de forma guiada, para el desarrollo de la competencia del alumnado en el uso responsable, seguro y sostenible de las tecnologías digitales y para garantizar su bienestar digital
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, con ayuda, los criterios didácticos que debe utilizar para que el alumnado desarrolle su competencia en seguridad y bienestar digital adquiriendo los conocimientos, hábitos de uso y valores a ella asociados siguiendo la programación didáctica y el plan digital del centro"
                - indicador: 2
                  titulo: "Contextualiza, con ayuda, sus conocimientos técnicos para que el alumnado sea capaz de configurar las opciones de privacidad y protección de datos personales disponibles en las tecnologías digitales proporcionadas por la AE o los titulares del centro, así como en sus propios dispositivos y en los servicios que emplea"
              afirmaciones_desempeño: Aplico, de forma guiada, las estrategias didácticas recogidas en la programación y en el plan digital del centro para que el alumnado realice un uso seguro, responsable, crítico, saludable y sostenible de las tecnologías digitales
        - etapa: B
          titulo: Diseño e integración de situaciones de aprendizaje para desarrollar la competencia digital del alumnado para que haga un uso seguro, responsable, crítico, saludable y sostenible de las tecnologías digitales
          niveles:
            - nivel: B1
              titulo: Integración de los aspectos curriculares relativos al desarrollo de la competencia digital del alumnado sobre el uso seguro, responsable, crítico, saludable y sostenible de las tecnologías digitales en los procesos de enseñanza y aprendizaje de forma autónoma
              indicadores_logro:
                - indicador: 1
                  titulo: "Integra en los procesos de enseñanza y aprendizaje situaciones dirigidas a que el alumnado desarrolle los conocimientos, hábitos y valores para hacer un uso seguro, responsable, crítico, saludable y sostenible de las tecnologías digitales"
                - indicador: 2
                  titulo: "Enseña al alumnado a implementar, desde un punto de vista técnico, el protocolo de ciberseguridad establecido en el plan digital de centro en todas las actuaciones en las que ha de hacer uso de las tecnologías digitales y le proporciona pautas para transferir dichas medidas a otros ámbitos"
              afirmaciones_desempeño: Pongo en práctica, de forma autónoma, diferentes estrategias didácticas para que el alumnado realice un uso responsable, seguro, crítico, saludable y sostenible de las tecnologías digitales, tanto dentro como fuera del centro, y aplique los protocolos de ciberseguridad contemplados en el plan digital
    - competencia: 6.5
      titulo: Resolución de problemas
      descripcion: Diseñar, implementar e integrar, en los procesos de enseñanza y aprendizaje, propuestas pedagógicas para el desarrollo y evaluación de la competencia digital del alumnado en la utilización de las tecnologías digitales para resolver problemas cotidianos y desenvolverse, como prosumidor, de forma creativa y crítica en un mundo digitalizado
      etapas:
        - etapa: A
          titulo: Conocimiento y aplicación guiada de las estrategias pedagógicas para integrar en los procesos de enseñanza y aprendizaje los aspectos curriculares de la competencia digital del alumnado para comprender el funcionamiento de las tecnologías y actuar como prosumidor en una sociedad digital
          niveles:
            - nivel: A1
              titulo: Conocimiento y comprensión teórica de los aspectos didácticos implicados en el desarrollo de la competencia del alumnado para que aprenda a utilizar la tecnología como medio para resolver problemas y cubrir sus necesidades en el contexto de una sociedad digital
              indicadores_logro:
                - indicador: 1
                  titulo: "Conoce los criterios didácticos que debe aplicar para que el alumnado desarrolle su competencia digital a la hora de satisfacer necesidades cotidianas y desenvolverse, como usuario, en un mundo digitalizado de forma crítica y el modo en que dicha competencia está integrada en el currículo o plan de estudios"
                - indicador: 2
                  titulo: "Conoce estrategias pedagógicas para desarrollar la competencia del alumnado, como artífice, para hacer un uso práctico, versátil, crítico y creativo de las tecnologías a la hora de llevar a cabo proyectos individuales o colectivos de cualquier tipo"
                - indicador: 3
                  titulo: "Comprende el funcionamiento de las tecnologías digitales y conoce estrategias didácticas para enseñar a otros a resolver problemas vinculados con su uso"
              afirmaciones_desempeño: Poseo los conocimientos didácticos, técnicos y normativos necesarios para integrar en los procesos de enseñanza y aprendizaje el desarrollo de la competencia del alumnado para identificar, comprender y resolver problemas cotidianos y desenvolverse en un mundo digitalizado de forma creativa y crítica empleando las tecnologías
            - nivel: A2
              titulo: Aplicación, de forma guiada, de propuestas didácticas para el desarrollo de la competencia del alumnado para comprender el funcionamiento de las tecnologías y actuar como prosumidor en una sociedad digital
              indicadores_logro:
                - indicador: 1
                  titulo: "Aplica, con ayuda, en los procesos de enseñanza y aprendizaje, criterios didácticos que permiten al alumnado desarrollar su competencia para utilizar como usuario las tecnologías con objeto de satisfacer necesidades cotidianas siguiendo la programación didáctica y el plan digital del centro"
                - indicador: 2
                  titulo: "Conoce estrategias pedagógicas y las aplica con ayuda de otros docentes para que el alumnado desarrolle diversos proyectos, tanto individuales como colectivos, haciendo un uso práctico, versátil, crítico y creativo de las tecnologías digitales"
                - indicador: 3
                  titulo: "Conoce y comprende el funcionamiento de las tecnologías digitales proporcionadas por la AE o los titulares del centro y conoce estrategias didácticas para enseñar a otros a resolver problemas vinculados con su uso"
              afirmaciones_desempeño: Aplico, de forma guiada, las estrategias didácticas recogidas en la programación y en el plan digital del centro para el desarrollo de la competencia del alumnado con el fin de resolver problemas cotidianos y desenvolverse en un mundo digitalizado de forma creativa y crítica empleando las tecnologías proporcionadas por la AE o los titulares del centro
        - etapa: B
          titulo: Diseño e implementación de estrategias pedagógicas para integrar en los procesos de enseñanza y aprendizaje los aspectos curriculares de la competencia del alumnado para comprender el funcionamiento de las tecnologías y actuar como prosumidor en una sociedad digital
          niveles:
            - nivel: B1
              titulo: Integración en los procesos de enseñanza y aprendizaje, de forma autónoma, de los aspectos curriculares relativos al desarrollo de la competencia del alumnado en el uso de las tecnologías digitales para dar respuesta a problemas cotidianos y llevar a la práctica proyectos individuales y colectivos
              indicadores_logro:
                - indicador: 1
                  titulo: "Enseña al alumnado, en función de su edad y grado de madurez, a utilizar las tecnologías digitales para atender necesidades y gestiones cotidianas y le proporciona pautas para transferir dichos aprendizajes a otros ámbitos, de forma que pueda integrarse en una sociedad digital"
                - indicador: 2
                  titulo: "Integra en los procesos de enseñanza y aprendizaje situaciones dirigidas a que el alumnado desarrolle proyectos individuales y colectivos que requieren su propia iniciativa empleando de forma creativa y crítica las tecnologías digitales"
                - indicador: 3
                  titulo: "Selecciona, de entre las tecnologías digitales proporcionadas por la AE o por los titulares del centro, aquellas que resultan más adecuadas para que el alumnado, en función de su edad y grado de madurez, desarrolle su competencia para resolver los problemas técnicos que pudieran presentarse"
              afirmaciones_desempeño: Pongo en práctica, de forma autónoma, diferentes estrategias didácticas para el desarrollo de la competencia del alumnado con el fin de que resuelva problemas cotidianos, se desenvuelva en un mundo digitalizado y pueda llevar a cabo proyectos individuales y colectivos empleando de forma creativa y crítica las tecnologías digitales




Diseño del curso:

-
    Fecha: 12/10/2014
    Título del Curso: Uso didáctico del aula virtual EVAGD (avanzado)
    Tipo de formación: Histórico-teleformación
    Total Horas: 50
    Area1: 
    Area2: 
    Area3: 
    Area4: 
    Area5: 
    Area6: 
    Proyecto para creación del diseño: Tecnología al Servicio de las personas [TSP]
    Competencia digital del docente: Búsqueda de información, Comunicación y colaboración, Creación de contenido
    Descripción: Esta actividad formativa pretende continuar profundizando en el conocimiento de actividades y recursos que nos ofrece la plataforma Moodle, creando un curso en el entorno virtual de aprendizaje EVAGD aplicable al alumnado y relacionado con el área o materia que se imparte. El curso creado será compartido con el resto de la Comunidad Educativa a través de una actividad destinada para ello.
    Destinatarios: El curso va dirigido a todo el profesorado, de cualquier área, materia, etapa o nivel educativo con conocimientos básicos sobre la creación de cursos en la plataforma Moodle y que deseen profundizar en el uso didáctico de un aula virtual en el Proyecto EVAGD.
    Objetivos: "<ul>\n\t<li>Impulsar la adquisición de las destrezas y conocimientos relacionados con el uso didáctico de las TIC y nuevos modelos metodológicos por parte del profesorado.</li>\n\t<li>Promover la capacitación del profesorado en la utilización de las TIC al servicio de la innovación y la investigación docente.</li>\n\t<li>Conocer las bases del Proyecto EVAGD así como el blog del Proyecto y el espacio de colaboración del profesorado en la plataforma Moodle (Sala del Profesorado).</li>\n\t<li>Capacitar al docente en la creación y uso del aula virtual como soporte del trabajo cooperativo y colaborativo del alumnado a través de las actividades colaborativas de Moodle (glosario, wiki, taller, creación de grupos y agrupamientos, etc.)</li>\n\t<li>Potenciar la atención a la diversidad por medio de Moodle (lección, cuestionarios, actividades condicionadas, etc.)</li>\n\t<li>Utilizar el entorno virtual como espacio para gestionar los usuarios en Moodle, integrando los recursos y actividades que nos ofrece la plataforma en las distintas situaciones de aprendizaje que se implementan en el aula.</li>\n\t<li>Compartir los cursos o aulas virtuales elaboradas en esta actividad formativa.</li>\n\t<li>Respetar la identidad digital y los derechos de autor.</li>\n</ul>"
    Contenidos: "<ul>\n\t<li>¿Qué es el Proyecto EVAGD? Conociendo el Blog y los diferentes espacios de la plataforma.</li>\n\t<li>Administración del sitio en la plataforma EVAGD.</li>\n\t<li>Creación de Grupos y agrupamientos dentro de un curso Moodle.</li>\n\t<li>Creación y utilización del recurso “Libro” y otros contenidos multimedia para enriquecer nuestro curso Moodle.</li>\n\t<li>Utilización de las actividades colaborativas que nos ofrece el proyecto EVAGD: glosarios, bases de datos, wikis y talleres.</li>\n\t<li>Utilización de las actividades individuales que nos ofrece el proyecto EVAGD: lecciones, cuestionarios y juegos.</li>\n\t<li>Utilización de las actividades condicionadas para realizar un seguimiento del aprendizaje del alumnado.</li>\n\t<li>Administración de las calificaciones de nuestra aula virtual: categorías e ítems, letras, escalas, importar y exportar calificaciones.</li>\n\t<li>La identidad digital y los derechos de autor.</li>\n</ul>"
    Metodología: <strong>Teórico práctica.</strong>El profesorado participante elaborará un curso en la zona de prácticas adaptado al diseño de su programación de aula dependiendo del área o materia elegida. Dicho curso deberá contemplar los requisitos mínimos especificados en los criterios de evaluación y certificación, de manera que el curso acabado sea aplicable directamente al alumnado. Una vez elaborado deberá ser compartido con el profesorado participante y el resto de la Comunidad Educativa.Para acometer las diferentes tareas propuestas, se consultarán los recursos y materiales facilitados en la plataforma e interactuarán entre sí y con los/as tutores/as del curso para resolver las posibles dudas o dificultades.
    Fase práctica: "<strong>Tareas: </strong>\n<ul>\n\t<li>Crear un curso en la zona de práctica relacionado con su área o materia, vinculado con uno o varios criterios de evaluación, donde se realizarán las siguientes acciones:\n<ul>\n\t<li>Administración del sitio en el Proyecto EVAGD.</li>\n\t<li>Configurar su curso.</li>\n\t<li>Creación de grupos y agrupamientos</li>\n\t<li>Añadir recursos: libros y otros contenidos multimedia.</li>\n\t<li>Añadir actividades colaborativas: glosarios, bases de datos, wikis y talleres.</li>\n\t<li>Añadir actividades individuales: lecciones, cuestionarios y juegos.</li>\n\t<li>Utilización de las actividades condicionadas para realizar un seguimiento del aprendizaje del alumnado.</li>\n\t<li>Administración de las calificaciones del aula virtual: categorías e ítems, letras, escalas, importar y exportar calificaciones.</li>\n\t<li>Compartir el curso creado con el resto de participantes a través de la actividad creada para ello.</li>\n</ul>\n</li>\n</ul>"
    Temporalización: 40 horas online
    Observaciones: "<strong>Perfil del ponente:</strong>\n<ul>\n\t<li>Conocimientos técnicos de la Plataforma Moodle.</li>\n\t<li>Conocimientos y experiencia práctica sobre el uso didáctico del Proyecto EVAGD.</li>\n</ul>\n<strong>Materiales:</strong>Los materiales de apoyo se ofrecen en la plataforma del curso y en el Blog del Proyecto EVAGD."
