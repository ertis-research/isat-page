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
      title: "iSAT"
      text: "Desarrollo de un sistema de alerta temprana inteligente para control de extracciones y de la contaminación de aguas subterráneas en abastecimiento urbanos durante períodos de sequía.
      "
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
      title: "iSAT: La herramienta inteligente y predictiva"
      subtitle: "El sistema de alerta temprana que integra monitorización continua, envío remoto de datos e inteligencia artificial en una solución económica y versátil para la evaluación y predicción en tiempo real de la disponibilidad y la calidad del agua
      "
      steps:
        - icon: "wave-square"
          title: "Sensores Inteligentes"
          description: "Monitorización continua de parámetros hidrogeológicos (nivel, caudal, conductividad, temperatura, turbidez, oxígeno disuelto)"
        - icon: "globe"
          title: "Protocolos de Comunicación Soportados"
          description: "WiFi, Ethernet, LoRaWAN, GPRS/4G, NB-IoT y comunicación serie (RS-485/Modbus) para máxima interoperabilidad con sensores y redes existentes"
        - icon: "satellite-dish"
          title: "Transmisión Multi-Protocolo"
          description: "Comunicación GPRS, radio y satélite para garantizar conectividad en entornos remotos"
        - icon: "circle-nodes"
          title: "Análisis con IA"
          description: "Algoritmos de IA para predecir periodos de sequia e inferir niveles de contaminantes
          "
        - icon: "exclamation-triangle"
          title: "Alerta Temprana"
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
          url: "/problematica/"
          metric: "kárstico"
          metric_label: "acuífero"
        - name: "Objetivos del Proyecto"
          description: "Metas técnicas y alcance de validación del sistema iSAT."
          icon: "bullseye"
          url: "/objetivos/"
          metric: "TRL7"
          metric_label: "nivel objetivo"
        - name: "Metodología iSAT"
          description: "Tecnologías clave y enfoque de desarrollo del sistema."
          icon: "microchip"
          url: "/metodologia/"
          metric: "4 nodos"
          metric_label: "pilotos activos"
        - name: "Impacto Esperado"
          description: "Reducción de costes operativos, protección de la salud pública y optimización del recurso hídrico subterráneo frente a sequias e impactos ambientales."
          icon: "leaf"
          url: "/impacto_esperado/"
          metric: "TRL 4→7"
          metric_label: "nivel tecnológico"
        - name: "Marco de Financiación"
          description: "Ficha administrativa y dotación tecnológica del proyecto."
          icon: "university"
          url: "/financiacion/"
          metric: "24 m"
          metric_label: "duración"
    design:
      background:
        color: "#ffffff"
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  # Sección de Mapa de Ubicación
  - block: map
    id: ubicacion
    content:
      announcement: "Descubre las zonas piloto"
      title: "Puntos de abastecimiento para la validación del iSAT"
      text: "El desarrollo, validación y demostración del prototipo en un entorno real se lleva a cabo en cuatro casos de estudio representativos de la problemática hídrica andaluza"
      points:
        - title: "Teba"
          subtitle: "Comarca Serranía de Ronda"
          color: "text-indigo-600"
          url: "/teba/"
        - title: "Cuevas del Becerro"
          subtitle: "Comarca Serranía de Ronda"
          color: "text-blue-500"
          url: "/cuevas_del_becerro/"
        - title: "Sierra de Yeguas"
          subtitle: "Comarca NORNORMA"
          color: "text-emerald-500"
          url: "/sierra_de_yeguas/"
        - title: "Villanueva de Tapia"
          subtitle: "Comarca NORNORMA"
          color: "text-orange-500"
          url: "/villanueva_de_tapia/"

  # Sección de Divulgación
  - block: divulgacion
    id: divulgacion
    content:
      title: "Últimas noticias"
---


