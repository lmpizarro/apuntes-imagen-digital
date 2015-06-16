# Compresión de imagen 

Para lograr optimizar el lugar que ocupan los archivos en los dispositivos
de almacenamiento, se requiere reducir el tamaño de los archivos. 

## Algoritmos de compresión

Procedimientos que se aplican a los datos para disminuir el tamaño de los
archivos.

## Sin pérdida de información

Reconstruir sin diferencias,
la información original. Ejemplo archivos ZIP, BZ2, PNG

## Con pérdida de información

Reconstrucción aproximada
de la información original. Ejemplos archivos JPG

# Formato JPEG [link](https://en.wikipedia.org/wiki/JPEG)

# Formato PNG [link](https://en.wikipedia.org/wiki/Portable_Network_Graphics)

## Encabezado del archivo

## Fragmentos

   * Principales
   * Auxiliares

# Unidad de información de imagen, pixel

## Formato del pixel

  * 0: escala de grises
  * 2: rojo, verde, azul: rgb/true color
  * 3: indexed: canal que contiene índices a una paleta de colores
  * 4: escala de grises y alpha: nivel de opácidad de cada pixel
  * 6: rojo, verde, azul y alpha.


# Imagen RAW [link](https://en.wikipedia.org/wiki/Raw_image_format)

Un archivo RAW de imagen contiene información directa del sensor 
de imagen con muy poco procesamiento. 

Es un archivo que no tiene procesamiento y no se puede usar en etapas
sucesivas de un flujo de trabajo. 

Se lo denomina negativo digital, cumplen el mismo rol que los negativos
de la fotografía analógica. No se puede usar directamente, pero contiene
toda la información que se necesita para ser posteriormente utilizado.


El archivo RAW está pensado para almacenar las características radiométricas
de la escena, es decir la información física sobre la intensidad de la luz y
color de la escena.

La mayoría de los formatos RAW guardan la información sensada de acuerdo
a la geometría de los elementos fotoreceptivos del  sensor. Sensores con
desplazamiento hexagonal guardan la información de cada una de las celdas
desplazadas hexagonalmente, un software adecuado lleva esa información
a la geometria rectangular típica.


# DNG (Negativo Digital)[link](https://en.wikipedia.org/wiki/Digital_Negative)

Es un formato de archivo de imagen abierto, sin pérdida y RAW (crudo)

# Cinems DNG [link](https://en.wikipedia.org/wiki/CinemaDNG)

Formato de archivo abierto propuesto por Adobe que contiene,
segmentos de película compuestos por secuencia de archivos RAW
(crudos) de imagen, audio y metadata. Es un contenedor.
Puede contener imágenes DNG, TIFF, XMP y/o MXF

Soporta cámaras stereo y múltiples canales de audio. 

### Metadata: dato sobre el dato, información del contenido del archivo


![nucleos](/images/nucleos.png)
