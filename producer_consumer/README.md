

# Problema del productor-consumidor con un buffer de tamaño 1

Problema del productor consumidor con un buffer de tamaño 1. El problema solo funciona con un solo productor

## Pruebas


|#|Producers|Consumers|Loops|Observaciones|
|---|---|---|---|---|
|1|1|1|20|Funciona|
|2|1|2|20|Funciona|
|3|2|1|20|No funciona con varios productores|

**Preguntas**:
1. ¿Que pasa cuando el numero de datos a meter es pequeño y hay varios consumidores?
2. ¿Por que a veces hay consumidores que parece que no se ejecutan?
