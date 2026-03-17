---
title: "Metodología iSAT"
date: 2026-02-20
type: landing
layout: metodologia
subtitle: "Enfoque técnico para monitorizar, analizar y anticipar riesgos en aguas subterráneas."
sections:
  - block: hero
    id: hero
    content:
      announcement:
        text: "Realización del Proyecto"
      title: "Metodología de desarrollo iSAT"
      text: "Combinamos sensores en campo, transmisión remota y analítica avanzada para convertir datos en alertas operativas."
      primary_action:
        text: "Ver sitios piloto"
        url: "/#ubicacion"
      secondary_action:
        text: "Últimas noticias"
        url: "/noticias/"
      image: "media/CONFIGURACIÓN2.png"

  - block: solucion
    id: flujo
    content:
      title: "Flujo metodológico"
      subtitle: "Del dato en campo a la decisión operativa."
      description: "La metodología iSAT integra adquisición continua de datos, comunicaciones robustas y analítica para anticipar cambios en disponibilidad y calidad del agua."
      dark_mode: true
      steps:
        - number: "1"
          icon: "drafting-compass"
          title: "Diseño de modulos hidrogeológicas y operacional"
          description: "Definición de requisitos técnicos, selección de sensores y diseño de la arquitectura de comunicaciones y nodos IoT."
          image: "media/metodologia/5_Modulo_Hidrogeológico.png"
        - number: "2"
          icon: "microchip"
          title: "Desarrollo e integración del prototipo"
          description: "Ensamblado de nodos, programación de firmware, integración con la plataforma cloud y entrenamiento de modelos IA."
          image: "media/metodologia/6_Prototipo.jpeg"
        - number: "3"
          icon: "satellite-dish"
          title: "Herramienta predictiva"
          description: "Instalación en los 4 sitios piloto, campañas de medición intensivas y ajuste de parámetros en tiempo real."
          image: "media/metodologia/5_Modulo_Hidrogeológico.png"
        - number: "4"
          icon: "file-alt"
          title: "Validación del prototipo"
          description: "Análisis estadístico integral, publicaciones científicas y presentación de resultados a gestores del agua."
          image: "media/metodologia/8_Validacion.jpeg"

  - block: features
    id: tecnologia
    content:
      title: "Concepto innovador y versátil"
      subtitle: "Especificaciones técnicas, protocolos y capacidades del hardware y software desarrollado ad-hoc para el proyecto iSAT."
      items:
        - name: "Inteligencia Artificial y Soft Sensors"
          icon: "microchip"
          color: "blue-600"
          description: "iSAT utiliza sensores virtuales (soft sensors) basados en arquitecturas de Machine Learning para estimar parámetros complejos, como nitratos o E. coli, a partir de mediciones más sencillas y económicas (conductividad, turbidez)."
          bullets:
            - "Procesamiento en la nube (Cloud) o en el borde (Edge AI)."
            - "Algoritmos calibrados mediante validación cruzada en laboratorio."

        - name: "Sistema Abierto y Flexible"
          icon: "sliders-h"
          color: "indigo-600"
          description: "Frente a los 'vendor lock-ins' de soluciones propietarias cerradas, la PCB de iSAT ha sido diseñada con una arquitectura modular que permite acoplar un número flexible de sensores industriales de diversos fabricantes."
          bullets:
            - "Puertos físicos: Múltiples entradas analógicas y digitales."
            - "Estándares industriales: Soporte nativo para buses SDI-12, RS-485 (Modbus RTU), I2C y UART."

        - name: "Bajo Coste y Bajo Consumo"
          icon: "dollar-sign"
          color: "emerald-600"
          description: "El diseño se fundamenta en microcontroladores de alto rendimiento y bajo coste (familia ESP32), optimizando tanto el coste de hardware (CAPEX) como los gastos de operación del software (OPEX) para facilitar su escalado."
          bullets:
            - "Power Management: Modos Deep Sleep programables."
            - "Alimentación: Operación a 12V/24V, compatible con paneles solares para ubicaciones remotas aisladas de la red eléctrica."

        - name: "Conectividad Total Multiprotocolo"
          icon: "signal"
          color: "amber-600"
          description: "El nodo incorpora un módulo de comunicaciones híbrido para asegurar la transmisión de datos sin importar la orografía. Prioriza redes móviles pero activa el respaldo satelital ante caídas de cobertura."
          bullets:
            - "Redes Híbridas: GPRS / 4G / NB-IoT + Satélite LEO (ej. Iridium)."
            - "Protocolos IoT: Envío de telemetría segura y ligera mediante MQTT, HTTP RESTful y CoAP."

  - block: timeline
    id: flujo-datos
    content:
      title: "El Flujo de Datos iSAT"
      subtitle: "Un proceso continuo y automatizado: desde la medición física en el acuífero hasta la toma de decisiones en la nube."
      items:
        - name: "Sondas en campo"
          color: "blue-600"
          description: "Instrumentación física sumergida en el punto de captación (pozo o manantial). Incluye sondas multiparamétricas industriales calibradas para la medición ininterrumpida de variables clave: nivel, conductividad eléctrica, temperatura y turbidez."
        
        - name: "PLC"
          color: "indigo-600"
          description: "El 'cerebro' local. Controlador lógico e interfaz de adquisición de datos (Datalogger) instalado en la caseta. Recibe las señales eléctricas de las sondas, empaqueta la información y gestiona la telemetría enviándola hacia los servidores seguros."
        
        - name: "Resultado gráfico soft sensor"
          color: "emerald-600"
          description: "Procesamiento de los datos crudos mediante Inteligencia Artificial (Redes Neuronales). El sistema infiere y genera gráficamente la concentración de contaminantes complejos a partir de los datos físico-químicos básicos en tiempo real."
        
        - name: "Grafana / alertas"
          color: "amber-500"
          description: "Plataforma de visualización en la nube. Los gestores visualizan el estado de la captación a través de paneles interactivos en Grafana y reciben notificaciones inmediatas si los algoritmos detectan superaciones de los umbrales de riesgo."
---
