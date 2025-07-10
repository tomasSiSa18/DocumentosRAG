#### **Taller Esfuerzo-Deformación:**

Este es un paso a paso de cómo desarrollar los puntos importantes de los talleres de esta temática

#### *Paso 1*

Es necesario sacar los datos de esfuerzo y deformación (únicamente cuando los valores estén en Cargas y Longitudes

1.1) Determinar si se trata de unidades del Sistema Internacional (SI) o del sistema inglés

1.2) Sacar el área de la probeta:

| Para probetas circulares                                     | Para probetas cuadradas                                                 |
|--------------------------------------------------------------|-------------------------------------------------------------------------|
| 𝜋<br>2<br>[𝑚𝑚2<br>2<br>]𝑜[𝑖𝑛<br>𝐴0<br>=<br>∙<br>𝑑0<br>]<br>4 | 𝜋<br>[𝑚𝑚2<br>2<br>]𝑜[𝑖𝑛<br>𝐴0<br>=<br>∙<br>𝑏𝑎𝑠𝑒<br>×<br>𝑎𝑛𝑐ℎ𝑜<br>]<br>4 |
| Donde 𝑑0<br>equivale al diámetro inicial de la<br>probeta    |                                                                         |

1.3) Dividir la carga en el área

1.4) Sacar la deformación:

$$
\varepsilon = \frac{l_i - l_0}{l_0} \,\, [ \% ]
$$

Donde corresponde a la longitud instantánea.

### *Calcule el módulo de Young.*

1) Identificar la región lineal (2 o 3 valor de la tabla esfuerzo-deformación) y aplicar la fórmula:

$$
E = \frac{\sigma}{\varepsilon}
$$

# *Calcule el esfuerzo de fluencia al 0.2%.*

b.1) Se debe hacer una curva adicional a esta en la cual se desplace la deformación en 0.2%, por ende, se debe crear una nueva columna en Excel, copiar los datos de deformación y sumarles un 0.2%

b.2) aplicar las ecuaciones de una curva característica lineal (y=mx +b). Donde: m= módulo de Young x=nuevos valores desplazados por 0.2% y=0 para 0.2%

De esa ecuación se despeja B y luego, con B, ya se tienen los valores de la ecuación de la línea recta para sacar los valores de Y.

El esfuerzo de fluencia es la intersección entre la curva original y luego la línea recta.

## *Calcule el esfuerzo máximo de tensión ingenieril.*

c.1) Identificar el valor máximo de la curva de esfuerzo deformación.

## *Calcule la ductilidad en área.*

d.1) Aplicar la fórmula:

$$
\%RA = \frac{A_0 - A_f}{A_0}
$$

# *Calcule la ductilidad en elongación.*

e.1) Aplicar la fórmula:

$$
\%EL = \frac{L_f - L_0}{L_0}
$$

## *Calcule el módulo de resiliencia del material.*

f.1) Aplicar la fórmula:

$$
U_r = \frac{1}{2} \cdot \sigma_y \cdot \varepsilon_y
$$

Donde:

 viene del esfuerzo de fluencia (valor del eje Y de la intersección de la línea de la pendiente con la curva original.

 viene de la elasticidad (valor del eje X de la intersección de la línea de la pendiente con la curva original.

![](_page_1_Figure_16.jpeg)

*Calcule la tenacidad del material.*

### g.1) Calcular el área bajo la curva completa. (Método de integrales, por ejemplo).

### *Calcule el esfuerzo de fractura del material.*

h.1) Identificar el último valor en la columna de esfuerzo de la tabla.