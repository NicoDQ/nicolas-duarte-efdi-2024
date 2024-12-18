---
hide:
    - toc
---

# Proyecto Final: WHTMet - Estación Meteorológica IoT

# Próximos Pasos

En este apartado compartiré algunos de los próximos pasos en el desarrollo de mi proyecto WHTMet, una estación meteorológica IoT diseñada para comunidades rurales. Considero que cada mejora que he planificado tiene el objetivo de hacer el sistema más eficiente, accesible y sostenible.

Entiendo estos próximos pasos son fundamentales para consolidar aún más el prototipo funcional de WHTMet, con miras a una implementación a escala en comunidades rurales. Cada mejora está diseñada para garantizar un sistema accesible, sostenible y capaz de empoderar a sus usuarios, mejorando su capacidad de tomar decisiones informadas sobre sus plantaciones y prácticas agrícolas.

## Diseño de una PCB personalizada para los circuitos

Uno de los primeros retos que voy a asumir es diseñar una PCB (Placa de Circuito Impreso) personalizada. Esto me ayudará a reducir la cantidad de cables y organizar mejor los componentes electrónicos del sistema. Mi idea es integrar todo, desde el microcontrolador hasta los sensores, en una sola placa. Quiero que sea compacta, eficiente y que se pueda fabricar a bajo costo. Además, voy a usar conectores estándar para que los módulos y sensores sean fáciles de conectar, reemplazar o actualizar.

Voy a dedicar tiempo también a garantizar que la PCB sea energéticamente eficiente y esté protegida contra las condiciones adversas que puedan darse en zonas rurales, como humedad o vibraciones. Todo esto lo voy a documentar para que otros puedan replicarlo y, si quieren, adaptarlo a sus necesidades.

Los objetivos principales de este diseño incluyen:

### Optimización del espacio y reducción de cables:
Integrar todos los componentes principales (microcontrolador, sensores, reguladores de voltaje, conectores de alimentación y comunicación) en una sola placa para minimizar el uso de cables y mejorar la organización interna del sistema.

### Compatibilidad con sensores y módulos modulares:
Diseñar la PCB con conectores estándar (como JST o headers) para facilitar la conexión de diferentes sensores y módulos adicionales, promoviendo la personalización y escalabilidad del sistema según las necesidades del usuario.

### Eficiencia energética:
Incorporar rutas optimizadas de alimentación y circuitos de gestión energética para minimizar las pérdidas y garantizar el funcionamiento estable en condiciones de bajo consumo energético.

### Protección y durabilidad:
Diseñar la PCB con un recubrimiento de máscara de soldadura resistente y, de ser posible, incluir un revestimiento conforme (conformal coating) que proteja los circuitos frente a humedad, polvo y vibraciones, aquí también se evalúa el uso del spray de silicona para sellado del circuito.

### Diseño compacto y modular:
Crear una PCB que sea compacta pero con áreas bien delimitadas para cada función (alimentación, comunicación, sensores), facilitando el mantenimiento y la identificación de componentes.

### Preparación para producción escalable:
Diseñar la PCB para que sea fabricable en procesos estándar de bajo costo, asegurando la posibilidad de producir en mayores volúmenes si el sistema se replica ampliamente.

### Pruebas de diseño y validación:
Simular y validar el diseño con herramientas de software como KiCad o Eagle antes de la fabricación, realizando prototipos iniciales para pruebas de funcionalidad y compatibilidad en el entorno real.

### Documentación completa:
Generar una documentación completa del diseño de la PCB (esquemáticos, BOM y archivos Gerber) y ofrecerla bajo licencias abiertas, para que pueda ser replicada y adaptada por otros usuarios interesados en el proyecto.

## Revisión y mejora del diseño de la caja que alberga los circuitos

El diseño de la caja es otro aspecto que necesito reversionar. Estoy pensando en usar materiales más sostenibles, como bioplásticos o incluso reciclados, que sean resistentes a la intemperie y a temperaturas extremas. También voy a trabajar en el sellado, usando juntas de silicona (en principio) para garantizar que el agua, el polvo y los pequeños animales no entren.

Además, quiero que sea fácil de abrir y mantener, así que estoy evaluando paneles desmontables o bisagras selladas. No menos importante, es de mi interés agregar algunos respiraderos con filtros hidrofóbicos para evitar condensación sin comprometer la protección. La caja debe ser funcional, modular y duradera, y planeo probarla en campo para asegurar que cumpla con todas estas expectativas.

Con lo anterior, busco que el diseño de la caja que protege los circuitos sea reversionado con un enfoque en resiliencia, modularidad y sostenibilidad. Los principales objetivos de esta revisión son:

### Materiales y durabilidad:
Evaluar el uso de materiales reciclados o bioplásticos para reducir el impacto ambiental, garantizando resistencia a la intemperie, como exposición a la radiación UV, lluvia y temperaturas extremas.
Implementar un acabado con recubrimientos impermeables y resistentes al desgaste, como esmaltes protectores que aumenten la vida útil de la caja.

### Diseño modular:
Reconfigurar la caja para permitir un acceso rápido y sencillo a los componentes internos mediante paneles extraíbles o bisagras selladas. Esto facilitará tareas de mantenimiento y reemplazo de partes sin comprometer la protección del sistema. Así como tomar en cuenta el punto anterior, de la PCB realizada a medida, para ajustar aún más las dimensiones de la caja.

### Mejora del sellado:
Incorporar juntas de goma o silicona en los bordes y puertos de la caja para garantizar un cierre hermético que proteja contra polvo, humedad y plagas. Adicionalmente, el uso de sprays de silicona ayudará a reforzar la impermeabilidad.

### Sistema de ventilación pasiva:
Integrar un sistema de ventilación pasiva mediante pequeños respiraderos con filtros hidrofóbicos, que permitan el intercambio de aire para evitar la condensación interna sin exponer los componentes al agua o al polvo.

### Personalización y escalabilidad:
Diseñar la caja con ranuras o espacios predefinidos para expandirla fácilmente, permitiendo la inclusión de nuevos sensores o módulos según las necesidades de los usuarios a futuro.

### Sistemas de montaje:
Optimizar y brindar más opciones de instalación mediante soportes ajustables para montaje en postes, paredes o incluso estructuras temporales, asegurando su adaptabilidad a diferentes contextos rurales.

### Validación ergonómica y pruebas de campo:
Realizar pruebas en entornos reales para asegurar que el diseño sea intuitivo para los usuarios finales, incluyendo ajustes en el peso, tamaño y facilidad de manipulación.

### Conectividad y accesibilidad de datos

La conectividad es clave para este proyecto. Mi idea es tomar como base lo comentado por Eduardo y utilizar redes Mesh con ESP32 para cubrir áreas más grandes sin depender de infraestructura costosa. También quiero añadir almacenamiento local, como una tarjeta SD, para que los datos no se pierdan si hay interrupciones de internet. Por último, sería ideal habilitar actualizaciones remotas de firmware para evitar tener que estar físicamente en cada estación al hacer ajustes.

### Mantenimiento sencillo y accesible

**Reemplazo fácil de componentes:** Diseñar el sistema de manera que los usuarios puedan reemplazar partes defectuosas sin necesidad de conocimientos técnicos avanzados, utilizando un sistema de conectores estándar y componentes modulares.
   
**Instrucciones claras para el mantenimiento:** Crear manuales y tutoriales accesibles, que no solo describan la instalación inicial, sino también cómo realizar el mantenimiento preventivo y reparar problemas comunes.

### Optimización energética y gestión eficiente de recursos

**Uso de energías renovables:** Además de los paneles solares, explorar la posibilidad de integrar pequeñas turbinas eólicas o sistemas de energía cinética (por ejemplo, generadores de baja energía que aprovechan el viento o el movimiento) para garantizar la autosuficiencia energética en diferentes condiciones ambientales.

**Gestión inteligente de energía:** Implementar un sistema de gestión de energía que regule el consumo del dispositivo, priorizando el uso de energía renovable y almacenada, y reduciendo el consumo en períodos de baja demanda.

### Resiliencia ante condiciones climáticas extremas

**Carcasa resistente y protección ante condiciones adversas:** Diseñar una caja protectora que sea resistente al agua, polvo y temperaturas extremas, asegurando que el sistema funcione sin problemas en entornos rurales con condiciones climáticas variables.

**Protección contra sobretensiones:** Incorporar mecanismos de protección para evitar daños en los componentes electrónicos por fluctuaciones o picos de voltaje, algo que es común en áreas sin infraestructura eléctrica estable.

### Facilidad de expansión y escalabilidad

**Sistema escalable:** Permitir que el sistema pueda ser fácilmente ampliado para monitorear más parámetros o conectar múltiples estaciones en una red, ofreciendo la posibilidad de cubrir grandes áreas de plantaciones o integrar datos de diversas fuentes para un análisis más completo.

**Compatibilidad con otras tecnologías abiertas:** Asegurar que el sistema sea compatible con otros dispositivos y plataformas de código abierto, como plataformas de agricultura de precisión o redes de sensores, para que pueda integrarse fácilmente con otras soluciones tecnológicas de los usuarios.

### Datos abiertos y análisis predictivo

**Plataforma de datos abiertos:** Desarrollar una plataforma de datos abiertos donde los usuarios puedan compartir sus datos con otros productores o investigadores. Esto fomenta la colaboración y el uso compartido de información climática para mejorar la toma de decisiones a nivel comunitario.

**Análisis predictivo:** Utilizar herramientas de análisis de datos para generar pronósticos climáticos basados en los datos históricos y en tiempo real, lo que permitiría a los usuarios anticipar condiciones adversas y ajustar sus prácticas de manera proactiva.

### Evaluación de impacto y retroalimentación

**Impacto en la productividad agrícola:** Medir el impacto directo de las estaciones meteorológicas en la toma de decisiones agrícolas, como la optimización del uso del agua, la reducción de costos operativos y el aumento de la producción.

**Recolección de retroalimentación:** Implementar un sistema de retroalimentación continuo, donde los usuarios puedan informar sobre el rendimiento del sistema, posibles mejoras y nuevas funcionalidades que les gustaría ver, garantizando que el sistema evolucione con las necesidades de la comunidad.

