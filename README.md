## PROYECTO DE INVESTIGACION CAP.8
- DAVID LOPEZ
- MARIU CORREA
- DANNY JIMENEZ



---------------------------------------------
### OBJETIVOS 
	

Objetivos generales   	
- Describir las características de una fuente de corriente y de voltaje cd.	
- Aplicar cuatro diferentes teoremas para simplificar y transferir potencia a circuitos. 
- Realizar conversiones.

Objetivos específicos	
- Aplicar teorema de superposición de análisis de circuitos. 
- Aplicar los teoremas de Thevenin para simplificar circuitos.
- Aplicar el teorema de transferencia de potencia máxima.
- Realizar conversiones de fuente y de aY y Ya.
Marco teorico


La fuente de voltaje de cd

La fuente de voltaje de cd idealmente proporciona un voltaje constante a una carga, 
incluso cuando la resistencia de varia varía.
En realidad, ninguna fuente de voltaje es ideal; sin embargo, las fuentes de potencia
regulada se aproximan a la situación ideal cuando funcionan dentro de la corriente de 
salida especificada. Todas las fuentes de voltaje tienen algo de resistencia interna
inherente a consecuencia de su composición física o química, la cual puede ser 
representada mediante un resistor dispuesto en serie con una fuente ideal

![fuentes de voltaje](https://user-images.githubusercontent.com/76136485/103899061-d528d580-50c3-11eb-9785-5179a7856c81.jpeg)

La fuente de corriente

Fuentes de corriente directa. También son llamadas fuentes de alimentación,
son un dispositivo que convierte la tensión alterna de la red de suministro, en una o 
varias tensiones, prácticamente continuas, que alimentan los distintos circuitos del 
aparato electrónico al que se conecta (ordenador, televisor, impresora, router, 
etc.).
Las fuentes de alimentación, para dispositivos electrónicos, pueden clasificarse 
básicamente como fuentes de alimentaciones lineales y conmutadas. Las lineales
tienen un diseño relativamente simple, que puede llegar a ser más complejo cuanto 
mayor es la corriente que deben suministrar, sin embargo su regulación de tensión
 es poco eficiente. 
 


Conversiones de fuente

En el análisis de circuitos, en ocasiones es útil convertir una fuente de voltaje en una
fuente de corriente equivalente, o viceversa.
Los métodos de transformación de fuente se utilizan para la simplificación de 
circuitos para modificar los circuitos complejos mediante la transformación de 
fuentes de corriente independientes en fuentes de tensión independientes y 
viceversa. Para analizar los circuitos, podemos aplicar un voltaje simple y
técnicas de divisor de corriente utilizando estas transformaciones. Este método
de transformación de fuente también se puede usar para convertir un circuito del 
equivalente de Thevinin en el equivalente de Norton. 

![conversion de fuente de corriente](https://user-images.githubusercontent.com/76136485/103899072-d6f29900-50c3-11eb-92dd-1ef3f1db89c1.jpeg)


El teorema de superposición

El teorema de superposición establece que en un circuito lineal con varias 
fuentes, la corriente y el voltaje para cualquier elemento en el circuito es la 
suma de las corrientes y voltajes producidos por cada fuente que actúa de 
manera independiente.
Para calcular la contribución de cada fuente de forma independiente, todas 
las demás fuentes deben eliminarse y reemplazarse sin afectar el resultado 
final. Al eliminar una fuente de voltaje, su voltaje debe establecerse en cero,
lo que equivale a reemplazar la fuente de voltaje con un cortocircuito. Alabama
eliminar una fuente de corriente, su corriente debe establecerse en cero, lo 
que equivale a reemplazar la fuente de corriente con un circuito abierto.
Cuando suma las contribuciones de las fuentes, debe tener cuidado de 
tener en cuenta sus signos. 

 ![metodo de superposicion](https://user-images.githubusercontent.com/76136485/103899064-d5c16c00-50c3-11eb-85c9-b0dce5453414.jpeg)


Teorema de Thevenin

Teorema de Thévenin establece que si una parte de un circuito eléctrico lineal 
está comprendida entre dos terminales A y B, esta parte en cuestión puede 
sustituirse por un circuito equivalente que esté constituido únicamente por un 
generador de tensión en serie con una impedancia de forma que al conectar un 
elemento entre las dos terminales A y B, la tensión que cae en él y la intensidad 
que lo atraviesa son las mismas tanto en el circuito real como en el equivalente.

![trorema de thevenin](https://user-images.githubusercontent.com/76136485/103899068-d65a0280-50c3-11eb-9d49-aa77bfca3a05.jpeg)



Teorema de Norton

Al igual que el teorema de Thevenin, el teorema de Norton proporciona un método para reducir un 
circuito más complejo a una forma equivalente más simple. La diferencia básica es que el teorema de
Norton da por resultado una fuente de corriente equivalente en paralelo con una resistencia equivalente.
Al ser sustituida una fuente de corriente por una de tensión el terminal positivo de 
la fuente de corriente tiene que coincidir con el terminar positivo de la fuente de 
tensión en el momento de aplicar el teorema de Norton. En esencia el teorema de
Norton permitirá simplificar un circuito comprendido entre dos terminales 
planteando lo siguiente: Un circuito que tenga dos terminales, se comporta 
respecto de una resistencia de carga colocada entre ellos como un simple 
generador de intensidad Ix en paralelo con una resistencia Rx.

![torema de norton](https://user-images.githubusercontent.com/76136485/103899067-d65a0280-50c3-11eb-9dc9-b3e7fa42ff16.jpeg)



Teorema de transferencia de potencia Máxima

El teorema de transferencia de potencia máxima no es tanto un medio
de análisis como una ayuda para el diseño del sistema. En pocas
palabras, la cantidad máxima de energía se disipará por una resistencia
de carga cuando esa resistencia de carga sea igual a la resistencia de 
Thevenin / Norton de la red que suministra la energía. Si la resistencia
de carga es menor o mayor que la resistencia Thevenin / Norton de la 
red de origen, su potencia disipada será menor que la máxima.

![y dentro de delta](https://user-images.githubusercontent.com/76136485/103899070-d6f29900-50c3-11eb-98a8-9ff815036622.jpeg)

Conversiones delta a Y 

Con el propósito de poder simplificar el análisis de un circuito a veces es conveniente poder
 mostrar todo o una parte de un circuito de una manera diferente, pero sin que el
funcionamiento general de éste cambie. Algunos circuitos tienen un grupo de resistencias que
están ordenadas formando como un triángulo y otros como una estrella. Hay una manera
sencilla de convertir estas resistencias de un formato al otro y viceversa. No es solo asunto de
 cambiar la posición de las resistencias si no de obtener los nuevos valores que estas tendrán.


### Conclusiones

- Los teoremas de este capitulo 8 se centran en simplificar los circuitos ya su vez los procesos para poder resolverlos con mayor fácilidad
dandonos unas herramientas muy utiles para resolver circuitos complejos.

- El teorema de superposicion se centra en ayudarnos a resolver ejercicios con una o más fuentes de voltaje de una manera más fácil y eficiente.

- Con el teorema de Thevenin podemos resolver problemas en el queramos hallar la carga de una resistencia específica eliminandola del circuito
y resolviendola a travez de la vision de la resistencia a calcular.

- El teorema de Norton y el teorema de Thevenin son practicamente iguales la unica diferencia es que en el teorema de Norton se halla la corriente en vez del voltaje
pero aún así sus fórmulas están corelacionadas. 

### **Anexos**

[Link Video](https://www.youtube.com/watch?v=gM3nKqke5yE "Link Video")

### Bibliografía

Floyd, T. L. (2021). Principios De Circuitos Electricos C/Cd Rom (Circuitos ed., Vol. 8) [Libro electrónico]. PRENTICE HALL/PEARSON. http://media.espora.org/mgoblin_media/media_entries/1455/Principios_de_circuitos_electricos.pdf

