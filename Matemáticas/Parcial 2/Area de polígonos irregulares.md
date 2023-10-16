
El area de un irregular se calcula como $\frac{1}{2}(|D|)$ donde D es el valor de la determinante de los vertices de el polígono  

$$
D = \begin{bmatrix}
x_1 & y_2\\
x_2 & y_2 \\
x_3 & y_3 \\
... \\
x_1 & x_2
\end{bmatrix}
$$


Los vertices se ordenan en sentido anti-horario, empezando por cualquier vértice

D se calcula como la multiplicación de todos los valores de x multiplicado por el valor de y un renglón abajo, menos todos los valores de x multiplicado por el valor y un renglón arriba

Considere la siguiente expresión, donde $n$ es la cantidad de vertices, e $i$ es el indice del vértice

$$
 D =\sum_{i=1}^{n} (x_i * y_{i+1}) - \sum_{i=2}^{n+1} (x_i * y_{i-1})
$$

![|300](https://study.com/cimages/videopreview/videopreview-full/kduwps36rs.jpg)

Una vez se ha calculado el determinante, se debe multiplicar su valor absoluto por 1/2, y ese es el área

$$
A = \frac{1}{2}|D|
$$
