<h1 style="font-size:36px">Suceciones y series</h1>

Tabla de contenidos:
Tabla de contenidos:
1. [Sumario general de formulas](#Sumario_general_de_formulas)
	1. [Criterios de convergencia de series generales (S)](#Criterios_de_convergencia_de_series_generales_(S))
		1. [Criterios por tipo de serie genera (S)](#Criterios_por_tipo_de_serie_genera_(S))
	2. [Series especiales (S)](#Series_especiales_(S))
	3. [Serie de Taylor (s)](#Serie_de_Taylor_(s))
		1. [Series de Taylor notables (S)](#Series_de_Taylor_notables_(S))
	4. [Serie de Fourier](#Serie_de_Fourier)
	5. [Serie compleja y exponencial de Fourier](#Serie_compleja_y_exponencial_de_Fourier)
	6. [Transformada de Fourier](#Transformada_de_Fourier)
2. [Suceciones](#Suceciones)
	1. [Funcion asociada](#Funcion_asociada)
	2. [Limites](#Limites)
	3. [Convergencia y divergencia](#Convergencia_y_divergencia)
	4. [Suceciones monotonas y acotadas](#Suceciones_monotonas_y_acotadas)
	5. [Sucecion de sumas parciales](#Sucecion_de_sumas_parciales)
3. [Series](#Series)
	1. [Convergencia y divergencia](#Convergencia_y_divergencia)
4. [Series numericas](#Series_numericas)
	1. [Clasificacion de series](#Clasificacion_de_series)
		1. [Series generales](#Series_generales)
		2. [Series especiales](#Series_especiales)
	2. [Criterios de convergencia](#Criterios_de_convergencia)
		1. [Criterios de convergencia de series generales](#Criterios_de_convergencia_de_series_generales)
		2. [Criterios por tipo de serie general](#Criterios_por_tipo_de_serie_general)
		3. [Desarrollo de los criterios de series generales](#Desarrollo_de_los_criterios_de_series_generales)
			1. [Criterio del termino n-esimo](#Criterio_del_termino_n-esimo)
			2. [Criterio de comparacion](#Criterio_de_comparacion)
			3. [Criterio de la integral](#Criterio_de_la_integral)
			4. [Criterio de D'Alambert](#Criterio_de_D'Alambert)
			5. [Criterio de la raiz](#Criterio_de_la_raiz)
			6. [Criterio de Leibniz](#Criterio_de_Leibniz)
		4. [Desarrollo de los criterios de series especiales](#Desarrollo_de_los_criterios_de_series_especiales)
			1. [Serie geometrica](#Serie_geometrica)
			2. [Series P](#Series_P)
	3. [Series notables](#Series_notables)
5. [Series de potencias](#Series_de_potencias)
	1. [Convergencia y divergencia](#Convergencia_y_divergencia)
				1. [Ej 1](#Ej_1)
				2. [Ej 2](#Ej_2)
	2. [Resolver integrales con series](#Resolver_integrales_con_series)
				1. [Ej 1](#Ej_1)
				2. [Ej 2](#Ej_2)
	3. [Criterio de D'Alambert modificado](#Criterio_de_D'Alambert_modificado)
				1. [Ej](#Ej)
6. [Series de Taylor](#Series_de_Taylor)
	1. [Series de Taylor notables](#Series_de_Taylor_notables)
	2. [Series de Taylor para funciones compuestas](#Series_de_Taylor_para_funciones_compuestas)
				1. [Ej](#Ej)
	3. [Trasladar centro de serie](#Trasladar_centro_de_serie)
		1. [Series de Taylor compuesta](#Series_de_Taylor_compuesta)
				1. [Ej 1](#Ej_1)
				2. [Ej 2](#Ej_2)
		2. [Series geometricas](#Series_geometricas)
				1. [Ej](#Ej)
7. [Series de fourier](#Series_de_fourier)
	1. [Producto escalar entre funciones](#Producto_escalar_entre_funciones)
	2. [Familia ortogonal de funciones en [a,b]](#Familia_ortogonal_de_funciones_en_[a,b])
		1. [Justificación del periodo](#Justificación_del_periodo)
		2. [Demostración: la familia trigonometrica es ortogonal en [-p,p]](#Demostración:_la_familia_trigonometrica_es_ortogonal_en_[-p,p])
	3. [Desarrollo de series de fourier](#Desarrollo_de_series_de_fourier)
	4. [Sumario serie de Fourier](#Sumario_serie_de_Fourier)
	5. [Propiedad de integración con funciones pares e impares](#Propiedad_de_integración_con_funciones_pares_e_impares)
				1. [Demostracion](#Demostracion)
	6. [Series de fourier con funciones pares e impares](#Series_de_fourier_con_funciones_pares_e_impares)
	7. [Desarrollo de serie exponencial y compleja de Fourier](#Desarrollo_de_serie_exponencial_y_compleja_de_Fourier)
	8. [Sumario serie exponencial y compleja de Fourier](#Sumario_serie_exponencial_y_compleja_de_Fourier)
	9. [Transformada y transformada inversa de Fourier](#Transformada_y_transformada_inversa_de_Fourier)
		1. [Extension del periodo](#Extension_del_periodo)
		2. [Serie de Fourier de frecuencias continuas](#Serie_de_Fourier_de_frecuencias_continuas)
				1. [Ej 1](#Ej_1)
				2. [Ej 2](#Ej_2)
				3. [Ej 3](#Ej_3)
		3. [Transformada de Fourier](#Transformada_de_Fourier)
				1. [Ej](#Ej)
		4. [Transformada de Fourier](#Transformada_de_Fourier)
		5. [Sumario de formulas de transformada de Fourier](#Sumario_de_formulas_de_transformada_de_Fourier)
	10. [C<sub>0</sub> =? a<sub>0</sub>/2](#C<sub>0</sub>_=?_a<sub>0</sub>/2)
				1. [Ej 1](#Ej_1)
				2. [Ej 2](#Ej_2)
	11. [Variacion de funcion](#Variacion_de_funcion)
	12. [Condiciones de Dirichlet](#Condiciones_de_Dirichlet)

---
<a name="Sumario_general_de_formulas"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Sumario general de formulas</h2>

A continuacion se enlistan todos los sumarios de formulas


<br>
<a name="Criterios_de_convergencia_de_series_generales_(S)"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Criterios de convergencia de series generales</h3>



* Termino n-ésimo
* Comparación
* Integral
* D'Alambert
* Raiz
* Leibniz


<a name="Criterios_por_tipo_de_serie_genera_(S)"></a>
<h4 style="font-size:16px;color:#FF7F00">Criterios por tipo de serie general:</h4>


* Todas
	* n-ésimo
	* D'Alambert
	* raíz (preferiblemente en series donde todo este elevado a n)
* Alternadas
	* Leibniz
* Monosigno
	* Integral
	* Comparación
* Términos no nulos
	* No tiene procedimiento propio alguno


<br>
<a name="Series_especiales_(S)"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Series especiales</h3>

* Serie geometrica
	* Converge para |r| < 1
$$ 
\sum_{n=0}^{\infty} {a r^n}  \\[3ex]

\text{Converge a }\frac{a}{1-r}
$$



* Series P
	* p > 0 
 	* Converge para p > 1
$$ 
\sum_{n=0}^{\infty} {\frac{1}{n^p}} \\
$$


* Serie telescopica (no desarrollada en este apunte)
$$ 
\sum_{n=0}^{\infty} {a_n - a_{n-1}} \\ 
$$

<br>
<a name="Serie_de_Taylor_(s)"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Serie de Taylor</h3>

Una serie de Taylor es una forma de aproximar una funcion mediante una suma infinita de potencias de polinomios como $(x-a)^n$. Busca aproximar a una funcion imitando el valor de todas las tasas de cambio de una funcion en un punto dado $a$, llamado centro.

$$

\sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n \\[4ex]

\text{Donde } f^{(n)}(x) \text{ representa la n-esima derivada de la función}

$$

<br>
<a name="Series_de_Taylor_notables_(S)"></a>
<h4 style="font-size:16px;color:#FF7F00">Series de Taylor notables</h4>


* Centrado en 0
	* $\frac{1}{1-x} = \sum_{n=0}^{\infty} {x^n}$
	* $\sin(x) = \sum_{n=0}^{\infty} {\frac{(-1)^n}{(2n+1)!} x^{2n+1}}$
	* $\cos(x) = \sum_{n=0}^{\infty} {\frac{(-1)^n}{(2n)!} x^{2n}}$
	* $e^{x} = \sum_{n=0}^{\infty} {\frac{x^n}{n!} }$
* Centrado en 1
	* $ln(x) = \sum_{n=1}^{\infty}{(-1)^{n+1}\frac{(x-1)^n}{n}}$
* Centrado en a
	* $ln(x) = ln(a) + \sum_{n=1}^{\infty}{(-1)^{n+1}\frac{(x-a)^n}{na^n}}$



<br>
<a name="Serie_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Serie de Fourier</h3>

* Aproxima mediante una suma infinita de senos y cosenos a casi cualquier funcion periodica  

* Serie de Fourier generada por $f(x)$

$$
f(x) \approx \approx \frac{a_0}{2} + \sum_{n=1}^{\infty}  \left(
a_n \left( \frac{n\pi x}{p} \right)    + 
b_n \left( \frac{n\pi x}{p} \right) 
\right) 
$$
$\approx \approx$ significa genera

* Coeficientes
$$
a_m = \frac{1}{p} \int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  dx \\[4ex]
b_m = \frac{1}{p} \int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) dx\\[4ex]
c_0 = \frac{1}{2p} \int_{-p}^p f(x) dx 
$$


<br>
<a name="Serie_compleja_y_exponencial_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Serie compleja y exponencial de Fourier</h3>

* Otra forma de expresar la transformada de Fourier, a partir de coeficientes complejos

$$
\text{Sea } \omega = \frac{\pi}{P} = \frac{2 \pi}{T}  \\[2ex]
\text{Sea } C_n  = \frac{1}{2p}   \left( \int_{-p}^{p} f(x)  (e^{- n \omega x}) dx  \right) =  \frac{a_n}{2} - j\frac{b_n}{2}
$$

* Forma exponencial de Fourier: 
$$
\bold{
f(x) = c_0 + \sum_{n=1}^{\infty}   \left( 
{e^{ n \omega x j} C_{n} + 
e^{- n \omega x j} C_{-n}   }  \right) } 
$$

* Forma compleja de Fourier:
$$
\bold{
f(x) = \sum_{-\infty}^{\infty} {e^{ n \omega x j} C_n} 
}
$$

<br>
<a name="Transformada_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Transformada de Fourier</h3>


* Transformada de Fourier 
	* $f(t) \rightarrow f(\omega)$
	* Genrealizacion de C<sub>n</sub> para los reales de una funcion de periodo $\infty$
$$
F(\omega) = \int_{-\infty}^{\infty} {f(t) e^{-\omega t j}} dt
$$

* Transformada inversa de Fourier
	* $f(\omega) \rightarrow f(t)$
	* Surge de la serie de Fourier de una funcion de periodo $\infty$
$$
f(t) = \frac{1}{2\pi} \int_{-\infty} ^{\infty} F(\omega) e^{\omega t j} d\omega
$$

TODO:: pasar condiciones de dirichlet NO um

---

<a name="Suceciones"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Suceciones</h2>


Son funciones cuyo dominio son los reales, normalmente su anotan como  *a<sub>n</sub>*

Ejemplos:

$$ 
a_n = \sqrt{n} 

\\[5ex]

a_n = \frac{6}{1-n}

$$

<br>

<a name="Funcion_asociada"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Funcion asociada</h3>


Una funcion asociada sera aquella cuyo argumento coincida con el argumento de la suceción

$$

a_n = \frac{ sin(n)}{2 n^2} 

\\[2ex]

f(x) = \frac{ sin(x)}{2 x^2} ; \text{ donde }  x \in \Reals

\\[5ex]

f(x) \text{ es la funcion asociada de } a_n

$$

<br>

<a name="Limites"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Límites</h3>


* Por ser funciones discretas, no tiene sentido evaluar el límite de una sucecion en un valor n, por lo que siempre se tomaran valores cuando n tiende a infito positivo o negativo

* Los límites de suceciones pueden ser calculados de igual forma que los límites de funciones

* La funcion asociada es esencial para operar con suceciones cuando queremos aplicar operaciones que requieran continuidad, como la regla de L'Hopital

* La mayoría de las propiedades de funciones también aplican para suceciones

<br>

<a name="Convergencia_y_divergencia"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Convergencia y divergencia</h3>

Se dice que una sucecion converge si, al hacer que su parametro tienda a infinito, la sucecion tiende a un valor especifico. Por otro lado, la sucecion diverge si dicho límite da como resultado infinito positivo o negativo.

<br>

<a name="Suceciones_monotonas_y_acotadas"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Suceciones monotonas y acotadas</h3>

Una sucecion es monotona si solo es creciente o decreciente

Una sucecion es acotada si contiene una cota mayor o menor

Si una sucecion es monotona y acotada, entonces diverge

<br>

<a name="Sucecion_de_sumas_parciales"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Sucecion de sumas sumas parciales</h3>

Dada una sucecion a<sub>n</sub>, podemos describir una nueva sucecion S<sub>n</sub>, donde el termino n-esimo sea la suma de los primeros n terminos de a<sub>n</sub>

$$
S_1 = a_1 \newline
S_2 = a_1 + a_2 \newline
S_3 = a_1 + a_2 + a_3 \newline
\vdots\\
 S_n = a_1 + a_2 + \dots a_n
$$


---
<a name="Series"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Series</h2>

Una serie es la suma de c términos de una sucesión, esta se denota como:

$$
\sum_{n=b}^{c} {a_n} \\[2ex]
\text{Donde }  b,c \in \mathbb{Z} 
$$


Dada una sucecion $a_n$, en el caso que exista una sucecion de sumas parciales de $a_n$, entonces se cumple:

$$
S_{n_0} = \sum_{n=b}^{n_0} {a_n} \\[2ex]
\text{Donde }  b,c \in \mathbb{Z} 
$$

<br>

<a name="Convergencia_y_divergencia"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Convergencia y divergencia</h3>

Si la serie se aproxima a un valor especifico al hacer que la suma tienda a infinitos terminos, entonces la serie converge. De lo contrario, se dice que la serie diverge.

Se podría pensar que la forma mas directa de saber si una serie converge o no consiste en encontrar una sucecion de sumas parciales S<sub>n</sub> para la sucecion que se esta evaluando en la serie y evaluar el límite de esta sucecion. Sin embargo encontrar una sucecion de sumas parciales de una sucecion dada resulta imposible para casi todos los casos, siendo solo utilizado para series especiales.


<br>

<a name="Series_numericas"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Series numericas</h2>

Series donde no aparece una variable independiente, el resultado sera un escalar.

<br>

<a name="Clasificacion_de_series"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Clasificacion de series</h3>

<a name="Series_generales"></a>
<h4 style="font-size:16px;color:#FF7F00">Series generales</h4>

* **Series monosigno**: Series donde todos los elementos tienen el mismo signo, tambien son llamdas series de signos positivos.
Ejemplos:

$$ 
\sum_{n=0}^{\infty} {\frac{e^n}{n+1}}  \hspace{10ex}
\sum_{n=0}^{\infty} {\frac{2^n}{n!}}  
$$

* **Series alternantes**: Series donde el signo de la sucecion cambia por iteracion. Son de la forma
$$ 
\sum_{n=0}^{\infty} {(-1)^n a_n} \\
\text{Donde } a_n \text{es monosigno}
$$

* **Series de terminos no nulos**: Resto de las series, aquellas que no sean monosignos ni alternantes
Ejemplo:

$$ 
\sum_{n=0}^{\infty} {\frac{sin(x)}{x}} 
$$

<a name="Series_especiales"></a>
<h4 style="font-size:16px;color:#FF7F00">Series especiales</h4>

* Serie geometrica
$$ 
\sum_{n=0}^{\infty} {a r^n} \\
 \text{Donde } a \text{ y } r \text{ no contienen a } n
$$
* Series P
$$ 
\sum_{n=0}^{\infty} {\frac{1}{n^p}} \\
 \text{Donde } p > 0 
$$
* Serie telescopica
$$ 
\sum_{n=0}^{\infty} {a_n - a_{n-1}} \\ 
$$

<br>


<a name="Criterios_de_convergencia"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Criterios de convergencia</h3>

Debido a lo dificil que resulta encontrar la suscecion de sumas parciales, se idearon diversos metodos para determinar si una serie converge o no.

<a name="Criterios_de_convergencia_de_series_generales"></a>
<h4 style="font-size:16px;color:#FF7F00">Criterios de convergencia de series generales:</h4>


* Termino n-ésimo
* Comparación
* Integral
* D'Alambert
* Raiz
* Leibniz


<a name="Criterios_por_tipo_de_serie_general"></a>
<h4 style="font-size:16px;color:#FF7F00">Criterios por tipo de serie general:</h4>


* Todas
	* n-ésimo
	* D'Alambert
	* raíz (preferiblemente en series donde todo este elevado a n)
* Alternadas
	* Leibniz
* Monosigno
	* Integral
	* Comparación
* Términos no nulos
	* No tiene procedimiento propio alguno

<br>

En el caso de las series especiales, existen metodos directos para saber si divergen o convergen.

<br>

<a name="Desarrollo_de_los_criterios_de_series_generales"></a>
<h4 style="font-size:16px;color:#FF7F00">Desarrollo de los criterios de series generales:</h4>

<a name="Criterio_del_termino_n-esimo"></a>
<h5 style="font-size:16px;color:#e65140">1- Criterio del término n-esimo</h5>

$$
\text{Por logica podemos deducir que: si una fucion converge su límite tendera a 0,} \\ \text{ya que la suma infinita de un valor cuaquiera siempre sera divergente, luego: }

\\[3ex]

\text{ Si }     \hspace{1ex}   \sum_{n=0}^{\infty}{a_n}   \hspace{1ex}   \text{ converge, entonces }   \hspace{1ex}   \lim_{n->\infty} = 0 

\\[3ex]

\text{Utilizando su contrarreciproco, podemos afirmar que} \\[3ex]

\text{ Si }     \hspace{1ex}    \lim_{n->\infty} = 0   \hspace{1ex}   \text{ entonces, la serie }   \hspace{1ex}   \sum_{n=0}^{\infty}{a_n}   \hspace{1ex}   \text{diverge}
$$

<br>
<a name="Criterio_de_comparacion"></a>
<h5 style="font-size:16px;color:#e65140">2- Criterio de comparación</h5>

$$
\text{Sean }  a_n, b_n, c_n \text{ sucesiones de términos no negativos, tales que} \\[3ex]

 a_n \leq b_n \leq c_n   \hspace{2ex}   \text{ para todo n > k} \\[1ex]
 \text{donde n,k } \in \mathbb{N} \\[3ex]
 
 \text{entonces:} \\[3ex]
 
 \text{Si } \sum_{n=0}^{\infty}{a_n}  \text{ diverge }  \Rightarrow   \sum_{n=0}^{\infty}{b_n}  \text{ también diverge }  \\[3ex]

 \text{Si } \sum_{n=0}^{\infty}{c_n}  \text{ converge }  \Rightarrow   \sum_{n=0}^{\infty}{b_n}  \text{ también converge}  
$$

<br>
<a name="Criterio_de_la_integral"></a>
<h5 style="font-size:16px;color:#e65140">3- Criterio de la integral</h5>

$$

\text{ Sea } k \in \mathbb{N} \\[1ex]
\text{ Sea } a_n \text{una sucesión de términos positivos} \\[1ex]
\text{ Sea } f (n) = a_n \text{ para } n \in [k,∞) \text {, donde f cumple:} \\[3ex]

\bullet \text{ es decreciente } \\
\bullet \text{ es positiva} \\
\bullet \text{ es continua} \\[3ex]

\text{entonces: } \\[3ex]

\text{si }  \int_{k}^{\infty} {f(x) dx} \hspace{1ex}   \text{ converge, entonces: }   \sum_{n=0}^{\infty}{a_n}    \hspace{1ex}   \text{también converge}

\\[3ex]

\text{si }  \int_{k}^{\infty} {f(x) dx} \hspace{1ex}   \text{ diverge, entonces: }  \sum_{n=0}^{\infty}{a_n}    \hspace{1ex}   \text{también diverge}


%TODO:: añadir demostración

$$

<br>
<a name="Criterio_de_D'Alambert"></a>
<h5 style="font-size:16px;color:#e65140">4- Criterio de D'Alambert</h5>

$$

\text{Dada una serie } \sum_{n=0}^{\infty}{a_n} \\[2ex]
\text{Sea } P = \lim_{n-> \infty} { \left| \frac{a_{n+1}}{a_n} \right|}  \\[3ex]
\text{entonces:}

\\[2ex]

\bullet \text{ si } P<1 \text{ la serie converge} \\
\bullet \text{ si } P>1 \text{ la serie diverge} \\
\bullet \text{ si } P=1 \text{ El criterio no decide} \\

%Demostracion: https://foro.rinconmatematico.com/index.php?topic=88034.0 

$$



<br>
<a name="Criterio_de_la_raiz"></a>
<h5 style="font-size:16px;color:#e65140">5- Criterio de la raiz</h5>

$$
\text{Dada una serie } \sum_{n=0}^{\infty}{a_n} \\[2ex]
\text{Sea } P = \lim_{n-> \infty} {  \sqrt[n]{\left|  a_n \right|}}  \\[3ex]
\text{entonces:}

\\[2ex]

\bullet \text{ si } P<1 \text{ la serie converge} \\
\bullet \text{ si } P>1 \text{ la serie diverge} \\
\bullet \text{ si } P=1 \text{ El criterio no decide} \\
$$


<br>
<a name="Criterio_de_Leibniz"></a>
<h5 style="font-size:16px;color:#e65140">6- Criterio de Leibniz</h5>


$$
\text{Dada una serie alternante } \\[2ex]
\sum_{n=0}^{\infty}{(-1)^n u_n}
\hspace{3ex}   \text{ o }    \hspace{3ex}
\sum_{n=0}^{\infty}{(-1)^{n+1} u_n} \\[4ex]

\text{Si la sucecion } u_n \text{ cumple que}   \\[2ex]

\bullet \text{ todos sus terminos son positivos} \\
\bullet \text{ es decreciente} \\
\bullet \lim_{n->\infty} u_n = 0\\[4ex]

\text{Entonces, la seria converge}
$$


<br>
<a name="Desarrollo_de_los_criterios_de_series_especiales"></a>
<h4 style="font-size:16px;color:#FF7F00">Desarrollo de los criterios de series especiales</h4>

<a name="Serie_geometrica"></a>
<h5 style="font-size:16px;color:#e65140">1- Serie geometrica</h5>


$$
\text{Las series geometricas son de la forma: } \\[2ex]

\sum_{n=0}^{\infty} {a r^n} \\[2ex]

\text{Por lo tanto, la suma parcial n-esima se obtiene como: }\\[2ex]

S_n = a + ar + ar^2 + ar^3 + \ldots ar^n (1) \\[2ex]

\text{Podemos multiplicar (1) por }r \\[2ex]

rS_n =  ar + ar^2 + ar^3 ar^4 + \ldots ar^{n+1} (1) \\[2ex]

\text{Operamos y desarrollamos } S_n - rS_n  \\[4ex]

S_n - rS_n =   ( a + ar + \ldots ar^n ) - (ar + ar^2 + \ldots ar^{n+1}) \\
S_n - rS_n =  a - ar^{n+1} \\
S_n (1 - r) =  a - ar^{n+1}  \\[1ex]
\bold{ S_n =  \frac{a}{1-r} - \frac{ar^{n+1}}{1-r}} \\[4ex]

\text{Vemos que pudimos obtener la sucecion de sumas parciales. A continuación debemos tomar su límite para saber si la serie converge o diverge} \\[4ex]

\lim_{n->\infty} {\frac{a}{1-r} - \frac{ar^{n+1}}{1-r}} \\[4ex]

\text{Podemos observar que el unico termino que contiene a n es } r^{n+1} \text{, por lo tanto, este valor sera lo que determine que ocurrira con la serie}  \\[4ex]

\bold{\textbf{ Si } r < 1} \\[2ex]

\lim_{n->\infty} {\frac{a}{1-r} - \frac{ar^{n+1}}{1-r}} \\[2ex]
{\frac{a}{1-r} - \frac{ar^{\infty}}{1-r}} \\[2ex]
{\frac{a}{1-r} - \frac{a 0}{1-r}} \\[2ex]
{\frac{a}{1-r} - \frac{0}{1-r}} \\[2ex]
{\frac{a}{1-r} - 0 } \\[2ex]
\bold{ \frac{a}{1-r} }\\[6ex]

\bold{\textbf{ Si } r > 1} \\[2ex]

\lim_{n->\infty} {\frac{a}{1-r} - \frac{ar^{n+1}}{1-r}} \\[2ex]
{\frac{a}{1-r} - \frac{ar^{\infty}}{1-r}} \\[2ex]
{\frac{a}{1-r} - \frac{a \infty}{1-r}} \\[2ex]
{\frac{a}{1-r} - \frac{\infty}{1-r}} \\[2ex]
{\frac{a}{1-r} - \infty } \\[2ex]
\bold{-\infty} \\[6ex]

\bold{\textbf{ Si } r = 1}  \\[2ex]
\text{La serie será de la forma} \\[2ex]
\sum_{n=0}^{\infty} {a 1^n} =  \sum_{n=0}^{\infty} {a} \\[2ex]
\text{Esto es, una suma infinita de terminos, por criterio del término n-ésimo la serie diverge} \\[8ex]

\text{Entonces:} \\[3ex]

\bullet   \hspace{2ex}   \bold{|r| < 1 }  \hspace{2ex}   \Rightarrow   \hspace{2ex}   \textbf{la serie converge}   \\[2ex] 
\bullet   \hspace{2ex}   \bold{|r| \ge 1 }  \hspace{2ex}   \Rightarrow   \hspace{2ex}   \textbf{la serie diverge}   \\[2ex] 

%TODO:: Modificar el calculo y poner en horizontal

$$


<br>
<a name="Series_P"></a>
<h5 style="font-size:16px;color:#e65140">2- Series P</h5>

$$

\text{ sea } k > 0 \\[2ex]

\text{Las series P son de la forma: } \\[2ex]

\sum_{n=0}^{\infty} {\frac{1}{n^p}} \\
\text{Donde } p > 0 \\[2ex]

\text{Aplicamos criterio de la integral} \\[6ex]

f(x) = a_n \text{ para todo } n \in \mathbb{R}\\[2ex]
f(x) = \frac{1}{x^P} \\[2ex]

\int_{1}^{\infty} {\frac{1}{x^p} dx} = \int_{1}^{\infty} {x^{-p} dx} \\[6ex]


\textbf{Si } \bold{ p < 1} \\[2ex]

\int_{1}^{\infty} {x^{-p} dx} = \left. \frac{x^{(-p+1)}}{-p+1} \right|_{1}^{\infty} = \frac{\infty^{(k)}}{-p+1} -   \frac{1^{(k)}}{-p+1}  = \frac{\infty}{-p+1} -   \frac{1}{-p+1}  = \infty - \frac{1}{-p+1} = \bold{\infty} \\[6ex]

\textbf{Si } \bold{ p > 1} \\[2ex]

\int_{1}^{\infty} {x^{-p} dx} = \left. \frac{x^{(-p+1)}}{-p+1} \right|_{1}^{\infty} = \frac{\infty^{(-k)}}{-p+1} -   \frac{1^{(-k)}}{-p+1}  = \frac{\frac{1}{\infty^k} }{-p+1} -   \frac{1}{-p+1}  = \frac{0 }{-p+1} -   \frac{1}{-p+1}   = 0 - \frac{1}{-p+1} = - \bold{\frac{1}{-p+1}} \\[6ex]

\textbf{Si } \bold{ p = 1} \\[2ex]

\int_{1}^{\infty} {x^{-1} dx} = \left. ln(x) \right|_{1}^{\infty} = ln(\infty) - ln(1) = \infty - 0 = \bold{\infty}

\\[8ex] 

\text{Entonces:}\\[3ex]

\bullet   \hspace{2ex}   \bold{p > 1 }  \hspace{2ex}   \Rightarrow   \hspace{2ex}   \textbf{la serie converge}   \\[2ex] 
\bullet   \hspace{2ex}   \bold{p \le 1 }  \hspace{2ex}   \Rightarrow   \hspace{2ex}   \textbf{la serie diverge}   \\[2ex] 

$$

<br>
<a name="Series_notables"></a> 
<h3 style="font-size:16;font-style:italic;color:blue">Series notables</h3>


* Serie armonica

$$
\sum_{n=0}^{\infty} {\frac{1}{n}}    \hspace{10ex}   \text{la serie diverge por criterio de la integral}
$$

* Serie armonica alternante

$$
\sum_{n=0}^{\infty} {(-1)^n \frac{1}{n}}    \hspace{10ex}   \text{la serie converge por el criterio de Leibniz}
$$


<br>

<a name="Series_de_potencias"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Series de potencias</h2>


Son series de la forma

$$
\sum_{n=0}^{\infty} {a_n (x-c)^n}
$$

Donde a<sub>n</sub> es una suceción y c es el centro de la serie. Si la serie esta centrada en 0, se la llama **serie de McLaurin**

A diferencia de una serie normal, al tomar el límite de este tipo de series obtendremos una función en lugar de un valor.




<br>
<a name="Convergencia_y_divergencia"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Convergencia y divergencia</h3>

A diferencia de una serie normal, al tomar el límite de este tipo de series veremos que se aproximan a una función en lugar de a un varlor.

Ej:

$$
\sum_{n=0}^{\infty} {4 (x-2)^n}  =  \frac{4}{1- (x-2)} = \bold{\frac{4}{3-x}} \\[3px]
\text{La serie se aproxima a una función en lugar de a un valor, se cumple para un intervalo I} \\[2ex]
\text{A esta funcion se la llama funcion de convergencia}
$$

Una serie de potencias converjera a una función solo dentro de un intervalo dado, por fuera de dicho intervalo la serie crecera de forma indefinida u oscilara de forma permante. Este intervalo recibe el nombre de **radio de convergencia**

Para hallar este radio, debemos aplicar algun criterio de convergencia y evaluar para que valores de x se cumplen las condiciones de convergencia

Si bien es facil hallar el intervalo de convergencia de una serie, resulta muy dificil encontrar a que función convergen. Esto solo será sencillo para series geometricas

<br>
<a name="Ej_1"></a>
<h6 style="font-size:14px;color:green">Ej 1: </h6>

$$

\text{Hallar intervalo de convergencia de } \\[4ex]
\sum_{n=1}^{\infty} {\frac{x^n}{n}} \\[4ex]
\text{Aplicamos teorema de D'alambert } \\[4ex]

\lim_{n \rightarrow \infty} { \left| \frac{a_{n+1}}{a_n}\right|} = 
\lim_{n \rightarrow \infty} { \left|  \frac{  \frac{x^{n+1}}{n+1}  }{  \frac{x^n}{n}  }   \right|} =
\lim_{n \rightarrow \infty} \left| \frac{x^n x n}{x^n (n+1)} \right| =
\lim_{n \rightarrow \infty} \left| \frac{x n}{n+1} \right| =
\lim_{n \rightarrow \infty} \left| \frac{x}{1+\frac{1}{n}} \right| =
\left| \frac{x}{1+0} \right| =
\bold{ \left| x \right|}
\\[4ex]



\text{Para que la serie converga, debe cumplirse que} \\[2ex]

\lim_{n \rightarrow \infty} { \left| \frac{a_{n+1}}{a_n}\right|}  < 1 \\[2ex]

\text{Entonces, para que la serie de potencias converga, debe cumplirse que:} \\[2ex]

\hspace{6ex} \left| x \right| < 1 \\[1ex]
\bold{-1 <  x < 1} \\[2ex]

\text{La sere convergera cuando x se encuentre entre -1 y 1. A continuacion debemos evaluar si la serie converge en los extremos, ya que para estos valores el criterio no decide} \\[4ex]

x=1 \\[2ex]

\sum_{n=0}^{\infty} {\frac{1^n}{n}} = \sum_{n=0}^{\infty} {\frac{1}{n}} \rightarrow \text{ Diverge (serie armonica)} 
\\[4ex] 

x=-1 \\[2ex]

\sum_{n=0}^{\infty} {\frac{(-1)^n}{n}} \rightarrow \text{ converge (serie armonica alternante)} 
\\[6ex]

\textbf{Luego, la serie converge para } \bold{x \in [-1,1)}
$$


<br>
<a name="Ej_2"></a>
<h6 style="font-size:14px;color:green">Ej 2 </h6>

$$

\text{Hallar intervalo de convergencia de } \\[4ex]
\sum_{n=0}^{\infty} {\frac{2 x^n}{5^{n+1}}}  \\[4ex]
\text{Usamos el criterio de series geometricas } \\[4ex]

\sum_{n=0}^{\infty} {\frac{2 x^n}{5^{n+1}}}  = \sum_{n=0}^{\infty} {\frac{2}{5} \left( \frac{x}{5} \right)^n}  \rightarrow a=\frac{2}{5}   \hspace{1ex} ; \hspace{1ex}   r = \frac{x}{5}   \\[4ex] 

\sum_{n=0}^{\infty} {\frac{2 x^n}{5^{n+1}}} = \frac{\frac{2}{5}}{1- \frac{x}{5}} = \bold{ \frac{2}{5-x} } \\[4ex]

\text{Ya que la serie es geometrica, sabemos que la convergencia se da cuando: }\\[4ex]
\hspace{25px} \left| r \right| < 1 \\[2ex]
\hspace{25px} \left| \frac{x}{5} \right| < 1 \\[2ex]
-1 < \frac{x}{5} < 1 \\[2ex]
\bold{-5 < x < 5} 
\\[6ex]

\textbf{Luego, la serie converge para } \bold{x \in (-5,5)}

$$

<br>

Si bien es facil hallar el intervalo de convergencia de una serie, resulta muy dificil encontrar a que función convergen. Esto solo será sencillo para series geometricas

<br>
<a name="Resolver_integrales_con_series"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Resolver integrales con series</h3>

En algunas ocaciones, nos encontraremos con integrales que no poseen una primitiva, por lo que no podemos resolverlas de la forma convencional. Sin embargo, podemos aproximar su resultado mediante el uso de series

<br>
<a name="Ej_1"></a>
<h6 style="font-size:14px;color:green">Ej 1</h6>

$$

\int_{a}^{b} {\frac{2x}{5-x}dx} = \int_{a}^{b} {x \frac{2}{5-x}dx}  \\[4ex]

\text{Vemos que } \frac{2}{5-x} \text{ presenta la estructura de la funcion convergente de una serie geometrica, luego podemos afirmar que} \\[4ex]

\frac{2}{5-x} = \sum_{n=0}^{\infty}{2 x^n} \\[4ex]

\text{Ahora, podemos reescribir la integral como} \\[4ex]

\int_{a}^{b} {\frac{2x}{5-x}dx} = \int_{a}^{b} 2  \sum_{n=0}^{\infty}{2 x^n} \approx  \int_{a}^{b} 2  \sum_{n=0}^{k}{2 x^n}  \\[4ex]

\text{Vemos que el último termino es una aproximación de la integral original, mientras mayor sea k mejor será la aproximación} \\[1ex]
\text{También debe tenerse en cuenta que solo se podra aproximar para valores que se encuentren en el radio de convergencia de la serie. En caso de que el intervalo de integración quede fuera del radio de convergencia, debera desplazarse la serie}

$$


<br>
<a name="Ej_2"></a>
<h6 style="font-size:14px;color:green">Ej 2</h6>

$$

\int_{a}^{b} {\frac{sin(x)}{x} dx} \\[4ex]

\text{Vemos que } sin(x) \text{ puede expresarse como una serie, luego podemos rescribir la integral como}\\[4ex]

\int_{a}^{b} {\frac{sin(x)}{x} dx} = 
\int_{a}^{b} {\frac{1}{x} \sum_{n=0}^{\infty} { \frac{(-1)^n}{(2n-1)!}x^{(2n-1)}}} dx \approx
\int_{a}^{b} {\frac{1}{x} \sum_{n=0}^{k} { \frac{(-1)^n}{(2n-1)!}x^{(2n-1)}}} dx \\[4ex]

\text{Ahora podemos aproximar una integral sin primitiva, a mayor k mejor sera la aproximación.}

$$

<br>
<a name="Criterio_de_D'Alambert_modificado"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Criterio de D'Alambert modificado</h3>

Este criterio es una version modificada, diseñada especificamente para series de potencias. Utilizar este criterio tiene la ventaja de simplificar en gran medida los calculos

En este caso, obtendremos un resultado que sera igual al inverso multiplicativo del radio de convergencia. El centro de convergencia puede deducirse de la misma expresion

$$
\text{Dada una serie de potencias:} \\[2ex]
\sum_{n=0}^{\infty} {c_n (x-a)^n} \\[2ex]
\text{Tomamos el límite y obtenemos} \\[2ex]
\lim_{n \rightarrow \infty} {\left|    \frac{c_{n+1}}{c_n}      \right|} = L \\[2ex]
\text{Donde } L = \frac {1}{R}
$$

<br>
<a name="Ej"></a>
<h6 style="font-size:14px;color:green">Ej</h6>

$$

\text{Determine el intervalo de convergencia de } \\[2ex]
\sum_{n=1}^{\infty} {\frac{(-1)^n (x-5)^{n-1}}{n5^n}} = 
\sum_{n=1}^{\infty} {\frac{(-1)^n}{n5^n  (x-5)}} (x-5)^{n} \\[2ex]

\text{Del resultado anterior se tiene que el centro es x=5} \\[2ex]
\text{Tomamos limite} \\[2ex]

\lim_{n \rightarrow \infty} \left|  \frac{  
\frac{(-1)^{(n+1)}}{(n+1)5^n 5 (x-5)}  }    {\frac{(-1)^n}{n5^n  (x-5)}}   \right|  =

\lim_{n \rightarrow \infty} \left|  \frac{  
\frac{1}{(n+1)5^n 5 (x-5)}  }    {\frac{1}{n5^n  (x-5)}}   \right|  =

\lim_{n \rightarrow \infty} \left| \frac{n5^n  (x-5)}{(n+1)5^n 5 (x-5)} \right| =

\lim_{n \rightarrow \infty} \left| \frac{n }{(n+1) 5 } \right|  = 

\lim_{n \rightarrow \infty} \left| \frac{n }{5n+5 } \right|  = 

\bold{\frac{1}{5}} \\[2ex]

\text{Luego, se tiene que } R=5 \text{. Evaluamos en los extremos: x=0 ; x=10} \\[4ex]

\text{x=0} \\[2ex]
\sum_{n=0}^{\infty}{\frac{(-1)^n(-5)^n(-5)^{-1}}{n5^n}} = \sum_{n=0}^{\infty}{\frac{-1}{5n} \left(     \frac{(-1)(-5)}{5}     \right)^n}  = 
\sum_{n=0}^{\infty}{\frac{-1}{5} \frac{1}{n} \left(    1    \right)^n} = 
\frac{-1}{5} \sum_{n=0}^{\infty}{ \frac{1}{n}} \\[2ex]
\text{Se obtiene la serie armonica, luego la serie } \textbf{diverge } \text{ para } x=0 \\[4ex]

\text{x=10} \\[2ex]
\sum_{n=0}^{\infty}{\frac{(-1)^n(5)^n(5)^{-1}}{n5^n}} = \sum_{n=0}^{\infty}{\frac{1}{5n} \left(     \frac{(-1)(5)}{5}     \right)^n}  =  
\sum_{n=0}^{\infty}{\frac{1}{5} \frac{1}{n} \left(    -1    \right)^n} = 
\frac{1}{5} \sum_{n=0}^{\infty}{ \frac{(-1)^n}{n}} \\[2ex]
\text{Se obtiene la serie armonica alternante, luego la serie } \textbf{converge } \text{ para } x=10 \\[6ex]

\text{Luego, la serie } \sum_{n=1}^{\infty} {\frac{(-1)^n (x-5)^{n-1}}{n5^n}} \text{ converge para el intervalo } \bold{ (0;10] } \\[4ex]

\text{Nota: Para los extremos de intervalos no conviene evaluar utilizando D'Alambert }
$$


<br>
<a name="Series_de_Taylor"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Series de Taylor</h2>

Una serie de Taylor es una forma de aproximar una funcion mediante una suma infinita de potencias de polinomios como $(x-a)^n$.

Este tipo de series busca aproximar a una funcion imitando el valor de todas las tasas de cambio de una funcion en un punto dado $a$, llamado centro.

Entonces, las series de taylor toman la forma:

$$

\sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n \\[4ex]

\text{Donde } f^{(n)}(x) \text{ representa la n-esima derivada de la función}

$$

<br>
<a name="Series_de_Taylor_notables"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Series de Taylor notables</h3>

* Centrado en 0
	* $\frac{1}{1-x} = \sum_{n=0}^{\infty} {x^n}$
	* $\sin(x) = \sum_{n=0}^{\infty} {\frac{(-1)^n}{(2n+1)!} x^{2n+1}}$
	* $\cos(x) = \sum_{n=0}^{\infty} {\frac{(-1)^n}{(2n)!} x^{2n}}$
	* $e^{x} = \sum_{n=0}^{\infty} {\frac{x^n}{n!} }$
* Centrado en 1
	* $ln(x) = \sum_{n=1}^{\infty}{(-1)^{n+1}\frac{(x-1)^n}{n}}$
* Centrado en a
	* $ln(x) = ln(a) + \sum_{n=1}^{\infty}{(-1)^{n+1}\frac{(x-a)^n}{na^n}}$


<br>
<a name="Series_de_Taylor_para_funciones_compuestas"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Series de Taylor de para funciones compuestas</h3>


A la hora de representar funciones compuestas como series, podemos hacerlo representando la serie de la funcion mas externa evaluada en el resto de funciones

<a name="Ej"></a>
<h6 style="font-size:14px;color:green">Ej</h6>

$$

\text{Hallar la serie asociada a:} \\[2ex]
{f(x) = e^{x^2}} \\[2ex]
\text{Podemos reescribir f(x) como g(h(x)), donde} \\[2ex]
g(x)= e^x \\
h(x) = x^2 \\[2ex]
\text{Sabemos que } g(x) \text{puede expresarse como una serie} \\[2ex]
g(x) = e^{x} = \sum_{n=0}^{\infty} {\frac{x^n}{n!} } \\[2ex]

\text{Entonces, la composicion } g(h(x)) \text{ puede reescribirse como} \\[2ex]

g(h(x)) = \sum_{n=0}^{\infty} {\frac{(h(x))^n}{n!} } =  \sum_{n=0}^{\infty} {\frac{(x^2)^n}{n!} } = \bold{\sum_{n=0}^{\infty} {\frac{x^{2n}}{n!}}} \\[2ex]

\text{Luego, se tiene que } \\[2ex]

e^{x^2} = \sum_{n=0}^{\infty} {\frac{x^{2n}}{n!}}\\[2ex]

\text{No tuvimos que derivar la expreison compuesta, con la que se obtienen derivadas muy complejas, en su lugar solo debimos descomponer la composicion y trabajar con la expresion mas externa, haciendo el proceso mas sencillo.}

$$


<br>
<a name="Trasladar_centro_de_serie"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Trasladar centro de serie</h3>

<a name="Series_de_Taylor_compuesta"></a>
<h4 style="font-size:16px;color:#FF7F00">Series de Taylor compuesta</h4>

Si queremos trasladar el centro de una serie de Taylor compuesta, , debemos modificar la expresión original de forma tal que el  termino $x$ pase a ser $(x-a)$.

<a name="Ej_1"></a>
<h6 style="font-size:14px;color:green">Ej 1</h6>


$$
\text{Dada la función } \\[2ex]
e^{2x} \\[2ex]
\text{Trasladar su centro a } x=3 \\[2ex]
e^{2x} = e^{2(x-3+3)} = e^{2(x-3) + 6} = e^{2(x-3)} e^6 \\[2ex]
\text{Vemos que la función sigue siendo la misma, sin embargo convertimos el término } x \text{ a } (x-a) \\[2ex]
\text{Planteamos la función como una composición: }\\[2ex]
f(x) = e^{x} \\[2ex]
g(x) = 2(x-3) \\[2ex]
f(g(x)) = e^{2(x-3)} \\[2ex]
e^6 f(g(x))  = e^6  e^{2(x-3)} = e^{2x} \\[2ex]

\text{Buscamos la serie de la función mas externa} \\[2ex]

f(x) = \sum_{n=0}^{\infty}  \frac{x^n}{n!} \\[2ex]
f(g(x)) = \sum_{n=0}^{\infty}  \frac{g(x)^n}{n!} \\[2ex]
f(g(x)) = \sum_{n=0}^{\infty}  \frac{(2(x-3))^n}{n!} \\[2ex]
e^6 f(g(x)) = e^6 \sum_{n=0}^{\infty}  \frac{(2(x-3))^n}{n!} \\[4ex]
\bold{
e^6 e^{2(x-3)} = e^6 \sum_{n=0}^{\infty}  \frac{(2(x-3))^n}{n!} \\[2ex]
}
$$

<a name="Ej_2"></a>
<h6 style="font-size:14px;color:green">Ej 2</h6>

$$
\text{Dada la función } \\[2ex]
ln(1+x) \\[2ex]
\text{Trasladar su centro a } x=4 \\[2ex]
ln(1+x) = ln(1+(x-4+4)) = ln(5+(x-4))  \\[2ex]
\text{Vemos que la función sigue siendo la misma, sin embargo convertimos el término } x \text{ a } (x-a) \\[2ex]
\text{Planteamos la función como una composición: }\\[2ex]
f(x) = ln(5+x) \\[2ex]
g(x) = (x-4) \\[2ex]
f(g(x)) = ln(5 +(x-4))  = ln(1+x) \\[2ex]
\text{Buscamos la serie de la función mas externa} \\[2ex]
f(x) = ln(5) + \sum_{n=1}^{\infty} \frac{1}{5^n n} (-1)^{(n+1)} x^n \\[2ex]
f(g(x)) = ln(5) + \sum_{n=1}^{\infty} \frac{1}{5^n n} (-1)^{(n+1)} (g(x))^n \\[2ex]
f(g(x)) = ln(5) + \sum_{n=1}^{\infty} \frac{1}{5^n n} (-1)^{(n+1)} (x-4)^n \\[2ex]
\bold{
ln(5+(x-4))= ln(5) + \sum_{n=1}^{\infty} \frac{1}{5^n n} (-1)^{(n+1)} (x-4)^n
}
$$
 
<br>
<br>

Por otro lado, si queremos modificar el centro de una serie geometrica asociada a una función, debemos modificar la estructura de esta función para desplazar la estructura de la serie asociada.


<a name="Series_geometricas"></a>
<h4 style="font-size:16px;color:#FF7F00">Series geometricas</h4>

<a name="Ej"></a>
<h6 style="font-size:14px;color:green">Ej</h6>


$$
\text{Dada la función} \\[2ex]
f(x) = \frac{2}{5-x} \\[2ex]
\text{Hallar su serie asociada con centro en } x=8 \\[2ex]
\text{Vemos que la funcion tiene la forma de la convergencia de una serie geometrica, pero en este caso estara centrada en 0. Para centrarla en 8 debemos realizar operaciones sobre la función de forma tal que esta no se vea modificada} \\[2ex]

\frac{2}{5-x} = \frac{2}{5-(x-8+8)} = \frac{2}{5-(x-8) - 8} = \frac{2}{-3-(x-8)} 
= \frac{2}{-3-(x-8) } \frac{\frac{1}{-3}}    {\frac{1}{-3}} = 
\frac{ \frac{-2}{3}   }{1-((\frac{1}{-3})(x-8)) }  \\[2ex]

\text{Vemos que } \\[2ex] 
\frac{2}{5-x}  = \frac{ \frac{-2}{3}   }{1-((\frac{1}{-3})(x-8)) } \\[2ex]
\text{A pesar de representar la misma función, cada una genera una serie geometrica distinta} \\[2ex]

\bullet \hspace{2ex} \frac{2}{5-x} = \sum_{n=0}^{\infty} { \frac{2}{5} \left(   \frac{x}{5}   \right)^n } \\[2ex]

\bullet \hspace{2ex} \frac{ \frac{-2}{3}   }{1-((\frac{1}{-3})(x-8)) } =  \sum_{n=0}^{\infty} \frac{-2}{3} \left(  \frac{-(x-8)}{3}    \right)  \\[2ex]


\text{Ambas series convergen a la misma funcion, pero tienen distintos centros y convergen en intervalos distintos} \\[2ex]


\bullet \hspace{2ex}  \sum_{n=0}^{\infty} { \frac{2}{5} \left(   \frac{x}{5}   \right)^n } \text{ tiene centro en } x=0 \text{ y converge en } (-5,5) \text{, su radio vale } 5 \\[2ex] 

\bullet \hspace{2ex}  \sum_{n=0}^{\infty} \frac{-2}{3} \left(  \frac{-(x-8)}{3}    \right)  \text{ tiene centro en } x=8 \text{ y converge en } (5,11) \text{, su radio vale } 3

$$

<br>

<a name="Series_de_fourier"></a>
<h2 style="font-size:20px;text-align:center;color:purple">Series de fourier</h2>

Serie utilizada para para analizar funciones periódicas a través de la descomposición de dicha función en una suma infinita de funciones sinusoidales mucho más simples

Recordemos que una función periodica si verifica que $f(x) = f(x+T)$, donde $T$ es el periodo fundamenta, es decir, el periodo de menor valor

* **Periodo fundamental:**	valor mas pequeño que cumple $f(x) = f(x+T)$, el resto de periodos son productos escalares de este periodo fundamental.
* **Frecuencia:**			Cuantas veces se completa un periodo por unidad del término independiente, es el inverso multiplicativo del periodo fundamental.

<br>

Dos importates series periodicas son el seno y el coseno, Podemos definir a la función seno y coseno con un periodo o frecuencia especifico:

$sin(2\pi F x) ; cos(2\pi F x)$
$\text{Donde F es la frecuencia}$
<br>
$sin(\frac{2\pi x}{p}) ; cos(\frac{2\pi x}{p})$
$\text{Donde p es el periodo fundamental}$

<br>
<a name="Producto_escalar_entre_funciones"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Producto escalar entre funciones</h3>

Dadas dos funciones $f$ y $g$ definidas e integrables en $[a,b]$, se define el producto escalar usual entre ellas como:

$$
\int_{a}^b {f(x)g(x)dx}
$$

Cuando el producto escalar entre dos funciones en un intervalo $[a,b]$ es 0, de dice que dichas funciones son **ortogonales en el intervalo [a,b]**

<br>
<a name="Familia_ortogonal_de_funciones_en_[a,b]"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Familia ortogonal de funciones en [a,b]</h3>

Dado un conjunto de funciones, estas representaran una familia ortogonal de funciones en [a,b] si todas son ortogonales entre si en dicho intervalo

La única familia ortogonal de funciones con la que se trabajara será con la familia trigonométrica:

$$
\bigg\{1, cos \left( \frac{n\pi x}{p} \right), sin \left( \frac{n\pi x}{p} \right), n=1,2,3... \bigg\}
$$

Esta familia es ortogonal en el intervalo $[-p,-p]$ o $[0,2p]$, por lo que su periodo fundamental de cada función es $\frac{2p}{n}$

<br>
<a name="Justificación_del_periodo"></a>
<h4 style="font-size:16px;color:#FF7F00">Justificación del periodo</h4>

A continuación analizaremos porque el periodo toma dichos valores

Sabemos que podremos definir una función seno con periodo especifico de la siguiente forma:
$$
sin \left(    \frac{2\pi x}{p}    \right) (1)
$$
Si queremos encontrar el periodo fundamental de las funciones de la familia trigonometrica, debemos deasarrollar el argumento de la familia hasta llegar a una expresion con la misma estructura que el argumento en (1)

$$
 \frac{n\pi x}{p} =   \frac{n\pi x}{p} \frac{2}{2} =
 \frac{1}{\frac{1}{n}}\frac{2\pi x}{2p} =
 \bold{    \frac{2\pi x}{\frac{2p}{n}}    }
$$

Vemos que llegamos a la misma estructura que en (1). De aqui se deduce que el periodo de cada función sera será  $\frac{2p}{n}$


<br>
<a name="Demostración:_la_familia_trigonometrica_es_ortogonal_en_[-p,p]"></a>
<h4 style="font-size:16px;color:#FF7F00">Demostración: la familia trigonometrica es ortogonal en [-p,p]</h4>


$$
\text{Se demostrará para el intervalo [-p,p], la resulucion para el intervalo [0,2p] es análoga} \\[2ex]

\text{1) 1 y coseno} \\[2ex]

\int_{-p}^{p} { cos \left( \frac{n\pi x}{p} \right) 1 dx } = 
\left. \frac{p}{n\pi } sin  \left( \frac{n\pi x}{p} \right)    \right|_{-p}^{p} =
\frac{p}{n\pi } sin  \left( \frac{n\pi p}{p} \right) -  \frac{p}{n\pi } sin  \left( \frac{-n\pi p}{p} \right) = 
\frac{p}{n\pi } sin  \left( n\pi  \right) -  \frac{p}{n\pi } sin  \left( -n\pi  \right) =
\frac{p}{n\pi } 0 - \frac{p}{n\pi } 0 = \bold{ 0 } 
\\[6ex]


\text{2) 1 y seno} \\[2ex]
\int_{-p}^{p} { sin \left( \frac{n\pi x}{p} \right) 1 dx } = 
\left.  -cos  \left( \frac{n\pi x}{p} \right) \frac{p}{n\pi }    \right|_{-p}^{p} =
-cos  \left( \frac{n\pi p}{p} \right) \frac{p}{n\pi }  - \left(   -cos  \left( \frac{-n\pi p}{p} \right) \frac{p}{n\pi }   \right)= 
-cos  \left(    n\pi    \right)  \frac{p}{n\pi } +cos  \left( -n\pi  \right) \frac{p}{n\pi }   = 
-cos  \left(    n\pi    \right)  \frac{p}{n\pi } +cos  \left( n\pi  \right) \frac{p}{n\pi } =
\bold{0} 
\\[6ex]

\text{3) seno y coseno con igual n} \\[2ex]

\int_{-p}^{p}  sin \left( \frac{n\pi x}{p} \right)  cos \left( \frac{n\pi x}{p} \right) dx \\[4ex]

\text{Planteamos la sustitución} \\[2ex]
u=sin \left(    \frac{n\pi x}{p}    \right) ; 
du = \frac{n\pi}{p} sin \left(    \frac{n\pi x}{p}    \right) \\[2ex]
\text{Buscamos la antiderivada} \\[2ex]

\int  \sin \left( \frac{n\pi x}{p} \right)  \cos \left( \frac{n\pi x}{p} \right) dx  = 
\int  u \frac{p}{n \pi} du =
 \frac{p}{2n\pi}u^2 = 
 \frac{p}{2n\pi} \sin^2 \left( \frac{n\pi x}{p} \right) \\[4ex]
 
 \text{Resolvemos la integral definida} \\[2ex]
 
 
\int_{-p}^{p}  sin \left( \frac{n\pi x}{p} \right)  cos \left( \frac{n\pi x}{p} \right) dx =  
\left.    \frac{p}{2n\pi} \sin^2 \left( \frac{n\pi x}{p} \right)    \right|_{-p}^{p} = 
 \frac{p}{2n\pi} \sin^2 \left( \frac{n\pi p}{p} \right)  -  \frac{p}{2n\pi} \sin^2 \left( \frac{-n\pi p}{p} \right) =
 \frac{p}{2n\pi} \sin^2 \left( n\pi \right) -  \frac{p}{2n\pi} \sin^2 \left( -n\pi \right)  = 0 - 0 = \bold{0}
 \\[6ex]
 
 \text{seno y coseno con distinto n} \\[2ex]
\int_{-p}^{p}  sin \left( \frac{n\pi x}{p} \right)  cos \left( \frac{m\pi x}{p} \right) dx \\[4ex]

\text{Usamos la identidad} \\[2ex]

\sin(\alpha) \sin(\beta) = \frac{1}{2}(\sin(\alpha + \beta) + \sin(\alpha -\beta)) \\[4ex]

\int_{-p}^{p}  sin \left( \frac{n\pi x}{p} \right)  cos \left( \frac{m\pi x}{p} \right) dx = 
\frac{1}{2} \int_{-p}^{p}   \left(
\sin \frac{(m+n)\pi x}{p} + \sin \frac{(m-n)\pi x}{p}
\right) dx =
\frac{1}{2} \left(   
\int_{-p}^{p}  sin \left({\frac{k_1 \pi x}{p}} \right)  -  \int_{-p}^{p}  sin \left({\frac{k_2 \pi x}{p}} \right) 
\right) \\[2ex]
\text{Se obtuvo una suma de integrales equivalentes a las integrales resueltas en 2), por lo que sabemos que sus resultados seran 0} \\[2ex]

\frac{1}{2} \left(   
\int_{-p}^{p}  sin \left({\frac{k_1 \pi x}{p}} \right)  -  \int_{-p}^{p}  sin \left({\frac{k_2 \pi x}{p}} \right) 
\right) =

\frac{1}{2}  (0 - 0) = \bold{0} \\[6ex]

\text{Queda así demostrado que la familia trigonometrica es ortogonal}

$$

<br>
<a name="Desarrollo_de_series_de_fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Desarrollo de series de fourier</h3>

$$

\text{Dada la familia de funciones trigonometrica} \\[2ex]
\bigg\{1, cos \left( \frac{n\pi x}{p} \right), sin \left( \frac{n\pi x}{p} \right), n=1,2,3... \bigg\} \\[2ex]
\text{Dada una función f definida en el mismo intervalo, se buscara obtener esta función como una combinación lineal de los elementos de la familia trignonométrica} \\[2ex]

f(x) = c_0 1 + a_1 \cos \left( \frac{1\pi x}{p} \right) +   b_1 \sin \left( \frac{1\pi x}{p} \right) + a_2 \cos \left( \frac{2\pi x}{p} \right) +   b_2 \sin \left( \frac{2\pi x}{p} \right) + \dots  a_n \cos \left( \frac{n\pi x}{p} \right) +   b_n \sin \left( \frac{n\pi x}{p} \right) \\[2ex]

\text{Ahora, debemos encontrar una manera de hallar los valores }c_0, a_n, b_n \text{, Para esto, realizaremos el siguiente desarrollo} \\[12ex]

\text{1- Despejamos } c_0\\[2ex]

f(x) = c_0 1 + a_1 \cos \left( \frac{1\pi x}{p} \right) +   b_1 \sin \left( \frac{1\pi x}{p} \right) + a_2 \cos \left( \frac{2\pi x}{p} \right) +   b_2 \sin \left( \frac{2\pi x}{p} \right) + \dots  a_n \cos \left( \frac{n\pi x}{p} \right) +   b_n \sin \left( \frac{n\pi x}{p} \right) \\[2ex]

\text{Aplicamos integral entre -p y p a ambos lados de la igualdad} \\[2ex]

\int_{-p}^p f(x) dx = \int_{-p}^p  c_0 1 dx + \int_{-p}^p  a_1 \cos \left( \frac{1\pi x}{p} \right) dx + \int_{-p}^p  b_1 \sin \left( \frac{1\pi x}{p} \right) dx +  \dots \int_{-p}^p a_n \cos \left( \frac{n\pi x}{p} \right) dx + \int_{-p}^p  b_n \sin \left( \frac{n\pi x}{p} \right) dx \\[2ex]

\text{vemos ahora, que la mayoría de integrales representan la integral del producto de dos elementos de la familia trigonometrica, en este caso 1 y alguna variante del seno o coseno. Por lo que todos los terminos, exceptuando el primero, daran como resultado 0  } \\[2ex]

\int_{-p}^p f(x) dx = \int_{-p}^p  c_0 1 dx + 0 + 0 + \dots + 0 + 0 \\[2ex]
\int_{-p}^p f(x) dx =\int_{-p}^p  c_0 1 dx \\[2ex]
\int_{-p}^p f(x) dx = \int_{-p}^p  c_0 1 dx \\[2ex]
\int_{-p}^p f(x) dx = 2p c_0 \\[4ex]
\bold{ c_0 = \frac{1}{2p} \int_{-p}^p f(x) dx }\\[2ex]

\text{Obtuvimos asi el valor de }c_0,  \text{realizamos un proceso análogo para el seno y el coseno}\\[12ex]

%______________________________________________________

\text{2- Despejamos } a_m\\[2ex]

\text{Multiplicamos ambos lados por } \cos \left( \frac{m\pi x}{p} \right)  \text{, donde } 1 \le m \le n  \\[2ex]

f(x) \cos \left( \frac{m\pi x}{p} \right)  = 
c_0 1 + a_1 \cos \left( \frac{1\pi x}{p} \right) +   b_1 \sin \left( \frac{1\pi x}{p} \right) + \dots a_m \cos \left( \frac{m\pi x}{p} \right) +   b_m \sin \left( \frac{m\pi x}{p} \right) + \dots  a_n \cos \left( \frac{n\pi x}{p} \right) +   b_n \sin \left( \frac{n\pi x}{p} \right) \\[2ex]


f(x) \cos \left( \frac{m\pi x}{p} \right) 
= c_0 \cos \left( \frac{m\pi x}{p} \right)  1 + 
a_1 \cos \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{1\pi x}{p} \right) +  
b_1 \cos \left( \frac{m\pi x}{p} \right)  \sin \left( \frac{1\pi x}{p} \right) + 
\dots a_m \cos^2 \left( \frac{m\pi x}{p} \right) +  
b_m \cos \left( \frac{m\pi x}{p} \right)  \sin \left( \frac{m\pi x}{p} \right) +
\dots  a_n \cos \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{n\pi x}{p} \right) +   
b_n \cos \left( \frac{m\pi x}{p} \right)   \sin \left( \frac{n\pi x}{p} \right) \\[2ex]

\text{Aplicamos integral entre -p y p a ambos lados de la igualdad} \\[2ex] \\[2ex]

\int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right) 
= \int_{-p}^{p} c_0 \cos \left( \frac{m\pi x}{p} \right)  1 + 
\int_{-p}^{p} a_1 \cos \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{1\pi x}{p} \right) +  
\int_{-p}^{p} b_1 \cos \left( \frac{m\pi x}{p} \right)  \sin \left( \frac{1\pi x}{p} \right) + 
\dots \int_{-p}^{p} a_m \cos^2 \left( \frac{m\pi x}{p} \right) +  
\int_{-p}^{p} b_m \cos \left( \frac{m\pi x}{p} \right)  \sin \left( \frac{m\pi x}{p} \right) +
\dots  \int_{-p}^{p}  a_n \cos \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{n\pi x}{p} \right) +   
\int_{-p}^{p} b_n \cos \left( \frac{m\pi x}{p} \right)   \sin \left( \frac{n\pi x}{p} \right) \\[2ex] 


\text{Ya que todas las funciones son ortogonales a }  \cos \left( \frac{m\pi x}{p} \right)  \text{ en [-p,p], todas las integrales se cancelaran. exceptuando el caso donde } \cos \left( \frac{m\pi x}{p} \right)  \text{ multiplica a } \cos \left( \frac{m\pi x}{p} \right) \\[2ex]


\int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  = 0+ 0 + 0 + \dots \int_{-p}^{p} a_m \cos^2 \left( \frac{m\pi x}{p} \right) +  0 + \dots 0 + 0  \\[2ex] 

\int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  dx = \int_{-p}^{p} a_m \cos^2 \left( \frac{m\pi x}{p} \right) dx \\[4ex]

\text{-----------------------------------------------------------------------} \\[2ex]

\text{Tras desarrollar la integral de la derecha, se tiene: }\\[2ex]
\int_{-p}^{p} a_m \cos^2 \left( \frac{m\pi x}{p} \right) dx = a_m p \\[2ex]
 
\text{-----------------------------------------------------------------------} \\[4ex]
 
\int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  dx = a_m p \\[2ex]
\bold{ a_m = \frac{1}{p} \int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  dx } \\[12ex]


%___________________________________________________

\text{3- Despejamos } b_m\\[2ex]

\text{Multiplicamos ambos lados por } \sin \left( \frac{m\pi x}{p} \right)  \text{, donde } 1 \le m \le n  \\[2ex]

f(x) \sin \left( \frac{m\pi x}{p} \right)
= c_0 1 + a_1 \cos \left( \frac{1\pi x}{p} \right) +   b_1 \sin \left( \frac{1\pi x}{p} \right) + \dots a_m \sin \left( \frac{m\pi x}{p} \right) +   b_m \sin \left( \frac{m\pi x}{p} \right) + \dots  a_n \cos \left( \frac{n\pi x}{p} \right) +   b_n \sin \left( \frac{n\pi x}{p} \right) \\[2ex]


f(x) \sin \left( \frac{m\pi x}{p} \right) 
= c_0 \sin \left( \frac{m\pi x}{p} \right)  1 + 
a_1 \sin \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{1\pi x}{p} \right) +  
b_1 \sin \left( \frac{m\pi x}{p} \right)  \sin \left( \frac{1\pi x}{p} \right) + 
\dots  \sin \left( \frac{m\pi x}{p} \right) a_m \cos \left( \frac{m\pi x}{p} \right) +  
b_m  \sin^2 \left( \frac{m\pi x}{p} \right) +
\dots  a_n \sin \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{n\pi x}{p} \right) +   
b_n \sin \left( \frac{m\pi x}{p} \right)   \sin \left( \frac{n\pi x}{p} \right) \\[2ex]

\text{Aplicamos integral entre -p y p a ambos lados de la igualdad} \\[2ex] \\[2ex]

\int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) 
= \int_{-p}^{p} c_0 \sin \left( \frac{m\pi x}{p} \right)  1 + 
\int_{-p}^{p} a_1 \sin \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{1\pi x}{p} \right) +  
\int_{-p}^{p} b_1 \sin \left( \frac{m\pi x}{p} \right)  \sin \left( \frac{1\pi x}{p} \right) + 
\dots \int_{-p}^{p} a_m \sin \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{m\pi x}{p} \right) +  
\int_{-p}^{p} b_m  \sin^2 \left( \frac{m\pi x}{p} \right) +
\dots  \int_{-p}^{p}  a_n \sin \left( \frac{m\pi x}{p} \right)  \cos \left( \frac{n\pi x}{p} \right) +   
\int_{-p}^{p} b_n \sin \left( \frac{m\pi x}{p} \right)   \sin \left( \frac{n\pi x}{p} \right) \\[2ex] 


\text{Ya que todas las funciones son ortogonales a }  \sin \left( \frac{m\pi x}{p} \right)  \text{ en [-p,p], todas las integrales se cancelaran. exceptuando el caso donde } \sin \left( \frac{m\pi x}{p} \right)  \text{ multiplica a } \sin \left( \frac{m\pi x}{p} \right) \\[2ex]


\int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right)
= 0+ 0 + 0 + \dots \int_{-p}^{p} b_m  \sin^2 \left( \frac{m\pi x}{p} \right) dx +  0 + \dots 0 + 0  \\[2ex] 

\int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) dx = \int_{-p}^{p} b_m  \sin^2 \left( \frac{m\pi x}{p} \right) dx \\[4ex]

\text{-----------------------------------------------------------------------} \\[2ex]

\text{Tras desarrollar la integral de la derecha, se tiene: }\\[2ex]
\int_{-p}^{p} b_m \sin^2 \left( \frac{m\pi x}{p} \right) dx = b_m p \\[2ex]
 
\text{-----------------------------------------------------------------------} \\[4ex]
 
\int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) dx = b_m p \\[2ex]
\bold{ b_m = \frac{1}{p} \int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) dx } \\[12ex]


%________________________________________________

\text{Ahora, tenemos una forma de expresar cada uno de los terminos:} \\[4ex]

\bold{ a_m = \frac{1}{p} \int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  dx } \\[4ex]
\bold{ b_m = \frac{1}{p} \int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) dx } \\[4ex]
\bold{ c_0 = \frac{1}{2p} \int_{-p}^p f(x) dx }\\[4ex]

\text{Vemos que la expresion }c_0 \text{ es muy similar a } a_m \text{ si se evaluase m en 0, por lo que usualmente se anota a } c_0 \text{ como:} \\[4ex]

\bold{ c_0 = \frac{a_0}{2}}\\[12ex]


\text{Conociendo ya los coeficientes, obtenidos a partir de una igualdad, podemos armar la serie de fourier:} \\[2ex]

f(x) \approx \approx \frac{a_0}{2} + \sum_{n=1}^{\infty}  \left(
a_n \left( \frac{n\pi x}{p} \right)    + 
b_n \left( \frac{n\pi x}{p} \right) 
\right) 
$$

<br>

Nota: el simbolo ≈≈ representa ~, que significa **genera**

<br>
<a name="Sumario_serie_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Sumario serie de Fourier</h3>

* Serie de Fourier generada por $f(x)$
$$
f(x) \approx \approx \frac{a_0}{2} + \sum_{n=1}^{\infty}  \left(
a_n \left( \frac{n\pi x}{p} \right)    + 
b_n \left( \frac{n\pi x}{p} \right) 
\right) 
$$

* Coeficientes
$$
a_m = \frac{1}{p} \int_{-p}^{p} f(x) \cos \left( \frac{m\pi x}{p} \right)  dx \\[4ex]
b_m = \frac{1}{p} \int_{-p}^{p} f(x) \sin \left( \frac{m\pi x}{p} \right) dx\\[4ex]
c_0 = \frac{1}{2p} \int_{-p}^p f(x) dx 
$$


<br>
<a name="Propiedad_de_integración_con_funciones_pares_e_impares"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Propiedad de integración con funciones pares e impares</h3>


Sea $f(x)$ una funcion par y sea $g(x)$ una función impar, se tiene que
$$
\int_{-a}^a{f(x)dx} = 2 \int_{0}^p {f(x)dx} \hspace{6ex} (1) \\[3ex]
\int_{-a}^a{g(x)dx} = 0 \hspace{6ex}  (2)
$$

<br>
<a name="Demostracion"></a>
<h6 style="font-size:14px;color:green">Demostración (1)</h6>

$$
\int_{-p}^{p} {f(x) dx } = \int_{-p}^{0} {f(x) dx } + \int_{0}^{p} {f(x) dx }  \\[2ex]

\text{Planteamos la sustitución:} \\[2ex]

u=-x \\
du = -dx \\[2ex]

\text{Remplazamos en el primer término} \\[2ex]

 \int_{-p}^{0} {f(x) dx } + \int_{0}^{p} {f(x) dx } \\[2ex]
 \int_{p}^{0} {f(-u) (-du) } + \int_{0}^{p} {f(x) dx } \\[2ex]
 
 \text{Multiplicamos por 0 el primer integrando, con la finalidad de invertir los extremos de integracion} \\[2ex]
 
 - \int_{0}^{p} {f(-u) (-du) } + \int_{0}^{p} {f(x) dx } \\[2ex]
 \int_{0}^{p} {f(-u) du } + \int_{0}^{p} {f(x) dx } \\[2ex] 
 
\text{Ya que } f \text{ es par, se tiene que } f(-u) = f(u) \\[2ex]

 \int_{0}^{p} {f(u) du } + \int_{0}^{p} {f(x) dx } \\[2ex] 
 
 \text{Cambiamos las variables del primer termino} \\[2ex]
 
 \int_{0}^{p} {f(x) dx } + \int_{0}^{p} {f(x) dx } \\[4ex]
\bold{ 2 \int_{0}^{p} {f(x) dx }  }
$$

<br>

El desarrollo para la demostración (2) es análogo

<br>
<a name="Series_de_fourier_con_funciones_pares_e_impares"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Series de fourier con funciones pares e impares</h3>


Sabemos que la serie de fourier se construye como

$$
f(x) = c_0 + \sum_{n=1}^{\infty}  \left(
a_n \left( \frac{n\pi x}{p} \right)    + 
b_n \left( \frac{n\pi x}{p} \right) 
\right) 
$$


Donde
$$
\bold{ a_n = \frac{1}{p} \int_{-p}^{p} f(x) \cos \left( \frac{n\pi x}{p} \right)  dx } \\[4ex]
\bold{ b_n = \frac{1}{p} \int_{-p}^{p} f(x) \sin \left( \frac{n\pi x}{p} \right) dx } \\[4ex]
\bold{ c_0 = \frac{1}{2p} \int_{-p}^p f(x) dx }\\[4ex]
$$

<br>

También recordemos que
$$
\text{par} \times \text{ par = par} \\[2ex]
\text{par} \times \text{ impar = impar} \\[2ex]
\text{impar} \times \text{ par = impar} \\[2ex]
\text{impar} \times \text{ impar = par} \\[2ex]
$$

<br>

Vemos que la funcion $\cos \left( \frac{n\pi x}{p} \right)$ es par, y la función $\sin \left( \frac{n\pi x}{p} \right)$ es impar, por lo que:

* Si f(x) es par
	* $f(x) \cos \left( \frac{n\pi x}{p} \right)$ es  **par**, ya que par x par = par
	* $f(x) \sin \left( \frac{n\pi x}{p} \right)$ es  **impar**, ya que par x impar = impar
* Si f(x) es impar
	* $f(x) \cos \left( \frac{n\pi x}{p} \right)$ es **impar**, ya que impar x par = impar
	* $f(x) \sin \left( \frac{n\pi x}{p} \right)$ es  **par**, ya que impar x impar = par

<br>
En base a esto, podemos afirmar que para una función f en un intevalo simetrico [-p,p] se cumple que:

* Si f(x) es impar
	* **a<sub>n</sub> = 0**, ya que tenemos la integral entre -P y P de $f(x) \cos \left( \frac{n\pi x}{p} \right)$, una función impar
	* **c<sub>n</sub> = 0**,  ya que tenemos la integral entre -p y p de $f(x)$, una función impar
* Si f(x) es par
	* **b<sub>n</sub> = 0**, ya que tenemos la integral entre -P y P de $f(x) \sin \left( \frac{n\pi x}{p} \right)$, una función impar

Por lo tanto, podemos simplificar el planteo para las series de Fourier de funciones pares e impares:

* Seire de fourier para funciones impares:
$$
f(x) = \sum_{n=1}^{\infty} { b_n \sin \left( \frac{n\pi x}{p} \right)} \\[2ex]
\text{A esta serie se la llama } \textbf{serie de senos de Fourier de } \bold{f}
$$

* Serie de fourier para funciones pares: 
$$
f(x) = \frac{a_0}{2} + \sum_{n=1}^{\infty} { a_n \cos \left( \frac{n\pi x}{p} \right)} \\[2ex]
\text{A esta serie se la llama } \textbf{serie de cosenos de Fourier de } \bold{f}
$$


<br>
<a name="Desarrollo_de_serie_exponencial_y_compleja_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Desarrollo de serie exponencial y compleja de Fourier</h3>

Usando las identidades de euler, podemos representar la serie de fourier usando la funcion exponencial

Sabemnos que
$$
\cos(\alpha) = \frac{e^{\alpha j} + e^{-\alpha j}}{2} \\[2ex]
\sin(\alpha) = \frac{e^{\alpha j} - e^{-\alpha j}}{2j} \\[2ex]
$$
Luego, podemos reescribir la serie de fourier como:
$$
\omega = \frac{\pi}{P} = \frac {2\pi}{T} \\[2ex]

\\[4ex]

f(x) = c_0 + \sum_{n=1}^{\infty} {a_n \cos(n \omega x) + b_n \sin(n \omega x)} \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} {
a_n     \frac{e^{n \omega x j} + e^{- n \omega x j}}{2}     
+ b_n      \frac{e^{n \omega x} - e^{- n \omega x}}{2j}    } \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{a_n   \left(   e^{n \omega x j} + e^{- n \omega x j}  \right)
+ b_n   \left(   \frac{e^{n \omega x} - e^{- n \omega x}}{j}   \right)  }    \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{a_n   \left(   e^{n \omega x j} + e^{- n \omega x j}  \right)
+ b_n   \left(   e^{n \omega x} - e^{- n \omega x}  \right) (-j)  }    \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{a_n   \left(   e^{n \omega x j} + e^{- n \omega x j}  \right)
+ b_n   \left(   -e^{n \omega x}j + e^{- n \omega x} j  \right)  }    \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{   a_n e^{n \omega x j} + a_n e^{- n \omega x j}  
-  b_n  e^{n \omega x}j +   b_n  e^{- n \omega x} j    }    \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{   a_n e^{n \omega x j} + a_n e^{- n \omega x j}  
-  b_n  e^{n \omega x}j +   b_n  e^{- n \omega x} j    }    \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left(
{   e^{n \omega x j} (a_n - b_n j) + e^{-n \omega xj } ( a_n + b_n j)  }  \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{   e^{n \omega x j } (a_n - b_n j) + e^{-n \omega x j} ( a_n + b_n j)  }  \right) \\[6ex]




\text{Desarrollamos la expresion } a_n \pm b_n j \\[2ex]


(a_n \pm b_n j)  = \left( \frac{1}{p} \int_{-p}^{p} f(x) \cos \left( \frac{n\pi x}{p} \right)  dx  \pm \frac{1}{p} j \int_{-p}^{p} f(x) \sin \left( \frac{n\pi x}{p} \right) dx \right) \\[2ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x) \cos \left( \frac{n\pi x}{p} \right)  dx  \pm  j \int_{-p}^{p} f(x) \sin \left( \frac{n\pi x}{p} \right) dx \right) \\[2ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x) \cos (n \omega x) dx  \pm j \int_{-p}^{p} f(x) \sin(n \omega x) dx \right)  \\[2ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x) \cos (n \omega x) \pm j f(x) \sin(n \omega x) dx \right)  \\[2ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x) \cos (n \omega x) \pm j f(x) \sin(n \omega x) dx \right)  \\[2ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (\cos (n \omega x) \pm j \sin(n \omega x)) dx  \right)  \\[4ex]

\text{Ya que} \\[2ex]
e^{\pm \alpha j} = \cos(\alpha) \pm j \sin(\alpha) \\[4ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (\cos (n \omega x) \pm j \sin(n \omega x)) dx  \right)  \\[2ex]

(a_n \pm b_n j)  = \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (e^{\pm n \omega x j}) dx  \right)  \\[6ex]

%(a_n \pm b_n j)  =  \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (e^{ \pm \frac{n \pi}{P} x}) dx  \right)  \\[4ex]

\text{Planteamos la sucecion } C_n \\[2ex]

%C_n  = \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (e^{ \frac{n \pi}{P} x}) dx  \right) \\[2ex]

C_n  = \frac{1}{2p}   \left( \int_{-p}^{p} f(x)  (e^{ -n \omega x j}) dx  \right) = \frac{a_n}{2} - \frac{j b_n}{2} \\[4ex]

\left( \text{Recordemos que  }  \omega = \frac{\pi}{p} = \frac{2\pi}{T} \right) \\[6ex]


\text{Remplzamos en la sumatoria}\\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{   e^{n \omega x j} (a_n - b_n j) + e^{-n \omega x j} ( a_n + b_n j)  }  \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty} \frac{1}{2}  \left( 
{   e^{n \omega x j} \left( \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (e^{ -n \omega x j}) dx  \right) \right) 
+ e^{-n \omega x j} \left(   \frac{1}{p}   \left( \int_{-p}^{p} f(x)  (e^{  n \omega x j}) dx  \right)   \right)  }  \right) \\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty}  \left( 
{   e^{n \omega x j} \left( \frac{1}{2p}   \left( \int_{-p}^{p} f(x)  (e^{ -n \omega x j}) dx  \right) \right) 
+ e^{-n \omega x j} \left(   \frac{1}{2p}   \left( \int_{-p}^{p} f(x)  (e^{  n \omega x j}) dx  \right)   \right)  }  \right) \\[2ex]

\bold{
f(x) = c_0 + \sum_{n=1}^{\infty}   \left( 
{e^{n \omega x j} C_{n} + 
e^{-n \omega x j} C_{-n}   }  \right) } \\[2ex]
\text{La expresion anterior es llamada forma exponencial de fourier. Aun asi podemos seguir desarrollando: } \\[6ex]

\text{Desarrollamos } c_0\\[2ex]
c_0 = \frac{1}{2p} \int_{-p}^p f(x) dx =  \frac{1}{2p} \int_{-p}^{p} f(x)  (e^{n \omega 0}) dx  = C_0 \\[6ex]

\text{Remplazamos }\\[2ex]

f(x) = c_0 + \sum_{n=1}^{\infty}   \left( 
{e^{n \omega x j } C_{n} + 
e^{-n \omega x j} C_{-n}}  \right) \\[2ex]

f(x) = C_0 + \sum_{n=1}^{\infty} \left( 
{e^{n \omega x j } C_{n} + 
e^{-n \omega x j} C_{-n}}  \right) \\[2ex]

f(x) = C_0 + 
\sum_{n=1}^{\infty} \left( {e^{n \omega x j } C_{n} } \right)  + 
\sum_{n=1}^{\infty}  \left( {e^{-n \omega x j} C_{-n}}  \right) \\[2ex]

f(x) = 
\sum_{n=0}^{\infty} \left( {e^{n \omega x j } C_{n} } \right)  + 
\sum_{n=1}^{\infty}  \left( {e^{-n \omega x j} C_{-n}}  \right) \\[2ex]

f(x) = 
\sum_{n=0}^{\infty} \left( {e^{n \omega x j } C_{n} } \right)  + 
\sum_{n= -\infty}^{0}  \left( {e^{n \omega x j} C_{n}}  \right) \\[2ex]

\bold{
f(x) = \sum_{-\infty}^{\infty} {e^{n \omega x j} C_n} 
} \\[2ex]

\text{A esta última forma de la serie de fourier se la conoce como forma compleja de Fourier} \\[6ex]
$$

<br>
<a name="Sumario_serie_exponencial_y_compleja_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Sumario serie exponencial y compleja de Fourier</h3>

* Otra forma de expresar la serie de Fourier, a partir de coeficientes complejos.

$$
\text{Sea } \omega = \frac{\pi}{P} = \frac{2 \pi}{T}  \\[2ex]
\text{Sea } C_n  = \frac{1}{2p}   \left( \int_{-p}^{p} f(x)  (e^{- n \omega x}) dx  \right)  =  \frac{a_n}{2} - j\frac{b_n}{2}
$$

* Forma exponencial de Fourier: 
$$
\bold{
f(x) = c_0 + \sum_{n=1}^{\infty}   \left( 
{e^{ n \omega x j} C_{n} + 
e^{- n \omega x j} C_{-n}   }  \right) } 
$$

* Forma compleja de Fourier:
$$
\bold{
f(x) = \sum_{-\infty}^{\infty} {e^{ n \omega x j} C_n} 
} 
$$


<br>

<br>

<a name="Transformada_y_transformada_inversa_de_Fourier"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Transformada y transformada inversa de Fourier</h3>

Sabemos que podemos representar cualquier funcion acotada de forma periodica mediante una suma de senos y cosenos. Sin embargo, haciendo algunas modificaciones a la serie de fourier podemos conseguir representar cualquier funcion de forma no periodica.

<a name="Extension_del_periodo"></a>
<h4 style="font-size:16px;color:#FF7F00">Extension del periodo</h4>

Dada una funcion acotada f, definida entre [-p,p] sabemos que su serie será:

![42d1fe44b17127d2363c388ad6fbe172.png](:/bd5f23294153428b813c1e88727e4330)
Vemos que la funcion se tiene como periodo 2p, pero podemos aumenar su periodo en Δt agregando la funcion h(t) = 0 
![2cd53c35da815651bdd43bfb14cb43d6.png](:/186c2387e8ae4e838ee81efd8b3b7c2c)

Ahora, la serie de fourier de f para [-p-Δt, p+Δt] será

![aba3b9efc7c45dc2faebe7dfc807bac2.png](:/fffef2a35b524172beac9a9693c96238)

Podemos hacer que Δt →∞, entonces, f y su serie de fourier seran

![fca1e4381600d94b97669975dc040a1b.png](:/6f10a4029a3a42e388bbe4b108887104)


<a name="Serie_de_Fourier_de_frecuencias_continuas"></a>
<h4 style="font-size:16px;color:#FF7F00">Serie de Fourier de frecuencias continuas</h4>

La serie de fourier de una funcion f(t), definida en un periodo T ( Dom(f) =[-T/2, T/2] ), representara una aproximacion de dicha serie como una suma discreta de senos y cosenos con frecuencias especificas.

Si analizamos la forma trigonometrica de la serie de Fourier

$$
f(t) = \frac{a_0}{2} + \sum_{n=1}^{\infty} {a_n \cos \left( \frac{n 2\pi }{T} t \right) +b_n \sin \left( \frac{n 2\pi }{T} t \right)}
$$

vemos que la frecuencia de cada iteración estara dada por el termino: 

$$
\frac{n 2\pi }{T}
$$

Esto nos indica que las frecuencias de los armonicos de una serie de Fourier estaran determinados por el valor de su periodo.

(Armonico =  ${a_0 \cos \left( \frac{n 2\pi }{T} t \right) +a_0 \sin \left( \frac{n 2\pi }{T} t \right)}$ para un n especifico. Es decir, una iteracion de la sumatoria)

Podemos plantear la sucecion $\omega_n = \frac{n 2\pi }{T}$ que nos indique las frecuencias de los armonicos de una serie con un periodo especifico. Podemos graficar esta sucecion sobre una recta.

A su vez, podemos utilizar esta sucecion para determinar cuantos armonicos tienen una frecuencia menor o igual a K

$$
Ar = \left\lfloor \frac{K · n}{\omega_n} \right\rfloor = \left\lfloor \frac{T K n}{n 2 \pi} \right\rfloor   \\[2ex]
\text{Donde K es un valor real arbitrario. }
$$



Podemos expresar este resultado como que la serie de fourier de f contiene $\left\lfloor \frac{K n}{\omega_n} \right\rfloor$ armonicos en el intervalo de frecuencias [0,k]

<br>

Veamos algunos ejemplos


<a name="Ej_1"></a>
<h6 style="font-size:14px;color:green">Ej 1</h6>

Sea f<sub>1</sub> una funcion cuyo periodo es $2\pi$, las frecuencias de su serie de Fourier seran:

$$
\omega_n = \frac{n 2\pi}{T} = \frac{n 2\pi}{2\pi} = n
$$

![ba30145d719c37346762404d1c4fed73.png](:/f05318445ac044b5b1ec275d572c1e54)

Buscamos la cantidad de armonicos con frecuencias menores o iguales a 10 que posee la serie de Fourier de f<sub>1</sub>

$$
\frac{10 n}{\omega_n} = \frac{10 n}{n} = 10
$$

La serie de Fourier de f<sub>1</sub> tendra 10 armonicos con frecuencia igual o menor a 10. También podemos decir que f<sub>1</sub> contiene 10 armonicos en el intervalo de frecuencias [0,10] 

<!-- -------------------------------------------- -->

<a name="Ej_2"></a>
<h6 style="font-size:14px;color:green">Ej 2</h6>

Sea f<sub>2</sub> una funcion cuyo periodo es $3$, las frecuencias de su serie de Fourier seran:

$$
\omega_n = \frac{n 2\pi}{T} = \frac{n 2\pi }{3}
$$

![4e0168432ef6ddab6ca554b8c8ca9082.png](:/467c7320daf4420e96a2efbf53424940)

Buscamos la cantidad de armonicos con frecuencias menores o iguales a 10 que posee la serie de Fourier de f<sub>2</sub>. 

$$
\frac{10 n}{\omega_n} = \frac{10 n}{\frac{n 2\pi }{3}} = \frac{30 n}{n 2\pi} = \frac{15}{\pi} \approx 4.77 \\[2ex]
\left\lfloor 4.77\right\rfloor  = 4
$$

La serie de Fourier de f<sub>2</sub> tendrá 4 armonicos con frecuencia igual o menor a 10. También podemos decir que f<sub>2</sub> contiene 4 armonicos en el intervalo de frecuencias [0,10] 

<a name="Ej_3"></a>
<h6 style="font-size:14px;color:green">Ej 3</h6>

Sea f<sub>3</sub> una funcion cuyo periodo es $10$, las frecuencias de su serie de Fourier seran:

$$
\omega_n = \frac{n 2\pi }{10}
$$

![4c5ef70cf246ef283781bd15f0f43c5a.png](:/6d7a1b4ba2044affa6aacaae0e197beb)

Buscamos la cantidad de armonicos con frecuencias menores o iguales a 10 que posee la serie de Fourier de f<sub>3</sub>

$$
\frac{10 n}{\omega_n} = \frac{10 n}{\frac{n 2\pi }{10}} = \frac{100 n}{n 2\pi} = \frac{50}{\pi} \approx 15.91549 \\[2ex]
\left\lfloor 15.91549 \right\rfloor  = 15
$$

La serie de Fourier de f<sub>3</sub> tendrá 15 armonicos con frecuencia igual o menor a 10. También podemos decir que f<sub>2</sub> contiene 15 armonicos en el intervalo de frecuencias [0,10] 

<br>

Vemos que la cantidad de armonicos en un intervalo de frecuencias dado es directamente proporcional al periodo ¿Que Ocurrira en el caso donde extendamos el periodo de una funcion a infinito como se explico en [Extension del periodo](#Extension_del_periodo)?

Sea f una funcion cuyo periodo es T, queremos buscar cuantos armonicos tendra su serie en el intervalo de frecuencias [0,k]. Lo hacemos mediante la operacion:

$$
\left\lfloor \frac{K n}{\omega_n} \right\rfloor = \left\lfloor \frac{K n}{\frac{n2\pi}{T}} \right\rfloor = \left\lfloor \frac{T K n}{n2\pi} \right\rfloor
$$

Si hacemos $T \rightarrow \infty$

$$
\lim_{T \rightarrow \infty} \left\lfloor \frac{T K n}{n2\pi} \right\rfloor = \left\lfloor \frac{\infty K n}{n2\pi} \right\rfloor = \left\lfloor \frac{\infty}{n2\pi} \right\rfloor = \left\lfloor \infty \right\rfloor = \infty
$$

Este resultado nos indica que la seire de Fourier de cualquier funcion con periodo infinito tendrá una cantidad infinita de armonicos para cualquier intervalo de frecuencias. Es decir, en un intervalo I acotado se sumaran infinitos armonicos, por lo que pasara de ser una suma discreta a una suma continua. 

Grafico de los armonicos de f:
![2d806396e21dd92ab9ce8a25f1aec4e3.png](:/519ed3ff13474e0586fd576bcc59f709)

Sabiendo esto, podemos representar cualquier funcion con dominio en los reales como serie de Fourier con periodo infinito, por lo que cualquier funcion de este tipo representara una suma continua en lugar de una suma discreta

Convertimos la sumatoria discreta en una sumatoria continua:

$$
f(t) = \sum_{n=-\infty}^{\infty} {C_n e^{\frac{n 2\pi}{T} tj}}
$$
Hacemos que $T \rightarrow \infty$
$$
f(t) = \lim_{T \rightarrow \infty} \sum_{n=-\infty}^{\infty} {C_n e^{\frac{n 2\pi}{T} tj}} \\[2ex]

f(t) = \lim_{T \rightarrow \infty} \sum_{n=-\infty}^{\infty} \left[ \frac{1}{T} \int_{-T/2}^{T/2} f(t) e^{-{\frac{n 2\pi}{T} tj}} dt \right] e^{\frac{n 2\pi}{T} tj} \\[2ex]

$$
Ya que $\omega = \frac{2 \pi}{T}$, Podemos expresar esta igualdad como
$$
f(t) = \lim_{\omega \rightarrow 0} \sum_{n=-\infty}^{\infty} \left[ \frac{1}{\frac{2\pi}{\omega}} \int_{-\pi/\omega}^{\pi/\omega} f(t) e^{-n \omega tj} dt \right] e^{n \omega tj}  \\[2ex]

f(t) = \lim_{\omega \rightarrow 0} \sum_{n=-\infty}^{\infty} \left[ \frac{1}{2 \pi} \int_{-\pi/\omega}^{\pi/\omega} f(t) e^{-n \omega tj} dt \right] e^{n \omega tj} \omega \\[2ex]

f(t) = \lim_{\omega \rightarrow 0} \sum_{n=-\infty}^{\infty} \left[ \frac{1}{2 \pi} \int_{-\infty}^{\infty} f(t) e^{-n \omega tj} dt \right] e^{n \omega tj} \omega \\[2ex]
$$

Planteamos la funcion $g(\omega)$

$$
g(\omega) = \left[ \frac{1}{2 \pi} \int_{-\infty}^{\infty} f(t) e^{-\omega tj} dt \right] e^{\omega tj}
$$

Remplazamos en f(t)
$$
f(t) = \lim_{\omega \rightarrow 0} \sum_{n=-\infty}^{\infty} g(n \omega) \omega \\[2ex]
f(t) = \int_{-\infty}^{\infty} g(\omega) d\omega \\[2ex]
f(t) = \int_{-\infty}^{\infty} \left[ \frac{1}{2 \pi} \int_{-\infty}^{\infty} f(t) e^{-\omega tj} dt \right] e^{\omega tj} d\omega \\[2ex]
f(t) = \frac{1}{2 \pi} \int_{-\infty}^{\infty} \left[  \int_{-\infty}^{\infty} f(t) e^{-\omega tj} dt \right] e^{\omega tj} d\omega \\[2ex]
$$




<br>
<a name="Transformada_de_Fourier"></a>
<h4 style="font-size:16px;color:#FF7F00">Transformada de Fourier</h4>

Sabemos que cualquier función acotada puede representarse de forma periodica como una suma de senos y cosenos:
$$
f(t) --  \sum_{n=-\infty}^{\infty} C_n e^{n \omega_0 t j}
$$

El término C<sub>n</sub>  representa el peso del armonico de frecuencia |C<sub>n</sub> ω<sub>0</sub>|. Donde ω<sub>0</sub> es un valor fijo y representa la frecuencia fundamental de f ($\omega_0 = \frac{2 \pi}{T}$). Por lo que C<sub>n</sub> solo representara el peso de multiplos de la frecuencia fundamental y su dominio seran solo contendrá valores discretos.

Podemos buscar una forma de generalizar a C<sub>n</sub>, para que su dominio sean los reales. Analizamos la expresion de C<sub>n</sub>

$$
C_n = \frac{1}{T} \int_{-T/2}^{T/2} f(t) e^{ n \frac{2\pi}{T}t j} dt
$$
Si desarrollamos C<sub>n</sub> utilizando las formulas de euler, se tiene
$$
C_n =  \frac{1}{T} \int_{-T/2}^{T/2}f(t) \cos \left( n \frac{2\pi}{T}t \right) +  \frac{1}{T} \int_{-T/2}^{T/2}f(t) \sin \left( n \frac{2\pi}{T}t \right)
$$
Vemos que la frecuencia estará determinada por el termino $n \frac{2\pi}{T}$, remplazaremos este termino por ω $\in \mathbb{R}$. Obtendremos asi una funcion equivalente a $C_n$, pero  que puede tomar todos los valores reales en lugar de solo aquellos determinados por su frecuencia fundamental.

Planteamos la funcion:

$$
\eta (\omega) = \frac{1}{T} \int_{-T/2}^{T/2} f(t) e^{- \omega t j} dt
$$

Vemos que la funcion eta generaliza a C<sub>n</sub>, ya que

$$
\eta(n \omega_0) =  \frac{1}{T}  \int_{-T/2}^{T/2} f(t) e^{- n \omega_0 t j} dt \\[2ex]
\eta (n \omega_0) = \text{C}_n \\[2ex]
\text{Cuando } n \in \mathbb{Z} \text{ y } \omega_0 \text{ es la frecuencia fundamental de f}
$$

<a name="Ej"></a>
<h6 style="font-size:14px;color:green">Ej: </h6>

Dada una funcion f, definida como

$$
f(t) ={\left\{\begin{matrix}
-3 & -3 < t < 0\\ 
3 &  0 < t < 3
\end{matrix}\right.}
$$

Entonces:

<!--TODO:: Agregar expresiones parametricas para contraste con parte "Vemos que para periodo 12, la funcion $\Phi$ es igual" -->

$$
C_n =  \frac{1}{6} \int_{-3}^{3} f(t) e^{\frac{n 2\pi t j}{T}}dt \\[2ex]
C_n = \frac{-3}{n \pi} (1- cos(n \pi))j \\[6ex]

\eta(\omega) = \frac{1}{6} \int_{-3}^{3} f(t) e^{- \omega t j} dt \\[2ex]
\eta (\omega) = \frac{\cos(3 \omega) - 1}{ \omega} j - \frac{sin(3 \omega)}{\omega }
$$

Se verifica que

$$
\eta (n \omega_0) = \eta \left( n \frac{\pi}{3} \right) = 3 \frac{\cos(n \pi) - 1}{ n \pi} j - 0 =  \frac{-3}{n \pi} (1- cos(n \pi))j = C_n
$$

Comparamos las graficas de sus valores absolutos:

![c25cd8549956b34004a4bc67c44a5e3f.png](:/dc32008e8b6243f38a1719e7317702d7)

En la grafica vemos que C<sub>n</sub> siempre coincide con $\eta$, lo que nos indica que $\eta$ es una generalización valida.

La grafica anterior representa por que valor se escalaría cada frecuencia de la serie de f(t) cuando esta tiene su periodo determinado entre [-3,3], pero podríamos alargar su periodo como se indico en el apartado [Extension del periodo](#Extension_del_periodo), 

Calculemos cuando valdría $\eta$ de una funcin f definida en [-p,p] para un periodo arbitrario T


$$
\eta (\omega) = \frac{1}{T} \int_{-T/2}^{T/2} f(t) e^{- \omega t j} dt \\[2ex]
\eta (\omega) = \frac{1}{T} \left[
 \int_{-T/2}^{-p} 0 e^{- \omega t j} dt  +
\int_{-p}^{p} f(t) e^{- \omega t j} dt  +
 \int_{p}^{-T/2} 0 e^{- \omega t j} dt 
\right] \\[2ex]
\eta (\omega) = \frac{1}{T} \int_{-p}^{p} f(t) e^{- \omega t j} dt \\[2ex]
$$

Vemos que a diferentes periodos, les corresponden la misma funcion determinada por la integral, pero escalada por el inverso del periodo elegido. 

Se deduce entonces que la integral $\int_{-p}^{p} f(t) e^{- \omega t j} dt$ representa una función que describe el peso no escalado que debería tener el armonico con la frecuencia $\omega$ de la serie de Fourier de f(t). Pero ya que este tipo de serie es una sumatoria discreta, esta integral describira el peso de infinitas frecuencias no utilizadas por ningun armonico.

Esto cambia si hacemos que el periodo de la funcion sea $\infty$, como se demostro en el apartado anterior, la serie de Fourier de una funcion con periodo infinito será una suma continua de armonicos con todas las frecuencias posibles, por lo que en este caso $\int_{-p}^{p} f(t) e^{- \omega t j} dt$ describiria el peso no escalado de todos los armonicos que componen la serie de una funcion. Su grafica nos servira para determinar que frecuencias son mas importantes.


Utilizando esta integral para una funcion con periodo infinito, se define la transformada de Fourier:

$$
F[f(t)] = \int_{-\infty}^{\infty} f(t) e^{- \omega t j} dt

$$

F: $f(t) \rightarrow f(\omega)$



<br>
<a name="Transformada_de_Fourier"></a>
<h4 style="font-size:16px;color:#FF7F00">Transformada inversa de Fourier</h4>

Si analizamos la serie de fourier para funciones de periodo infinito:

$$
f(t) = \frac{1}{2 \pi} \int_{-\infty}^{\infty} \left[  \int_{-\infty}^{\infty} f(t) e^{-\omega tj} dt \right] e^{\omega tj} d\omega
$$

Vemos que el termino entre corchetes es la transformada de Fourier de f, por lo que podemos expresar esta igualdad como

$$
f(t) = \frac{1}{2 \pi} \int_{-\infty}^{\infty} F(\omega) e^{\omega tj} d\omega
$$

La parte derecha de la igualdad es una transformacion que recibe la transformada de Fourier de cualquier funcion y devuelve la funcion original:

$$T: f(\omega) \rightarrow f(t)$$

Vemos que esta operacion es inversa a la transformada de fourier, luego esta transformacion se llamara **transformada inversa de fourier**


<br>
<a name="Sumario_de_formulas_de_transformada_de_Fourier"></a>
<h4 style="font-size:16px;color:#FF7F00">Sumario de formulas de transformada de Fourier</h4>

* Transformada de Fourier 
	* $f(t) \rightarrow f(\omega)$
	* Genrealizacion de C<sub>n</sub> para los reales de una funcion de periodo $\infty$
$$
F(\omega) = \int_{-\infty}^{\infty} {f(t) e^{-\omega t j}} dt
$$

* Transformada inversa de Fourier
	* $f(\omega) \rightarrow f(t)$
	* Surge de la serie de Fourier de una funcion de periodo $\infty$
$$
f(t) = \frac{1}{2\pi} \int_{-\infty} ^{\infty} F(\omega) e^{\omega t j} d\omega
$$


<br>
<a name="C<sub>0</sub>_=?_a<sub>0</sub>/2"></a>
<h3 style="font-size:16;font-style:italic;color:blue">C<sub>0</sub> =? a<sub>0</sub>/2</h3>


En principio, C<sub>0</sub> debería devolver el valor del término independiente de la correspondiente serie de Fourier, ya que:

$$
C_0 = \frac{a_0}{2} + j \frac{b_0}{2} \\[2ex]
C_0 = \frac{1}{2p} \int_{-p}^{p} {f(t) \cos \left( \frac{0 \pi t}{p}\right)} dt + j \frac{1}{2p} \int_{-p}^{p} {f(t) \sin \left( \frac{0 \pi t}{p}\right)} dt \\[2ex]
C_0 = \frac{1}{2p} \int_{-p}^{p} {f(t) \cos (0)} dt + j \frac{1}{2p} \int_{-p}^{p} {f(t) \sin (0)} dt \\[2ex] 
C_0 = \frac{1}{2p} \int_{-p}^{p} {f(t) 1} dt + j \frac{1}{2p} \int_{-p}^{p} {f(t) 0} dt \\[2ex] 
C_0 = \frac{1}{2p} \int_{-p}^{p} {f(t)} dt +  0 j \\[2ex] 
\bold{
C_0 = \frac{1}{2p} \int_{-p}^{p} {f(t)} dt 
}
$$

Pero en la mayoría de los casos, aparecerá n como factor en el denominador, por lo que no podemos evaluar directamente n=0 para C<sub>n</sub>. En su lugar podemos aproximarnos a este valor tomando el límite de n  $\rightarrow$ 0 (considerando n $\in \mathbb{R})$:

<a name="Ej_1"></a>
<h6 style="font-size:14px;color:green">Ej 1:</h6> 

Buscamos la serie de 

$$
f(t)= {
\left\{\begin{matrix}
2 & -2 < x < 0 \\ 
0 & 0 < x < 2
\end{matrix}\right.
}
$$

Se obtiene:

$$
C_n = \frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) + \sin(n \pi) \right) \frac{j}{n \pi} \left( \cos \left( n \frac{\pi}{2}\right) - \cos(n \pi) \right) \\[2ex]

C_n = \frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) \right) + \frac{j}{n \pi}{\left(  \cos \left( n \frac{\pi}{2} \right) - \cos(n \pi)   \right)}
$$

Por lo que su serie es 

$$
\sum_{n=-\infty}^{\infty}  \left[ \frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) \right) + \frac{j}{n \pi}{\left(  \cos \left( n \frac{\pi}{2} \right) - cos(n \pi)   \right)} \right] e^{\frac{n \pi j t}{2}}
$$

Analizamos el valor del C<sub>0</sub>, ya que n esta en el denominador, evaluaremos usando límites

$$
\lim_{n \rightarrow 0}  \frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) \right) + \frac{j}{n \pi}{\left(  \cos \left( n \frac{\pi}{2} \right) - cos(n \pi)   \right)}
$$

$$
\lim_{n \rightarrow 0}  \frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) \right) + \frac{j}{n \pi}{\left(  \cos \left( n \frac{\pi}{2} \right) - cos(n \pi)   \right)} = \frac{1}{2} \\[2ex]
$$

Luego
$$
C_0 = \frac{1}{2}
$$

Ya que $C_0 = \frac{a_0}{2}$, el termino independiente de la serie debería ser $\frac{1}{2}$

Verificamos evaluando $\frac{a_0}{2}$ por definicion

$$
\frac{a_0}{2} = \frac{1}{4} \int_{-2}^{2} f(t) dt = \frac{3}{2}
$$ 

Al evaluar por definicion, obtenemos que el termino independiente de la serie debe ser $\frac{3}{2}$, es decir $C_0 \neq \frac{a_0}{2}$

¿Porque aparece esta diferencia? Anteriormente demostramos que ambos terminos deberían ser iguales, pero la igualdad no se cumple en este caso.

Esto se debe a que se simplificó $Re(C_n)$. Al desarrollar la integral se obtiene que $Re(C_n) =\frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) + \sin(n \pi) \right)$. Por ser n un valor entero, se simplifica el termino $\sin(n \pi)$, ya que para valores enteros este siempre valdra 0. Por otro lado al evaluar el límite n $\rightarrow$ 0, se considera a n como un real, por lo que no sería correcto cambiar a $\sin(n \pi)$ por 0 al evaluar el límite.

Volvemos a evaluar el límite dejando el termino $\sin(n \pi)$

$$
\lim_{n \rightarrow 0} \frac{1}{n \pi} \left( \sin \left( n \frac{\pi}{2} \right) + \sin(n \pi) \right) = \frac{1}{2} + 1 = \frac{3}{2}
$$

Vemos que al evaluar el límite de la expresion completa, obtenemos el valor correcto.

<br>

<a name="Ej_2"></a>
<h6 style="font-size:14px;color:green">Ej 2:</h6>

Buscamos la serie de 

$$
f(t)= t \\[2ex]
0 < t < 4
$$

Se obtiene:

$$
C_n = \frac{1}{4} \left[  
\frac{8 e^{-2 n \pi t}}{n \pi} j 
- \frac{4- 4 e^{-2 \pi n j}}{ (n \pi)^2}
\right] \\[2ex]

C_n = \frac{1}{4} \left[  
\frac{8 (1)}{n \pi } j 
- \frac{4- 4 (1)}{ (n \pi)^2}
\right] \\[2ex]

C_n = \frac{1}{4} \left[  
\frac{8 (1)}{n \pi } j 
- \frac{4- 4 (1)}{ (n \pi)^2}
\right] \\[2ex]

C_n = \frac{1}{4} \left[  
\frac{8 (1)}{n \pi } j 
- 0
\right] \\[2ex]

C_n = \frac{1}{4} \left[  
\frac{8 (1)}{n \pi } j 
- 0
\right] \\[2ex]

C_n = \frac{2j}{n \pi}
$$

Por lo que su serie es 

$$
\sum_{n=-\infty}^{\infty} \frac{2j}{n \pi} e^{\frac{n \pi}{2} jt}
$$

En este caso, se tiene que:

$$
a_n = 0 \\[2ex]
b_0 = \frac{-4}{n \pi}
$$

Por lo que se esperaría que el valor de $\frac{a_0}{2}$ sea 0

Analizamos el valor del C<sub>0</sub>, ya que n esta en el denominador, evaluaremos usando límites.

$$
\lim_{n \rightarrow 0} C_n \\[2ex]
\lim_{n \rightarrow 0} \frac{-2}{n \pi} j \\[2ex]
\text{El límite no existe, ya que} \\[2ex]
\lim_{n \rightarrow 0^-} = -\infty j\\[2ex]
\lim_{n \rightarrow 0^+} = \infty j
$$

En este caso, vemos que la parte imaginaria no solo no se anula, sino que diverge.

Recordemos que $C_0 = \frac{a_0}{2} + j \frac{b_0}{2}$
ya que $b_0 = 0$
 $C_0 = \frac{a_0}{2}$

Sabemos que $C_0$ = $\frac{a_0}{2}$, ya que $\frac{b_0}{2} = 0$, pero al considerar n como real y evaluar $C_{n \rightarrow 0}$, en lugar de $b_{0}$ estaremos evualuando $b_{n \rightarrow 0}$ y puede darse el caso donde $b_{n \rightarrow 0}$ no sea cero o diverga.

Entonces, para evaluar $C_n$ con limites, debemos evaluar unicamente su parte real.

<br>

De estos ejemplos, podemos concluir que:

* Para hallar el termino independiente a partir de $C_n$, solo debe evaluarse su parte real
* El limite de Re($C_0$) solo representara al termino independiente de forma correcta cuando cuando no se hayan realizado simplificaciones en base a que n es un numero entero en la parte real
* Usar el término Re($C_0$) generalmente no es una buena forma de encontrar el termino independiente
* Podemos resumir estas propiedades como:
$$
\frac{a_0}{2} = \lim_{n \rightarrow 0} Re(\eta (\omega))
$$
Donde $\eta(\omega)$ es la funcion que generaliza a los reales la función $C_n$. Ya que en el caso de $\eta$, no se realizan simplificaciones por la existencia de valores enteros.
* La forma mas sencilla de hallar el término independiente, es por definición: $\frac{a_0}{2} = \frac{1}{2p}\int_{-p}^{p} f(t) dt$




<br>
<a name="Variacion_de_funcion"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Variacion de funcion</h3>

La variacion total de una funcion nos indicara la suma de todos los cambios ocurridos sobre el codominio de una funcion en un intervalo acotado.

* Sea $f$ una funcion definida en un intervalo $I$
* Sea $[a,b]$ un intervalo contenido en $I$
* Sea $\tau = [\tau_1, \tau_2, \cdots \tau_n]$ una particion de $[a,b]$, tal que 
	* $a = \tau_1 < \tau_2 < \cdots \tau_n = b \hspace{3ex}$:  Los extremos de la particion deben coincidir con los extremos del intervalo $[a,b]$
	* $(\tau_c - \tau_{c-1}) = k \hspace{3ex}$: cada elemento de la particion $\tau$ está espaciado uniformemente
* Sea $n = \#\tau$ 


La variacion de $f$ sobre el intervalo $[a,b]$ con la particion $\tau$ se define como:

$$
\sum_{n=1}^{n}  |f(\tau_{n+1}) - f(\tau_n)|
$$

La variacion total de $f$ sobre el intervalo $[a,b]$ se define como

$$
Var_{a}^{b} (f) = \lim_{n \rightarrow \infty} \sum_{n=1}^{n}  |f(\tau_{n+1}) - f(\tau_n)|
$$

<br>
<a name="Condiciones_de_Dirichlet"></a>
<h3 style="font-size:16;font-style:italic;color:blue">Condiciones de Dirichlet</h3>

Las condiciones de Dirichlet son condiciones suficientes para que una función periódica f  sea igual a la suma de su serie de Fourier en cada punto donde f es continua. Es decir, estas condiciones nos garantizan la convergencia de la serie de fourier de la funcion f


Sea $f(x)$ una funcion periodica de periodo [-p,p], su serie sera convergente si


* **$f(x)$ es absolutamente integrable**: esta condicion verifica la existencia del termino n-ésimo de la sumatoria.
$$
\int_{-p}^{p} f(x)^2 dx < \infty
$$
* **$f(x)$ es de variacion acotada**: esta condicion limita la cantidad de oscilaciones que una funcion puede presentar en un intervalo de tiempo. Funciones con infinitas oscilaciones en periodos de tiempo finitos no tendran series fourier convergentes

$$
Var_{-p}^{p} (f) = \lim_{n \rightarrow \infty} \sum_{n=1}^{n}  |f(\tau_{n+1}) - f(\tau_n)| < \infty \\

\text{esto tambien puede interpretarse como que $f(x)$ tiene una cantidad finita de maximos y minimos locales estricos:}
$$

* **$f(x)$ presenta un numero finito de discontinuidades para el periodo [-p,p], además, y ninguna de estas discontinuidades es de salto infinito.**

<br>
<br>

Un ejemplo de funcion que rompen la primera condicion es:

$$
f(x) = \frac{1}{x} \hspace{4ex} 0<x<1
$$


Un ejemplo que cumple la primera condicion pero no la segunda condicion es:

1. La funcion impulso
2. 
$$
f(x) = \sin \left( \frac{2 \pi}{x} \right)
$$

<br>
<br>

señales que no satisfacen las condiciones de Dirichlet son generalmente de naturaleza patológica y, en consecuencia, no suelen surgir en contextos prácticos. Por esta razón, la cuestión no se realiza un desarrollo exausitvo de este tema en la mayoria de catedras.

<br>

Fuentes

[Signals & Systems, Oppenheim, Willsky](http://materias.df.uba.ar/l5a2021c1/files/2021/05/Alan-V.-Oppenheim-Alan-S.-Willsky-with-S.-Hamid-Signals-and-Systems-Prentice-Hall-1996.pdf)
(pagina 228)

[Dirichlet conditions and the fundamental period](https://math.stackexchange.com/questions/3657243/dirichlet-conditions-and-the-fundamental-period)

[Funciones de variacion acotada](http://esfm.egormaximenko.com/analysis/bounded_variation_functions_es.pdf)
