---
title: "Threat Jammer, mi nuevo proyecto"
categories: startup
layout: post
---


## ¿Por qué Threat Jammer?
Llevo varios años haciendo productos de Threat Intel y muchos más desarrollando servicios en la nube consumidos a través de una API. ¿Por qué un nuevo servicio como [Threat Jammer](https://threatjammer.com)? ¿Qué tiene de especial? ¿Cómo empezó todo esto? ¿Y qué nos ofrecerá en el futuro?

<p align="center">
  <img src="https://threatjammer.com/threatjammer-risk-score.png">
</p>

## ¿Cómo empezó todo?
Después de dejar mi anterior empresa (que por cierto [adquirió mi empresa de threat intel](https://www.geekwire.com/2020/auth0-makes-first-ever-acquisition-launch-new-tools-protect-automated-cyberattacks/)) pasé varios meses revisando estudios y papers de universidades. Tienen un enfoque más teórico y menos ejecutivo del problema de la detección de amenazas que el que solemos tener en la industria, pero las conclusiones son perfectamente válidas.

Aunque la mayoría de estos estudios tienen una aplicación algo limitada en escenarios de "ciberguerra real", encontré enfoques de los problemas que podrían ser perfectamente válidos si se "aterrizan" adecuadamente en un entorno profesional.

Cuando nos enfrentamos a la detección de una amenaza, debemos ser conscientes de los siguientes retos:

- Lo que ayer era válido para detectar una amenaza puede no serlo hoy: la variable **tiempo** es fundamental.
- La detección de amenazas es un problema **multifactorial**: una función de evaluación multifactorial reduce los errores, principalmente los falsos positivos y negativos.
- **La calidad de los datos es crítica**. Es más importante tener buenos datos que muchos datos.

## ¿Qué tiene de especial?
Decidir si un actor va a realizar una acción dañina se convierte en un problema de selección de los mejores datos y los mejores factores en esa función de evaluación. Y ahí es donde [Threat Jammer](https://threatjammer.com) destaca.

Mientras estaba en mi año sabático, cayó en mis manos un artículo sobre cómo Apility (mi anterior empresa) obtenía mejores resultados que otras herramientas OSINT en la detección de amenazas. Se anunció en la [Conferencia Internacional sobre Informática, Redes y Comunicaciones (ICNC) de 2020](https://www.researchgate.net/publication/340306013_IP_Reputation_Analysis_of_Public_Databases_and_Machine_Learning_Techniques) y es una buena lectura. Una vez que mi vanidad quedó satisfecha, me puse manos a la obra para entender por qué mi anterior empresa obtenía mejores resultados que otras herramientas. Mi conclusión es que inconscientemente realicé una evaluación previa de los datos y pude identificar las mejores fuentes de OSINT.

Así que la pregunta ahora era: ¿puedo implementar un servicio que preevalúe automáticamente las diferentes fuentes de datos y luego seleccione las mejores? ¿Puedo crear un servicio que aprenda de las distintas entradas externas y seleccione los mejores factores para utilizarlos en la función de evaluación?

Pues aquí está la respuesta: **Bienvenido a [Threat Jammer](https://threatjammer.com)**.

## Threat Jammer en pocas palabras
Todas las empresas que ofrecen servicios digitales tiene un enfoque diferente para la detección de abusos porque los modelos de negocio no son los mismos y tampoco sus necesidades. Los ciberdelincuentes siempre están pensando en cómo explotar los servicios. Se convierte en un interminable juego del gato y el ratón por mucho que una empresa dedique recursos a la protección contra los abusos. La respuesta a las nuevas formas de explotar los servicios debe ser ágil, rápida y eficaz.

**Threat Jammer es una herramienta para los creadores de servicios**. Threat Jammer es un conjunto de servicios que actúan como "building blocks" en la estrategia de detección de amenazas de las empresas digitales. Entendemos lo difícil que es encontrar una solución para detectar y bloquear la actividad maliciosa, y por eso nuestros servicios están construidos para resolver este problema: **tú sabes lo que tienes que hacer; nosotros te ofrecemos las herramientas para hacerlo**.

El motor de detección de amenazas (Threat Detection Engine) evoluciona constantemente. Los factores utilizados para detectar y bloquear la actividad maliciosa pueden cambiar con el tiempo. Por ejemplo, la dirección IP del usuario puede variar con el tiempo de un proveedor de red a otro. El nivel de amenaza asociado al proveedor de red puede cambiar con el tiempo, por lo que el nivel de riesgo general del usuario también.

Threat Jammer ejecuta múltiples procesos y recoge de diferentes fuentes datos para mantener la información lo más precisa y fresca. Las evaluaciones realizadas utilizarán siempre la información más actualizada disponible. Como resultado, la precisión del sistema será siempre la más alta, además de reducir los falsos positivos al mínimo.

## ¿Y el futuro?
Hoy inicio un viaje para ofrecer la mejor herramienta de evaluación de riesgos para la industria digital. Sin financiación externa, bootstrapeado íntegramente por mi. Intuyo que será un viaje largo en el que espero que los usuarios me ayuden a entender mejor sus necesidades. Quiero escuchar a los usuarios sobre sus necesidades y cómo pueden utilizar Threat Jammer para mejorar su evaluación de riesgos. 

Los usuarios pueden tener una cuenta gratuita para siempre que les permite utilizar la herramienta sin costo alguno. 

Así que, ¿por qué no te unes en este viaje como usuario de [Threat Jammer](https://threatjammer.com)?
