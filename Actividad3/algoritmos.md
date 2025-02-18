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





