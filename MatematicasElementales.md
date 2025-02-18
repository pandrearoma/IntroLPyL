# Curso de Introducción a la Lógica de Programación

## Repaso de Matemáticas Elementales

### Operaciones Básicas

1. **Suma (+)**: La operación de adición toma dos números y produce su total.
   ```markdown
   Ejemplo:
   5 + 3 = 8
   ```
2. **Resta (-)**: La operación de sustracción toma dos números y produce su diferencia.
   ```markdown
   Ejemplo:
   10 - 4 = 6
   ```
3. **Multiplicación (*)**: La operación de multiplicación toma dos números y produce su producto.
   ```markdown
   Ejemplo:
   4 - 7 = 28
   ```
4. **División (/)**: La operación de división toma dos números y produce su cociente.
   ```markdown
   Ejemplo:
   20 / 5 = 4
   ```
5. **Residuo (/)**: El residuo es la cantidad que sobra después de realizar una división entera.
   ```markdown
   Ejemplo:
   17 mod 5 = 2
   ```


## Pre-Álgebra

### Propiedades de las Operaciones

1. **Propiedad Conmutativa**:
   - **Suma**: El orden de los números no afecta la suma.
     \[ a + b = b + a \]
     ```markdown
     Ejemplo:
     3 + 5 = 5 + 3
     ```

   - **Multiplicación**: El orden de los números no afecta el producto.
     \[ a * b = b * a \]
     ```markdown
     Ejemplo:
     4 * 7 = 7 * 4
     ```

2. **Propiedad Asociativa**:
   - **Suma**: La forma en que los números se agrupan no afecta la suma.
     \[ (a + b) + c = a + (b + c) \]
     ```markdown
     Ejemplo:
     (2 + 3) + 4 = 2 + (3 + 4)
     ```

   - **Multiplicación**: La forma en que los números se agrupan no afecta el producto.
     \[ (a * b) * c = a * (b * c) \]
     ```markdown
     Ejemplo:
     (2 * 3) * 4 = 2 * (3 * 4)
     ```

3. **Propiedad Distributiva**:
   - Distribuir una multiplicación sobre una suma o resta.
     \[ a * (b + c) = a * b + a * c \]
     ```markdown
     Ejemplo:
     2 * (3 + 4) = 2 * 3 + 2 * 4
     ```


### Fracciones

1. **Definición**:
   - Una fracción representa una parte de un todo y se compone de un numerador (parte superior) y un denominador (parte inferior).

$$\frac{a}{b}$$

$$\frac{1}{2} = 1/2, \quad \frac{3}{4} = 3/4  \quad  \frac{5}{8} = 5/8$$ 

 #### **Máximo Común Divisor**: 
 El MCD de un conjunto de números es el mayor divisor común de esos números.

 **Método 1: Listado de Factores**
 
 1. Haz una lista de los factores de cada número.
 
  Factores de 12 : 1, 2, 3, 4, 6, 12
  
  Factores de 30 : 1, 2, 3, 5, 6, 10, 15, 30
  
 2. Encuentra el número más grande que comparten todas las filas anteriores. Este es el MCD.
 
  MCD = 6


 **Método 2: Factores Primos**
 
 1. Enumera los factores primos de cada número.
 
  Factor Primo de 12 : 2, 2, 3
  
  Factor Primo de 30 : 2, 3, 5
  
 2. Encuentra la intersección de estos números primos (factores comunes).
 
  2,3
  
 3. Multiplique estos números: 
 
  2×3=6
  
  MCD = 6
  

 
   Ejemplo:
   
MCD (225, 300)

225: **3**,3,**5**,**5**
300: 2,2,**3,5,5**


Comunes: 3,5,5

Se multiplican 2*5*5=75

**MCD=75**
  


 #### **Mínimo Común Múltiplo (MCM)**: 
El Mínimo Común Múltiplo (MCM) de dos o más números es el menor número positivo que es múltiplo de cada uno de esos números. En otras palabras, el MCM de un conjunto de números es el número más pequeño que es divisible por todos ellos

Método de Factorización:

Para encontrar el MCM mediante la factorización, sigue estos pasos:

1. Descompón cada número en sus factores primos.
2. Identifica los factores primos comunes y no comunes con sus mayores exponentes.
3. Multiplica estos factores para obtener el MCM.

Ejemplo
MCM
12: 2,2,3
15: 3,5

Los factores primos con sus mayores exponentes son: 
$$ 12 = 2^2 * 3   y   15 = 3 * 5 $$

$$ MCM (12,15) = 2^2 * 3 * 5 = 4* 3* 5= 60)$$ 




2. ### **Suma y Resta de Fracciones**:
   - Para sumar o restar fracciones, deben tener un denominador común MCM (Mínimo Común Múltiplo).

    a/b + c/d = (a*d + b+c) / b*d

   $$\frac{a}{b} + \frac{c}{d} = \frac{ad}{bd} + \frac{bc}{bd} = \frac{ad + bc}{bd}$$

         
1. **Encuentra un Denominador Común**:
   - El denominador común debe ser un múltiplo común de los denominadores de las fracciones que estás sumando. El denominador común más pequeño se llama Mínimo Común Múltiplo (MCM) de los denominadores.

2. **Ajusta las Fracciones**:
   - Convierte cada fracción a una fracción equivalente con el denominador común encontrado.

3. **Suma los Numeradores**:
   - Suma los numeradores de las fracciones ajustadas.

4. **Simplifica la Fracción Resultante**:
   - Simplifica la fracción resultante si es posible.

Ejemplo

Vamos a sumar las fracciones 

$$\frac{1}{4} + \frac{2}{3} $$.

##### Paso 1: Encuentra el Denominador Común

- Los denominadores son 4 y 3.
- El MCM de 4 y 3 es 12.

##### Paso 2: Ajusta las Fracciones

Convierte cada fracción a una fracción equivalente con el denominador común 12.

$\frac{1}{4}$ se convierte en $\frac{1 \times 3}{4 \times 3} = \frac{3}{12} $.

$\frac{2}{3}$ se convierte en $\frac{2 \times 4}{3 \times 4} = \frac{8}{12} $.

#### Paso 3: Suma los Numeradores

- Suma los numeradores de las fracciones ajustadas: \( 3 + 8 = 11 \).

#### Paso 4: Simplifica la Fracción Resultante

- La fracción resultante es $\frac{11}{12} $. No es necesario simplificar más ya que $\frac{11}{12} $ es la fracción más simple.

   
4. ### **Multiplicación y División de Fracciones**:
   - Multiplicación:
     $\frac{a}{b} \times \frac{c}{d} = \frac{a \times c}{b \times d} $
   
   Ejemplo
     $\frac{1}{2} \times \frac{2}{3} = \frac{1 \times 2}{2 \times 3} = \frac{2}{6} = \frac{1}{3}$
     

   - División:
     $\frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \times \frac{d}{c}$
   
     $\frac{1}{2} \div \frac{2}{3} = \frac{1}{2} \times \frac{3}{2} = \frac{3}{4}$
    

### Decimales

1. **Conversión entre Fracciones y Decimales**:
   - Para convertir una fracción a un decimal, divide el numerador entre el denominador.
     $\frac{3}{4} = 3 \div 4 = 0.7$
     
