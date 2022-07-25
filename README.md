<!--
**povrgb/povrgb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# POV RGB 
# Varita de 8 LEDs RGB <3

Proyecto para realizar persistencia de la visión (POV) con una placa a medida con 8 LEDs RGB controlados con Arduino Nano.

##Funcionamiento

Una hilera de luces de LED se encienden y apagan a alta frecuencia en base a secuencias de bytes enviadas por un microcontrolador (Arduino) encargado de controlar dicha rutina. Al mover el dispositivo con rapidez o al ser capturado con una cámara, utilizando larga exposición, se pueden percibir imágenes y textos.

###Software

Controlamos los LEDs con un programa desarrollado en Arduino para mandar texto y dibujos pre-diseñados. Los colores RGB se controlan mediante transistores y toda la hilera usa el mismo color por cada momento.
Hay un programa desarrollado en Processing con la posibilidad de poder dibujar y crear nuevos diseños o incluso una nueva fuente tipográfica. Este programa requiere instalar la librería ControlP5.
V2 Las posibilidades de este software son para crear dibujos de dimensiones variables, el alto de los dibujos es de 8 pixeles condicionado por el hardware, pero con la posibilidad de ajustar el ancho de 7 a 36 columnas  (7 filas x X columnas). 
V1 Las posibilidades de este software son para crear dibujos del tamaño de los caracteres (7 filas x 8 columnas). 
Si necesitás ayuda para instalar estos programas podés ver el siguiente paso a paso: SUBIR E INSERTAR LINK!!


Hardware

Incorporamos el diseño de placa doble faz. Que utiliza un arduino Nano, 8 LEDs RGB ánodo común, 3 transistores NPN, 24 resistencias 220Ω, 3 resistencias 1KΩ, switch y un clip de batería.

![alt text](https://github.com/povrgb/Cosas/blob/main/img/placa_povrgb.JPG)

Beca FNA

El proyecto contó con la beca Formación del Fondo nacional de las artes para su desarrollo y el dictado de un taller gratuito en Mayo-Junio de 2022 donde cada participante soldó y aprendió a programar su propia placa.

![alt text](https://github.com/povrgb/Cosas/blob/main/img/flyerCuadrado.png)

Registro y pruebas del taller

![alt text](https://github.com/povrgb/Cosas/blob/main/img/pruebas0.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/taller0.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/taller1.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/taller2.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/taller3.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/taller4.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0011_marcia.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0022_lucy.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0023_cele.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0030_carlos.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0031_ushi.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0051_seba.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/IMG_2924_seba.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0072_leila.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0090_nicoFla.jpg)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/IMG_7731_ima.JPG)
![alt text](https://github.com/povrgb/Cosas/blob/main/img/DSC_0073_todos.jpg)

