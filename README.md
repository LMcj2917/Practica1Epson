# Practica1Epson
Conocer y describir el robot Epson
# Práctica 1

## Integrantes:
Luis Eduardo Mariscal Ceja
Dafne Stephany Garcia Garcia
Jarhim Salvador Pahua Leyva

## Introducción
La primera práctica del laboratorio de robótica consiste en la instalación del programa **Epson RC+** y la visualización de los primeros movimientos del robot a través de este software.

**Epson** es líder mundial en automatización industrial, ofreciendo una combinación de alto rendimiento y simplicidad. Sus robots industriales proporcionan sistemas de fabricación automatizada altamente productivos para una amplia gama de sectores industriales. [1]

## Instrucciones

### 1. Instalar el programa Epson RC+
- Descargar el archivo comprimido que contiene los instaladores del programa.
- Descomprimir la carpeta y ejecutar el archivo **.exe** como administrador.
- Seguir las instrucciones del proceso de instalación y ejecutar el programa.

Una vez instalado, se exploró el simulador proporcionado por el programa utilizando los siguientes atajos.

### 2. Conexión al Robot Epson C4
- Conectar la laptop al robot mediante un cable USB.
- Seleccionar en el programa el tipo de conexión **USB**.
- Ejecutar el **Robot Manager** y controlar el robot utilizando los joysticks.

### 3. Conocer las partes del robot
El robot **Epson C4** posee un diseño compacto de 6 ejes, ideal para trabajar en espacios reducidos. Está diseñado para manejar cargas de hasta 4 kg mientras mantiene rápidas velocidades y ciclos de trabajo. Algunas partes importantes del robot incluyen:

- **Base**: Proporciona soporte estructural y contiene la fuente de alimentación.
- **Articulaciones (J1-J6)**: Permiten el movimiento del brazo en múltiples direcciones.
- **Pinza**: La última articulación cuenta con una pinza impulsada por aire presurizado.
- **Cabina protectora**: Protege al robot de elementos externos como polvo y humedad.

El robot también incluye **sensores** de posición, velocidad y aceleración, entre otros.

### 4. Movimiento del robot en modos "World" y "Joint"
- **Modo World**: El movimiento del brazo se especifica en un sistema de coordenadas cartesiano, útil para movimientos lineales y precisos.
- **Modo Joint**: El control se realiza a nivel de cada articulación individual, proporcionando mayor flexibilidad para evitar colisiones en espacios complejos.

### 5. Análisis de las Diferencias
- **Modo World**: Ideal para movimientos lineales basados en coordenadas.
- **Modo Joint**: Ofrece mayor control de cada articulación, permitiendo movimientos más fluidos y adaptativos.
