[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ZHlrD2sU)
# **Hardware y Software**
## Investigacion Hardware

### CPU
La CPU es el componente principal que procesa las señales y hace posible la computación, actúa como el cerebro de cualquier dispositivo de computación, obtiene instrucciones de la memoria, realiza las tareas necesarias y envía la salida a la memoria y maneja todo tipo de tareas de computación necesarias para que el sistema operativo y las aplicaciones se ejecuten.
Una CPU es un circuito electrónico complejo compuesto por varios componentes clave que procesan datos y ejecutan instrucciones. Estos incluyen la unidad de control, que gestiona el procesamiento de instrucciones y coordina el flujo de datos; los registros, que son pequeñas ubicaciones de almacenamiento de alta velocidad que facilitan el acceso rápido a los datos; la unidad aritmética lógica (ALU), que realiza operaciones aritméticas y lógicas; y la unidad de gestión de memoria, que maneja la interacción entre la CPU y la memoria RAM, así como la memoria caché y virtual. Además, la CPU se sincroniza mediante una señal de reloj que coordina sus operaciones internas y determina la cantidad de instrucciones que puede ejecutar por segundo.
Una CPU funciona procesando datos y gestionando el flujo de información a través de ciclos de instrucción, que comprenden tres pasos principales:
Búsqueda de instrucciones: La CPU obtiene instrucciones codificadas en binario desde la memoria, las interpreta a través de la unidad de control y determina las operaciones necesarias y los componentes de la CPU involucrados.
Procesamiento de instrucciones: La CPU realiza la operación especificada, que puede incluir cálculos matemáticos, comparaciones lógicas, manipulación de datos o transferencia de datos entre registros o memoria.
Almacenamiento de resultados: La CPU almacena los resultados en la memoria o actualiza los registros, y actualiza el contador de programas para señalar la siguiente instrucción.
Además, la CPU gestiona instrucciones de flujo de control, interrupciones y utiliza técnicas como el paralelismo y la canalización para mejorar el rendimiento, permitiendo que múltiples instrucciones se procesen simultáneamente en diferentes etapas del ciclo.

### RAM
La memoria RAM (Random Access Memory) es la memoria principal de un dispositivo, utilizada para almacenar temporalmente los datos de los programas en uso. Se encuentra en diversos dispositivos, desde ordenadores hasta teléfonos móviles. La RAM destaca por su alta velocidad y por almacenar datos de forma temporal, lo que significa que toda la información almacenada se pierde al reiniciar o apagar el dispositivo. Esto permite que los programas y aplicaciones se ejecuten rápidamente, proporcionando un acceso rápido a los datos necesarios para el funcionamiento eficiente del sistema.

### Almacenamiento HDD y SSD
Las SSD (unidades de estado sólido) y las HDD (unidades de disco duro) son dispositivos de almacenamiento, pero difieren en su tecnología y funcionamiento:
SSD: Utilizan memoria flash sin partes móviles, lo que las hace más rápidas, duraderas y eficientes. Almacenan datos en bloques de memoria y permiten un acceso rápido.
HDD: Utilizan platos magnéticos giratorios con partes mecánicas móviles. Son más lentas y susceptibles a daños físicos, pero ofrecen mayor capacidad de almacenamiento a menor costo.

### Placa base (Motherboard)
La placa madre, también conocida como placa base o motherboard, es la tarjeta de circuito principal de un sistema informático. Integra y conecta todos los componentes esenciales del computador, como el microprocesador, la memoria RAM, las ranuras de expansión y el chipset. También alberga el firmware del BIOS, que regula y prueba las funciones básicas del hardware y soporta la carga del sistema operativo. La placa madre se fabrica en formatos estándar para caber dentro de las carcasas del CPU, aunque algunas empresas utilizan formatos propietarios. Existen placas para procesadores AMD e Intel, así como placas multiprocesador para mayor potencia de procesamiento. Es el componente central donde se distribuyen y gestionan los datos y las instrucciones del sistema.

### Dispositivos de entrada y salida
Los dispositivos de entrada y salida (I/O) son aparatos electrónicos que permiten tanto introducir como extraer información de un sistema informático. Se les llama periféricos bidireccionales o mixtos porque pueden desempeñar ambas funciones, ya sea simultáneamente o por turnos.
Entrada (Input): Cuando funcionan como dispositivos de entrada, introducen nueva información en el sistema, aumentando el contenido de la base de datos. Por ejemplo, una impresora multifunción que escanea un documento y lo guarda en la computadora como una imagen.
Salida (Output): Cuando funcionan como dispositivos de salida, extraen información del sistema para que pueda ser interpretada por el usuario, ya sea en forma de imagen, texto, o audio. Por ejemplo, una impresora multifunción que imprime un documento desde la computadora.

### Buses (Datos y direccion)
Los buses de comunicación son sistemas que permiten la transferencia de datos entre diferentes componentes de un sistema informático o industrial. Se pueden clasificar según la forma en que transfieren la información y según su uso específico. Aquí se describen los principales tipos:

Según la transferencia de datos:

En paralelo: Transfieren datos simultáneamente por múltiples líneas.
En serie: Transfieren datos secuencialmente, bit a bit, por una sola línea.

En entornos industriales:

Profibus: Para comunicación en tiempo real.
Modbus: Para automatización de procesos industriales.
Bus CAN: Usado en gestión hospitalaria y automotriz.
AS-interface: Para dispositivos simples.
Interbus: Para transmisiones de datos a altas velocidades.

Según su uso específico:

Bus de datos: Transfiere datos entre componentes del sistema.
Bus de direcciones: Transmite la dirección de memoria de los datos.
Bus de control: Coordina y sincroniza las operaciones del sistema, evitando conflictos.
Bus multiplexado: Permite la transmisión de múltiples señales en una sola línea mediante técnicas de multiplexación.

## Investigacion Software

### Sistema Operativo
El sistema operativo es el software fundamental que coordina y dirige todos los servicios y aplicaciones en una computadora. Actúa como el núcleo del sistema, regulando funciones básicas como comunicaciones, procesamiento e interfaz con el usuario. Los sistemas operativos más conocidos incluyen Windows, Linux, OS/2 y DOS.

Se ejecuta con privilegios especiales para mantener el sistema seguro y estable, evitando que programas no autorizados realicen cambios críticos. Ofrece interfaces gráficas o líneas de comandos para que el usuario interactúe con el sistema. Los sistemas operativos han evolucionado desde los años 60, con hitos importantes como el lanzamiento de Windows 95 en los años 90.

### Aplicaciones de usuario
La aplicación Usuarios es donde crea y gestiona los registros de usuarios. Los registros de usuarios contienen nombres de usuarios, contraseñas y perfiles de seguridad que determinan las aplicaciones, opciones y datos a los que puede acceder un usuario.

Cuando crea un registro de usuario, debe crear también un registro de persona. Un registro de usuario puede asociarse con un solo registro de persona. Un registro de persona puede asociarse con un solo registro de usuario. Puede asociar un registro de mano de obra y un registro de usuario con el mismo registro de persona.

De forma predeterminada, cuando se utiliza un servidor de aplicaciones para la autenticación, el directorio gestiona la creación de usuarios. Puede establecer propiedades para permitir que la creación de usuarios se lleve a cabo directamente en el sistema. Los valores de estas propiedades resultan en que determinadas funciones se habiliten o inhabiliten en el sistema.

### Drivers
Drivers (o controladores) son programas que permiten al sistema operativo y al software comunicarse con el hardware. Actúan como intermediarios, traduciendo las instrucciones del sistema operativo en comandos que el hardware puede entender. Ejemplos incluyen drivers para impresoras, tarjetas gráficas y adaptadores de red. Son esenciales para el funcionamiento correcto de los dispositivos y suelen requerir actualizaciones para mantener la compatibilidad y el rendimiento.

### Software de desarrollo
Software de desarrollo es un conjunto de herramientas utilizadas para crear, editar y mantener software y aplicaciones. Incluye:

Entornos de Desarrollo Integrados (IDEs): Como Visual Studio o Eclipse, que proporcionan un conjunto completo de herramientas para escribir, depurar y probar código.
Editores de Código: Como Sublime Text o Atom, que permiten escribir y editar código fuente.
Compiladores e Intérpretes: Programas que convierten el código fuente en código ejecutable o interpretan el código en tiempo real.
Sistemas de Control de Versiones: Como Git, que gestionan y registran los cambios en el código fuente a lo largo del tiempo.
Herramientas de Construcción y Automatización: Como Maven o Gradle, que automatizan el proceso de compilación y despliegue.