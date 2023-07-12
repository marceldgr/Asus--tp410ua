# Asus TP-410UA- OpenCore 0.9.3  

 Breve descripción del proyecto. Con este modelo Asus se obtine la mayor parte de todo la funcionalidad del equipo es compatible con monterey
 pero no es muy estable con la siguinetes versiones de mac os. 

## Tabla de contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Instalación](#instalación)
- [QUE FUNCIONA](#Quefunciona)
- [QUE NO FUNCIONA](#Quenofunciona)

## Descripción
-   Con la guia de dortania para le modelo de procesodor se logro contruir la Config.plis para la funcionalidad total del equipo
-   se realizaron Cambios y actulizacion de partes fisica como disco duro HDD a M2 sata y memoria Ram a 8gb ya que las 4gb de fabrica son soldadas
-   El Asus TP410UA es un portátil 2 en 1 diseñado por Asus, una reconocida empresa de tecnología. El dispositivo combina la funcionalidad de una computadora portátil y una tableta, lo que permite a los usuarios utilizarlo en diferentes modos, como una computadora portátil tradicional o plegándolo como una tableta.

Testing on:

Model | ASUS TP410U
------------- | ---------------
CPU | Intel Core i3-7200u
iGPU | Intel HD Graphics 620
RAM | 4 GB DDR4 + 8GB DDR4 
WiFi |intel corporation wirelees 8265 + BT 
Sonic | realtek ALC294
macOS | Ventura 12.+
EFI | 0.9.3 


El TP410UA cuenta con una pantalla táctil de 14 pulgadas con resolución Full HD, lo que proporciona una experiencia visual nítida y vibrante. La pantalla es compatible con lápices ópticos, lo que permite una mayor precisión al interactuar con la pantalla táctil.

En cuanto al rendimiento, el TP410UA está equipado con un procesador Intel Core de séptima generación, que ofrece un rendimiento sólido para tareas diarias y multitarea. Además, viene con 8 GB de memoria RAM, lo que permite ejecutar aplicaciones y programas sin problemas.

En términos de almacenamiento, el TP410UA cuenta con una unidad de estado sólido (SSD) de 256 GB, que ofrece velocidades de lectura y escritura más rápidas en comparación con los discos duros tradicionales. Esto permite un acceso rápido a los archivos y una mayor capacidad de respuesta del sistema.

El dispositivo también incluye varias opciones de conectividad, como puertos USB, HDMI y lector de tarjetas SD, lo que facilita la conexión de periféricos y dispositivos externos. También cuenta con conectividad inalámbrica Wi-Fi y Bluetooth para una mayor flexibilidad de conexión.

En cuanto al diseño, el TP410UA presenta un acabado elegante y moderno, con bordes delgados y un perfil delgado. Esto lo hace portátil y fácil de transportar.  

## Características

- Pantalla: Pantalla táctil de 14 pulgadas con resolución Full HD (1920 x 1080 píxeles). Soporta entrada con lápiz óptico.
-  Procesador: Procesador Intel Core de séptima generación. El modelo específico puede variar según la configuración.
-  Memoria RAM: 4 / 8 GB de memoria RAM, lo que permite un rendimiento fluido en tareas diarias y multitarea. expandible
-  Almacenamiento: Unidad de estado sólido (SSD) de 256 GB. Proporciona velocidades de lectura y escritura más rápidas en comparación con los discos duros tradicionales.
-  Sistema operativo: Viene con Windows 10 preinstalado. compatible con Mac Os x desde mojave en adelante
-  Conectividad: Puertos USB, incluyendo USB Type-C, puertos HDMI y lector de tarjetas SD. También cuenta con
-  conectividad inalámbrica Wi-Fi y Bluetooth. funcional en hackintosh
-  Diseño y portabilidad: Acabado elegante y moderno con bordes delgados. Perfil delgado que facilita su transporte y portabilidad.
-  Batería: Batería de larga duración que permite un uso prolongado sin necesidad de estar constantemente conectado a una fuente de alimentación.
-  Altavoces: Altavoces integrados que ofrecen un sonido de calidad para disfrutar de contenido multimedia.
-  Funcionalidad 2 en 1: Diseño convertible que permite utilizar el dispositivo en diferentes modos, como portátil o tableta, adaptándose a las necesidades del usuario.

## Instalación

seguir la guia de dortania link: https://dortania.github.io/OpenCore-Install-Guide/

## Que funciona?
-  Audio.
-  Microfono.
-  Salida de audio jack 3.5.
-  Pantalla tactil.
-  Salida HDMI.
-  Graficos 2048 mb 
-  Puertos usb tipa y tipo C.
-  Dormir.
-  Apagado.
-  Teclado.
-  Bluetooth.
-  Wifi.
-  Gestor de eneriga

  ## Que no funciona ?  
  - Lector de tarjeta de SD(en ocaciones si funcina pero genera error panic).
  - Control de Volumen fisico.
  - Control de giro al poner la pantalla en 360°.
  - Lapiz optico.
