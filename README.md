# The Linkin´ Tool 📡📡📡
Accede a la web: icebreaker26.github.io/thelinkintool/
Es un software que aplica principios de ingeniería de radiopropagación, propios de la Ingeniería de Telecomunicaciones, para planificar enlaces punto a punto con precisión.

## ¿En que consiste? 🔻

Sección destinada para ingresar las coordenadas y características de los puntos A y B de los enlaces. Los parámetros a ajustar incluyen latitud, longitud, altura de la antena respecto al suelo, potencia de transmisión (Tx) en dBm, y ganancia de la antena Tx en dBi. A partir de estos datos, y considerando la ganancia de recepción (Rx) en dBi, es posible calcular la potencia recibida por la antena de Rx en dBm.

![image](https://github.com/user-attachments/assets/f818c37c-87bc-43c8-8cda-be3e1f6d6057)

En la sección central se añaden parámetros como la frecuencia, la zona de Fresnel a calcular (1, 2, 3, etc.), y las pérdidas adicionales que puedan presentarse en el sistema (como atenuaciones debido a las condiciones del sitio). Próximamente, estas pérdidas se podrán calcular de forma automatizada. Esta información permite determinar la distancia máxima entre ambas antenas, según los parámetros del horizonte de radio

![image](https://github.com/user-attachments/assets/d945b7cd-469f-4d8c-9f0f-a45a363cac70)

Estos botones nos permiten ejecutar diversas acciones, que se pueden dividir en las siguientes funciones: <br>

📌 Mostrar Mapa: Calcula los puntos intermedios entre ambas coordenadas y los grafica según la elevación del terreno. <br>
📌 Mostrar Línea de Vista: Traza una línea recta entre ambas antenas considerando la altura proporcionada, lo que permite evaluar visualmente si existen interferencias en el terreno.<br>
📌 Mostrar Zona de Fresnel: Calcula el radio de la zona de Fresnel para cada punto de la línea de vista, con el fin de determinar si el enlace operará en condiciones óptimas o si se presentarán atenuaciones debido a interferencias en el terreno.<br>
📌 Reset: Permite borrar los datos del gráfico.<br>
![image](https://github.com/user-attachments/assets/603b2b8a-6c23-482e-b455-a9a41a1253f7)

## 🗺📍 Grafico <br>

En este ejemplo podemos identificar tres series de datos:

🔹 Puntos de elevación del terreno entre las coordenadas A y B. <br>
🔹 Puntos de la línea de vista entre A y B. <br>
🔹 Una elipse que representa el radio de la zona de Fresnel para cada punto de la línea de vista (en el ejemplo se usa una frecuencia de 7 MHz). <br>

![image](https://github.com/user-attachments/assets/b5ae9d5b-8a43-4490-b873-422063726cff)

## 🎯🔰 Mapa <br>
Permite visualizar en el mapa la ubicación de ambas antenas (para lo cual es necesario proporcionar la latitud y longitud de cada una en el primer apartado), así como su línea de vista sobre el terreno.

![image](https://github.com/user-attachments/assets/e7550033-401a-4761-868d-62a3d910e3a1)

🛠🟡Coordenadas de ejemplo<br>
En esta tabla se referencian algunos puntos arbitrarios en la región de Risaralda y Caldas para la ubicación de antenas para testear enlaces entre ellos.
![image](https://github.com/user-attachments/assets/43139af3-7574-471b-8302-72e6f5ceaa08)

# 💻⚙📡 Detalles Tecnicos.<br>

Desarrollado con tecnologia de React JS - Create React App

![image](https://github.com/user-attachments/assets/782b6b1c-8aab-4526-83a9-33dfcb4608bc)

## 📚Librerias: 

🎴ChartJS para la elaboración de los graficos.

![image](https://github.com/user-attachments/assets/7058463e-fa92-4292-bdc9-e38ce8225c35)

🖼 Leaflet React para la elaboración de mapas.

![image](https://github.com/user-attachments/assets/e56d14b6-bfee-4e62-a472-58ca3f50e2d4)

# 📓📊Conceptos matemáticos y fisicos relevantes para la ingenieria de Telecomunicaciones e ingenieria de RadioPropagación: 

## 🏴‍☠️ Radio Zona de Fresnel:

![image](https://github.com/user-attachments/assets/67ec6f5b-c9ba-4a85-b16a-e5834818e8df)

### 🛠Para realizar calculos independientes recomiendo mi calculadora de fresnel: https://icebreaker26.github.io/zonafresnel/

## 🏴‍☠️Calculo del semiverseno (calcula la distancia entre dos coordenadas dado que la tierra es esferica):

![image](https://github.com/user-attachments/assets/9359928f-1802-41d7-b485-904ab30381af)

## 🏴‍☠️Pérdida de trayectoria en espacio libre (Lp):

![image](https://github.com/user-attachments/assets/1dc5e2a9-32d6-457d-a87b-d8ac773bfeb7)

## 🏴‍☠️Horizonte de radio (distancia maxima entre dos antenas):

![image](https://github.com/user-attachments/assets/05a5e2ae-2e1f-4593-829a-f4434b45ad9b)


Desarrollado por Alejandro Torres - Icebreaker26 septiembre 2024 - Universidad Católica de Pereira - Ingenieria de Sistemas y Telecomunicaciones







