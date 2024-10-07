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

</details>

<details>
<summary>Proyecto Final</summary>
- [Primer día](#primer-día)
- [Avanzando en el proyecto final](#avanzando-en-el-proyecto-final)
  * [Componentes y Conceptos que He Considerado](#componentes-y-conceptos-que-he-considerado)

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

### Componentes y Conceptos que He Considerado

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





