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

<img width="1532" height="842" alt="image" src="https://github.com/user-attachments/assets/6ccf8a13-1de1-4c27-94f3-e48aa82fc324" /><br>

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
Los aspectos matemáticos de la graficación por computadora se basan en la geometría y el álgebra para crear y manipular imágenes. Utilizan el plano cartesiano (coordenadas X, Y, Z), transformaciones geométricas (escalado, rotación, traslación) y modelos matemáticos como geometría fractal, descriptiva y vectorial para definir puntos, líneas y polígonos. <br> 

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/eb7b31bd-dfb1-44d8-b1ab-77169e3ea9da" /><br>

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

<h2>1.4. Modelos del color: RGB, CMY, HSV y HSL.</h2>
Un modelo de color establece un conjunto de colores primarios a partir de los que, mediante mezclas, se pueden obtener otros colores hasta cubrir todo el espectro visible, además del propio blanco, negro y grises, y aún más. Por ejemplo, hay colores, como el marrón o el magenta, que no están presentes en el espectro visible, y es nuestro cerebro el que lo interpreta a partir de la combinación de ondas con diferentes longitudes.<br>
Los modelos de color más comunes son RGB (utilizado en monitores) y CMYK (utilizado para impresión). <br>

### Modelos aditivos y sustractivos<br>
Hay dos tipos de modelos de color, los aditivos y los sustractivos. Un modelo aditivo se basa en la adición o mezcla de los colores básicos como forma para obtener el blanco. <br>
Un modelo sustractivo se basa en la mezcla de los colores primarios de dicho modelo para «sustraer la luz», es decir, para obtener el negro. Cuando empleamos el término «color» en realidad nos referimos al «matiz» o «croma». Y junto a los colores también tenemos los tres casos especiales: el blanco, el negro y los grises. <br>

### Modelo RGB<br>
El modelo RGB define como colores primarios el rojo, el verde y el azul. La combinación de los tres genera blanco. La ausencia de los tres genera negro. Las diferentes mezclas entre ellos representarían toda la gama de color. De nuevo, los grises se representarían con diferentes intensidades de cada color, pero siempre los tres con el mismo valor.<br>

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/601695b9-8c6c-4308-9da4-f58221f30904" /><br>

El modelo RBG se utiliza cuando se representa color mediante haces de luz (pantallas o monitores). Un pixel en un monitor se representaría mediante tres subpíxeles o células: una roja, una verde y una azul, correspondiendo cada una a un LED o diodo emisor de luz del respectivo color. <br>
Si los tres diodos están apagados, obtendríamos el negro. Si están encendidos a diferentes intensidades, obtendríamos colores, si están todos encendidos con la misma intensidad y al máximo, tendríamos el blanco, y si la intensidad es menor pero igual en los tres diodos, obtendríamos grises. <br>

### Modelo CMYK<br>
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

### Modelo HSV y HSL<br>
Estos modelos incluyen otros dos parámetros adicionales al matiz o croma para obtener el color, que son la saturación (en ambos) y el valor (en HSV) o la luminosidad o tono (en HSL). De ahí sus siglas: HSL (H – hue o matiz, S – saturation o saturación, L – luminosity o luminosidad/tono), HSV (idem excepto V de value o valor). <br>
La diferencia entre HSV y HSL es que en HSV la saturación va del color puro al blanco, y en HSL la saturación va del color puro al gris medio, y el tono, en HSV va desde el negro al color, y en HSL va desde el negro al blanco. De ahí que HSL sea el que se utiliza más comúnmente en fotografía. <br>

<img width="1020" height="500" alt="image" src="https://github.com/user-attachments/assets/fca41a3d-51a1-4e43-9241-95d9899e20c8" /><br>

Lightroom, que se basa en HSL, dispone de controles para alterar H – matiz, S – saturación y L – Tono para los siguientes colores: rojo, naranja, amarillo, verde, cian, azul, violeta y magenta. <br>
Siguiendo con Lightroom, éste nos permite fijar la saturación entre gris y color puro para esos 8 colores. Respecto al matiz, nos permite virar los 8 colores a los adyacentes que comentaba en el artículo de luz y color, por ejemplo, para el rojo, desde magenta a naranja. <br>
Por último, respecto al tono, Lightroom nos permite oscurecer cada uno de esos 8 colores hasta el negro, o bien aclararlo hasta llegar al blanco. <br>

# Iluminación de un cubo y sus caras, en Blender <br>
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
La representación y trazo de líneas y polígonos en graficación consiste en definir figuras geométricas mediante vértices en un plano cartesiano y renderizarlas usando algoritmos como DDA o Bresenham para líneas. Se emplean estructuras de datos para cerrar polígonos uniendo puntos, formando superficies cerradas y contornos. <br>

Representación de Líneas: Se define mediante dos puntos (x_1,y_1) y (x_2,y_2). Los algoritmos principales incluyen: <br>
	DDA (Digital Differential Analyzer): Algoritmo incremental basado en la pendiente. <br>
	Bresenham: Algoritmo eficiente que utiliza solo aritmética de enteros, ideal para hardware gráfico. <br>
	Xiaolin Wu: Algoritmo para antialiasing (suavizado de líneas). <br>

 <img width="1020" height="617" alt="image" src="https://github.com/user-attachments/assets/8fa6c846-7866-482e-8b67-3b507ffa70e1" /> 

Representación de Polígonos: Son superficies planas encerradas por segmentos rectos, definidos por sus vértices en orden (ciclo). Se clasifican en regulares e irregulares. <br>
Trazo y Visualización: <br>
	Líneas: Pueden tener distintos grosores, colores y estilos (sólida, punteada). <br>
	Polígonos: Se trazan uniendo los vértices secuencialmente. Implica el uso de un «lienzo» y métodos gráficos para dibujar el contorno. <br>
	Líneas Poligonales: Pueden ser abiertas o cerradas (cuando los extremos coinciden). <br>

 Representación en el Plano Cartesiano (Computación)
•	Se definen los vértices como pares ordenados (x,y).
•	El trazo sigue un orden consecutivo, uniendo el punto A con B, B con C, y finalmente el último con el primero para cerrar el polígono.

Algoritmos de trazado: <br>
	DDA: Calcula puntos intermedios sumando la pendiente a la coordenada actual. <br>
	Bresenham: Selecciona el píxel más cercano a la línea ideal, evitando la división y el redondeo para mayor rapidez. <br>
 <img width="1020" height="741" alt="image" src="https://github.com/user-attachments/assets/0597adeb-59b4-438f-881e-3f85ce39b3c4" />


<h3>1.5.1 Formatos de imagen.</h3>
Los formatos de imagen en graficación son métodos de codificación y almacenamiento de datos visuales (píxeles o vectores). Se dividen en mapa de bits (JPG, PNG, GIF, TIFF, BMP) y vectoriales (SVG, AI, EPS), determinando la calidad, peso, compresión y transparencia. La elección depende del uso final: web, impresión o edición. <br>
 <br>

Principales Formatos de Mapa de Bits (Ráster) <br>
•	JPG/JPEG (Joint Photographic Experts Group): Formato estándar para fotos en web. Ofrece alta compresión, pero pierde calidad al editar y guardar reiteradamente. <br>
•	PNG (Portable Network Graphics): Ideal para web con fondos transparentes. Utiliza compresión sin pérdida, manteniendo alta calidad. <br>
•	GIF (Graphics Interchange Format): Limitado a 256 colores. Utilizado para animaciones web simples. <br>
•	TIFF (Tagged Image File Format): Alta calidad, sin compresión. Utilizado en impresión profesional. <br>
•	BMP (Bitmap): Formato nativo de Windows, sin compresión, lo que resulta en archivos muy pesados. <br>
•	RAW: Formato crudo de cámaras digitales con máxima información, esencial para edición profesional. <br>

Formatos Vectoriales <br>
•	SVG (Scalable Vector Graphics): Estándar web para gráficos escalables que no pierden calidad al cambiar de tamaño. <br>
•	AI/EPS: Formatos de trabajo de Adobe Illustrator para edición profesional. <br>

<img width="1020" height="444" alt="image" src="https://github.com/user-attachments/assets/3e4572a4-50a2-4a1e-aac5-6dee46ce4d8b" /><br>

Tipos de Compresión <br>
•	Con pérdida (Lossy): Reduce el peso del archivo eliminando información, como en JPG. <br>
•	Sin pérdida (Lossless): Reduce el peso sin eliminar información, como en PNG o TIFF. <br>

La elección adecuada entre compresión y calidad es crucial para la velocidad de carga en sitios web (optimizando archivos) o la calidad final en la impresión. <br>

# Práctica de dibujo de un polígono
El script automatiza la creación de polígonos regulares (n-gonos) en el espacio 2D de Blender. Utiliza la librería math para calcular coordenadas polares y la API bpy para instanciar objetos de malla (mesh) de forma programática.<br>

 1. De Polares a Malla (Mesh). Para crear un polígono regular (como un hexágono o un pentágono), el código utiliza el concepto de distribución radial de vértices. A diferencia de la práctica anterior, aquí no solo posicionamos objetos, sino que definimos los puntos exactos que componen una malla.     
-Cálculo del Ángulo: Se divide una circunferencia completa (2π radianes) entre el número de lados deseados.    
-Conversión a Cartesianas: Se aplican las funciones trigonométricas para obtener las coordenadas de cada vértice:     
x = radio·cos(Ɵ)     
x = radio·sin(Ɵ)     

2. Lógica de Programación: Creación de Datos de Malla. El algoritmo se divide en tres fases críticas para que Blender pueda renderizar el objeto:     
-Generación de Vértices: Se utiliza un ciclo for para calcular las posiciones (x, y, 0) de cada esquina del polígono y se guardan en una lista.     
-Definición de Aristas (Edges): Para conectar los puntos, se crean parejas de índices. Por ejemplo, el vértice 0 se conecta con el 1, el 1 con el 2, y así sucesivamente. El uso del operador módulo % permite que el último vértice se conecte automáticamente con el primero para cerrar la figura.     
-Carga de Datos (from_pydata): Esta es la función clave de Blender que toma las listas de vértices y aristas para construir físicamente la geometría en la escena.

3. Código Implementado y Explicado. El script define una función reutilizable llamada crear_poligono_2d:
   
```python
import bpy
import math

def crear_poligono_2d(nombre, lados, radio):
    # Crear nueva malla y objeto
    malla = bpy.data.meshes.new(nombre)
    objeto = bpy.data.objects.new(nombre, malla)

    # Vincular objeto a la colección actual
    bpy.context.collection.objects.link(objeto)

    vertices = []
    aristas = []

    # Crear vértices
    for i in range(lados):
        angulo = 2 * math.pi * i / lados
        x = radio * math.cos(angulo)
        y = radio * math.sin(angulo)
        vertices.append((x, y, 0))  # Z = 0 para 2D

    # Crear aristas
    for i in range(lados):
        aristas.append((i, (i + 1) % lados))

    # Cargar datos en la malla
    malla.from_pydata(vertices, aristas, [])
    malla.update()


#  Limpiar escena antes de crear el objeto
bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()

#  Llamar función (Hexágono de radio 5)
crear_poligono_2d("Poligono2D", lados=6, radio=5)
```

#### Pasos que realiza el programa
1. *Importar módulos*:
    - `bpy`: API de Blender para manipular datos y objetos.
    - `math`: para cálculos trigonométricos (seno y coseno).

2. *Definir la función `crear_poligono_2d(nombre, lados, radio)`*:
    - *Crear malla y objeto*:
        - Se genera una nueva malla (`mesh`) y un objeto (`object`) con el nombre especificado.
        - El objeto se vincula a la colección activa de la escena.

    - *Calcular vértices*:
        - Usa trigonometría para generar los vértices de un polígono regular inscrito en un círculo de radio dado.
        - Los vértices se almacenan en una lista `[x, y, 0]` (el eje Z es 0 para 2D).

    - *Definir aristas*:
        - Crea conexiones entre los vértices consecutivos (incluyendo el cierre del polígono con el módulo `%`).

    - *Asignar datos a la malla*:
        - Usa `from_pydata` para cargar los vértices y aristas en la malla.
        - Actualiza la malla con `update()`.

    - *Limpiar escena*:
        - Elimina todos los objetos seleccionados antes de crear el nuevo polígono (útil para evitar duplicados).

3. *Ejecución*:
    - Llama a la función con parámetros específicos (ejemplo: un hexágono de radio 5).

<img width="1020" height="900" alt="image" src="https://github.com/user-attachments/assets/60663acb-d36c-4822-846c-b1c0fe6de543" />


# Práctica de dibujo de la flor de la vida

Práctica 1: Geometría Generativa con Python en Blender.

1. La base Matemática: Coordenadas Polares
Para posicionar cualquier objeto en un círculo (como los centros de los círculos periféricos
de nuestra figura), no usamos coordenadas X e Y de forma directa, sino coordenadas
polares (r, Ɵ).
Para que Blender entienda dónde colocar un objeto, debemos convertir esas coordenadas polares
a Cartesianas usando las funciones trigonométricas básicas:

x = r·cos(Ɵ)   
x = r·sin(Ɵ)

Donde r es el radio (la distancia desde el origen) y Ɵ es el ángulo en radianes. En Python,
como el círculo completo tiene 360°, usamos math.radians() para convertir los grados a
un formato que las funciones sin y cos entiendan.

2. Lógica de Construcción
La figura "Flor de la Vida" se basa en un concepto simple: Desplazamiento del Centro.     
 Círculo Base: Dibujamos un círculo con centro en $(0, 0, 0)$.     
 Círculos Periféricos: Los centros de los siguientes círculos deben estar ubicados
exactamente sobre el perímetro del primer círculo.     
 El Patrón: Si queremos que la figura sea simétrica y perfecta (como la imagen roja),
necesitamos distribuir los centros uniformemente. Dividimos los 360° de la circunferencia
entre el número de círculos que queremos (en este caso, 6 círculos, por lo que el paso es de
60°).

3. Algoritmo de la Práctica (Paso a Paso)      
 Paso 1: Configuración del entorno. Importar la librería bpy para controlar Blender y
math para los cálculos. Limpiar la escena para no encimar objetos en cada ejecución.     
 Paso 2: Definición de variables. Establecer el radio del círculo y el angulo_actual
(iniciando en 0).     
 Paso 3: Trazado del origen. Crear la primitiva de círculo en el centro exacto de la
escena.     
 Paso 4: Identificación de la repetición. Aquí es donde el alumno nota que para el
segundo círculo debe sumar 60° al ángulo, calcular la nueva $x, y$, y volver a ejecutar el
comando de creación.
Explicación de la ejecución del código en Blender (Python)

```python
import bpy
import math

# Limpiar escena
bpy.ops.object.select_all(action='SELECT')
bpy.ops.object.delete()

# Parámetros de la figura
radio = 3

angulo_actual = 0
paso_angular = 60  # Cada 60 grados para obtener 6 círculos alrededor

# 1. Círculo central
bpy.ops.mesh.primitive_circle_add(radius=radio, location=(0, 0, 0), vertices=64)

# --- INICIO DEL PATRÓN REPETITIVO ---
while angulo_actual < 360:
    x = radio * math.cos(math.radians(angulo_actual))
    y = radio * math.sin(math.radians(angulo_actual))
    
    bpy.ops.mesh.primitive_circle_add(
        radius=radio,
        location=(x, y, 0),
        vertices=64
    )
    
    angulo_actual += paso_angular
# --- FIN DEL PATRÓN ---
```
<br>
Explicación de la ejecución del código en Blender (Python)<br>
Primero, el código importa los módulos bpy y math, los cuales permiten trabajar con Blender y realizar cálculos matemáticos como seno y coseno.<br>
Después, se limpia la escena seleccionando todos los objetos existentes y eliminándolos, para comenzar con un espacio vacío.<br>

A continuación, se define el radio de los círculos con un valor de 3 y se inicializan las variables angulo_actual y paso_angular. El paso angular se establece en 60 grados para poder distribuir seis círculos de forma uniforme alrededor del centro.<br>

Luego, se crea un círculo central ubicado en el origen (0,0,0) con 64 vértices, lo que permite que tenga una forma suave.<br>
Posteriormente, el programa entra en un ciclo while que se ejecuta mientras el ángulo sea menor a 360 grados. En cada iteración, se calculan las coordenadas x e y usando funciones trigonométricas para posicionar los círculos alrededor del círculo central.<br>

Finalmente, en cada iteración se genera un nuevo círculo en la posición calculada y se incrementa el ángulo, repitiendo el proceso hasta completar los 360 grados, formando un patrón circular de seis círculos alrededor del centro.<br>

Ejecución: El resultado final es una estructura equilibrada y repetitiva, similar a una flor o roseta geométrica.

<img width="1020" height="900" alt="image" src="https://github.com/user-attachments/assets/f497cb5a-6dc0-48cb-9439-bb1a29e9b4a8" /><br>


<h2>1.6. Procesamiento de mapas de bits.  </h2>
El procesamiento de mapas de bits es un conjunto de técnicas y algoritmos utilizados para manipular imágenes digitales que están compuestas por píxeles (mapas de bits o imágenes ráster). Dado que estas imágenes se almacenan como una cuadrícula de datos, el procesamiento se centra en modificar la información de cada píxel, ya sea de forma individual o en relación con sus píxeles vecinos. <br>

<img width="1020" height="510" alt="image" src="https://github.com/user-attachments/assets/2bac88d4-dffe-41eb-98ca-56bb9bd68b49" /><br>

Técnicas Comunes de Procesamiento <br>
El procesamiento de mapas de bits es la base de la mayoría de los programas de edición de imágenes, como Photoshop. Aquí tienes algunas de las técnicas más importantes: <br>
•	Filtros y Efectos: Se aplican a los píxeles de una imagen para cambiar su apariencia. Por ejemplo, los filtros de desenfoque (blur) promedian los valores de color de los píxeles vecinos, los filtros de nitidez (sharpen) realzan los bordes y los filtros de relieve (emboss) simulan efectos de luz y sombra. <br>
•	Transformaciones Geométricas: Permiten modificar la posición y la forma de la imagen. Incluyen: <br>
o	Rotación: Girar la imagen alrededor de un punto. <br>
o	Escalado: Aumentar o disminuir el tamaño de la imagen. Al escalar un mapa de bits, se deben interpolar (calcular) los nuevos píxeles para evitar la pérdida de calidad, lo que a menudo puede resultar en imágenes borrosas o pixeladas. <br>
o	Traslación: Mover la imagen de un lugar a otro. <br>
•	Ajuste de Color y Brillo: Se manipulan los valores de color de los píxeles para corregir la exposición, cambiar la paleta de colores o crear efectos artísticos. Esto se puede hacer ajustando el brillo, el contraste, la saturación o el balance de color de toda la imagen o de partes específicas. <br>
•	Compresión: Reduce el tamaño del archivo para facilitar su almacenamiento y transmisión. Los métodos de compresión se dividen en dos categorías: <br>
o	Compresión con pérdida: Elimina información para reducir drásticamente el tamaño del archivo. El formato JPEG es el ejemplo más conocido, ideal para fotografías. <br>
o	Compresión sin pérdida: Reduce el tamaño del archivo sin eliminar datos, por lo que la calidad de la imagen original se mantiene intacta. El formato PNG es un ejemplo común, perfecto para logotipos o imágenes con transparencias. <br>
•	Conversión de Formatos: Se refiere al proceso de cambiar una imagen de un formato a otro. Por ejemplo, convertir un archivo BMP a JPG para reducir su tamaño o un SVG (formato vectorial) a un mapa de bits (proceso llamado rasterización) para poder visualizarlo en una pantalla. <br>

</div>

# Referencias 
Client challenge. (s. f.-c). https://es.scribd.com/document/490473069/libro-de-texto-de-graficacion-1
Notas para el curso de graficación por computadora. (s. f.). https://prometeo.matem.unam.mx/recursos/VariosNiveles/iCartesiLibri/recursos/Notas_Graficacion_por_Computadora/index.html?page=8
Client challenge. (s. f.). https://es.slideshare.net/slideshow/introduccin-a-la-graficacin-por-computadora/15421140#3
Client challenge. (s. f.-b). https://es.scribd.com/presentation/526947797/Retroalimentacion-1-3-Aspectos-matematicos-de-la-graficacion
Antonio. (2016, 19 junio). Modelos de color (RGB, CMYK, HSV/HSL). Antonio Herrera. https://ahenav.wordpress.com/2014/04/09/modelos-de-color/
Admin_Wp. (s. f.). Formatos de imagen – Blog Software Informático. https://softwareinformatico.com/blog/formatos-de imagen/#:~:text=Formatos%20de%20imagen%20Una%20buena%20elecci%C3%B3n%20en,blogs,%20campa%C3%B1as%20de%20publicidad,%20dise%C3%B1o%20gr%C3%A1fico%20etc.



