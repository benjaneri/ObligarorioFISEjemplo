**Título:** Ingresar un gasto

**Actor:** Usuario del sistema

| Acción de los actores      | Respuesta del sistema |
| :--- | :--- |
| Selecciona 'Ingresar gasto'      | Muestra distintas opciones de acciones realizar       |
| Selecciona una divisa de la lista   | Muestras las distintas divisas        |
| Ingresa monto   | Muestra un campo numérico donde poder ingresar el monto|
| Selecciona categoría de gasto  de la lista| Muestra una lista con categorías preseleccionadas |
|Confirma datos ingresados, hora y día| Confirma mostrando datos del ingreso |

**Cursos alternativos:**

3.1 El usuario ingresa texto en el campo de monto:  se emite mensaje *"ERROR: debe ingresar solamente la cantidad del monto. No especifique la divisa."*


<br>

***

<br>


**Título:** Editar un gasto

**Actor:** Usuario del sistema

| Acción de los actores      | Respuesta del sistema |
| :--- | :--- |
| Selecciona 'Editar gasto'| Muestra distintas opciones de acciones a realizar       |
| Selecciona gasto de la lista      | Muestra una lista con los gastos ya ingresados        |
| Ingresa datos correctos| Muestra los datos asociados al gasto seleccionado
| Confirma datos        | Confirma mostrando nuevos datos de ingreso


**Cursos alternativos:**

3.1 El usuario ingresa texto en el campo de monto:  se emite mensaje *"ERROR: debe ingresar solamente la cantidad del monto. No especifique la divisa."*

<br>

***

<br>

**Título:** Eliminar un gasto

**Actor:** Usuario del sistema

| Acción de los actores      | Respuesta del sistema |
| :--- | :--- |
| Selecciona 'Eliminar gasto'| Muestra distintas opciones de acciones a realizar       |
| Selecciona gasto de la lista      | Muestra una lista con los gastos ya ingresados        |
| Confirma eliminación        | Confirma notificando de lo que implica la eliminación de un gasto


**Cursos alternativos:**

1.1 El usuario selecciona 'Eliminar gasto' no habiendo ingresado uno anteriormente:  se emite mensaje *"ERROR: primero asegúrese de haber ingresado un gasto."*

<br>

***

<br>

**Título:** Visualizar historial de gastos

**Actor:** Usuario del sistema


| Acción de los actores      | Respuesta del sistema |
| :--- | :--- |
| Selecciona 'Ver Historial'.      | Muestra un listado con todos los gastos realizados. |
| Selecciona 'filtrar'.   | Muestra las opciones para filtrar (fecha o categoría). |
| Selecciona una opción.  | Muestra el resultado del filtrado. |

**Cursos alternativos:** 

2.1 Podría ser que no tenga gastos según ese filtro, el sistema le muestra *"No se realizaron gastos".*

<br>

***


<br>

**Título:** Crear usuario en el sistema

**Actor:** Usuario del sistema

| Acción de los actores | Respuesta del sistema |
| :--- | :--- |
| Selecciona "Crear usuario"| Muestra distintos campos a completar |
| Completa los campos | Valida la información ingresada|
| Confirma los datos | Crea usuario|

**Cursos alternativos:**

3.1 Al confirmar, el sistema nota la creación de un usuario repetido. Se muestra el mensaje: *"ERROR: este usuario ya existe"*.

<br>

***

<br>

**Título:** Crear presupuesto mensual

**Actor:** Usuario del sistema

| Acción de los actores | Respuesta del sistema |
| :--- | :--- |
| Selecciona 'Crear presupuesto'| Muestra los campos a completar |
| Ingresa preferencias de ahorro y confirma | Le asigna el presupuesto al usuario |


**Cursos alternativos:**

2.1 Al agregar un nuevo presupuesto, existe uno asignado al mismo mes. El sistema muestra mensaje: *"¿Desea reemplazar?"*. 