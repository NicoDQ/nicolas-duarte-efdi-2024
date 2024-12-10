---
hide:
    - toc
---

# Proyecto Final: WHTMet - Estación Meteorológica IoT

# Diseño y Funcionalidad

El diseño y funcionalidad de WHTMet está basado en un enfoque abierto y modular, utilizando tecnologías accesibles y de código abierto para asegurar que el sistema sea no solo efectivo, sino también personalizable y escalable para diferentes contextos. La integración de tecnologías como Proxmox, Node-RED, InfluxDB, PostgreSQL, ESP32, y sensores de bajo costo ha permitido crear una solución flexible, eficiente y sostenible, que puede ser adaptada fácilmente por comunidades rurales o tecnológicas para monitorear plantaciones de eucalipto y otros ecosistemas forestales.

## Proxmox

![Imagen de Proxmox](../images/PF2/imagenesTec/proxmox.png#mt02){ align=left }


Proxmox es una plataforma de virtualización de código abierto que se utiliza en WHTMet para la gestión de servidores y máquinas virtuales. En el contexto del proyecto, Proxmox permite crear un entorno centralizado y eficiente para gestionar y almacenar los datos climáticos recolectados por los sensores distribuidos en las plantaciones. La capacidad de virtualizar múltiples entornos dentro de una sola máquina física optimiza el uso de recursos y proporciona una base sólida para futuras expansiones del sistema, al permitir la creación de entornos dedicados para diferentes módulos de software sin la necesidad de hardware adicional.

## Mosquitto MQTT

![Imagen de MosquittoMQTT](../images/PF2/imagenesTec/mosquitto.png#mt02){ align=left }

Se utiliza Mosquitto como el broker MQTT. Mosquitto es un servidor de código abierto, ligero y altamente eficiente para la implementación de la comunicación basada en el protocolo MQTT. Es ampliamente utilizado en sistemas IoT debido a su simplicidad y bajo consumo de recursos, lo que lo hace ideal para entornos con dispositivos limitados en términos de memoria y potencia de procesamiento, como los sensores distribuidos en las plantaciones.

## Node-RED

![Imagen de Node-Red](../images/PF2/imagenesTec/node-red.png#mt02){ align=left }


Node-RED es una herramienta de programación visual de código abierto que facilita la integración y automatización de flujos de datos. En WHTMet, Node-RED se utiliza para conectar y gestionar los datos que se recopilan desde los sensores distribuidos. A través de un flujo de trabajo visual, los datos de temperatura, humedad, viento y otras variables climáticas se capturan, procesan y envían a las bases de datos. Además, Node-RED permite la creación de alertas y procesos automáticos, como notificaciones en caso de que los valores de ciertas variables superen umbrales críticos, lo que facilita la toma de decisiones en tiempo real.

## InfluxDB y PostgreSQL

![Imagen de InfluxDB](../images/PF2/imagenesTec/influxdb.png#mt02){ align=left }

InfluxDB es una base de datos especializada en la gestión de datos temporales, ideal para almacenar las mediciones climáticas que se recopilan a lo largo del tiempo. En WHTMet, se utiliza para registrar de manera eficiente y escalable las mediciones en tiempo real de los sensores, lo que permite un análisis profundo de las condiciones climáticas en las plantaciones de eucalipto.


![Imagen de PostgreSQL](../images/PF2/imagenesTec/postgresql.png#mt02){ align=left }

Por otro lado, PostgreSQL, una base de datos relacional de código abierto, se emplea para gestionar otros aspectos del sistema que requieren un almacenamiento estructurado, como los datos de usuarios, configuraciones y coordenadas geográficas de los puntos de monitoreo. Ambos sistemas de bases de datos trabajan de manera conjunta para ofrecer un almacenamiento eficiente y accesible de grandes volúmenes de datos climáticos.

## ESP32 y Sensores


![Imagen de ESP32](../images/PF2/imagenesTec/esp32.png#mt02){ align=left }

El ESP32 es un microcontrolador de bajo costo y alto rendimiento que se utiliza para conectar los sensores climáticos con la red y procesar las mediciones antes de enviarlas a las bases de datos. Su bajo consumo energético lo hace ideal para entornos remotos donde el acceso a fuentes de energía es limitado. Además, el ESP32 es modular y adaptable, lo que permite a los usuarios personalizar el sistema según sus necesidades, como agregar más sensores o integrar nuevas tecnologías sin complicaciones.

![Imagen de SHT31](../images/PF2/imagenesTec/sht31.png#mt02){ align=left }

Los sensores de bajo costo, que miden variables como la temperatura, la humedad y el viento, proporcionan los datos necesarios para optimizar la gestión de las plantaciones de eucalipto, permitiendo a los gestores tomar decisiones informadas sobre el riego y el cuidado forestal.


## Diseño Abierto y Personalización

El sistema de WHTMet se ha desarrollado bajo un enfoque de diseño abierto, lo que implica que todos los componentes y planos están disponibles para ser modificados y personalizados por cualquier comunidad o desarrollador. Esta apertura fomenta la colaboración y la innovación, permitiendo que los usuarios adapten el sistema a sus necesidades específicas, como la incorporación de sensores adicionales o la modificación de la estructura física. El acceso a los planos y a la documentación técnica también facilita la fabricación local y el uso de materiales reciclables, lo que refuerza la sostenibilidad y la autonomía de las comunidades.

## Distribución Modular

El sistema está diseñado de forma modular, lo que permite distribuir los sensores en puntos clave de las plantaciones para capturar datos georreferenciados. Aunque, por el momento, las coordenadas se ingresan manualmente, el diseño modular facilita la futura incorporación de un sistema de geolocalización automática, lo que optimizará la recolección de datos y su precisión. Esta distribución también permite una escalabilidad fácil, ya que los sensores y módulos adicionales pueden integrarse sin necesidad de reestructurar todo el sistema.

## Sostenibilidad y Eficiencia Energética

La sostenibilidad es un principio fundamental del diseño de WHTMet. En cuanto a los materiales, se ha priorizado el uso de cubiertas reciclables para proteger los circuitos y componentes electrónicos, contribuyendo a la reducción de residuos y promoviendo el uso responsable de los recursos. Además, el sistema ha sido diseñado con un enfoque en bajo consumo energético, utilizando componentes como el ESP32 y sensores de bajo consumo que aseguran que el sistema pueda operar durante largos períodos con una baja huella ecológica.

## Escalabilidad

Uno de los aspectos clave de WHTMet es su capacidad de escalabilidad. El sistema modular permite adaptarse a diferentes tamaños de plantaciones, desde pequeñas explotaciones agrícolas hasta grandes plantaciones comerciales, garantizando que la solución pueda ser utilizada en diversos contextos sin perder eficiencia. Esta escalabilidad también asegura que el sistema pueda evolucionar a medida que surjan nuevas necesidades tecnológicas o ambientales, lo que lo convierte en una solución flexible a largo plazo.
