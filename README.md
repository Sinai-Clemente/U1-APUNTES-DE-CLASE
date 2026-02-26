# U1-APUNTES-DE-CLASE
 <div align="justify"> 
<h1>Unidad I. Introducción a la graficación por computadora. </h1>

La graficación por computadora es el estudio y aplicación de algoritmos, técnicas y software para crear, almacenar, manipular y visualizar imágenes y objetos gráficos en un ordenador. Abarca desde gráficos 2D hasta modelado 3D, animación y renderizado en tiempo real, utilizando técnicas como gráficos raster (píxeles) y vectoriales. Sus usos son esenciales en diseño (CAD), entretenimiento, medicina, simulaciones científicas y visualización de datos.<br>

La graficación interactiva es la técnica de utilizar comunicación bidireccional entre la computadora y el usuario en la que la computadora se comunica con imágenes gráficas. La computadora, al recibir señales del usuario, modifica la imagen. Y el usuario, viendo la imagen, puede tomar acciones para modificarla.<br>

Ejemplos de graficación interactiva:<br>
•	Programa de diseño de circuitos<br>
•	Un juego de video<br>

Ejemplos de graficación pasiva o no interactiva:<br>
•	Un programa que solamente grafica la función seno(x) es un ejemplo de graficación no interactiva, o pasiva.<br>

<img width="1020" height="400" alt="image" src="https://github.com/user-attachments/assets/f10aa7d4-c0e7-4df4-9871-f516201dadfc" /> <br>

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

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/4505a7ae-a3e0-43c9-82ec-485cfd1fc3b0" /><br>

<h2>1.2. Áreas de aplicación.</h2>
La graficación por computadora (GC) es un campo multidisciplinario bastante amplio, donde tanto computólogos, matemáticos, físicos, ingenieros, artistas y otros practicantes comparten un mismo objetivo "mostrar un mundo a través de una ventana", nos podemos referir como mundo a un modelo digital, una simulación, o bien, cualquier representación visual que se busque mostrar, y como ventana a cualquier medio para mostrar imágenes, como un proyector, la pantalla de un monitor, tablet, entre otros. Por lo que nos podemos dar una idea de las multiples aplicaciones que se pueden obtener en este campo sobre los diferentes ámbitos, veamos algunas de estas aplicaciones: <br>
•	Industria del entretenimiento: Creación de películas o caricaturas sintéticas, publicidad, efectos visuales y videojuegos. <br>
•	Ingeniería Mecánica: Diseño de prototipos virtuales de partes mecánicas para su construcción, utilizando sistemas CAD/CAM (Computer-Aided Design/ Computer-Aided Manufacturing). <br>
•	Arquitectura: Uso del software CAD para la creación de planos de alguna estructura arquitectónica, visualizaciones de espacios antes y después de una construcción planeada. <br>
•	Diseño: Diseño y creación de productos, haciendo uso de sistemas CAD/CAM, promoviendo la creatividad del diseñador al permitirle experimentar con varias formas antes de producir la idea final. <br>
•	Patrimonio cultural: Reconstrucciones virtuales de templos, monumentos, piezas antiguas, o bien, reconstrucciones hipotéticas de escenas. <br>
•	Medicina: Simulaciones virtuales de cirugías para entrenamiento y visualización de datos dados por algún instrumento de diagnóstico. <br>

<br><img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/5f80f7f6-abec-4743-98c9-136dbdd89d56" /><br>

Asimismo, se han ido desarrollando un gran número de áreas de especialización, las cuales han ido evolucionando de acuerdo a las necesidades de los usuarios y al avance tecnológico en el hardware y software. Las principales suelen ser las siguientes: <br>
•	Renderización: Es el proceso para generar una imagen final dada una entrada ordenada de datos, se suele clasificar dependiendo del algoritmo que se use, generalmente se toma como referencia el tiempo que a éste le tome en producir una imagen sintética (Real time rendering, Offline rendering), o bien, el tipo de técnica de renderizado que utilice (Photorealistic rendering, non-photorealistic rendering o information visualization). <br>
•	Modelado: Es la especificación matemática del mundo a representar, es decir, se describen los objetos y sus propiedades de un modo que éstos puedan ser almacenados en la computadora, por ejemplo, una manzana puede ser descrita como un conjunto de puntos 3D, los cuales forman caras ordenadas, con un modelo de iluminación especifico para describir cómo interactúa la luz con la manzana. <br>
•	Animación: Es la creación de una secuencia de imágenes con una computadora, que tiene como finalidad producir la ilusión de movimiento. Si bien, hace uso de las dos áreas anteriores, no se encarga del estudio de éstas, pues su objetivo es añadir alguna animación sobre un rango de tiempo específico a los modelos, con la cual modifica algún aspecto de éstos, como su color, posición, apariencia, entre otros. <br>

<img width="1020" height="600" alt="image" src="https://github.com/user-attachments/assets/506d0355-69cc-4cec-9138-8f249dc88366" /><br>

Y entre algunas otras áreas de relevancia se encuentran: <br>
•	Simulación: Es el proceso en el que un modelo matemático es ejecutado y representado con una computadora, la cual es usada para simular un comportamiento y su repercusión en el mundo real, o bien, dentro de un sistema físico impuesto, permitiendo revisar la fiabilidad del modelo, por lo cual es útil para modelar sistemas en física, astrofísica, climatología, química, biología, economía, ingeniería, etc. Por ejemplo, el movimiento de las partículas del agua en una ola, o bien, la simulación en tiempo real de un escenario de entrenamiento, como volar un avión. Las simulaciones garantizan un menor costo y mayor seguridad para los usuarios. <br>
•	Fotografía Computacional: Es el uso de las técnicas de graficación por computadora, visión artificial y proceso digital de imágenes empleadas para mejorar el potencial de la fotografía digital y la calidad de la captura digital de imágenes, desarrollando otras formas de capturar objetos, escenas y ambientes. Permitiéndonos producir equipos fotográficos de bajo costo capaces de identificar caras, hacer reenfoques, panorámicas, e incluso hacer que el resultado luzca similar o mejor al de un equipo caro. <br>
•	Escaneo en 3D: Es el proceso de colectar información de objetos del mundo real para crear un modelo 3D, desarrollando muchos dispositivos y algoritmos para obtener la geometría y apariencia del objeto real, dichos modelos son utilizados para crear visualizaciones. <br>
•	Proceso Digital de Imágenes: Es la aplicación de técnicas y algoritmos para la manipulación de imágenes 2D, para obtener información de éstas, o bien, mejorar su calidad. <br>
•	Realidad Virtual: Es la simulación de un entorno virtual en 3D generado por computadora, que intenta hacer experimentar al usuario una sensación de estar inmerso en él. Aunque puede ser proyectado simplemente en la pantalla de un dispositivo como un monitor, se suelen utilizar otras tecnologías tales como cascos de realidad virtual, guantes, o incluso diseñar espacios, para intensificar las sensación de realidad y que además le permita una mejor interacción con el mundo virtual, creando imágenes realistas, sonidos y otras sensaciones. <br>
•	Realidad Aumentada: Es la visualización de un espacio real en donde a los objetos tangibles de éste se les añade información gráfica generada por computadora, es decir, elementos virtuales son agregados al mundo real, cubriendo total o parcialmente a objetos del entorno, y permitiéndole al usuario interactuar en tiempo real dentro de este espacio mixto. <br>

<img width="1020" height="600" alt="image" src="https://github.com/user-attachments/assets/6c773896-d7a5-4ba9-aa62-1be40b35b9b3" /><br>

<h2>1.3. Aspectos matemáticos de la graficación.</h1>

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/eb7b31bd-dfb1-44d8-b1ab-77169e3ea9da" /><br>

Los aspectos matemáticos de la graficación por computadora se basan en la geometría y el álgebra para crear y manipular imágenes. Utilizan el plano cartesiano (coordenadas X, Y, Z), transformaciones geométricas (escalado, rotación, traslación) y modelos matemáticos como geometría fractal, descriptiva y vectorial para definir puntos, líneas y polígonos. <br> 
Aspectos Matemáticos Clave: <br>
•	Sistemas de Coordenadas: El uso de coordenadas cartesianas (x, y) en 2D y (x, y, z) en 3D para ubicar píxeles o vértices. <br>
•	Geometría Computacional: <br>
o	Geometría Euclidiana/Analítica:  Aplicación de fórmulas para dibujar líneas (Y=mx+b) y formas geométricas (circunferencias, polígonos). <br>
o	Geometría 3D: Uso de vectores para representar dirección y magnitud, esencial para modelar superficies curvas y sólidos como cubos o esferas. <br>
o	Geometría Fractal: Estudio de métodos automáticos repetitivos (recursivos) para generar estructuras complejas autosimilares, como el Triángulo de Sierpinski o el Copo de Nieve de Koch. <br>
o	Geometría Descriptiva: Es un conjunto de técnicas geométricas que permite representar el espacio tridimensional sobre una superficie bidimensional. <br>
•	Transformaciones Geométricas: Operaciones matriciales para mover, rotar o cambiar el tamaño de objetos. <br>
•	Representación de Imágenes: Píxeles que toman formas específicas para construir imágenes mediante algoritmos gráficos. <br> 
La graficación transforma modelos matemáticos abstractos en representaciones visuales funcionales. <br>

<img width="1020" height="100" alt="image" src="https://github.com/user-attachments/assets/d1c80605-bda3-4b16-9ab2-916bf0403321" /><br>

<h2>1.4. Modelos del color: RBG, CMY, HSV y HSL.</h2>
Un modelo de color establece un conjunto de colores primarios a partir de los que, mediante mezclas, se pueden obtener otros colores hasta cubrir todo el espectro visible, además del propio blanco, negro y grises, y aún más. Por ejemplo, hay colores, como el marrón o el magenta, que no están presentes en el espectro visible, y es nuestro cerebro el que lo interpreta a partir de la combinación de ondas con diferentes longitudes.<br>
Los modelos de color más comunes son RGB (utilizado en monitores) y CMYK (utilizado para impresión). <br>

Modelos aditivos y sustractivos<br>
Hay dos tipos de modelos de color, los aditivos y los sustractivos. Un modelo aditivo se basa en la adición o mezcla de los colores básicos como forma para obtener el blanco. <br>
Un modelo sustractivo se basa en la mezcla de los colores primarios de dicho modelo para «sustraer la luz», es decir, para obtener el negro. Cuando empleamos el término «color» en realidad nos referimos al «matiz» o «croma». Y junto a los colores también tenemos los tres casos especiales: el blanco, el negro y los grises. <br>

Modelo RGB<br>
El modelo RGB define como colores primarios el rojo, el verde y el azul. La combinación de los tres genera blanco. La ausencia de los tres genera negro. Las diferentes mezclas entre ellos representarían toda la gama de color. De nuevo, los grises se representarían con diferentes intensidades de cada color, pero siempre los tres con el mismo valor.<br>

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/601695b9-8c6c-4308-9da4-f58221f30904" /><br>

El modelo RBG se utiliza cuando se representa color mediante haces de luz (pantallas o monitores). Un pixel en un monitor se representaría mediante tres subpíxeles o células: una roja, una verde y una azul, correspondiendo cada una a un LED o diodo emisor de luz del respectivo color. <br>
Si los tres diodos están apagados, obtendríamos el negro. Si están encendidos a diferentes intensidades, obtendríamos colores, si están todos encendidos con la misma intensidad y al máximo, tendríamos el blanco, y si la intensidad es menor pero igual en los tres diodos, obtendríamos grises. <br>

Modelo CMYK<br>
Es un modelo sustractivo y se utiliza en impresión a partir de pigmentos de tres colores básicos: C – cian, M – magenta y Y – amarillo. La K viene del negro, ya que la combinación de los tres anteriores produce un negro poco puro, de ahí que se añada al modelo un pigmento negro puro. Al contrario que en RGB, donde el negro es la ausencia de luz, en CMYK el blanco se representa aquí como ausencia de pigmentos. <br>
Los colores intermedios se producen a partir de la mezcla en distintas proporciones de los pigmentos base. <br>

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/ed03d50a-40e5-40fa-ae43-0780a7635a19" /><br>

Hay una relación entre los modelos RGB y CMYK, ya que con la mezcla a igual parte de cada uno de los colores básicos de un modelo obtenemos los primarios del otro. <br>
En RGB (rojo, verde, azul): <br>
	Rojo y verde en iguales proporciones: obtenemos amarillo – Y de CMYK<br>
	Rojo y azul en iguales proporciones: obtenemos el magenta – M<br>
	Verde y azul en iguales proporciones: obtenemos el cian – C<br>

En CMYK (cian, magenta, amarillo): <br>
	Cian y magenta en igual proporción: obtenemos el azul<br>
	Cian y amarillo en igual proporción: obtenemos el verde<br>
	Magenta y amarillo en igual proporción: obtenemos el rojo<br>

Modelo HSV y HSL<br>
Estos modelos incluyen otros dos parámetros adicionales al matiz o croma para obtener el color, que son la saturación (en ambos) y el valor (en HSV) o la luminosidad o tono (en HSL). De ahí sus siglas: HSL (H – hue o matiz, S – saturation o saturación, L – luminosity o luminosidad/tono), HSV (idem excepto V de value o valor). <br>
La diferencia entre HSV y HSL es que en HSV la saturación va del color puro al blanco, y en HSL la saturación va del color puro al gris medio, y el tono, en HSV va desde el negro al color, y en HSL va desde el negro al blanco. De ahí que HSL sea el que se utiliza más comúnmente en fotografía. <br>

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/fca41a3d-51a1-4e43-9241-95d9899e20c8" /><br>

Lightroom, que se basa en HSL, dispone de controles para alterar H – matiz, S – saturación y L – Tono para los siguientes colores: rojo, naranja, amarillo, verde, cian, azul, violeta y magenta. <br>
Siguiendo con Lightroom, éste nos permite fijar la saturación entre gris y color puro para esos 8 colores. Respecto al matiz, nos permite virar los 8 colores a los adyacentes que comentaba en el artículo de luz y color, por ejemplo, para el rojo, desde magenta a naranja. <br>
Por último, respecto al tono, Lightroom nos permite oscurecer cada uno de esos 8 colores hasta el negro, o bien aclararlo hasta llegar al blanco. <br>

#### Iluminación de un cubo y sus caras, en Blender <br>
Para esta práctica, primero se abre el programa Blender y se selecciona el cubo que aparece por defecto en la escena. Posteriormente, en el panel derecho, se busca la opción Materiales y se da clic sobre ella. <br>

<img width="1172" height="622" alt="image" src="https://github.com/user-attachments/assets/3b7a60cb-e5c6-4d64-910e-556f76fbc8c3" /><br>

A continuación, en el apartado Color base, se despliega la paleta de colores y se selecciona el color deseado para el cubo.<br>

<img width="1176" height="620" alt="image" src="https://github.com/user-attachments/assets/600880ac-ce70-4acc-b955-ebf2a3ff4148" /><br>

Una vez asignado el material, se presiona la tecla F12 para renderizar la escena y observar el cubo iluminado. <br>

<img width="1020" height="488" alt="image" src="https://github.com/user-attachments/assets/77d87c0c-b246-4e9b-b65b-2ee9fcf5ee2c" /><br>

Para asignar diferentes colores a las caras del cubo, se da clic en el símbolo “+”, que corresponde a Agregar contenedor de material.<br>

<img width="1174" height="623" alt="image" src="https://github.com/user-attachments/assets/89069b88-b12e-463c-9ea9-8e2a91cb47d3" /><br>

Y después se selecciona la opción Nuevo.<br>

<img width="1169" height="609" alt="image" src="https://github.com/user-attachments/assets/2155b5cb-a009-4f7f-9146-683a6159dcc7" /><br>

Nuevamente, en Color base, se elige un color distinto. <br>

<img width="1169" height="624" alt="image" src="https://github.com/user-attachments/assets/3f8f6a1d-162f-436b-bd27-e5e63d9a6ed3" /><br>

Después, se cambia a la pestaña Modo Objeto y se selecciona Modo Edición.<br>

<img width="1167" height="623" alt="image" src="https://github.com/user-attachments/assets/5342ee3c-7dbd-42a6-a328-deb81c55c3c1" /><br>

En la barra de herramientas se activa el Modo de selección de caras y se elige la cara del cubo a la que se desea aplicar el nuevo color. En el apartado de materiales, se presiona la opción Asignar. <br>

<img width="1170" height="623" alt="image" src="https://github.com/user-attachments/assets/7ef286b8-a3a6-4f4d-ac00-040acc89038e" /><br>

Finalmente, se vuelve a presionar la tecla F12 para visualizar el resultado.<br>

<img width="1020" height="488" alt="image" src="https://github.com/user-attachments/assets/16f9acc1-3c6b-403f-b58b-4765367ade4f" /><br>

Este procedimiento se repite de la misma manera para aplicar diferentes colores a las demás caras del cubo. <br>


<h2>1.5. Representación y trazo de líneas y polígonos.</h2>

<h3>1.5.1 Formatos de imagen.</h3>

(En este apartado vas a colocar las prácticas de dibujo de un polígono y la flor de la vida, como ejercicio práctico)
```python
def saludo():
    print("Hola Mundo")
```

ejemplo 

<h2>1.6. Procesamiento de mapas de bits.  </h2>

</div>

Referencias 

https://www.scribbr.es/citar/generador/
