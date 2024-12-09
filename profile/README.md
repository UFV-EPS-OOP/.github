# Roadmap de C# y Programación Orientada a Objetos

## C#: Fundamentos del lenguaje

### 1. Introducción al Lenguaje C#

- ¿Qué es C#?
- Configuración del entorno (Visual Studio, .NET SDK).
- Primer programa en C# (Hello, World!)

### 2. Variables y Tipos de Datos

- Declaración de variables.
- Tipos de datos primitivos (int, double, string, bool).
- Literales (verbatim, interpolación de cadenas).
- Conversión de tipos (implicit, explicit, Convert, Parse).

### 3. Operadores y Expresiones

- Operadores aritméticos, relacionales, lógicos y bit a bit.
- Operadores de asignación compuesta (+=, -=).
- Operadores avanzados: ternario (`?:`), `??` y `??=`.

### 4. Estructuras Condicionales

- Uso de `if`, `else if` y `else`.
- Expresiones `switch` clásicas.
- Expresiones `switch` basadas en patrones (`case`, `when`).

### 5. Bucles y Control de Flujo

- Bucles: `for`, `while`, `do-while`.
- Uso de `break` y `continue`.

### 6. Constantes y Enumeraciones

- Declaración y uso de `const` y `readonly`.
- Definición de enumeraciones (`enum`).
- Ventajas de usar enumeraciones frente a valores literales.

### 7. Arrays y Colecciones Básicas

- Arrays unidimensionales, multidimensionales y jagged arrays (arrays de arrays).
- Operaciones con arrays (`Length`, `IndexOf`).
- Introducción a listas (`List<T>`) y diccionarios (`Dictionary<TKey, TValue>`).
- Bucles `foreach` para colecciones.

### 8. Métodos y Funciones

- Declaración de métodos.
- Parámetros: valor, `ref`, `out` y predeterminados.
- Retorno de valores.
- Métodos de extensión.

### 9. Manejo Básico de Excepciones

- Bloques `try-catch-finally`.
- Lanzamiento de excepciones (`throw`).
- Excepciones comunes en C#.
- Uso de `using` para manejar recursos.

### 10. Entrada y Salida

- Entrada desde la consola (`Console.ReadLine()`).
- Salida a la consola (`Console.WriteLine()`).
- Introducción al manejo básico de archivos (`File.ReadAllText`, `File.WriteAllText`).

---

## Programación Orientada a Objetos (OOP)

### 1. Conceptos Fundamentales de OOP

- ¿Qué es OOP?
- Diferencia entre programación estructurada y orientada a objetos.
- Principios básicos: Encapsulación, Herencia, Polimorfismo y Abstracción.

### 2. Clases y Objetos en C#

- ¿Qué son las clases y objetos?
- Definición de clases.
- Creación e instanciación de objetos.
- Diferencia entre tipos por valor y por referencia.

### 3. Propiedades y Encapsulación

- Propiedades automáticas y personalizadas (`get` y `set`).
- Modificadores de acceso (`public`, `private`, `protected`, `internal`).
- Uso de propiedades para encapsular campos.

### 4. Constructores en C#

- Tipos de constructores: predeterminados, parametrizados y estáticos.
- Uso de `this` y `base` en constructores.
- Sobrecarga de constructores.

### 5. Métodos en Clases

- Métodos de instancia y métodos estáticos.
- Sobrecarga de métodos.
- Uso de parámetros opcionales y nombrados.

### 6. Herencia

- ¿Qué es la herencia?
- Creación de clases derivadas.
- Uso del operador `base` para acceder a miembros de la clase padre.
- Modificadores relacionados con herencia (`sealed`, `new`).

### 7. Polimorfismo

- Introducción al polimorfismo.
- Métodos virtuales y sobrescritura (`virtual`, `override`).
- Diferencia entre polimorfismo en tiempo de compilación y tiempo de ejecución.

### 8. Clases Abstractas

- Definición de clases abstractas.
- Métodos abstractos y concretos.
- Uso práctico de abstracción.

### 9. Interfaces

- Definición y propósito de las interfaces.
- Diferencias entre interfaces y clases abstractas.
- Implementación de múltiples interfaces.

### 10. Introducción a los Principios SOLID

- S: Principio de responsabilidad única (Single Responsibility).
- O: Principio de abierto/cerrado (Open/Closed).
- L: Principio de sustitución de Liskov (Liskov Substitution).
- I: Principio de segregación de interfaces (Interface Segregation).
- D: Principio de inversión de dependencias (Dependency Inversion).
