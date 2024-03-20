# Especialización en Inteligencia Artificial

# Trabajo Práctico N° 2

# Visión por Computadora I
---

## Alumno: Jorge Ceferino Valdez


# Enunciado

- Implementar la función create_gauss_filter(h, w, k_size, sigma) para crear filtros gaussianos para filtrado espectral. Debe retornar un filtro gaussiano de tamaño HxW en dominio espacial y su transformada de Fourier.
    1. Graficar ambas representaciones para diferentes tamaños de kernel y sigma. Aplicar el filtro una imagen para validar el funcionamiento en el dominio espectral.
    2. Usando el método descripto en el paper “Image Sharpness Measure for Blurred Images in Frequency Domain” comparar el resultado de un filtrado por convolución con el filtrado espectral.
    3. Repetir la comparación usando uno de los métodos descriptos en el apéndice del paper “Analysis of focus measure operators in shape-from-focus”

# Instalación

Luego de clonar el repositorio ejecutar desde el directorio raiz:

1.- Crear un entorno virtual con venv.

2.- Active el entorno creado

3.- Proceda a instalar los paquetes necesarios para el proyecto.

    $ make install

4.- Desinstalación del ambiente venv

    $ make clean

