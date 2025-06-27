# Asistente IA para Búsqueda Laboral Personalizada

### Autor: Leonardo Javier Fleita

### Curso: Inteligencia Artificial - Generación de Prompts

### Comisión: 84185

---

## 📌 Resumen del proyecto

Este proyecto propone una solución asistida por inteligencia artificial para acompañar a personas que están en proceso de búsqueda laboral en áreas tecnológicas como desarrollo web, diseño UX/UI y desarrollo mobile. La solución ofrece una experiencia personalizada a través de generación de contenido con IA, incluyendo:

- Creación de perfiles laborales.
- Redacción de cartas de presentación personalizadas.
- Generación de currículums (CVs).
- Simulación de entrevistas laborales.
- Creación de banners visuales para perfiles profesionales (LinkedIn, GitHub).

Se utilizan modelos de texto a texto y texto a imagen con **Gemini**, aplicando distintas técnicas de prompting como **zero-shot, one-shot, few-shot** e **iteración** según el contexto y el tipo de contenido a generar. Todo el proyecto está implementado en una Jupyter Notebook, que permite combinar código, texto e imágenes en una interfaz interactiva, sin depender de herramientas de pago.

---

## 🧩 Introducción

### Nombre del proyecto

**Asistente IA para Búsqueda Laboral Personalizada**

### Presentación del problema a abordar

Buscar empleo en el área de desarrollo web, aplicaciones móviles o diseño UX/UI puede ser un proceso largo, frustrante y competitivo. Muchas personas enfrentan dificultades para adaptar su currículum a distintos perfiles, redactar cartas de presentación personalizadas, prepararse para entrevistas técnicas o crear una identidad profesional sólida en plataformas como LinkedIn.

Además, quienes se inician en estas disciplinas o buscan una reconversión profesional (como es mi caso) suelen no saber cómo destacar sus habilidades transferibles o proyectos personales. Esta propuesta busca facilitar ese proceso mediante el uso de inteligencia artificial generativa, automatizando y personalizando contenidos claves para la búsqueda laboral.

---

## 💡 Propuesta de solución

La solución consiste en un asistente basado en IA que utiliza modelos de generación de texto y de imagen para acompañar al usuario en su proceso de búsqueda laboral. A través de prompts personalizados, el sistema podrá generar:

- CVs adaptados a distintos puestos de desarrollo web, mobile o diseño UX/UI.
- Cartas de presentación orientadas a ofertas específicas.
- Simulaciones de entrevistas con preguntas técnicas.
- Resúmenes profesionales optimizados para LinkedIn.
- Banners para LinkedIn u otros portales laborales.

Se implementarán técnicas de **Fast Prompting** para mejorar la precisión y relevancia de las respuestas, reducir la cantidad de consultas necesarias y optimizar los resultados.

Cada módulo aplica técnicas de Fast Prompting específicas:

- **Zero-shot** en tareas simples o comunes.
- **One-shot/Few-shot** donde el estilo debe ser imitado (ej: respuestas de entrevista, descripción de perfil).
- **Iteración** cuando el primer resultado necesita refinarse por longitud, tono o formato.

---

## 🔍 Justificación de la viabilidad del proyecto

El proyecto es técnicamente viable, ya que los prompts propuestos han sido probados con herramientas gratuitas como **Gemini** (Google AI), que permiten generar resultados útiles sin necesidad de conocimientos de programación avanzados ni costos de uso.

El desarrollo puede organizarse en etapas, centrándose en la calidad de los prompts y en su adaptación a distintos perfiles laborales del ámbito digital. Se trabajará con una cantidad controlada de consultas para asegurar la viabilidad económica del proyecto, aprovechando el acceso gratuito que ofrece la API de Gemini.

---

## 🎯 Objetivos

- Facilitar el proceso de búsqueda laboral a través de generación de contenido con IA.
- Aplicar estrategias de Fast Prompting para mejorar la calidad de los resultados.
- Simular casos reales como CVs, cartas, entrevistas y perfiles laborales.
- Crear una interfaz sencilla en Jupyter para mostrar cómo interactuar con los prompts.

## 🧪 Metodología

El proyecto se divide en etapas:

1. Análisis de las necesidades del usuario que busca empleo.
2. Desarrollo de distintos tipos de prompts para cubrir esas necesidades.
3. Aplicación de técnicas de Fast Prompting (estructura clara, instrucciones precisas, ejemplos).
4. Evaluación de los resultados obtenidos por cada prompt.
5. Optimización de prompts según los criterios de claridad, brevedad y efectividad.
6. Documentación de los hallazgos y generación de outputs demostrativos.

---

## 🛠️ Herramientas y tecnologías

- **Python**
- **Jupyter Notebook**
- **Gemini API (Google AI, modelo gemini-pro)**
- **Fast Prompting**
- **Git y GitHub**
- **Técnicas de Prompting**:
  - Zero-shot
  - One-shot
  - Few-shot
  - Iteración sobre prompts

---

## 🚀 Implementación

La implementación se desarrollará en un archivo `poc_prompts.ipynb` donde se mostrarán ejemplos funcionales de los prompts propuestos, junto con los resultados obtenidos. Se documentarán también los ajustes hechos a los prompts para mejorar su rendimiento utilizando Gemini.

Se priorizará un enfoque modular y reutilizable para facilitar futuras ampliaciones y adaptaciones del proyecto.

---

## 📊 Resultados

- Se logró automatizar la creación de contenido personalizado con buena calidad textual y visual.
- Los prompts optimizados mejoraron la claridad, tono y longitud deseada.
- La generación de imagen permitió agregar identidad visual profesional al CV y a redes.
- Las funciones creadas son reutilizables y escalables.

---

## ✅ Conclusiones

- Los objetivos planteados fueron alcanzados con éxito.
- El uso de Gemini resultó práctico, gratuito y efectivo para generar tanto texto como imágenes.
- La aplicación de distintas técnicas de prompting según el tipo de tarea fue clave para optimizar los resultados.
- La solución es viable para ser usada en contextos reales de búsqueda laboral con mínima intervención técnica del usuario.
