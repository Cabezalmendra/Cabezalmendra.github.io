<h1 style="font-size:24px">Funciones especiales</h1>

Son funciones definidas de tal forma que, que por su importancia en el campo del análisis matemático, análisis funcional, la física y otras aplicaciones, posee nombres y designaciones más o menos establecidos.

<br>
<a name="Sumario_de_formulas"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Sumario de formulas</h3>

<a name="Funcion_gamma"></a>
<h4 style="font-size:16px;color:#FF7F00">Funcion gamma</h4>

Generaliza el factorial para los reales y complejos
$$\bold{
\Gamma(n) = \int_{0}^{\infty} {x^{n-1} e^{-x} dx} } \\[6ex]

\text{Propiedades} \\[3ex]

\Gamma(n+1) = n \cdot \Gamma(n) \\[2ex]
\Gamma(n+1) = n!\\[2ex]
\Gamma(1) = 1 \\[2ex]
\Gamma \left( \frac{1}{2} \right) = \sqrt{\pi} \\[2ex]
\lim_{k \rightarrow 0} \Gamma (k) =\pm \infty \\[2ex]
\Gamma(k) \Gamma(1-k) = \frac{\pi}{\sin(k \pi)}  \\[2ex]
k \text{ es fraccionario con denominador distinto de 2}$$

<br>

<a name="Funcion_beta"></a>
<h4 style="font-size:16px;color:#FF7F00">Funcion beta</h4>

$$
\beta (m,n) = \int_{0}^{1} x^{m-1} (1-x)^{n-1} dx \\[2ex]
\beta (m,n) = \frac{1}{a^{m+n-1}} \int_{0}^{a} x^{m-1} (a-x)^{n-1} dx \\[2ex]
\beta(m,n) = 2 \int_{0}^{\frac{\pi}{2}}{\sin^{2m-1}(\theta) \cdot \cos^{2n-1}(\theta)} \cdot d\theta \\[2ex]
\beta(m,n) = \int_{0}^{\infty} \frac{x^{n-1}}{(1+x)^{m+n}}  dx \\[6ex]

\text{Propiedades}\\[3ex]

\beta(m,n) = \beta(n,m)\\[2ex]
\beta(m,n) = \frac{\Gamma(n) \cdot \Gamma(m)}{\Gamma(m + n)}

$$



<br>
<br>
<a name="Funcion_gamma"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Funcion gamma</h3>

Fue definida por Euler como:

$$
\Gamma(n) = \int_{0}^{\infty} x^{n-1} e^{-x} dx \\[2ex]
\text{Converge para }n>0
$$

Esta funcion extiende el concepto de factorial a los números reales y complejos, y tiene la caracteristica de ser logaritmicamente concava.

<a name="Gamma_generaliza_al_factorial,_desmotracion"></a>
<h4 style="font-size:16px;color:#FF7F00">Gamma generaliza al factorial, desmotracion</h4>

Para que una funcion generalice al factorial, esta debe cumplir que:

$$
f(x) = x \cdot f(x-1) \\[2ex] 
f(0) = 1 \\[4ex]

\text{Luego:} \hspace{6ex}
f(x) = x!


$$

Tambien puede plantearse como

$$
f(x+1) = x * f(x) \\[2ex] 
f(1) = 1 \\[4ex]

\text{Luego:} \hspace{6ex} f(x+1) = x!
$$

<br>

Veamos si la funcion gamma cumple esta propiedad

$$
\Gamma (x) = \int_{0}^{\infty} {x^{n-1} e^{-x} } dx \\[2ex]
\Gamma (x+1) = \int_{0}^{\infty} {x^{n} e^{-x} } dx 
$$

Aplicamos integracion por partes a $\Gamma(x+1)$

$$
 \int_{0}^{\infty} {x^{n} e^{-x} } dx = \left. x^{n} \cdot (-e^{-x}) \right|_{0}^{\infty}  - \int_{0}^{\infty} { \frac{d}{dx}(x^n)} \cdot (-e^{-x}) dx \\[2ex]
 
\Gamma (x+1) = \left. -x^{n}e^{-x} \right|_{0}^{\infty}  - \int_{0}^{\infty} n x^{n-1} \cdot (-1) \cdot e^{-x}  dx \\[2ex]

\Gamma (x+1)  = \left. -x^{n}e^{-x} \right|_{0}^{\infty}  - \left[ (-n)  \int_{0}^{\infty}  x^{n-1} \cdot  \cdot e^{-x} dx \right] \\[2ex]

\Gamma (x+1)  = \left. -x^{n}e^{-x} \right|_{0}^{\infty} + n \int_{0}^{\infty}  x^{n-1} \cdot  \cdot e^{-x} dx \\[2ex]
$$

Vemos que el segundo termino del lado derecho se corresponde con $x \Gamma(x)$

$$
\Gamma (x+1)  = \left. -x^{n}e^{-x} \right|_{0}^{\infty} + n \int_{0}^{\infty}  x^{n-1} \cdot  \cdot e^{-x} dx \\[2ex]

\Gamma (x+1)  = \left. -x^{n}e^{-x} \right|_{0}^{\infty} + x \Gamma(x) \hspace{3ex} (1)
$$

Analizamos que valor tomara el primer termino del lado derecho

$$
\left. -x^{n}e^{-x} \right|_{0}^{\infty} \\[2ex]
\left. -\frac{x^{n}}{e^{x}} \right|_{0}^{\infty} (2) \\[2ex]
-\frac{\infty^{n}}{e^{\infty}} - \left( -\frac{0^n}{e^0} \right) \\[2ex]
-\frac{\infty}{\infty} + \frac{0}{1} \\[2ex]
-\frac{\infty}{\infty} 
$$

Vemos que el límite de $\frac{x^{n}}{e^{x}}$ genera una indeterminacion del tipo $\frac{\infty}{\infty}$. Podemos solucionar esto utilizando el teorema de L'Hopital n veces. 


$$
\lim_{k \rightarrow \infty}  -\frac{k^{n}}{e^{k}} 
$$

Aplicamos L'Hopital n veces y tenemos

$$
\lim_{k \rightarrow \infty}  -\frac{\tau k^{n-n}}{e^{k}} \\[2ex]
$$

Donde
$$
\prod_{v=0}^{n-1} (n-v) = \tau \\[2ex] 
\text{(} \tau \text{ es una constante)}  \\[6ex]

\lim_{k \rightarrow \infty}  -\frac{\tau k^{n-n}}{e^{k}} \\[2ex]
\lim_{k \rightarrow \infty}  -\frac{\tau k^{0}}{e^{k}} \\[2ex]
\lim_{k \rightarrow \infty}  -\frac{\tau}{e^{k}} \\[2ex]
-\frac{\tau}{e^{\infty}} \\[2ex] 
-\frac{\tau}{\infty} \\[2ex] 
0
$$

Sabiendo esto, remplazamos (2)


$$
\left. -x^{n}e^{-x} \right|_{0}^{\infty} \\[2ex]
\left. -\frac{x^{n}}{e^{x}} \right|_{0}^{\infty} \\[2ex]
-\frac{\infty^{n}}{e^{\infty}} - \left( -\frac{0^n}{e^0} \right) \\[2ex]
0 - 0 \\[2ex]
0
$$

Remplazamos nuestro resultado en (1)

$$
\Gamma (x+1)  = \left. -x^{n}e^{-x} \right|_{0}^{\infty} + x \Gamma(x) \\[2ex]

\Gamma (x+1)  = 0 + x \Gamma(x) \\[2ex]

\Gamma (x+1)  = x \Gamma(x)
$$

Luego, se puede afirmar que

$$
\Gamma (n+1) = n! \\[2ex]
n \in \mathbb{N} 
$$

Queda asi demostrado que gamma generaliza al factorial


<br>
<a name="Gamma_evaluada_en_0.5"></a>
<h4 style="font-size:16px;color:#FF7F00">Gamma evaluada en 0.5</h4>

Normalmente, resulta muy dificil calcular el valor de gamma en un valor no entero. Se estudiara el desarrollo de gamma evaluada en 0.5 por resultar muy útil y no ser excesivamente compleja en su desarrollo.

$$
\Gamma \left( \frac{1}{2} \right) = \int_{0}^{\infty} x^{\frac{1}{2}-1} e^{-x} dx \\[2ex]

\Gamma \left( \frac{1}{2} \right) = \int_{0}^{\infty} x^{-\frac{1}{2}} e^{-x} dx
$$

Realizamos un cambio de variables

$$
x = u^2 \\[2ex]
dx = 2u du \\[2ex]
$$

Evaluamos los extremos

$$
x = 0 \Rightarrow u = 0 \\[2ex] 
x = \infty \Rightarrow u = \infty
$$

Remplazamos

$$
\int_{0}^{\infty} x^{-\frac{1}{2}} e^{-x} dx \\[2ex]
\int_{0}^{\infty} \left( u^{2} \right)^{-\frac{1}{2}} e^{-u^2} 2u du \\[2ex]
2 \int_{0}^{\infty}  u \cdot u^{-1} e^{-u^2} du \\[2ex]
2 \int_{0}^{\infty}  e^{-u^2}  du \\[2ex]
$$

La integral obtenida es conocida como *integrtal de poisson*.
$$
Ip = \int_{0}^{\infty}  e^{-u^2}  du
$$

La resolveremos utilizando el teorema de Fubini. Planteamos dos funciones $f(u)$ y $g(v)$ de forma equivalente

$$
f(u) = \int_{0}^{\infty}  e^{-u^2} du = Ip \\[2ex]
g(v) = \int_{0}^{\infty}  e^{-v^2} dv = Ip
$$

Planteamos su producto

$$
f(u) \cdot g(v) = \int_{0}^{\infty}  e^{-u^2} du \cdot \int_{0}^{\infty}  e^{-v^2} dv = Ip \cdot Ip
$$

Por el teorema de fubbini sabemos que el producto de dos integrales simples puede expresarse como una integral doble, luego:

$$
\int_{0}^{\infty}  e^{-u^2} du \cdot \int_{0}^{\infty}  e^{-v^2} dv = Ip \cdot Ip \\[2ex]

\int_{0}^{\infty} \int_{0}^{\infty}  e^{-u^2}  \cdot e^{-v^2} du dv = Ip^2 \\[2ex]

\int_{0}^{\infty} \int_{0}^{\infty}  e^{-u^2-v^2}  du dv = Ip^2 \\[2ex]

\int_{0}^{\infty} \int_{0}^{\infty}  e^{-(u^2+v^2)}  du dv = Ip^2
$$

Planteamos un nuevo cambio de variables, en este caso de coordenadas cartesianas a coordenadas polares

$$
u = r \cdot \cos(\theta) \\[2ex]
v = r \cdot \sin(\theta) \\[2ex]
J = r 
$$

Remplazamos en la integral

$$


\int_{0}^{\infty} \int_{0}^{\infty}  e^{-(u^2+v^2)}  du dv \\[2ex]

\int_{0}^{\frac{\pi}{2}}\int_{0}^{\infty}  e^{-(r \cdot \cos(\theta))^2 + ( r \cdot \sin(\theta))^2)} \cdot r \cdot dr d\theta  \\[2ex]

\int_{0}^{\frac{\pi}{2}}\int_{0}^{\infty} e^{-r^2(\cos^2(x) + \sin^2(x))}   \cdot r \cdot dr d\theta  \\[2ex]

\int_{0}^{\frac{\pi}{2}}\int_{0}^{\infty}  e^{-r^2}  \cdot r \cdot  dr d\theta 
$$

Planteamos un último cambio de variables

$$
t = r^2 \\[2ex]
dt = 2 r dr \\[2ex]
\frac{dt}{2} = rdr
$$

Remplazamos

$$
\int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty}  e^{-r^2}  \cdot r \cdot  dr d\theta = Ig^2 \\[2ex]

\int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty}  e^{-t}  \cdot \frac{dt}{2} d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}} \int_{0}^{-\infty}  e^{-t}  \cdot dt d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}} \left. -e^{-t} \right|_{0}^{\infty} d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}} \left. \frac{1}{-e^{t}} \right|_{0}^{\infty} d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}} \left[  \frac{1}{-e^{\infty}} - \frac{1}{-e^{0}} \right] d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}}  \left[   \frac{1}{-\infty} + \frac{1}{1}  \right]  d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}}  [0 +1]  d\theta = Ig^2 \\[2ex]

\frac{1}{2} \int_{0}^{\frac{\pi}{2}} 1 \cdot  d\theta = Ip^2 \\[2ex]

\frac{1}{2}  \frac{\pi}{2} = Ip^2 \\[2ex]
\frac{\pi}{4}  = Ip^2 \\[2ex]
$$

Teniendo el resultado de esta integral, despejamos el valor de Ip

$$
Ip^2 = \int_{0}^{\infty}  e^{-u^2} du \cdot \int_{0}^{\infty}  e^{-v^2} dv \\[2ex]
Ip^2 = \frac{\pi}{4} \\[2ex]
Ip = \frac{\sqrt{\pi}}{2}

$$

Teniendo el resultado de la integral de Poisson, podemos calcular $\Gamma \left( \frac{1}{2} \right)$

$$
\Gamma \left( \frac{1}{2} \right) = 2 \cdot Ip \\[2ex]
\Gamma \left( \frac{1}{2} \right) = 2 \cdot \frac{\sqrt{\pi}}{2} \\[6ex]

\bold{
\Gamma \left( \frac{1}{2} \right) = \sqrt{\pi} \\[2ex]
}
$$


<br>
<a name="Funcion_beta"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Funcion beta</h3>

Funcion que resulta muy practica por sus multiples formas para resolver integrales. Tiene una fuerte relacion con la funcion gamma.

La funcion beta se define como

$$
\beta(m,n) = \int_{0}^{1} x^{m-1} \cdot (1-x)^{n-1} dx 
$$

<br>
<a name="beta_es_simétrica"></a>
<h4 style="font-size:16px;color:#FF7F00">beta es simétrica</h4>

una funcion es simetrica es aquella que cumple

$$
f(x,y) = f(y,x)
$$

Debemos demostrar entonces, que 

$$
\beta(m,n) = \beta(n,m)
$$

Planteamos una sustitucion

$$
x = 1 - y \\[2ex]
dx = -dy \\[6ex]

x=0 \Rightarrow y=1 \\[2ex]
x=1 \Rightarrow y=0
$$

Remplzamos en $\beta$

$$
\beta(m,n) = \int_{0}^{1} x^{m-1} \cdot (1-x)^{n-1} dx \\[2ex]
\beta(m,n) = \int_{1}^{0} (1 - y)^{m-1} \cdot (1-(1 - y))^{n-1} -dy \\[2ex]
\beta(m,n) = - \int_{1}^{0} (1 - y)^{m-1} \cdot (y)^{n-1} dy \\[2ex]
\beta(m,n) = \int_{0}^{1} (1 - y)^{m-1} \cdot (y)^{n-1} dy \\[2ex]
\beta(m,n) = \int_{0}^{1}  y^{n-1} \cdot (1 - y)^{m-1}  dy \\[6ex]

\bold{
\beta(m,n) = \beta(n,m)
}
$$

Queda asi demostrado que $\beta$ es simetrica 

<br>
<a name="Forma_trigonometrica_de_beta"></a>
<h4 style="font-size:16px;color:#FF7F00">Forma trigonometrica de beta</h4>

Planteamos la sustitucion
$$
x = \sin^2(\theta) \\[2ex]
dx = 2 \sin(\theta) \cos(\theta) d\theta \\[2ex]
x=0 \Rightarrow \theta = 0 \\[2ex]
x=0 \Rightarrow \theta = \frac{\pi}{2}
$$

Remplazamos

$$
\beta(m,n) = \int_{0}^{1} x^{m-1} \cdot (1-x)^{n-1} dx \\[2ex]
\beta(m,n) = \int_{0}^{\frac{\pi}{2}}  (\sin^2(\theta) )^{m-1} \cdot (1-\sin^2(\theta) )^{n-1} \cdot 2 \sin(\theta) \cos(\theta) d\theta \\[2ex]
\beta(m,n) = \int_{0}^{\frac{\pi}{2}}  \sin^{2m-2}(\theta) \cdot \cos^{2n-2}(\theta) \cdot 2 \sin(\theta) \cos(\theta) d\theta \\[6ex]

\bold{
\beta(m,n) = 2 \int_{0}^{\frac{\pi}{2}}  \sin^{2m-1}(\theta) \cdot \cos^{2n-1}(\theta) d\theta \\[2ex]
}
$$ 

<br>

<a name="Forma_general_de_beta"></a>
<h4 style="font-size:16px;color:#FF7F00">Forma general de beta</h4>

Planteamos la sustitucion

$$
x = \frac{y}{a} \\[2ex]
dx = \frac{1}{a} dy \\[4ex]
x=0 \Rightarrow y = 0 \\[2ex]
x=1 \Rightarrow y = a
$$

Remplazamos

$$
\beta(m,n) = \int_{0}^{a} x^{m-1} \cdot (1-x)^{n-1} \frac{1}{a} dy \\[2ex]

\beta(m,n) = \int_{0}^{a} \left( \frac{y}{a} \right)^{m-1} \cdot \left( 1-\frac{y}{a} \right)^{n-1} \frac{1}{a} dy \\[2ex]

\beta(m,n) = \int_{0}^{a} \left( \frac{y}{a} \right)^{m-1} \cdot \left(\frac{a-y}{a} \right)^{n-1} \frac{1}{a} dy \\[2ex]

\beta(m,n) = \int_{0}^{a} \frac{1}{a^{m-1}} y^{m-1} \cdot \frac{1}{a^{n-1}} (a-y)^{n-1} \frac{1}{a} dy \\[2ex]

\beta(m,n) = \int_{0}^{a} \frac{1}{a^{m-1}}  \frac{1}{a^{n-1}}  \frac{1}{a}  \cdot y^{m-1} \cdot (a-y)^{n-1} dy \\[2ex]

\beta(m,n) = \int_{0}^{a} \frac{1}{a^{m-1 + n - 1 + 1}} \cdot y^{m-1} \cdot (a-y)^{n-1} dy \\[2ex]

\beta(m,n) = \int_{0}^{a} \frac{1}{a^{m+ n - 1 }} \cdot y^{m-1} \cdot (a-y)^{n-1} dy \\[4ex]

\bold{
\beta(m,n) = \frac{1}{a^{m+ n - 1 }} \int_{0}^{a}   y^{m-1} \cdot (a-y)^{n-1} dy 
}
$$



<br>
<a name="Forma_racional_de_beta"></a>
<h4 style="font-size:16px;color:#FF7F00">Forma racional de beta</h4>

Se plantea la sustitucion
$$
x = \frac{y}{1+y} \\[2ex]
dx = \frac{1}{(1+y)^2} dy \\[4ex]

x=0 \Rightarrow x=1 \\[2ex]
x=1 \Rightarrow y= \infty 
$$

Remplazamos:

$$
\beta(m,n) = \int_{0}^{1} x^{m-1} \cdot (1-x)^{n-1} dx \\[2ex]

\beta(m,n) = \int_{0}^{\infty} \left( \frac{y}{1+y} \right)^{m-1} \cdot \left(1-\frac{y}{1+y}  \right)^{n-1} \cdot  \left( \frac{1}{(1+y)^2} \right) dy \\[2ex]

\beta(m,n) = \int_{0}^{\infty} \left( \frac{y}{1+y} \right)^{m-1} \cdot \left(\frac{1}{1+y}  \right)^{n-1} \cdot  \left( \frac{1}{(1+y)^2} \right) dy \\[2ex]

\beta(m,n) = \int_{0}^{\infty} \frac{y^{m-1}}{(1+y)^{m-1}}  \cdot \frac{1^{n-1}}{(1+y)^{n-1}} \cdot \frac{1}{(1+y)^2} dy \\[2ex]

\beta(m,n) = \int_{0}^{\infty} \frac{y^{m-1}}{(1+y)^{m-1+n-1+2}}  dy \\[4ex]

\bold{
\beta(m,n) = \int_{0}^{\infty} \frac{y^{m-1}}{(1+y)^{m+n}}  dy 
}
$$

<br>
<a name="Relacion_entre_beta_y_gamma"></a>
<h4 style="font-size:16px;color:#FF7F00">Relacion entre beta y gamma</h4>

La funcion gamma es por definicion

$$
\Gamma(n) = \int_{0}^{\infty} z^{n-1} \cdot e^{-z} dz
$$

Planteamos una sustitucion

$$
z=x^2\\[2ex]
dz = 2x dx \\[4ex]

z=0 \Rightarrow x=0 \\[2ex]
z=\infty \Rightarrow x=\infty \\[2ex]
$$

Remplazamos

$$
\Gamma(n) = \int_{0}^{\infty} z^{n-1} \cdot e^{-z} dz \\[2ex]

\Gamma(n) = \int_{0}^{\infty} {(x^2)}^{n-1} \cdot e^{-x^2} 2xdx \\[2ex]

\Gamma(n) = 2 \int_{0}^{\infty} {x}^{2n-2} \cdot e^{-x^2} xdx \\[2ex]

\Gamma(n) = 2 \int_{0}^{\infty} {x}^{2n-1} \cdot e^{-x^2} dx \\[2ex]
$$

Podemos plantear esta misma igualdad utilizando otras variables

$$
\Gamma(m) = 2 \int_{0}^{\infty} {y}^{2m-1} \cdot e^{-y^2} dy \\[2ex]
$$

Elevamos $\Gamma$ al cuadrado, utilizando una variable distinta para cada factor

$$
\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\infty} {x}^{2n-1} \cdot e^{-x^2} dx \right] \cdot \left[  2 \int_{0}^{\infty} {y}^{2m-1} \cdot e^{-y^2} dy \right] \\[2ex]
$$

Por el teorema de fubini sabemos que el producto de dos integrales simples puede expresarse como una integral doble, luego:

$$
\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\infty} {x}^{2n-1} \cdot e^{-x^2} dx \right] \cdot \left[  2 \int_{0}^{\infty} {y}^{2m-1} \cdot e^{-y^2} dy \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\infty} \int_{0}^{\infty} {x}^{2n-1} \cdot e^{-x^2} \cdot {y}^{2m-1} \cdot e^{-y^2} dxdy \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\infty} \int_{0}^{\infty} {x}^{2n-1} \cdot {y}^{2m-1} \cdot e^{-x^2 -y^2} dxdy \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\infty} \int_{0}^{\infty} {x}^{2n-1} \cdot {y}^{2m-1} \cdot e^{-(x^2 +y^2)} dxdy \\[2ex]
$$

Planteamos una sustitucion a coordenadas polares

$$
x = r \cos(\theta) \\[2ex]
y = r \sin(\theta)  \\[2ex]
J = r \\[4ex]

dxdy = r \cdot drd\theta
$$

Remplazamos

$$
\Gamma(n) \cdot \Gamma(m) =4 \int_{0}^{\infty} \int_{0}^{\infty} {x}^{2n-1} \cdot {y}^{2m-1} \cdot e^{-(x^2 +y^2)} dxdy \\[2ex]

\Gamma(n) \cdot \Gamma(m)  =4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} {(r\cos(\theta) )}^{2n-1} \cdot {(r \sin(\theta) )}^{2m-1} \cdot e^{-r^2} \cdot r \cdot drd\theta \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} {(r\cos(\theta) )}^{2n-1} \cdot {(r \sin(\theta) )}^{2m-1} \cdot e^{-r^2} \cdot r \cdot drd\theta  \\[2ex]

\Gamma(n) \cdot \Gamma(m)  = 4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} {r^{2n-1}\cos(\theta) }^{2n-1} \cdot r^{2m-1} \sin(\theta)^{2m-1} \cdot e^{-r^2} \cdot r \cdot drd\theta  \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot e^{-r^2} \cdot r^{2m-1} \cdot r^{2n-1} \cdot r \cdot drd\theta  \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot e^{-r^2} \cdot r^{2m-1+2n-1} \cdot r \cdot drd\theta  \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot e^{-r^2} \cdot r^{2m+2n-2} \cdot r \cdot drd\theta  \\[2ex]
$$

Nuevamente podemos aplicar el teorema de Fubini, y separar la integral doble de $d\theta$ y $dr$ en dos integrales, una con $dr$ y otra con $d\theta$

$$
\Gamma(n) \cdot \Gamma(m) = 4 \int_{0}^{\frac{\pi}{2}} \int_{0}^{\infty} \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot e^{-r^2} \cdot r^{2m+2n-2} \cdot r \cdot drd\theta  \\[2ex]

\Gamma(n) \cdot \Gamma(m) = 4 \left[ \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1}   d\theta \cdot  \int_{0}^{\infty} e^{-r^2} \cdot r^{2(m+n-1)} \cdot r \cdot dr \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot   d\theta \right] \cdot  \left[ 2 \int_{0}^{\infty} e^{-r^2} \cdot (r^{2})^{(m+n-1)} \cdot r \cdot dr \right] \\[2ex]
$$

Planteamos una última sustitucion para $r$

$$
t = r^2 \\[2ex]
dt = 2r dr \\[2ex]
\frac{dt}{2} = r dr \\[4ex]

r = 0 \Rightarrow t = 0 \\[2ex]
r = \infty \Rightarrow t = \infty
$$


Remplazamos

$$
\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot   d\theta \right] \cdot  \left[ 2 \int_{0}^{\infty} e^{-r^2} \cdot (r^{2})^{(m+n-1)} \cdot r \cdot dr \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot   d\theta \right] \cdot  \left[ 2 \int_{0}^{\infty} e^{-t} \cdot (t)^{(m+n-1)} \cdot \frac{dt}{2} \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot   d\theta \right] \cdot  \left[ 2 \cdot \frac{1}{2} \int_{0}^{\infty} e^{-t} \cdot t^{(m+n-1)} \cdot dt \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot   d\theta \right] \cdot  \left[ \int_{0}^{\infty} e^{-t} \cdot t^{(m+n-1)} \cdot dt \right] \\[2ex]
$$

Vemos que el primer factor del lado izquierdo es la definicion trigonometrica de beta, mientras que el segundo factor es $\Gamma(m+n)$. Remplazamos y se tiene:

$$
\Gamma(n) \cdot \Gamma(m) = \left[ 2 \int_{0}^{\frac{\pi}{2}}  \cos(\theta)^{2n-1} \cdot  \sin(\theta)^{2m-1} \cdot   d\theta \right] \cdot  \left[ \int_{0}^{\infty} e^{-t} \cdot t^{(m+n-1)} \cdot dt \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = \beta(m,n) \cdot  \left[ \int_{0}^{\infty} e^{-t} \cdot t^{(m+n-1)} \cdot dt \right] \\[2ex]

\Gamma(n) \cdot \Gamma(m) = \beta(m,n) \cdot \Gamma(m+n) \\[2ex]

\frac{\Gamma(n) \cdot \Gamma(m)}{\Gamma(m+n)} = \beta(m,n) \\[4ex]

\bold{
\beta(m,n) = \frac{\Gamma(n) \cdot \Gamma(m)}{\Gamma(m+n)}
}
$$




<br>
<a name="Aplicaciones_interesantes"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Aplicaciones interesantes</h3>

1. 

$$
\int_{0}^{1} \left[ \ln \left( \frac{1}{t} \right) \right]^{\frac{1}{2}} dt
$$

Este integral puede resolverse con la funcion gamma


<br>
<a name="Tips"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Tips</h3>

* Funcion beta
	* cuando se opera entre m y n, siempre sera suma
	* cuando se opera entre m/n y 1, siempre sera m-1
	* cuando se opera entre x/y/t y a, si en numerador a-x, si en denominador a + x
