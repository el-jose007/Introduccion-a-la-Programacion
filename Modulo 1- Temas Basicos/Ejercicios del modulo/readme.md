# ✅ Ejercicios resueltos – Semana 1

Aquí encontrarás las soluciones explicadas de los 10 ejercicios propuestos en el PDF.

---

## 1. Área y perímetro de una circunferencia

```python
import math

radio = float(input("Ingrese el radio de la circunferencia: "))

area = math.pi * radio**2
perimetro = 2 * math.pi * radio

print("Área:", area)
print("Perímetro:", perimetro)
 ```

👉 Usamos math.pi para tomar el valor de π. Esto esta en el apunte. La verdad que se podria hacer directamente sin importar nada, es realmente simple.

👉 Fórmulas:

    Área = π * r²

    Perímetro = 2 * π * r

## 2. Precio promedio de un producto

 ```Python

p1 = float(input("Ingrese el precio en la primera tienda: "))
p2 = float(input("Ingrese el precio en la segunda tienda: "))
p3 = float(input("Ingrese el precio en la tercera tienda: "))

promedio = (p1 + p2 + p3) / 3
print("El precio promedio es:", promedio)
 ```

👉 Se suman los tres precios y se dividen entre 3.

## 3. Conversión de metros

 ```Python

metros = float(input("Ingrese la cantidad de metros: "))

cm = metros * 100
mm = metros * 1000
pulgadas = cm / 2.54

print("Centímetros:", cm)
print("Milímetros:", mm)
print("Pulgadas:", pulgadas)
```
👉 Recordá:

    1 m = 100 cm

    1 m = 1000 mm

    1 pulgada = 2.54 cm

## 4. Consumo de combustible

``` Python

litros = float(input("Litros cargados: "))
km = float(input("Kilómetros recorridos: "))
# aca resolvemos:
consumo = km / litros
print("El consumo es de", consumo, "km por litro.")
```

👉 Se divide la distancia recorrida por la cantidad de litros consumidos.

## 5. Intercambio de variables

```Python

num1 = int(input("Ingrese el primer número: "))
num2 = int(input("Ingrese el segundo número: "))

aux = num1
num1 = num2
num2 = aux

print("Después del intercambio: num1 =", num1, "num2 =", num2)
 ```
👉 Guardamos el primer valor en una variable auxiliar, luego hacemos el cambio.

## 6. Porcentaje de niños y niñas

```Python

ninos = int(input("Cantidad de niños: "))
ninas = int(input("Cantidad de niñas: "))

total = ninos + ninas

porcentaje_ninos = (ninos * 100) / total
porcentaje_ninas = (ninas * 100) / total

print("Niños:", porcentaje_ninos, "%")
print("Niñas:", porcentaje_ninas, "%")
```
👉 Regla de 3 simple: (parte * 100) / total.

# 7. Área y perímetro de un rectángulo

```Python

base = float(input("Ingrese la base: "))
altura = float(input("Ingrese la altura: "))

area = base * altura
perimetro = 2 * base + 2 * altura

print("Área:", area)
print("Perímetro:", perimetro)
```
👉 Fórmulas:

    Área = base * altura

    Perímetro = 2 * base + 2 * altura

## 8. Volumen de un cilindro

```Python

import math

radio = float(input("Ingrese el radio: "))
altura = float(input("Ingrese la altura: "))

volumen = math.pi * radio**2 * altura

print("Volumen del cilindro:", volumen)
# Este es otro caso en el que no es necesario para usar math.pi
```
👉 Fórmula: volumen = π * r² * h.

## 9. Conversión de días

```Python

dias = int(input("Ingrese la cantidad de días: "))

# recorda que in INT, convierte el tipo de datos te texto (String o str) a numero entero (INT)

horas = dias * 24
minutos = horas * 60
segundos = minutos * 60

print(dias, "días equivalen a:")
print(horas, "horas")
print(minutos, "minutos")
print(segundos, "segundos")
```

👉 Conversión directa:
```
    1 día = 24 horas

    1 hora = 60 minutos

    1 minuto = 60 segundos
```
## 10. Porcentaje de aumento de precio

```Python
precio_inicial = float(input("Ingrese el precio al inicio del año: "))
precio_final = float(input("Ingrese el precio al final del año: "))

aumento = ((precio_final - precio_inicial) * 100) / precio_inicial

print("El porcentaje de aumento es:", aumento, "%")
```


# Recorda:
* Los input generan cadenas de texto.
* si necesitas una entrada tenes que convertirlo a el tipo adecuada de dato. por ejemplo:
```Python
Numero = input("Ingresa un dato: ") 
```
Gererara una cadena de texto que no se puede operar. Por mas que lo veas como un numero, python lo trata como una cadena de texto y no se le puede sumarni restar nada. 

En cambio, podemos cambiar el tipo, encerrandolo en un int. 

```Python
Numero = int(input("Ingresa un dato: "))