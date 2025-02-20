# Ejercicio 1.

1. Óvalo (símbolo de terminal).

Etiquete siempre este símbolo de diagrama de flujo claramente como 'Inicio' o 'Fin' para definir los límites de todo el proceso, garantizando que los espectadores puedan identificar fácilmente dónde comienza y dónde concluye el flujo de trabajo.

![Ovalo](https://clickup.com/blog/wp-content/uploads/2024/09/Oval.png)

2. Rectángulo (símbolo de proceso).

Este símbolo de proceso describe tareas, acciones u operaciones específicas dentro del proceso, proporcionando rótulos detallados que aclaran lo que ocurre en cada fase. Es el símbolo más utilizado y forma el núcleo de la mayoría de los organigramas.

![Rectangulo](https://clickup.com/blog/wp-content/uploads/2024/09/Rectangle.png)

3. Diamante (símbolo de decisión).

Añádalo donde se plantee una pregunta que conduzca a diferentes resultados para indicar un punto de decisión dentro del proceso. del diamante deben surgir *ramas basadas en los posibles resultados (por ejemplo, Sí/No o Verdadero/Falso). Etiquete claramente cada rama para guiar el flujo de la toma de decisiones.

![Diamante](https://clickup.com/blog/wp-content/uploads/2024/09/Diamond.png)

4. Paralelogramo (Símbolo de entrada/salida).

Utilice este símbolo para ilustrar los puntos en los que se introducen datos o se producen resultados. Es esencial para visualizar el flujo de datos en procesos que implican la interacción del usuario o la salida del sistema.

![Paralelogramo](https://clickup.com/blog/wp-content/uploads/2024/09/Parallelogram.png)

5. Flecha (Línea de flujo).

Considérelas como las líneas de vida de su diagrama de flujo, que guían al espectador a través del proceso. Conectan símbolos y muestran la dirección. Asegúrese de que están colocadas claramente y evite cruzar las líneas para mantener la claridad.

![Flecha](https://clickup.com/blog/wp-content/uploads/2024/09/Arrow.png)

6. Símbolo del documento.

Utilice este símbolo para ilustrar dónde se crean, revisan o utilizan los documentos en el proceso, ayudando a seguir el flujo de documentos en papel o digitales.

![Simb](https://clickup.com/blog/wp-content/uploads/2024/09/Document-symbol-.png)

7. Símbolo de entrada manual.

Utilice este símbolo para resaltar las interacciones del usuario que requieren la introducción de datos, que pueden ser cruciales para comprender las dependencias del proceso en las acciones manuales.

![Entrada manual](https://clickup.com/blog/wp-content/uploads/2024/09/image-478.png)

# Ejercicio 2.

Algoritmo que, al recibir como datos el ID del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual.

![Diagrama del algoritmo](<Diagrama de flujo.png>)

# Ejercicios.

1) Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. 

Inicio
Leer lS          # lS = cantidad de lapices
Si LS >= 1000
    CT = 85 * LS   # CT = costos lapices
Si no 
    CT = 90 * LS
fin si
Escribir "el costo de los lapices es de: $",CT
Fin

2) Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá.
 
Inicio
Leer CMP       # CMP = valor de compra
Si CMP > 250000
    Ds = 0.15 * CMP  # Ds = descuento
Si no 
    Ds = 0.08 * CMP 
Fin si
PF = CMP - Ds   # PF = precio final
Escribir "Precio final de la compra de $" PF "con un descuento aplicado de" Ds
Fin

3) El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

Inicio 
Leer alumnos 
Si alumnos >= 100
    precio = 65 * alumnos
Si no
    Si alumnos >= 50
        precio = 70 * alumnos
    Si no
        Si alumnos >= 30
            precio = 95 * alumnos
        Si no
            precio = 4000/alumnos
Escribir "precio total" precio
Fin

# Ejercicios libro algoritmos.

1) 

Inicio 
sal_ini = 1500
incre_anual = 0.10
desde cont = 1 hasta cont = 6
	aumento = sal_ini*incre_anual
	sal_ini = sal_ini + aumento
    escribir salario anual de, sal_ini
fin mientras
escribir salario al cabo de 6 años, sal_ini
Fin

2) 

Inicio
precio_S = 20
precio_D = 25
precio_T = 28
cargo_tarjeta = 0.05
total_pagar = 0
cont = 1
Escribir "Ingrese el número de hamburguesas a comprar: "
leer NH
Mientras cont <= NH
    Escribir "Ingrese el tipo de hamburguesa (S, D, T) para la hamburguesa: "
    Leer tipo
    Si tipo = "S" Entonces
        total_pagar = total_pagar + PRECIO_S
        cont = cont + 1
    Sino 
        Si tipo = "D" Entonces
            total_pagar ← total_pagar + PRECIO_D
            cont = cont + 1
        Sino
            Si tipo = "T" Entonces
                total_pagar ← total_pagar + PRECIO_T
                cont = cont + 1
            Sino
                Escribir "Tipo inválido. Por favor, ingrese S, D o T."
    Fin Si
Fin Mientras
Escribir "¿Pagará con tarjeta? (si/No)"
Leer pago_tarjeta
Si pago_tarjeta = "si" Entonces
    total_pagar = total_pagar + (total_pagar * cargo_tarjeta)
si no
    si pago_tarjeta == 'no':
        total_pagar == total_pagar
    si no
        print("Ingrese si o no")
Fin Si
Escribir "El total a pagar es: $", total_pagar
Fin

# Parte 1: Identificar Algoritmos.

1) Una página web.

No representa un algoritmo. 
Una página web es un sitio web que puede contener información, pero en sí misma no define un conjunto de pasos claros para resolver un algoritmo.

2) Receta para hacer un pastel, donde se indican ingredientes y pasos a seguir.

Sí representa un algoritmo. 
Una receta es un algoritmo, ya que ofrece una serie de pasos ordenados y específicos que, producen un resultado esperado.

3) "Piensa en un número y multiplícalo por otro".

No representa un algoritmo completo. 
Este sugiere una operación, no es un algoritmo porque no es del todo claro o preciso, ya que no indica qué números usar ni qué hacer después.

4) Un manual de instrucciones para armar un mueble, con pasos detallados y un orden claro.

Sí representa un algoritmo. 
El manual da instrucciones claras, detalladas y secuenciales para lograr un objetivo específico, lo que lo convierte en un algoritmo.

5) Una lista de compras organizada en orden alfabético.

No representa un algoritmo. 
Una lista de compras es solo un conjunto de datos organizados. No incluye pasos o instrucciones para resolver un problema o alcanzar un objetivo.

# Parte 2: Variables y Constantes.

1) El valor de la gravedad en la Tierra, 9.8 m/s².

Constante. 
Este valor no cambia, por lo que es una constante.

2) La edad de una persona calculada en base al año actual y su año de nacimiento.

Variable. 
La edad cambia con el pasar del tiempo, por lo que es un valor variable.

3) La cantidad de dinero en una cuenta bancaria.

Variable. 
El saldo puede aumentar o disminuir debido a depósitos, retiros, lo que lo convierte en una variable.

4) La velocidad de la luz en el vacío, 299,792,458 m/s.

Constante. 
Este valor es una constante y no cambia.

5) El radio de un círculo.

Variable. 
Depende del círculo que se esté considerando, por lo que puede variar su radio.

# Parte 3: Características de los Algoritmos.

1) Para elegir la ruta más corta entre varias ciudades, el algoritmo examina rutas candidatas, deteniéndose cuando los cambios en la distancia parecen lo suficientemente pequeños.

No cumple con todas las características de un algoritmo. 
Aunque el proceso tiene un objetivo claro, carece de finitud y precisión. Detenerse cuando los cambios "parecen lo suficientemente pequeños" es ambiguo, lo que impide que el algoritmo sea realizado correctamente.

2) Suma los números ingresados y muestra el resultado.

Cumple con las características de un algoritmo.
El proceso es claro, finito y preciso. Se definen pasos específicos (sumar y mostrar el resultado), lo que lo convierte en un algoritmo.

3) Un conjunto de pasos para calcular el área de un rectángulo dado su base y altura.

Cumple con las características de un algoritmo.
Es un proceso finito, definido y con un resultado claro. Se especifican los datos de entrada (base y altura) y la operación necesaria para obtener el área.

4) El algoritmo cuenta el número de votos obtenidos por cada uno de los candidatos de una elección para presidente. Empieza solicitando el nombre del candidato y finaliza cuando se ingresa el valor -1.

Cumple con las características de un algoritmo.
El algoritmo tiene un inicio claro, sigue pasos bien definidos y termina al recibir un valor de parada (-1), asegurando finitud y precisión.

# Parte 4: Comprensión de Herramientas.

1) El pseudocódigo utiliza símbolos estándar para representar las operaciones lógicas.

Falso.
El pseudocódigo se basa en descripciones textuales claras y estructuradas, sin utilizar símbolos gráficos estandarizados (a diferencia de los diagramas de flujo).

2) Los diagramas de flujo son una representación gráfica de un algoritmo.

Cierto.
Los diagramas de flujo usan símbolos estandarizados (óvalos, rectángulos, rombos, etc.) y flechas para representar visualmente el flujo de un algoritmo.

3) El pseudocódigo debe estar escrito en un lenguaje de programación específico.

Falso.
El pseudocódigo es independiente de cualquier lenguaje de programación. Se utiliza para describir algoritmos de manera clara y sencilla, sin preocuparse por el lenguaje.

4) Un diagrama de flujo siempre debe tener un inicio y un fin claramente definidos.

Cierto.
Todo diagrama de flujo debe tener un punto de inicio y otro de fin para representar adecuadamente el flujo completo del algoritmo y asegurar su finitud.

# Parte 5: Estructuras de Control.

1) ¿Para qué sirven las estructuras de control?

Las estructuras de control permiten definir el flujo de ejecución de un algoritmo o programa. Determinan cómo y cuándo se ejecutan ciertas instrucciones, permitiendo la toma de decisiones, la repetición de procesos y la organización lógica del código.

## Ejemplo 1 (vida diaria).

Que ropa usar según el clima
Inicio
    Si está soleado
        Usa ropa comoda y protectora contra los rayos del sol
    Sino 
        si hace frío
            usa abrigo
        Sino
            si llueve
                usa impermeable y paraguas
    fin si
Fin

## Ejemplo 2 (calculos)

Saber si un estudiante aprueba una materia
Inicio
Si (promedio_final >= 3.0)  
    Entonces mostrar "Aprobado"  
Sino  
    Mostrar "Reprobado" 
Fin 


