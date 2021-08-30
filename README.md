# InformeLaboratorio7


Integrantes: Jonathan Insuasti - César Garnica - Melany Villa

# 1. Objetivos 

      Objetivo General
     
    - Analizar y comprobar el comportamiento del capacitor y el inductor en coriente alterna y 
    corriente directa mediante la   resolución del ejerciciopropuesto en la guía de práctica
    para identificar el uso correcto con su respectiva simulación en un software de diseño electrónico.
    
      Objetivos Específicos
      
      - Verificar el comportamiento de la bobina y el capacitor en circuitos DC.
      - Verificar el comportamiento de la bobina y el capacitor en circuitos AC.
      - Verificar las combinaciones serie y paralelo de bobinas y capacitores. 
      - Familiarizarse con el uso de los simuladores e instrumentos de dicho simulador. 
     
     

    
# 2. Marco Teórico

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Inductor%20y%20Capacitor.PNG)

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/TablaLab7.PNG)
![](https://github.com/mjvilla1/ImagenesLab7/blob/main/TablaLab7.1.PNG)

# 3. Explicación  del procedimiento

En esta práctica vamos a plasmar los diagramas en un simulador de circuitos eléctricos con el fin de poder realizar mediciones de Voltaje y corriente en distintos puntos del circutio.

Por lo cual hacemos las representaciones del diagrama ubicando los valores correspondientes de los elementos que tenemos en el circuito.

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Diagrama%20condensadores.jpeg)

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Capacitor.jpeg)

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Diagrama%20inductores.jpeg)

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Conexion%20de%20nductor.jpeg)

Con los circuitos ya hechos procedemos a dar inicio a la práctica por lo cual variaremos el valor de la frecuencia en la fuente de voltaje y el resto se mantendra intacto, al variar la frecuencia debemos mover las perillas en el oscilloscopio hasta encontrar una curva idónea para analizar su movimiento ya que con el cambio de frecuencia el periodo sera distinto por lo que los dos terminos son inversamente proporcionales, moviendo el tiempo en el cual podemos encontrar la onda busaremos con cada cambio de frecuencia el valor de voltaje pico el cual sera el valor más grande que se pueda observar en las ondas mostradas por el oscilloscopio, también mediremos el valor del voltaje con un multímetro convencional en el mimso punto  y el amperaje se lo medira en la resistencia propuesta por el ejercicio, anotamos los valores mostracos y proseguimos con su análisis


#  4. Respuestas 

A continuación se procede a poner en la tabla los resultados obtenidos

Tabla de circuito con condensadores.

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Tabla%20de%20datos%20circuito%20con%20con%20capacitores.jpeg)

Tabla de circuito con inductores.

![](https://github.com/mjvilla1/ImagenesLab7/blob/main/Tabla%20de%20datos%20de%20circuitos%20con%20inductores%20.jpeg)

Analizando los valores de voltajes podemos decir  que el valor de voltaje con cada tipo de frecuencia siempre varia ya puede ser de menos a mas o de mas a menos dependiendo del componente que tengamos, la diferencia se encuentra que en el caso de tener inductancia presente en el circuito al tener el valor de 0H como frecuencia empieza n un valor mas alto el cual decae con la subida de la frecuencia y con capacitancia no tendremos el maximo valor con un valor de 0H de frecuencia.



Respuestas a Interrogantes

## ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

La bobina actúa de forma diferente a un capacitor , la bobina deja pasar corriente debido a que las bobinas son cables enrollados que solo conducen más no poseen voltaje debido a que las bobinas en corriente directa actúan como corto circuto.

El capacitor actúa como circuito abierto en corriente continua , en un circuito tomando en cuenta en corriente continua se puede entender un capacitor como un circuito abierto,
no deja pasar corriente (por lo que no hay presencia de intensidad) sin embargo esta la presencia de voltaje debido a que en el condensador posee una reactancia


## ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

Bobinas en AC

Cuando las bobinas son sometidas a corriente con frecuencia (A.C.), cumplen su función de inductancia, es decir además de poseer corriente esta también tiene la presencia de voltaje, debido al efecto de frecuencia.
Las bobinas se pueden utilizar para “Adelantar voltaje y retrasar corriente”, dependiendo de cómo se utiliza para mejorar el factor de potencia.

Capacitores en AC

En este caso, sucede todo lo contrario: el capacitor deja pasar corriente, y tiene la presencia del voltaje, todo debido al efecto que tiene la corriente alterna en el elemento. 
Los condensadores se utilizan para “Adelantar corriente y atrasar voltaje”, dependiendo para mejorar el factor de potencia.


## ¿Qué cree usted que ocurriría con el voltaje y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

Al colocar dos capacitores o dos bobinas de diferente valor en elcircuito, se facilita los cálculos al momento de encontrar el valor de Vo porque podemos reducir el circuito a su mínima expresión usando el concepto de fasores,en los cuales a las impedancias y a las inductancias las convertimos al dominio fasorial y se representaría como una caja en el circuito a la cual podemos reducirle por el concepto de serie y paralelo.

## ¿Qué son los valores eficaces de voltaje y corriente?

Se llama valor eficaz de una corriente alterna, al valor que tendría una corriente continua que produjera la misma potencia que dicha corriente alterna, al aplicar la sobre una misma resistencia.Es decir, el valor RMS es el valor del voltaje o corriente en CA que produce el mismo efecto de calentamiento de la onda seno que su equivalente de voltaje o corriente directa.

# 5. Video

https://youtu.be/4WXK7w9LT3Y

# 6. Conclusiones

- Es posible representar la impedancia para cada una de las frecuencias asociadas en los  dos  circuitos  como  un  número  complejo  donde  predomina  en  un  caso  la
 impedancia capacitiva y en el otro caso la impedancia inductiva Z =R +j(Xl - Xc).
- Utilizar la impedancia Z nos permite realizar cálculos utilizando la ley de ohm para los cálculos.
- El valor de la caída de tensión medida con el multímetro corresponde al valor eficaz de la caída de tensión media con el osciloscopio. 
- Mientras mayor sea la frecuencia la impedancia capacitiva será menor.
- Mientras mayor sea la frecuencia la impedancia inductiva será mayor.
 

# 7. Bibliografía 

Robbins, A. H. (2008). Análisis de Circuitos Teoria y Practica. Santa Fe-Mexico: Cengage Learning.
