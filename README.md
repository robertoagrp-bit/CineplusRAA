# CineplusRAA
Aplicacion Bàsica de cobro para un cine creada en python con wxglade.consta con 4 ventanas de inicio de sesiòn
CinePlus
Aplicación básica de cobro para un cine creada en Python utilizando wxGlade. Consta de un sistema dividido en 4 ventanas que representan el flujo completo desde el inicio de sesión, la selección de boletos, la compra en dulcería y la venta final del ticket. Este proyecto fue desarrollado como práctica para comprender la creación de interfaces gráficas, manejo de eventos y lógica de control dentro de una aplicación estructurada por ventanas.

Ventana de Inicio de Sesión
Esta ventana permite al usuario acceder al sistema mediante un formulario con usuario y contraseña.
El sistema valida la información ingresada.
Solo permite avanzar si los datos son correctos.
El objetivo principal es simular un acceso básico antes de entrar al módulo principal.

Ventana de Venta de Boletos
En esta ventana el usuario puede seleccionar la película, el horario y la sala.
Incluye una lista de películas disponibles.
Se muestran horarios correspondientes a cada función.
El usuario selecciona la cantidad de boletos que desea comprar.
Se calcula el subtotal según la cantidad seleccionada.

Ventana de Dulcería
Esta ventana permite agregar productos adicionales como parte de la compra.
Incluye opciones como palomitas, refrescos, combos y dulces.
Cada producto suma un costo adicional al subtotal.
El usuario puede seleccionar uno o varios productos.
El sistema registra los productos elegidos y su precio correspondiente.

Ventana de Venta Final
Esta ventana reúne todos los datos generados en las ventanas anteriores.
Resume el costo de los boletos.
Muestra el total de productos adquiridos en la dulcería.
Calcula el total general de la compra.
Presenta toda la información de forma ordenada para completar la venta.

Tecnologías Utilizadas
Python
wxGlade
Interfaces gráficas (GUI)
Programación estructurada basada en ventanas

Descripción General
Este sistema simula el proceso básico de compra dentro de un cine, desde el inicio de sesión del usuario hasta la generación de un resumen final del ticket. Permite comprender la comunicación entre ventanas, el uso de controles gráficos, el manejo de datos, así como la integración de distintas funcionalidades dentro de una misma aplicación. El proyecto sirve como base para desarrollar aplicaciones más complejas que integren bases de datos, validaciones avanzadas y registros de compras.
