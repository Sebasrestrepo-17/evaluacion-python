Descripción

Este proyecto permite ingresar nombres de estudiantes junto con sus respectivas calificaciones, almacenar los datos en un diccionario y luego exportar los nombres cortos (con 4 o menos caracteres) a un archivo de Excel utilizando la librería openpyxl.

Requisitos

Para ejecutar este proyecto, necesitas tener instaladas las siguientes dependencias:

Python 3.x

La librería openpyxl

Puedes instalar openpyxl con el siguiente comando:

pip install openpyxl

Estructura del Código

El programa se divide en las siguientes partes:

Creación del Diccionario: Se solicita al usuario ingresar tres nombres de estudiantes junto con sus calificaciones y se almacenan en un diccionario.

Creación del Archivo Excel: Se genera un nuevo archivo de Excel usando openpyxl.

Escritura del Encabezado: Se escribe un encabezado en la celda A1 del archivo Excel.

Filtrado y Escritura de Datos: Se recorren los nombres del diccionario y aquellos con 4 o menos caracteres se escriben en la columna A del archivo Excel.

Guardado del Archivo: Se guarda el archivo como Ejercicio4.xlsx.

Notas

Este programa actualmente solo permite ingresar 3 estudiantes, pero puede modificarse fácilmente para aceptar más registros.

El archivo Ejercicio4.xlsx se sobrescribirá cada vez que se ejecute el programa.

Se recomienda abrir el archivo con Microsoft Excel, Google Sheets o cualquier visor compatible con archivos .xlsx.