# ejercicios de pseudocodigo a python

1) Se requiere obtener la distancia entre dos puntos en el plano cartesiano.

```
import math

Y1 = int(input("ingrese Y1: "))
Y2 = int(input("ingrese Y2: "))
X1 = int(input("ingrese X1: "))
X2 = int(input("ingrese X2: "))
cateto1 = X2-X1
print(cateto1)
cateto2 = Y2-Y1
print(cateto2)
distancia = math.sqrt(cateto1*cateto1+cateto2*cateto2)
print(distancia)
```

2) Una modista, para realizar sus prendas de vestir, encarga las telas al extranjero.
Para cada pedido, tiene que proporcionar las medidas de la tela
en pulgadas, pero ella generalmente las tiene en metros.

```
medidas = int(input("ingrese las medidas de la tela: "))
pulgadas = 0.0254*medidas
print(f"las medidas de la tele son: {pulgadas}")
```

3) Se requiere determinar la hipotenusa de un triángulo rectángulo.

```
import math
cateto1 = int(input("ingrese cateto1: "))
cateto2 = int(input("ingrese cateto2: ")) 
hipotenusa = math.sqrt(cateto1*cateto1+cateto2*cateto2)
print(f"la hipotenusa del triangulo es: {hipotenusa}")
```

4) Se requiere determinar la edad actual de una persona basándose en su fecha de nacimiento. Además, es necesario establecer si la persona ya ha cumplido años en el año en curso, si aún no lo ha hecho, o si hoy es su cumpleaños, para celebrarlo. La fecha de nacimiento y la fecha actual estarán representadas mediante tres variables: día, mes y año.

```
año_actual = 2025
mes_actual = 2
dia_actual = 25
año = int(input("ingrese su año de nacimiento: "))
mes = int(input("ingrese su mes de nacimiento: "))
dia = int(input("ingrese su dia de nacimiento: "))
edad_años = año_actual - año
ya_cumplio_este_año = (mes < mes_actual) or (
    mes == mes_actual and dia <= dia_actual)
if ya_cumplio_este_año:
    print(f"ya cumplio este año")
else:
    edad_años -=1
hoy_cumple_años = (dia == dia_actual and mes == mes_actual)
if hoy_cumple_años:
    print("Feliz Cumpleaños")
print(f"su edad es {edad_años} años")
```
5) Realice un algoritmo que permita determinar el sueldo semanal de un trabajador con base en las horas trabajadas y el pago por hora, considerando que a partir de la hora número 41 y hasta la 45, cada hora se le paga el doble, de la hora 46 a la 50, el triple, y que trabajar
más de 50 horas no está permitido.

```
pago_hora = int(input("ingrese el pago por hora: "))
horas_trabajadas = int(input("ingrese las horas trabajadas: "))
if horas_trabajadas < 41:
    horas_trabajadas = horas_trabajadas*pago_hora
elif horas_trabajadas < 46:
    horas_trabajadas = 2*horas_trabajadas*pago_hora
elif horas_trabajadas < 51:
    horas_trabajadas = 3*horas_trabajadas*pago_hora
else:
    print("no permitido trabajar mas de 50 horas")
    
print(f"el sueldo semanal es de: {horas_trabajadas}")
```


