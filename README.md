![](https://images.cooltext.com/5387547.png)

<a href="http://cooltext.com" target="_top"><img src="https://cooltext.com/images/ct_pixel.gif" width="80" height="15" alt="Cool Text: Logo and Graphics Generator" border="0" /></a>

| Integrantes | Participación | Calificación |
|-------------|----------------|--------------|
| Alvarado Godinez Edson          |                |              |
| Aragon Bustos Victor Leonel           |                |              |
| Martinez Cervantes Gerardo           |                |              |
| Luna Fuentes Fernando           |                |              |

## Definición
Un sensor óptico o también llamado fotoeléctrico es capaz de detectar una presencia o algún objeto a distancia, a travez del cambio de intensidad de luz. Debido a que estos dispositivos se basan en la cantidad de luz detectada o reflectividad de los objetos, es posible detectar casi todos los tipos de materiales, por ejemplo. Vidrio, metal, plástico, madera y líquidos.
sensor óptico.

Los sensores ópticos son de los más sensibles que existen y justamente por este motivo es que la mayoría de ellos no duran demasiado tiempo, además más allá de las utilidades que los mismos pueden tener. 

![sensor_óptico](https://i1.wp.com/www.ingmecafenix.com/wp-content/uploads/2018/04/Fotoel%C3%A9ctrico.png?w=438&ssl=1)

## ¿Como funcionan?
Estos componentes requieren la participación de un emisor y un receptor, el emisor se encarga de enviar una señal en forma de luz y el receptor esta encargado de detectar ese haz de luz enviado por el emisor.

Existen sensores que utilizan como emisor la luz natural y de receptor una fotoresistencia. Pero debido a que en este tipo de sensores es fácil alterar su funcionamiento con alguna fuente de luz distinta a la prevista. Se utilizan principalmente  para activar o desactivar lamparas de alumbrado.

![](https://i2.wp.com/www.ingmecafenix.com/wp-content/uploads/2017/05/Fotorresistencia_L%C3%A1mpara.png?ssl=1)

Para poder solucionar el problema que tienen estos sensores, se utiliza un  emisor (led infrarrojo) y un receptor (fototransistor) los cuales están sincronizados a una frecuencia especifica para que el receptor este siempre seguro que la señal que detecta es la que produce el emisor.

![](https://i0.wp.com/www.ingmecafenix.com/wp-content/uploads/2018/04/Infrarrojo.jpg?ssl=1)

## Partes de un sensor óptico
Este tipo de sensor no es muy complejo por consecuencia están conformados por pocas partes y todas sencillas de entender:

## Emisor

Origina un haz luminoso, usualmente con un LED que puede tener un amplio rango en el espectro (incluyendo luz visible e infraroja). Para la mayoria de las aplicaciones se prefiere kas radiaciones infrarojas pues son las que mayor porcentaje de luz emiten y disipan menos calor. Los LEDs tipos visibles son muy utiles sobre todo para facilitar el ajuste de la operacion del sensor. Entre los LED de luz visible los LEDs de luz roja son los más eficaces para la aplicación. En la figura 1 se muestra el diagrama de un LED y se observan sus partes.

![](https://merakideveloper.com/wp-content/uploads/2020/03/Figura-1.jpg)

El haz con frecuencai es modulado con pulsos, ya que la modulación presenta ventajas como son: mayor luminosidad en el haz, mayor vida útil del LED, inmunidad del sensor a otras fuentes de luz que puedan unterferir con la señal. Presenta la desventaja de reducir la respuesta en frecuencia del detector óptico. La figura 2 presenta los pulsos de alimentación para la modulación de un emisor.

![](https://merakideveloper.com/wp-content/uploads/2020/03/Figura-2.jpg)

## Receptor

Recibe el haz luminoso de la fuente, usualmente es un fotodiodo o un foto transistor. El foto sensor debe estar acoplado espectramente con el emisor, esto significa que el fotodiodo o el foto transistor que se encuentra en el detector debe permitir mayor circulación de corriente cuando la longitud de onda recibida sea igual a la del LED en el emisor. El receptor recibe los pulsos de luz en sincronia con el emisor, esto permite ignorar radiaciones provenientes de otras fuentes. Este tipo de recepción sincrónica sólo es posible cuando la fuente y el receptor están en el mismo encapsulado. En el receptor, además existe un circuito asociado que acondiciona la señal antes de llegar al dispositivo de salida. En la figuta 3 se observa una gráfica que muestra como LED infrarrojo tiene mayor eficacia que el LED visible rojo.

![](https://merakideveloper.com/wp-content/uploads/2020/03/Figura-3.jpg)

## Lentes 

Tienen la función de dirigir el haz de luz tanto en el emisor como en el receptor para restringir el campo de visión, esto trae como consecuencia aumentar la distancia de detección. El área de la base del cono de haz emitido por el LED y el lente aumenta a mayor distancia. Utilizando un lente que se puede generar un cono muy estrecho, lo que permitiría darle más alcance al sensor pero con el inconveniente de presentar mayor dificultad en el momento de alinearlo. Algunos detectores son diseñados para tener un amplio campo de visión, esto permite detectar objetos grandes, pero a distancias relativamente cortas. La figura 4 presenta como propaga el campo de visión en presencia y ausencia del lente.

![](https://merakideveloper.com/wp-content/uploads/2020/03/Figura-4.jpg)

## Circuito de salida 

Existen varios tipos de salidas discretas o digitales (se denominan asi por  tener dos estados y las más comunes son: NPN o PNP, TRIAC, MOSFET. En la figura 5 se muestra un diagrama de bloque de un sensor fotoeléctrico con todas sus partes.

![](https://merakideveloper.com/wp-content/uploads/2020/03/Figura-5.jpg)

La fuente de alimentación suministra la potencia necesaria para el funcionamiento del detector, en el regulador de voltaje se ajustan y mantienen los niveles de tensión utilizados por el resto de los bloques del sensor. El generador de pulsos de pulsos suministra al LED la señal modulada que permitirá la emisión de un haz discontinuo de luz que al chocar con un objeto regresa al foto detector. La salida de foto detector es amplificada (nota: la ganacia del amplificador puede ser cambiada para ajustar la sensibilidad) y luego es comparada con la frecuencia de pulsos para verificar que la señal recibida provenga del LED del detector, esto se hace en el integrador. El nivel de salida del integrador es chequeado en el detector de nivel de tal forma que la cantidad de luz recibida sea suficiente para activar o desactivar el sensor. En algunos sensores se puede colocar una lógica de tiempo opcional que permite introducir retardos para activar o desactivar la salida. Finalmente se encuentra el dispositivo de salida, para el diagrama de la figura 5, que corresponde a un sensor con salida discreta, este dispositivo puede ser un relé, un transistor NPN, un transistor PNP, un TRIAC, un FET o un MOSFET. La salida alimenta directamente a la carga que puede ser la entrada de un controlador lógico programable, la bobina de un relé, de un arrancador o de una válvula solenoide, una luz piloto o cualquier otro dispositivo de salida.

A continuación de manera mucho mas resumida, donde se trata de manera directa y consisa las partes que integran el sensor óptico.



- **Emisor**: Da origen a un haz luminoso normalmente a travez de un led infrarrojo.
- **Receptor**: Esta encargado de captar la señal producida por el emisor, generalmente se utiliza un fototransistor o un fotodiodo.
- **Lentes**: Están diseñados para modificar el campo de visión de los componentes, esto trae como consecuencia el aumento de la distancia de detección
- **Circuito de salida**: Básicamente es el circuito que se encarga de mandar la señal de salida ya sea digital o analógica.

![](https://i1.wp.com/www.ingmecafenix.com/wp-content/uploads/2018/04/Partes-sensor-infrarrojo.jpg?ssl=1)


## Clasificacion de sensores ópticos

**Barrera (Emisor-Receptor)**
Detectan al objeto midiendo la diferencia de intensidad de la luz que se emite el emisor y la que llega al receptor
 
![](https://www.keyence.com.mx/Images/sensorbasics_photoelectric_info_img_02_1547920.gif?ssl=1)




**Retro reflectivo**
Usa un espejo especial (reflector) con alta reflectividad para medir y comparar la diferencia de cantidad
de luz emitida con la luz recibida a través del espejo. En el mismo cuerpo se encuentra el emisor y el receptor.

![](https://www.keyence.com.mx/Images/sensorbasics_photoelectric_info_img_03_1547921.gif?ssl=1)




**Retro reflectivo polarizado**
Incluye un filtro polarizador para recibir únicamente la luz reflejada proveniente del reflejante. Se aplica para detectar objetos con superficies brillantes (plástico, acrílico, piezas con pintura brillante). En el mismo cuerpo se encuentra el emisor y el receptor.
 
![](https://1.bp.blogspot.com/-S0XkUPYiZc4/XmFeWp9lk_I/AAAAAAAABa4/b9fUhsGliAsUaR_MQ349mV_3BvmCMTskQCLcBGAsYHQ/s1600/Retro%2Breflectivo%2Bpolarizado.PNG?ssl=1)



**Difuso Reflectivo**
Detecta recibiendo directamente la luz reflejada del objeto. En el mismo cuerpo se encuentra el emisor y
el receptor.

![](https://www.keyence.com.mx/Images/sensorbasics_photoelectric_info_img_01_1547919.gif?ssl=1)



**Convergente reflectivo**
 Distancia de detección limitada. El fondo y color del objeto no tienen efectos significativos en la detección.

![](https://1.bp.blogspot.com/-TrPQI6Xh-Wc/XmFgnZylgqI/AAAAAAAABbc/r215tLwLtNwHqHwKIlZYozNjS8jo425nQCLcBGAsYHQ/s1600/1.PNG?ssl=1)



**Amplificador de fibra óptica**
Sensor fotoeléctrico que tiene separada la electrónica (amplificador) y la óptica (fibra).
- Detectan objetos pequeños.
- Instalación el lugares estrechos y ambientes hostiles

![](https://www.panasonic-electric-works.com/pew/es/images/sensors/pp_fx550_rdax_478x358.jpg?ssl=1)


## Principio de funcionamiento del sensor óptico CNY70

El principio es realmente sencillo, ya que en el momento que nosotros alimentamos el LED emisor, este genera una señal lumínica, rebotara en el obstáculo, de modo que el receptor mostrar la señal como que existe una interferencia.

## ¿Cómo configurar un sensor óptico?

En el caso que ya tengas configurado el sensor de forma física te explicamos como configurar, para ello es recomendable que utilices el software “Proteus 8”, de este modo podrás ver al simulación y el circuito final. En el vídeo esta todo explicado.

[![](http://img.youtube.com/vi/IkW5-hjZ7XM/0.jpg)](http://www.youtube.com/watch?v=IkW5-hjZ7XM "Configuracion del sensor CNY70")

## Sensor Optico PIR
El sensor  PIR es un circuito electronico pasivo que mide luz infraroja radiando de los objetos.
Comunmente usados en detectores de movimiento PIR como en las alarmas de seguridad y aplicaciones de luz automatizadas.

El sensor PIR detecta movimiento pero no  envia informacion de que  fue lo que se movio, para eso se ocupa un sensor PIR activo. 
El sensor tiene 2 puertos de material ultrasencible a la luz almacenado en una cubieta de metal que lo proteje de condiciones externas como temperatura, humedad, polvo etc. En conjunto con un lente que le ayuda a enfocar la luz a su alrededor hacia estos 2 puertos los cuales actuan en conjunto en detectar el diferencial de calor, asi enviando una instruccion 1 o 0.

![sensor_óptico](https://cdn-learn.adafruit.com/guides/cropped_images/000/000/030/medium640/proximity_pirsensor.jpg?1520539813?w=438&ssl=1)
