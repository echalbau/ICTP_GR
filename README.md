# ICTP_GR

Repositorio con los cuadernos de Mathematica a ser utilizados en las clases del curso de relatividad general ICTP PWF 2023. 
Este repositorio contiene algunos tutoriales disponibles en http://www.xact.es para manipulacion de indices en tensores y
densidades tensoriales.

Requisitos:
Mathematica 9 o superior.
xAct: Paquete base para manipulacion tensorial.
xTensor: Paquete para manipulacion algebraica de tensores y sus propiedades.
xCoba: Paquete para manipulacion de componentes de tensores.
xPert: Paquete para perturbaciones a varios ordenes. 


# Pasos para instalar xAct dentro de Mathematica

1) Descargar el archivo xAct_1.2.0.tgz (Mac/Linux) o xAct_1.2.0.zip (Windows) en http://www.xact.es/download.html

2) Extraer el contenido en la terminal (Se puede hacer manualmente en la interfaz gráfica del sistema operativo):

tar -xvf xAct_1.2.0.tgz (Mac/Linux)

unzip xAct_1.2.0.zip

3) Copiar la carpeta xAct en los siguientes lugares dependiendo del sistema operativo usado

# Linux

en modo sudo (Terminal escribir sudo su y colocar la clave del usuario root), copiar la carpeta en esta direccion dentro de Mathematica:

/usr/share/Mathematica/Applications/

# Mac

Copiar la carpeta (en modo root) en:

/Library/Mathematica/Applications/

# Windows

En windows:

C:\Program Files\Wolfram Research\Mathematica\<version>\AddOns\Applications\

Nota: Puedes localizar la instalacion de Mathematica dentro de tu computadora escribiendo en un cuaderno:

$Path 
Haciendo shift + Enter en el teclado, el cuaderno te mostrara la path absoluta de instalacion de Mathematica.






