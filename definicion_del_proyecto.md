# Proyecto para Arquitectura de Backend

## Objetivo
Desarrollar un sitio web donde las personas puedan visualizar en tiempo real el Índice UV, así como descargar los datos dentro de un rango de fechas seleccionado por el usuario.
El sistema recolectará los datos desde un dispositivo sensor ubicado en un punto estratégico. Estos datos serán almacenados en una base de datos, permitiendo su posterior consulta y descarga.

## Requerimientos del cliente

El sitio web debe adaptarse a cualquier dispositivo (computadoras, tablets, móviles).

La plataforma debe permitir la visualización en tiempo real de los datos, mostrando de forma continua el Índice UV, la temperatura y la humedad. Además, la información debe actualizarse automáticamente cada 10 minutos, sin necesidad de que el usuario tenga que recargar la página manualmente.

Para facilitar el análisis de los datos, el sistema debe permitir a los usuarios seleccionar un rango de fechas y descargar la información recopilada en diferentes formatos, como CSV (para su uso en Excel).

En cuanto a la infraestructura del backend y almacenamiento, el sistema debe contar con una API encargada de recuperar y procesar los datos del sensor. Además, la base de datos debe almacenar cada registro junto con su fecha y hora, garantizando un historial ordenado y accesible.


