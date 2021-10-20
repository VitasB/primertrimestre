
Imagenes
 -por el lado(ráster) podemos haceruna matriz de punos(mapa de bits) y a cada punto le ásignamos un color(píxel)
 

### Propiedas de una imagen ráster
* Resolución. Una mapa de bitd tiene untamańo la resolución se puede expresar de diferentes formas.
*  Numero total de píxeles. Normalmente MP (megapíxel) esto es el número que resulta de Axó en millone de píxeles.   3MP
*  Líneas horizontales. En vídeo se utiliza la camtidad de líneas horizontales, normalmente se asume una properacíon concreta entre AyB.
-  144p
-  240p
-  480p
-  720p
-  1080p
-1440p
*  2k
*  4k
*  Un archivo puede empresar su relución diciendo Axó. Por ejemplo una imagen el 350x250x píxeles.
*  Se utiliza cuantos hablamos de archivos concretos.

# 
Pixeles, la nunidad de la pantalla

1.100----3D----2D

2D: raster y vectorin

ImaGENES: Las imagenes se guardan digitalmente de dos maneras. 

RASTER: Por un lado podemos hacer una matriz de puntos (MAPA DE BITS) y a cada punto le asignamos un color.


RESOLUCION: UN MAPA DE TIENE UN TAMAÑO CONCRETO

de a x b

La resolucion se puede expresar de diferentes formas: 

Numero total de pixeles, normalmente megapixeles (mp) esto es el numero que resulta de a x b en millones de pixeles

Lineas horizontales: en el video se utiliza la cantidad de lineas horizontales, normalmente se asume una medida, crean ellas en A y B por medida

formatos comunes:

![JPG](https://www.cleverfiles.com/howto/wp-content/uploads/2018/03/minion.jpg)

png

tiff

![GIF](https://i2.wp.com/hipertextual.com/wp-content/uploads/2016/10/giphy.gif?w=400&ssl=1)

 Rasterizamos una imagen, cuando pasamos de una imagen "Vectorial" a una imagen "Raster" (Mapa Debits)
 Vectorizar es pasar de un mapa de bits.(Imagen Rástera) A formato vectoral.

### Ejercicio vectorización

Vamos a tomar la imagen de cuadro del león de Rosa Bonhevr.
Esta es la imagen rasterizada original 

![LEON ROSA BONHEUR](https://content3.cdnprado.net/imagenes/Documentos/imgsem/a6/a61b/a61b0f48-75f0-43fe-a995-63cc36158cbc/51b34837-980c-420b-8be3-76e896cce33b_268.jpg)

[ORIGINAL](https://imagenes.elpais.com/resizer/BZC1wtnQ7F9Fh9_KJdxKWADf-yA=/1960x0/arc-anglerfish-eu-central-1-prod-prisa.s3.amazonaws.com/public/XFGHWVUB6GGPQQBIV36UCJXVOY.jpg)

Tamaño personalizado, ancho 600, alto 1000, cerramos la ventana, accedemos a la imagen de internet

-archivo importar
-Arrastras la imagen
-Copiar y pegar la imagen


### Ejercicio Vectorizacion

* Vectorizaciamos el leon con las siguientos caracteristicas 
* Multiples dasadas, colores, pasadas
* Borramos el Ráster
* Guardamos como "leon".svg
* Subimos al Github
- Leon 1.svg
- Despues de importar el leon lamos a ajustar el lienzo. Para ello vamos a ajustar pagina o contenido seleccionamos la imagen y pulsamos el boton (Ajustar pagina a contenido o seleccion)



![Captura de pantalla de 2021-10-20 12-52-29](https://user-images.githubusercontent.com/90753262/138080136-03d115c5-7e08-42da-aab0-bd156e229fd7.png)



## explicacin del cuadro de vecotira

Existen varias opciones

Lo primero es decidir si el programa hara una o mas pasadas

con una unica pasada siempre obtendremos una imgane en blanco y negro (que podemos colorear despues)

Una unica pasada tenemos detecion de bordes --- revisa el contraste entre pixeles

Corte de luminosidad: jkunta todos los pixeles mas oscuros que un umbral
