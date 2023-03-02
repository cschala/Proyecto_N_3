# Informe de Proyecto N°3

Titulo: Interruptor controlado por luz (LDR y 741)

Nombres:

-Christian Chala  

-Steveen Vallejo

-Ismael Paez

Fecha: 01/03/2023

NRC: 10067

Carrera: Mecatronica

OBJETIVO GENERAL:

Analizar el video propuesto del funcionamiento del circuito y utilizar ingenieria inversa para comprender su funcionamineto asi como que funcion realiza cada componente del mismo.

OBJETIVOS ESPECIFICOS:

-Replicar el circuito del video para verificar su funcionamiento con nuestros propios elementos. 

-Investigar los nuevo componentes utilizados en el video que no se han visto en clase.

-Implementar la materia estudiada para hacer el circuito con componentes que se utilizarian en una estructura real y ya no a pequela escala como lo es en el protoboard.

# 2.	MARCO TEÓRICO (RESUMEN)

![MATERIALES](https://user-images.githubusercontent.com/117959424/222326419-6f5f8e5f-9636-42c4-95d5-cc1a20f25b99.png)

# 3.	EXPLICACIÓN DEL PROCEDIMIENTO

1. Debido a que no es un circuito muy complejo no vamos a realizar un diagrama esquematico y pasaremos directo al ensamblaje en la placa de pruebas (protoboard). Vamos a partir con los materiales que no son muy complicados de conseguir y empezaremos con el ensamble. El relee que utilizaremos es uno capaz de soportar las subidas de voltaje de 120V que es lo que conocemos como corriente alterna y el potenciometro nos servira para poder "sensibilizar" aun mas la fotoresistencia que en palabras simples nos sirve para que con mas o menos ausencia de luz el fotoresistor detecte que no hay luz.

![WhatsApp Image 2023-03-01 at 9 00 20 PM](https://user-images.githubusercontent.com/117959424/222327368-ce11b9fb-9c87-4f65-9044-7f843702705f.jpg)

2. Una vez explicado cada material, procedemos a ensamblar, primero es hacer un puente entre las entradas de voltaje superiores e inferiones para la fuente de 120V. El fotorresitor se conecta una punta a la entrada negativa del protoboard y el otro extremo a se conecta en serie con el circuito integrado, luego el potenciometro tiene 3 pines, el pin numero uno se conecta a la entrada negativa del protoboard el del medio al circuito integrado y el tercer pin a la entrada positiva del protoboard.

![image](https://user-images.githubusercontent.com/117959424/222328420-b766e0cf-d90a-4b57-a11d-988a402de703.png)

3. A continuacion conectamos una resistencia al circuito integrado y esta sera conectada al primer pin del transistor, tambien debemos hacer un puente de uno de los pines del circuito integrado con la entrada positiva del protoboard para abastecer de energia al circuito integrado.

![image](https://user-images.githubusercontent.com/117959424/222328672-76d527fb-41c2-4c2f-bbaa-b4067a0f881e.png)

4. El pin de la mitad del transistor ira conectado al relee ya que el transistor se encarga de regular las amplitud de la onda, debido a que la corriente alterna tiene caidas y bajadas, el transistor se encarga de regular estas ondas; el ultimo pin del transistor ira conectado a la entrada negativa del protoboard para cerrar el circuito.

![image](https://user-images.githubusercontent.com/117959424/222328955-2471dd4e-23b0-486e-85b1-e519b029fad8.png)

5. Para finalizar haremos un puente entre la entrada libre del relee con la entrada positiva del protoboard y a su vez esto creara una conexion entre el relee y el circuito integrado.

![image](https://user-images.githubusercontent.com/117959424/222329091-965997c7-b071-4930-87a4-c193c8192fdd.png)

6. Conectaremos una fuente de voltaje de 5V, en este caso usaremos un arduino como fuente de 5V a una de las otras entradas del relee para abastecer de energia al circuito, y luego conectaremos la fuente de 120V teniendo en cuenta que tenga un terminal comun para el foco.

![WhatsApp Image 2023-03-01 at 8 37 56 PM (1)](https://user-images.githubusercontent.com/117959424/222329451-12ee9664-f8c2-4be2-8217-81d653d4514d.jpeg)

# 4.	RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

NO APLICA.

# 5.	VIDEO

https://youtu.be/SYOA_5A5ssk

# 6.	CONCLUSIONES

-) Este proyecto es del tipo que se pueden aplicar a un escenario real ya que es el principio basico del alumbrado publico como lo son los postes de luz.

-) Con este tipo de instalaciones ya hay que tener un poco de precaucion debido a que se trabaja con dos fuentes siendo una de ellas de 120V que podria ser un poco peligroso.

-) Para mayor versatilidad se puede utilizar una fuente casera de 5V si no se dispone de un arduino, y utilizar cables que no sean jumpers.

# 7.	BIBLIOGRAFIA

-)Wikipedia contributors. (s/f-a). Circuito integrado. Wikipedia, The Free Encyclopedia. https://es.wikipedia.org/w/index.php?title=Circuito_integrado&oldid=148713743


-)Wikipedia contributors. (s/f-b). Fotorresistor. Wikipedia, The Free Encyclopedia. https://es.wikipedia.org/w/index.php?title=Fotorresistor&oldid=147895111


-)(S/f-a). Farnell.com. Recuperado el 2 de marzo de 2023, de https://es.farnell.com/multicomp/tip120/trans-darlington-npn-60v-5a-to/dp/9294210#:~:text=El%20TIP120%20de%20Multicomp%20es,y%20conmutación%20de%20baja%20velocidad.

-)(S/f-b). Wikipedia.org. Recuperado el 2 de marzo de 2023, de https://es.wikipedia.org/wiki/Amplitud_(física)

-)(S/f-c). Wikipedia.org. Recuperado el 2 de marzo de 2023, de https://es.wikipedia.org/wiki/Relé

-)(S/f-d). Wikipedia.org. Recuperado el 2 de marzo de 2023, de https://es.wikipedia.org/wiki/Potenciómetro

# 8. RUBRICA

![image](https://user-images.githubusercontent.com/116814096/200999683-fe53d616-5553-4761-bdf4-e15a280451cb.png)









