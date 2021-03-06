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
**Diagrama del circuito usando capacitores**

![](https://github.com/erickfi/Practica-9/blob/master/Img/diagrama%20capacitor.PNG)

**Diagrama del circuito usando inductores**

![](https://github.com/erickfi/Practica-9/blob/master/Img/diagrama%20inductor.PNG)

**Simulación del circuito con capacitores**

![](https://github.com/erickfi/Practica-9/blob/master/Img/simulaci%C3%B3n%20capacitor.jpeg)

**Simulación del circuito con inductores**

![](https://github.com/erickfi/Practica-9/blob/master/Img/simulaci%C3%B3n%20inductor.jpeg)

### 5. LISTA DE COMPONENTES

| Materiales               | Cantidad   |
| -----------------------  |----------- |
| Generador de señales     |    1       |
| Fuente DC                |    1       |
| Osciloscopio             |    1       |
| Protoboard               |    1       |
| Multímetro               |    1       |
| Resistencias de 100 Ω    |    1       |
| Capacitor 10 uF          |    2       |
| Bobina o inductor 100 mH |    2       |

### 6. TABLA DE RESULTADOS

***Tabla 1. Resultados para el circuito usando capacitores***

![](https://github.com/erickfi/Practica-9/blob/master/Img/TablaCapacitancia.png)

***Tabla 2. Resultados para el circuito usando inductores***

![](https://github.com/erickfi/Practica-9/blob/master/Img/TablaInductancia.png)

### 7. Explicación de Código Fuente

- 1. Armar el circuito tal como se muestra en el diagrama.
- 2. Utilice el osciloscopio para observar el voltaje 𝑉𝑜 variando la frecuencia entre los
valores de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los valores pico de las ondas observadas.
- 3. Utilice un multímetro para medir el voltaje 𝑉𝑜 variando la frecuencia entre los valores
de 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.
- 4. Utilice un multímetro para medir la corriente que atraviesa la resistencia variando la
frecuencia entre los valores 0, 10, 50, 100, 500, 1000 𝐻𝑧. Anote los resultados.

### 8. PREGUNTAS
- 1. Justifique los errores cometidos en las mediciones.

> Los errores en la práctica se deben a que se realiza una comparación de los valores del voltaje obtenidos con el osciloscopio y el multímetro, por un lado el multímetro del simulador solo tiene la capacidad de presentar 3 dígitos de valor por lo que en caso de tener más decimales los redondea a 3 cifras, por otra parte se puede deber a un error en la lectura del osciloscopio, ya que para hallar el valor se da  _valor de voltaje_ a cada cuadro de la pantalla de osciloscopio 
        
- 2. ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

> Una bobina ideal en corriente continua se comporta como un cortocircuito, es decir sería un conductor ideal, ya que al ser la corriente constante, no hay autoinducción de ninguna FEM, Fuerza electromotriz, por otro lado, un capacitor en corriente continua se comporta como un circuito abierto ya que no hay una variación en el flujo de corriente para generar un campo eléctrico capaz de permitir la interacción entre las placas.

- 3. ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

> En un bobina el capacitor ya no se comporta como un circuito abierto, ya que hay una variación en el flujo de la corriente, entonces se genera un campo eléctrico que permite que la corriente fluya, sin embargo, presenta una oposición al avance del voltaje, por lo que el valor que presenta un osciloscopio está desfasado 90° respecto a la corriente, por otro lado, la bobina como la resistencia se opone al flujo de la corriente, pero a diferencia de esta, el valor de esta oposición se llama reactancia inductiva, por lo tanto se dice que el voltaje está adelantado.


- 4. ¿Qué cree usted que ocurriría con el voltaje 𝑉𝑜 y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

> Los valores van a variar, en el caso de los capacitores el voltaje será inversamente proporcional, mientras que para la corriente será directamente proporcional, al cambio en el valor de la capacitancia.

> Para los inductores, tanto el voltaje como la corriente serán directamente proporcional al cambio de de la inductancia.

> No obstante hay que tener en cuenta que al hablar de elementos conectados en paralelo debemos sumár los valores, sin embargo, ya que sus valores individuales disminuyen, la suma de sus valores también lo hará
        
- 5. ¿Qué son los valores eficaces de voltaje y corriente?

> Son los valores que usan los equipos conectados, los cuáles se miden directamente con un multímetro, en caso de obtenerlos con un osciloscopio estos tendrán un factor de conversión igual a la raiz cuadrada de dos.

### 8. CONCLUSIONES

- En el circuito donde se implementó los capacitores en paralelo, si la frecuencia tiende a 0 entrega valores de voltaje máximo, pero valores de corriente mínimos. Por otra parte, si implementamos las bobinas en paralelo ocurre todo lo contrario, entre más baja la frecuencia, los valores que se miden en el osciloscopio y multímetro son los valores mínimos en el caso del voltaje, y para la corriente se mide un valor máximo.

- La reactancia se puede obtener gracias al voltaje que se disipa en los capacitores o inductores y la corriente que pasa por estos, no importa si estos son los valores  eficaces o pico, ya que se tiene la misma proporcion entre estos.

- El valor eficaz  el cual es el medido por los multímetros  son los que permiten conocer cuanta energía circula por este.
### 9. RECOMENDACIONES

- Usar un software capaz de simular bobinas y capacitores, corriente alterna y simular un osciloscopio, para esta práctica se usó Proteus.

### 10. CRONOGRAMA

![](https://github.com/erickfi/Practica-9/blob/master/Img/Crongrama.PNG)

### 11. REFERENCIAS
- [1] M. A. Sadiku.Fundamentos de circuitos eléctricos. Mc Graw Hill, third edition, 2006
### 12. ANEXOS
- [Cálculos análiticos](https://github.com/erickfi/Practica-9/blob/master/Anexos/C%C3%A1lculos%20Anal%C3%ADticos.pdf)
- [Cómo funciona el circuito](https://youtu.be/FitkQEedJ9s)
- [Cómo se implementó el circuito](https://youtu.be/dFJMlqRMNd4)
