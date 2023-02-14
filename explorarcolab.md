# Primeros pasos en Google Colab

## Crear un nuevo notebook:

En Google Drive, haz clic en el botón "Nuevo" y selecciona "Más" -> "Google Colaboratory".
Se abrirá un nuevo notebook en tu navegador.

## Ejecutar una celda de código:

Haz clic en una celda de código.
Presiona Shift + Enter para ejecutar la celda.

## Crear una nueva celda:

Haz clic en el botón "+ Código" en la barra de herramientas superior.

## Cambiar el tipo de celda:

Haz clic en la celda que quieres cambiar.
En la barra de herramientas superior, selecciona "Código" o "Texto" para cambiar el tipo de celda.

## Guardar el notebook:
En el menú "Archivo", selecciona "Guardar" o presiona Ctrl/Cmd + S.

## Conectar Google Colab a Google Drive:
Ejecuta la siguiente celda de código
Conectar Google Colab a Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```
Sigue las instrucciones para autorizar la conexión con tu cuenta de Google Drive.

##Importar una librería de Python:

En una celda de código, escribe import seguido del nombre de la librería. Por ejemplo, import pandas para importar la librería Pandas.

## Subir un archivo a Google Colab:
Haz clic en el botón "Archivos" en la barra de herramientas lateral.
Selecciona "Cargar" y selecciona el archivo que quieres subir.

## Descargar un archivo desde Google Colab:
Ejecuta la siguiente celda de código:
```python
from google.colab import files
files.download('/path/to/file')
```
Reemplaza '/path/to/file' con la ruta y el nombre de archivo que quieres descargar.
