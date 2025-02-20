# Ejercicios

1) solicitar al usuario 2 numeros enteros, imprimir en pantalla los numeros pares comprendidos entre ellos.

```
Inicio
Escribir "ingrese un numero entero: "
leer N1
Escribir "ingrese un numero entero: "
leer N2
si N1 < N2:
    mayor = N2
    menor = N1
si no
    mayor = N1
    menor = N2
fin si
mientras menor <= mayor:
    si residuo(menor, 2) = 0
        escribir residuo
    fin si
    menor = menor + 1
Fin
```

2) Serie de fibonacci

0 1 1 2 3 5 8 13 21 34 55...

```
Inicio
Escribir "¿cuantós números de la serie imprimir?
Leer N
cont = 0
N1 = 0
N2 = 1
escribir N1
mientras cont <= N
    N3 = N1 + N2
        escribir N3
    N1 = N2
    N2 = N3
    cont = cont + 1
Fin
```


    