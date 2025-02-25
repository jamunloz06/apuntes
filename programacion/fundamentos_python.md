Python es un lenguaje de programación interpretado, de alto nivel y multipropósito. Es conocido por su sintaxis simple y legible, lo que lo hace ideal para principiantes y a la vez poderoso para desarrolladores experimentados.

## **1. Características de Python**
- **Sintaxis clara y legible:** Usa indentación en lugar de llaves `{}`.
- **Lenguaje interpretado:** No necesita compilación, se ejecuta línea por línea.
- **Tipado dinámico:** No es necesario declarar tipos de variables.
- **Multiparadigma:** Soporta programación estructurada, orientada a objetos y funcional.
- **Gran comunidad y librerías:** Existen muchos módulos y frameworks listos para usar.

---

## **2. Instalación y Configuración**
Para instalar Python:
1. Descárgalo desde [python.org](https://www.python.org/)
2. Instálalo y verifica la versión con:
   ```sh
   python --version  # O en algunos sistemas: python3 --version
   ```

Para ejecutar Python:
- Desde la terminal: `python`
- Desde un archivo `.py`: `python script.py`
- Usando Jupyter Notebook o entornos como PyCharm, VS Code.

---

## **3. Variables y Tipos de Datos**
```python
# Tipos de datos básicos
entero = 10          # int
decimal = 3.14       # float
texto = "Hola"       # str
booleano = True      # bool
lista = [1, 2, 3]    # list
tupla = (1, 2, 3)    # tuple
diccionario = {"clave": "valor"}  # dict

# Imprimir valores y tipos
print(entero, type(entero))
```

---

## **4. Operadores Básicos**
```python
a = 10
b = 3

# Operaciones matemáticas
suma = a + b        # 13
resta = a - b       # 7
multiplicacion = a * b  # 30
division = a / b    # 3.333
division_entera = a // b  # 3
modulo = a % b      # 1
potencia = a ** b   # 1000

# Operadores de comparación
print(a > b)   # True
print(a == b)  # False
print(a != b)  # True
```

---

## **5. Estructuras de Control**
### **Condicionales**
```python
edad = 18

if edad >= 18:
    print("Eres mayor de edad")
elif edad >= 13:
    print("Eres adolescente")
else:
    print("Eres niño")
```

### **Bucles**
```python
# Bucle for
for i in range(5):  # 0, 1, 2, 3, 4
    print(i)

# Bucle while
contador = 0
while contador < 5:
    print(contador)
    contador += 1
```

---

## **6. Funciones**
```python
def saludar(nombre):
    return f"Hola, {nombre}!"

print(saludar("Carlos"))  # Hola, Carlos!
```

---

## **7. Listas y Diccionarios**
```python
# Listas
numeros = [1, 2, 3, 4, 5]
numeros.append(6)  # Agregar elemento
print(numeros[0])  # Acceder al primer elemento

# Diccionarios
persona = {"nombre": "Ana", "edad": 25}
print(persona["nombre"])  # Ana
```

---

## **8. Programación Orientada a Objetos (POO)**
```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def presentar(self):
        return f"Soy {self.nombre} y tengo {self.edad} años"

p1 = Persona("Juan", 30)
print(p1.presentar())  # Soy Juan y tengo 30 años
```

---

## **9. Manejo de Excepciones**
```python
try:
    resultado = 10 / 0
except ZeroDivisionError:
    print("Error: División por cero")
finally:
    print("Fin del bloque")
```

---

## **10. Módulos y Librerías**
```python
import math
print(math.sqrt(16))  # 4.0
```

Python tiene una gran cantidad de bibliotecas como `numpy`, `pandas`, `requests`, `matplotlib`, entre otras.

---

