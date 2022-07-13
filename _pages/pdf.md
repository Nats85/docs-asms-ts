---
title: Release Notes Aranda SERVICE MANAGEMENT ASMS
permalink: /pdf
---

Conoce las últimas liberaciones de Aranda SERVICE MANAGEMENT ASMS.

 Aquí podras acceder a las más recientes actualizaciones de las funcionalidades de ASMS.

## Artículos Visualización
---
title: Artículos Visualización
chapter: "9.2.2.4"
---

## CASO PM-24361:

Se soluciona inconsistencia en el portal de usuarios (ASMSCustomer) para el concepto artículos,
actualmente solo se visualizan los artículos que se encuentran en un estado publicado y tienen la opción
pública habilitada sobre el artículo.

## Asignar ícono y Descripción a Grupos

## CASO CH-23501

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite asignar un Ícono y descripción a los grupos de clientes creados y de esta manera identificar desde la consola de especialista los clientes con características especiales. 

[Ver Grupos de clientes](https://docs.arandasoft.com/asms-admin/pages/02-empresa/07-Grupos.html)


## Descarga Masiva de Archivos Adjuntos

### CASO CH-23800:

Se implementa nueva funcionalidad en la consola de especialista (ASMSSpecialist) la cual permite realizar la descarga masiva de archivos adjuntos. 


[Ver Descarga Masiva de Archivos Adjuntos](https://docs.arandasoft.com/asms-specialist/pages/02-consola/02-Vistas%20por%20defecto.html)
## Cambio Masivo en Propiedades Comunes

## CASO CH-23798:

Se implementa nueva funcionalidad en la consola de especialista (**ASMSSpecialist**) la cual permite realizar cambios masivos de las propiedades comunes del caso: 


[Ver Cambios Masivos en propiedades comunes](https://docs.arandasoft.com/asms-specialist/pages/02-consola/02-Vistas%20por%20defecto.html)
## Exportación de Información con Datos para creación y actualización de Usuarios

## CASO CH-23498, CH-23499:

Se realiza un ajuste en el formato de exportación de usuarios (clientes, especialistas), ahora se incluyen los campos adicionales y es posible exportar la información con datos o sin datos para la actualización y/o creación de usuarios. 



[Ver Exportar Formato](https://docs.arandasoft.com/asms-admin/pages/02-empresa/06-Usuarios.html)
## Asociación/Desasociación Masiva de Usuarios

## CASO CH-23500:

Se implemente nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite realizar asociación y des asociación masiva de usuarios (clientes y especialista) a proyectos. 


[Ver Asociación Masiva de Usuarios](https://docs.arandasoft.com/asms-admin/pages/09-cargas%20masivas/01-Asociar%20Usuarios%20a%20Proyectos.html)
## Carga Masiva en Módulo CMDB

## CASO CH-21585: 

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite realizar la carga masiva de diferentes conceptos para el módulo de CMDB. 

[Ver Carga masiva de Datos de CMDB](https://docs.arandasoft.com/asms-admin/pages/09-cargas%20masivas/02-Carga%20Masiva%20de%20CMDB.html)
## Asociar Modelos a Categorías en Importación de Proyectos

## CASO CH-21829:

Se realiza un ajuste en la plantilla de importación de proyectos, ahora es posible asociar los modelos directamente a las categorías. 

<span>1.</span> Haga la apertura del archivo **ProjectFormat.xls** y ubíquese sobre la pestaña **ServiceCategories**. 

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.2.4/048.jpg"></center>

<br>


<span>2.</span> En las columnas **EnableIncidents, EnableServicall, EnableChange** etc. defina el nombre del modelo que va a tener cada una de las categorías. 

**Nota**: El modelo debe estar previamente asociado al servicio en la pestaña **Services** y no se deben incluir modelos que no estén habilitados en el servicio. 
## Carga Masiva de Casos

## CASO CH-23797:

Se implementa nueva funcionalidad en la consola de administración (**ASMSAdministrator**) la cual permite realizar carga masiva de casos. 

[Ver Carga masiva de Casos](https://docs.arandasoft.com/asms-admin/pages/09-cargas%20masivas/03.Cargas%20Masivas%20por%20Tipo%20de%20Caso.html)
## Página de Votación

## CASO CH-7247

Se realiza un ajuste sobre la página de votación, ahora se incluye el grupo responsable y responsable del caso.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.3.8/002.jpg"></center>

<br>

## creación y/o actualización masiva de ubicaciones


## CASO CH-23760:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y/o actualización masiva de ubicaciones. 

[Ver creación y/o actualización masiva de ubicaciones](https://docs.arandasoft.com/asms-admin/pages/02-empresa/06-Ubicaciones.html)
## Creación y/o Actualización Masiva de Ubicaciones

## CASO CH-7635

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite realizar actualización masiva de CI’s.

[Ver Actualización Masiva de Cis](https://docs.arandasoft.com/asms-admin/pages/07-cmdb/17-CIs.html)
## Asociar LDAPs por Proyecto

## CASO CH-24339

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite asociar LDAP’s por proyecto.

[Ver Asociar Ldaps por Proyecto](https://docs.arandasoft.com/asms-admin/pages/01-general/02-Proyectos.html)
## Asociación Masiva de Servicios

## CASO CH-24521

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite realizar asociación masiva de servicios a usuarios a través de la sincronización por LDAP.

[Ver Asociación MAsiva de Servicios a traves de sincronización LDAP](https://docs.arandasoft.com/asms-admin/pages/01-general/07-LDAP.html)
## Comportamiento Agendado para los estados en ASDK

## CASO CH-23796:

Se realiza implementación del comportamiento Agendado para los estados en Aranda SERVICE DESK ASDK, cuya acción es devolver al estado anterior el caso una vez se cumpla la fecha agendada al ingresar a ese estado a menos que el caso cambie de estado antes de la fecha agendada. El comportamiento tiene las siguientes características:

**Consola Administración**

- Aplica para los estados diferentes a inicial, final y cuyo estado anterior no sea inicial.

- Se pueden configurar dos estados consecutivos con el comportamiento Agendado, pero en consola especialista se realizará la validación que el estado anterior no tenga el comportamiento Agendado, de ser así, se omite la configuración de comportamiento para el nuevo estado.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.3.8/032.jpg"></center>

<br>

**Consola Especialista**

- Al ingresar a un estado cuyo comportamiento este configurado como **Agendado,** se visualizará un nuevo campo en la sección **Información Básica** el cual es obligatorio para guardar el cambio de estado**,** el cual solicita la fecha límite en la que el caso debe cambiar de estado antes de volver al estado anterior.

- Si se cambia de estado antes de que se cumpla la fecha agendada para el caso, ya no se tendrá en cuenta el agendamiento realizado.

- Si se cumple la fecha de agendamiento y el caso no ha cambiado de estado, el caso se devuelve al estado anterior sin modificar ningún otro campo, registrando en el historial el cambio de estado.



## Configurar Calendario por Rangos de Tiempo

## CASO CH-23501:

Se realiza un ajuste en la consola de administración (ASMSAdministrator) el cual permite configurar un calendario por los siguientes rangos de tiempo: 1 minuto, 15 minutos, 30 minutos y 60 minutos.

[Ver Configurar Calendarios por rango de tiempo](https://docs.arandasoft.com/asms-admin/pages/01-general/15-Calendarios.html)
## Actualización Automática al Asociar Ubicación

## CASO CH-24338:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) para que, al realizar la asociación de la ubicación en los datos del Cliente, esta información se actualice de manera automática en la pestaña de dirección del usuario seleccionado.

[Ver Asociación de Ubicación en datos del cliente](https://docs.arandasoft.com/asms-admin/pages/02-empresa/06-Usuarios.htmll)
## Cálculo Automático para Ubicación del Cliente

## CASO CH-23801

Se implementa nuevo ajuste en la consola de especialista (ASMSSpecialist), ahora al seleccionar cliente, compañía y/o CI se calcula de manera automática el campo ubicación con el valor que tiene asociado el primer concepto que se seleccionó en la creación del caso.

<span>1.</span> En consola de especialista haga clic en el botón **Crear caso**.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.3.8/050.jpg"></center>

<br>

<span>2.</span> Seleccione el proyecto, tipo, servicio y categoría.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.3.8/051.jpg"></center>

<br>

<span>3.</span>  Al asociar un cliente al caso, se calcula de manera automática la ubicación del cliente.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.3.8/052.jpg"></center>

<br>

**Nota**

- la ubicación solo es calculada la primera vez de acuerdo al primer concepto (cliente, compañía
CI) que se seleccione en el formulario de creación del caso.
- Si la ubicación fue calculada por cliente y el especialista cambia manualmente la ubicación del caso, se visualizará el siguiente mensaje:

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.2.3.8/053.jpg"></center>

<br>

<span>4.</span> Si el especialista hace clic en botón **Si** entonces se actualiza la ubicación del cliente por la seleccionada manualmente..


<br>
## Creación y Actualización Masiva de Calendarios

## CASO CH-24443:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y actualización masiva de calendarios.

[Ver Creación y Actualización MAsiva de Calendarios](https://docs.arandasoft.com/asms-admin/pages/01-general/15-Calendarios.html)
## Creación y Actualización Masiva de Estados

## CASO CH-24454:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y actualización masiva de estados para cada uno de los conceptos (Finanzas, Service Desk, Catalogo y portafolio de servicios, CMDB, Base de conocimiento y Eventos).

[Ver Creación y Actualización Masiva de Estados Service desk](https://docs.arandasoft.com/asms-admin/pages/04-sd/04-Estados.html)
## Importación Masiva de Proyectos


## CASO CH-24445:

Se realiza un ajuste en el archivo de importación masiva de proyectos, ahora es posible adicionar las alertas de vencimiento y revisión de los ANS.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.3.0.11/017.jpg"></center>

<br>
## Enviar Correo a grupo de Especialistas


## CASO CH-24831:

Se implementa nueva opción en la acción **Enviar correo electrónico** en reglas, ahora es posible enviar correo electrónico al grupo de especialista asignado al caso.

[Ver Enviar correo electrónico en reglas](https://docs.arandasoft.com/asms-admin/pages/04-sd/13-Reglas.html)
## Selección Masiva de Campos Adicionales

## CASO CH-24920:

Se realiza un ajuste en la consola de administración (ASMSAdministrator), ahora es posible seleccionar y deseleccionar de manera masiva los campos adicionales y tiempos en la edición de las categorías.

[Ver Seleccionar y deseleccionar de forma masiva campos adicionales](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/11-Servicios.html)
## Creación y Actualización Masiva de Campos Adicionales

## CASO CH-24456:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y actualización masiva de campos adicionales para cada uno de los conceptos (Configuración de la empresa, Finanzas, Service Desk, Catalogo y portafolio de servicios, CMDB, Base de conocimiento y Eventos).

[Ver creación y actualizacion masiva campos adicionales/Configuración Empresa](https://docs.arandasoft.com/asms-admin/pages/02-empresa/03-Adicionales.html)

[Ver creación y actualizacion masiva campos adicionales/Finanzas](https://docs.arandasoft.com/asms-admin/pages/03-finanzas/04-Adicionales.html )

[Ver creación y actualizacion masiva campos adicionales/service desk](https://docs.arandasoft.com/asms-admin/pages/04-sd/07-Adicionales.html )

[Ver creación y actualizacion masiva campos adicionales/Catálogo y Portafolio de Servicios](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/03-Campos%20Adicionales.html)

[Ver creación y actualizacion masiva campos adicionales/CMDB](https://docs.arandasoft.com/asms-admin/pages/07-cmdb/06-Campos%20Adicionales.html)

[Ver creación y actualizacion masiva campos adicionales/Base de Conocimiento](https://docs.arandasoft.com/asms-admin/pages/06-conocimiento/04-Adicionales.html)

[Ver creación y actualizacion masiva campos adicionales/Eventos](https://docs.arandasoft.com/asms-admin/pages/08-eventos/03-Adicionales.html)

## Asociación Masiva por Tipo de Usuarios

## CASO CH-24444:

Se realiza un ajuste en el archivo de importación masiva de usuarios, ahora es posible realizar la asociación masiva de los diferentes conceptos de acuerdo al tipo de usuario, para clientes existe la opción de asociar Servicios, Compañías y Grupos de clientes, para especialistas existe la opción de asociar Grupos de especialistas y Roles

[Ver Asociación Masiva por tipo de usuario](https://docs.arandasoft.com/asms-admin/pages/02-empresa/07-Usuarios.html)

## Asociación Masiva de Ubicaciones

## CASO CH-21872:

Se realiza un ajuste en el archivo de importación masiva de Usuarios, Compañías y CI’s, ahora es posible  realizar  la  asociación  masiva  de  ubicaciones  a  cada  uno  de  los  conceptos  anteriormente mencionados.

[Ver Importación Masiva de Usuarios](https://docs.arandasoft.com/asms-admin/pages/02-empresa/07-Usuarios.html)

[Ver Importación Masiva de Compañías](https://docs.arandasoft.com/asms-admin/pages/02-empresa/05-Compa%C3%B1ias.html)


## Creación Masiva de Contratos

## CASO CH-23790:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y actualización masiva de contratos para el módulo de Finanzas.

[Ver Creación y Actualización Masiva de Contratos](https://docs.arandasoft.com/asms-admin/pages/03-finanzas/06-Contratos.html)

## Creación y Actualización Masiva de Categorías

## CASO CH-24678:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y actualización masiva de categorías para el módulo de Catálogo y portafolio de servicios.

[Ver Creación y Actualización Masiva de Categorías](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/10-Categorias.html)

## Selección Categorías Hijas Activas

## CASO 24830:

Se implementa funcionalidad en la consola de especialista y en consola cliente (ASMSSpecialst y ASMSCustomer) la cual permite seleccionar en la creación o edición de un caso las categorías hijas activas.

[Ver Seleccionar Categorías Hijas Activas](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/11-Servicios.html)

## Clonación y Eliminación Masiva de Reglas

## CASO CH-24549:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible la clonación y eliminación masiva de reglas para el concepto Service Desk.

[Ver Clonación y eliminación masiva de reglas](https://docs.arandasoft.com/asms-admin/pages/04-sd/13-Reglas.html)

## Confirmación Cierre de Casos

## CASO CH-23802:

Se realiza implementación de funcionalidad para consola administración (ASMSAdministrator) y consola especialista (ASMSSpecialist), la cual consiste que al momento en el que realizó el cierre del último caso hijo se solicita confirmación para cerrar los casos padres.

[Ver Solicita Información al cierre de caso hijo](https://docs.arandasoft.com/asms-admin/pages/04-sd/04-Estados.html)

## Ingresar Nota Cambio de Estado

## CASO CH-24829:

Se realiza implementación de funcionalidad para consola administración (ASMSAdministrator) y consola especialista (ASMSSpecialist), la cual consiste que al momento en el que el caso ingresa al estado donde se configuro la nota obligatoria, se visualiza un modal para ingresar la nota de cambio de estado.

[Ver Nota obligatoria](https://docs.arandasoft.com/asms-admin/pages/04-sd/04-Estados.html)

## Separar Acceso para Grupo de Especialista

## CASO CH-24536:

Se implementa nueva funcionalidad en la consola de administración (ASMS Administrador) para separar el acceso para distinto grupo de especialista.


## Visualización de adjuntos en aprobaciones

## CASO PM-27736-19-200721:

Se realiza ajuste en la visualización de los un caso en estado de aprobación interna, ahora al ingresar a visualizar un caso en estado de aprobación interna los adjuntos del caso se tendrán el siguiente comportamiento:

1. Al visualizar el caso desde la consola especialista **(ASMSSpecialist)**, será posible la visualización y descarga de adjuntos existentes en el caso.
2. Al visualizar el caso desde el link de aprobación sera posible la visualización y descarga de adjuntos sin importar si el especialista tiene o no permisos para visualizar los adjuntos del tipo de caso.


## Agregar votantes en diferentes procesos de aprobación

## CASO PM-27903-19-200720:

Se realiza ajuste en la aprobación de casos, ahora es posible agregar un especialista al proceso de aprobación de un caso, sin importar las veces que el caso ingrese al proceso de aprobación interna.
## Mensaje recibido al case creator como adjunto del caso
---
title: Mensaje recibido al case creator como adjunto del caso
chapter: "9.3.2"
---

## CASO CH-25113:

Se realiza ajuste en la funcionalidad del **case creator**, ahora al momento en el que se crea un caso por medio del correo,
se adjunta el correo recibido como archivo en el caso, así mismo se agrega la nota en historial del adjunto.

Al crear un caso por **case creator** se adjuntará el archivo **email-attachment.eml** el cual se puede visualizar en cualquier
cliente de correo, al visualizar el adjunto este se visualizará del mismo modo en que se recibió el correo en el
servidor, incluyendo los archivos adjuntos que se envió el cliente en el correo.

En el historial del caso se adjunta la nota estándar por archivos adjuntos, indicando que el usuario ARANDA SERVICE USER
agregó el archivo adjunto **email-attachment.eml** al caso.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/001.png"></center>
## Asociación de clientes y servicios desde carga de compañías
---
title: Asociación de clientes y servicios desde carga de compañías
chapter: "9.3.2"
---

## CASO CH-25509:

Se realiza un ajuste en el archivo de importación masiva de compañías, ahora es posible realizar la asociación masiva
de servicios y clientes desde el archivo de compañías.

<span>1.</span> Haga la apertura del archivo **Company.xls** y ubíquese sobre la hoja **CompanyRelations**. 

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/002.png"></center>

<br>

<span>2.</span> En las columnas **Company, RelationType, Name, Provider e IsRelated** diligencie los datos para
asociar los clientes y/o servicios a las compañías.

**Provider**
Tenga en cuenta que esta columna solo aplica para la asociación de clientes, si al asociar un cliente se deja esta
columna vacia se toma por defecto el tipo de autenticación ARANDA.

Es posible crear relaciones a compañías ya creadas únicamente diligenciando la pestaña **CompanyRelations**, al igual
que es posible la creación de compañías y asociación de clientes y servicios en el mismo archivo.

Para eliminar relaciones existentes descargue el archivo **Company.xls** con datos y en la hoja **CompanyRelations**
cambie la columna **IsRelated** a 0 en el item que desea desasociar.

**Nota**: Los servicios y clientes deben estar asociados al proyecto donde se importe el archivo.
## LDAP’s por proyecto en Aranda Pass Recovery
---
title: LDAP’s por proyecto en Aranda Pass Recovery
chapter: "9.3.2"
---

## CASO CH-25051:

Se realiza un ajuste en Aranda Pass Recovery, ahora al hacer clic en ¿Olvido su contraseña? 
desde la consola de especialista (ASMSspecialist) o el portal de usuario (ASMSCustomer) navegando 
por la url del proyecto, se obtienen los LDAP’s asociados por proyecto.

**Precondiciones:**

Edite el archivo **Web.config** del sitio **APRAPI**.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_6.png"></center>

Busque la opción **ASMSAPI** y digite la url de la siguiente manera:

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_7.png"></center>

Reemplace **“localhost”** por el nombre o IP de su servidor de aplicaciones.

**Configuración**

Desde la consola de administración haga clic en **Configuración General / Ajustes.**

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_1.png"></center>

Seleccione la opción ASMS, Ubíquese sobre la opción UsersAPRURL e ingrese la url de Aranda Pass Recovery 
de la siguiente manera: **https://localhost/APRUsers/#!/login/**

Reemplace **“localhost”** por el nombre o IP de su servidor de aplicaciones.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_2.png"></center>

Asegúrese de tener LDAP’s asociados al proyecto.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_3.png"></center>

Navegue a la consola de cliente o especialista con la url del proyecto, seleccione autenticación 
por dominio y haga clic en la opción **¿Olvido su contraseña?.**

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_4.png"></center>

Al desplegar los dominios en Aranda Pass Recovery únicamente se visualizarán los dominios 
asociados al proyecto.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25051_5.png"></center>


## Hipervínculos en notas
---
title: Hipervínculos en notas
chapter: "9.3.2"
---

## CASO CH-25538:

	Se implementa nueva funcionalidad en consola de especialista (ASMSspecialist) y cliente 
(ASMScustomer), ahora es posible agregar hipervínculos en las notas.

En consola de especialista haga la edición de un caso y seleccione el botón para añadir una nota.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25538_1.png"></center>

Digite un hipervínculo y/o un texto, selecciónelo y haga clic en el botón **Insertar hipervínculo.**

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25538_2.png"></center>

En la opción **Dirección web** digite el hipervínculo, el **Titulo** y defina si desea abrir el enlace en 
una nueva pestaña. 

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25538_3.png"></center>

Haga clic en **Insertar** y posteriormente agregue la nota.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25538_4.png"></center>

Al ir al historial del caso se visualizará la nota agregada y desde allí podrá abrir el hipervínculo.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25538_5.png"></center>


## Base de conocimiento en especialista
---
title: Base de conocimiento en especialista
chapter: "9.3.2"
---

## CASO CH-24939:

Se implementa la sección de base de conocimiento en la consola especialista, en esta sección se visualizarán los 
artículos configurados en consola administración y que cumplan con la configuración.

**Consola administración**
Para que los artículos sean visibles en consola especialista, se tendrá en cuenta el check de publicado en **Base de
conocimiento / Estados**, los artículos que se encuentren en los estados donde se tenga habilitado el check de estados
se visualizarán en consola especialista.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_1.png"></center>

**Consola especialista**

La base de conocimiento de Aranda contiene artículos que brindan información útil relacionada con los servicios ofrecidos a los clientes.  

Para consultar los artículos publicados haga clic en **Base de conocimiento**.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_2.png"></center>

Aparecerá el listado de artículos disponibles. En el panel izquierdo puede filtrar los artículos por proyecto.  

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_3.png"></center>

También puede filtrar el listado por categorías o por **Artículos más consultados**, **Artículos mejor calificados** y **Artículos nuevos**.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_4.png"></center>

En las barras de la parte superior puede buscar artículos por palabras clave y tipo.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_5.png"></center>

En la esquina inferior derecha de la tarjeta de cada artículo hay tres iconos que le permiten ver los relacionados del artículo, enviarlo por correo y añadir el artículo a la lista de favoritos.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_6.png"></center>

En el panel derecho se observa el nombre de la persona responsable del artículo, la última fecha de modificación, la descripción y los archivos adjuntos publicos y privados. Puede ampliarlo haciendo clic en  ![]({{ site.baseurl }}/assets/images/9.3.2/CH24939_7.png).

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_8.png"></center>

Puede dar una calificación al artículo y agregar comentarios.  

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH24939_9.png"></center>



## Buscador de categorías
---
title: Buscador de categorías
chapter: "9.3.2"
---

## CASO CH-25045:

Se implementa funcionalidad para permitir la búsqueda de categorías en consolas administración (ASMSAdministrator) y 
especialista (ASMSSpecialist), para complementar la vista actual tipo árbol.

**Consola administración**
Haga clic en **Catálogo y Portafolio de servicios / categorías** se visualizarán dos íconos los cuales son para 
seleccionar la manera en la que se desean visualizar las categorías (por defecto vista árbol).

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25045_1.png"></center>

Al seleccionar la vista lista se visualizara un campo para realizar la búsqueda de las categorías, haga clic sobre 
el título **Categorías** para organizar los resultados de forma alfabética.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25045_2.png"></center>

**Consola especialista**
Al realizar la creación o edición de un caso, al momento de seleccionar la categoría se
visualizarán dos íconos los cuales son para seleccionar la manera en la que se desean 
visualizar las categorías (por defecto vista árbol).

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25045_3.png"></center>

Al seleccionar la vista lista se visualizara un campo para realizar la búsqueda de las categorías,
en esta vista solo se listaran las categorías activas en el servicio.

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25045_4.png"></center>


## Cambios masivos grupo responsable
---
title: Cambios masivos grupo responsable
chapter: "9.3.2"
---

## CASO CH-26134:

Se realiza ajuste en la funcionalidad del **cambios masivos** en consola especialista, ahora al momento en el que se desea
realizar un cambio masivo se visualizará el campo para seleccionar el grupo responsable.


<span>1.</span>  Desde la consola de especialista ubíquese sobre el modo de visualización rejilla y/o tarjeta, marque la casilla de verificación para diferentes casos y haga clic en **Opciones del caso.** 

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH25538_5.png"></center>

<br>


<span>2.</span> Al seleccionar la opción **Cambios masivos** se habilitará la siguiente ventana.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH26134_1.png"></center>

<br>

El campo Grupo Responsable puede estar deshabilitado por las siguientes causas: 

- Cuando selecciono dos o más casos que no tienen grupos en común.

<span>3.</span> Al seleccionar dos o más casos que tienen grupos en común, al seleccionar el grupo responsable solo se listaran los grupos que tengan en común.

<br>

<center><img src="{{ site.baseurl }}/assets/images/9.3.2/CH26134_2.png"></center>

<br>

<span>4.</span> Los campos adicionales sólo se habilitarán cuando realice el cambio de estado.

<span>5.</span> Al seleccionar primero el responsable y luepo el grupo, el campo responsable quedará en seleccione.

<span>6.</span> Los campos adicionales sólo se habilitarán cuando se realice el cambio de estado.



## Archivo vacío
---
title: Archivo vacío
chapter: "9.3.2"
---

## CASO PM-26133:

Se soluciona inconsistencia en la consola de administración (ASMSAdministrator), ahora al ir a 
la opción **Cargas Masivas / Proyectos** ya no se genera un archivo en formato .txt vacío.

## Modificación campos filtro en el LDAP
---
title: Modificación campos filtro en el LDAP
chapter: 9.3.2
---

## CASO PM-25962

Se realiza ajuste de los campos de filtro en la pestaña de detalles del LDAP, se modifica la cantidad de caracteres
que aceptan los filtros.


## Actualización de ubicación de CI
---
title: Actualización de ubicación de CI
chapter: 9.3.2
---

## CASO PM-26132

Se realiza ajuste en la consola administración para permitir la modificación de la ubicación del CI, al modificar la
ubicación de un CI anteriormente se realiza correctamente.
## Edición de carpetas
---
title: Edición de carpetas
chapter: "9.3.2"
---
## CASO PM-26474-19-200613:
Se soluciona error al realizar la edición de la descirpción en las carpetas, ahora al editar la descripción de una carpeta, 
la descirpción se actualizara correctamente en la consola.
## Integridad información a través del API
---
title: Integridad información a través del API
chapter: 9.3.2
---

## CASO PM-25349

Se realiza ajuste de validaciones de regla de negocio para la creación y edición de casos a través del API.

Los ajustes realizados corresponden a los siguientes casos:

 - Creación y edición de casos:
    - Especialista autenticado asociado al proyecto.
    - Servicio, Categoría, Cliente, Compañía, CI, Ubicación, Contrato, Proveedor y Área organizacional asociados al proyecto.
    - Campos obligatorios según el estado.
    - Grupo de Especialistas asociado al proyecto y especialista asociado al grupo.
    - El modelo corresponde a la Categoría.
    - Campos adicionales deben corresponden al **modelo/Categoría**.
    - El especialista debe contar con permisos para la creación / edición del tipo de caso.

 - Listar o buscar casos:
    - El especialista autenticado asociado al proyecto.
    - El especialista autenticado debe contar con permisos para visualización de: **Mis casos** , **Mis grupos**, **Mis proyectos**.
    - El especialista autenticado debe contar con permisos para visualizar el tipo de caso.

 - Agregar, borrar, listar o descargar archivo
    - El especialista autenticado asociado al proyecto.
    - El especialista autenticado debe contar con permisos para visualizar el tipo de caso.
    - El especialista debe contar con permisos para la listar/descargar archivos.

 - Agregar nota
    - El especialista autenticado asociado al proyecto.
    - El especialista autenticado debe contar con permisos para editar el tipo de caso.
    - El especialista debe contar con permisos para la listar/descargar archivos.
## Campo solicitante

## CASO CH-24158:

Se crea el nuevo campo **Solicitante** el cual aplicará para los casos de la consola especialista (Requerimientos de servicio, Incidentes, Cambios, Problemas y Releases) y los mantenimientos.

### Consola administración

El campo **Solicitante** tendrá las mismas configuraciones disponibles para el campo cliente.

Para temas de configuración de etiquetas y visibilidad de campos de interfaz y campos adicionales se tomarán los mismos configurados para el cliente.

Para el tema de reglas se agrega el campo solicitante para la evaluación de condiciones, así como para el envío de correo electrónico.

### Consola especialista

El campo **Solicitante** contará con las siguientes características:

- Al realizar la búsqueda de solicitante no se tendrá en cuenta el filtro de servicios, esto significa que se podrá asociar cualquier cliente asociado al proyecto y que se encuentre activo.  

  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26158_3.png"></center>

- Se visualizará en la sección **Información de cliente**.

  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26158_1.png"></center>
  
- Contará con su propia sección de **Detalles** en donde se podrán visualizar los casos en los que el usuario se encuentra como solicitante.

  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26158_2.png"></center>

- Los cambios realizados sobre este campo se visualizarán en el historial del caso.

- Esta disponible el tag de **Solicitante** para envío de correo desde el caso.

### Consola cliente

En consola cliente será posible visualizar los casos de los cuales soy cliente y también los casos de los cuales soy solicitante, por medio del filtro ubicado en la lista de casos.
  
<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26158_4.png"></center>

<br>
## Cierre conforme 

## CASO CH-25350:

Se realiza modificación de cierre conforme, ahora el cierre o no de un caso se realizará por proceso de aprobación de cliente.

### Consola administración

Para configurar la aprobación por cliente diríjase a **Service Desk > Aprobaciones**, 

 <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_1.png"></center>

Seleccione el tipo caso (Aplica únicamente para **Requerimientos de Servicio, Incidentes y Cambios**) y el modelo sobre el cual va a crear el proceso de aprobación.

 <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_2.png"></center>

Haga clic en el botón **Nuevo** y complete los datos requeridos en la pestaña Detalles, así:

**Nombre**: Ingrese un nombre para el proceso de votación.

**Estado**: Elija el estado en el que desea que se active el proceso de votación.

**Descripción**: Ingrese una descripción para el proceso de votación.

**Tipo de aprobación**: Seleccione la opción **Aprobación cliente** para configurar una aprobación de cierre conforme.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_3.png"></center>


Al seleccionar el tipo de aprobación, estarán visualibles u ocultos los campos y pestañas correspondientes.

**Regla para cambio de estado**
Es posible configurar una regla para el cambio automático de estado de acuerdo a los días de garantía del contrato.
<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_5.png"></center>

Al cumplirse los días del contrato y si la aprobación por parte del cliente no se ha realizado, el caso pasará al estado configurado en la regla.

La regla se debe configurar de la siguiente manera:
<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_7.png"></center>

### Consola especialista

Si un caso ingresa al estado en el que se configuró el proceso de aporobación, se presentará el siguiente comportamiento:
  - **Caso con cliente asociado**: Se bloquea el caso, se envia solicitud de aprobación al cliente y se visualiza el mensaje **El caso se encuentra pendiente por aprobación del cliente** 
  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_4.png"></center>

- **Caso sin cliente asociado**: El caso no se bloquea y no se genera proceso de aprobación.

**Aprobación o rechazo cliente**

- **Correo**
Cuando el cliente reciba la solicitud de aprobación, se visualizarán las opciones de acuerdo a la configuración de la plantilla de correo; una vez el cliente aprueba o rechaza la solución, el caso pasará al estado establecido en la configuración del proceso de aprobación.

- **Teams**
El cliente recibirá una notificación solicitando el voto; al dar clic para realizar la votación se habilita las opciones **Aprobar o Rechazar** y no se solicitará justificación de la votación.

 <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25350_6.png"></center>


<br>
## Exportación de CIs con campos adicionales.
---
title: Exportación de CIs con campos adicionales.
chapter: "9.3.3"
---

## CASO CH-25845:

Se realiza ajuste en la consola de administración (ASMS Administrator) con la exportación de Cis, 
ahora el formato se exporta con los campos adicionales de acuerdo a la categoría.

En consola de administración haga clic en **CMDB / CIs**.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25845_1.png"></center>

Seleccione el proyecto y haga clic en **Nuevo / Exportar**.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25845_2.png"></center>

**Nota:**

- Si no configura ningún filtro por tipo, se descargará un formato por cada categoría sobre la cual tenga permiso.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25845_3.png"></center>

- Si realiza el filtro por tipo, se descargará el formato del tipo seleccionado.

Defina si desea exportar los formatos vacíos o con datos.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25845_4.png"></center>

Al abrir el formato generado, en la pestaña CI se visualizarán los campos adicionales.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH25845_5.png"></center>




## Exportación e importación asíncrona.
---
title: Exportación e importación asíncrona.
chapter: "9.3.3"
---

## CASO CH-26046:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual 
permite realizar la exportación con datos e importación asíncrona de los siguientes conceptos:

- Cis
- Clientes
- Especialistas
- Campos adicionales
- Compañías
- Proveedores
- Calendarios
- Estados
- Categorías
- Ubicaciones

Desde consola de administración ubíquese sobre alguno de los conceptos y haga clic en la opción 
**Nuevo / Exportar formato.**

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_1.png"></center>

Seleccione la opción **Formato con datos** y haga clic en el botón **Exportar formato.**

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_2.png"></center>

Vaya a la opción **Notificaciones** ubicada en la parte superior de la consola.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_3.png"></center>

Despliegue el panel de notificaciones, allí se visualizará el formato en estado **Pendiente** y una 
vez finalice, cambiará a estado **Completado** con la fecha de descarga.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_4.png"></center>

Haga clic en la notificación para descargar el archivo.

Para la importación asíncrona, actualice o diligencie el formato y desde la consola de 
administración haga clic en **Nuevo / Importar.**

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_5.png"></center>

En la ventana **Importar** seleccione el archivo y haga clic en **Guardar**. 

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_6.png"></center>

Despliegue el panel de notificaciones, allí se visualizará la importación en estado **Pendiente** y 
una vez finalice, pasará a estado **Completado** con la fecha de carga.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_7.png"></center>

Haga clic en la notificación, allí se desplegará una ventana con los detalles de la importación.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26046_8.png"></center>

**Nota:** 

- la descarga de los formatos sin datos se hace de manera directa para todos los conceptos 
excepto para CIs.



## Ajustes ticket complementario

## CASO CH-26186:

Se realizan ajustes en el cierre por ticket complementario, ahora el ticket complementario se verificará de acuerdo al tipo de relación que tengan los casos.

El ticket complementario verificará la relación en doblevía, no podrá cerrar el caso padre si  tienen casos hijos abiertos con relación complementaria.

**Consola administración**
  - **Relación complementaria**
  Haga clic en **Service Desk / Relaciones** y seleccione la(s) relacion(es) que desea marcar como relación complementaria.
  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26186_1.png"></center>

  - **Estado con cierre por defecto**
  Se modifica el nombre del comportamiento de **Cierre complementario** por **Cierre por defecto**
  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26186_2.png"></center>

**Consola especialista**
- **Cierre de casos padre**
  Al intentar de cerrar un caso que tenga relaciones complementarias abiertas con casos hijos se visualizará el mensaje **No se puede cerrar el caso, tiene hijos con relación complementaria**, para poder cerrar el caso primero debe cerrar todos los casos hijos asociados con relación que tengan la marca de **Relación complementaria**.
  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26186_3.png"></center>

**Nota:** 
Al cerrar el caso padre por cierre complementario, este se cerrará con el estado que está marcado con el comportamiento de  **Cierre por defecto**, si ningún estado del modelo esta marcado con este comportamiento, entonces el caso se cerrara con el primer estado final registrado que no tenga el comportamiento **Anulado**. 
## Configuración por defecto campos adicionales

## CASO CH-26785:

Se realiza ajuste en la creación de campos adicionales a través de la interfaz, ahora al crear un nuevo campo adicional será posible seleccionar si se aplicará la configuración por defecto o no.

**Consola administración**

Al crear un nuevo campo adicional en cualquiera de las secciones se visualizará un modal confirmando si al nuevo campo se asignará la configuración por defecto.

 <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26785_1.png"></center>

  - Al dar clic aceptando la configuración por defecto, en la pestaña **Estados** el campo quedará configurado como editable para las diferentes consolas.  
  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26785_2.png"></center>
  - Al dar clic rechazando la configuración por defecto, en la pestaña **Estados** el campo quedará configurado como oculto para las diferentes consolas.  
  <center><img src="{{ site.baseurl }}/assets/images/9.3.3/CH26785_3.png"></center>

  

## Perdida de adjuntos al convertir un caso.
---
title: Perdida de adjuntos al convertir un caso.
chapter: "9.3.3"
---

## CASO PM-25448:

Se soluciona inconsistencia en la consola de especialista (ASMSSpecialist) con la conversión de casos, 
actualmente se mantienen los archivos adjuntos al realizar conversión de casos. 
## Visualización de servicios en contratos
---
title: Visualización de servicios en contratos
chapter: "9.3.3"
---

## CASO PM-25500:

Se realiza ajuste en la visualización de los servicios asociados a un contrato, Al seleccionar un
nombre de un servicio asociado se visualizará un tooltip con el nombre completo del servicio.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/PM-25500_1.png"></center>
## Eliminar categoría creada por importación
---
title: Eliminar categoría creada por importación
chapter: "9.3.3"
---

## CASO PM-25977:

Se realiza ajuste en la carga masiva de categorías desde la carga de proyectos y desde 
la carga del concepto categorías, ahora al eliminar una categoría recien creada desde
importación no se genera error.
## Envió por correo de artículos con adjuntos.
---
title: Envió por correo de artículos con adjuntos.
chapter: "9.3.3"
---

## CASO PM-26068:

Se soluciona inconsistencia en la consola de usuario (ASMSCustomer) con el envió de artículos vía 
correo electrónico; se incluye la opción **Anexar archivos al correo** con la que podrá definir 
si requiere enviar los archivos adjuntos del artículo en el correo electrónico.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/PM26068_1.png"></center>
## Exportación de Cis con datos.
---
title: Exportación de Cis con datos.
chapter: "9.3.3"
---

## CASO PM-26079:

Se soluciona inconsistencia en la consola de administración (ASMSAdministrator) con la exportación 
del formato de Cis con datos; actualmente exporta toda la información de manera correcta de acuerdo 
al proyecto y tipo seleccionado.
## Descarga masiva de categorías.
---
title: Descarga masiva de categorías.
chapter: "9.3.3"
---

## CASO PM-26136:

Se soluciona inconsistencia en consola de administración (ASMSAdministrator) con la exportación de 
categorías asíncrona cuando existen altos volúmenes de datos; ahora el archivo se se visualiza completo 
solo cuando se haterminado de construir.
## Heredar configuración de las categorías padres a las categorías hijas.
---
title: Heredar configuración de las categorías padres a las categorías hijas.
chapter: "9.3.3"
---

## CASO PM-26434:

Se soluciona inconsistencia en la consola de administración (ASMSAdministrator) al heredar la 
configuración de las categorías padre en la configuración de las categorías hijas; ahora se incluye la opción 
que permite definir al usuario si desea replicar los cambios realizados a las categorías hijas.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/PM26434_1.png"></center>

**Nota**: El ajuste NO aplica para la configuración de la pestaña **Adicionales**.


## Plantillas de correo – consola de especialista.
---
title: Plantillas de correo – consola de especialista.
chapter: "9.3.3"
---

## CASO PM-26511:

Se soluciona inconsistencia en la consola de especialista (ASMSSpecialist) con la selección de plantillas 
para el envío de correo desde el caso; actualmente al seleccionar una plantilla esta se asocia de 
manera correcta al cuerpo del mensaje y al hacer clic en la previsualización, la información se
visualiza de manera adecuada.
## Visualización de estados que no corresponden con las transiciones configuradas.
---
title: Visualización de estados que no corresponden con las transiciones configuradas.
chapter: "9.3.3"
---

## CASO PM-26560:

Se soluciona inconsistencia en la consola de especialista (ASMSSpecialist) con la visualización 
de estados que no corresponden, de acuerdo a las transiciones configuradas desde consola de 
administración.
## Nota por estado al pasar nuevamente por el estado

## CASO PM-26623-19-200627:

Se realiza ajuste en la solicitud de la nota obligatoria por estado, al pasar nuevamente por el estado donde esta configurada la nota obligatoria, se visualiza el modal de nota por estado.
## Modificación del formato de creación de caso
---
title: Modificación del formato de creación de caso
chapter: "9.3.4"
---

## CASO CHG-26620-19-300523:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual al estar activa cambiará el orden de la visualización de secciones en la creación de caso en consola especialista (ASMSSpecialist): 


[Ver Modificación del formato en crear un caso](https://docs.arandasoft.com/asms-specialist/pages/03-crear/01-Crear%20un%20Caso.html)
## Carga masiva Base de conocimiento

## CASO CH-21586:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator) la cual permite realizar la carga masiva de diferentes conceptos para el módulo Base de conocimiento.

[Ver Carga masiva de datos en Base de conocimiento](https://docs.arandasoft.com/asms-admin/pages/09-cargas%20masivas/04-Carga_Masiva_Base_de_conocimiento.html)
## Carga masiva de artículos

## CASO CH-24940:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), ahora es posible hacer creación y actualización masiva de artículos con adjuntos y asociación a carpetas para el módulo de Base de conocimiento.

[Ver Carga masiva de artículos en Base de conocimiento](https://docs.arandasoft.com/asms-admin/pages/06-conocimiento/11-Articulos.html) 
## Configuración masiva matriz de prioridades

## CASO CH-26198:

Se implementa nueva funcionalidad para la configuración de **Matriz de Prioridades**, ahora es posible realizar la configuración realizando la importación de un archivo de Excel.

[Ver Configuración masiva en Matriz de prioridades](https://docs.arandasoft.com/asms-admin/pages/04-sd/17-Matriz%20de%20prioridades.html) 

 
## Cambios masivos no cumplio con los escenarios

## CASO CHG-26619-19-300522:

Se realizan ajustes en la funcionalidad de **Cambios masivos** en la consola de especialista (**ASMSSpecialist**); Actualmente se evaluan los **comportamientos agendado, resuelto y la nota obligatoria por estado**.


[Ver Cambios Masivos en propiedades comunes](https://docs.arandasoft.com/asms-specialist/pages/02-consola/02-Vistas%20por%20defecto.html)
 

 
## SLA por prioridad

## CASO CHG-26692-19-300526:

Se realiza ajuste en la selección de SLA al crear o editar un caso; En la asignación de SLA se tendrá en cuenta toda la lista de prioridades de asignación de SLA del servicio.

<center><img src="{{ site.baseurl }}/assets/images/9.3.4/CHG26692_1.png"></center>

Se asignará el SLA al caso en orden de prioridades, en el orden en el que está asignada la prioridad; si la primera opción no tiene SLA definido, se asignará el SLA de la segunda opción y así hasta encontrar un SLA asocido a una de las opciones.

En el caso en el que **Compañía, Cliente, Categoría, CI o Ubicación** no tengan SLA definido se asignará al caso el SLA por defecto del servicio.

 
## Clonación de reglas por proyecto y modelo

## CASO CHG-27182-19-300548:

Se realizan ajustes en la clonación de reglas por proyecto, ahora es posible realizar la clonación de las reglas por proyecto y modelo para las diferentes secciones donde se encuentra esta funcionalidad.

[Ver Clonación y eliminación masiva de reglas](https://docs.arandasoft.com/asms-admin/pages/04-sd/13-Reglas.html)
## Importación de usuarios por cargue masivo.
---
title: Importación de usuarios por cargue masivo.
chapter: "9.3.4"
---

## CASO CH-26085:

Se realiza ajuste en el formato de creación y/o actualización masiva de usuarios (Especialista, cliente), ahora al realizar creación de usuarios, sólo se importarán usuarios tipo Aranda; los usuarios de dominio deben ser creados a través de la importación con el LDAP.

## Creación y/o actualización masiva de servicios.
---
title: Creación y/o actualización masiva de servicios.
chapter: "9.3.4"
---

## CASO CH-26194, CH-26200, CH-26201 :

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), la cual permite realizar la creación y/o actualización masiva de servicios con la información básica, si se desea incluir la totalidad de la información del servicio la plantilla sólo puede tener un servicio diligenciado.

[Ver Servicios](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/11-Servicios.html)

## Actualización masiva de tiempos.
---
title: Actualización masiva de tiempos.
chapter: "9.3.4"
---

## CASO CH-26196:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), la cual permite realizar actualización masiva de los tiempos de los acuerdos.

[Ver Acuerdos](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/12-Acuerdos.html)
## Falla tiempo de sesión.
---
title: Falla tiempo de sesión.
chapter: "9.3.4"
---

## CASO PM-25024-19-200555:

Se corrige inconsistencia en la consola de especialista (ASMSSpecialist) con los tiempos de sesión. En el momento que una petición responda con código 401, se cierra de manera automática la sesión y deja al usuario en el login de la consola.
## Falla filtros de servicio y compañía.
---
title: Falla filtros de servicio y compañía.
chapter: "9.3.4"
---

## CASO PM-25072-19-200559:

Se corrige inconsistencia en la consola de especialista (ASMSSpecialist) con los filtros por servicio y compañía en la creación y edición del caso; Actualmente los filtros se aplican de manera correcta de acuerdo a la configuración definida en la consola de administración (ASMSAdministrator).
## Configuración calendarios

## CASO PM-26435-19-200601:

Se realiza ajuste en la configuración de calendarios, ahora es posible configurar un calendario iniciando por cualquier día de la semana.


## Relación casos como hijos

## CASO PM-26437-19-200602:

Se realiza ajuste en la relación de casos, ahora se visualizan las relaciones padres e hijas configuradas según corresponda.


## Configuración proyectos

## CASO PM-26438-19-200603:

Se realiza ajuste en la configuración de proyectos, ahora en la pestaña ajustes del proyecto se selecciona el primero de la lista.


## Falla inactivar categoría visible para usuarios.
---
title: Falla inactivar categoría visible para usuarios.
chapter: "9.3.4"
---

## CASO PM-26439-19-200604:

Se corrige inconsistencia en consola de administración (ASMSAdministrator) cuando se activa una categoría y se inhabilita la opción Categoría visible para usuarios, actualmente esta guardando las modificaciones de manera correcta.
## Falla chat consola de especialista.
---
title: Falla chat consola de especialista.
chapter: "9.3.4"
---

## CASO PM-26610-19-200624:

Se corrige inconsistencia en la consola de especialista (ASMSSpecialist), ahora al abrir el chat el control NO queda en blanco.
## Razón al crear caso desde consola cliente

## CASO PM-26621-19-200625:

Se realiza ajuste en la creación de casos desde la consola cliente, ahora en el momento en el que se crea un caso desde consola cliente se asignará como razón para el estado la primera razón que se creó para el estado y que no se encuentre eliminada.


## Actualizar tiempos al cambiar SLA

## CASO PM-26622-19-200626:

Se realiza ajuste en la carga de tiempos una vez se edita un caso y se cambia de acuerdo, los nuevos tiempos se calculan y visualizan de acuerdo a los tiempos y calendario del nuevo acuerdo.

## Ajuste envío de correo desde el caso.
---
title: Ajuste envío de correo desde el caso.
chapter: "9.3.4"
---

## CASO PM-26624-19-200628:

Se realiza ajuste en la consola de especialista (ASMSSpecialist), en el envío de correo desde el caso.

[Ver Editar un caso](https://docs.arandasoft.com/asms-specialist/pages/04-editar/01-Editar%20un%20Caso.html)

## Carpetas administración vs especialista

## CASO PM-26685-19-200639:

Se realiza ajuste en la visualización de categorías en consola especialista, ahora se visualizan las mismas categorías.

## Reactivar conteo de tiempos

## CASO PM-26687-19-200640:

Se desarrolla nueva funcionalidad en consola administración (ASMSAdministrator), para poder reactivar los tiempos una vez se haya cumplido el estado o condición para finalizar el cronómetro.

[Ver Tiempo (Cronómetros) en Service Desk](https://docs.arandasoft.com/asms-admin/pages/04-sd/08-Tiempo%20(Cronometros).html)
## Manejo de tiempos por prioridad

## CASO PM-26688-19-200641:

Se realiza ajuste en la   pestaña de tiempos  y costos de un caso,  ahora al cambiar la prioridad  del caso   y guardar cambios, se actualizarán inmediatamente  los tiempos y progresos de acuerdo a la nueva prioridad cuando el tiempo así este configurado. 

## Falla visualización encuestas consola cliente.
---
title: Falla visualización encuestas consola cliente.
chapter: "9.3.4"
---

## CASO PM-26786-19-200651:

Se corrige inconsistencia en el portal de usuarios (ASMSCustomer), con la visualización de encuestas desde el panel de novedades, ahora se muestra de manera correcta la cantidad de encuestas pendientes por responder.
## Responsable de CI en CMDB

## CASO PM-26844-19-200656, PM-26846-19-200657:

Se realiza ajuste en consola administración (ASMSAdministrator) **CMDB / CI**, ahora es posible asociar como responsable del CI a cualquier usuario (Cliente o Especialista) que se encuentre asociado al proyecto y además que se encuentre activo.

## Limpiar categoría por defecto en servicio

## CASO PM-27177-19-200680:

Se realiza ajuste en la consola administración (ASMSAdministrator), ahora es posible limpiar la categoría por defecto de un servicio una vez se tiene configurada.

## Branding consola especialista

## CASO PM-27389-19-200691:

Se realiza ajuste en el branding de consola especialista, al cargar la imagen se visualiza en el 100% de la pantalla.

## Caso al no alcanzar el umbral de aprobación

## CASO PM-27471-19-200694:

Se realiza ajuste en el proceso de aprobación, ahora a medida en la que se realiza la votación de un caso se va verificando el estado de la votación y si el proceso todavía puede ser aprobado.

En cuanto se evalúa que los votos faltantes no alcanzan para aprobar el caso, el caso es rechazado sin importar los votos faltantes.

## Mensaje al no tener licencias disponibles

## CASO PM-27568-19-200700:

Se realiza ajuste en consola especialista (ASMSspecialist) para mostrar el mensaje correspondiente al no tener licencias concurrentes disponibles para ingresar.

## Asignación de responsable al seleccionar grupo

## CASO PM-27631-19-200706:

Se realiza ajuste en consola especialista (ASMSSpecialist), ya sea en la creación o edición de un caso, al seleccionar el grupo responsable, el campo responsable tendrá el siguiente comportamiento:

1. Si el especialista logueado se encuentra asociado al grupo responsable, este será asociado automáticamente como responsable del caso.
   
2. Si el especialista logueado no se encuentra asociado al grupo responsable, el campo responsable quedará en **seleccione** para definir el responsable del caso.

3. Si el grupo responsable sólo tiene un especialista asociado o disponible, este se selecciona automáticamente como responsable, sin importar si es o no el especialista logueado.

## Asociación masiva de ubicaciones a servicios
---
title: Asociación masiva de ubicaciones a servicios
chapter: "9.3.5"
---

## CASO CH-26135:

Se implementa nueva opción en la hoja **RelationItems** para el formato de cargue y/o 
actualización masiva de servicios, ahora es posible hacer la asociación masiva de
ubicaciones a servicios.

[Ver Servicios](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/11-Servicios.html)

## Se ajusta la etiqueta Desasociar categoría

## CASO CH-26581:

Desde la asociación de las categorías al servicio si se desea desasociar cuando el usuario haga clic derecho sobre el ítem, se desplegará con la etiqueta “desasociar categoría”.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/CHG-26581.png"></center>

## Visualizar la jerarquia de toda la categoría tanto para cliente como para especialista

## CASO CH-26613:

Se ajusta la funcionalidad para que al ubicar el cursor del mouse sobre el respectivo campo, se visualice toda la jeraquía que contiene la categoría en cuestión.

Aplica para consola de administración (ASMSAdministrator) y especialista (ASMSSpecialist).


<center><img src="{{ site.baseurl }}/assets/images/9.3.5/CHG-26613.png"></center>

## Cambio botón ubicación asignado

## CH-26690:

Se realiza ajuste para cambiar la pre selección que trae por defecto el recuadro para cambio de ubicacaión del servicio.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/CHG-26690.png"></center>

## Creación nuevo artículo

## CASO CH-26781:

Se implementa nueva funcionalidad en la consola de especialista (ASMSSpecialist) para que al momento de crear un nuevo artículo, el modal contenga únicamente el formulario que permite crear el artículo en cuestión.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/CHG-26781.png"></center>

## Barra de progreso en casos cerrados.
---
title: Barra de progreso en casos cerrados.
chapter: "9.3.5"
---

## CASO CHG-26686-19-300524:

Se corrige inconsistencia en la consola de especialista (ASMSSpecialist), ahora la barra 
de progreso en la placa del caso se visualiza de manera correcta para casos cerrados.
## Asociar y desasociar relaciones de conceptos a servicios
---
title: Asociar y desasociar relaciones de conceptos a servicios
chapter: "9.3.5"
---

## CASO CHG-26783-19-300532:

Se implementa nueva funcionalidad en la consola de administración (ASMSAdministrator), 
la cual permite asociar y desasociar relaciones de diferentes conceptos a servicios incluyendo categorías.

[Ver Carga y/o actualización masiva de servicios - Servicios](https://docs.arandasoft.com/asms-admin/pages/05-catalogo/11-Servicios.html)
## No visualizar artículos en la consulta de servicios
---
title: No visualizar artículos en la consulta de servicios
chapter: "9.3.5"
---

## CASO CHG-26874-19-300537, CHG-27180-19-300547:

Se incluye la opción **No visualizar artículos en la consulta de servicios en el portal cliente** en el formato de cargue masivo de proyectos.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/CHG26874_1.png"></center>

## URL’s por proyecto para consolas móviles.
---
title: URL’s por proyecto para consolas móviles.
chapter: "9.3.5"
---

## CASO CHG-27202-19-300549:

Se implementa nueva opción en consola de administración (**ASMSAdministrator**) la cual permite obtener 
las URL’s por proyecto a través del API para ser utilizada desde las consolas móviles de cliente 
y especialista.

[Ver Proyectos](https://docs.arandasoft.com/asms-admin/pages/01-general/02-Proyectos.html#url_movil)
## Opción Activar filtro de contratos sobre los servicios en el formato de cargue masivo de proyectos.
---
title: Opción Activar filtro de contratos sobre los servicios en el formato de cargue masivo de proyectos.
chapter: "9.3.5"
---

## CASO CHG-27811-19-300606:

Se incluye la opción **Activar filtro de contratos sobre los servicios** en el 
formato de cargue masivo de proyectos.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/CHG27811_1.png"></center>

## Impacto, Urgencia y Prioridad de acuerdo a la cultura

## CASO PM-25829-19-200581:

Se realiza ajuste en consola especialista (ASMSSpecialist) con la visualzación de los campos Impacto, Urgencia y Prioridad, al crear, editar o visualizar un caso estos campos se visualizarán de acuerdo a la configuración de traducción para cada uno de los valores. 

En consola especialista se visualizará el valor configurado en la traducción de acuerdo a la cultura del especialista logueado en consola., si el valor no tiene traducción configurada se visualizará el valor configurado en base de datos.

## Relacion de articulos 
---
title: Relacion de articulos 
chapter: "9.3.5"
---

## CASO PM-26069:

Se realiza un ajuste en la consola de administracion, se agrega información del tag de relaciones y al importar el formato los datos se asocian correctamente.
## Editar modelo clonado
---
title: Editar modelo clonado
chapter: "9.3.5"
---

## CASO PM-26515-19-200618:

Se realizó un ajuste en la consola de administración, ahora es posible modificar un modelo clonado, aunque ya haya sido clonado anteriormente.
## Clonación de modelos 
---
title: Clonación de modelos 
chapter: "9.3.5"
---

## CASO PM-26517-19-200620:

Se realiza un ajuste en la consola de administracion, ahora es posible clonar un modelo con varios adicionales sin que se genere error en el proceso.
## CASO PM-26580-19-200623, PM-26068:

Se soluciona inconsistencia en la consola de usuario (ASMSCustomer) con el envió de artículos vía 
correo electrónico; se incluye la opción **Anexar archivos al correo** con la que podrá definir 
si requiere enviar los archivos adjuntos del artículo en el correo electrónico.

<center><img src="{{ site.baseurl }}/assets/images/9.3.3/PM26068_1.png"></center>
## Comportamiento de estados en modelo clonado

## CASO PM-27121-19-200682:

Se realiza ajuste en la clonación de modelos en consola administración (ASMSAdministrator); ahora al clonar un modelo, los estados del nuevo modelo contarán con la configuración del modelo original en cuanto a comportamiento y solicitud de nota.


## Fecha fin en encuestas

## CASO PM-27178-19-200681:

Se realiza ajuste en la consola administrador (ASMSAdministrator); ahora si en las configuraciones de **Encuestas**, al configurar el agendamiento de la encuesta, con la opción **una vez**, no se visualizará el campo fecha final.



## CASO PM-27736-19-200721:

Se realiza ajuste en la visualización de los un caso en estado de aprobación interna; ahora al visualizar un caso en estado de aprobación interna, los adjuntos del caso se tendrán el siguiente comportamiento:

1. Al visualizar el caso desde la consola especialista **(ASMSSpecialist)**, será posible la visualización y descarga de adjuntos existentes en el caso.

2. Al visualizar el caso desde el link de aprobación, será posible la visualización y descarga de adjuntos sin importar si el especialista tiene o no permisos para visualizar los adjuntos del tipo de caso.


## Campos adicionales por categoría

## CASO PM-27850-19-200717:

Se soluciona inconsistencia en las consolas cliente (ASMSCustomer) y especialista (ASMSSpecialist); ahora en consola especialista y cliente se visualizarán los campos adicionales de acuerdo a la configuración de la categoría seleccionada en la creación o edición del caso.
## CASO PM-27903-19-200720:

Se realiza ajuste en la aprobación de casos; ahora es posible agregar un especialista al proceso de aprobación de un caso, sin importar las veces que el caso ingrese al proceso de aprobación interna.
## Categorías no visibles cliente

## CASO PM-28110-19-200731:

Se soluciona inconsistencia en la consola cliente (ASMSCustomer); ahora si en **Consola administración / Configuración General / Proyectos / Valores por defecto** se tiene deshabilitada la casilla **Ver categorías no visibles para los usuarios** para el proyecto.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/PM-28110_1.png"></center>

Al tener desactivada una categoría padre en el servicio, al crear el caso con el servicio en consola cliente, no se visualizará la categoría desactivada, pero si se visualizan los hijos.

<center><img src="{{ site.baseurl }}/assets/images/9.3.5/PM-28110_2.png"></center>



## Modificacion articulos publicados
---
title: Modificacion articulos publicados
chapter: "9.3.6"
---

## CASO PM-26321:

Se realizó un ajuste en la consola de administración; cuando un artículo se encuentre en estado publicado, no se podrá modificar la información del artículo, únicamente se podrá modificar el estado y la marca “pública” del artículo.


[Ver Articulos](https://docs.arandasoft.com/asms-admin/pages/06-conocimiento/11-Articulos.html)
## Tipo de caso predeterminado
---
title: Tipo de caso predeterminado
chapter: "9.3.6"
---

## CASO PM-26784-19-200650:

Se realiza un ajuste en la consola de administración; al momento de seleccionar un tipo de caso predeterminado y crear un caso en consola cliente, el tipo de caso se visualizará.

## Campos obligatorios en tareas
---
title: Campos obligatorios en tareas
chapter: "9.3.6"
---

## CASO PM-26822-19-200653:

Se realiza un ajuste en la consola de especialista, en la creación de tareas manuales de un caso, se podrá visualizar el símbolo (*) obligatorio, en los campos **Duración** y **Fecha inicio**.
## Aumentar longitud de contraseña (Case Creator)
---
title: Aumentar longitud de contraseña (Case Creator)
chapter: "9.3.6"
---

## CASO PM-28752-19-200773:

Se realiza ajuste en la consola de administración (ASMSAdministrator), ahora es posible almacenar contraseñas para el servidor de salida con una longitud máxima de 255 caracteres a nivel de BD, en consola de administración se mantiene la longitud para este campo en 50 caracteres.