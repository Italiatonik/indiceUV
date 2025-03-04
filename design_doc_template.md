# Titulo: Template de documento de diseño
---
## Overview: Problema a resolver
Actualmente, no existe un sistema accesible en línea que permita a los usuarios visualizar el Índice UV en tiempo real y descargar los datos históricos de medición. La falta de esta información puede dificultar la toma de decisiones en actividades al aire libre, especialmente en lugares donde la exposición prolongada al sol representa un riesgo.

Este proyecto busca solucionar este problema mediante un sistema en línea que recopila datos desde un dispositivo sensor, los almacena en una base de datos y los muestra en una interfaz web intuitiva, accesible desde cualquier dispositivo.


### Alcance(Scope)
Visualización en tiempo real del Índice UV, temperatura y humedad.
Descarga de datos en formatos CSV.
Base de datos centralizada para almacenar las mediciones.
Actualización automática de los datos cada 10 minutos.

#### Casos de uso
Descripción...
* Caso de uso 1
* Caso de uso 2
* ...

#### Out of Scope (casos de uso No Soportados)
Descripción...
* Caso de uso 1
* Caso de uso 2
* ...
---
## Arquitectura
Se utilizarán los siguientes diagramas para representar la arquitectura del sistema:
* Diagrama de arquitectura general (Cliente-Servidor).
* Diagrama UML de las interacciones entre usuario, API y base de datos.
* Diagrama de secuencia del proceso de consulta y descarga de datos.


### Diagramas
poner diagramas de secuencia, uml, etc

### Modelo de datos
Poner diseño de entidades, Jsons, tablas, diagramas entidad relación, etc..
| #  | Nombre            | Tipo      | Permite NULL | Predeterminado | Extra          |
|----|------------------|----------|-------------|--------------|---------------|
| 1  | id               | int(11)  | No          | Ninguna      | AUTO_INCREMENT |
| 2  | fecha            | date     | Sí          | NULL         |               |
| 3  | hora             | time     | Sí          | NULL         |               |
| 4  | indice_uv_int    | int(11)  | Sí          | NULL         |               |
| 5  | indice_uv_float  | float    | Sí          | NULL         |               |
| 6  | vout_330         | float    | Sí          | NULL         |               |
| 7  | temperatura      | float    | Sí          | NULL         |               |
| 8  | humedad          | float    | Sí          | NULL         |               |


---
## Limitaciones
Lista de limitaciones conocidas. Puede ser en formato de lista.
Ej.
* Llamadas del API tienen latencia X
* No se soporta mas de X llamadas por segundo
---
## Costo
Descripción/Análisis de costos
Ejemplo:
"Considerando N usuarios diarios, M llamadas a X servicio/baseDatos/etc"
* 1000 llamadas diarias a serverless functions. $XX.XX
* 1000 read/write units diarias a X Database on-demand. $XX.XX
Total: $xx.xx (al mes/dia/año)
