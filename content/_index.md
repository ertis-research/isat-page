---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "8rem"

sections:
  # Sección 1: Cabecera renovada
  - block: hero
    content:
      image: "media/logo_proy.png"
      gallery:
        - "media/tebas/1764688478809.jpg"
        - "media/sierra_yeguas/1764688479676.jpg"
        - "media/tapia/1764688484025.jpg"
        - "media/cuevas_del_becerro/1764688483083.jpg"
      title: "iSAT: Sistema de Alerta Temprana Inteligente"
      text: "Gestión predictiva de aguas subterráneas para combatir la sequía y garantizar la calidad del agua"
      primary_action:
        id: btn-technology
        text: "Conoce la Metodología"
        url: "/Metodología/#tecnologia"
      secondary_action:
        text: "Grupos"
        url: "#pilotos"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"


  # # Sección 2: El Reto - La Crisis del Agua
  # - block: features
  #   id: reto
  #   content:
  #     title: "El Doble Desafío de la Sequía"
  #     text: "**Los períodos de sequía conllevan una merma significativa en la disponibilidad de los recursos hídricos, pero también un empeoramiento de la calidad. Cuando los recursos superficiales son insuficientes, se recurre especialmente a los acuíferos.**"
  #     items:
  #       - name: "Riesgo de Sobreexplotación"
  #         description: "Es necesario desarrollar tecnologías avanzadas que permitan optimizar el aprovechamiento del agua subterránea para evitar su sobreexplotación."
  #         icon: "exclamation-triangle"
  #       - name: "Vulnerabilidad a la Contaminación"
  #         description: "Los acuíferos kársticos, muy permeables, son especialmente vulnerables a la contaminación, que puede transportarse a altas velocidades (superiores a 100 m/h)."
  #         icon: "flask"
  #       - name: "Escasez de Sistemas de Alerta"
  #         description: "En España apenas hay implementados Sistemas de Alerta Temprana (SAT) en captaciones de agua procedentes de acuíferos."
  #         icon: "bell"
  #   design:
  #     columns: '3'
  #     background:
  #       color: "#f8f9fa"
  #     spacing:
  #       padding: ["0", 0, "4rem", 0]

  # Sección 3: Nuestra Solución - Presentando iSAT
  - block: solucion
    id: solucion
    content:
      title: "iSAT: La Respuesta Inteligente y Predictiva"
      subtitle: "Sistema de alerta temprana inteligente que integra sensores de bajo coste, comunicación remota e Inteligencia Artificial para analizar en tiempo real la disponibilidad y calidad del agua."
      description: "Su objetivo es mejorar la gestión del agua subterránea en captaciones de abastecimiento urbano durante períodos de sequía."
      steps:
        - number: "1"
          icon: "satellite-dish"
          title: "Sensores Inteligentes"
          description: "Monitorización continua de parámetros hidrogeológicos (nivel, caudal, conductividad, temperatura, turbidez, oxígeno disuelto)"
        - number: "2"
          icon: "globe"
          title: "Transmisión Multi-Protocolo"
          description: "Comunicación GPRS, radio y satélite para garantizar conectividad en entornos remotos"
        - number: "3"
          icon: "brain"
          title: "Análisis con IA"
          description: "Algoritmos de inteligencia artificial que predicen disponibilidad y calidad del agua"
        - number: "4"
          icon: "exclamation-triangle"
          title: "Alertas Tempranas"
          description: "Sistema de alertas para optimizar la toma de decisiones"
    design:
      background:
        color: "#ffffff"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
      
  # Sección de navegación con tarjetas métricas
  - block: hero-metrics
    id: exploracion
    content:
      title: "Explora el proyecto por apartados"
      text: "Accede directamente a las secciones clave del proyecto."
      items:
        - name: "Calidad del Agua"
          description: "Contexto hidrogeológico y riesgos de contaminación en sequía."
          icon: "flask"
          url: "/problematica/#calidad"
          metric: "kárstico"
          metric_label: "acuífero"
        - name: "Objetivos del Proyecto"
          description: "Metas técnicas y alcance de validación del sistema iSAT."
          icon: "bullseye"
          url: "/objetivos/"
          metric: "TRL7"
          metric_label: "nivel objetivo"
        - name: "Marco de Financiación"
          description: "Ficha administrativa y dotación tecnológica del proyecto."
          icon: "university"
          url: "/financiacion/"
          metric: "24 m"
          metric_label: "duración"
        - name: "Metodología iSAT"
          description: "Tecnologías clave y enfoque de desarrollo del sistema."
          icon: "microchip"
          url: "/metodologia/#tecnologia"
          metric: "4 nodos"
          metric_label: "pilotos activos"
    design:
      background:
        color: "#ffffff"
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  # Sección de Mapa de Ubicación
  - block: map
    id: ubicacion
    content:
      announcement: "Ubicación de las 4 Zonas"
      title: "Red Provincial de Validación iSAT"
      text: "La validación tecnológica del proyecto iSAT se lleva a cabo en cuatro emplazamientos representativos de la problemática hídrica andaluza."
      points:
        - title: "Teba"
          subtitle: "Control en Guadalteba (Piloto Activo)"
          color: "text-indigo-600"
        - title: "Cuevas del Becerro"
          subtitle: "Manantial Remoto"
          color: "text-blue-500"
        - title: "Sierra de Yeguas"
          subtitle: "Presión Agrícola"
          color: "text-emerald-500"
        - title: "Villanueva de Tapia"
          subtitle: "Bombeo Municipal"
          color: "text-orange-500"

  # Sección de Divulgación
  - block: divulgacion
    id: divulgacion
    content:
      title: "Últimas Noticias"
      text: "Novedades recientes de desarrollo, validación y divulgación del proyecto iSAT."
      featured:
        name: "Instalación finalizada en Sierra de Yeguas"
        description: "Despliegue completado del nodo piloto con comunicación LoRa y satélite. Las primeras lecturas en continuo de conductividad y nivel piezométrico ya se reciben en la plataforma cloud, marcando el inicio de la fase de validación en campo."
        image: "media/sierra_yeguas/1764688479676.jpg"
        tag: "Infraestructura"
        tag_color: "blue"
        date: "Enero 2026"
        url: "/noticias/"
        cta: "Leer noticia completa"
      items:
        - name: "Nueva jornada de demostración en la UMA"
          description: "Sesión abierta para mostrar sensores virtuales, operación en campo y análisis de datos en tiempo real."
          image: "media/tebas/1764688478809.jpg"
          icon: "calendar-check"
          tag: "Evento"
          tag_color: "green"
          date: "Febrero 2026"
          url: "/eventos/"
        - name: "Publicaciones técnicas iSAT"
          description: "Consulta los documentos y avances científicos más recientes vinculados al proyecto."
          image: "media/tapia/1764688484025.jpg"
          icon: "book-open"
          tag: "Ciencia"
          tag_color: "purple"
          date: "2025–2026"
          url: "/publicaciones/"
        - name: "Visita técnica a Cuevas del Becerro"
          description: "El equipo realizó una jornada de campo para revisar el estado del prototipo instalado en el manantial urbano."
          image: "media/cuevas_del_becerro/1764688483083.jpg"
          icon: "map-marker-alt"
          tag: "Campo"
          tag_color: "orange"
          date: "Diciembre 2025"
          url: "/noticias/"

  # Sección del Equipo
  - block: team
    id: equipo
    content:
      eyebrow: "Equipo de investigación"
      title: "Las personas detrás de iSAT"
      subtitle: "Un equipo multidisciplinar de expertos en hidrogeología, IoT, inteligencia artificial y desarrollo de software."
      investigators_title: "Investigadores Clave"
      investigators:
        - role: "Investigador Principal"
          name: "Juan Antonio Barberá Fornell"
        - role: "Hidrogeología"
          name: "Bartolomé Andreo Navarro"
        - role: "Recursos Hídricos"
          name: "Matías Mudarra Martínez"
        - role: "Desarrollo de Software"
          name: "Manuel Díaz Rodríguez"
        - role: "IoT e Inteligencia Artificial"
          name: "Luis Llopis Torres"

  # # Sección de Detalles del Proyecto
  # - block: markdown
  #   id: proyecto-intro
  #   content:
  #     title: "Detalles del Proyecto"
  #     text: |
  #       <div style="background: linear-gradient(135deg, #1e3a8a 0%, #1e40af 100%); color: white; padding: 2rem; border-radius: 8px; box-shadow: 0 10px 25px rgba(30, 58, 138, 0.15);">
  #         <h2 style="color: white; margin-bottom: 1rem; font-weight: 600;">Desarrollo de un Sistema de Alerta Temprana Inteligente</h2>
  #         <p style="font-size: 1.1rem; opacity: 0.95; line-height: 1.6;">Control de extracciones y contaminación de aguas subterráneas en abastecimiento urbanos durante períodos de sequía</p>
  #       </div>

  # # Información del proyecto con iconos
  # - block: features
  #   id: proyecto-info
  #   content:
  #     items:
  #       - name: "Duración del Proyecto"
  #         description: "El proyecto tiene una duración total de 24 meses, dividido en fases de desarrollo, implementación y validación."
  #         icon: clock
  #       - name: "Desarrollo Experimental"
  #         description: "Categoría de investigación aplicada enfocada en el desarrollo de prototipos funcionales y su validación en entornos reales."
  #         icon: flask
  #       - name: "Nivel Tecnológico TRL4 → TRL7"
  #         description: "Evolución desde prueba de concepto hasta prototipo pre-comercial validado en entornos operacionales."
  #         icon: chart-bar
  #       - name: "Financiación Ministerio de Ciencia"
  #         description: "Proyecto financiado por el Ministerio de Ciencia e Innovación dentro del programa de I+D+i."
  #         icon: university
  #   design:
  #     background:
  #       color: "white"
  #     spacing:
  #       padding: ["3rem", 0, "3rem", 0]
---


