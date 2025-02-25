Los **fundamentos de la programación** son los conceptos básicos y principios que forman la base del desarrollo de software. Aquí tienes un resumen de los elementos clave:

---

### **1. Algoritmos**
Un **algoritmo** es una secuencia de pasos definidos y finitos para resolver un problema o realizar una tarea.

Ejemplo (pseudocódigo para sumar dos números):
```
Inicio
    Leer num1
    Leer num2
    suma ← num1 + num2
    Escribir suma
Fin
```

---

### **2. Lenguajes de Programación**
Los **lenguajes de programación** permiten escribir código que las computadoras pueden interpretar y ejecutar. Se dividen en:

- **Lenguajes de bajo nivel** (Ej: Ensamblador, C)
- **Lenguajes de alto nivel** (Ej: Java, Python, JavaScript)
- **Lenguajes compilados vs. interpretados**:
  - **Compilados**: Traducen todo el código a máquina antes de ejecutarse (Ej: C, Java).
  - **Interpretados**: Ejecutan línea por línea (Ej: Python, JavaScript).

---

### **3. Tipos de Datos**
Los **tipos de datos** definen qué tipo de valores puede almacenar una variable:

- **Enteros (int)** → Números sin decimales (Ej: `42`)
- **Decimales (float, double)** → Números con decimales (Ej: `3.14`)
- **Caracteres (char)** → Un solo carácter (Ej: `'A'`)
- **Cadenas de texto (String)** → Conjunto de caracteres (Ej: `"Hola"`)
- **Booleanos (boolean)** → `true` o `false`

---

### **4. Variables y Constantes**
- **Variable**: Espacio en memoria que puede cambiar su valor.
  ```java
  int edad = 25; // Variable que almacena un número entero
  ```
- **Constante**: Su valor no cambia durante la ejecución del programa.
  ```java
  final double PI = 3.1416; // Constante en Java
  ```

---

### **5. Operadores**
Son símbolos que permiten realizar operaciones:

- **Aritméticos** (`+`, `-`, `*`, `/`, `%`)
- **Relacionales** (`==`, `!=`, `>`, `<`, `>=`, `<=`)
- **Lógicos** (`&&`, `||`, `!`)

Ejemplo en Java:
```java
int a = 10, b = 5;
int suma = a + b; // 15
boolean esMayor = a > b; // true
```

---

### **6. Estructuras de Control**
Permiten modificar el flujo de ejecución del programa.

#### **Condicionales**
```java
if (edad >= 18) {
    System.out.println("Eres mayor de edad.");
} else {
    System.out.println("Eres menor de edad.");
}
```

#### **Bucles**
- **while** → Se ejecuta mientras la condición sea verdadera.
  ```java
  int i = 0;
  while (i < 5) {
      System.out.println(i);
      i++;
  }
  ```
- **for** → Se ejecuta un número determinado de veces.
  ```java
  for (int i = 0; i < 5; i++) {
      System.out.println(i);
  }
  ```
- **do-while** → Se ejecuta al menos una vez.
  ```java
  int i = 0;
  do {
      System.out.println(i);
      i++;
  } while (i < 5);
  ```

---

### **7. Funciones o Métodos**
Son bloques de código reutilizables que realizan una tarea específica.

```java
public static int suma(int a, int b) {
    return a + b;
}
```
Llamada a la función:
```java
int resultado = suma(5, 3);
System.out.println(resultado); // 8
```

---

### **8. Arreglos (Arrays)**
Son estructuras que almacenan múltiples valores del mismo tipo.

```java
int[] numeros = {1, 2, 3, 4, 5};
System.out.println(numeros[0]); // 1
```

---

### **9. Programación Orientada a Objetos (POO)**
Es un paradigma basado en clases y objetos.

- **Clase**: Modelo que define atributos y métodos.
- **Objeto**: Instancia de una clase.

Ejemplo en Java:
```java
class Coche {
    String marca;
    
    public void acelerar() {
        System.out.println("El coche está acelerando.");
    }
}

// Creación de objeto
Coche miCoche = new Coche();
miCoche.marca = "Toyota";
miCoche.acelerar();
```

---

### **10. Manejo de Excepciones**
Permite capturar errores y evitar que el programa se detenga abruptamente.

```java
try {
    int resultado = 10 / 0; // Error: División por cero
} catch (ArithmeticException e) {
    System.out.println("Error: No se puede dividir por cero.");
}
```

---
