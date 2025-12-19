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
      title: "iSAT: Sistema de Alerta Temprana Inteligente"
      text: "Gestión predictiva de aguas subterráneas para combatir la sequía y garantizar la calidad del agua"
      primary_action:
        id: btn-technology
        text: "Conoce la Tecnología"
        url: "#tecnologia"
      secondary_action:
        text: "Grupos"
        url: "#pilotos"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"


  # Sección 2: El Reto - La Crisis del Agua
  - block: features
    id: reto
    content:
      title: "El Doble Desafío de la Sequía"
      text: "**Los períodos de sequía conllevan una merma significativa en la disponibilidad de los recursos hídricos, pero también un empeoramiento de la calidad. Cuando los recursos superficiales son insuficientes, se recurre especialmente a los acuíferos.**"
      items:
        - name: "Riesgo de Sobreexplotación"
          description: "Es necesario desarrollar tecnologías avanzadas que permitan optimizar el aprovechamiento del agua subterránea para evitar su sobreexplotación."
          icon: "exclamation-triangle"
        - name: "Vulnerabilidad a la Contaminación"
          description: "Los acuíferos kársticos, muy permeables, son especialmente vulnerables a la contaminación, que puede transportarse a altas velocidades (superiores a 100 m/h)."
          icon: "flask"
        - name: "Escasez de Sistemas de Alerta"
          description: "En España apenas hay implementados Sistemas de Alerta Temprana (SAT) en captaciones de agua procedentes de acuíferos."
          icon: "bell"
    design:
      columns: '3'
      background:
        color: "#f8f9fa"
      spacing:
        padding: ["0", 0, "4rem", 0]

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
      
  # Sección de Tecnología Innovadora
  - block: features
    id: tecnologia
    content:
      title: "Innovación en el Corazón de iSAT"
      items:
        - name: "Inteligencia Artificial y Soft Sensors"
          description: "iSAT utiliza soft sensors (sensores virtuales) basados en IA para estimar parámetros complejos, como la concentración de nitratos, a partir de mediciones más sencillas y económicas. Esto reduce costes y permite el control de contaminantes que hoy no se pueden medir en continuo."
          icon: microchip
        - name: "Sistema Abierto y Flexible"
          description: "A diferencia de las soluciones comerciales con software propietario, iSAT es un sistema abierto y configurable. Permite acoplar un número flexible de sensores y adaptarse a distintos esquemas de captación."
          icon: sliders-h
        - name: "Bajo Coste y Bajo Consumo"
          description: "El diseño se centra en una reducción significativa de costes tanto en hardware como en software para facilitar su expansión. Su bajo consumo le permite operar con autonomía en puntos remotos."
          icon: dollar-sign
        - name: "Conectividad Total"
          description: "Para garantizar la conectividad en áreas con cobertura limitada, el sistema incorpora comunicación multi-protocolo, incluyendo GPRS y un módulo de comunicaciones por satélite (LEO)."
          icon: signal
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  # Sección de Proyectos Piloto
  - block: pilotos 
    id: pilotos
    content:
      title: "Del Laboratorio al Terreno: Proyectos Piloto"
      subtitle: |
        El proyecto busca elevar la tecnología desde un nivel **TRL4** (prueba de concepto) hasta un **TRL7**, validando el prototipo pre-comercial en condiciones reales de operación.
    design:
      background:
        gradient:
          start: "#f1f5f9"
          end: "#e2e8f0"

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
        - title: "Sierra de Líbar (Benaoján)"
          subtitle: "Manantial Remoto"
          color: "text-blue-500"
        - title: "Sierra de Yeguas"
          subtitle: "Presión Agrícola"
          color: "text-emerald-500"
        - title: "Villanueva de Tapia"
          subtitle: "Bombeo Municipal"
          color: "text-orange-500"

    # Sección del Equipo
  - block: team
    id: equipo
    content:
      title: "Un Equipo Multidisciplinar"
      subtitle: "iSAT es fruto de la colaboración entre investigadores del Centro de Hidrogeología de la Universidad de Málaga (CEHIUMA), expertos en la gestión de recursos hídricos, y el grupo de investigación ERTIS, especialistas en desarrollo de software para infraestructuras críticas, IoT e Inteligencia Artificial."
      groups:
        - name: "CEHIUMA"
          icon: water
          description: "Con décadas de experiencia en la investigación de acuíferos y la participación en numerosos proyectos nacionales e internacionales sobre gestión hídrica."
        - name: "ERTIS"
          icon: laptop-code
          description: "Amplia experiencia en la integración de dispositivos IoT, gemelos digitales, IA y computación en la nube (cloud), con una reconocida capacidad de transferencia tecnológica."
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
    design:
      background:
        color: "#f8f9fa"

  # Sección de Detalles del Proyecto
  - block: markdown
    id: proyecto-intro
    content:
      title: "Detalles del Proyecto"
      text: |
        <div style="background: linear-gradient(135deg, #1e3a8a 0%, #1e40af 100%); color: white; padding: 2rem; border-radius: 8px; box-shadow: 0 10px 25px rgba(30, 58, 138, 0.15);">
          <h2 style="color: white; margin-bottom: 1rem; font-weight: 600;">Desarrollo de un Sistema de Alerta Temprana Inteligente</h2>
          <p style="font-size: 1.1rem; opacity: 0.95; line-height: 1.6;">Control de extracciones y contaminación de aguas subterráneas en abastecimiento urbanos durante períodos de sequía</p>
        </div>

  # Información del proyecto con iconos
  - block: features
    id: proyecto-info
    content:
      items:
        - name: "Duración del Proyecto"
          description: "El proyecto tiene una duración total de 24 meses, dividido en fases de desarrollo, implementación y validación."
          icon: clock
        - name: "Desarrollo Experimental"
          description: "Categoría de investigación aplicada enfocada en el desarrollo de prototipos funcionales y su validación en entornos reales."
          icon: flask
        - name: "Nivel Tecnológico TRL4 → TRL7"
          description: "Evolución desde prueba de concepto hasta prototipo pre-comercial validado en entornos operacionales."
          icon: chart-bar
        - name: "Financiación Ministerio de Ciencia"
          description: "Proyecto financiado por el Ministerio de Ciencia e Innovación dentro del programa de I+D+i."
          icon: university
    design:
      background:
        color: "white"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # Objetivos específicos
    # Objetivos específicos
  - block: objetivos
    id: objetivos
    content:
      title: "Objetivos Específicos"
      items:
        - title: "Versatilidad máxima"
          description: "en diferentes esquemas de captación"
        - title: "Dispositivo pre-comercial"
          description: "configurable, autónomo y con comunicación multi-protocolo"
        - title: "Capacidad predictiva mejorada"
          description: "mediante IA y reducción de costes de sensórica"
        - title: "Validación tecnológica"
          description: "en entornos controlados y reales"
    design:
      background:
        color: "bg-primary"
---