# APUNTES TERCER CORTE
# FUNCIÓN DE TRANSFERENCIA
💡 EJEMPLO
•Hallar y(t) para la siguiente ecuación diferencial:

$$y''(t)+3y'(t)+2y(t)=3u'(t)+3u(t)$$

•Aplicando transformadade LaPlace:

$$s^2Y(s)-y(0)-y'(0)+3(sY(s)-y(0))+2Y(s)=3(sU(s)-u(0))+3U(s)$$

•Se despejala variable que se quiere hallar:

$$s^2Y(s)+3sY(s)+2Y(s)-y(0)-y'(0)-3y(0)=U(s)(3s+3)-3u(0)$$

$$Y(s)(s^2+3s+2)=U(s)(3s+3)-3u(0)+y(0)+y'(0)-3y(0)$$

$$Y(s)=\frac{U(s)(3S+3)-3u(0)+y(0)+y'(0)+3y(0)}{s^2+3s+2}$$

•Al final se aplica transformada inversade LaPlacepara volver al dominio del tiempo

## Funciónde transferencia
• En el área de control se usaotrotipode representación matemática denominada función de transferencia
• Consiste en la transformada de Laplace de la ecuación diferencial

𝑆𝑒 𝑑𝑒𝑠𝑝𝑒𝑗𝑎, $\frac{𝑠𝑎𝑙𝑖𝑑𝑎}{𝐸𝑛𝑡𝑟𝑎𝑑𝑎}$, 𝑒𝑠 𝑑𝑒𝑐𝑖𝑟: $\frac{𝑌(𝑠)}{𝑈(𝑠)}$

𝑇𝑜𝑑𝑎𝑠 𝑙𝑎𝑠 𝑐𝑜𝑛𝑑𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑖𝑛𝑖𝑐𝑎𝑙𝑒𝑠 𝑑𝑒 𝑙𝑎 𝑒𝑐𝑢𝑎𝑐𝑖ó𝑛 𝑑𝑖𝑓𝑒𝑟𝑒𝑛𝑐𝑖𝑎𝑙 𝑠𝑜𝑛 𝑖𝑔𝑢𝑎𝑙𝑒𝑠 𝑎 0.

>𝑂𝐽𝑂: 𝐸𝑠𝑡𝑜 𝑠ó𝑙𝑜 𝑎𝑝𝑙𝑖𝑐𝑎 𝑐𝑢𝑎𝑛𝑑𝑜 𝑠𝑒 𝑣𝑎𝑛 𝑎 ℎ𝑎𝑐𝑒𝑟 𝑓𝑢𝑛𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 𝑡𝑟𝑎𝑛𝑠𝑓𝑒𝑟𝑒𝑛𝑐𝑖𝑎, 𝑒𝑛 𝑒𝑙
𝑐𝑎𝑠𝑜 𝑑𝑒 𝑞𝑢𝑒𝑟𝑒𝑟 𝑠𝑜𝑙𝑢𝑐𝑖𝑜𝑛𝑎𝑟 𝑙𝑎 𝑒𝑐𝑢𝑎𝑐𝑖ó𝑛 𝑑𝑖𝑓𝑒𝑟𝑒𝑛𝑐𝑖𝑎𝑙 𝑠𝑖 𝑠𝑜𝑛 𝑛𝑒𝑐𝑒𝑠𝑎𝑟𝑖𝑎𝑠 𝑙𝑎𝑠 𝑐𝑜𝑛𝑑𝑖𝑐𝑖𝑜𝑛𝑒𝑠 𝑖𝑛𝑖𝑐𝑖𝑎𝑙𝑒𝑠 𝑦 𝑛𝑜 𝑛𝑒𝑐𝑒𝑠𝑎𝑟𝑖𝑎𝑚𝑒𝑛𝑡𝑒 𝑠𝑜𝑛 0

## CLASIFICACIÓN DE LAS FUNCIONES DE TRANSFERENCIA
Sexto semestre Dinámica de sistemas
•Una función de transferencia se puede expresar como:

$$G(s)=\frac{N(s)}{D(s)}$$

•Donde N(s) Y D(s) son polinomios en la variable “s”
•Si denominamos n al grado del polinomio del numerador
•Si denominamos m al grado del polinomio del denominador
•Se tienen 3 casos posibles:

n>m impropia
m>n estrictamente propia
n=m bipropia

💡 Ejemplo

$𝑠2 + 1$, 𝑖𝑚𝑝𝑟𝑜𝑝𝑖𝑎

$2$, 𝑏𝑖𝑝𝑟𝑜𝑝𝑖𝑎

$\frac{1}{𝑠 + 1}$, *estrictamente* 𝑝𝑟𝑜𝑝𝑖𝑎

$\frac{(𝑠2−1)}{𝑠 + 1}$, 𝑖𝑚𝑝𝑟𝑜𝑝𝑖𝑎

$\frac{𝑠 − 1}{𝑠 + 1}$, *bi* 𝑝𝑟𝑜𝑝𝑖𝑎

## ZEROS DE UNA FUNCIÓN DE TRANSFERENCIA

•Si se igual a N(s) a 0 se obtienen los valores de “s” que cumplen con la condición
•Si el numerador se hace 0 toda la función de transferencia se vuelve cero de ahí el nombre para estos valores de “s”
•Estos valores pueden ser reales o complejos por lo tanto se pueden ubicar en un plano cartesiano

## Hallar los zeros de una función de transferencia

$$𝐺(𝑠)=\frac{𝑌(𝑠)}{𝑈(𝑠)}=\frac{3𝑠 − 1}{𝑠2 + 3𝑠 + 2}=\frac{𝑁(𝑠)}{𝐷(𝑠)}$$

$$ 𝑁(𝑠)=0, \qquad 3𝑠 − 1 = 0 $$

$$𝑠=\frac{1}{3}$$

> "S" es un número complejo

![GRÁFICA DE LOS ZEROS DE LA FUNCIÓN](https://github.com/AmAk-KAMB/APUNTESTERCERCORTE/blob/main/plano%20cartesiano.png))


Figura 1. Gráfica de zeros de la función

Ejemplo 

• Hallar los zeros para la siguiente función de transferencia:

$\frac{𝑠2+4𝑠+1}{𝑠4+3𝑠3+3𝑠2+𝑠+2}$

$$N(s)=0, \qquad s^2+4s+1$$

$$\frac{-4+\sqrt{16-4}}{2} \qquad \frac{-4-\sqrt{16-4}}{2}   $$
$$\frac{-4+\sqrt{12}}{2} \qquad \frac{-4-\sqrt{12}}{2}   $$

## Polos de una función de transferencia
•Si se iguala D(s)a 0 se obtienen los valores de“s”que cumplen con la condición
•Si el denominador se hace 0 toda la función de transferencia se vuelve infinito de ahí el nombre para estos valores de “s”
•Estos valores pueden ser reales o complejos por lo tanto se pueden ubicar en un plano cartesiano


$$𝐺(𝑠)=\frac{𝑌(𝑠)}{𝑈(𝑠)}=\frac{3𝑠 − 1}{𝑠2 + 3𝑠 + 2}=\frac{𝑁(𝑠)}{𝐷(𝑠)}$$

>𝑠2 + 3𝑠 + 2   →   Polinomio Característico

$$D(𝑠)= 0$$

$$s2 + 3𝑠 + 2 = 0$$

$$(𝑠 + 1) (𝑠 + 2) = 0$$

$$𝑠 = −1$$
$$𝑠 = −2$$


![Representación gráfica de polos](https://github.com/AmAk-KAMB/APUNTESTERCERCORTE/blob/main/2.png)


>Los polos pueden resultar siendo de 3 formas:

>Polos complejos conjugados: estos se veran con un "efecto de espejo" en el eje horizontal, es decir, que un polo se encuentre en el cuadrante enfrentado verticalmente y el otro en el otro cuadrante compartiendo su coordenada abscisa(en el eje horizontal)

>Polos reales diferentes: Estos se veran ubicados sobre el eje de las abscisas en 2 puntos diferentes

>Polos iguales repetidos:  Estos se veran ubicados sobre el eje de las abscisas en 2 puntos iguales

Ejemplo 

• Hallar los polos para la siguiente función de transferencia:

$\frac{s+2}{(s+3)(s^2+0.5s+1)}$


$$D(s)=0, \qquad s^2+0.5s+1$$

$$s_1=\frac{-1+\sqrt{1^(2)+4(2)(2)}}{2(2)} \qquad s_2=\frac{-1-\sqrt{1^(2)+4(2)(2)}}{2(2)} \qquad  (s+3)=0   $$
$$s_1=\frac{-1+\sqrt{1+16}}{4} \qquad s_2=\frac{-1-\sqrt{1+16}}{4} \qquad  s=-3 $$
$$s_1=\frac{-1+\sqrt{1}+\sqrt{16}}{4} \qquad s_2=\frac{-1-\sqrt{1}+\sqrt{16}}{4} \qquad  s=-3 $$
$$s_1=\frac{-1+1+4}{4} \qquad s_2=\frac{-1-1+4}{4} \qquad  s=-3 $$
$$s_1=\frac{-1+5}{4} \qquad s_2=\frac{-1-5}{4} \qquad  s=-3 $$
$$s_1=\frac{4}{4} \qquad s_2=\frac{-6}{4} \qquad  s=-3 $$
$$s_1=1 \qquad s_2=\frac{-3}{2} \qquad  s=-3 $$

![Representación gráfica de polos](https://github.com/AmAk-KAMB/APUNTESTERCERCORTE/blob/main/saaaaaa.png)


$$𝑢(𝑡)= 𝐴 𝑝𝑎𝑟𝑎 𝑡 > 𝑡0

$$    0 𝑝𝑎𝑟𝑎 𝑡 < 𝑡0}


$$ ℒ{𝑢(𝑡)} =\frac{𝐴}{𝑠} $$


##Grado de una función de transferencia

•Otra forma de clasificarlas funciones de transferencia es por su orden o grado
•Esto lo define el polinomio característisco
•Por ejemplo:

$$𝐺(𝑠)=\frac{3𝑠 − 1}{𝑠2 + 3𝑠 + 2}$$

>>Polinomio Característico de Segundo orden	

•Quiere decir que la función de transferencia es de segundo orden

Teorema del valor final

• El error en estado estacionario corresponde al error
  medido en 𝑡 = ∞
• Es posible aprovechar el teorema del valor final para
  saber el valor final del error

$$\lim_{𝑡→∞}  𝑓(𝑡)=\lim_{𝑠→0}𝑠𝐹(𝑠) $$

💡Ejemplo



$$𝐺(𝑠)=\frac{𝑌(𝑠)}{𝑈(𝑠)}=\frac{4}{5𝑠 + 1}$$
$$𝑌(𝑠)=\frac{4 ∗ 𝑈(𝑠)}{5𝑠 + 1}$$

•Si la entrada es un escalón:

$$𝑌(𝑠)=\frac{\frac{4}{𝑠}}{5𝑠 + 1}$$

El valor final de Y(s) se puede calcular aplicando el teorema del valor final:


$$\lim_{𝑠→0}𝑠𝐹(𝑠)=\lim_{𝑠→0}𝑠 * \frac{4 ∗ 𝑈(𝑠)}{5𝑠 + 1} $$



$$\lim_{𝑠→0}\frac{4 ∗ 𝑈(𝑠)}{5𝑠 + 1} = 4 $$

![Representación gráfica de polos](https://github.com/AmAk-KAMB/APUNTESTERCERCORTE/blob/main/4.png)


Entradas de prueba a un sistema

Respuesta de un sistema

• Sería necesario modelar cada Sistema desde cero
>Si se tuviera en cuenta las señales reales
>Ruido, Diferentes rangos, Diferentes señales

![Representación gráfica de polos](https://github.com/AmAk-KAMB/APUNTESTERCERCORTE/blob/main/5.png)


Posibles entradas de un sistema

•Si la solución de una ecuación diferencial depende de la entrada, la respuesta de un Sistema También
•Es muy difícil conocer la señales que están ocurriendo en un Sistema yaque depende de muchos factores como ruido, tipode señales, ambiente, entre otras
•Además el Sistema de control debe diseñarse para que funcione ante cualquier señal
•En control se utilizan diferentes tipos de señales de prueba para evaluar el desempeñode un sistema

Entrada Escalón

•Es una entrada que considera un cambio de nivel repentino

![Curva del limite resultante](https://github.com/AmAk-KAMB/APUNTESTERCERCORTE/blob/main/6.png)

$$\begin{Bmatrix}
A para & \\ t>t_0 
0 para & \\  t<t_ 
\end{Bmatrix}$$


$ℒ{𝑢(𝑡)}=\frac{𝐴}{𝑠}$$

𝑢 𝑡 = {
𝐴 𝑝𝑎𝑟𝑎 𝑡 > 𝑡0
0 𝑝𝑎𝑟𝑎 𝑡 < 𝑡0
ℒ{𝑢 𝑡 } =
𝐴
𝑠

𝑢 𝑡 = {
𝐴 𝑝𝑎𝑟𝑎 𝑡 > 𝑡0
0 𝑝𝑎𝑟𝑎 𝑡 < 𝑡0
ℒ{𝑢 𝑡 } =
𝐴
𝑠




Entrada Rampa

•Es una entrada que varíaenel tiempode forma lineal

Entrada parábola

•Es una entrada que considera una variación no lineal en el tiempo lo cual permite evaluar diferentes condiciones de inicio y final

Actividad

•Calcule el valor final para las 3 entradas de prueba

Actividad

• Para la ecuación diferencial 𝑦ഺ + 5𝑦ሷ + 13,5𝑦ሶ + 3,75𝑦 =
 7,5𝑢ሶ + 3,75𝑢 obtenga:
• Función de transferencia
• Zeros
• Polos
• Valor final frente a un escalón unitario y una rampa de
 pendiente 5

Resumen

•Una representación de los sistemas dinámicos es la función de transferencia
•La función de transferencia contiene tanto la respuesta transitoria como la respuesta estacionaria del sistema
•Se asumen todas las condiciones iniciales del sistema en cero(0)
•Al igualar los polinomios del numerador o denominador a cero se obtienen la ubicación de los polos y los zeros respectivamente

Preguntas…?

Modelamiento de sistemas con diagramas de bloques

Modelosde sistemascomplejos

•Se podrían modelar sistemas comoun todo hallando las funciones de transferencia de cadacomponente
•Otro enfoque es utilizar modelos y adesarrollados ampliamente para construir modelos más complejos
•Aún usando este enfoque hay muchos tipos de procesos y dispositivos

Solenoide

•Un solenoide está formado por un circuito eléctrico, una coplamiento electromecánico (transductor) y un sistema mecánico de traslación

Modelodel circuitoelectromagnético

Solenoide

•El electroimán produce una fuerza mecánica proporcional a la corriente en el embobinado

Acople en tre la parte electromagnética y la parte mecánica

Solenoide

•El electroimána trae una masa acoplada por medio de un resorte y se considera el mortiguamiento dado por la envolvente de la bobina

Sistema mecánico

Representación en bloques

Motor DC

Motor DC (Corriente de campo)

•Circuito electromagnético:

Motor DC (Corriente de campo)
• El flujo Φ en el entrehierro es proporcional a la corriente de
 campo 
• El torque desarrollado es proporcional al Φ y a la corriente de
 armadura
• El torque desarrollado es proporcional al Φ y a la corriente de
 armadura

Motor DC (Corriente de campo)
•El torque aplicado (partemecánica)a la carga se comporta como un Sistema rotacional clásico que considera la inercia y la fricción mecánica

Motor DC (Corriente de campo)

•La conexión de los modelos se realiza de la siguiente manera:

Motor DC (Corriente de armadura)

•La corriente de campo se asume constate por lo tanto el Torque es:
•La corriente de armadura se relaciona con el voltaje aplicado a la armadura por:

Motor DC (Corrientede armadura)

•El voltaje inducido en la armadura es proporcional a la velocidad angular del eje:
•Combinando estas ecuaciones se obtiene:

Motor DC (Corriente de armadura)

•La parte mecánica se comporta de la misma manera que en el caso anterior:

Diagram de bloques resultante

ElementosTransmisoresde energía

Engranajes y Poleas

•Son dispositivos mecánicos que transmiten la energía desde una parte del sistema aotra

Engranajes y Poleas

• J y 𝐾𝑚 Cambian si se tiene en cuenta el efecto de los
engranajes o poleas

Diagrama de bloques

Transmisión rotacional a lineal

Palancas

Potenciómetro

Potenciómetro de rotación

Potenciómetro de translación

Tacómetros

•Son dispositivos que convierten la velocidad angular a voltaje.

Sensores transmisores
•Si son lineales:
•Si no son lineales:

Modelos de otros procesos

💡Ejemplo

•Sea un tanque lleno con ocho litros de agua salada en el cual están disueltos dos kg de sal. Una solución de salmuera (agua salada) con tres kg de sal por litro entra al tanque a una velocidad de 4 l/min, mientras la mezcla bien agitada sale a la misma velocidad con la que entra.

Sistema Térmico

💡Ejemplo

conclusiones 


Álgebrade Bloques

Definición

•Una herramienta que puede ayudara en tender un poco la interacción entre varios sistemas son los diagramas de bloques
•Primer sistema de control J. Watt
•Para explicar su sistema empezó a
desarrollar los diagramas de bloques

Elementos de un diagrama de bloques

•Bloque Funcional:es un símbolo para representar la operación matemática que sobre la señal de entrada hace el bloque para producir la salida

Elementos de un diagrama de bloques

•Flechas:Representa las señales dentro del proceso.Obsérveseque la señal sólo puede pasar en la dirección de las flechas.Portanto,un diagrama de bloques de un sistema de control muestra explícitamente una propiedad unilateral.Lapunta de flecha que señala el bloque indica la entrada, y la punta de flecha quesealeja de  l bloque representa la salida.Tales flechas se conocen como señales.
