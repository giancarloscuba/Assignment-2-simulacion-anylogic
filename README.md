# Proyecto de Simulación Discreta - AnyLogic

## Descripción

Proyecto académico de simulación discreta desarrollado en AnyLogic 8.9.9.

El modelo representa un sistema de atención de clientes en una agencia bancaria, considerando la llegada de clientes, espera en cola, atención mediante cajeros y salida del sistema.

## Escenarios

Se analizaron dos escenarios:

- Escenario 1: 1 cajero.
- Escenario 2: 2 cajeros.

## Parámetros principales

- Tasa de llegada: 0.5 clientes/minuto.
- Tiempo de atención: triangular(2,4,6) minutos.
- Tiempo de simulación: 100 minutos.
- Réplicas: 30 por escenario.

## Resultados observados

### 1 cajero

- Clientes que llegaron: 41
- Clientes que salieron: 24
- Clientes en cola: 16
- Utilización: 99 %
- Clientes pendientes: 17

### 2 cajeros

- Clientes que llegaron: 43
- Clientes que salieron: 38
- Clientes en cola: 3
- Utilización: 80 %
- Clientes pendientes: 5

## Comparación

El escenario con 2 cajeros permitió finalizar la atención de una mayor cantidad de clientes durante la ejecución observada y presentó una menor cantidad de clientes en cola al finalizar la simulación.

## Software

AnyLogic 8.9.9

## Archivo del modelo

El archivo `.alp` incluido en este repositorio corresponde al modelo desarrollado para el proyecto.
