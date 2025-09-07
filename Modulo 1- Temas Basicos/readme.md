# 📘 Módulo 1 – Introducción a la Programación en Python

Imaginemos que aprender Python es como aprender a hablar un nuevo idioma.
Primero necesitamos aprender cómo **decir cosas**, cómo **escuchar lo que otros dicen** y cómo **hacer cuentas simples**.

---

## 🔹 1. Hablar con la computadora → `print()`

👉 La función `print()` es como la “boca” de tu programa: sirve para **decir algo en la pantalla**.
Si no usamos `print()`, el programa se queda mudo.

**Ejemplo de la vida real:**

* Si querés que la compu te salude, le decís:

  ```python
  print("Hola, mundo!")
  ```

  **Salida en pantalla:**

  ```
  Hola, mundo!
  ```

También podés hacer que diga el valor de una variable:

```python
nombre = "Ana"
print("Tu nombre es:", nombre)
```

📌 **Idea clave:** `print()` sirve para mostrar cualquier cosa que el programa sepa.

---

## 🔹 2. Escuchar al usuario → `input()`

👉 La función `input()` es como los **oídos** del programa.
Le permite **preguntarle algo al usuario** y esperar la respuesta.

**Ejemplo:**

```python
nombre = input("¿Cómo te llamas? ")
print("Encantado de conocerte,", nombre)
```

* La computadora muestra:

  ```
  ¿Cómo te llamas?
  ```
* Si vos escribís `José`, la salida será:

  ```
  Encantado de conocerte, José
  ```

⚠️ Importante: Todo lo que entra por `input()` se guarda como **texto** (aunque escribas un número).

---

## 🔹 3. Saber qué tipo de dato tenemos → `type()`

👉 En la vida real sabés distinguir entre **números** y **palabras**.
La computadora también necesita eso. Con `type()` podemos preguntarle **qué clase de dato tiene una variable**.

**Ejemplo:**

```python
print(type(5))        # número entero (int)
print(type(5.0))      # número con decimales (float)
print(type("Hola"))   # texto (str)
```

Esto es como cuando jugás a clasificar:

* Una manzana es una fruta 🍎
* El 5 es un número 🔢
* “Hola” es una palabra 💬

---

## 🔹 4. Medir cosas → `len()`

👉 `len()` es como usar una **regla o un contador**.
Sirve para saber **cuántos caracteres** tiene un texto.

**Ejemplo:**

```python
frase = "Hola a todos!"
print(len(frase))   # 13
```

📌 Contá los caracteres (incluyendo espacios y signos):
`H o l a _ a _ t o d o s !` → en total **13**.

---

## 🔹 5. Jugar con cadenas de texto

Los textos (en programación se llaman **strings**) tienen trucos, como las cartas de un mago 🎩✨.

* `.count()` → **contar apariciones** de algo.

  ```python
  texto = "Hola a todos!"
  print(texto.count("o"))   # 3
  ```

* `.lower()` → poner todo en **minúsculas**.

  ```python
  print("Hola A TODOS".lower())   # "hola a todos"
  ```

* `.upper()` → poner todo en **MAYÚSCULAS**.

  ```python
  print("Hola a todos".upper())   # "HOLA A TODOS"
  ```

---

## 🔹 6. Matemáticas con Python

👉 Python también sabe hacer cuentas como en la escuela:

| Operador | Significado               | Ejemplo  | Resultado |
| -------- | ------------------------- | -------- | --------- |
| `+`      | Suma                      | `5 + 3`  | `8`       |
| `-`      | Resta                     | `5 - 3`  | `2`       |
| `*`      | Multiplicación            | `5 * 3`  | `15`      |
| `/`      | División                  | `5 / 2`  | `2.5`     |
| `//`     | División entera           | `5 // 2` | `2`       |
| `%`      | Resto de la división      | `5 % 2`  | `1`       |
| `**`     | Exponenciación (potencia) | `2 ** 3` | `8`       |

📌 Ejemplo divertido:

```python
galletas = 7
amigos = 3
print("A cada amigo le tocan", galletas // amigos, "galletas")
print("Sobran", galletas % amigos, "galletas")
```

Salida:

```
A cada amigo le tocan 2 galletas
Sobran 1 galleta
```

---