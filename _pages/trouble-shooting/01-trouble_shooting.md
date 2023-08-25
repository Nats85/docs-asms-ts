---
title: Troubleshooting
chapter: "trouble_shooting"
---

<iframe
  src="https://codepen.io/team/codepen/embed/preview/PNaGbb](https://aes-supporchart-node.azurewebsites.net/"
  style="width:100%; height:300px;"
></iframe>


## 9.3.6.15: 

Se solucionan los siguientes problemas:

- Error Creación del caso cuando iniciaba desde el cliente.  

- Error al guardar servicio. "Proyecto - modelo".

- Error que permitía que modelos inactivos aparecieran seleccionables en la creación de la tarea.

- Error que muestra en la ventana de casos abiertos los casos con * así no se les hayan hecho modificaciones.

<br>

## 9.3.5.17:

Navegación en general de la consola:

- Se incluye cache de un minuto para los settings por proyecto.

Mejora en desempeño para la creación, edición y vista previa del caso:

- Se optimiza consulta para completar el contexto de los campos en el caso.

- Se incluye índice para campos adicionales.

Se solucionan los siguientes problemas:

- PM-29315-19-200795: Error que no permitía exportación de casos en consola de usuarios.

- PM-29490-19-200803: Error que no permitía exportación de CIs.

- PM-29488-19-200802: Error que mostraba servicios en operación en consola de usuarios.

- PM-29518-19-200805: Error que no permitía cargar la plantilla de proyectos cuando se llena el TAB ServiceSLAs.

Compatible con common 9.6.3.3

<br>

## 9.3.5.12: 

- Se soluciona error que no permitía crear artículos desde la consola de especialistas cuando el especialista no pertenecía a ningún grupo de especialista.  

- Se incluyo regla de negocio que valida si el especialista no está asignado a algún grupo de especialistas y si es así, se mostrará el componente para seleccionar el grupo de especialistas y el especialista. 

- Se soluciona problema que permitía que se editara un artículo desde la consola de especialistas, después de creado o desde la lista de relaciones 

<br>

## 9.3.5.9: 

- Se incluye cambio que muestra el proyecto que se tiene en la sesión así la URL de la consola de especialistas no lo lleve incluido. 

- Se modifica la ventana de creación de artículos cuando se invoca desde la consola de especialistas para que no muestre los campos Estado, razón, grupo de especialistas, especialista y Pública para el artículo. Si el artículo, según el tipo, solo tiene un estado inicial, el componente de estado se mantendrá oculto, si llega a tener más de un estado se mostrará el componente para que el especialista lo seleccione. 

- El grupo de especialista será seleccionado con el primer grupo al que pertenezca el especialista que está creando el artículo. 

- Se soluciona error que ocasionaba que el artículo se visualizara en la consola de especialistas para las opciones de "Artículos más consultados y Nuevos" así el estado en el que estuviera no tuviera la marca de publicado. 

- Se incluye cambio que oculta la opción para lanzar la consola de administración desde la consola de especialistas siempre y cuando el especialista autenticado no tenga el rol "Administrator Role" o el permiso "Administrator_Console". 

<br>

## 9.3.4.31: 

- Se remedia vulnerabilidad que ocasiona que al colocar un valor por fuera de rango para el vencimiento de sesión por inactividad ocasionaba que no se pudieran autenticar en las consolas arrojando un error que indica que el usuario no tiene asociado proyectos. Lo que se hizo es limitar el valor para que el mínimo valor sea 20 minutos y el máximo sea 1440 minutos (24 horas) 

<br>

## 9.3.4.30: 

- Solución el error de Multiidioma: Se evidenció que las traducciones para las consolas de especialistas y clientes no habían quedado en su totalidad en el idioma portugués. 

- Solución el Error asignación de cronómetros a los casos en determinada categoría y servicio: Se solucionó el problema y los nuevos casos creados quedarán con sus respectivos cronómetros asignados.  

- Solución el Error al editar datos adicionales en importación de Cis: Esta situación se presentaba cuando se crean campos adicionales después de tener un CI creado o por una importación de Cis que fue interrumpida por TimeOUT. 

- Solución el Error de traducción en estados en la consola especialistas: Este error se debe a que el cache para los estados estaba definido en 15 minutos; se procedió a bajarlo a 3 minutos y se está implementando la solución para invalidar cache en el momento que se realicen cambios desde la consola de administración. Esta solución será entregada próximos releases. 

<br>

## 9.3.4.26: 

- Consola de administración: Solución el error que no permitía la actualización de ubicaciones de servicios. 

<br>

## 9.3.4.25: 

- Consola de administración: Solución al error que no permitía clonar modelos si se tenía configurado cierre conforme. 

- Consola de especialistas / usuarios: Solución al error que no permitía que se cambiar el estado cuando se tenía configurado cierre conforme y se seleccionaba contrato al caso.  

<br>

## 9.3.4.19: 

PM-27903-19-200720: Problema para volver a incluir a los invitados a votar después de que el proceso se va por el camino de más información. 

PM-27736-19-200721: Los adjuntos no se visualizan para aprobaciones. 

<br>

## 9.3.4.17:  

- Se soluciona error con la importación de servicios básica  

- Se soluciona error al importar artículos cuando no hay campos adicionales configurados para el tipo de artículo. 


<br>

## 9.3.4.15: 

- Se realiza optimización a exportar e importar de servicios. 

<br>

## 9.3.4.14: 

- Se implementó cierre conforme para incidentes 

<br>


## 9.3.4.13: 

- Se realiza optimización para la obtención de datos al momento de exportar servicios. 

<br>


## 9.3.2.34: 

- Consola de usuarios: Se soluciona error que no permitía guardar los casos que pertenecían a servicios y categorías que en la configuración de la categoría tenía campos sin agregar, pero en el modelo estaban marcados como obligatorios. 

<br>

## 9.3.2.32: 

- Consola de especialistas / usuarios:  Se soluciona error que no permitía guardar los casos que pertenecían a servicios y categorías que en la configuración de la categoría tenía campos sin agregar pero en el modelo estaban marcados como obligatorios. 

<br>

## 9.3.2.31: 

- Consola de especialistas / usuarios: Se soluciona error que no permitía visualizar todos los campos de una categoría y un servicio al editar el caso en consola de especialistas. 

<br>

## 9.3.2.29: 

- Consola de administración: Modificación en la selección de campos adicionales para que el buscador no elimine el campo chequeado cuando se limpie la búsqueda y organización de los campos adicionales para que primero se vean los campos marcados como incluidos y exclusivos. 

- Modificación en el módulo de importaciones de compañías para el manejo de nulos y que se puedan asociar clientes a las compañías. 


<br>

## 9.3.2.28: 

- Consola de administración: Se soluciona problema que no permitía realizar el cambio de página en la opción servicios. 

- Optimización al momento de dar clic en los adicionales configurados por categoría para asociar o desasociar en el servicio. 

<br>

## 9.3.2.27: 

Consola de usuario: Ya no se consumen licencias al autenticarse en la consola de cliente. 

<br>


## 9.3.2.26: 

- Se soluciona error que se tenía en las aprobaciones de cambios y requerimientos.  


<br>

## 9.3.2.25: 

- Consola de administración: Confirmación para dejar visibles y editables campos adicionales en todas las categorías del modelo al crear un nuevo campo (Corrección compilado 9.3.2.24). 

- Modificación visualización ancho vista de acuerdos en configuración de servicios, solo se muestra a una columna. 

- Consola de especialistas / usuarios: Corrección visualización campos adicionales en consola. 

<br>

## 9.3.2.24: 

- Consola de administración: Confirmación para dejar visibles y editables campos adicionales en todas las categorías del modelo al crear un nuevo campo 

- Actualización de Common a versión 9.6.3.3 para solucionar problema de autenticación con ADFS 

<br>


## 9.3.2.23: 

- Consola de administración: Modificación en la clonación de reglas por proyecto y modelo. Modificación en la asociación de usuarios a proyectos y servicios por sincronización LDAP. 

- Consola de especialistas / usuarios: Validación de solicitud de notas en los estados recurrentemente. 

<br>

## 9.3.2.22: 

- Consola de administración: Modificación de icono de la categoría. Edición campos adicionales por categoría en el servicio. Inclusión de buscador para categorías en el servicio. 

- Consola de especialistas / usuarios: Configuración Carrusel distinto entre Consola Especialista y Consola Cliente. Corrección clic en columnas sin título en rejilla que no permitía visualizar información. Workaround logout ADFS.   

 
<br>

## 9.3.2.21 

- Modificación de icono de la categoría. 

- Posibilidad de cambio de categorías por proyecto a transversales. 

<br>


## 9.3.2.14: 

- Error perdido de permisos. 

<br>

## 9.3.2.13: 

- Error al cargar plantilla de proyecto con categorías transversales 

<br>

## 9.3.2.12: 

- Error al clonar modelos. 

- Error al adjuntar archivos en consola de usuarios y especialistas cuando se tiene configurados varias instancias. 

- Error en el portal de usuario al visualizar las encuestas pendientes por diligenciar. 

 
