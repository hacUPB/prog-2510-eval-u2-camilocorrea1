# Ejercicio 1.

## 1.  Cómo se representan los datos en una computadora.

Lo que son textos, números, imagenes, sonidos, etc, son representados en la computadora por medio de una trasnformación que se le hace a estos datos, la transformación es en secuencias de bits(0 y 1). Estos digitos son la base de la codificación, estos permiten a la computadora procesar y almacenar datos de una manera mas eficiente.

## 2. ¿Cuántos estados diferentes pueden ser representados por N variables binarias?

2 a la N. Es una exponencial que depende de N variables.

## 3. ¿Cuáles son las unidades de almacenamiento de datos que se utilizan en computación?
 
| Unidad       | Símbolo | Equivalencia en Bytes (B) |
|--------------|---------|--------------------------|
| **Bit**          | b       | 1 b       |
| **Byte**         | B       | 8 b       |
| **Kilobyte**     | KB      | 1,024 B   |
| **Megabyte**     | MB      | 1,024 KB  |
| **Gigabyte**     | GB      | 1,024 MB  |
| **Terabyte**     | TB      | 1,024 GB  |

## 4. la importancia del trabajo de George Bool.

La lógica booleana de George Boole ha sido fundamental en la informática moderna, permitiendo el desarrollo de circuitos lógicos, sistemas de programación e inteligencia artificial. Sus principios han sido clave en lenguajes como C++, Java y Python, así como en el diseño de dispositivos electrónicos como transistores y circuitos integrados.

# Ejercicio 2.

## De binarios a decimales

- 1010101010 = 512+128+32+8+2 = 682

- 11111 = 1+2+4+8+16 = 31

- 10000000 = 128

- 100100100 = 4+32+256 = 292

- 111000 = 8+16+32 = 56

## De decimales a binarios

- 127 = 64+32+16+8+4+2+1 = 1111111

- 246 = 128+64+32+16+4+2 = 11110110

- 1025 = 1024+1 = 10000000001

- 354 = 256+64+32+2 = 101100010

- 187 = 128+32+16+8+2+1 = 10111011

# Ejercicio 3.

- Enteros (int): Representan números enteros sin parte decimal. Pueden ser positivos, negativos o cero.

- Punto flotante (float o double): Representan números con parte decimal. Incluyen números decimales y exponenciales.

- Cadenas de caracteres (string): Representan secuencias de caracteres. Se utilizan para representar texto.

- Booleanos (bool): Representan valores de verdad, es decir, True o False. Se utilizan para expresar condiciones lógicas.

- Caracteres (char): Representan un solo carácter. Se utilizan en algunos lenguajes de programación para manipular caracteres individuales.

- Arreglo (array): una colección de valores, como [1, 2, 3] o [a, b, c].

- Conjuntos (Set): Los conjuntos son una colección no ordenada de elementos únicos. Los elementos en un conjunto no tienen orden, y no se repiten.

- Diccionarios (Dict): Los diccionarios son una colección de elementos que se acceden mediante una clave en lugar de un índice. 



# Ejercicio 4.

Tabla comparativa con los principales tipos de datos en **C, Java y Python**:

| Tipo de Dato     | Descripción                                    | C                     | Java                  | Python              |
|------------------|----------------------------------------------|-----------------------|-----------------------|---------------------|
| **Enteros**      | Números enteros positivos o negativos       | `int`                 | `int`                 | `int`               |
| **Enteros largos** | Valores enteros de mayor tamaño         | `long`, `long long`   | `long`                 | `int`                |
| **Flotantes**    | Números con decimales                      | `float`               | `float`               | `float`             |
| **Dobles**       | Mayor precisión en decimales               | `double`              | `double`              | `float`              |
| **Caracteres**   | Representa un solo carácter                | `char`                | `char`                | `str`                |
| **Cadenas de texto** | Conjunto de caracteres                | `char[]`, `string.h`  | `String`              | `str`               |
| **Booleanos**    | Verdadero o falso                          | `_Bool`              | `boolean`             | `bool`              |
| **Arreglos**     | Conjunto de elementos del mismo tipo       | `int arr[]`           | `int[] arr`           | `list` o `tuple`    |
| **Conjuntos**    | Colección de elementos únicos             | No disponible         | `Set`                 | `set`               |
| **Diccionarios** | Clave-valor (hashmaps)                    | No disponible         | `HashMap`             | `dict`              |

# Ejercicio 5.

|  Int  |  float  |  bool  |  string  |
|-------|---------|--------|----------|
|  4B   |   4B    |   1B   |    10B   |

19B por 10 segundos

60*60 = 3.600; 3.600*24 = 86.400; 86.400/10 = 8.640; 8.640*19B = 164,160B

De B a KB; 164,160B * 1024B = 168.099.840KB

# Ejercicio 6.

La representación binaria es la base de la computación, permitiendo el almacenamiento, procesamiento y manipulación eficiente de datos a través de la lógica booleana, sistemas numéricos y estructuras de datos en distintos lenguajes de programación.



