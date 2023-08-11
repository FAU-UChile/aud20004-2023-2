# ayudantía-01

viernes 11 agosto 2023

## resumen

### segunda ley de newton

$$\vec{F} = m \cdot \vec{a}$$

*"La aceleración de un objeto es directamente proporcional a la fuerza que actúa sobre él, e inversamente proporcional a la masa"*

la fuerza se mide en Newton $[N] = [kg \cdot m/s^2]$

### ley de gravitación universal

$$F_g = G\frac{m_1m_2}{r^2}$$

Los objetos con masa se atraen mutuamente.

$F_g$ : fuerza de atracción gravitatoria

$m_1$ : masa cuerpo 1

$m_2$ : masa cuerpo 2

$r$ : distancia entre los centros de ambos cuerpos.

$G = 6.67 \cdot 10^{-11} [\frac{Nm^2}{kg^2}]$ : constante de gravitación universal

### vectores

un vector es un objeto geométrico que representa una dirección y un sentido dentro de un sistema de coordenadas. En general se representa como una flecha.

el vector de dos dimensiones $\vec{V}$ de coordenadas $(V_x, V_y)$ se grafica de la siguiente manera:

![Alt text](./img/vec.jpg)

#### modulo, magnitud o amplitud de un vector $||\vec{V}||$

el módulo o amplitud de un vector nos dice su tamaño. 

$$||\vec{V}|| = \sqrt{V_x^2 + V_y^2}$$

#### vectores unitarios $\hat{V}$

son vectores de modulo igual a 1. 

a todos los vectores se les puede calcular su vector unitario:

$$\hat{V} = \frac{\vec{V}}{||\vec{V}||} $$

#### componentes de un vector

teniendo el ángulo de un vector y su magnitud es posible calcular las componentes del vector utilizando trigonometría.

$$\vec{F} = (F \cdot cos(\alpha), F \cdot sen(\alpha))$$

![Alt text](./img/vector_fuerza.jpg)


## ejercicio-01: unidades de medida

a) La distancia de mi casa al metro es de $1.23[km]$ ¿a cuántos metros corresponde esta distancia? ¿y a cuántos centímetros?

b) La distancia de la tierra a la luna es de aproximadamente $3.84 \cdot 10^{5} \ [km]$. Exprese esta distancia en metros, centímetros.

c) Tomé un bus y demoré 2.3 horas en llegar a Valparaíso. ¿Cuántos minutos demoré en total? ¿y cuántos segundos?

d) La micro D13 viaja a una velocidad promedio de $12[m/s]$ ¿a cúantos kilómetros por hora corresponde esta velocidad?

e) ¿a cuántos metros por segundo corresponden $120[km/h]$?

<details>
<summary>--- solución ---</summary>

a) $1230[m]$, $123000[cm]$

b) $3.84 \cdot 10^{5} \ [km] \Rightarrow 3.84 \cdot 10^{8} \ [m] \Rightarrow 3.84 \cdot 10^{10} \ [cm]$

c) $138[min]$,  $8280 [seg]$

d) $12[m/s] \Rightarrow \frac{0.012[m]}{1[s]} \Rightarrow \frac{0.012[m]}{\frac{1}{3600}[h]} \Rightarrow 43.2[km/h]$

e) $120[km/h] \Rightarrow \frac{120000[m]}{1[h]} \Rightarrow \frac{120000[m]}{3600[s]} \Rightarrow 33.3[m/s]$
</details>

## ejercicio-02: ley de gravitación universal

a) calcule aproximadamente la fuerza de atracción de gravedad entre la tierra y la luna sabiendo que: 
- masa de la tierra = $5.98 \cdot 10^{24} \ [kg]$
- masa de la luna = $7.35 \cdot 10^{22} \ [kg]$
- distancia entre la tierra y la luna = $3.84 \cdot 10^{5} \ [km]$

<details>
<summary>--- solución ---</summary>

$$F_g = G\frac{m_1m_2}{r^2}$$

$$F_g =  6.67 \cdot 10^{-11} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{5.98 \cdot 10^{24} \ [kg] \cdot 7.35 \cdot 10^{22} \ [kg]}{(3.84 \cdot 10^{5} \ [km])^2}$$

$$F_g =  6.67 \cdot 10^{-11} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{5.98 \cdot 7.35 \cdot 10^{24+22} \ [kg^2] }{(3.84 \cdot 10^{8} \ [m])^2}$$

$$F_g =  6.67 \cdot 5.98 \cdot 7.35 \cdot 10^{(-11+24+22-16)} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{[kg^2]}{3.84^2 \cdot 10^{16} \ [m^2]}$$

$$F_g =  \frac{6.67 \cdot 5.98 \cdot 7.35 \cdot 10^{19}}{3.84^2} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{[kg^2]}{[m^2]}$$

$$F_g =  \frac{293.16651 \cdot 10^{19}}{14.7456} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{[kg^2]}{[m^2]}$$

$$F_g = 19.88 \cdot 10^{19} [N]$$

$$F_g \approx 1.98 \cdot 10^{20} [N]$$

</details>

b) calcule aproximadamente la fuerza de atracción de la tierra sobre una persona de $80[kg]$ sabiendo que:
- masa de la tierra = $5.98 \cdot 10^{24} \ [kg]$
- radio promedio de la tierra = $6.37 \cdot 10^{6} \ [m]$

<details>
<summary>--- solución ---</summary>

$$F_g = G\frac{m_1m_2}{r^2}$$

$$F_g =  6.67 \cdot 10^{-11} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{5.98 \cdot 10^{24} \ [kg] \cdot 85 \ [kg]}{(6.37 \cdot 10^{6} \ [m])^2}$$

$$F_g =  6.67 \cdot 10^{(-11+24-12)} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{5.98 \cdot 85 \ [kg^2]}{(6.37)^2 \ [m^2]}$$

$$F_g =  \frac{6.67 \cdot 5.98 \cdot 85 \cdot 10^{1}}{(6.37)^2} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{[kg^2]}{[m^2]}$$

$$F_g =  \frac{33903.61}{40.5769} \left[\frac{Nm^2}{kg^2}\right] \cdot \frac{[kg^2]}{[m^2]}$$

$$F_g = \frac{33903.61}{40.5769} \ [N]$$

$$F_g \approx 835.54 \ [N]$$

</details>

## ejercicio-03: fuerza, masa y aceleración

a) ¿cuál es la masa de un cuerpo que, estando en reposo, al recibir una fuerza de $10 [N]$ adquiere una aceleración de $20[m/s^2]$?

b) Un objeto de $5[kg]$ tiene una velocidad de $10[m/s]$ y se le aplica una fuerza de $20[N]$ por 5 segundos ¿qué aceleración experimentará durante esos 5 segundos? ¿Cuál será su velocidad final?

c) Un vehículo de $100[kg]$ de masa se mueve en línea recta a $70[km/h]$. ¿Qué fuerza debe aplicarse en forma constante para que reduzca su velocidad a $20[km/h]$ durante los siguientes 10 segundos de aplicada la fuerza?


<details>
<summary>--- solución ---</summary>

a) 

$$F=m \cdot a$$ 

$$m=F/a$$ 

$$m=\frac{10[N]}{20[m/s^2]}$$ 

$$m=\frac{10[kg \cdot m/s^2]}{20[m/s^2]}$$ 

$$m=\frac{10}{20}[kg]$$ 

$$m=0.5[kg]$$ 


b)

$$F=m \cdot a$$ 

$$a=F/m$$ 

$$a=\frac{20[N]}{5[kg]}$$ 

$$a=\frac{20[kg \cdot m/s^2]}{5[kg]}$$ 

$$a= 4[m/s^2]$$ 

por lo tanto, experimentará una aceleración de $4[m/s^2]$, lo que significa que cada segundo su velocidad aumentará $4[m/s]$. Eso quiere decir que en 5 segundos su velocidad aumentará $20[m/s]$ y su velocidad final será de $30[m/s]$.

c) se debe aplicar una fuerza para bajar la velocidad $50[km/h]$ en $10[seg]$.

$$a=\frac{50[km/h]}{10[seg]}$$ 

$$a=\frac{13.88[m/s]}{10[s]}$$ 

$$a=1.388[m/s^2]$$ 

por lo tanto la fuerza requerida es:

$$F=m \cdot a$$ 

$$F=100[kg] \cdot 1.388[m/s^2]$$ 

$$F=138.8[kg \cdot m/s^2]$$ 

$$F=138.8[N]$$ 


</details>

## ejercicio-04: fuerza, velocidad y aceleración como vectores

a) si una pelota de basketball se mueve a una velocidad constante de $\vec{v} = (2, 3) [m/s]$, responda:

- ¿cuál es su velocidad en el eje $\hat{x}$ de coordenadas?

- ¿cuál es su velocidad en el eje $\hat{y}$ de coordenadas?

- ¿en qué eje de coordenadas se desplazará más rápido?

- Calcule la velocidad lineal de la pelota.

<details>
<summary>--- solución ---</summary>

- su velocidad en el eje $\hat{x}$ es de $2 [m/s]$.

- su velocidad en el eje $\hat{y}$ es de $3 [m/s]$.

- se desplazará más rápido en el eje $\hat{y}$ (hacia arriba).

- para encontrar la velocidad lineal de la pelota, calculamos la magnitud del vector velocidad:

$$||\vec{v}|| = \sqrt{v_x^2 + v_y^2}$$

$$||\vec{v}|| = \sqrt{2^2 + 3^2}$$

$$||\vec{v}|| = \sqrt{4 + 9}$$

$$||\vec{v}|| = \sqrt{13}$$

$$||\vec{v}|| \approx 3.605 \ [m/s]$$

</details>

b) si una pelota de tenis de $50[g]$ es golpeada con una fuerza de $20[N]$ con un ángulo de incidencia $60°$.

- Calcule el vector fuerza ejercido a la pelota al momento de ser golpeada.

- ¿En qué eje de coordenadas recibe mayor fuerza?

- Calcule el vector aceleración ejercida en la pelota al momento de ser golpeada.

- Calcule la aceleración lineal ejercida en la pelota al momento de ser golpeada.

<details>
<summary>--- solución ---</summary>

- para calcular el vector fuerza utilizamos trigonometría:

$$\vec{F} = (F \cdot cos(\alpha), F \cdot sen(\alpha))$$

$$\vec{F} = (20[N] \cdot cos(60°), 20[N] \cdot sen(60°))$$

$$\vec{F} \approx (10, 17.32) [N]$$

- por lo tanto, recibe una fuerza mayor en el eje $\hat{y}$ (hacia arriba).

- para calcular la aceleración, aplicamos la versión vectorial de la segunda ley de newton:

$$\vec{F} = m \cdot \vec{a}$$

$$\vec{a} = \frac{\vec{F}}{m}$$

$$\vec{a} = \frac{(10, 17.32) [N]}{50[g]}$$

$$\vec{a} = \frac{(10, 17.32) [N]}{0.05[kg]}$$

$$\vec{a} = \left(\frac{10[N]}{0.05[kg]}, \frac{17.32[N]}{0.05[kg]}\right)$$

$$\vec{a} = (200[m/s^2], 346[m/s^2])$$

$$\vec{a} = (200, 346) \ [m/s^2]$$

- la aceleración lineal se calcula con el módulo del vector aceleración:

$$||\vec{a}|| = \sqrt{a_x^2 + a_y^2}$$

$$||\vec{a}|| = \sqrt{200^2 + 346^2}$$

$$||\vec{a}|| \approx 400 [m/s^2]$$


</details>