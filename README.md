# Hackathon For Good: La Región de AWS en España al Servicio de la Sociedad

Los participantes del Hackathon tendrán que hacer un fork de este repositorio y crear un repositorio público en GitHub
con su propio nombre de usuario (un repositorio único por cada equipo).

A continuación, os mostraremos en este README.md las diferentes secciones que deberán completarse, resaltando los puntos
indicados para la solución/implementación. Por favor, sentiros libres de crear más subsecciones si fuese necesario. La
idea es comprender qué componentes habéis utilizado y cuál es la esencia de vuestra propuesta.

## Descripción del Proyecto

**Reto Seleccionado: Cruz Roja**

TakeNoteAI ofrece una solución innovadora que permite a Cruz Roja recopilar información de los usuarios de manera
automatizada, eliminando la necesidad de escribir datos manualmente. Esto permite que los usuarios de la organización se
enfoquen en tener conversaciones significativas y establecer relaciones efectivas con las personas afectadas. Además,
TakeNoteAI es altamente personalizable y se puede adaptar a las necesidades específicas de área de la organización

En esta sección podéis realizar una descripción más detallada de vuestra aplicación/solución, indicando el caso de uso,
los pros y contras de vuestra implementación, etc.

------

TakeNoteAI se enfoca en mejorar la eficiencia de la toma de datos en organizaciones como Cruz Roja, permitiendo a los
usuarios de la organización concentrarse en establecer relaciones efectivas con las personas afectadas.

El caso de uso se basa en el escenario en el que los trabajadores de la Cruz Roja necesitan recopilar información
de las personas afectadas, pero no quieren desviarse de su objetivo principal: brindar apoyo a las personas.

Para lograr este objetivo, utilizamos una variedad de tecnologías de AWS, incluyendo S3 para almacenar los archivos de
audio, EC2 para el servidor y Transcribe para convertir el audio a texto, OpenAI - ChatGPT para comprender las acciones
necesarias y obtener los datos requeridos, y MongoDB para almacenar los datos obtenidos.

**Los pros de nuestra implementación son**: la automatización de la toma de datos permite que los trabajadores de Cruz
Roja se concentren en lo que realmente importa y la adaptabilidad a las necesidades específicas de cada área de la
organización.

Sin embargo, **también hay algunos contras que deben tenerse en cuenta**: la precisión de la transcripción de voz a
texto puede variar según la calidad de la grabación y la complejidad del discurso. El sistema trabaja con internet para
conectarse con los servicios por lo que puede ser un desventaja en lugares con poca conexión a internet.

## Diagrama de Arquitectura

Adjuntar una imagen del diagrama de arquitectura de la solución.

![Screenshot](takenote-arch.png)

## Descripción Técnica

Una visión general de:

**¿Qué tipo de arquitectura habéis planteado?** Por lo general, las arquitecturas modernas de aplicaciones suelen
utilizar microservicios y APIs para conectar los servicios, eso no quiere decir que nos podemos encontrar con
arquitecturas de N-capas, arquitecturas monolíticas, de microservicios o basadas en eventos. Dependerá de vuestro caso
de uso, pero nos gustaría conocer cuál ha sido vuestra elección.

**¿Qué tecnologías AWS se han utilizado?**

## Demo Vídeo

Link del video en Youtube:

## Team Members

* Jose Chipana Tica - josepaulct@gmail.com
* Nelson Moncada - juniormoncada17@gmail.com
 
