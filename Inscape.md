

![Captura de pantalla de 2021-10-20 13-53-08](https://user-images.githubusercontent.com/90753279/138089405-300f224d-e4bb-4c1d-99a3-68a171cb908b.png)




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

Leon 1 x160 de ancho

![imagen](https://user-images.githubusercontent.com/90753194/139021990-3cf2bd21-8c8a-47a3-a7f1-3f1417c9dc38.png)
 
Leon 2 x350 de ancho

![imagen](https://user-images.githubusercontent.com/90753194/139022325-4cd168bf-2662-41a4-a6be-27ba54881c94.png)

Leon 3 x800 de ancho

![imagen](https://user-images.githubusercontent.com/90753194/139022338-4dc849dc-476f-43dc-87b6-910ff297b749.png)

Leon 4 x1500 de ancho

![imagen](https://user-images.githubusercontent.com/90753194/139022345-64a85883-99a9-4ae6-8c1a-c719885cef06.png)



![imagen](https://user-images.githubusercontent.com/90753194/139022361-050a30dc-eb02-4b70-9011-164b72228035.png)



![imagen](https://user-images.githubusercontent.com/90753194/139022391-3cdf2693-60bf-4c50-855f-e37eab4d5874.png)
