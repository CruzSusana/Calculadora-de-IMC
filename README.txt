# Calculadora de IMC

Este proyecto es una calculadora de Índice de Masa Corporal (IMC) 
que permite a los usuarios ingresar sus datos personales para calcular y clasificar su IMC ajustado según el sexo y la edad. 
La aplicación también permite guardar los resultados en un archivo CSV.

## Requisitos

- Python 3.x
- Tkinter (incluido en la biblioteca estándar de Python)
- Archivo de imagen para el fondo: `FondoIMC0.png`
- Archivo de imagen para el botón de calcular: `Calcular.png`
- Archivo de imagen para el botón de guardar: `Guardar.png`

## Estructura del Proyecto

El proyecto consta de los siguientes archivos:
- `calculadoraIMC.py`: Contiene el código fuente principal de la aplicación.
- `FondoIMC0.png`: Imagen de fondo para la interfaz gráfica.
- `Calcular.png`: Imagen para el botón de calcular IMC.
- `Guardar.png`: Imagen para el botón de guardar datos.

## Instrucciones de Uso

1. Asegúrate de tener Python 3.x instalado en tu sistema.
2. Guarda todas las imágenes requeridas (`FondoIMC0.png`, `Calcular.png`, `Guardar.png`) en el mismo directorio que el archivo `main.py`.
3. Ejecuta el archivo `calculadoraIMC.py` con Python.
4. La interfaz gráfica se abrirá con los siguientes campos y botones:
- Nombre
- Peso (kg)
- Altura (m)
- Edad
- Sexo (Masculino o Femenino)
- Botón "Calcular" para calcular el IMC ajustado.
- Botón "Guardar" para guardar los datos en un archivo CSV.

## Funcionalidades

### Calcular IMC

- Ingrese los datos requeridos en los campos de texto.
- Haga clic en el botón "Calcular" para calcular su IMC ajustado.
- El resultado del IMC ajustado se mostrará en la etiqueta de resultado.

### Guardar Datos

- Ingrese un nombre en el campo de texto "Nombre".
- Asegúrese de haber ingresado todos los demás datos correctamente.
- Haga clic en el botón "Guardar" para guardar los datos en un archivo CSV con el nombre ingresado.

## Manejo de Errores

- Si algún campo de entrada contiene valores no válidos, se mostrará un mensaje de error.
- Si el campo "Nombre" está vacío cuando se intenta guardar los datos, se mostrará un mensaje de error indicando que no hay datos para guardar.

## Nota

- Asegúrese de que los archivos de imagen estén en la ruta correcta para que la interfaz gráfica se cargue correctamente.

