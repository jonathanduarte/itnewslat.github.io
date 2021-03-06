---
layout: posts
color-schema: red-dark
date: '2018-04-25 14:23 -0400'
published: true
superNews: false
title: >-
  VMware AppDefense presenta seguridad de privilegios mínimos para aplicaciones
  en contenedores
image: >-
  https://raw.githubusercontent.com/itnewslat/assets/master/img/540x320/Ton-Corn-p.jpg
detail-image: >-
  https://raw.githubusercontent.com/itnewslat/assets/master/img/1024x680/Ton-Corn-g.jpg
categories:
  - Colombia
tags:
  - Seguridad
---
**Por: Tom Corn, vicepresidente sénior y gerente general de productos de seguridad de VMware**

A medida que el gasto mundial en seguridad de TI continúa aumentando, las probabilidades _de ser víctima de una filtración de datos han aumentado de 1 a 4._ A pesar de la abundancia de productos de seguridad existentes en el mercado y de los grandes presupuestos para comprarlos, las empresas no son significativamente más seguras. 

La estandarización del delito cibernético ha hecho posible que prácticamente cualquier persona con una computadora pueda lanzar un ataque complejo contra una empresa y todos los días se están desarrollando nuevos ataques. Esto significa que el enfoque continuo en la búsqueda de amenazas sigue siendo relativamente ineficaz para acabar con los desafíos más extensos que enfrenta la seguridad de TI.

Es una perspectiva aterradora para los CISO que tienen que asegurar las aplicaciones y los datos que viven en entornos de TI cada vez más dinámicos y distribuidos. Y a medida que más empresas adoptan procesos de desarrollo de aplicaciones ágiles y modernos, el problema de implementar la seguridad a la velocidad del negocio se ve agravado: la seguridad a menudo se ve como un obstáculo para el progreso.

Creamos VMware AppDefense para abordar estos mismos problemas, con un enfoque único que aprovecha la capa de virtualización para proteger las aplicaciones “asegurando lo bueno” en lugar de “persiguiendo lo malo”. AppDefense aprovecha la posición única de VMware en la capa de virtualización con el fin de comprender para qué fueron suministradas o destinadas las aplicaciones y entonces supervisar contra ese estado. Si se manipulan las aplicaciones, AppDefense puede usar la capa de virtualización para automatizar la respuesta. Este nuevo modelo es a la vez simple y potente, reduce drásticamente la superficie de ataque y brinda un contexto y controles más ricos para los controles de seguridad de una organización.

Y si pensaba que nos detendríamos solo en el hipervisor, se equivoca.

Hoy nos complace anunciar otro importante paso adelante para AppDefense, que es la posibilidad de asegurar cargas de trabajo en contenedores, lo que demuestra nuestro compromiso continuo con la seguridad de las aplicaciones que se ejecutan en cualquier infraestructura. La propuesta de valor de AppDefense de proporcionar seguridad fundamental para aplicaciones de centros de datos ha resonado con los clientes. 

Quieren aplicar AppDefense en toda la empresa, lo que incluye las cargas de trabajo que se ejecutan en VMware vSphere, así como las plataformas de tiempo de ejecución de los contenedores. AppDefense es ahora la única solución que puede abarcar cargas de trabajo virtualizadas y cargas de trabajo en contenedores con un enfoque invariable para descubrir contexto, establecer reglas y administrar alertas y soluciones. Al integrar en AppDefense la aptitud para contenedores, los clientes pueden comenzar a estandarizar la aplicación de privilegios mínimos en todas sus aplicaciones. Profundicemos un poco más en esta noticia.

**DevSecOps cambia las reglas de trabajo para la seguridad de TI******

Debido a los avances en el centro de datos moderno, las aplicaciones y la infraestructura evolucionan hoy más rápido que nunca. Esto crea un desafío único para los equipos de seguridad. Los métodos manuales que usan los equipos de seguridad para revisar y gestionar los cambios ya no pueden seguir el ritmo cuando se reconstruyen y se vuelven a implementar regularmente aplicaciones completas. Eso significa que si un equipo de seguridad fue lo suficientemente afortunado para comprender lo que originalmente hacía la aplicación (y pudo aplicar las normas de seguridad correspondientes), en realidad no saben lo que hace hoy la aplicación.

Con AppDefense, aprovechamos estas herramientas de automatización para nuestro beneficio. Al integrarse en el canal de CI/CD con herramientas de aprovisionamiento y marcos de automatización, y alinear la condición esperada con la supervisión del tiempo de ejecución, AppDefense puede mantener un mapa acreditado de la condición prevista que se mantiene sincronizado con los equipos de aplicaciones ágiles. Esto permite un enfoque DevSecOps.

Este enfoque se extiende fácilmente a los contenedores que surgieron por la automatización y mecanismos muy declarativos para la condición buscada; manifiestos de contenedores. Entonces, al integrar las soluciones de seguridad de contenedores, podemos extender nuestro modelo al mundo nativo de la nube.

AppDefense ha ido más allá de solo respaldar el inventario de VMware vCenter para incluir ahora cargas de trabajo de contenedores, que se ejecutan en todas las plataformas (servidores virtuales, servidores bare metal de un solo inquilino y plataformas en la nube). AppDefense expone una API para aceptar el contexto de la carga de trabajo de los sistemas de orquestación de contenedores, y también configura las reglas impuestas por los proveedores de seguridad de contenedores que se ejecutan dentro del entorno de tiempo de ejecución.

Estamos orgullosos de anunciar que Aqua Security es el primer socio con el que estamos trabajando en este área (lea su comunicado de prensa aquí). Aqua proporciona garantía de tiempo de ejecución para contenedores evaluando y aplicando el comportamiento cuando el contenedor se ejecuta. Enviarán contexto de los contenedores (“perfiles de tiempo de ejecución”) a AppDefense para que VMware pueda gestionar/mantener los ámbitos de seguridad en todo el centro de datos. 

Aqua también enviará alertas de cumplimiento a la consola de AppDefense para su administración y remedio. La integración de Aqua Security estará generalmente disponible para los clientes de AppDefense en el segundo trimestre del año fiscal 2019 de VMware.

Como hemos visto, la gran mayoría de los problemas de seguridad de la actualidad no se pueden resolver con un único producto o tecnología, ya que son de naturaleza más fundacional y arquitectónica. Con nuestros continuos avances y el creciente impulso de AppDefense, VMware está desempeñando un papel aún mayor para ayudar a que la seguridad sea una parte intrínseca de la red y el tejido de aplicaciones en el que se construyen las empresas.