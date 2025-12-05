# CINEPLUS-JAC
Aplicación básica de cobro para un cine creada con Python en wxglade. Cuenta con 4 ventanas: Inicio de sesión, Taquilla, Dulceria y Ticket
Creada por Alumnos de bachillerato
Descripción del Proyecto:
CinePlus es un sistema de interfaz para un cine que simula las operaciones principales de una sala de cine.
El proyecto incluye una interfaz interactiva donde los usuarios pueden iniciar sesión, vender boletos, comprar productos de la dulcería y finalizar la venta.
Es un proyecto escolar diseñado para demostrar diseño de interfaces gráficas, manejo de eventos y está hecho con Python y wxGlade.


Pantallas de la Aplicación

1. Pantalla de Inicio de Sesión 

Permitira que solo los usuarios autorizados accedan al sistema mediante una interfaz de inicio de sesión y contraseña

2. Taquilla

El usuario puede seleccionar películas, horarios y el número de boletos que necesite
El sistema calculara los precios individuales y el subtotal correspondiente.

3. Dulcería

Muestra los productos disponibles, como combos, palomitas y bebidas.
El usuario puede seleccionar artículos para agregarlos a la lista de compra y visualizar el subtotal.

4. Resumen de Compra

Presenta el resumen completo de la venta (boletos + dulcería).
Muestra los subtotales y el total final a pagar.


5-.Tecnologías Utilizadas
Python
wxGlade
wxPython
Visual Studio Code



6-.Integrantes del Equipo JAC

Nombre, Rol y Responsabilidades

Jatziri Rodríguez Alatorre
Project Owner: Coordinó el proyecto, supervisó el desarrollo y realizó la integración final.

Alexander Capistrán Velázquez
Diseñador: Creó los diseños, colores y estructura visual de la interfaz.

Cristal Sugey Alonso Castro
Analista: Analizó los requerimientos, flujos de trabajo y verificó las funcionalidades.


7-.Cómo Ejecutar el Proyecto

1. Requisitos

Python

wxPython

Visual Studio Code


2. Instalar Dependencias

Ejecuta el comando correspondiente en la terminal para instalar wxPython u otras bibliotecas necesarias.

3. Pasos para Ejecutar

1. Abre la carpeta del proyecto en Visual Studio Code.
1. Ubica el archivo principal, normalmente llamado: Cineplus.v1.py
2. Ábrelo y presiona Run.
3. El sistema iniciará y mostrará la pantalla de inicio de sesión.
4. Al ingresar usuario y contraseña correctos, se abrirá la ventana de Taquilla y si son incorrectos mandara mensaje de error


2. En la pantalla de taquilla
1-.Seleccionara, pelicula, boletos, horario y número de personas (adultos/niños).
2-.Ahí se mostrarán, la pelicula elegida, la cantidad de boletos y el subtotal
3-.Al hacer clic en Aceptar, mandara un mensaje de aceptar y se abrirá la siguiente pantalla.


3. En la pantalla de Dulcería
1-.El cliente podrá agregar combos, palomitas extras y refrescos.
3-.Nos dara un resumen de los productos seleccionados y su subtotal a pagar
4-. Al acepta continuar, se abrira la siguiente ventana.


4-. La pantalla de Ticket mostrará el resumen total:
1-.Información de taquilla
2-.Subtotal de boletos
3-.Subtotal de dulcería
4-.Total final a pagar
fin

Todas las ventanas fueron generadas con wxGlade e integradas en un archivo de Python.
