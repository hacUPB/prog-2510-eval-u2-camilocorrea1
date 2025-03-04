# ¿Qué es un computador?

Un computador es una maquina electrónica que es programable con la capacidad de recibir, procesar y almacenar información. La información ya procesada puede ser interpretada por una persona o transmitida a otro sistema electronico.

![Computador](https://tomi-digital-resources.storage.googleapis.com/images/classes/resources/rsc-61379-5e8e6c1712a42.jpeg)

# Arquitecturas de un computador.

Es el diseño y estructura básica de un sistema informático. Se encarga de definir cómo funciona internamente la unidad central de procesamiento (UCP), cómo accede a la memoria y cómo se conectan los distintos componentes de hardware para cumplir con ciertos requerimientos de rendimiento y costo. En otras palabras, es el modelo que determina cómo están organizadas y funcionan las computadoras.

## Tipos de arquitectura.

### Arquitectura CISC.

La arquitectura CISC (Complex instruction set computing) minimiza la cantidad de instrucciones de un software y se ignora el número de ciclos por instrucción. CISC tiene un gran conjunto de instrucciones complejas con un tiempo de ejecución mas largo.

![CISC](https://1.bp.blogspot.com/-Sav1VtMPCtw/X-vDAuwZZKI/AAAAAAAAFbQ/OpNChcN_wcsg08kBpAnmKxuPNINx5nq2ACLcBGAsYHQ/s1520/CISC.png)

#### ¿Cómo está construida?

1. Unidad de Control (UC) basada en Microcódigo.

2. Decodificador de Instrucciones Complejo.

3. ALU (Unidad Aritmética y Lógica).

4. Buses y Memoria.

5. Registros y Cache.

##### Ejemplos de arquitectura CISC incluyen:

1. Intel x86 y x86-64 (utilizados en procesadores Intel y AMD).

2. VAX (utilizado en sistemas operativos OpenVMS y BSD).

3. MIPS R4000 (utilizado en estaciones de trabajo Silicon Graphics).

4. PA-RISC (utilizado en sistemas operativos HP-UX y OpenVMS).

5. PowerPC (utilizado en consolas de videojuegos como PlayStation 3 y Wii U).

### Arquitectura RISC.

La arquitectura RISC (Reduced Instruction Set Computing)  es un modelo de diseño de procesadores basado en un conjunto reducido de instrucciones. Su objetivo principal es mejorar el rendimiento simplificando las instrucciones y optimizando la ejecución en hardware.

![RISC](https://1.bp.blogspot.com/-dnZLaLUY0OY/X-vE8wZc_jI/AAAAAAAAFbg/slSn3NFCxBMxS2Tyz57NSJKiGNZgAQwHACLcBGAsYHQ/s1380/Risc.png)

#### ¿Como está construida?

1. Unidad de Control Simple.

2. Decodificador de instrucciones eficiente.

3. ALU optimizada para operaciones rápidas

4. Pipeline Profundo.

5. Más registros, menos accesos a memoria.

##### Ejemplos de arquitectura RISC incluyen:

6. ARM (utilizado en smartphones, tablets y dispositivos wearables).

7. MIPS (utilizado en routers y consolas de videojuegos como PlayStation y Nintendo 64).

8. PowerPC (utilizado en sistemas operativos como AIX y IBM i).

9. SPARC (utilizado en sistemas operativos Solaris y Illumos).

10. SuperH (utilizado en dispositivos electrónicos de consumo como reproductores de MP3 y cámaras digitales).

# ¿Qué es el hardware? 

El hardware es la parte física de una computadora o sistema informático. Incluye todos los componentes eléctricos, electrónicos, mecánicos y electromecánicos, como circuitos, cables, placas, memorias, discos duros y dispositivos periféricos. En general, abarca cualquier elemento físico esencial para el funcionamiento del equipo.

![Hardware](https://www.lifewire.com/thmb/-HqTo5VoM4OZ_vZswOECJl62ZwU=/3000x2000/filters:no_upscale():max_bytes(150000):strip_icc()/computer-hardware-2625895-final-v1-8c909b8a32434e26a225db2314823bb2.jpg)

## CPU. 

El CPU es el componente que permite la programación y, junto con la memoria y los dispositivos de entrada/salida, ha sido una parte fundamental en la evolución de las computadoras. Con el tiempo, los microprocesadores de un solo chip fueron sustituyendo a los CPU tradicionales, por lo que hoy en día el término suele usarse para referirse a los microprocesadores.  

Entre sus principales funciones están recopilar información, dividirla en partes más pequeñas, procesar las instrucciones y ejecutarlas.

### Partes importantes del CPU.

- ALU: La unidad aritmética lógica se encarga de realizar las operaciones matemáticas y lógicas que permiten a los  ordenadores tomar decisiones y procesar datos.

- Unidad de control: Es un circuito digital que extrae la instrucción de la memoria, la descifra y la ejecuta.

- Núcleo: Es la unidad base que constituye a un CPU, que interpreta y ejecuta acciones.

- Memoria caché: Es la memoria en la que se almacenan los datos que el usuario consulta con frecuencia, esto permite ganar velocidad al procesador.

- Registros: Es una memoria de alta velocidad que permite controlar y almacenar las instrucciones en ejecución.

- Controlador de memoria: Es un circuito que puede estar integrado al procesador y que regula el flujo de datos entre el procesador y la memoria.

- Bus: Es un sistema digital que envía y recibe datos entre los componentes.

## GPU.

GPU (Unidad de Procesamiento de Gráficos) es un tipo de procesador que maneja y acelera la representación de gráficos (la generación de las imágenes que verá en las pantallas de las computadoras). Esto es especialmente importante para tareas informáticas como renderizado o modelado 3D y juegos de cierta categoría.

El funcionamiento del GPU es procesar los píxeles y esto consiste en llevar toda la información gráfica al monitor o pantalla de tu equipo según las necesidades del ordenador.

### GPU vs CPU.

| Caracteristicas | GPU                 | CPU                                      |
|---------------  |---------------------|------------------------------------------|
| Núcleos         | Miles (pequeños y paralelos) | Miles (pequeños y paralelos)    | 
| Tareas          | Gráficos, IA, cómputo masivo | Procesos generales del sistema  | 
| Memoria         | VRAM (rápida y dedicada)     | RAM del sistema                 |
| Velocidad | Alto rendimiento en cálculos paralelos | Mejor en tareas secuenciales|

![CPU vs GPU](https://www.redswitches.com/wp-content/uploads/2023/05/CPU-vs-GPU-1.jpg)

## Memoria. 

La memoria en un hardware hace referencia a todos los componentes cuya función es resguardar la información para que el usuario pueda acceder a ella en cualquier momento.

1. Registros:

- Son pequeños espacios de almacenamiento dentro del procesador.
- Almacenan datos e instrucciones de manera temporal para su procesamiento inmediato.
- Son la memoria más rápida, pero también la más limitada en capacidad.

2. Caché:

- Es una memoria intermedia entre la RAM y el procesador.
- Su función es almacenar datos e instrucciones usadas frecuentemente para acelerar el acceso.

3. Principal (RAM):

- Es la memoria de acceso aleatorio donde se cargan los programas y datos en uso.
- Su contenido se borra cuando el equipo se apaga (memoria volátil).
- Es más lenta que la caché, pero tiene mayor capacidad.

4. Secundaria (Disco duro y unidades externas de almacenamiento):

- Se utiliza para el almacenamiento permanente de datos.
- Incluye discos duros (HDD y SSD), memorias USB y discos ópticos.
- Es más lenta que la RAM, pero tiene una capacidad mucho mayor.

## Dispositivos de entrada / salida.

Los dispositivos de entrada y salida, también conocidos como periféricos, son los componentes físicos conectados a una computadora que permiten la comunicación entre el usuario y el sistema o la gestión de datos.  
Se les llama periféricos porque funcionan de manera independiente al procesador central.  

Estos dispositivos se clasifican según su función en tres tipos:  
- Dispositivos de entrada: que envían información a la computadora.  
- Dispositivos de salida: que muestran o transmiten datos desde la computadora.  
- Dispositivos de entrada y salida: que pueden realizar ambas funciones.

## Buses de datos.

El bus de datos es un sistema de comunicación que conecta los diferentes dispositivos electrónicos de una computadora, permitiéndoles intercambiar información. Gracias a esta conexión, el procesador puede ejecutar operaciones, así como almacenar y recuperar datos.  

Este mecanismo es esencial para el flujo de información dentro del sistema, ya que facilita la transferencia de datos entre los componentes. Su desarrollo ha mejorado la velocidad y eficiencia de los equipos informáticos, optimizando el rendimiento en la ejecución de tareas.

### Funciones del bus de datos.

1. Transferencia de información.

- Permite el intercambio de datos entre el procesador, la memoria y otros dispositivos del sistema.

2. Arbitraje.

- El bus de datos es capaz de garantizar que cada dispositivo reciba exactamente la cantidad correcta de información sin sobrecargar otros dispositivos conectados al mismo.

3. Comunicación entre componentes.

- Facilita la conexión y el flujo de información entre distintos elementos de la computadora, como la RAM, la tarjeta gráfica y los dispositivos de almacenamiento.

4. Protección.

- El bus también proporciona protección contra errores humanos y fallas en hardware, permitiendo al sistema detectar fallas y recuperarse adecuadamente sin necesidad de reiniciarse manualmente en caso de fallas graves o incluso inexistentes.

# ¿Qué es el software?

El software es un conjunto de programas, datos e instrucciones que permiten ejecutar diversas funciones en un sistema informático. A diferencia del hardware, que es la parte física de un dispositivo, el software es intangible pero fundamental para su funcionamiento.
Este término se refiere a los programas y procedimientos que permiten a una computadora o dispositivo digital realizar tareas específicas, gestionando y procesando información de manera eficiente.

![Software](https://th.bing.com/th/id/R.cbe39532004a21c45b0d22312138ee5a?rik=1PptEM9wW59EFw&riu=http%3a%2f%2fcomofuncionaque.com%2fwp-content%2fuploads%2f2015%2f03%2fMuchos-de-los-programas-que-utilizamos-tienen-un-software-propio-que-les-ayuda-a-funcionar-correctamente.jpg&ehk=%2fluJ0w0KDCfGk1zom3Ss82vRCSbPykdxxOWfzTHMaok%3d&risl=&pid=ImgRaw&r=0)

## Tipos de software.

### Software de sistema.

Es el conjunto de programas y herramientas que permiten que el hardware y otras aplicaciones funcionen de manera eficiente. Incluye el sistema operativo, controladores de dispositivos, utilidades de optimización y servidores, entre otros componentes.

### Software de aplicacón.

El software de aplicación está diseñado para realizar tareas específicas que ayudan al usuario en su vida diaria o en su trabajo. Ejemplos incluyen procesadores de texto, hojas de cálculo, aplicaciones de diseño, videojuegos y programas de comunicación.
Los videojuegos, los programas de diseño asistido (como CAD), el software utilizado en las telecomunicaciones, las aplicaciones de productividad empresarial o educativa son algunos ejemplos de este tipo de programas.

### Software de desarrollo.

Es un conjunto de herramientas y programas diseñados para ayudar a los programadores en la creación, prueba y mantenimiento de aplicaciones y sistemas informáticos.

Algunos ejemplos son:

- Editores de código (como Visual Studio Code, Sublime Text).
- Compiladores e intérpretes (como GCC, Python).
- Entornos de desarrollo integrado (IDE) (como Eclipse, IntelliJ IDEA).
- Sistemas de control de versiones (como Git, GitHub).

# Funcionamiento del computador.

El funcionamiento de una computadora se basa en cuatro operaciones principales: entrada, procesamiento, almacenamiento y salida.  

1. Entrada: Se suministran datos e instrucciones a la computadora mediante dispositivos como teclado, mouse, escáner y micrófono. Estos datos son codificados para ser comprendidos por la CPU.  
2. Procesamiento: La CPU ejecuta operaciones aritméticas y lógicas para convertir los datos en información útil.  
3. Almacenamiento: Los datos pueden guardarse temporalmente en la memoria o de forma permanente en discos duros, CDs, DVDs y dispositivos externos.  
4. Salida: Los resultados del procesamiento se presentan a través de monitores, impresoras, parlantes u otras computadoras.  

Este proceso, llamado ciclo de procesamiento de la información, permite que las computadoras realicen múltiples tareas de manera eficiente.

## ¿Qué procesos se llevan a cabo cuando se enciende una computadora?

1. Inicio de la CPU.

- Se activan circuitos esenciales como el RTC (reloj en tiempo real) y el oscilador de reloj para sincronizar el sistema.
- La fuente de alimentación suministra energía y verifica su estabilidad mediante la señal Power Good.
- La CPU se inicializa, borrando datos residuales y cargando una dirección de inicio específica para ejecutar la rutina de arranque.

2. Reset Code.

- Se ejecuta un programa almacenado en una memoria no volátil, que activa componentes esenciales como el controlador de interrupciones.
- El contador de programa (PC) avanza secuencialmente, ejecutando cada instrucción en orden.

3. Startup Code.

- Se ejecuta el código de inicio, que realiza el autodiagnóstico POST (Power-On Self-Test).
- Se verifican componentes como la memoria RAM, la GPU, el teclado y otros periféricos.
- Si se detectan fallos, se muestran mensajes de error o se emiten pitidos de advertencia.

4. Bootstrap.

- Se carga el gestor de arranque (bootloader), como GRUB, LiLo o Windows Loader, para iniciar el sistema operativo.
- Si no se encuentra un medio de inicio válido, se muestra el mensaje "No boot device available".
- Este proceso garantiza que el sistema esté listo para ejecutar el sistema operativo y responder a las órdenes del usuario.

## ¿Qué sucede desde que ingreso un dato a través del teclado, hasta que veo el resultado de la operación en la pantalla?

1. Generación del código de escaneo.

- Cada tecla del teclado tiene un código de escaneo único.
- Al presionar una tecla, se envía un número binario a la computadora que representa su posición en el teclado.

2. Transmisión de datos a la CPU.

- Los datos viajan desde el teclado hasta la computadora a través de USB, Bluetooth u otro tipo de conexión.
- La CPU recibe y procesa estos datos para interpretar qué tecla fue presionada.

3. Interpretación por el sistema operativo.

- El kernel del sistema operativo detecta y gestiona cada pulsación de tecla.
- Convierte el código de escaneo en su equivalente en ASCII o Unicode, dependiendo del diseño de teclado configurado.

4. Envío de la pulsación a la aplicación activa.

- Se genera un evento que el sistema operativo dirige a la aplicación que estaba en uso en el momento de la pulsación (ejemplo: Word, Bloc de notas, terminal).

5. Visualización en pantalla.

- La aplicación convierte la pulsación en un carácter visible, respetando la fuente y el formato del texto.
- La CPU envía los datos a la GPU, que procesa la imagen y la muestra en el monitor.

## ¿Cómo se codifican los datos internamente en el computador?

La codificación de caracteres es el proceso de asignar valores numéricos a los caracteres para poder almacenarlos y transmitirlos en una computadora. Esto se hace para que los diferentes sistemas informáticos puedan leer y entender los archivos entre ellos. Algunas de las codificaciones más comunes son:

- ASCII: Estándar Americano para el Intercambio de Información. Utiliza 8 bits para representar cada carácter. Fue uno de los primeros estándares y aún se usa ampliamente hoy en día.
- Unicode: Utiliza 16 bits o más para representar cada carácter, lo que significa que puede representar un mayor número de caracteres, incluyendo caracteres latinos, griegos, cirílicos, hebreos y chinos.
- UTF-8: Un conjunto de codificaciones basadas en Unicode que utilizan 8 bits para representar cada carácter. Es la codificación más comúnmente usada hoy en día porque es compatible con la mayoría de los lenguajes informáticos y permite el intercambio sin problemas entre plataformas e idiomas.

## ¿Cuáles son las unidades de medida de datos en un computador? 

Las unidades de medida de datos en un computador son:

- Bit: Es la unidad mínima de información empleada en informática.
- Byte (B): Equivale a 8 bits.
- Kilobyte (kB): 1024 bytes forman un Kilobyte.
- Megabyte (MB): Equivale a 1024 Kilobytes.
- Gigabyte (GB): Es igual a 1024 Megabytes.
- Terabyte (TB): Lo componen 1024 Gigabytes.

# Mapa conceptual.

![Mapa](<Captura de pantalla 2025-02-05 183627.png>)

# Referencias. 

[Concepto de computadora](https://concepto.de/computadora/)
[Arquitectura de un computador](https://www.ecured.cu/Arquitectura_de_computadoras)
[Arquitectura CISC y RISC](https://mefics.org/es/qu%C3%A9-es-la-arquitectura-risc-y-cisc-con-sus-ventajas-y-desventajas/)
[Ejemplos arquitectura](https://definicionwiki.com/arquitectura-cisc-y-risc-definicion-que-es-diferencias-significado-usos/)
[Que es hardware](https://www.significados.com/hardware/)
[CPU Y sus partes](https://concepto.de/cpu/)
[GPU y función](https://culturacion.com/que-es-el-gpu-y-cual-es-su-funcion/)
[Memoria Ram](https://www.significados.com/memoria-ram/)
[Memoria secundaria](https://askanydifference.com/es/difference-between-primary-memory-and-secondary-memory/#:~:text=La%20memoria%20primaria%2C%20o%20RAM%2C%20es%20un%20almacenamiento,y%20la%20recuperaci%C3%B3n%20de%20datos%20a%20largo%20plazo.)
[Dispositivos entrada y salida](https://www.diferenciador.com/dispositivos-de-entrada-y-salida/)
[Buses de datos](https://muytecnologicos.com/diccionario-tecnologico/bus-de-datos)
[Sofware y tipos](https://www.significados.com/software/)
[Software de desarrollo](https://programacionpro.com/que-es-el-software-de-desarrollo-y-ejemplos/)
[Funcionamiento del computador](https://www.lifeder.com/funcionamiento-basico-computadora/)
[Proceso arranque](https://www.guiahardware.es/proceso-arranque/)
[Función teclado](https://www.guiahardware.es/como-funciona-teclado/)
[Codificación de datos](https://muytecnologicos.com/diccionario-tecnologico/codificacion-informatica)
[Unidades de medida en un computador](https://mejorsoftware.info/app33/53540/cuales-son-las-unidades-de-medida-de-la-computadora)








