---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: iSAT
      text: Desarrollo de un sistema de alerta temprana inteligente para control de extracciones y de la contaminación de aguas subterráneas en abastecimiento urbanos durante períodos de sequía.
      # primary_action:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
      #   icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: rose-petals.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: features
    id: about
    content:
      title: Descripción del proyecto
      text: El proyecto propone el desarrollo de un Sistema de Alerta Temprana inteligente (iSAT) para mejorar la gestión del agua subterránea en captaciones urbanas durante periodos de sequía. El iSAT integrará un conjunto de sensores de bajo coste para medir parámetros hidrogeológicos en continuo (nivel, caudal, conductividad, temperatura, turbidez y oxígeno disuelto), junto con algoritmos de inteligencia artificial (soft sensors) capaces de anticipar la disponibilidad y calidad del agua e identificar posibles episodios de contaminación. Los datos serán enviados de forma remota mediante comunicaciones multi-protocolo (GPRS, radio y satélite), garantizando la operatividad en entornos remotos. Con este sistema, se busca disponer de una herramienta predictiva y preventiva que apoye la toma de decisiones de gestores y operadores del agua, optimizando el aprovechamiento de acuíferos kársticos y reduciendo riesgos para el abastecimiento urbano.
  - block: features
    id: objetivos
    content:
      title: Objetivos del proyecto
      text: Desarrollar un sistema inteligente de monitorización continua de parámetros físico-químicos para identificar patrones de afectación a caudales y detectar episodios de contaminación en abastecimientos urbanos.
      items:
        - description: Maximizar la versatilidad de los SAT en diferentes esquemas de captación.
          icon: magnifying-glass
          name: Maximización
        - description: Crear un dispositivo pre-comercial, configurable, autónomo y con comunicación multi-protocolo.
          icon: bolt
          name: Diseño
        - description: Mejorar la capacidad predictiva mediante IA y reducir costes de sensórica.
          icon: sparkles
          name: Optimización
        - description: Validar la tecnología en entornos controlados y reales.
          icon: code-bracket
          name: Validación
---
