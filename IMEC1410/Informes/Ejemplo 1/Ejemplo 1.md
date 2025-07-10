# **DUREZA A DIFERENTES ESCALAS**

Mariana González Puentes, 202311308

### **RESUMEN**

El presente informa busca reportar los resultados de las pruebas de dureza por penetración realizados sobre muestras metálicas, poliméricas y cerámicas a diversas escalas según el material. Esta práctica se realizó con el fin de identificar las diferentes escalas de dureza, junto con sus diferentes ordenes de magnitud para reconocer cual es mejor utilizar según el material al que se le desea conocer la dureza. Posterior a la práctica se encontró que la dureza de los materiales de mayor a menor es: vidrio templado, acero 4340, aluminio 6063 y poliestireno de alto impacto. De igual forma, se generó la relación del porque la escala Brinell no puede ser convertida a cualquier otra escala.

## **INTRODUCCIÓN**

El presente informe tiene como objetivo principal comparar la dureza de dos metales, un polímero y un cerámico, mediante diferentes métodos de medición de dureza (Rockwell, Vickers, Shore y Brinell), además de la conversión de las durezas a las demás escalas. De este modo, se puede identificar cuál de las escalas es la más adecuada para tener un valor acertado de la dureza de un material.

El reconocimiento de la dureza de un material permite asociar esta característica a las propiedades mecánicas del material, tales como el esfuerzo último y el módulo de Young; por lo que una medida correcta de la dureza de un material, no importa la escala, permite obtener la información necesaria para escoger un material según la aplicación a la que se le desea someter. De igual forma, los diversos ordenes de magnitud encontrados de la dureza según el material permite relacionar de mejor forma esta característica con las propiedades mecánicas de cada uno. En este laboratorio se realizaron 4 pruebas de dureza: Rockwell, Vickers, Shore y Brinell, bajo las normas ASTM E18 para materiales metálicos, ASTM C1327 para materiales cerámicos, ASTM D2240 para cauchos y ASTM E10 para materiales metálicos, respectivamente. A partir de los resultados encontrados de las pruebas se van a comparar las diferentes durezas de cada material al pasarlas a una misma escala, exceptuando por los valores obtenidos en SHORE D.

A continuación se presentan los conceptos y fórmulas utilizados en el ensayo, según [1] [2] [3] y [4]:

En primera instancia es importante reconocer que la dureza de un material hace referencia a la resistencia de este a la deformación plástica permanente. Esta se puede medir a partir de una prueba de penetración con un indentador al material, según la prueba cambia tanto la geometría como el tamaño del indentador.

La prueba de dureza Rockwell se utiliza para materiales metálicos, al permitir medir las macro durezas de estos. Esta prueba cuenta con diferentes escalas (A-K) cada una de estas cuenta con una combinación diferente de geometría y carga aplicada. Sus posibilidades de geometría son: esfera de 1/16 de pulgada o 1/8 de pulgada y un diamante; para las cargas aplicadas se tiene una posibilidad de 60, 100 o 150Kgf. Por otro lado, la prueba Vickers permite medir las micro durezas de un material, especialmente materiales muy duros, por lo que se utiliza con mayor frecuencia en materiales cerámicos. Esta prueba se realiza con un indentador de diamante de 136º, el cual deja una huella en forma de rombo, a partir del cual se toman las dimensiones de las diagonales y se calcula la dureza del material.

Ahora bien, la escala Shore se utiliza comúnmente para polímeros, esta se realiza una aguja que ingresa al material a una fuerza constante y se obtiene la dureza de este. Esta prueba constata de 9 escalas, y puede realizarse tanto de forma manual como en un equipo, del cual se obtiene un resultado más preciso y confiable al ejercer una fuerza constante. Finalmente, la escala Brinell también se utiliza para materiales metálicos, mediante un indentador en forma esférica de 10mm de acero o de carbono de tungsteno de 2.5 mm o 5 mm; y se aplica una carga que puede oscilar entre los 5Kgf a 125 Kgf por 10 segundos.

Durante este ensayo no se calcularon manualmente las durezas de las escalas Rockwell, Shore y Brinell, dado que los equipos utilizados presentaban esta información, por ende las fórmulas para encontrar las durezas no fueron utilizadas, sin embargo en la ecuación ( 1 ) se presenta la como encontrar la dureza según el ensayo Brinell, donde P es la carga aplicada en Kgf, D es el diámetro de la esfera en mm y d es el diámetro de la huella que dejo el indentador en el material. De igual forma, la ecuación ( 2 ) presenta como encontrar la dureza en Vickers, donde P es la carga aplicada en Kgf y d<sup>1</sup> es la diagonal de la huella en forma de rombo.

$$
HB = \frac{2P}{\pi D \left[ D - \sqrt{D^2 - d^2} \right]} \tag{1}
$$

$$
HV = 1.854P/{d_1}^2 \tag{2}
$$

Aunque no se calculen las durezas según las escalas, se convierten los valores entre escalas, esto utilizando la norma ASTM E140, la cual contiene tablas que muestran la relación entre los valores de dureza de las escalas.

Ahora bien, para reportar correctamente todos los valores, tanto de los valores de dureza obtenidos como los diámetros de huella medidos, es necesario encontrar las incertidumbres de cada valor; para esto se debe tener en cuenta que existentes dos tipos de errores que van a estar asociados a cada medida, el error sistemático y el error aleatorio. Para encontrar los errores asociados a las medidas del diámetro y las durezas de los materiales se utilizan las ecuaciones ( 3 ), ( 4 ) y ( 5 ). Donde la ecuación para el error aleatorio es una función de Excel, a la cual se le ingresan por parámetros: alfa, el cual es el intervalo de confianza que se desea, la desviación estándar y el número de muestras tomadas.

á = ó ( 3 )

.

= . . (, , )

$$
Error\ total = \sqrt{E_{sis}^2 + E_{ale}^2} \tag{5}
$$

( 4 )

### **Objetivos**

- Conocer e identificar las diferentes escalas de dureza (normas, medición, reporte y análisis) y la instrumentación utilizada en cada una
- Establecer los criterios para la selección del método, su utilidad y la escala adecuada para determinar la dureza en las distintas familias de materiales
- Familiarizar al estudiante con los órdenes de magnitud en las pruebas de dureza para las distintas familias de materiales.

## **MÉTODO**

A continuación se explica el procedimiento seguido para este ensayo tomando en cuenta las normas ASTM E18 para materiales metálicos, ASTM C1327 para materiales cerámicos, ASTM D2240 para cauchos y ASTM E10 para materiales metálicos.

En primera instancia se va a describir el proceso de la prueba de dureza Rockwell a la cual fue sometida el acero 4340 en la escala C, dado que es un acero en alto carbono. En el figura 17 ubicada en el anexo se presentan las diferentes escalas Rockwell y la clasificación de estas según los materiales a los cuales se pueden someter. Esta prueba fue realizada en el Durómetro AFFRI 250 DRMC con un indentador con geometría de diamante a 120º

En primera medida antes de realizar las pruebas, el técnico de laboratorio debía realizar una verificación que los resultados que se estaban obteniendo eran acordes a los establecidos por la norma, para no tener discrepancias con los valores de dureza que se iban a obtener. De igual forma se comprobó que la temperatura del laboratorio estuviera entre 10ºC y 35ºC, dado que la norma indica que si se realizan las pruebas a una temperatura fuera de este rango los valores que se obtendrían serían diferentes a los reales. Ahora bien, para empezar la prueba se configuró el equipo para utilizar la escala C y que realizara una pre carga de 10 Kg por 2 segundos y posterior a eso aplicara una carga de 150 Kg por 5 segundos, tal como es indicado en el apartado 7.4 de la norma. Después se ubicó el acero en el equipo de tal forma que estuviera completamente apoyado en la máquina y tuviera una ubicación perpendicular al indentador para que el contacto con este sea el correcto, tal como se indica en el apartado 7.5 y como se observa en la Figura 1.

![](_page_1_Picture_15.jpeg)

**Figura 1. Ubicación de la muestra de acero 4340 en el equipo**

Una vez se contaba con la ubicación correcta de la muestra se inició la prueba, y el equipo empezó a aplicar la pre carga y la carga correspondiente. Durante este proceso se trató de no realizar ningún tipo de movimiento o vibración que pudiera afectar el resultado. Una vez se completó este proceso se tomaron los datos de dureza registrados en la máquina, tal como se puede ver en la figura 2. Este procedimiento se realizó 5 veces, para no obtener valores de dureza más elevados de los reales las nuevas indentaciones se ubicaron de tal forma que la distancia entre los centros de las dos indentaciones fueran al menos 3 veces el diámetro del indentador, tal como se especifica en el apartado 7.9 .

![](_page_1_Picture_18.jpeg)

**Figura 2. Formato de presentación de resultados de Rockwell C**

En segunda instancia se va a describir el proceso de la prueba de dureza Vickers aplicada sobre el vidrio arquitectónico, y para la cual fue utilizado el Microdurómetro BUEHLER MICROMET 5104 y un indentador con geometría de pirámide de diamante con 4 caras (136º). La norma ASTM C1327 indica

Formato Unificado de Informes de Laboratorio. Versión 1.0

que antes de la prueba se debe ubicar la muestra de tal forma que no se pueda balancear ni mover durante el ensayo y este ubicada perpendicularmente al indentador, de igual forma esta debe estar completamente limpia dado que al ser una medida de microdureza cualquier tipo de suciedad puede afectar los resultados. Según el apartado 10.2 si se identifica que el indentador deja diagonales asimétricas debe girar la probeta 90º y se realizar otra indentación. Antes de iniciar la prueba se debe configurar el equipo para que aplique 1 Kgf, no se puede aplicar más de esta carga porque se pueden empezar a formar gritas que invalidan los resultados que se obtengan. Ahora bien, durante la prueba se debe iniciar el equipo de forma lenta para que la velocidad de contacto entre el indentador y la muestra sea entre 0.015 y 0.070 mm/s y la aplicación de la carga debe ser durante 15 segundos. Una vez se realiza el procedimiento se debe observar la forma de la indentación si es acorde a lo aceptado por la norma, como se puede ver en la figura 3, se registran los datos y se toman las pruebas restantes, de lo contrario esta indentación es errada y no se puede tomar en cuenta para los valores de dureza. Para realizar los cálculos de dureza de esta prueba, la norma indica en el apartado 10.2 que se debe utilizar la ecuación ( 2 ) para luego ser registrados.

![](_page_2_Figure_1.jpeg)

**Figura 3. Indentaciones aceptadas y no aceptadas de la prueba Vickers. Fuente [3]**

En tercera instancia se va a describir el proceso de la prueba de dureza Shore, llevada a cabo sobre poliestireno de alto impacto, un material con características de goma dura y que pertenece a la familia de los termoplásticos, por lo que se utilizó la escala D para conocer su dureza; esta escala se escogió acorde a la norma ASTM D2240, en la figura 18 en el anexo se puede ver la tabla donde la norma específica la escala según el material. Esta prueba se realizó con el Durómetro ZWICK 3131 con un indentador en forma de aguja según la norma. Antes de iniciar la prueba, como es especificado en el apartado 8 de la norma se verificaron las condiciones de humedad y temperatura de la prueba para no obtener valores errados si estas no están dentro de las condiciones estándar de un laboratorio como es

especificado en la norma ASTM D618. Con objetivos pragmáticos primero se realizó la prueba Shore de forma manual con el durómetro para después evaluar cómo cambian los resultados al hacerlo manual y al hacerlo con el equipo, gracias al cual se aplica una carga constante. Para empezar con la prueba se ajustaron los prénsatelas a la superficie de contacto de la muestra a una distancia de 25,4 6 2,5 mm como es indicado en el apartado 9.1; después el técnico de laboratorio activo el equipo permitiendo que el indentador del durómetro descendiera y entrara en contacto con el poliestireno, se estaba aplicando una fuerza de 50N, como indica la norma, a una velocidad constante. Se prosiguió registrando los resultados de dureza obtenidos, estos fueron los valores máximos obtenidos, dado que la aguja marca un valor máximo y luego tiene a estabilizarse en un punto más bajo. Se realizaron 5 mediciones las cuales estaban a 6 mm de distancia, como indica el apartado 9.1.8, para no tener valores errados.

En cuarto instancia se va a describir el proceso de la prueba de dureza Brinell, llevada a cabo sobre el Aluminio 6063, con el Durómetro AFFRI 250 DRMC y con un indentador de carburo de tungsteno en forma esférica y con un diámetro de 2.5 mm. Antes de comenzar la prueba se debía realizar una confirmación que la máquina si este dando los resultados correctos de dureza, una vez se cumplía con esto se podía comenzar con el procedimiento. Para este se acercó el indentador a la superficie de la muestra de tal forma que pudieran tener un contacto perpendicular, una vez estaba ubicado de manera adecuada se configuró el equipo para que se aplicara una fuerza de 62.5 Kgf por 10 segundos, después de aplicar la carga se tomaron los resultados de dureza. Para conocer las medidas de los diámetros finales de la indentación se llevó la muestra a un microscopio para poder calcular estas medidas en un programa especial, tal como se puede observar en la figura 4, y de igual forma estos resultados se registraron.

![](_page_2_Figure_6.jpeg)

**Figura 4. Indentación Brinell bajo el microscopio y los resultados de diámetro y dureza.**

Finalmente, se va a explicar cómo fue el procesamiento de todos los datos para encontrar las durezas y las incertidumbres de estas.

Primero para la dureza Rockwell, Vickers y Shore se registraron los datos de dureza, y luego se sacó el promedio y la

Formato Unificado de Informes de Laboratorio. Versión 1.0

desviación estándar de estos. Con estos datos se calculó la incertidumbre con las ecuaciones ( 3 ), ( 4 ) y ( 5 ), este procedimiento se puede ver en la figura 5.

| Indentación         | Dureza [HRC] |            |  |
|---------------------|--------------|------------|--|
|                     | 26,1         |            |  |
|                     | 27,9         | Resolucion |  |
|                     | 25,7         | 0,1        |  |
|                     | 29,1         | Alpha      |  |
|                     | 29,1         | 0,05       |  |
| Promedio            | 27,58        | Aleatorio  |  |
| Desciación estándar | 1,616168308  | 1,41660795 |  |
| Error asociado      | 1,420133123  |            |  |

**Figura 5. Proceso realizado para calcular la incertidumbre de Rockwell**

Para la dureza Brinell se realizó el mismo procedimiento, pero adicionalmente se calculó la incertidumbre del diámetro de la huella de la indentación, tal como se ve en la figura 6.

| resolucion dureza   | 0,1                                    |            | alpha | 0.05 |
|---------------------|----------------------------------------|------------|-------|------|
| resolucion huella   | 0,00001                                |            |       |      |
|                     |                                        |            |       |      |
| aleatorio dureza    | 3,047728241                            |            |       |      |
| aleatorio huella    | 0,015867407                            |            |       |      |
|                     |                                        |            |       |      |
| Indentación         | Diámetro huella [mm] Dureza [HBW/62.5] |            |       |      |
|                     | 0,9413                                 | 86,5       |       |      |
| $\overline{2}$      | 0,9419                                 | 86,4       |       |      |
| 3                   | 0,9386                                 | 87         |       |      |
| 4                   | 0,9749                                 | 80,4       |       |      |
| 5                   | 0.9262                                 | 80,2       |       |      |
| Promedio            | 0.94458                                | 84.1       |       |      |
| Desviación estándar | 0.018102679                            | 3,47706773 |       |      |
| Error asociado      | 0                                      | 0          |       |      |

**Figura 6. Proceso realizado para calcular la incertidumbre de Brinell**

Una vez se contaba con todos los resultados de dureza se convirtió cada valor obtenido a otra escala para tener un mejor entendimiento de la diferencia de durezas entre los diversos materiales probados. De igual forma, se realizó la ilustración de los indentadores utilizados según cada prueba. Todos estos valores son reportados en la sección de resultados.

## **RESULTADOS**

A continuación se presentan los resultados obtenidos de cada prueba de dureza realizada a diferentes escalas.

| Prueba de dureza Rocwell |                   |                                                    |                           |  |
|--------------------------|-------------------|----------------------------------------------------|---------------------------|--|
| Temperatura [ºC]         | 21.1              | Humedad [%]<br>49                                  |                           |  |
| Material                 | <b>Acero 4340</b> | Tiempo de aplicación [s]                           | 5                         |  |
| Escalas                  |                   | Indentador                                         | Diamante 120 <sup>o</sup> |  |
| Indentación              | Dureza [HRC]      | Observaciones                                      |                           |  |
|                          | 26,1              |                                                    |                           |  |
| 2                        | 27.9              | Para esta prueba de dureza se aplicó una pre-      |                           |  |
| 3                        | 25,7              | carga de 10 Kgf por 2 segundos, esto para poder    |                           |  |
| 4                        | 29,1              | medir la dureza del material y no obtener errores  |                           |  |
| 5                        | 29,1              | por la superficie del material. Posterior a eso se |                           |  |
| Promedio                 | 27,58             | aplicó una carga de 150 Kgf por 5 segundos. - El   |                           |  |
| Desciación estándar      | 1,616168308       | equipo mide el recorrido lienal del penetrador     |                           |  |
| Error asociado           | 1.420133123       | sobre el material                                  |                           |  |

**Figura 7. Resultados de la prueba de dureza Rockwell C**

En la figura 7 se presentan los resultados del ensayo de dureza Rockwell C, junto con su incertidumbre y observaciones notadas a lo largo de la toma de datos.

![](_page_3_Picture_12.jpeg)

**Figura 8. Muestra del acero 4340 luego de ser sometido a la prueba de dureza.**

En la figura 8 se pueden identificar las huellas que deja el indentador después de aplicar la fuerza.

![](_page_3_Figure_15.jpeg)

## **Figura 9. Ilustración del indentador utilizado para la escala Rockwell C**

En la figura 9 se evidencia el indentador utilizado para para la escala Rockwell C, el cual contaba con una geometría de diamante de 120º.

| Prueba de dureza Vickers |                       |                    |                          |                                |
|--------------------------|-----------------------|--------------------|--------------------------|--------------------------------|
| Temperatura [ºC]         | 21.1                  |                    | Humedad [%]              | 49                             |
| Material                 | Vidrio arquitectónico |                    | Tiempo de aplicación [s] | 15                             |
| Carga [Kgf]              | 0.3                   |                    | Indentador               | Pirámide diamante 136º         |
| Indentación              | Diagonal 1, d [mm]    | Diagonal 2, d [mm] | Dureza [HV]              | Observaciones                  |
|                          | 32,63                 | 32.9               | 518,1                    | El vidrio arquitectónico usado |
|                          | 32,46                 | 32,59              | 525,9                    | no tenia ningún tipo de        |
| з                        | 32,95                 | 33,13              | 509.5                    | tratamiento térmico. Para      |
| Δ                        | 33,45                 | 32,72              | 508,3                    | tomar mejor las medidas de     |
| 5                        | 32,87                 | 32,95              | 513,7                    | las huellas dejadas por el     |
| Promedio                 | 32,872                | 32,858             | 515.1                    | intentador se rota 90º. El     |
| Desciación estándar      | 0.376988063           | 0.20921281         | 6.406246951              | indentador deja una huella en  |
| Error asociado           | 0,330589815           | 0.1836522          | 5,615228758              | forma de rombo                 |

**Figura 10. Resultados de la prueba de dureza Vickers**

En la figura 10 se presentan los resultados del ensayo de dureza Vickers, junto con su incertidumbre y observaciones notadas a lo largo de la toma de datos.

Formato Unificado de Informes de Laboratorio. Versión 1.0 Documento controlado. Aprobado por el Consejo del Departamento de Ingeniería Mecánica el 10 de junio de 2016

![](_page_4_Picture_0.jpeg)

**Figura 11. Muestra del Vidrio arquitectónico con la huella dejada por el indentador** 

En la figura 11 se pueden identificar la huella dejada por el indentador después de aplicar la fuerza, esta tiene una geometría de rombo.

![](_page_4_Figure_3.jpeg)

**Figura 12. Ilustración del indentador utilizado para la escala Vickers**

| Prueba de dureza Shore |                              |            |                         |  |
|------------------------|------------------------------|------------|-------------------------|--|
| Temperatura [ºC]       | Humedad [%]<br>21.1          |            | 49                      |  |
| Material               | Poliestireno de alto impacto |            |                         |  |
| Carga [N]              | 50                           | D          |                         |  |
| Indentación            | Dureza [HS]                  | Tiempo [S] | Observaciones           |  |
|                        | 79,4                         | $<$ 1      |                         |  |
| 2                      | 77,4                         | <1         | Esta medida no fue      |  |
| 3                      | 77,4                         | <1         | tomada con              |  |
| 4                      | 78,4                         | $<$ 1      | esclerómetro. La escala |  |
| 5                      | 78,3                         | $<$ 1      | D se usa para           |  |
| Promedio               | 78,18                        | $<$ 1      | materiales duros        |  |
| Desviación estándar    | 0,831865374                  | 0          | (termoplásticos)        |  |
| Error asociado         | 0,735974117                  | n          |                         |  |

**Figura 13. Resultados de la prueba de dureza Shore D**

En la figura 13 se presentan los resultados del ensayo de dureza Shore, junto con su incertidumbre y observaciones notadas a lo largo de la toma de datos.

![](_page_4_Figure_8.jpeg)

**Figura 14. Ilustración del indentador utilizado para la escala Shore D**

| Prueba de dureza Brinell                                  |                                        |                          |                       |  |
|-----------------------------------------------------------|----------------------------------------|--------------------------|-----------------------|--|
| Temperatura [ºC]                                          | 21.1                                   | Humedad [%]              | 49                    |  |
| Material                                                  | Aluminio 6063                          | Tiempo de aplicación [S] | 10                    |  |
| Carga [Kgf]                                               | 62.5                                   | Indentador               | $2,5$ [mm]            |  |
| Indentación                                               | Diámetro huella [mm] Dureza [HBW/62.5] |                          | <b>Observaciones</b>  |  |
|                                                           | 0,9413                                 | 86,5                     |                       |  |
| $\overline{2}$                                            | 0.9419                                 | 86,4                     |                       |  |
| 3                                                         | 0,9386                                 | 87                       | El material del       |  |
| 4                                                         | 0,9749                                 | 80,4                     | indentador es carburo |  |
| 5                                                         | 0,9262                                 | 80,2                     | de tungsteno.         |  |
| Promedio                                                  | 0,94458                                | 84,1                     |                       |  |
| Desviación estándar                                       | 0,018102679                            | 3,47706773               |                       |  |
| Error asociado                                            | 0.01586741                             | 3.049368365              |                       |  |
| Desultados de la nouveles de durante Dobelli<br>医眼神经病 计图片 |                                        |                          |                       |  |

**Figura 15. Resultados de la prueba de dureza Brinell**

En la figura 15 se presentan los resultados del ensayo de dureza Brinell, junto con su incertidumbre y observaciones notadas a lo largo de la toma de datos.

![](_page_4_Figure_14.jpeg)

**Figura 16. Ilustración del indentador utilizado para la escala Brinell**

En la figura 19 ubicada en el anexo se reportan las durezas obtenidas en diferentes escalas, esta conversión se realizó con la norma ASTM E140.

# **DISCUSIÓN**

Con base a los resultados obtenidos en las diversas pruebas de dureza se logran identificar los valores correctos de dureza de

Formato Unificado de Informes de Laboratorio. Versión 1.0 Documento controlado. Aprobado por el Consejo del Departamento de Ingeniería Mecánica el 10 de junio de 2016 cada material. Para la prueba Brinell, tal como se muestra en la figura 15 se obtiene un resultado promedio de 84.1 [HBW/62.5] este valor es acorde a la literatura dado que la dureza del aluminio 6063 es de 82 [HB], esto según la guía ASM Handbook de aleaciones [9]. Por ende el valor que se obtuvo está dentro de un rango acorde a la literatura al tener una incertidumbre de +/- 3.05; esto indica que las condiciones ambientales a las cuales se realizó la prueba no variaron el resultado de la dureza. De igual forma este resultado muestra que este aluminio es un metal de baja dureza, dado que al ser comparado con otras escalas tiene un equivalente muy bajo de dureza. Esta característica se puede relacionar con las propiedades mecánicas tales como el módulo de Young y el esfuerzo de fluencia, dado que este último también es un indicador de la resistencia del material a la deformación plástica, por lo que son proporcionales [6]. Según la guías ASM los aluminios 6063, que cuentan con una dureza de 82 [HB] tienen un esfuerzo de fluencia de 241 [MPa] estos valores indican que el material tiene un bajo número de imperfecciones por lo que las dislocaciones se pueden mover con mayor facilidad, esto implica que se requiere aplicar una baja cantidad fuerza para llegar a la deformación plástica.

Para el acero 4340 se obtuvo una dureza promedio de 27.58 [HRC] este valor es similar al registrado en la literatura el cual está en un rango de 24 a 30 [HRC]según el Handbook ASM [10]. Al momento de comparar la dureza con la escala Brinell se identifica que se tiene un alto valor de dureza a comparación del aluminio 6063, esto se debe a que el acero es un metal altamente contenido de carbono, por lo que al tener enlaces iónicos se tiene una red cristalina más resistente, y la dureza aumenta al impedir que las dislocaciones se muevan con facilidad por la red [12] . Por esto mismo, el acero 4340 cuenta con un elevado esfuerzo de fluencia, el cual tiene un valor que oscila entre los 740 y los 860 [MPa].

Por otro lado, para el poliestireno de alto impacto se obtuvo un valor de dureza de 78.18 SHORE D con una incertidumbre de +/- 0.73, el valor obtenido no está alejado del valor de la literatura, el cual oscila entre 60 y 75 Shore D, según el Handbook ASM volumen 11b [11], sin embargo no entra dentro del rango de este al contar con una incertidumbre menor a la diferencia de valores a la dureza del material. Al momento de hacer la relación con el esfuerzo de fluencia se encuentra que este tiene un valor aproximado de 10.3 [MPa], este siendo un valor mucho menor al de los metales. Ahora bien, es importante tener en cuenta que los polímeros no cuentan con una zona de deformación plástica, y que su esfuerzo de fluencia es su mismo esfuerzo último. Esto se debe a que su esfuerzo de Peierls-Navarro (esfuerzo necesario para mover una dislocación) es mayor al esfuerzo de fluencia, por lo que el material llega a la fractura antes de deformarse, y por ende ninguna dislocación se mueve y el material tiene una baja dureza. [12]

Asimismo, para el vidrio arquitectónico se obtuvo una dureza promedio de 515.1[HV0.3] con una incertidumbre de +/- 5.6, resultado que está dentro de los rangos de la literatura dado que en una caracterización de vidrio arquitectónico [13] se obtiene una dureza de 540 [HV1] la pequeña discrepancia entre los valores de dureza se puede dar gracias a que en la

caracterización se estaba realizando sobre la muestra una fuerza de 1 Kgf, mientras que en la prueba de dureza realizada en la universidad se aplicó una fuerza de 0.3 Kgf, por lo cual la fuerza que se destina a mover las dislocaciones del material son diferentes, lo que puede dar cambios en los valores de dureza. Al momento de hacer una relación con el esfuerzo de fluencia y el módulo de Young se puede analizar que al ser un material muy duro va a tener un elevado esfuerzo de fluencia y esfuerzo último, debido a que se necesita una mayor carga para mover las dislocaciones. Es importante tener en cuenta que los cerámicos no cuentan con zona de deformación plástica, por lo que aunque son materiales muy duros una vez lleguen al esfuerzo de fluencia se van a fracturar gracias a las grietas que se van formando sobre estos al aplicarles fuerza.

Al momento de comparar las durezas entre los distintos materiales gracias a la figura 19, se identifica que entre los metales el acero es el que presenta mayor dureza, esto porque es un metal de alto carbono y sus enlaces generan una red cristalina más fuerte. Sin embargo, el vidrio arquitectónico (cerámico) es el material más duro de los cuatro probados; esto se puede dar dado que al ser un cerámico su estructura cristalina contiene átomos de dos diversos materiales, por lo que su estructura cristalina puede contener imperfecciones de sustitución de átomos, lo que genera una red más fuerte que dificulta el paso de las dislocaciones, y por ende el material es más duro.

Después de poder identificar cuáles son los valores de dureza según diversas escalas, se puede identificar que cada material tiene una diferente escala preseleccionada porque si se desea un valor más exacto no se puede seleccionar una escala muy general o una escala que no puede dar el valor de la dureza porque no está contenido en el rango. La escala Brinell es la escala más general de todas, dado que tiene un gran nivel de rango de la dureza, por eso es ideal para los materiales que tienen una dureza muy baja, tal como el aluminio 6063; el único impedimento que tiene esta escala es que no se puede pasar a la mayoría de las escalas según el rango, mientras que todas las escalas si se pueden pasar a Brinell, por lo que puede llegar a ser pensada como la escala universal. La escala Vickers al ser una escala de micro durezas es muy buena para medir la dureza de los materiales rígidos, por lo que es muy adecuada para medir esta característica del vidrio, ahora bien, para este también se puede usar la escala Brinell solo que esta no da una precisión tan buena como la Vickers. Finalmente, para el acero 4340 es ideal usar la escala Rockwell al ser un material alto en carbono y de los más duros, pues se puede obtener la dureza más específica en lugar de utilizar Brinell.

### **CONCLUSIONES**

Luego de realizar las pruebas de dureza a diferentes materiales en diferentes escalas, se logró caracterizar adecuadamente la resistencia a la deformación plástica de cada uno de ellos. Los resultados obtenidos y la conversión de estos a distintas escalas permitió identificar que método es el más indicado acorde al material, además de las proporciones en los órdenes de magnitud de las escalas. Gracias a los resultados se

Formato Unificado de Informes de Laboratorio. Versión 1.0

identificó que el material más duro fue el vidrio templado, seguido por el acero y al aluminio y finalmente el poliestireno, además se analizó que las propiedades mecánicas relacionadas a la dureza y esta característica son directamente proporcionales. Dado a que las variaciones en los resultados fueron mínimas y estas fueron muy cercanas a los valores de la literatura, se puede concluir que los procedimientos seguidos fueron los correctos y no incumplieron lo estipulado por las normas usadas.

## **BIBLIOGRAFÍA**

- [1] ASTM International, ASTM E18-05 Standard Test Method for Rockwell Hardness and Rockwell Superficial Hardness of Metalic Materials.
- [2] ASTM International, ASTM E10-07 Standard Test Method for Brinell Hardness of Metallic Materials.
- [3] ASTM International, ASTM C1327-03 Standard Test Method for Vickers Indentation Hardness of Advanced Ceramics.
- [4] ASTM International, ASTM D2240-05 Standard Test Method for Rubber Property—Durometer Hardness.
- [5] ASTM International, ASTM E140 12b Standard Hardness Conversion Tables for Metals Relationship Among Brinell Hardness, Vickers Hardness, Rockwell Hardness, Superficial Hardness, Knoop Hardness, Scleroscope Hardness, and Leeb Hardness.
- [6] W.F. Smith, J.Hashemi, y F.Presuel-Moreno, *Foundations of materials science and engineering*, Sixth edition. New York, NY: McGraw-Hill Education, 2019.
- [7] W.D. Callister y D.G. Rethwisch, *Fundamentals of Materials Sciencie and Engineering: An integrated Aproach*, Fifth Edition. Wiley, 2015.
- [8] M.F.Ashby, H. Shercliff y D. Cebon, *Materials: Engineering, science processing and design,* Fourth edition. Butterworth-Heinemann, 2019.
- [9] ASM International, *ASM Handbook, Volume 2: Properties and Selection: Nonferrous Alloys and Special-Purpose Materials*, 10th ed. Materials Park, OH, USA: ASM International, 1990.
- [10] J. R. Davis, Ed., *ASM Handbook, Desk Edition: Metals and Alloys*. Materials Park, OH, USA: ASM International, 1998.
- [11] T. J. Menna, Ed., *ASM Handbook, Volume 11B: Characterization and Failure Analysis of Plastics*, ASM International, 2022.
- [12] Jairo Escobar, "Imperfecciones",Ciencia de materiales, Universidad de los Andes, Febrero 26 de 2025.
- [13] A. Ortega García, "Análisis de las propiedades mecánicas del vidrio arquitectónico a escala nanométrica y macrométrica," Tesis de Maestría,

Universidad Autónoma de Chihuahua, México, 2021. [En línea]. Disponible en: [http://repositorio.uach.mx/441/1/TESIS%20Analisis%2](http://repositorio.uach.mx/441/1/TESIS%20Analisis%20de%20la%20Propiedades%20Mecanicas%20del%20Vidrio%20Arquitectonico%20-%20con%20Firmas.pdf) [0de%20la%20Propiedades%20Mecanicas%20del%20V](http://repositorio.uach.mx/441/1/TESIS%20Analisis%20de%20la%20Propiedades%20Mecanicas%20del%20Vidrio%20Arquitectonico%20-%20con%20Firmas.pdf) [idrio%20Arquitectonico%20-%20con%20Firmas.pdf](http://repositorio.uach.mx/441/1/TESIS%20Analisis%20de%20la%20Propiedades%20Mecanicas%20del%20Vidrio%20Arquitectonico%20-%20con%20Firmas.pdf)

# **ANEXO A**

| <b>TABLE 1 Rockwell Hardness Scales</b> |  |
|-----------------------------------------|--|
|-----------------------------------------|--|

| Scale<br>Symbol | Indenter                           | <b>Total Test</b><br>Force, kgf | Dial<br><b>Figures</b> | <b>Typical Applications of Scales</b>                                                                                          |  |  |
|-----------------|------------------------------------|---------------------------------|------------------------|--------------------------------------------------------------------------------------------------------------------------------|--|--|
| B               | $1/16$ -in. (1.588-mm) ball        | 100                             | red                    | Copper alloys, soft steels, aluminum alloys, malleable iron, etc.                                                              |  |  |
| С               | diamond                            | 150                             | black                  | Steel, hard cast irons, pearlitic malleable iron, titanium, deep case hardened steel, and other<br>materials harder than B100. |  |  |
| A               | diamond                            | 60                              | black                  | Cemented carbides, thin steel, and shallow case-hardened steel.                                                                |  |  |
| D               | diamond                            | 100                             | black                  | Thin steel and medium case hardened steel, and pearlitic malleable iron.                                                       |  |  |
| E               | $\frac{1}{8}$ -in. (3.175-mm) ball | 100                             | red                    | Cast iron, aluminum and magnesium alloys, bearing metals.                                                                      |  |  |
| F               | $1/16$ -in. (1.588-mm) ball        | 60                              | red                    | Annealed copper alloys, thin soft sheet metals.                                                                                |  |  |
| G               | $1/16$ -in. (1.588-mm) ball        | 150                             | red                    | Malleable irons, copper-nickel-zinc and cupro-nickel alloys. Upper limit G92 to avoid possible<br>flattening of ball.          |  |  |
| Н               | 1/8-in. (3.175-mm) ball            | 60                              | red                    | Aluminum, zinc, lead.                                                                                                          |  |  |
|                 | $\frac{1}{8}$ -in. (3.175-mm) ball | 150                             | red                    |                                                                                                                                |  |  |
|                 | $1/4$ -in. (6.350-mm) ball         | 60                              | red                    |                                                                                                                                |  |  |
| м               | $1/4$ -in. (6.350-mm) ball         | 100                             | red                    | Bearing metals and other very soft or thin materials. Use smallest ball and heaviest load that does                            |  |  |
| P               | $1/4$ -in. (6.350-mm) ball         | 150                             | red                    | not give anvil effect.                                                                                                         |  |  |
| R               | $1/2$ -in. (12.70-mm) ball         | 60                              | red                    |                                                                                                                                |  |  |
| S               | $1/2$ -in. (12.70-mm) ball         | 100                             | red                    |                                                                                                                                |  |  |
| ٧               | 1/2-in. (12.70-mm) ball            | 150                             | red                    |                                                                                                                                |  |  |

|  |  | Figura 17. Tabla con las escalas Rockwell según la norma ASTM E18 |  |  |
|--|--|-------------------------------------------------------------------|--|--|
|  |  |                                                                   |  |  |

| Type (Scale) | <b>Typical Examples of Materials Tested</b>                                 | <b>Durometer Hardness</b><br>(Typical Uses) |  |
|--------------|-----------------------------------------------------------------------------|---------------------------------------------|--|
| А            | Soft vulcanized rubber, natural rubber, nitriles, thermoplastic elastomers, | 20-90 A                                     |  |
|              | flexible polyacrylics and thermosets, wax, felt, and leathers               |                                             |  |
| в            | Moderately hard rubber, thermoplastic elastomers, paper products, and       | Above 90 A                                  |  |
|              | fibrous materials                                                           | Below 20 D                                  |  |
| С            | Medium-hard rubber, thermoplastic elastomers, medium-hard plastics, and     | Above 90 B                                  |  |
|              | thermoplastics                                                              | Below 20 D                                  |  |
| D            | Hard rubber, thermoplastic elastomers, harder plastics, and rigid           | Above 90 A                                  |  |
|              | thermoplastics                                                              |                                             |  |
| DO           | Moderately hard rubber, thermoplastic elastomers, and very dense textile    | Above 90 C                                  |  |
|              | windings                                                                    | Below 20 D                                  |  |
| М            | Thin, irregularly shaped rubber, thermoplastic elastomer, and plastic       | 20-85 A                                     |  |
|              | specimens                                                                   |                                             |  |
| O            | Soft rubber, thermoplastic elastomers, very soft plastics and               | Below 20 DO                                 |  |
|              | thermoplastics, medium-density textile windings                             |                                             |  |
| OO           | Extremely soft rubber, thermoplastic elastomers, sponge, extremely soft     | Below 20 O                                  |  |
|              | plastics and thermoplastics, foams, low-density textile windings, human     |                                             |  |
|              | and animal tissue                                                           |                                             |  |
| CF           | Composite foam materials, such as amusement ride safety cushions,           | See Test Method F1957                       |  |
|              | vehicle seats, dashboards, headrests, armrests, and door panels             |                                             |  |
|              |                                                                             |                                             |  |

Figura 18. Tabla con las escalas Shore según la norma ASTM D2240

| Material            |             | <b>Acero 4340</b>                             |             | Vidrio arquitectónico                        | Aluminio 6063        |                         |
|---------------------|-------------|-----------------------------------------------|-------------|----------------------------------------------|----------------------|-------------------------|
| Indentación         |             | Dureza Inicial [HRC] Dureza equivalente [HBW] |             | Dureza Inicial [HV] Dureza equivalente [HBW] | Dureza Inicial [HBW] | Dureza equivalente [HV] |
|                     | 26,1        | 258,6                                         | 518,1       | 486.1                                        | 86,5                 | 86,5                    |
|                     | 27,9        | 270,3                                         | 525,9       | 493,9                                        | 86,4                 | 86,4                    |
|                     | 25,7        | 256,5                                         | 509,5       | 478,2                                        | 87                   | 87                      |
|                     | 29,1        | 279,7                                         | 508,3       | 477,2                                        | 80,4                 | 80,4                    |
|                     | 29,1        | 279,2                                         | 513,7       | 481,7                                        | 80,2                 | 80,2                    |
| Promedio            | 27.58       | 268.86                                        | 515,1       | 483,42                                       | 84,1                 | 84,1                    |
| Desviación estándar | 1,616168308 | 11,00604379                                   | 7,162401832 | 6,817404198                                  | 3,47706773           | 3,47706773              |

Figura 19. Tabla con los resultados de las conversiones de dureza entre diferentes escalas.

Formato Unificado de Informes de Laboratorio. Versión 1.0