Servicios para el proyecto:

-Active directory
-DHCP
-DNS
-FTP
-Audio
-Video
-HTTPS
-NFS
-Nagios

# 1 Propuesta de CPD

Cal proposar una solució de CPD que contempli -com a mínim- els següents requeriments:
* Ubicación física

  Situación física de la sala en el edificio.

  Para saber donde pondremos nuestro CPD tendremos que descartar estos lugares, para saber si al instalar el CPD lo hacemos correctamente. Deben evitarse áreas con fuentes de interferencia de radiofrecuencia, lugares con maquinaria pesada o almacenes con gas inflamable o nocivo, y evitar zonas con riesgo de inundaciones, como los sótanos, plantas bajas o salas de espera, ya que son más propensas al vandalismo o los sabotajes y la última planta, evitando desastres aéreos, etc. Por último evitar lugares con vehículos de motor por la propagación del fuego. En conclusión, la ubicación más conveniente se sitúa en las plantas intermedias de un edificio.

* Sistemas de climatización (aire acondicionado). Niveles de temperatura, humedad y limpieza del aire.

  Hay una inmensidad de información y recomendaciones en internet, pero mayoritariamente está recomendado mantener la temperatura entre 18 y 27 grados, como he mencionado antes al haber muchísima información nos hemos basado en la información que más se menciona, es recomendado mantener la humedad entre 40% y 55% o incluso 60%.

* Medidas para dificultar la identificación de la sala.

* Distribución y gestión del cableado.

  El cableado es uno de los elementos más importantes dentro de lo que es el CPD y su estructuración y organización es esencial, los cables irán por debajo del suelo, el suelo técnico es el protagonista de esto. El suelo técnico nos da la capacidad de esconder y ordenar mejorar los cables, además nos permite hacer cambios en cualquier momento sin ocasionar desastres ni nada. En la estructura del CPD el cableado irá por la parte céntrica y posteriormente pasará por debajo.

* Suelo técnico y techo técnico.

  El suelo técnico está elevado y esta elevación facilita la canalización de las instalaciones y el techo técnico está de manera descolgada del techo real para ocultar los cables del CPD, además la refrigeración del CPD saldrá del suelo y al tener un espacio considerablemente grande nos facilitará el trabajo, aparte nos garantiza que el sistema no se colapse por el calor.

* Planos, dibujos, diagramas de los elementos anteriormente citados.

  https://home.by.me/es/project/1da8d444075e08de9ed2e62/proasixcdgrup2?open_planner=true

  (imagen)

  La imagen mostrada es una pequeña representación de cómo funcionará el sistema de la refrigeración, el aire caliente saldrá por la parte céntrica y posteriormente saliendo por el sistema de aire acondicionado por la parte superior, el aire frío saldrá de unas rejillas instaladas en el suelo de la habitación del CPD, por eso el suelo técnico y el techo técnico son importantes para el espacio requerido. Y de la misma manera irían los cables, saldrían de la parte céntrica (donde empiezan los cables y que está marcado con las flechas rojas) y luego se irían por la zona de debajo.

* Estructuración de los racks (mínimo 2 racks).

  El Rack estaría estructurado por 1 router, 2 patch panels, 1 switch, 1 SAI, 1 Fuente de alimentación y por último 4 servidores.

* Infraestructura IT:

* Servidores: Número y tipo de modelo.

  En nuestro caso hemos pensado en hacer 4 Servidores (1 para la LAN, 1 para la red fuera de la LAN donde estará alojado el servicio de streaming y web y por último 1 servidor de Firewall).

* Patch panels.

  Vamos a utilizar dos patch panels para la organización.

* Switches.

  En nuestro caso solo vamos a utilizar 1 solo Switch dentro de la LAN.

* Planos y diagramas de cómo están distribuidos los racks con los servidores, patch panels y switches.

  https://online.visual-paradigm.com/es/diagrams/features/rack-diagram-software/

  (imagen)

* Infraestructura eléctrica:

* Sistemas de alimentación redundante.

  Hemos calculado aproximadamente cuanto consume mensualmente todo el rack pensando en 4 servidores, 1 router, 1 switch y 2 patch panels y sería aproximadamente unos 560 kWh.

* SAIS. Cálculo de cuántas baterías o componentes para tener los servidores operativos sin corriente eléctrica y tiempo que queréis de funcionamiento sin señal eléctrica en los servidores.

  Seguidamente viendo lo que consume mensualmente en caso de no haber luz necesitas mínimo 1 SAI de alta capacidad (aproximadamente 1500VA).

* Seguridad física y lógica:

* Física:

  * Elementos de control de acceso a incorporar en el CPD.

    Utilizaremos unas tarjetas de acceso que únicamente tendrá el departamento de IT para poder acceder a la sala de CPD.

  * Videovigilancia.

    La videovigilancia contrataremos a un servicio especial para poder mantener todo con una seguridad eficaz y mantener los datos a salvo, por ejemplo Securitas Direct podría ser una de las tantas opciones, pondremos alrededor de 10 cámaras de seguridad, tenemos en cuenta que precio podría oscilar entre 100 € y 500 € por los equipos instalados y después de la instalación hay que tener en cuenta el coste mensual y el mantenimiento, lo bueno es que la instalación es gratuita.

  * Sistemas prevención, detección y de extinción de incendios.

    Todas las habitaciones estarán dotadas de detectores de humo y con sus supuestos aspersores, sabiendo que cualquier persona pudiera sabotear la seguridad hemos decidido no arriesgarnos y tener todo asegurado a un incendio. Ya en el tema eléctrico hemos instalado 4 extintores en la habitación principal con el CPD por si surge algún imprevisto y en la sala de energía. ¿Porque tantos? Por el tamaño del propio CPD imaginemos que el fuego se propaga hay que tener suficientes extintores para poder apagar el fuego.

  * Vías de evacuación.

    Hay dos pasillos principales que son las vías de escape, digamos que se produce un incendio y un trabajador está en la sala de energía y no hubiera un pasillo tendría que recorrer la habitación del CPD y posteriormente salir, esto quiere decir que hay mayor riesgo de que el trabajador pierda la vida. Los pasillos se encargan de dividir a los empleados y que su salida sea exitosa.

  * Diagramas, planos y fotografías de toda la seguridad física incorporada.

  (imagen)

  Como podemos apreciar en las imágenes hemos intentado hacer una distribución segura y efectiva principalmente. Empezando por la habitación 1 (la del CPD) estaría compuesta por los extintores anteriormente mencionados y las cámaras de vigilancia que cubrirán todas las esquinas de cualquier sabotaje de dicha CPD. La habitación 6 (zona de alimentación) de igual manera estará vigilada por 4 cámaras y con un extintor. La habitación 2 y 5 serían zonas de escape en caso de incendio al ser dos se reparten el trabajo de sacar a los empleados, la habitación 2 con su cámara cubrirá la entrada y salida de todo el pasillo sin necesidad de poner más cámaras y gastar más, esto se aplica también en la habitación 5.

* Lógica:

  * Restricción de acceso por autorización.

    Se bloquearán todas las conexiones externas no permitidas por la empresa a la LAN y se restringirán de nuestra red hasta que se diga lo contrario, pero en cambio con el DMZ se permitirá todo el tráfico hacia este hasta que haya algún comportamiento extraño o alguna vulnerabilidad.

  * Firewalls.

    De firewalls tendremos dos ubuntus servers que utilizaran ufw con IPTABLES para poder tener una buena seguridad donde habrá un DMZ que tendrá el servidor web y el de streaming y video.

  * Monitorización.

    Para la monitorización de la red utilizaremos Nagios para los ordenadores utilizaremos Elasticsearch and Kibana.

  * Copias de seguridad/Backups.

    Las copias de seguridad se harán a mano pero las programaremos para que se hagan determinados días.

  * RAIDS.

* Prevención de riesgos laborales:

  * Medidas aplicadas en materia de prevención de RRLL en el CPD.

    Para tener un plan de prevención tenemos que tener en cuenta diversos factores para poder evitar desgracias con anticipación, los elementos son: precauciones a electricidad estática, cortes, aplastamiento, bacterias, cortocircuito o fuego. En una habitación donde se ubica el CPD hay que tener precaución de los peligros ya mencionados anteriormente, por lo tanto, hay diversas soluciones, poner carteles de peligro por electricidad o utilizar equipo especial para poder evitar cortes, la higiene también es importante para poder estar limpios de bacterias. Cabe recalcar la aparición de un incendio es un elemento a tener muy en cuenta y a esto nos referimos con tener métodos de extinción por supresión de oxígeno, combustible, de calor o proyección de sustancias químicas y hablando de sistemas de extinción: extintores, bocas de incendios o aspersores automáticos. Además, si se produce algún accidente hay que estar preparados con material de primeros auxilios como: tratamiento de hemorragias, tratamiento de quemaduras, urgencias oculares, sustancias tóxicas, porque nunca se sabe lo que puede pasar, por lo tanto, hay que estar alerta las 24/7.

* Sostenibilidad:

* Cómo optimizar el consumo de energía.

  Gestión inteligente de la refrigeración: Utiliza sistemas de refrigeración con control de precisión que ajusten la temperatura en función de la carga de trabajo.
  Optimización de la distribución de energía: Asegúrate de que la distribución de energía sea eficiente.
  Utiliza sistemas de alimentación ininterrumpida (SAI/UPS) de alta eficiencia.

* Uso de energía verde para el CPD.

  Contratación de suministro de energía renovable: Contratos de suministro de energía con compañías que la electricidad proviene de fuentes renovables.

* Ahorro en longitud de cableado.

  Distribución de equipos: La ubicación de los equipos de red y servidores.
  Tecnologías de conexión avanzadas: Uso de tecnologías como la fibra óptica para conexiones de larga distancia.

* Sistemas de circulación de aire que aprovechen condiciones naturales.

  Sistemas híbridos: Combinación de sistemas de refrigeración tradicionales con soluciones de free cooling para maximizar la eficiencia energética.

* Parada de equipos de comunicaciones cuando no hay carga.

  Identificación de períodos de baja demanda: Analiza los patrones de tráfico y uso de los servicios para identificar períodos donde la carga de trabajo es menor.

* Equipos de bajo consumo energético.

  Configuración del BIOS y del sistema operativo: Configura los equipos para maximizar la eficiencia energética.

* Implementación del CPD en la nube AWS con los servicios utilizados (mínimo de 4 - los servicios de audio, video y bases de datos se valoran en los otros bloques).

# Instalación de servicio de audio (Icecast2/Darkice)

## Icecast2
