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

>  🔑 UC = Unidad de Control (PC = Contador de programa)

>  🔑 ALU = Unidad aritmetico Logica (Tiene 2 entradas)

Y estos están comunicandose con MATRIZ DE REGISTROS

## 3. Set de instrucciones

>  🔑 CISC (Complex Instructions set computer): La UC descompone las instrucciones en microinstrucciones que permiten ejecutar operaciones mucho mas complejas

>  🔑 RISC (Reduced instruction set computer): La UC habilita directamente los pines necesarios para llevar a cabo una instrucción

## 4. Arquitecturas

>  🔑 Von Neumann: Tanto la memoria de programa como la memoria de datos comparten almacenamiento por lo tanto usan el mismo bus. Se presentan caso de cuello de botella debido a esto

>  🔑 Harvard: El programa y los datos estan en diferentes espacios de memoria lo cual hace mas eficiente el rendimiento, pero exige el uso de 2 buses separados y dos chips de memoria

## 5. Memoria 

- Volatil
  - RAM
    - SRAM
    - DRAM
      
- No Volatil
  - ROM (Read Only Memory)
  - PROM (Solo una programación)
  - EPROM
  - EEPROM
  - Flash (Estados Solidos (USB))
  - NVRAM

## 6. Características de un Microprocesador

- Reloj
- Tamaño del Bus de datos
- Tamaño del Bus de instrucciones
- Set de instrucciones
- Entradas y Salidas
- Memoria de Programa

## 7. MICROCONTROLADOR

>  🔑 Definición: El microcontrolador es una pequeña computadora usada para aplicaciones especificas, esto quiere decir que el microcontrolador 
debe incluir ciertas unidades fundamentales y comunes en cualquier computadora, estas unidades son:<br/> - CPU<br/> - MEMORIA RAM<br/> - MEMORIA ROM<br/> - ENTRADAS Y SALIDAS<br/>

  ### 7.1 Clasificación
  
  Se clasifican de acuerdo a la longitud de palabra desde los: 
  
  - 4bits
  - 8bits
  - 16bits
  - 32bits

## 8. Diagrama lógico 

- Un microcontrolador integra diferentes dispositivos en un solo circuito integrado
- En este se encuentra la Unidad Central, Memoria ROM, Memoria RAM, los cuales estan en comunicación bidireccional con los circuitos de interfaz y a su vez con el exterior.

  ### 8.1 Características

  - Tamaño en memoria
  - Tamaño de bus
  - Módulos
  - Familia
  - Encapsulado

## 9. Aplicaciones

  - Robótica:
    - Subsistemas específicos de control
      - Extremidades
      - Facciones del rostro
      - Soportes prensiles

  - Equipamiento informático:
    - Impresoras
    - Scanners
    - Copiadoras
    - Sistemas portátiles y autónomos
      
  - Sector automotriz:
    - Control centralizado de puertas y ventanas
    - Climatizadores
    - Inyección
    - Alarmas
      
  - Sector doméstico:
    - Integrado en los sistemas de:
      - Televisores
      - Lavarropas
      - Microondas
      - Heladeras
        
  - Sector industrial:
    - Controladores industriales
    - Automatización

## 10. Familias, gamas, modelos 

| Fabricante |  Familia |
|:----------:|:--------:|
|  Motorola  | Frescale |
|  Microchip |    PIC   |
|   Hitachi  |    H8    |
|    Atmel   |    AVR   |
|    Texas   |   Texas  |
|    Intel   |    MSC   |

## 11. Conclusiones

- Aprendimos que los microprocesadores han avanzado desde el Intel 4004 hasta modelos más potentes y accesibles, impulsando la informática moderna
- Identificamos los 2 tipos de arquitecturas usadas en los micro-procesadores
- Analizamos la identificación de los microprocesadores de acuerdo a la cantidad de bits




      

