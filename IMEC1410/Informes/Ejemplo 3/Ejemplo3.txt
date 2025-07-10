# **ENSAYO DE DUREZA EN METALES, POLÍMEROS Y CERÁMICOS: APLICACIÓN DE LOS MÉTODOS ROCKWELL, BRINELL, VICKERS Y SHORE**

Claudia Alejandra Montero Peluffo, 202310675

#### **RESUMEN**

Se realizó un ensayo de dureza en metales, polímeros y cerámicos utilizando los métodos de indentación Rockwell, Brinell, Vickers y Shore, midiendo la dureza de cada material con cargas e indentadores específicos. Se registraron y analizaron los valores obtenidos, calculando conversiones entre escalas y determinando las incertidumbres asociadas. Los ensayos se realizaron según las normas ASTM correspondientes a cada método. Los resultados mostraron variaciones significativas según el material y el método empleado, confirmando que los metales presentan mayor dureza que los polímeros y cerámicos. Además, se concluyó que la selección del método es clave para obtener mediciones precisas y que las conversiones entre escalas deben aplicarse con precaución según el tipo de material.

#### **NOMENCLATURA**

- *d* Diámetro de la huella de indentación
- *D* Diámetro de la bola indentadora
- Deformación
- !"#! Error aleatorio
- \$%\$& Error sistemático
- & Error total o asociado
- *F* Fuerza aplicada
- *H* Dureza Shore
- *HBW* Dureza Brinell
- *HR* Dureza Rockwell
- *HV* Dureza Vickers
- Esfuerzo
- *t* Tiempo de aplicación de la carga

# **INTRODUCCIÓN**

La dureza es una propiedad mecánica fundamental utilizada en la ciencia e ingeniería de materiales para evaluar la resistencia a la deformación plástica o la penetración de un material cuando se le aplica una carga determinada. Existen distintos enfoques para medir la dureza, entre los cuales destacan los métodos de rayado, rebote y penetración. [4]

Existen tres tipos principales de ensayos de dureza. La dureza al rayado se mide utilizando la escala de Mohs, la cual clasifica los materiales en un rango de 1 a 10, donde 1 representa un material blando y 10 un material extremadamente duro. Esta prueba es esencialmente cualitativa y se basa en la resistencia que opone un material a ser rayado por otro más duro. No solo

mide la resistencia a ser rayado, sino también la capacidad de otro material para generar una indentación sobre su superficie. Es un método grueso y frecuentemente utilizado en la industria energética y geológica. [2]

La dureza al rebote, en cambio, mide la resistencia de un material al impacto, es decir, cuánta energía absorbe o transforma en deformación plástica. Se determina utilizando un esclerómetro o escleroscopio, los cuales evalúan la altura de rebote de un objeto tipo martillo sobre la superficie del material. Generalmente, materiales con baja energía de deformación plástica tienen una mayor altura de rebote. Este método es ampliamente utilizado en trabajos de campo debido a que es portátil, permite mediciones en geometrías complejas y se puede aplicar en superficies no horizontales. Sin embargo, presenta desventajas como la necesidad de un montaje especial para piezas con masa menor a la mínima requerida y la exigencia de un espesor mínimo de material. [2]

Por otro lado, la dureza a la indentación es el método más sofisticado y ampliamente utilizado en control de calidad y toma de decisiones de diseño. Se mide a través de ensayos de penetración, los cuales generan una deformación permanente en la superficie de un metal mediante la aplicación de una carga. En este tipo de ensayos, si queda una marca en la superficie, significa que se superó el esfuerzo de fluencia [2]. Sin embargo, no se busca alcanzar el esfuerzo último o máximo, sino determinar la dureza en un punto intermedio de la curva esfuerzo-deformación, ubicado en la zona de deformación plástica estable.

La dureza a la indentación se clasifica en macro dureza y micro dureza. Dentro de la macro dureza, existen dos métodos principales: Rockwell y Brinell [2]. La dureza Rockwell es el método más preciso y ampliamente utilizado. Se basa en la medición de la profundidad de penetración bajo una carga específica y presenta diversas subescalas. Sus cargas oscilan entre 60, 100 y 150 kgf, y el indentador es un cono de diamante con un ángulo de 120°. Existen variantes como la Rockwell superficial, utilizada para materiales con recubrimientos de hasta un 20 % del espesor total, y la Rockwell estándar, empleada en metales duros. La dureza Rockwell (HR) se calcula mediante la ecuación (1).

$$
HR = 130 - \frac{h}{0.002} \tag{1}
$$

Formato Unificado de Informes de Laboratorio. Versión 1.0

Otro método de macro dureza es la dureza Brinell, que evalúa la resistencia a la penetración de una superficie metálica utilizando una esfera de acero o carburo de tungsteno con un diámetro de 10 mm. Las cargas aplicadas oscilan entre 500 y 3000 kgf. La dureza Brinell (HB) se calcula mediante la ecuación (2).

$$
HB = \frac{2F}{\pi D \left[ D - \sqrt{D^2 - d^2} \right]} \tag{2}
$$

En cuanto a la micro dureza, los métodos principales son Vickers y Knoop. Estos ensayos requieren una preparación previa del material, como un proceso de lijado para asegurar una superficie homogénea. La dureza Vickers utiliza un penetrador de diamante piramidal con un ángulo de 136°, dejando una huella en forma de rombo. Se mide la diagonal media de la huella y se calcula la dureza mediante la ecuación (3).

$$
HV = 1.854 \frac{F}{d_1^2} \tag{3}
$$

Por otro lado, la dureza Knoop también emplea un penetrador de diamante, pero con una geometría asimétrica, con ángulos de 172.5° y 130°. Este método es especialmente útil para materiales frágiles o con anisotropía estructural. [2]

Un método adicional es la dureza Shore [3], que evalúa la penetración de un penetrador cónico afilado en la superficie del material bajo una carga preestablecida. La profundidad de la huella determina la dureza del material. Existe una variante que mide la altura de rebote de un martillo sobre la superficie, donde un rebote alto indica una mayor dureza del material y un rebote bajo sugiere una mayor penetración y menor dureza.

Finalmente, en polímeros y gomas se utilizan escalas de dureza específicas como Shore A y Shore D. En el ensayo Shore, la carga debe aplicarse de forma rápida pero sin impacto, y la lectura de dureza se realiza 15 segundos después de la aplicación. [3]

Asimismo, Para el cálculo del error asociado o el error total, se consideró tanto el error sistemático, correspondiente a la resolución de la máquina, como los errores aleatorios de las variables, entre ellas la dureza. En este sentido, la combinación de ambos tipos de error se realizó conforme a lo establecido en la ecuación (4).

$$
E_t = \sqrt{E_{\text{sist}}^2 + E_{\text{alea}}^2} \tag{4}
$$

Para concluir, en esta práctica se realizaron ensayos de dureza por penetración en distintos materiales utilizando los métodos Rockwell, Brinell, Vickers y Shore, seleccionando para cada uno el material adecuado según su aplicación industrial y normativa ASTM. Se ensayó acero AISI 4340 con el método Rockwell, aluminio 6063 con el método Brinell, vidrio flotado con el método Vickers y neopreno con el método Shore.

Se establecen las siguientes hipótesis para contrastar lo esperado con los resultados obtenidos: el acero AISI 4340, por su alto contenido de carbono y tratamiento térmico [5], deberá presentar una mayor dureza que el aluminio 6063, el cual, al ser un metal más blando y dúctil, exhibirá valores de dureza más bajos. El vidrio flotado, al ser un material frágil y amorfo, tendrá valores elevados en la escala Vickers, reflejando su resistencia a la indentación pero su baja tenacidad. En cuanto a los polímeros, el neopreno, al ser un elastómero, mostrará una dureza significativamente menor en la escala Shore en comparación con los metales y cerámicos.

### **Objetivos**

- Conocer e identificar las diferentes escalas de dureza (normas, medición, reporte y análisis) y la instrumentación utilizada en cada una
- Establecer los criterios para la selección del método, su utilidad y la escala adecuada para determinar la dureza en las distintas familias de materiales.
- Familiarizar al estudiante con los órdenes de magnitud en las pruebas de dureza para las distintas familias de materiales.

# **MÉTODO**

### **Preparativos**

Para la realización de los ensayos de dureza, se inició con la medición de la temperatura ambiente y la humedad relativa del laboratorio tal y como se muestra en la "Tabla 1", con el fin de asegurar condiciones estables y reproducibles durante las pruebas. Posteriormente, se seleccionaron los materiales a ensayar, los cuales incluyeron acero 4340 en forma de disco, vidrio arquitectónico fundido, aluminio 6063 y neopreno, un elastómero. Cada material fue sometido a distintos ensayos de dureza, dependiendo de sus propiedades mecánicas y características estructurales. Se utilizaron los siguientes equipos e instrumentos: el durómetro AFFRI 250 DRMC para los ensayos Rockwell y Brinell, el micro durómetro BUEHLER MICROMET 5104 para el ensayo Vickers, y un durómetro digital Shore para el ensayo en polímeros.

|  | Tabla 1. Temperatura ambiente y humedad relativa |  |  |  |
|--|--------------------------------------------------|--|--|--|
|--|--------------------------------------------------|--|--|--|

| Temperatura [°�] | Humedad relativa [%] |
|------------------|----------------------|
| 20.3 ± 0.3       | 53.2 ± 0.1           |

# **Ejecución**

El primer ensayo realizado fue el de Rockwell en la escala C, empleando un indentador de cono de diamante con un ángulo de 120° y una carga de 150 kgf [4]. La norma ASTM E18

Formato Unificado de Informes de Laboratorio. Versión 1.0

establece que primero se debe aplicar una precarga de 10 kgf durante 2 segundos para asentar el indentador en la muestra. Luego, se incrementa la carga hasta 150 kgf durante 5 segundos y, posteriormente, se retira la carga principal, dejando nuevamente solo la precarga durante 2 segundos antes de retirarla por completo, tal y como se muestra en la "Figura 1" [6]. En este ensayo no se analiza la geometría de la huella dejada por el indentador, sino que la dureza se determina a partir de la profundidad de la penetración. Se tomaron cinco mediciones en distintas zonas del disco de acero.

![](_page_2_Figure_1.jpeg)

**Figura 1. Método de ensayo de dureza Rockwell (Diagrama esquemático). Fuente [6].**

El segundo ensayo fue el de Vickers, realizado sobre vidrio arquitectónico fundido. En este caso, se utilizó un indentador de diamante en forma de pirámide con ángulos de 136° en sus aristas, aplicando una carga de 0.3 kgf durante 15 segundos, según lo establecido en la norma ASTM C1327 [8]. Este ensayo se realizó con el equipo BUEHLER MICROMET 5104 [4], el cual permitió obtener la dureza en escala Vickers y su equivalente en Rockwell C, además de registrar las dimensiones de las diagonales de la huella mediante un microscopio, tal y como se muestra en la "Figura 2". Se efectuaron cinco mediciones en diferentes puntos de la muestra.

![](_page_2_Figure_4.jpeg)

**Figura 2. Indentadores de Vickers con las diagonales señaladas. Fuente [8].**

A continuación, se realizó el ensayo Brinell sobre aluminio 6063, utilizando un indentador esférico de 2.5 mm de diámetro y aplicando una carga de 62.5 kgf durante 10 segundos. La medición se llevó a cabo con el durómetro AFFRI 250 DRMC [4], que proporcionó la dureza en escala HB, así como una imagen ampliada de la huella con una escala de ± 0.5001 mm. En este caso, solo se obtuvo un dato debido a restricciones de tiempo, mientras que los cuatro valores restantes fueron enviados

por correo con sus respectivas imágenes y mediciones de diámetro. De acuerdo con la norma ASTM E10 [7], se verificó que el diámetro de la huella estuviera entre el 24 % y el 60 % del diámetro de la bola, y se midió la huella en dos direcciones perpendiculares para obtener un promedio.

Por último, se efectuó el ensayo Shore en muestras de neopreno, empleando un durómetro digital tipo A, adecuado para materiales blandos [4] . Se aplicó una carga de 10 N con un indentador de cono truncado, conforme a la norma ASTM D2240 [9]. Se realizaron cinco mediciones, asegurando que la presión del instrumento sobre la muestra se mantuviera constante para evitar variaciones en los resultados.

#### **Procesamiento de datos**

Los datos obtenidos en cada ensayo fueron analizados de acuerdo con las especificaciones de cada norma. En el caso de Rockwell, la dureza se determinó a partir de la diferencia entre la profundidad inicial y final de la penetración [6]. Para Vickers, se calcularon los valores de dureza a partir de la media de las diagonales de la huella dejada en la muestra, utilizando la fórmula estándar para la conversión a la escala Rockwell C [8]. En el ensayo Brinell, se determinó la dureza promediando las mediciones del diámetro de la huella y verificando la relación entre la carga aplicada y el área de la huella [7]. En el ensayo Shore, se registró el valor máximo alcanzado por el indentador de cono truncado dentro del tiempo especificado [9], todo recapitulado en la sección "Resultados".

A fin de organizar y analizar la información de manera clara y precisa, se recopilaron los datos obtenidos en tablas, en las cuales se registraron los valores correspondientes a cada ensayo. Para Vickers, se incluyeron las medidas de las diagonales de la huella, mientras que en Brinell se documentaron los diámetros promediados de cada indentación. En los ensayos de Rockwell y Shore, se consignó directamente el valor de dureza obtenido para cada indentación numerada. Estas tablas permitieron una comparación estructurada de los resultados y facilitaron la interpretación de la dureza de cada material en función del método aplicado.

Para finalizar, junto con estos datos tabulados en Excel, se calcularon los valores de los errores sistemáticos, considerando la resolución de los equipos utilizados, y los errores aleatorios, redondeados a dos cifras significativas mediante el cálculo de la desviación estándar de cada conjunto de mediciones. Con esta información, fue posible aplicar la ecuación (4) y obtener el error total asociado a cada ensayo, valores que se presentan en la "Tabla 2", "Tabla 3", "Tabla 4", "Tabla 5".

### **RESULTADOS**

Se presentan las ilustraciones de las indentaciones obtenidas en los ensayos de Rockwell "Figura 3", Vickers

Formato Unificado de Informes de Laboratorio. Versión 1.0

![](_page_3_Figure_0.jpeg)

"Figura 4", Shore "Figura 5" y Brinell "Figura 6" , incluyendo su escala para una correcta interpretación de las mediciones.

#### **Figura 3. Ilustraciones de las indentaciones obtenidas en el ensayo de Rockwell y Vickers. Basado en [6] y [8].**

![](_page_3_Figure_3.jpeg)

#### **Figura 4. Ilustraciones de las indentaciones obtenidas en el ensayo de Shore y Brinell. Basado en [6] y [8].**

Se reportan los resultados obtenidos según las normas ASTM E18 [6], ASTM C1327 [8], ASTM D2240 [9] y ASTM E10 [7], siguiendo la estructura de las tablas ilustradas en el Anexo I en el documento [4] para una presentación clara y organizada de los datos. Además, se incluyen los cálculos de las incertidumbres asociadas a los valores obtenidos, asegurando una adecuada estimación de la precisión de las mediciones.

|  |  |  |  |  | Tabla 2. Prueba de dureza Rockwell |
|--|--|--|--|--|------------------------------------|
|--|--|--|--|--|------------------------------------|

| Temperatura [℃] | 20.3         | Humedad [%]                 | 53.2             |
|-----------------|--------------|-----------------------------|------------------|
| Material        | AISI 4340    | Tiempo de<br>aplicación [s] | 5                |
| Escala          | HRC          | Indentador                  | Cono<br>diamante |
| Indentación     | Dureza [HRC] | Observaciones               |                  |
| 1               | 25.7         |                             |                  |

| 2<br>3<br>4<br>5    | 27.4<br>26.2<br>26.6<br>26.3 | Se visualizó una indentación en<br>forma de círculo desde una vista<br>superior. Además, se detalló desde<br>un microscopio pero a simple vista<br>también se podía ver. |  |
|---------------------|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--|
| Promedio            | 26.4                         |                                                                                                                                                                          |  |
| Desviación Estándar | 0.63                         |                                                                                                                                                                          |  |
| Error asociado      | 0.6                          |                                                                                                                                                                          |  |

# **Tabla 3. Prueba de dureza Vickers**

| Temperatura<br>[℃]     | 20.3                     | Humedad [%]                 | 53.2                                                       |
|------------------------|--------------------------|-----------------------------|------------------------------------------------------------|
| Material               | Vidrio<br>arquitectónico | Tiempo de<br>aplicación [s] | 15                                                         |
| Carga [kgf]            | 0.3                      | Indentador                  | Pirámide diamante                                          |
| Indentación            | Diagonal, d [mm]         | Dureza [HV]                 | Observaciones                                              |
| 1                      | 32.86                    | 515.3                       | Se<br>observó<br>una                                       |
| 2                      | 33.01                    | 510.5                       | huella en forma de<br>rombo cuadrada que                   |
| 3                      | 33.04                    | 509.9                       | a simple vista era                                         |
| 4                      | 32.99                    | 511.2                       | visible<br>su<br>geometría. A través<br>del microscopio se |
| 5                      | 32.70                    | 520.4                       |                                                            |
| Promedio               | 32.90                    | 513.5                       | veía sus diagonales.                                       |
| Desviación<br>estándar | 0.14                     | 3.95                        |                                                            |
| Error asociado         | 0.20                     | 3.5                         |                                                            |

## **Tabla 4. Prueba de dureza Shore**

| Temperatura [℃]        | 20.3            | Humedad [%] | 53.2                                    |  |  |
|------------------------|-----------------|-------------|-----------------------------------------|--|--|
| Material               | Neopreno        |             |                                         |  |  |
| Carga [N]              | 10              | Escala      | Shore a                                 |  |  |
| Indentación            | Dureza<br>[HRC] | Tiempo [s]  | Observaciones                           |  |  |
| 1                      | 80.1            | < 1         | Huella<br>de                            |  |  |
| 2                      | 80.4            | < 1         | indentación<br>en<br>geometría circular |  |  |
| 3                      | 79.9            | < 1         | por<br>su<br>cono                       |  |  |
| 4                      | 79.6            | < 1         | truncado.                               |  |  |
| 5                      | 79.4            | < 1         |                                         |  |  |
| Promedio               |                 | 79.9        |                                         |  |  |
| Desviación<br>Estándar |                 | 0.4         |                                         |  |  |
| Error asociado         | 0.4             |             |                                         |  |  |

### **Tabla 6. Prueba de dureza Brinell**

| Temperatura<br>[℃] | 20.3   | Humedad [%]                 | 53.2             |
|--------------------|--------|-----------------------------|------------------|
| Material           | Al6063 | Tiempo de<br>aplicación [s] | 10               |
| Carga [kgf]        | 62.5   | Indentador                  | Esfera- 2.5 [mm] |

Formato Unificado de Informes de Laboratorio. Versión 1.0

| Indentación            | Diámetro de huella<br>[mm] | Dureza [HBW] | Observaciones                              |
|------------------------|----------------------------|--------------|--------------------------------------------|
| 1                      | 0.989                      | 78.00        | Se<br>observó<br>una                       |
| 2                      | 0.974                      | 80.40        | huella en forma de<br>circulo a través del |
| 3                      | 0.941                      | 86.40        | microscopio                                |
| 4                      | 0.941                      | 86.50        |                                            |
| 5                      | 0.937                      | 87.00        |                                            |
| Promedio               | 1.000                      | 83.70        |                                            |
| Desviación<br>estándar | 0,020                      | 3.730        |                                            |
| Error asociado         | 0,100                      | 3.300        |                                            |

Asimismo, para cada uno de los valores obtenidos, se determinó la dureza en una escala diferente a la inicial utilizando las tablas de correlación de la norma ASTM E140 [10], reflejadas en la "Tabla 6". Sin embargo, no se incluyó el del ensayo de Brinell debido a que no se encuentra una tabla de equivalencias para el indentador que se utilizó una esfera de diámetro de 2,5 mm.

| Material               | Acero 4340                 |                                | Vidrio flotado<br>arquitectónico |                                | Neopreno                       |                                |
|------------------------|----------------------------|--------------------------------|----------------------------------|--------------------------------|--------------------------------|--------------------------------|
| Indentación            | Dureza<br>inicial<br>[HRC] | Dureza<br>equivalente<br>[HBW] | Dureza<br>inicial<br>[HV]        | Dureza<br>equivalente<br>[HRC] | Dureza<br>inicial<br>[Shore A] | Dureza<br>equivalente<br>[HRC] |
| 1                      | 25.7                       | 253.0                          | 515.3                            | 50.1                           | 80.1                           | 59.6                           |
| 2                      | 27.4                       | 264.0                          | 510.3                            | 49.8                           | 80.4                           | 59.6                           |
| 3                      | 26.2                       | 258.0                          | 509.9                            | 49.8                           | 79.9                           | 59.0                           |
| 4                      | 26.6                       | 258.0                          | 511.2                            | 49.9                           | 79.6                           | 59.0                           |
| 5                      | 26.3                       | 258.0                          | 520.4                            | 50.5                           | 79.4                           | 59.0                           |
| Promedio               | 26.4                       | 258.2                          | 513.5                            | 50.0                           | 79.9                           | 59.2                           |
| Desviación<br>estándar | 0.63                       | 3.9                            | 3.95                             | 0.29                           | 0.4                            | 0.3                            |

**Tabla 6. Reporte de conversión de durezas**

# **DISCUSIÓN**

En esta sección se analizan y discuten los resultados obtenidos en los ensayos de dureza, considerando la selección del método de medición para cada material, la validez de los datos en relación con la literatura y posibles fuentes de error.

Cada método de medición de dureza fue seleccionado con base en las propiedades del material y la normativa ASTM correspondiente [6,7,8,9]. La escala Rockwell C fue utilizada para el acero AISI 4340, dado que emplea un indentador de cono de diamante y una carga elevada (150 kgf), lo que permite evaluar la resistencia del material a la deformación permanente sin generar una indentación excesiva. Además, es un método rápido y reproducible, ampliamente utilizado en la industria metalúrgica [5]. La escala Rockwell C es recomendada para medir la dureza del acero debido a su adecuada interacción con la estructura cristalina del material. El acero, dependiendo de su composición y tratamiento térmico, puede presentar fases como ferrita, perlita, martensita o bainita, cada una con distintas propiedades mecánicas. La prueba Rockwell C emplea un penetrador de cono de diamante y una carga elevada (150 kgf),

lo que permite evaluar con precisión la resistencia del acero a la deformación plástica y su capacidad para soportar esfuerzos sin fallar. En aceros endurecidos, como los tratados térmicamente, la martensita es la fase predominante, caracterizada por su alta dureza y fragilidad, lo que hace que este método sea ideal para medir su resistencia. En aceros más blandos, donde la ferrita y la perlita son dominantes, el ensayo sigue siendo útil para determinar cómo estos microconstituyentes afectan la dureza general del material. [11]

En el caso del aluminio 6063, se empleó la prueba de Brinell con una bola de acero o carburo de tungsteno, ya que este método es adecuado para metales blandos y relativamente dúctiles. La aplicación de cargas intermedias (62.5 kgf) y la medición del diámetro de la huella permitieron obtener valores de dureza fiables [7]. Además, el aluminio 6063 es una aleación relativamente blanda y dúctil, con una microestructura homogénea y de grano fino. El método Brinell utiliza un penetrador esférico de carburo de tungsteno que, al aplicarse sobre materiales como el aluminio, produce una huella lo suficientemente grande para promediar posibles defectos microestructurales, proporcionando así una medida representativa de la dureza del material [12].

El vidrio arquitectónico fue evaluado con el método Vickers, debido a que es un material frágil con alta resistencia a la indentación [8]. La prueba Vickers emplea un indentador de diamante en forma de pirámide con cargas bajas (0.3 kgf), lo que permite obtener una huella precisa sin fracturar el material y facilita la comparación con otros materiales frágiles. El ensayo de dureza Vickers es especialmente adecuado para medir la dureza del vidrio arquitectónico fundido debido a las propiedades intrínsecas de este material. El vidrio es un material frágil y homogéneo con una estructura amorfa, lo que significa que carece de una disposición cristalina regular. El método Vickers utiliza un penetrador de diamante en forma de pirámide cuadrangular que, al aplicarse con cargas controladas, produce una pequeña indentación en la superficie del vidrio. Esta técnica permite evaluar con precisión la resistencia del vidrio a la deformación permanente sin causar fracturas, gracias a la aplicación de cargas ligeras que minimizan el riesgo de daño en materiales quebradizos. Además, la forma del penetrador y la posibilidad de ajustar la carga hacen que el ensayo Vickers sea versátil y aplicable a materiales con diferentes niveles de dureza, incluyendo aquellos tan duros y frágiles como el vidrio [13].

Para el neopreno, se utilizó la escala Shore A, que es adecuada para elastómeros, debido a su comportamiento viscoelástico [9], además cuenta con una estructura molecular flexible, lo que le confiere una consistencia blanda y elástica [14]. Este método emplea un indentador cónico truncado con una carga de 10 N aplicada de forma controlada y es común en la industria de los

Formato Unificado de Informes de Laboratorio. Versión 1.0

polímeros para evaluar la resistencia superficial sin afectar la estructura interna del material.

Los valores obtenidos en los ensayos concuerdan con lo reportado en la literatura. En el caso del acero AISI 4340, la dureza promedio obtenida en Rockwell C fue de 26.4 HRC, que al convertirse a la escala Brinell resultó en 258.2 HBW, dentro del rango esperado según la bibliografía, donde se reportan valores entre 250-280 HBW dependiendo del tratamiento térmico [10]. Para el aluminio 6063, la dureza Brinell promedio fue de 83.7 HBW, lo que coincide con valores reportados en la literatura para este tipo de aleación (80-90 HBW según el temple aplicado) [10]. En cuanto al vidrio arquitectónico, la dureza Vickers promedio fue de 513.5 HV, lo cual es consistente con los valores reportados para vidrios comerciales, que oscilan entre 500-600 HV [10]. Finalmente, para el neopreno, se obtuvo una dureza Shore A promedio de 79.9, lo que está dentro del rango esperado (75-85 Shore A según la formulación del elastómero) [3].

Se observó un error conceptual en la conversión de dureza de Shore A a Rockwell C, ya que los materiales blandos no pueden compararse directamente con metales duros. Por ejemplo, la tabla muestra un valor de 59.2 HRC para el neopreno, lo que implicaría que es más duro que el acero AISI 4340 (26.4 HRC), lo cual es incorrecto. Las conversiones deben realizarse solo dentro de escalas compatibles [10]. Además, la variabilidad en los ensayos fue baja, lo que indica una buena repetitividad. Sin embargo, en la prueba de Brinell, se registró una variación en los valores debido a la dificultad de medir con precisión el diámetro de la huella. Factores como la temperatura y la humedad se mantuvieron estables (20.3°C y 53.2%), minimizando efectos ambientales en los resultados [4].

Para mejorar la exactitud de las mediciones, se podrían tomar más repeticiones y utilizar métodos de análisis de imagen digital para medir huellas de indentación con mayor precisión. Asimismo, se recomienda evitar la conversión de escalas entre materiales de distinta naturaleza (por ejemplo, de Shore a Rockwell C), ya que no reflejan correctamente la resistencia mecánica de los materiales [10]. En general, los resultados obtenidos reflejan adecuadamente la dureza de cada material y están alineados con la teoría y la literatura. Se confirmó la importancia de seleccionar el método adecuado para cada material y de aplicar las conversiones con precaución para evitar interpretaciones erróneas.

# **CONCLUSIONES**

Tras realizar el ensayo de dureza en los diferentes materiales, se concluyó que la selección del método de medición es fundamental para obtener resultados precisos y representativos de cada material. Se identificaron y estudiaron las diferentes escalas de dureza utilizadas en metales, polímeros y cerámicos, comprendiendo su aplicación y limitaciones en

función de las propiedades estructurales de los materiales ensayados.

Se estableció la importancia de elegir un método adecuado según las características del material, evidenciando que la escala Rockwell es ideal para metales, la Vickers para cerámicas, la Brinell para materiales blandos como el aluminio y la Shore para elastómeros. Además, los resultados experimentales mostraron una buena concordancia con los valores teóricos, con ligeras fluctuaciones atribuibles a variaciones en la microestructura, condiciones ambientales y precisión del equipo utilizado.

Asimismo, se observó que la conversión de dureza a la escala Rockwell C permitió una comparación entre materiales, destacando que el acero 4340 presentó una dureza considerablemente mayor en comparación con el vidrio y el neopreno. También se demostró que la dureza no es una propiedad intrínseca del material, sino un valor relativo dependiente del método de ensayo y la carga aplicada, lo que sugiere la necesidad de realizar pruebas complementarias para obtener información más detallada sobre las propiedades mecánicas de los materiales.

Finalmente, se identificaron dificultades en la aplicación de algunos métodos de dureza a ciertos materiales, como la prueba de Brinell, cuya adecuación se ve limitada en superficies pequeñas o en materiales excesivamente rígidos. A través de esta experiencia experimental, se logró obtener una visión integral sobre las distintas escalas de medición de dureza bajo la normativa establecida, comprendiendo su utilidad en el análisis de metales, polímeros y cerámicos.

# **BIBLIOGRAFÍA**

- [1] W. Callister y D. Rethwisch, Fundamentals of Materials Science and Engineering: An Integrated Approach, Fifth edition ed., Wiley, 2015.
- [2] J. Escobar, "Semana 4 - Propiedades (Plásticas, dureza)," OneDrive, Dec. 13, 2024.
- [3] "Dureza en Polímeros," Scribd.
- [4] M. Vargas, "GL – IMEC 1410: Prueba de dureza para metales, polímeros y cerámicos" Bogotá, 2024
- [5] "4340 Alloy Steel," Neo Nickel.
- [6] ASTM International, ASTM E18-05 Standard Test Method for Rockwell Hardness and Rockwell Superficial Hardness of Metalic Materials.
- [7] ASTM International, ASTM E10-07 Standard Test Method for Brinell Hardness of Metallic Materials.

Formato Unificado de Informes de Laboratorio. Versión 1.0

- [8] ASTM International, ASTM C1327-03 Standard Test Method for Vickers Indentation Hardness of Advanced Ceramics.
- [9] ASTM International, ASTM D2240-05 Standard Test Method for Rubber Property—Durometer Hardness.
- [10] ASTM International, ASTM E140 - 12b Standard Hardness Conversion Tables for Metals Relationship Among Brinell Hardness, Vickers Hardness, Rockwell Hardness, Superficial Hardness, Knoop Hardness, Scleroscope Hardness, and Leeb Hardness.
- [11] Struers, "Ensayo de dureza Rockwell," Struers.
- [12] Struers, "Ensayo de dureza Brinell," Struers.
- [13] Struers, "Ensayo de dureza Vickers," Struers.
- [14] J-Flex, "¿Qué es la dureza Shore? ¿Cómo se mide la dureza del caucho?," J-Flex.

### **ANEXO A**

### **TÍTULO DEL ANEXO**

Put text of Annex here

Formato Unificado de Informes de Laboratorio. Versión 1.0 Documento controlado. Aprobado por el Consejo del Departamento de Ingeniería Mecánica el 10 de junio de 2016