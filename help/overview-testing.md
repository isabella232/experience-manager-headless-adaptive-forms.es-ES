---
title: Información general sobre formularios adaptables sin encabezado de AEM
description: Los formularios adaptables sin encabezado de AEM Forms proporcionan una forma rápida y eficaz de crear formularios para varias plataformas, incluidos CMS con encabezado o sin encabezado, aplicaciones React, aplicaciones de una sola página (SPA), aplicaciones web, aplicaciones móviles, Amazon Alexa, Google Assistant, WhatsApp y más. Con Formularios adaptables sin encabezado, puede optimizar el proceso de creación de formularios, lo que facilita la recopilación de datos de los usuarios en diferentes dispositivos y plataformas.
solution: Experience Manager Forms
feature: Adaptive Forms
topic: Headless
role: Admin, Developer
level: Beginner, Intermediate
keywords: CMS sin encabezado, formularios adaptables, IU sin encabezado, CMS con encabezado, asistentes de voz, Alexa, bots de chat, arquitectura de WhatsApp
hide: true
hidefromtoc: true
source-git-commit: 78ae6bc3e390d6a8e46d10d3ad3580c4268bf4ed
workflow-type: tm+mt
source-wordcount: '403'
ht-degree: 92%

---

# Introducción

Formularios adaptables sin encabezado de Adobe Experience Manager (AEM) es una solución para crear y administrar los formularios web sin encabezado dentro de la plataforma de Adobe Experience Manager. Esta función permite a las organizaciones crear, publicar y administrar formularios interactivos a los que se puede acceder e interactuar mediante API, en lugar de a través de una interfaz de usuario gráfica tradicional. Los Formularios adaptables sin encabezado de AEM permiten una mayor flexibilidad y escalabilidad en el desarrollo e implementación de formularios, así como una experiencia del usuario mejorada con la posibilidad de adaptar el diseño y la funcionalidad del formulario a sus necesidades específicas. Al utilizar las funciones de la tecnología sin encabezado y de AEM, esta solución proporciona una plataforma sólida para crear, administrar e implementar formularios web para varios casos de uso y aplicaciones.

![Generar y procesar de forma nativa un formulario en cualquier sitio web, aplicación o interacciones no visuales](/help/assets/headless-forms-for-any-device.jpeg)

Los formularios adaptables sin encabezado le ayudan a:

* crear formularios multicanal de alta calidad en el lenguaje de programación que desee
* integrar formularios de forma nativa en sus aplicaciones móviles y de escritorio, sitios web y aplicaciones de chat
* reutilizar los componentes de IU propios con aplicaciones de formularios
* aprovechar la [potencia de Adobe Experience Manager Forms](https://experienceleague.adobe.com/docs/experience-manager-65/forms/getting-started/introduction-aem-forms.html?lang=es)

Además, tiene la libertad de desarrollar sus propios componentes para procesar un formulario con cualquier marco de trabajo de IU y lenguaje de programación de su elección. También puede utilizar los componentes de React disponibles de forma predeterminada para procesar un formulario adaptable sin encabezado.

## Funciones principales

<!-- 

<table style="width:100%;">
  <tr>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px;">
        <img src="/help/assets/01-overview-responsive-forms.jpeg" alt="Card Image 1" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Responsive Forms</h2>
          <p>The adaptive form feature enables you to create a single source for a form that automatically sizes and re-flows on mobile devices.</p>
        </div>
      </div>
    </td>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/01-overview-responsive-forms.jpeg" alt="Card Image 1" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Communication API</h2>
          <p>The adaptive form feature enables you to create a single source for a form that automatically sizes and re-flows on mobile devices.</p>
        </div>
      </div>
    </td>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/02-overview-backend-systems.jpeg" alt="Card Image 2" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Business Process Management</h2>
          <p>Integrate RDBMS, OData, Or Microsoft SOAP services, as well as protocols like Swagger 2.0 to connect to just about anything.</p>
        </div>
      </div>
    </td>
  </tr>
  <tr>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/03-overview-save-and-resume.jpeg" alt="Card Image 3" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Save and resume forms</h2>
          <p>Allow clients to save in-progress forms and return later to complete them, even on another device.</p>
        </div>
      </div>
    </td>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/04-overview-search.jpeg" alt="Card Image 1" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Forms Search and Discovery</h2>
          <p>Let customers easily find relevant forms based on a simple search query, tags, filters, and even geolocation — on any device through a personalized portal, with or without authentication.
          </p>
        </div>
      </div>
    </td>
      <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/04-overview-search.jpeg" alt="Card Image 1" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Forms Search and Discovery</h2>
          <p>Let customers easily find relevant forms based on a simple search query, tags, filters, and even geolocation — on any device through a personalized portal, with or without authentication.
          </p>
        </div>
      </div>
    </td>
  </tr>
  <tr>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/05-overview-analytics.jpeg" alt="Card Image 2" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Form analytics and reporting</h2>
          <p>Out-of-the-box, customizable dashboards make it easy to apply analytics to forms to gain insight for actionable areas of improvement.</p>
        </div>
      </div>
    </td>
    <td style="width:33.33%;">
      <div style="width: 250px; border: 1px solid #ccc; border-radius: 8px; ">
        <img src="/help/assets/06-overview-business-process.jpeg" alt="Card Image 3" style="width:33.33; height: auto;">
        <div style="padding: 20px;">
          <h2 style="margin-top: 0;">Business Process Management</h2>
          <p>Route application submissions through customized workflows and a centralized dashboard for review, approval, and digital signatures by back-office employees — even when employees are on the go on a mobile device.
          </p>
        </div>
      </div>
    </td>
  </tr>
</table>

-->


<div style="display: flex; flex-wrap: wrap; justify-content: space-between; margin: 20px;">
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/01-overview-responsive-forms.jpeg" alt="Icono 1" style="width: 50px; height: 50px;">
        <h2 style="margin-top: 10px;">Encabezado 1</h2>
        <p>Descripción 1</p>
    </div>
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/02-overview-backend-systems.jpeg" alt="Icono 2" style="width: 50px; height: 50px;">
        <h2 style="margin-top: 10px;">Encabezado 2</h2>
        <p>Descripción 2</p>
    </div>
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/03-overview-save-and-resume.jpeg" alt="Icono 3" style="width: 50px; height: 50px;">
        <h2 style="margin-top: 10px;">Encabezado 3</h2>
        <p>Descripción 3</p>
    </div>
        <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/04-overview-search.jpeg" alt="Icono 1" style="width: 50px; height: 50px;">
        <h2 style="margin-top: 10px;">Encabezado 1</h2>
        <p>Descripción 1</p>
    </div>
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/05-overview-analytics.jpeg" alt="Icono 2" style="width: 50px; height: 50px;">
        <h2 style="margin-top: 10px;">Encabezado 2</h2>
        <p>Descripción 2</p>
    </div>
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/06-overview-business-process.jpeg" alt="Icono 3" style="width: 50px; height: 50px;">
        <h2 style="margin-top: 10px;">Encabezado 3</h2>
        <p>Descripción 3</p>
    </div>
    <!-- Add more cards as needed -->
</div>




<div style="display: flex; flex-wrap: wrap; justify-content: space-between; margin: 20px;">
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/01-overview-responsive-forms.jpeg" alt="Imagen 1" style="width: 100%; border-radius: 5px;">
        <h2 style="margin-top: 10px;">Encabezado 1</h2>
        <p>Descripción 1</p>
    </div>
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/02-overview-backend-systems.jpeg" alt="Imagen 2" style="width: 100%; border-radius: 5px;">
        <h2 style="margin-top: 10px;">Encabezado 2</h2>
        <p>Descripción 2</p>
    </div>
    <div style="width: 30%; margin-bottom: 20px; border: 1px solid #ccc; border-radius: 5px; padding: 20px; box-sizing: border-box;">
        <img src="/help/assets/03-overview-save-and-resume.jpeg" alt="Imagen 3" style="width: 100%; border-radius: 5px;">
        <h2 style="margin-top: 10px;">Encabezado 3</h2>
        <p>Descripción 3</p>
    </div>
    <!-- Add more cards as needed -->
</div>



## ¿Quién puede utilizar formularios adaptables sin encabezado? {#who-can-use-headless-adaptive-forms}

Cualquier desarrollador front-end familiarizado con los marcos de trabajo de JavaScript modernos puede utilizar formularios adaptables sin encabezado. Los desarrolladores pueden aprovechar su experiencia existente en lenguajes de front-end como React para crear atractivas experiencias de captura de datos de clase empresarial.

No necesita tener conocimientos previos de Adobe Experience Manager para desarrollar formularios adaptables sin encabezado.

<!-- 
## How to join the early adopter program? {#how-to-join-early-adopter-forms}

The service is available for AEM Forms as a Cloud Service and AEM 6.5.16.0 Forms or later On-Premise term customers and Adobe-Managed Service enterprise customers. Send an email to [headlessadaptiveforms@adobe.com](mailto:headlessadaptiveforms@adobe.com) from your official email ID to join the early adopter program. 

-->