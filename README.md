# Mecatronica-2024-2025
### Bitácora de Mecatrónica
-------------------------------------------------------------
## Índice de prácticas
<details>
<summary>Clases</summary>

- [L4: Tutorial Inkscape](#l4-tutorial-inkscape)
  * [Retos completados](#retos-completados)
- [L5: Técnicas avanzadas en Inkscape](#l5-técnicas-avanzadas-en-inkscape)
  * [Dibujo con precisión](#dibujo-con-precisión)
  * [Geometría constructiva](#geometría-constructiva)
  * [Calcado vectorial](#calcado-vectorial)
- [L6: Introducción al diseño 3D con FreeCAD](#l6-introducción-al-diseño-3d-con-freecad)
  * [Configuración y navegación básica en FreeCAD](#configuración-y-navegación-básica-en-freecad)
  * [Geometría Constructiva](#geometría-constructiva-1)
  * [Imprimir en 3D](#imprimir-en-3d)
- [L7: Operaciones de extrusión y bocetos en FreeCAD](#l7-operaciones-de-extrusión-y-bocetos-en-freecad)
  * [Operaciones fundamentales con croquis](#operaciones-fundamentales-con-croquis)
  * [Creación de croquis en FreeCAD](#creación-de-croquis-en-freecad)
  * [Diseñando con restricciones de boceto](#diseñando-con-restricciones-de-boceto)
  * [Part Design: Operaciones encadenadas](#part-design-operaciones-encadenadas)
 - [L8: Diseño 2D en FreeCAD](#l8-diseño-2d-en-freecad)
   * [Dibujos con líneas verticales y horizontales](#dibujos-con-líneas-verticales-y-horizontales)
   * [Dibujos con líneas en diferentes orientaciones](#dibujos-con-líneas-en-diferentes-orientaciones)
   * [Ejercicios](#ejercicios)
 - [L10: Garras mecánicas](#l10-garras-mecánicas)
   * [Método de inspiración](#método-de-inspiración)
   * [Diseño de la garra](#diseño-de-la-garra)
   * [Reto](#reto)
 - [L11: Estructuras mecánicas (II)](#l11-estructuras-mecánicas-ii)
   * [Pinzas simples](#pinzas-simples)
   * [Pinzas simétricas](#pinzas-simétricas)
   * [Tiempo de proyecto](#tiempo-de-proyecto)
 - [S3: Estructuras mecánicas (II)](#s3-estructuras-mecánicas-ii)
   * [Pinzas simples](#pinzas-simples)
   * [Pinzas simétricas](#pinzas-simétricas)
   * [reto loco](#reto-loco)


</details>

<details>
<summary>Proyecto Final</summary>
 
- [Primer día](#primer-día)
- [Avanzando en el proyecto final](#avanzando-en-el-proyecto-final)
  * [Componentes y Conceptos que He Considerado](#componentes-y-conceptos-que-he-considerado)
- [Empezando a programar la ESP32](#empezando-a-programar-la-esp32)
- [Probando motores](#probando-motores)
- [Conectando el mando PS4 a la ESP32](#conectando-el-mando-ps4-a-la-esp32)
  * [Pasos para realizar la configuración](#pasos-para-realizar-la-configuración)
  * [Funcionamiento final](#funcionamiento-final)

</details>

## Primer día
Hoy el señor don profesor nos ha comentado que tenemos que hacer un proyecto que vale el **80%** de la asignatura. Como nos dejó libertad creativa lo primero que se me ocurrió fue hacer algo que pueda ayudar a personas con problemas con discapacidades. Para ello lo primero que hice fue hablar con unos amigos que trabajan en centros sociales que ayudan a estas personas a tener una vida normal. Al ponerme en contacto con ellos les pregunté dudas del día a día para ver si se me ocurría algo. Mis ideas principales para el grupo fueron:

- Cuchara antitemblores
- Guantes traductores de lengua de signos
- Cordones de zapatos que se cierran con orden de voz

Tras debatirlo con mis compañeros no vimos mucha viabilidad para poder seguir adelante con esos temas asi que al final nos pusimos de acuerdo y decidimos intentar hacer el robot kantam de shin chan!!


<div align="center">
  <img src="https://github.com/user-attachments/assets/128acd29-ff4f-4f6f-bbd8-c0d0526493f2" alt="imagen">
</div>



## L4: Tutorial Inkscape
Hoy en clase hemos visto como utilizar cosas básicas de Inkscape y nos ha propuesto unos retos para sacar nuestro lado más creativo!


### Retos completados:
- **Reto 1**: 
<div align="center">
  <img src="https://github.com/user-attachments/assets/592dc438-32d7-4425-8b8e-dfb0d99c9c58" alt="imagen">
</div>

- **Reto 6**: 
<div align="center">
  <img src="https://github.com/user-attachments/assets/b4027637-2a07-4311-be16-e0aa1d9ba0a9" alt="imagen">
</div>

## L5: Técnicas avanzadas en Inkscape

Hoy le dimos caña a Inkscape con nuevas técnicas para hacer dibujos más precisos y jugar con geometría constructiva. También practicamos un poco el calcado vectorial.

### Dibujo con precisión
- **Ajustes (snap)**: Aprendí a conectar líneas de manera precisa, como de extremo a extremo, de punto medio a punto medio y de centro a centro. Todo mucho más limpio y exacto.
- **Dimensiones y guías**: Usamos guías y líneas auxiliares para alinear las formas con más precisión, lo cual fue súper útil.
- **Tangentes y perpendiculares**: Practicamos cómo crear líneas tangentes y perpendiculares, algo que no es tan obvio pero ayuda un montón para figuras complejas.

### Geometría constructiva
- **Operaciones booleanas**: Esto fue muy guay, combinamos formas con operaciones como la unión, intersección y diferencia. Hice cosas como:
  - Un tornillo plano (gracias a las líneas auxiliares).
  - Las piezas del Tetris (usando cuadrados y la técnica de unión).
  - Creé una luna menguante restando dos círculos y hasta un escudo combinando intersecciones.

### Calcado vectorial
- **Vectorización manual**: Aquí calqué un robot usando la herramienta de pluma. La idea era poner una imagen en el fondo y trazar los contornos encima. Fue más fácil de lo que pensaba y quedó bastante chulo.


## L6: Introducción al diseño 3D con FreeCAD

Hoy nos iniciamos en el mundo del diseño 3D utilizando FreeCAD, un programa libre y muy versátil. Aquí va un resumen rápido de lo que vimos:

### Configuración y navegación básica en FreeCAD
- **Configuración inicial**: Configuramos FreeCAD para usar el sistema de navegación de Blender y organizamos los paneles para mayor comodidad (Tree View, Task, Property).
- **Navegación 3D**: Aprendí a rotar, hacer zoom, y mover la cámara de manera eficiente. También exploramos cómo ajustar vistas (perspectiva, ortográfica) y seleccionar estilos de visualización.

### Geometría Constructiva
- **Objetos primitivos**: Creé cubos y cilindros como "Hola mundo" del 3D.
- **Operaciones booleanas**: Hicimos operaciones de diferencia para crear taladros en piezas planas y de unión para fusionar objetos. Esto es clave para modelar estructuras más complejas.
- **Referencias y clonación**: Usamos referencias para crear taladros vinculados, lo que facilita hacer cambios en masa a todos los objetos clonados.

### Imprimir en 3D
- **Exportar a STL**: Preparé una pieza para impresión exportando el diseño en formato STL.
- **Laminado e impresión**: Abrimos el STL en un laminador como Cura y obtuvimos el archivo .gcode para la impresora 3D.

### Retos completados:
- **Reto 6**:
![Screenshot from 2024-09-30 11-47-09](https://github.com/user-attachments/assets/64e178b4-2999-443b-81a0-f268a0d74d03)

Aquí puedes acceder a los [documentos](https://github.com/LiamSaboridoSueiro/Mecatronica-2024-2025/blob/main/Docs/L6%20FreeCad/anillodemoniaco.FCStd) relacionados con el diseño 3D de la sesión.

## L7: Operaciones de extrusión y bocetos en FreeCAD

En esta sesión nos metimos de lleno en las operaciones básicas de FreeCAD con bocetos 2D para crear piezas 3D. Lo más importante que vimos fue cómo manejar las restricciones de boceto para crear diseños de forma precisa.

### Operaciones fundamentales con croquis
- **Extrusión**: Aprendimos a estirar un boceto 2D para convertirlo en un sólido 3D.
- **Revolución**: Usamos la técnica de revolución para crear objetos girando un boceto alrededor de un eje (por ejemplo, un cono).
- **Vaciado**: Eliminamos material de un sólido utilizando un croquis y la operación de vaciado.

### Creación de croquis en FreeCAD
- **Importar SVG**: Dibujamos una figura en Inkscape, la importamos a FreeCAD y la extruimos para obtener un objeto sólido 3D.
- **Part y Draft**: También vimos cómo usar formas predefinidas y cómo dibujar figuras en 2D directamente en FreeCAD.
- **Sketcher**: Con Sketcher, aplicamos restricciones de boceto para ajustar líneas, distancias, y hacer los croquis mucho más precisos.

### Diseñando con restricciones de boceto
- **Ficha de casino**: Diseñamos una ficha de casino simple aplicando restricciones de diámetro y coincidencia en el croquis para que todo quede bien ajustado.
- **Base rectangular con taladro**: Creamos una base rectangular y un taladro en el centro usando restricciones de simetría e igualdad.

### Part Design: Operaciones encadenadas
- **Tope con tornillo y tuerca**: Utilizamos operaciones de extrusión y vaciado para crear un diseño más complejo, añadiendo tanto el cuerpo como los agujeros para tornillo y tuerca.

### Retos completados:
- **Reto 4**: Soporte para móvil.

![image](https://github.com/user-attachments/assets/0f79d485-05ed-4942-b8e0-f29bca863885)

Aquí puedes acceder a los [documentos](https://github.com/LiamSaboridoSueiro/Mecatronica-2024-2025/tree/main/Docs/L7Dise%C3%B1o3D) relacionados con los retos de esta sesión.

## Avanzando en el proyecto final!

 He estado desarrollando el robot Kantam, en principio se moverá con orugas y tendrá una funcionalidad especial: ¡puede disparar un puño desde su brazo usando un mecanismo de resorte! Mi idea es que sea radiocontrolado, por lo que estoy integrando componentes para poder controlar tanto el movimiento como el disparo de manera remota. He estado explorando varias opciones para hacer realidad tanto el disparo del puño como la movilidad del robot.

 ![image](https://github.com/user-attachments/assets/dd4f94d4-6f64-4d2e-936c-6c50c2618288)
 ![image](https://github.com/user-attachments/assets/5407e1c2-6388-4c02-b484-7f50adcf42cc)



### Componentes y Conceptos que he considerado

- **Microcontrolador (ESP32)**  
   La ESP32 es el cerebro de mi robot, ya que me permite la conexión inalámbrica (por Bluetooth o WiFi) y el control de los actuadores. Es perfecto para mi proyecto porque soporta comunicación remota y es compatible con varios tipos de motores y actuadores.

- **Sistema de Desplazamiento (Orugas de Tanque)**  
   - **Motores DC con reductora**: Estoy considerando motores N20 o TT Motors para mover las orugas del robot. Estos motores son compactos y proporcionan el balance ideal entre tamaño y torque, que es justo lo que necesito para que el robot se mueva tanto en terrenos planos como irregulares.
   - **Driver de Motor (L298N o similar)**: Necesito un driver para controlar los motores desde la ESP32, ya que la placa por sí sola no puede manejar la corriente que requieren los motores.

- **Mecanismo de Disparo del Puño**  
   - **Resorte o muelle**: Estoy usando un resorte helicoidal comprimido dentro del brazo para almacenar la energía que dispara el puño.
   - **Mecanismo de retención**: Incluye un gancho o pestillo que mantiene el puño en posición hasta que active el disparo.

- **Actuadores para Activar el Gatillo del Muelle**  
   - **Micro Servo (SG90 o MG90S)**: Inicialmente, pensé en un micro servo tanto para mover el brazo como para activar el mecanismo de retención del puño usando una leva o engranaje.
   - **Alternativas al Servo**:
     - **Solenoide Lineal**: También consideré un solenoide lineal, que proporciona un movimiento rápido y directo para liberar el gatillo y disparar el puño, aunque requiere bastante corriente y espacio en el brazo.
     - **Sistema de Tensión (Cable Bowden)**: Si el espacio en el brazo resulta muy limitado, podría usar un cable Bowden para transmitir el movimiento desde un actuador colocado en otra parte del robot.

- **Alimentación**  
   - **18650 Battery Shield**: Pensé en usar una batería 18650 con un shield, que proporciona una salida de 5V a través de un puerto USB. Esto es ideal para alimentar la ESP32 y simplificar el sistema de alimentación.
   - **Capacidad de la batería**: Un power bank de entre 2000mAh y 5000mAh o una batería 18650 debería ser suficiente para mantener funcionando el microcontrolador, los motores y el sistema de disparo.

  De momento estas son mis investigaciones respecto a los componentes que estoy pensando en usar. Ahora solo falta pedirlos y empezar a hacer pruebas!

## L8: Diseño 2D en FreeCAD

<div align="center">
  <img src="https://github.com/user-attachments/assets/ca852e12-8c00-4b89-a6ab-febe7dc8cab8" alt="imagen">
</div>


Hoy estuvimos practicando el diseño en 2D en FreeCAD. Empezamos con dibujos básicos usando solo líneas verticales y horizontales, y luego pasamos a crear figuras más complejas con diferentes orientaciones y ángulos.

### Dibujos con líneas verticales y horizontales
Primero, nos centramos en piezas sencillas como rectángulos y formas en T. Usamos la herramienta de multi-línea para dibujar contornos y aplicamos restricciones automáticas de horizontalidad y verticalidad. Luego creamos vistas en TechDraw para agregar cotas y exportar planos en SVG.

### Dibujos con líneas en diferentes orientaciones
Después, trabajamos en figuras como un triángulo rectángulo, donde aprendimos a usar restricciones angulares para manejar ángulos. Esto nos permitió añadir cotas angulares y trabajar con formas en diferentes orientaciones.

### Ejercicios
Para cerrar, hicimos varios ejercicios para reforzar estas técnicas y practicar el acotado de piezas en 2D. La idea es mejorar nuestra precisión en el diseño y poder exportar planos listos para impresión o documentación. Una pena que en esta sesión no hubiera retos...

## Empezando a programar la ESP32

<div align="center">
  <img src="https://github.com/user-attachments/assets/0aabe8d8-da95-4fd8-855f-fa8d68665c81" alt="imagen">
</div>


Hoy me puse manos a la obra con la configuración para programar la **ESP32**. La idea era dejar todo listo para poder cargar y probar el clásico “Hola Mundo” en el microcontrolador. Para ello, instalé **PlatformIO** como extensión en Visual Studio Code, que facilita bastante el trabajo con este tipo de placas.

Para no perderme en el proceso, seguí [este video de YouTube](https://youtu.be/tc3Qnf79Ny8?si=LDuCUOu9fi1D89gF), donde explican cómo preparar todo el entorno. Después de tener todo configurado, pude cargar el "Hola Mundo" en la ESP32 y verificar que el código se ejecutaba bien. Con esto ya tengo el entorno listo para empezar a programar la ESP32 en serio...

## L10: Garras mecánicas

Hoy empezamos con algo nuevo: el diseño de garras mecánicas. Vimos cómo funcionan las garras sencillas y cuáles son los pasos para diseñar una propia. Utilizamos el “método de inspiración”, que se basa en observar mecanismos de la naturaleza para luego simplificarlos y crear algo similar.

### Método de inspiración
Primero, buscamos inspiración en la naturaleza, que tiene un montón de ejemplos útiles para diseñar garras. Después, elegimos un mecanismo simple (en este caso, nuestra propia mano) y analizamos sus partes clave para poder replicarlas. La idea es quedarnos solo con lo esencial y luego usar esa base para crear una versión simplificada y funcional.

### Diseño de la garra
Empezamos a diseñar nuestra propia garra inspirándonos en la función de pinza de la mano. Nos centramos en los dos dedos básicos de una pinza: el índice como móvil y el pulgar como fijo. Luego, calcamos el movimiento de la mano con Inkscape, sacando puntos importantes como articulaciones y extremos para entender mejor el mecanismo.

### Reto
Al final de la sesión, nos propusieron un reto: diseñar nuestra propia pinza siguiendo el método de inspiración. No tuve tiempo de hacerlo en casa, ya que estuve aprovechando para avanzar con el proyecto final, ¡pero espero retomarlo pronto!


## Probando motores

<div align="center">
  <img src="https://github.com/user-attachments/assets/f3933020-4019-432e-96c0-70f7fc56b592" alt="imagen">
</div>

Hoy avancé con el proyecto final y estuve aprendiendo a controlar tanto un servo como un motor DC usando la ESP32. Para el motor DC, utilicé un driver **L293D**, que me permite cambiar la dirección del motor fácilmente. Conecté el motor amarillo al L293D y configuré la ESP32 para controlar su giro en ambas direcciones. Esto me dio bastante flexibilidad para ajustar el movimiento según se necesite.

También logré controlar un servo, experimentando con diferentes ángulos para ver cómo respondería. Esta práctica con el servo y el motor DC me va a ayudar a tener el control necesario para el movimiento y las funciones del robot. Ahora tengo el driver y los motores funcionando bien con la ESP32, lo cual es un gran paso para el proyecto.

## L11: Estructuras mecánicas (II)

Hoy estuvimos viendo el diseño y funcionamiento de **pinzas mecánicas** simples. Lo que hicimos fue observar cómo funcionan nuestras propias manos, y luego pasarlo a un diseño usando **Sketcher en FreeCAD** para entender mejor cómo funcionan las pinzas mecánicas.

### Pinzas simples

Empezamos con una **pinza simple**, observando el movimiento de los dedos y sacando un diseño en 2D con **Inkscape**. Luego lo importamos a FreeCAD para darle volumen y convertirlo en un diseño 3D. Las articulaciones las hicimos con un **tornillo M3x12** y una tuerca autoblocante.

### Pinzas simétricas

Después vimos las **pinzas simétricas**, donde los dos dedos se mueven al mismo tiempo. Para eso, usamos engranajes que permiten un movimiento coordinado. Implementamos un diseño básico con engranajes para ver cómo funciona este tipo de pinza.

### Tiempo de proyecto

No me dio tiempo a hacer los retos de hoy porque estuve a tope con el **proyecto final**, avanzando en el control del mando PS4 y probando los motores. Pero voy viendo buenos progresos con todo eso.

## Conectando el mando PS4 a la ESP32

Estuvimos pensando en cómo controlar el robot, y después de barajar varias opciones (como una app móvil por Bluetooth o WiFi), decidimos que lo más intuitivo y práctico era hacerlo con un mando de PS4. Esto también le da un toque de "robot de juguete", que nos gustó bastante. Al buscar código por internet, encontramos que usar un mando con la ESP32 mediante la librería **BluePad32** era mucho más sencillo y versátil.

### Pasos para realizar la configuración

1. **Instalación de librerías y configuración**:  
   Lo primero fue instalar los gestores de placas para **ESP32** y **BluePad32** en el **Arduino IDE**. Agregamos las URLs necesarias en las preferencias del IDE para tener acceso a las librerías. Luego instalamos las placas correspondientes: **ESP32 by Expressive Systems** y **BluePad32**.

2. **Elegir la placa**:  
   Seleccionamos la placa correcta, en nuestro caso la **DOIT ESP32 Devkit V1**, que es bastante común si compras en Amazon o sitios similares.

3. **Subir el código de ejemplo**:  
   Utilizamos un sketch de ejemplo de **BluePad32** que venía bastante completo. El código tiene tres secciones clave:
   - **dump gamepad**: Muestra en el monitor serie los botones del mando y sus valores.
   - **process gamepad**: Aquí es donde añadimos el código para activar los motores y LEDs.
   - **setup**: Definimos los pines del ESP32 y conectamos los servos y LEDs.

4. **Probar y mapear los botones**:  
   Una vez que conectamos el mando al ESP32 y abrimos el monitor serie, fuimos mapeando los botones. Esto nos permitió asignar cada botón o joystick a una función del robot, como mover un motor o encender un LED.

5. **Control de componentes**:  
   Asignamos cada botón y joystick a una acción específica. Por ejemplo, uno de los botones enciende el LED y los joysticks controlan los motores. Tras varias pruebas, logramos que el mando y la ESP32 trabajaran juntos sin problemas.

Nos costó un poco controlar los dos motores a la vez porque el cableado era un lío y tuvimos que rehacerlo como 5 veces. Pero al final, con el controlador **L293D** (que es el más pequeño que tenemos), conseguimos que ambos motores funcionaran al mismo tiempo. Estuvimos varios días entre configuraciones del mando y los motores, pero finalmente lo hicimos funcionar.

### Aquí dejamos cómo quedó funcionando:

https://github.com/user-attachments/assets/ec388d40-a87c-4168-a044-f4b63a985d88


## S3: Estructuras mecánicas (II)

### Pinzas simples
En esta sección nos enfocamos en el diseño y funcionamiento de una pinza mecánica básica. Primero analizamos los elementos clave de la mecánica de agarre, inspirándonos en el funcionamiento de nuestra mano. Luego, diseñamos las piezas en 2D para crear la estructura de la pinza y la importamos a FreeCAD, donde le damos volumen y forma en 3D. Aquí también abordamos cómo identificar y colocar el eje de articulación para que el movimiento sea fluido y efectivo.

### Pinzas simétricas
Las pinzas simétricas permiten que ambos "dedos" de la pinza se muevan al mismo tiempo y en direcciones opuestas, lo que ayuda a mejorar la precisión del agarre. Vimos cómo implementarlas con un modelo alámbrico y en FreeCAD, utilizando engranajes para crear una transmisión de movimiento simétrica. También exploramos ejemplos prácticos como la pinza del PrintBot Beetle y la Ultimate Gripper, que aplican esta simetría en diseños de robots.

### Reto loco
El reto de esta sesión es diseñar nuestra propia pinza, inspirándonos en las estructuras vistas o implementando un mecanismo de paralelogramo para un agarre más preciso. Aquí muestro mi intento de mano!

<div align="center">
  <img src="https://github.com/user-attachments/assets/f7f6e90b-4352-4d7c-99f4-72690a710411" alt="imagen">
</div>

Puedes acceder al [documento del reto aquí](https://github.com/LiamSaboridoSueiro/Mecatronica-2024-2025/tree/main/Docs/S3%20Estructuras%20mecanicas).

