## UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE
![](https://github.com/erickfi/Practica-5/blob/master/Img/Escudo.jpg)
### Práctica de laboratorio N° 9
## Inductor y capacitor
**Autores:** Figueroa Erick, León Jipshon,Viracucha William.
### 1. PLANTEAMIENTO DEL PROBLEMA

El estudio de circuito eléctricos hasta el momento se ha limitado a ciruitos resistivos, es decir, ciruitos donde la energía es discipada, no obstante, a veces se requiere almacenar esta energía para usarla como una señal de activación en circuitos más complejos, es por ello que se los puede atribuir como almacenadores de energía temporales, sin embargo, aunque ambos realicen la misma actividad, la forma en que esto ocurre es lo que los diferencia.

Los capacitores e inductores al igual que los resistores presentan oposición al flujo de corriente, sin embargo, su estructura les permite mantenerse cargados incluso cuando el circuito sea desconectado de la fuente, esto debido a la generación de un campo.

### 2. OBJETIVOS

- Verificar el comportamiento de la bobina y el capacitor en circuitos DC.
- Verificar el comportamiento de la bobina y el capacitor en circuitos AC.
- Verificar las combinaciones serie y paralelo de bobinas y capacitores.
- Familiarizarse con el uso de instrumentos de medida.

### 3. MARCO TEÓRICO

Aunque capacitancia e inductancia son elementos pasivos tienen la propiedad de almacenar energía, y por tanto se dice que pueden tener condiciones iniciales para las variables de voltaje y corriente, esto en función de la energía que tengan almacenada. La capacitancia almacena la energía en un campo eléctrico mientras que la inductancia almacena la energía en un campo magnético.

#### CAPACITORES

![](https://github.com/erickfi/Practica-9/blob/master/Img/capacitores.PNG)

Un capacitor o también conocido como condensador es un dispositivo capaz de almacenar  energía a través de campos eléctricos (uno positivo y uno negativo). Este se clasifica dentro de los componentes pasivos ya que no tiene la capacidad de amplificar o cortar el flujo eléctrico.

Según Sadiku(2006):
> Un capacitor es un elemento pasivo diseñado para almacenar energía en su campo eléctrico. En muchas aplicaciones prácticas, las placas pueden ser de láminas de aluminio,
mientras que el dieléctrico puede ser de aire, cerámica, papel o mica.

Por lo tanto podemos decir que, son elementos que retrasan el flujo de voltaje con respecto a la corriente, dentro de los circuitos eléctricos son el segundo elementos más usado luego de los resistores.

![](https://github.com/erickfi/Practica-9/blob/master/Img/estructura%20capacitor.PNG)

Cuando una fuente de tensión _V_ se conecta al capacitor, deposita una carga positiva _q_ en una placa y una carga negativa _-q_ en la otra. Se dice que el capacitor almacena la carga eléctrica. El monto de carga almacenada, representado por _q_, es directamente proporcional a la tensión aplicada _V._

        q = C V

Donde C, la constante de proporcionalidad, se conoce como la capacitancia del capacitor. La unidad de capacitancia es el farad (F), así llamado en honor al físico inglés Michael Faraday (1791-1867).

Hay que recordar dos aspectos importantes al momento de analizar el capacitor.
- Un capacitor representa un circuito abierto en DC.
- En un capacitor la tensión no puede cambiar abrutamente ya que para que esto requiere una corriente infinita lo que es físicamente imposible.

En un circuito el capacitor se representa con dos lineas de igual longitud en paralelo, si este tiene una flecha que lo atraviesa se dice que es un capacitor variable.

![](https://github.com/erickfi/Practica-9/blob/master/Img/simbolo%20capacitor.PNG)

#### Inductores

![](https://github.com/erickfi/Practica-9/blob/master/Img/inductores.PNG)

También llamados bobinas, la Inductancia es un elemento pasivo de dos terminales que almacena energía en un campo magnético. De acuerdo a la ley de Faraday la variación de corriente en el tiempo en un conductor induce una caída de voltaje en el mismo. De acuerdo a las ecuaciones de Maxwell una variación de la corriente en el conductor produce
un campo magnético variable, que a su vez produce un campo eléctrico variable y por tanto se genera una caída de voltaje variable en el tiempo. 

![](https://github.com/erickfi/Practica-9/blob/master/Img/estructura%20inductor.PNG)

Un inductor es un elemento pasivo diseñado para almacenar energía en su campo magnético. Básicamente, todo inductor consiste en un arrollamiento de hilo conductor.  La inductancia resultante es directamente proporcional al número y diámetro de las espiras y a la permeabilidad del interior del arrollamiento, y es inversamente proporcional a la longitud de la bobina, por lo que, todos los conductores de corriente eléctrica tienen propiedades inductivas y pueden considerarse inductores. Pero para aumentar el efecto inductivo, un inductor práctico suele formarse en una bobina cilíndrica con muchas vueltas de alambre conductor.

Sadiku (2006) describe a un inductor como:

> Un inductor consta de una bobina de alambre conductor.

Si se permite que pase corriente por un inductor, se descubre que la tensión en el inductor es directamente proporcional a la velocidad de cambio de la transformación de la corriente.

        V=L di/dt
        
donde L es la constante de proporcionalidad, llamada inductancia del inductor.

La inductancia es la propiedad por la cual un inductor presenta oposición al cambio de la corriente que fluye por él, medida en henrys (H), la unidad de inductancia es el henry (H), así llamado en honor al inventor estadounidense Joseph Henry (1797-1878). La inductancia de un inductor depende de sus dimensiones y composición física. Las fórmulas para calcular la inductancia de inductores de diferentes formas se derivan de la teoría electromagnética y pueden encontrarse en [manuales estándar de ingeniería eléctrica.](https://www.casadellibro.com/libro-manual-de-ingenieria-electrica-2-tomos/9789701008713/509358)

Hay otras consideraciones a tomar en cuenta en los inductores.
- inductores es que se oponen a los cambios bruscos de la corriente que circula por ellas. Esto significa que a la hora de modificar la corriente que circula por ellos esta intentará mantener su condición anterior.
- Cuando este componente es conectado a una fuente de corriente alterna y causa un desfase entre el voltaje que se le aplica y la corriente que circula por ella.
- La bobina o inductor es un elemento que reacciona contra los cambios
en la corriente a través de él, generando un voltaje que se opone al voltaje aplicado y es proporcional al cambio de la corriente.

En un diagrama de un circuito un inductor se puede representar de las siguientes formas.

![](https://github.com/erickfi/Practica-9/blob/master/Img/simbolo%20inductor.PNG)


        Los inductores y capacitores dentro de un análisis de circuitos generalmente se los encuentra en corriente alterna AC,
        dentro de la cuál se trabaja con números complejos, y forman parte de la resistencia de un circuito, estos pueden ser 
        usados para modificar las condiciones de un circuito, cambiar el factor de corriente, y aumentar o disminuir el voltaje
        y/o corriente, puesto que se los considera resistencias, están sujetos a las mismas reglas, se pueden encontrar en serie,
        en paralelo y más de uno en un circuito, sin embargo, la operacionalización de los mismos varía.

### 4. DIAGRAMAS
**Diagrama del circuito**

![](https://github.com/erickfi/Laboratorio-6/blob/master/Img/Diagrama.PNG)

**Medición de valores**

![](https://github.com/erickfi/Laboratorio-6/blob/master/Img/Thinker%206.1.PNG)
![](https://github.com/erickfi/Laboratorio-6/blob/master/Img/Thinker%206.2.PNG)
![](https://github.com/erickfi/Laboratorio-6/blob/master/Img/Thinker%206.3.PNG)

### 5. LISTA DE COMPONENTES

![](https://github.com/erickfi/Laboratorio-6/blob/master/Img/Materiales.PNG)

### 6. TABLA DE RESULTADOS

***Tabla 1. Parámetros eléctricos del circuito***

|   RL (Ω)  | Corriente  |   Voltaje  | Potencia calculada | Potencia calculada | Error |
|:---------:|:----------:|:----------:|:------------------:|:------------------:|:-----:| 
|           |  Medida    |   medido   | Experimentalmente  | teóricamente       |       |
|           |   (mA)     |    (V)     |       (mW)         |        (mW)        |  (%)  |
|   220     |   10.6     |   2.32     | 24.592             | 24.548             | 0.18  |
|   470     |   8.98     |   4.22     | 37.895             | 37.918             | 0.06  |
|   680     |   7.98     |   5.43     | 43.311             | 43.288             | 0.1   |
|   820     |   7.43     |   6.09     | 45.248             | 45.216             | 0.07  |
|   1000    |   6.82     |   6.82     | 46.512             | 46.487             | 0.05  |
|   1500    |   5.56     |   8.33     | 46.314             | 46.296             | 0.04  |
|   1800    |   5        |   9        | 45                 | 45                 | 0     |
|   2200    |   4.41     |   9.71     | 42.821             | 42.82              | 0.002 |
|   3900    |   2.94     |   11.5     | 33.81              | 33.737             | 0.216 |
|   4700    |   2.54     |   11.9     | 30.226             | 30.379             | 0.5   |



### 7. Explicación de Código Fuente

- 1. Armar el circuito tal como se muestra en el diagrama.
- 2. Medir la corriente y voltaje de la resistencia de carga para cada valor que adquiere esta resistencia mediante un multímetro, específicamente se debe realizar las mediciones para 220 Ω, 470 Ω, 680 Ω, 820 Ω, 1000 Ω, 1500 Ω, 1800 Ω, 2200 Ω, 3900 Ω, 4700 Ω. En total son 10 mediciones de voltaje y 10 mediciones de corriente.

### 8. CONCLUSIONES

- Una fuente de voltaje entrega la máxima transferencia de potencia cuando necesariamente su resistencia interna es igual a la resistencia de la carga, en este caso la resistencia de Thévenin debe ser obligadamente el mismo valor de la resistencia de la carga.
- Las resistencias mas próximas a 1200 Ohmios como la de 1000 y 1500, entregan una potencia casi próxima a la potencia máxima, entonces podemos decir que entre mas cercano sea el valor de la resistencia interna, al valor de la resistencia de carga, la potencia tiende a su valor máximo, pero no la van a superar.
- Para que la potencia sea máxima P= 46.875 mW, la resistencia de la carga RL debe ser igual a la de la fuente RTh, por lo tanto, RL= RTh= 1200 Ω.
- Se cumple el Teorema de la Máxima Transferencia de Potencia, al observar que la potencia suministrada por todas las resistencias utilizadas es menor a la cálculada si RL=1200 Ω.
- Dentro de las resistencias utilizadas se obtiene que la resistencia de 1000 Ω, es la que más se aproxima al valor de la potencia máxima, la cuál entrega una potencia de 46.487 mW.

### 9. RECOMENDACIONES

- Una forma de comprobar el teorema de máxima transferencia de potencia es dar valores a la resistencia de carga muy cercanos a la resistencia interna, y observar que la potencia va a estar al limite de la potencia máxima

### 10. CRONOGRAMA

![](https://github.com/erickfi/Laboratorio-6/blob/master/Img/Cronograma%206.PNG)

### 11. REFERENCIAS
- [1] M. A. Sadiku.Fundamentos de circuitos eléctricos. Mc Graw Hill, third edition, 2006
### 12. ANEXOS
- [Cálculos análiticos](https://github.com/erickfi/Laboratorio-6/blob/master/Anexos/Anexos%20lab%206.pdf)
- [Cómo funciona el circuito](https://www.youtube.com/watch?v=pdyatt-rUAg&feature=youtu.be)
- [Cómo se implementó el circuito](https://www.youtube.com/watch?v=wW0A3P_5MHM&feature=youtu.be)
