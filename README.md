# Investigación

## ¿Qué es una tarjeta de adquisición de datos?

Las tarjetas de adquisición de datos (hardware) actúan como la interfaz entre una computadora y señales físicas, es decir, la información recaudada por el sensor se pasa al **"DAQ"** (Data Acquisition System), el cual se encarga de transformar los códigos del mundo real a los códigos digitales.
Las tarjetas de adquisición de datos consisten en tres partes principales:  

- Circuito de acondicionamiento de señales. 
- Convertidor analógico-digital **"ADC"** (Analog-to-Digital Converter). 
- Bus del ordenador.

## ¿Qué es un HMI?

Un HMI (Human Machine Interface) es un sistema que proporciona una plataforma para la interacción entre los usuarios y los sistemas automatizados. Esta interfaz juega un papel crucial en la automatización industrial, facilitando la comunicación bidireccional entre humanos y máquinas.
Las HMI constan de varios componentes de hardware que permiten la interacción entre el usuario y la máquina. Los más comunes incluyen:
- **Pantallas Táctiles:**
Las pantallas táctiles proporcionan una interfaz de usuario interactiva que permite a los operadores interactuar directamente con el sistema de automatización.
- Pantallas
Las pantallas permiten a los operadores visualizar datos en tiempo real, representaciones gráficas de los procesos y alertas de estado del sistema.
- **Teclados:**
Los teclados son un componente esencial de muchas HMI, permitiendo a los usuarios introducir comandos y datos.
- **Software y Herramientas de Desarrollo de HMI:**
El software HMI es lo que hace que la interfaz sea interactiva y fácil de usar. Proporciona las funcionalidades necesarias para la visualización de datos, el control del proceso y la interacción con el sistema de automatización. Hay varias herramientas de desarrollo de HMI disponibles en el mercado, cada una con sus propias características y capacidades, siendo las más populares las proporcionadas por fabricantes como Siemens, Rockwell Automation y Schneider Electric.

## Elementos de un sistema de adquisición de datos

Todos los sistemas de adquisición de datos constan de tres elementos esenciales:
-
1.- El sensor.
2.- El acondicionamiento de la señal.
3.- El convertidor analógico-digital (ADC).

- **Sensores (transductores):**
Los sensores, a menudo llamados transductores, convierten los elementos del mundo real, como la temperatura, la fuerza y el movimiento, en señales de tensión o de corriente que pueden utilizarse como entradas para el ADC.
Los sensores más comunes son los termopares, los termistores y los RTD para medir la temperatura, los acelerómetros para medir el movimiento y las galgas extensométricas para medir la fuerza.
A la hora de elegir el sensor adecuado para tu sistema de medición, es importante tener en cuenta factores como la precisión del sensor y el acondicionamiento de la señal necesario para registrar una señal legible.

- **Acondicionamiento de la señal:**
Para realizar mediciones de calidad en los transductores, a menudo se necesita un circuito adicional entre el transductor y el ADC.
Esta circuitería se conoce generalmente como acondicionamiento de la señal y puede incluir amplificación/atenuación, filtrado, puente de Wheatstone, excitación, alineación, calibración y compensación de unión fría.
En función del tipo de sensor existen necesidades diferentes de acondicionamiento de la señal.

- **Convertidor analógico-digital:**
El núcleo de todos los sistemas de adquisición de datos es el convertidor analógico-digital (ADC).
Como su nombre indica, este chip toma los datos del entorno y los convierte en gráficos discretos que pueden ser interpretados por un procesador.
Estos niveles discretos corresponden al cambio más pequeño detectable en la señal que se está midiendo.
Cuanto mayor sea el número de «bits» de un ADC (12 bits, 16 bits, 18 bits, etc.), mayor será el número de gráficos discretos que pueden representar una señal analógica y mayor será la resolución del ADC.

## ¿Qué es un sensor?
Un sensor es un dispositivo que detecta el cambio en el entorno y responde a alguna salida en el otro sistema. Un sensor convierte un fenómeno físico en un voltaje analógico medible (o, a veces, una señal digital) convertido en una pantalla legible para humanos o transmitida para lectura o procesamiento adicional.

**Tipos de sensores**

- **Sensores de proximidad:**
Son transductores que detectan objetos o señales que se encuentran cerca del elemento sensor. Existen varios tipos de sensores de proximidad según el principio físico que utilizan, los más comunes son los que te mencionamos a continuación.

- **Inductivos:**
Han sido diseñados para trabajar generando un campo magnético y detectando las pérdidas de corriente de dicho campo generadas al introducirse en él los objetos de detección férricos. El sensor consiste en una bobina con núcleo de ferrita, un oscilador, un sensor de nivel de disparo de la señal y un circuito de salida.
Al aproximarse un objeto metálico, se inducen corrientes de histéresis en el objeto, debido a ello hay una pérdida de energía y una menor amplitud de oscilación. El circuito sensor reconoce entonces un cambio específico de amplitud y genera una señal que conmuta la salida de estado sólido o la posición on y off.

- **Magnéticos:**
Son caracterizados por la posibilidad de distancias grandes de la conmutación, disponible de los sensores con dimensiones pequeñas. Detectan los objetos magnéticos (imanes generalmente permanentes) que se utilizan para accionar el proceso de la conmutación.
Los campos magnéticos pueden pasar a través de muchos materiales no magnéticos, el proceso de la conmutación se puede también accionar sin la necesidad de la exposición directa al objeto. Usando los conductores magnéticos, por ejemplo el hierro; el campo magnético se puede transmitir a mayores distancias para poder llevarse la señal de áreas de alta temperatura.

- **Capacitivos:**
Detectan objetos metálicos, o no metálicos, midiendo el cambio en la capacitancia, la cual depende de la constante dieléctrica del material a detectar, su masa, tamaño, y distancia hasta la superficie sensible del detector.  Debido a la influencia del objeto a detectar, y del cambio de capacitancia, la amplificación se incrementa haciendo entrar en oscilación el oscilador.
Cuando un objeto conductor se acerca a la cara activa del detector, el objeto actúa como un condensador. El cambio de la capacitancia es significativo durante una larga distancia, si se aproxima un objeto no conductor, (>1) solamente se produce un cambio pequeño en la constante dieléctrica, y el incremento en su capacitancia es muy pequeño comparado con los materiales conductores.
Estos sensores se utilizan comúnmente para detectar material no metálico como papel, plástico y madera, ya que, funcionan como un condensador.

- **Ultrasónicos:**
Trabajan libres de roces mecánicos y detectan objetos a distancias de hasta 8 m y emiten impulsos ultrasónicos. Estos se reflejan en un objeto, el sensor recibe el eco producido y lo convierte en señales eléctricas, las cuales son elaboradas en el aparato de valoración.
Trabajan solamente en el aire, y pueden detectar objetos con diferentes formas, superficies y de diferentes materiales. Los materiales pueden ser sólidos, líquidos o polvorientos, sin embargo, han de ser deflectores de sonido. Los sensores trabajan según el tiempo de transcurso del eco, es decir, se valora la distancia temporal entre el impulso de emisión y el impulso del eco.

- **Codificadores incrementales y absolutos:**
Los incrementales generan un tren de pulsos o una onda sinusoidal, donde el número de pulsos pueden ser una medida de velocidad, longitud o posición. En los absolutos, cada posición corresponde a un único código, de modo que tras un corte de energía la posición queda almacenada y puede ser leída al volver la alimentación. Esto evita tener que volver a referenciar el equipo.

- **Sensores fotoeléctricos:**
Responden al cambio en la intensidad de la luz, requieren de un componente emisor que genera la luz, y un componente receptor que percibe la luz generada por el emisor. Están diseñados especialmente para la detección, clasificación y posicionamiento de objetos; la detección de formas, colores y diferencias de superficie, incluso bajo condiciones ambientales extremas.

- **Sensores de área:**
Se emplean en numerosas soluciones como el registro de objetos, personas, vehículos, y el control de presencia y sobredimensionamiento de objetos. Utilizan multi haces de luz para la detección de objetos en movimiento en áreas específicas.

- **Sensores de presión:**
Su objetivo es transformar una magnitud física en una eléctrica, en este caso transforman una fuerza por unidad de superficie en un voltaje equivalente a esa presión ejercida. Aunque los formatos son diferentes, destacan en general por su robustez, ya que, en procesos industriales están sometidos a todo tipo de líquidos, existiendo así sensores de presión para agua, de presión para aceite, líquido de frenos, etc.

- **Sensores de temperatura:**
Recogen información sobre la temperatura de una fuente y la cambian a una forma que pueda ser comprendida por otro dispositivo. Se trata de una categoría de sensores de uso común que detectan la temperatura o el calor y también mide la temperatura de un medio.

- **Sensores de flujo:**
Permiten medir y monitorear el flujo de los medios de proceso, como lubricante o agua de enfriamiento, en una amplia gama de aplicaciones. Cuando reciben una alerta de que el flujo se ha ralentizado o detenido, pueden responder rápidamente y evitar un tiempo de paro imprevisto de la máquina o incluso la detención del sistema en su totalidad.

- **Sensores de corriente:**
Detectan la corriente de forma rápida y exacta para controlar con precisión sistemas electrónicos de potencia tales como convertidores de frecuencia, convertidores de tracción, sistemas de alimentación eléctrica ininterrumpida o sistemas de soldadura.

## ¿Qué es un acondicionador de señal?
Se encarga de acondicionar señales para que el subsistema A/D pueda convertirlas en el dominio digital y luego mostrarlas, almacenarlas y analizarlas.
Los sistemas de adquisición de datos deben conectarse a una amplia variedad de sensores y señales para hacer su trabajo. Los acondicionadores de señal toman la señal del sensor, la procesan y la envían al subsistema A/D.
Hoy en día, los acondicionadores de señal incluyen algunos de los elementos necesarios que los hacen útiles para los sistemas modernos de adquisición de datos. Estos elementos son:

- Aislamiento electrico
- Los conectores correctos para conexiones de sensores
- Selección del rango de medida
- Filtrado de señales
- Conformidad con los requisitos del sensor.
