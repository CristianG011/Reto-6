# Reto-6
# Punto 1 
1. Dado la figura de la imagen, desarrolle:

<div align='center'>
<figure> <img src="https://i.postimg.cc/FRvCmpxx/image.png" alt="" width="400" height="auto"/></br>
<figcaption><b></b></figcaption></figure>
</div>

+ Una función matemática para calcular el volumen y el área superficial.
+ Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado `r1`, `r2` y `h`.
+ Revise como utilizar el valor de `pi` usando *import math* y *math.pi*
+ 
![](https://i.ibb.co/N6x7BZY/Punto-1-pi.jpg)
# Punto 2
2. Dado la figura de la imagen, desarrolle:

<div align='center'>
<figure> <img src="https://i.postimg.cc/1t4MrzsL/image.png" alt="" width="400" height="auto"/></br>
<figcaption><b></b></figcaption></figure>
</div>

+ Una función matemática para calcular el área y el perimetro.
+ Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado `r`, `a` y `b`.
+ Revise como utilizar el valor de `pi` usando *import math* y *math.pi*
+ 
![](https://i.ibb.co/kJmf4sX/Punto-2-pi.jpg)
# Punto 3
3. Diseñe una función que calcule la cantidad de carne de aves en kilos si se tienen N gallinas, M gallos y K pollitos cada uno pesando 6 kilos, 7 kilos y 1 kilo respectivamente.
   
![](https://i.ibb.co/gZh9xrc/punto-3.jpg)
# Punto 4
4. Mi mamá me manda a comprar P panes a 300 cada uno, M bolsas de leche a  3300 cada una y H huevos a  350 cada uno. Hacer un programa que me diga las vueltas (o lo que quedo debiendo) cuando me da un billete de B pesos.
![](https://i.ibb.co/Pg31bt3/Punto-4.jpg)
# Punto 5
5. Haga un programa que utilice una función para calcular el valor de un préstamo `C` usando interés compuesto del `i` por `n` meses.
![](https://i.ibb.co/jfh0WHK/Punto-5.jpg)
# Punto 6
6. El número de contagiados de Covid-19 en el país de NuncaLandia se duplica cada día. Hacer un programa que diga el número total de personas que se han contagiado cuando pasen D días a partir de hoy, si el número de contagiados actuales es C.

![](https://i.ibb.co/4jHMVSY/Punto-6.jpg)

# Punto 7
7. Escriba un programa que pida 5 números reales y calcule las siguientes operaciones usando una función para cada una:
  + El promedio
  + La mediana 
  + El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
  + Ordenar los números de forma ascendente
  + Ordenar los números de forma descendente
  + La potencia del mayor número elevado al menor número
  + La raíz cúbica del menor número
```
def p(a:float, b:float, c:float, d:float, e:float):
    p1: (a + b + c + d + e) / 5
    print(p1)

def me(a:float, b:float, c:float, d:float, e:float):
    if c > d > a > b > e or c > d > a > e > b or c > e > a > d > b or c > e > a > b > d or c > b > a > d > e or c > b > a > e > d or d > c > a > b > e or d > c > a > e > b or d > e > a > c > b or d > e > a > b > c or d > b > a > c > e or d > b > a > e > c or e > c > a > b > d or e > c > a > d > b or e > d > a > c > b or e > d > a > b > c or c > d > a > b > e or c > d > a > e > b or c > e > a > d > b or c > e > a > b > d or c > b > a > d > e or c > b > a > e > d or d > c > a > b > e or d > c > a > e > b:
        print("la mediana es " + str(a) + ".")
    elif a > c > b > d > e or a > c > b > e > d or a > d > b > c > e or a > d > b > e > c or a > e > b > c > d or a > e > b > d > c or c > a > b > d > e or c > a > b > e > d or c > d > b > a > e or c > d > b > e > a or c > e > b > a > d or c > e > b > d > a or d > a > b > c > e or d > a > b > e > c or d > c > b > a > e or d > c > b > e > a or d > e > b > a > c or d > e > b > c > a or e > a > b > c > d or e > a > b > d > c or e > c > b > a > d or e > c > b > d > a or e > d > b > a > c or e > d > b > c > a:
        print("La mediana es "  + str(b) + "." )
    elif a > b > c > d > e or a > b > c > e > d or a > d > c > b > e or a > d > c > e > b or a > e > c > b > d or a > e > c > d > b or b > a > c > d > e or b > a > c > e > d or b > d > c > a > e or b > d > c > e > a or b > e > c > a > d or b > e > c > d > a or d > a > c > b > e or d > a > c > e > b or d > b > c > a > e or d > b > c > e > a or d > e > c > a > b or d > e > c > b > a or e > a > c > b > d or e > a > c > d > b or e > b > c > a > d or e > b > c > d > a or e > d > c > a > b or e > d > c > b > a:
        print("La mediana es "  + str(c) + ".")
    elif a > b > d > c > e or a > b > d > e > c or a > c > d > b > e or a > c > d > e > b or a > e > d > b > c or a > e > d > c > b or b > a > d > c > e or b > a > d > e > c or b > c > d > a > e or b > c > d > e > a or b > e > d > a > c or b > e > d > c > a or c > a > d > b > e or c > a > d > e > b or c > b > d > a > e or c > b > d > e > a or c > e > d > a > b or c > e > d > b > a or e > a > d > b > c or e > a > d > c > b or e > b > d > a > c or e > b > d > c > a or e > c > d > a > b or e > c > d > b > a:
        print("La mediana es "  + str(d) + ".")
    elif b > c > e > a > d or b > c > e > a > d or b > c > e > d > a or b > c > e > d > a or b > d > e > a > c or b > d > e > a > c or b > d > e > c > a or b > d > e > c > a or c > b > e > a > d or c > b > e > a > d or c > b > e > d > a or c > b > e > d > a or c > e > b > a > d or c > e > b > a > d or c > e > b > d > a or c > e > b > d > a or d > b > e > a > c or d > b > e > a > c or d > b > e > c > a or d > b > e > c > a or d > c > e > a > b or d > c > e > a > b or d > c > e > b > a or d > c > e > b > a:
        print("La mediana es "  + str(d) + ".")
def pm(a:float, b:float, c:float, d:float, e:float):
    p2 = (a * b * c * d * e)**1/5
    print(p2)
def oa(a:float, b:float, c:float, d:float, e:float):
    l = [a, b, c, d, e]
    z = sorted(l)
    print(z)
def od(a:float, b:float, c:float, d:float, e:float):
    l = [a, b, c, d, e]
    z = sorted(l, reverse=True)
    print(z)
def po(a:float, b:float, c:float, d:float, e:float):
    l = [a, b, c, d, e]
    z = max(l)
    x = min(l)
    po = z**x
    print(po)
def cu(a:float, b:float, c:float, d:float, e:float): 
    l = [a, b, c, d, e]
    m = min(l)
    raiz = m**(1/3)
    print(raiz)
if __name__ == "__main__":
    a = float(input("Ingrese el primer número "))
    b = float(input("Ingrese el segundo número "))
    c = float(input("Ingrese el tercer número "))
    d = float(input("Ingrese el cuarto número "))
    e = float(input("Ingrese el quinto número "))
    promedio = p(a, b, c, d, e)
    mediana = me(a, b, c, d, e)
    promedio_mult = pm(a, b, c, d, e)
    orden_a = oa(a, b, c, d, e)
    orden_b = od(a, b, c, d, e)
    potencia = po(a, b, c, d, e)
    raiz = cu(a, b, c, d, e)
```    
# Punto 9
9. Consultar qué es y cómo funciona *pip* en python.
Pip en python es un sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python y descargarlos a nuestra computadora con la finalidad de integrarlos a nuestros desarrollos realizado en python. Muchos paquetes pueden ser encontrados en el Python Package Index (PyPI). Python 2.7.9 y posteriores (en la serie Python2), Python 3.4 y posteriores incluyen pip (pip3 para Python3) por defecto; lo cual no es necesario instalarlo en nuestra pc ya que al instalar python en la version 3.4 o superior en automaático se instala el gestor de paquetes.
Fuente(https://www.buscaminegocio.com/cursos-de-python/pip-en-python.html)
# Punto 10 
10. Hacer un listado de módulos populares para python que se puedan instalar com *pip* y consultar cómo instalarlos.
1.Colecciones
2.CSV
3.Aleatorio
4.Tkinter
5.Solicitudes
6.BeautifulSoup4
7.Numpy
8.Pandas
9.Matplotlib
10.TensorFlow



