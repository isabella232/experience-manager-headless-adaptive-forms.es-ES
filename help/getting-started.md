---
title: Introducción a Forms adaptable sin encabezado
description: Introducción a Forms adaptable sin encabezado
keywords: sin encabezado, formulario adaptable, tutorial
hide: true
source-git-commit: 0127f8ddede38083f0932b0e8d7efdd0dd77c3a6
workflow-type: tm+mt
source-wordcount: '352'
ht-degree: 8%

---


# Introducción a Forms adaptable sin encabezado

Este tutorial le proporciona un marco de trabajo completo para crear un formulario adaptable sin encabezado. El tutorial está organizado en un caso de uso y en varias guías. Cada guía le ayuda a aprender y agregar nuevas características al formulario adaptable sin encabezado que se crea en este tutorial. Después de cada guía, tendrá un formulario adaptable sin encabezado en funcionamiento. Al final de este tutorial, podrá:

* Crear un formulario adaptable sin encabezado
* Agregar reglas empresariales al formulario
* Usar la interfaz de usuario de material de Google para aplicar estilo al formulario
* Rellenar previamente el formulario 
* Incrustar el formulario en una página web

También generará una comprensión de la arquitectura, los artefactos disponibles y la estructura JSON de los formularios adaptables sin encabezado.

**El recorrido comienza con el aprendizaje del caso de uso**:

Raya Tan, miembro del departamento de asuntos exteriores de un país conocido por su belleza natural y su próspera economía turística, supervisa la distribución de formularios de visa a los turistas. Estos formularios están disponibles en el sitio web del departamento, las aplicaciones móviles nativas y en formato PDF, con múltiples opciones de idioma para que los turistas elijan. Sin embargo, administrar y escalar estos formularios en diferentes plataformas y tecnologías puede ser un desafío.

Con el fin de mejorar la eficiencia y la flexibilidad de su proceso de solicitud de visados, el Departamento de Asuntos Exteriores ha decidido adoptar un enfoque de formularios adaptables sin encabezado. Esta arquitectura disociada separa el front-end del back-end, lo que permite una mayor personalización y escalabilidad. El departamento tiene previsto utilizar los componentes de React de la interfaz de usuario de Google Material para mejorar la experiencia del usuario con los formularios, mientras utiliza funciones back-end como firmas digitales, integración de datos, administración de procesos empresariales, documentos de registro y análisis de uso.

La forma más popular entre los turistas es el formulario &quot;Contáctenos&quot;, que se utiliza para hacer diversas preguntas y consultas. Como tal, el departamento de asuntos exteriores ha elegido empezar a implementar el método de formularios adaptables sin encabezado con este formulario. Este tutorial le guiará a través del proceso de creación del formulario de contacto con nosotros mediante esta nueva arquitectura. El resultado final tendrá este aspecto:

![Formulario adaptable sin encabezado](assets/contact-us-headless-adaptive-forms.png)