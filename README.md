# U1-APUNTES-DE-CLASE
 <div align="justify"> 
<h1>Unidad I. Introducción a la graficación por computadora. </h1>

La graficación por computadora es el estudio y aplicación de algoritmos, técnicas y software para crear, almacenar, manipular y visualizar imágenes y objetos gráficos en un ordenador. Abarca desde gráficos 2D hasta modelado 3D, animación y renderizado en tiempo real, utilizando técnicas como gráficos raster (píxeles) y vectoriales. Sus usos son esenciales en diseño (CAD), entretenimiento, medicina, simulaciones científicas y visualización de datos.<br>
<img width="799" height="420" alt="image" src="https://github.com/user-attachments/assets/2e02bf32-86bb-42f0-a860-5cb196579926" /> <br>
La graficación interactiva es la técnica de utilizar comunicación bidireccional entre la computadora y el usuario en la que la computadora se comunica con imágenes gráficas. La computadora, al recibir señales del usuario, modifica la imagen. Y el usuario, viendo la imagen, puede tomar acciones para modificarla.<br>

Ejemplos de graficación interactiva:<br>
•	Programa de diseño de circuitos<br>
•	Un juego de video<br>

Ejemplos de graficación pasiva o no interactiva:<br>
•	Un programa que solamente grafica la función seno(x) es un ejemplo de graficación no interactiva, o pasiva.<br>

Criterios que han impulsado y dirigido el desarrollo de la tecnología de despliegue:<br>
•	Rapidez de Despliegue: El tiempo que se requiere para dibujar. También se toma en cuenta la carga en el CPU para controlar el despliegue.<br>
•	Modificación Selectiva: la facilidad con que se puede modificar una parte de la imagen sin afectar el resto.<br>
•	Realismo y Calidad de la Imagen: Alta Resolución.<br>
•	Relleno: la calidad en la representación de objetos sólidos.<br>
•	Color: el rango de colores, tonos e intensidades que se pueden desplegar.<br>
•	Estabilidad: La imagen no es intermitente ni mareada; y al ser borrada, no deja "fantasmas" en la pantalla.<br>
•	La resolución se define como el número de puntos distinguibles por pulgada que se pueden desplegar, pero comúnmente es usada para significar el número total de puntos direccionables en una pantalla. La resolución está muy relacionada con la precisión de la representación de una imagen.<br>
•	Precio: mientras más barato sea, más útil y utilizado será.<br>

<h2>1.1. Historia y evolución de la graficación por computadora.</h2>
La graficación por computadora evolucionó desde visualizaciones básicas en osciloscopios en los años 50 hasta el fotorrealismo 3D actual, impulsada por hitos como Sketchpad (1963) de Ivan Sutherland, el desarrollo de CAD, el ratón, las tarjetas gráficas (GPU) y el cine (Pixar). Esta tecnología transformó la interacción humano-máquina, la visualización científica, los videojuegos y la animación, pasando de trazos simples a entornos virtuales complejos. <br>
Hitos Clave en la Evolución: <br>
•	Años 50 - Los Inicios: Uso de osciloscopios para mostrar datos y el sistema Whirlwind (1951) del MIT, considerado el primer sistema gráfico 3D.<br>
•	Años 60 - Fundamentos Interactivos: Ivan Sutherland crea Sketchpad (1963), introduciendo el lápiz óptico y estructuras de datos. Aparece el primer ratón y se desarrollan técnicas de algoritmos de línea. <br>
•	Años 70 - Gráficos y Consolas: Nolan Bushnell funda Atari y populariza los videojuegos (Pong). Aparecen los primeros modelos de curvas y superficies, además de los primeros fractales. <br>
•	Años 80 - La Era PC y 3D: Lanzamiento de AutoCAD (1982) y auge del modelado 3D. Pixar comienza a producir cortometrajes y Apple populariza las interfaces gráficas. <br>
•	Años 90 - Aceleración y Fotorrealismo: Lanzamiento de las tarjetas gráficas de consumo, el estándar OpenGL (1992) y el estreno de Toy Story (1995), el primer largometraje 3D. <br>
•	Siglo XXI - Alta Definición y Tiempo Real: Las GPUs (NVIDIA GeForce 256 en 1999) permiten renderizado en tiempo real, motores gráficos avanzados (Doom 3, 2003), realidad virtual y aumento de realismo en simulaciones e inteligencia artificial. <br>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3dac547c-4411-4d2f-8d4f-0bb359df063e" />


<h2>1.2. Áreas de aplicación.</h2>
La graficación por computadora (GC) es un campo multidisciplinario bastante amplio, donde tanto computólogos, matemáticos, físicos, ingenieros, artistas y otros practicantes comparten un mismo objetivo "mostrar un mundo a través de una ventana", nos podemos referir como mundo a un modelo digital, una simulación, o bien, cualquier representación visual que se busque mostrar, y como ventana a cualquier medio para mostrar imágenes, como un proyector, la pantalla de un monitor, tablet, entre otros. Por lo que nos podemos dar una idea de las multiples aplicaciones que se pueden obtener en este campo sobre los diferentes ámbitos, veamos algunas de estas aplicaciones: <br>
•	Industria del entretenimiento: Creación de películas o caricaturas sintéticas, publicidad, efectos visuales y videojuegos. <br>
•	Ingeniería Mecánica: Diseño de prototipos virtuales de partes mecánicas para su construcción, utilizando sistemas CAD/CAM (Computer-Aided Design/ Computer-Aided Manufacturing). <br>
•	Arquitectura: Uso del software CAD para la creación de planos de alguna estructura arquitectónica, visualizaciones de espacios antes y después de una construcción planeada. <br>
•	Diseño: Diseño y creación de productos, haciendo uso de sistemas CAD/CAM, promoviendo la creatividad del diseñador al permitirle experimentar con varias formas antes de producir la idea final. <br>
•	Patrimonio cultural: Reconstrucciones virtuales de templos, monumentos, piezas antiguas, o bien, reconstrucciones hipotéticas de escenas. <br>
•	Medicina: Simulaciones virtuales de cirugías para entrenamiento y visualización de datos dados por algún instrumento de diagnóstico. <br>
<br>
Asimismo, se han ido desarrollando un gran número de áreas de especialización, las cuales han ido evolucionando de acuerdo a las necesidades de los usuarios y al avance tecnológico en el hardware y software. Las principales suelen ser las siguientes: <br>
•	Renderización: Es el proceso para generar una imagen final dada una entrada ordenada de datos, se suele clasificar dependiendo del algoritmo que se use, generalmente se toma como referencia el tiempo que a éste le tome en producir una imagen sintética (Real time rendering, Offline rendering), o bien, el tipo de técnica de renderizado que utilice (Photorealistic rendering, non-photorealistic rendering o information visualization). <br>
•	Modelado: Es la especificación matemática del mundo a representar, es decir, se describen los objetos y sus propiedades de un modo que éstos puedan ser almacenados en la computadora, por ejemplo, una manzana puede ser descrita como un conjunto de puntos 3D, los cuales forman caras ordenadas, con un modelo de iluminación especifico para describir cómo interactúa la luz con la manzana. <br>
•	Animación: Es la creación de una secuencia de imágenes con una computadora, que tiene como finalidad producir la ilusión de movimiento. Si bien, hace uso de las dos áreas anteriores, no se encarga del estudio de éstas, pues su objetivo es añadir alguna animación sobre un rango de tiempo específico a los modelos, con la cual modifica algún aspecto de éstos, como su color, posición, apariencia, entre otros. <br>
<br>
Y entre algunas otras áreas de relevancia se encuentran: <br>
•	Simulación: Es el proceso en el que un modelo matemático es ejecutado y representado con una computadora, la cual es usada para simular un comportamiento y su repercusión en el mundo real, o bien, dentro de un sistema físico impuesto, permitiendo revisar la fiabilidad del modelo, por lo cual es útil para modelar sistemas en física, astrofísica, climatología, química, biología, economía, ingeniería, etc. Por ejemplo, el movimiento de las partículas del agua en una ola, o bien, la simulación en tiempo real de un escenario de entrenamiento, como volar un avión. Las simulaciones garantizan un menor costo y mayor seguridad para los usuarios. <br>
•	Fotografía Computacional: Es el uso de las técnicas de graficación por computadora, visión artificial y proceso digital de imágenes empleadas para mejorar el potencial de la fotografía digital y la calidad de la captura digital de imágenes, desarrollando otras formas de capturar objetos, escenas y ambientes. Permitiéndonos producir equipos fotográficos de bajo costo capaces de identificar caras, hacer reenfoques, panorámicas, e incluso hacer que el resultado luzca similar o mejor al de un equipo caro. <br>
•	Escaneo en 3D: Es el proceso de colectar información de objetos del mundo real para crear un modelo 3D, desarrollando muchos dispositivos y algoritmos para obtener la geometría y apariencia del objeto real, dichos modelos son utilizados para crear visualizaciones. <br>
•	Proceso Digital de Imágenes: Es la aplicación de técnicas y algoritmos para la manipulación de imágenes 2D, para obtener información de éstas, o bien, mejorar su calidad. <br>
•	Realidad Virtual: Es la simulación de un entorno virtual en 3D generado por computadora, que intenta hacer experimentar al usuario una sensación de estar inmerso en él. Aunque puede ser proyectado simplemente en la pantalla de un dispositivo como un monitor, se suelen utilizar otras tecnologías tales como cascos de realidad virtual, guantes, o incluso diseñar espacios, para intensificar las sensación de realidad y que además le permita una mejor interacción con el mundo virtual, creando imágenes realistas, sonidos y otras sensaciones. <br>
•	Realidad Aumentada: Es la visualización de un espacio real en donde a los objetos tangibles de éste se les añade información gráfica generada por computadora, es decir, elementos virtuales son agregados al mundo real, cubriendo total o parcialmente a objetos del entorno, y permitiéndole al usuario interactuar en tiempo real dentro de este espacio mixto. <br>
<img width="950" height="534" alt="image" src="https://github.com/user-attachments/assets/6c773896-d7a5-4ba9-aa62-1be40b35b9b3" />



<h2>1.3. Aspectos matemáticos de la graficación.</h1>


<h2>1.4. Modelos del color: RBG, CMY, HSV y HSL.

(En este apartado puedes colocar un tutorial de como iluminar un cubo y sus caras, en blender)


\`\`\`python
def saludo():
    print("Hola Mundo")
\`\`\`

ejemplo 

<h2>1.5. Representación y trazo de líneas y polígonos.</h2>

<h3>1.5.1 Formatos de imagen.</h3>

(En este apartado vas a colocar las prácticas de dibujo de un polígono y la flor de la vida, como ejercicio práctico)

<h2>1.6. Procesamiento de mapas de bits.  </h2>

</div>

Referencias 

https://www.scribbr.es/citar/generador/
