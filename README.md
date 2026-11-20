# Control de distribución de paquetes

**Asignatura:** UCOM250 ORGANIZACIÓN Y ARQUITECTURA DE COMPUTADORES

**Integrantes:** Valentina Andrade y Saskia Brito

**Año:** 2026

**Fecha:** 20 de noviembre de 2026
---

## Descripción

### Escenario
Una empresa de logística necesita procesar información sobre los paquetes que administra en un centro de distribución. Al comenzar la jornada, el sistema registra 45 paquetes asociados a una operación y 60 paquetes correspondientes a un segundo registro. El programa realiza sumas y restas para representar cálculos intermedios relacionados con cantidades procesadas y diferencias. Durante la ejecución, los resultados se almacenan en distintos registros y algunos de ellos son sobrescritos para continuar el procesamiento.

Al finalizar, el sistema evalúa una operación aritmética para determinar el estado de la distribución. Cuando el resultado es diferente de cero, se almacena el código 505, que identifica la finalización del procesamiento de paquetes; si el resultado es cero, se almacena cero. El estado se conserva en una ubicación específica de memoria que permite registrar el resultado final.

---
### Referencias utilizadas
1.-
