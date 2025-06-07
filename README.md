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
