# Análisis del problema
# ¿Qué es la Lógica?

- La lógica es una disciplina que se ocupa de los principios y criterios de la validez inferencial y la demostración. Es una herramienta esencial para el pensamiento crítico y el razonamiento.
- Método o razonamiento en el que las ideas o la sucesión de los hechos se manifiestan o se desarrollan de forma **coherente** y **sin** que haya **contradicciones** entre ellas.

**Lógica natural**
1. f. Disposición natural de los seres humanos para pensar de forma coherente.


 <img src="../Img/Imagen2.jpg" alt="Camisa" width="200"/> “Manera más OBVIA Y FÁCIL de hacer cualquier cosa”


**Lógica de programación**
- En el contexto de la programación, la lógica es fundamental para la construcción de algoritmos y la solución de problemas de manera estructurada y eficiente.
- Habilidad de pensar de manera razonada, sistemática y ordenada que nos hace capaces de crear soluciones a problemas. 

Realizar los ejercicios de lógica [Ejercicios / Lógica](../Ejercicios/README.md)


## Importancia de la Lógica en la Programación

La lógica en la programación se utiliza para:

1. **Resolver Problemas**: Permite descomponer problemas complejos en partes más manejables, identificar patrones y formular soluciones efectivas.
2. **Diseñar Algoritmos**: Los algoritmos son secuencias de pasos lógicos para resolver un problema o realizar una tarea. Un buen entendimiento de la lógica es crucial para diseñar algoritmos correctos y eficientes.
3. **Tomar Decisiones**: La programación a menudo implica tomar decisiones basadas en condiciones específicas. La lógica ayuda a formular estas condiciones de manera clara y precisa.
4. **Depuración y Pruebas**: La capacidad de razonar lógicamente sobre el comportamiento del código es esencial para identificar y corregir errores, así como para asegurar que el software funcione correctamente bajo diversas condiciones.

## Tipos de Lógica

En programación, se utilizan principalmente los siguientes tipos de lógica:

1. **Lógica Proposicional**: Trata con proposiciones que pueden ser verdaderas o falsas y se combinan utilizando operadores lógicos como AND, OR, y NOT.
2. **Lógica de Predicados**: Extiende la lógica proposicional al incluir variables y cuantificadores, lo que permite expresar propiedades y relaciones más complejas.
3. **Lógica Difusa**: Permite trabajar con valores de verdad que no son estrictamente verdaderos o falsos, sino que pueden ser cualquier valor en un rango continuo.

## Ejemplos de Uso de Lógica en Programación

### Lógica Proposicional

a = True
b = False

# AND
print(a and b)  # False

# OR
print(a or b)  # True

# NOT
print(not a)  # False


# Problema
## ¿Qué es un problema?
Un problema es un enunciado en el cual se da cierta información y se plantea una pregunta que debe ser respondida; en general se pide calcular o indagar uno o más datos faltantes o generar explicaciones acerca de ciertos hechos o situaciones. 
Todo problema involucra una discrepancia o diferencia entre dos situaciones, una observada o dada y otra deseada. 
Resolver el problema es encontrar la manera de reducir o eliminar la discrepancia

Un problema es una situación, cuestión o asunto que requiere una solución. En el contexto de la programación, un problema es una tarea o desafío que debe resolverse mediante el uso de algoritmos y estructuras de datos.

### Cómo Abordar un Problema

Abordar un problema de programación generalmente implica los siguientes pasos:

1. **Comprender el Problema**: Leer y analizar cuidadosamente el enunciado del problema. Asegurarse de entender completamente los requisitos y las restricciones.
2. **Descomponer el Problema**: Dividir el problema en partes más pequeñas y manejables. Identificar los subproblemas y resolverlos por separado.
3. **Diseñar un Algoritmo**: Planificar una serie de **pasos lógicos** para resolver el problema. Utilizar diagramas de flujo o pseudocódigo para visualizar el algoritmo.
4. **Implementar el Algoritmo**: Escribir el código en un lenguaje de programación que siga los pasos del algoritmo diseñado.
5. **Probar y Depurar**: Ejecutar el programa con diferentes casos de prueba para asegurarse de que funciona correctamente. Identificar y corregir cualquier error.

### Procesos de Entrada/Proceso/Salida

En programación, el enfoque de entrada/proceso/salida (E/P/S) es una manera de estructurar la resolución de problemas. Cada problema puede ser visto en términos de:

1. **Entrada (Input)**: Los datos o información que se suministran al programa.
2. **Proceso (Process)**: Las operaciones o cálculos que el programa realiza sobre la entrada.
3. **Salida (Output)**: Los resultados o datos generados por el programa después del procesamiento.

### Ejemplo Práctico

#### Ejemplo de Problema

Queremos escribir un programa que calcule el promedio de tres números introducidos por el usuario.

#### Abordar el Problema

1. **Comprender el Problema**: El programa debe aceptar tres números como entrada y calcular su promedio.
2. **Descomponer el Problema**:
   - Leer tres números del usuario.
   - Sumar los tres números.
   - Dividir la suma entre tres para obtener el promedio.
3. **Diseñar un Algoritmo**:
   - Entrada: Leer tres números.
   - Proceso: Calcular la suma y el promedio.
   - Salida: Mostrar el promedio.

#### Implementación del Algoritmo


# Entrada: Leer tres números
numero1 = float(input("Ingrese el primer número: "))
numero2 = float(input("Ingrese el segundo número: "))
numero3 = float(input("Ingrese el tercer número: "))

# Proceso: Calcular la suma y el promedio
suma = numero1 + numero2 + numero3
promedio = suma / 3

# Salida: Mostrar el promedio
print("El promedio de los tres números es:", promedio)


# Algoritmos

### ¿Qué es un Algoritmo?

Un algoritmo es una secuencia finita de pasos bien definidos que se utilizan para resolver un problema o realizar una tarea específica. En términos simples, un algoritmo es un conjunto de instrucciones que, cuando se siguen, producen un resultado deseado.

### Características de un Algoritmo

1. **Finito**: Un algoritmo debe tener un número finito de pasos.
2. **Definido**: Cada paso del algoritmo debe estar claramente definido y no debe haber ambigüedades.
3. **Entrada**: Un algoritmo debe aceptar cero o más entradas.
4. **Salida**: Un algoritmo debe producir al menos una salida.
5. **Eficiente**: Un algoritmo debe ser eficiente en términos de tiempo y espacio, aunque esto puede depender del contexto y de las restricciones del problema.

### Importancia de los Algoritmos en Programación

Los algoritmos son fundamentales en la programación porque:

- **Solucionan Problemas**: Proporcionan un método estructurado para resolver problemas.
- **Optimizan Recursos**: Ayudan a encontrar soluciones óptimas en términos de tiempo de ejecución y uso de memoria.
- **Mejoran la Comprensión**: Facilitan la comprensión de problemas complejos al descomponerlos en pasos más simples.
- **Aseguran la Correctitud**: Aseguran que las soluciones son correctas y cumplen con los requisitos especificados.

### Ejemplo de Algoritmo

#### Encontrar el Máximo entre dos Números

**Pseudocódigo**:

```plaintext
Algoritmo EncontrarMaximo
  Entrada: a, b (dos números)
  Si a > b Entonces
    maximo <- a
  Sino
    maximo <- b
  FinSi
  Salida: maximo
FinAlgoritmo

