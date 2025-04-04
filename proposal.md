# Propuesta TP DSW

## Grupo
### Integrantes
* 48096 - Ruiz Aldea, Bautista
* 48011 - Gonzalez del Cerro, Iñaki
* 48813 - Ricobelli, Tomas

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Software para gestión de gastos compartidos
### Descripción
*Esta aplicación permite a los usuarios registrar y dividir gastos dentro de un grupo de manera eficiente y equitativa. Los integrantes pueden agregar sus gastos, visualizar deudas y saldar montos a través de transferencias dentro de la plataforma. Nuestra app ofrece a su vez un historial detallado con los montos y motivos de cada gasto, brindando un control organizado de las finanzas compartidas para el día a día.*

### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Grupo<br>3. CRUD Gasto|
|CRUD dependiente|1. CRUD Categoria de Gasto {depende de} CRUD Tipo Usuario<br>2. CRUD Recordatorio de Pago {depende de} CRUD Gasto|
|Listado<br>+<br>detalle| 1. Listado de balances filtrado por grupo,periodo de tiempo,estado de deuda,usuario,categoria => detalle ...<br> 2. Listado de Análisis de Gastos filtrado por periodo,grupo,categoria,tipo de gasto,vista,pagador => detalle ...|
|CUU/Epic|1. Simplificacion de Deudas<br>2. Analisis de Gastos y reportes personalizados|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD|1. CRUD Usuario<br>2. CRUD Grupo<br>3. CRUD Gasto<br>4. CRUD Liquidácion<br>5. CRUD Categoria de Gasto<br>6. CRUD Recordatorio de Pago<br>|
|CUU/Epic|1. Simplificacion de Deudas<br>2. Analisis de Gastos y reportes personalizados|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

