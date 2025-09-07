# 📝 Ejercicios – Módulo 1

Ahora sí, probemos lo aprendido:

1.  Haz que tu programa salude al mundo con `print()`.
2.  Pídele al usuario su nombre y respóndele con un saludo.
3.  Pregunta la edad del usuario y muestra en pantalla qué tipo de dato se guardó.
4.  Pide una frase y muestra cuántos caracteres tiene.
5.  Pide una frase y cuenta cuántas veces aparece la letra "e".
6.  Convierte en mayúsculas una palabra que ingrese el usuario.
7.  Convierte en minúsculas una frase escrita en mayúsculas.
8.  Pide dos números al usuario, súmalos y muestra el resultado.
9.  Divide 17 galletas entre 5 amigos usando `//` y `%` para mostrar cuántas recibe cada uno y cuántas sobran.
10. **Programa desafío 🎯:** Pregunta el nombre y edad del usuario, y muestra:
    `Hola [nombre], dentro de 10 años tendrás [edad+10] años.`

---

#Respuestas explicadas:

# ✅ Soluciones comentadas – Módulo 1

En esta sección encontrarás las soluciones a los 10 ejercicios propuestos, con explicaciones paso a paso.

---

## 1. Haz que tu programa salude al mundo con `print()`.
```python
print("Hola, mundo!")
````

👉 Simplemente mostramos un mensaje fijo en pantalla.

---

## 2. Pídele al usuario su nombre y respóndele con un saludo.

```python
nombre = input("¿Cómo te llamas? ")
print("Encantado de conocerte,", nombre)
```

👉 `input()` escucha lo que el usuario escribe.
👉 Guardamos el texto en la variable `nombre`.
👉 Luego lo mostramos con `print()`.

---

## 3. Pregunta la edad del usuario y muestra en pantalla qué tipo de dato se guardó.

```python
edad = input("¿Cuántos años tienes? ")
print("Ingresaste:", edad)
print("El tipo de dato es:", type(edad))
```

👉 Aunque escribas un número, `input()` lo guarda como texto (`str`).
👉 `type()` nos confirma qué tipo de dato tiene la variable.

---

## 4. Pide una frase y muestra cuántos caracteres tiene.

```python
frase = input("Escribe una frase: ")
print("La frase tiene", len(frase), "caracteres.")
```

👉 `len()` cuenta letras, espacios y signos de puntuación.

---

## 5. Pide una frase y cuenta cuántas veces aparece la letra `"e"`.

```python
frase = input("Escribe una frase: ")
print("La letra 'e' aparece", frase.count("e"), "veces.")
```

👉 `.count("e")` busca cuántas `"e"` hay dentro del texto.

---

## 6. Convierte en **mayúsculas** una palabra que ingrese el usuario.

```python
palabra = input("Escribe una palabra: ")
print("En mayúsculas:", palabra.upper())
```

👉 `.upper()` transforma todas las letras a mayúsculas.

---

## 7. Convierte en **minúsculas** una frase escrita en mayúsculas.

```python
frase = input("Escribe una frase en MAYÚSCULAS: ")
print("En minúsculas:", frase.lower())
```

👉 `.lower()` convierte todo a minúsculas.

---

## 8. Pide dos números al usuario, súmalos y muestra el resultado.

```python
n1 = input("Escribe un número: ")
n2 = input("Escribe otro número: ")

# Convertimos a enteros porque input() guarda como texto
n1 = int(n1)
n2 = int(n2)

print("La suma es:", n1 + n2)
```

👉 `int()` convierte el texto en número entero.
👉 Así podemos sumarlos correctamente.

---

## 9. Divide 17 galletas entre 5 amigos usando `//` y `%`.

```python
galletas = 17
amigos = 5

print("A cada amigo le tocan", galletas // amigos, "galletas")
print("Sobran", galletas % amigos, "galletas")
```

👉 `//` divide enteros (sin decimales).
👉 `%` da el resto de la división.

**Salida:**

```
A cada amigo le tocan 3 galletas
Sobran 2 galletas
```

---

## 10. Programa desafío 🎯

```python
nombre = input("¿Cómo te llamas? ")
edad = input("¿Cuántos años tienes? ")

# Convertimos la edad a número
edad = int(edad)

print("Hola", nombre + ", dentro de 10 años tendrás", edad + 10, "años.")
```

👉 Pedimos nombre y edad.
👉 Convertimos la edad a número para poder sumarle 10.
👉 Mostramos el mensaje final.

---
