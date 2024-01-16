# Autoencoder
Este repositorio contiene varios proyectos de autoencoders aplicados al conjunto de datos MNIST. Cada proyecto se enfoca en una tarea específica de procesamiento de imágenes y se proporcionan las medidas de rendimiento correspondientes.

## Proyecto 1: Reducción de Ruido con Autoencoder en MNIST

- Archivo: `Proyecto.ipynb`
- Descripción: En este proyecto se implementa un autoencoder para reducir el ruido en imágenes del conjunto de datos MNIST. Se evalúa el rendimiento del modelo y se proporcionan las siguientes métricas:
  - SSIM promedio: 0.9413
  - MAE promedio: 0.0222
  - PSNR promedio: 71.29 dB
  - Histogramas de densidades de la imagen original y la salida prácticamente iguales
  - PCA del espacio latente que distingue entre los 10 números

## Proyecto 2: Super Resolución de Imágenes de 14x14 a 28x28 en MNIST

- Archivo: `Proyecto14x14.ipynb`
- Descripción: Este proyecto se centra en la super resolución de imágenes de 14x14 a 28x28 píxeles en el conjunto de datos MNIST. Se evalúa el rendimiento del modelo y se proporcionan las siguientes métricas:
  - PSNR promedio: 67.54 dB
  - SSIM promedio: 0.9445
  - MAE promedio: 0.1276
  - Histogramas de densidades de la imagen original y la salida prácticamente iguales, aunque con algo de ruido en la salida
  - PCA con ruido en el espacio latente pero distinguible

## Proyecto 3: Super Resolución de Imágenes de 7x7 a 28x28 en MNIST

- Archivo: `Proyecto7x7.ipynb`
- Descripción: En este proyecto se aborda la super resolución de imágenes de 7x7 a 28x28 píxeles en el conjunto de datos MNIST. Se evalúa el rendimiento del modelo y se proporcionan las siguientes métricas:
  - PSNR promedio: 57.71 dB
  - SSIM promedio: 0.6451
  - MAE promedio: 0.2794
  - Histogramas de densidades de la imagen original y la salida prácticamente iguales, aunque con bastante ruido en la salida
  - PCA con mucho ruido en el espacio latente pero distinguible

## Carpetas

- `modelos/`: Contiene los modelos entrenados para cada proyecto.
- `data/`: Contiene los datos del conjunto de datos MNIST.

Si deseas obtener más detalles sobre cada proyecto o explorar los resultados, simplemente accede a los archivos `Proyecto.ipynb`, `Proyecto14x14.ipynb` y `Proyecto7x7.ipynb`. Los modelos entrenados se encuentran en la carpeta `modelos`, y los datos originales se encuentran en la carpeta `data`.

## Créditos
- [Susana Suárez](https://github.com/susanasrez)
- [Mara Pareja](https://github.com/marapareja17)
