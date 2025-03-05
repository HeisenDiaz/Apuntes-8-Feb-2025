# MICRO-PROCESADORES

- Es una máquina de estados de propósito general, cuando diseñamos máquinas de estados siempre cumplen una función específica

## 1. Evolución histórica

| Fecha |                           Evolución                            |
|:-----:|:--------------------------------------------------------------:|
|  1971 | (Intel 4004): 2300 transistores, 108 KHz.                      |
|  1972 | Microprocesador 8008: 8 bits                                   |
|  1973 | Micro procesador 8080: 500000 operaciones por segundo          |
|  1975 | Motorola lanza microprocesadores de bajo costo ($20 y $25 USD) |
|  1976 | Surgen las primeras microcomputadoras                          |

## 2. Componentes de un Microprocesador

UC = Unidad de Control (PC = Contador de programa)

ALU = Unidad aritmetico Logica (Tiene 2 entradas)

Y estos están comunicandose con MATRIZ DE REGISTROS

## 3. Set de instrucciones

- CISC (Complex Instructions set computer) :

>  🔑 La UC descompone las instrucciones en microinstrucciones que permiten ejecutar operaciones mucho mas complejas

- RISC (Reduced instruction set computer) :

>  🔑 La UC habilita directamente los pines necesarios para llevar a cabo una instrucción

## 4. Arquitecturas

- Von Neumann :

>  🔑 Von Neumann: Tanto la memoria de programa como la memoria de datos comparten almacenamiento por lo tanto usan el mismo bus. Se presentan caso de cuello de botella debido a esto

- Harvard :

>  🔑 El programa y los datos estan en diferentes espacios de memoria lo cual hace mas eficiente el rendimiento, pero exige el uso de 2 buses separados y dos chips de memoria

