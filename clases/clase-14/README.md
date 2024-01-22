# clase-12

jueves 23 noviembre 2023, presencial

repaso unidades 7 (luz) y 8 (electricidad)

## luz

## espectro de luz visible

como humanos, vemos ondas cuyas longitudes de onda van entre aproximadamente 400 y 800 nanómetros.

$$1 \cdot nanómetro = 1 \cdot nm = 1 \cdot 10^{-9} \cdot m$$

los colores del espectro visible, ordenadas de longitud de onda más corta a más larga:

| color    | longitud de onda (nm) | frecuencia (THz) |
| :------- | :-------------------- | :--------------- |
| violeta  | 380-450               | 670-790          |
| azul     | 450-485               | 620-670          |
| cyan     | 485-500               | 600-620          |
| verde    | 500-565               | 530-600          |
| amarillo | 565-590               | 510-530          |
| naranja  | 590-625               | 480-510          |
| rojo     | 625-750               | 400-480          |

a cada rango de longitud de onda, podemos encontrar la frecuencia asociada, que es cómodo medirla en Tera Hertz.

$$1 \cdot THz = 1 \cdot 10^{12} \cdot Hz$$

ondas de menor frecuencia que el espectro visible son infrarrojas, ondas de mayor frecuencia que el espectro visible son llamadas ultravioleta.

## velocidad de la luz

$$c = 3 \cdot 10^8 \cdot \frac{m}{s}$$

es la máxima velocidad posible.

esto lleva al concepto de año luz, que es una unidad de distancia, que simboliza cuánta distancia es capaz de recorrer la luz en un año

$$1 \cdot añoluz = velocidad_{luz} * 1 \cdot año = 3 \cdot 10^{8} \frac{m}{s} \cdot 365.25 \cdot 24 \cdot 60 \cdot 60 s = (3 \cdot 365 \cdot 24 \cdot 60 \cdot 60) \cdot 10^{8} m = (3 \cdot 365 \cdot 24 \cdot 36) \cdot 10^{10} \cdot m =  \cdot 10^{10} \cdot m = 9.46728 \cdot 10^{15} \cdot m \approx 10^{16} \cdot m$$

## percepción de color

tenemos tres receptores con canales independientes para colores, en los conos de nuestros ojos.

cada uno de esos receptores se encarga de una de 3 tipos de luz:

- L (long): 560 nm
- M (medium): 530 nm
- S (short): 420 nm

se estima que un humano puede distinguir hasta 10 millones de colores.

## daltonismo

habilidad reducida para ver colores o diferencias entre colores, que afecta aproximadamente al 8% de la población.

los más comunes son:

- rojo/verde
- azul/amarillo

## buenas prácticas en diseño

- dejar a la gente elegir los colores
- usar señales paralelas al color, como forma y orden.
- usar contraste en brillo además de contraste en color.
- incluir texto, incluso cuando el texto es obvio

## percepción de movimiento

hermanos Lumière en marzo de 1895 hicieron la primera función pública y pagada de imágenes en movimiento para 40 personas, lo que se denomina el nacimiento del cine.

las personas son capaces de percibir entre 10 y 12 imágenes por segundo como imágenes separadas, y tasas más grandes de refresco son percibidas como movimiento.

en cine se tiende a grabar a 24 cuadros por segundo.

en general se usa en computación tasas de refresco de 50 Hz hacia arriba.

https://www.youtube.com/watch?v=_SzGQkI-IwM

## modelo RGB

modelo aditivo, basado en los colores primarios rojo, verde y azul.

si usamos 8 bits para cada color, tenemos 24 bits en total, o sea, 2^24 posibilidades.

$$2^{24} = 16,777,216$$

## bibliografía

- https://www.cliffsnotes.com/study-guides/physics/light/characteristics-of-light
- https://en.wikipedia.org/wiki/Trichromacy
  https://en.wikipedia.org/wiki/Color_blindness
- https://en.wikipedia.org/wiki/HSL_and_HSV
- https://en.wikipedia.org/wiki/CMYK_color_model
- https://en.wikipedia.org/wiki/LMS_color_space
- https://en.wikipedia.org/wiki/Auguste_and_Louis_Lumi%C3%A8re
- https://en.wikipedia.org/wiki/Frame_rate













## colores y computadores

un pixel RGB es capaz de brillar y con eso generar color.

si tenemos B bits de resolución por canal de color, entonces un pixel tiene 3B bits para representar su color.

entonces la cantidad de colores posibles en 1 pixel es:

$$colores_{pixel}= 2^{3 \cdot B}$$

si tenemos una pantalla de resolución 1080p, con 1920 por 1080 pixeles, entonces tenemos un total de.

$$pixeles = 1920 \cdot 1080 = 2,073,600$$

y cada uno de esos pixeles, puede ser de un color distinto, y necesitamos 3\*B bits de información para cada uno, y así definir su color.

si tenemos una tasa de refresco de 60 Hz, significa que tenemos 60 cuadros por segundo.

## electricidad

la palabra electricidad viene del latín elektrum, y a su vez, del griego elektron, que significa ámbar, ya que los primeros experimentos donde se observaron características eléctricas fueron hechos al frotar ámbar con otros objetos.

la electricidad describe flujo de energía y materia. con simpleza, tenemos la materia, hecha con átomos, en cuyo núcleo hay masa compuesta de protones y neutrones, que aportan carga positiva, y fuera del núcleo, orbitando, hay partículas de menor masa pero igual carga, llamadas electrones, con carga negativa.

un átomo o una molécula sin carga, es aquella que tiene igual número de protones y electrones, con lo que su carga total se anula y es 0. pero los electrones, en ciertas condiciones, pueden fluir, a lo que le llamamos corriente eléctrica.

## fuerza eléctrica

la ecuación de fuerza eléctrica entre 2 cargas viene dada por:

$$F_{electrica} = K \cdot \frac{q_1 \cdot q_2}{r^2}$$

donde:

- K es la constante de Coulomb
- q_1 y q_2 son cargas eléctricas, que tienen signo
- r es la distancia entre las cargas

la constante K de Coulomb tiene el siguiente valor y unidades:

$$K \approx 9 \cdot 10^9 \cdot \frac{N \cdot m^2}{C^2}$$

## corriente eléctrica

la corriente eléctrica la denotamos por I, de intensidad, y se mide en Amperes (A), que es una representación de carga eléctrica por unidad de tiempo. la unidad de carga eléctrica es Coulomb, con lo que 1 Ampere es igual a 1 Coulomb por segundo.

$$1 \cdot A = 1 \cdot \frac{C}{s}$$

1 Ampere es mucha carga por segundo, ya que 1 electrón posee una pequeña carga de aproximadamente

$$1 \cdot electron \approx 1.6 \cdot 10^{-19} \cdot  C$$

## voltaje eléctrico

el voltaje eléctrico es una medida de potencial eléctrico, y se mide en volts, donde 1 volt (V) es equivalente a 1 Joule dividido por Coulomb.

$$1 \cdot V = 1 \frac{J}{C}$$

las fuentes de poder que usamos en la vida cotidiana, como el enchufe, una batería, un puerto USB, tienen una medida de voltaje y una medida de corriente, donde ocurre lo siguiente:

- el voltaje entregado es IGUAL al de la especificación. ejemplos: enchufe 220 V en Chile, puerto USB 5 V, batería 1.5 V o 9V o algún otro estándar.
- la corriente entregada está LIMITADA por el valor de la especificación. si una fuente de poder es de 10 A, significa que lo máximo que provee es 10 A.

## potencia eléctrica

la potencia eléctrica se mide en watts (W), y un Watt es la cantidad de energía por segundo.

$$1 \cdot W = 1 \cdot {J}{s}$$

la relación entre potencia, voltaje y corriente viene dada por la ecuación:

$$P = V \cdot I$$

y si analizamos las unidades, podemos comprobar:

$$1 \cdot W = 1 \cdot V \cdot 1 \cdot A = 1 \cdot \frac{J}{C} \cdot \frac{C}{s} = 1 \cdot {J}{s}$$

## magnetismo

los imanes tienen 2 polos: norte y sur.

la tierra está polarizada, por eso tenemos brújulas que son capaces de detectar estos polos magnéticos para orientar.

no se han observado en la naturaleza, polos aislados, que no se presenten de a pares.

## electromagnetismo

la electricidad produce magnetismo, y a su vez, el magnetismo produce electricidad, son fenómenos interrelacionados.

el resumen entre cómo electricidad y magnetismo interactúan fue resumido en 4 ecuaciones por James Clerk Maxwell (1831-1879).

la tríada de físicos considerados más relevantes son Newton, Maxwell y Einstein, en ese orden cronológico.

## aplicaciones industriales de electromagnetismo

los micrófonos son imanes, que al ser movidos, producen un voltaje inducido. ese voltaje puede ser amplificado, y usado para alimentar un motor, conectado a un parlante, para volver a transducir de energía eléctrica a energía mecánica.

la guitarra eléctrica tiene cuerdas de metal, que al ser tocadas, vibran sobre las cápsulas, que son imanes. estos imanes tienen un campo magnético, y cuando las cuerdas vibran,se induce un pequeño voltaje en las cápsulas, que luego puede ser amplificado y hacer mover un parlante.

las turbinas hidroeléctricas son imanes, que con la energía mecánica del agua, se mueven e inducen voltaje, que luego alimenta al sistema eléctrico.

## Leo Fender

Leo Fender fue un inventor estadounidense que revolucionó la música popular del siglo XX, al crear la primera guitarra eléctrica sólida de producción industrial (Fender Esquire/Telecaster, 1950), y luego inventar el bajo eléctrico (Precision Bass, 1951), a pesar de nunca haber aprendido a tocar estos instrumentos.

## referencias

- https://en.wikipedia.org/wiki/James_Clerk_Maxwell
- https://en.wikipedia.org/wiki/Leo_Fender
- https://www.twitterandteargas.org/
- https://github.com/montoyamoraga/audiv020-2022-2/tree/main/clases/clase-06
