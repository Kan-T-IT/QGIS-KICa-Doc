# Guía de Usuario

## Instalación del complemento
Descargar el plugin comprimido desde este link.
Una vez descargado, abrir el QGIS (es recomendable que sea la última versión estable).
En la barra de herramientas, ir a Plugins y a “Gestionar e Instalar Plugins”.

Allí se abrirá una ventana como la siguiente:


Para instalar el plugin, hay que dirigirse hacia “Instalar desde un ZIP” y seleccionar desde nuestro disco local la ubicación del zip descargado anteriormente.

Una vez cargado, clickear en “Instalar Plugin” y esperar el tiempo que tarde. Una vez que se instale, aparecerá el ícono de “Kan Imagery Catalog” como también en la barra de herramientas Plugins > Kan Imagery Catalog.


## Plugin
Al abrir el plugin de Kan Imagery Catalog, se desplegará sobre la derecha de la pantalla del QGIS con el siguiente orden:


+ Configuración
+ Área de búsqueda
+ Selección de catálogos
+ Filtros
+ Listado

### Configuración
Para hacer uso del plugin Kan Imagery Catalog, lo primero que hay que hacer es configurar las credenciales que se usarán para conectarse a los distintos proveedores de imágenes.

#### Credenciales
En este momento, avanzaremos con la configuración de las credenciales para UP42. Para poder avanzar es necesario contar con un usuario y contraseña en la plataforma del proveedor. Para registrarse, puedes ingresar a https://console.up42.com/log-in.
Una vez que hayas habilitado tu usuario y hayas cargado el primer proyecto, podrás acceder a la información solicitada por el plugin para poder utilizarlo.

Para conectarse con el proveedor, el plugin solicita la siguiente información:
+ Project ID
+ API ID

*Ayuda:* estos datos se encuentran en el portal de UP42 > Projects > Developers.

Habiendo cargado los datos necesarios, puede verificarse las credenciales.

De ser válidas, aparecerá la leyenda **“Las credenciales son válidas”**.

#### Parámetros Generales
A parte de cargar las credenciales, el usuario puede setear los siguientes parámetros:
+ **Idioma:** seleccionar Español, Inglés o Portugués.
+ **Cantidad de días de consulta**
+ **Nubosidad máxima por defecto:** puede variar entre 0 y 100%.
+ **Ruta de descarga**
+ **Cantidad máxima de catálogos** 
+ **Cantidad máxima de objetos por catálogo**

Establecidos los parámetros generales, aplicar los cambios mediante **Aceptar**.

### Área de búsqueda
Con el área de búsqueda, el usuario puede delimitar la zona (bounding box) sobre la que el plugin buscará disponibilidad de imágenes.
Puede utilizarse la extensión de lo que se está viendo en el QGIS, es decir, en este caso se usaría “Usar área visible en pantalla”, o bien se puede seleccionar una capa de geometría de tipo polígono que esté siendo usada en el presente proyecto de QGIS.


### Selección de catálogos
En este apartado, el usuario podrá seleccionar los catálogos y las colecciones que se quieran consultar.

En el buscador por nombre o descripción, el usuario puede filtrar por el valor que escriba. En caso de dejarlo en blanco y filtrar, se enlistarán todos los catálogos del/de los proveedor/es que se esté consultando.
Por ejemplo, si colocamos “Sentinel” en el buscador y filtramos:

Al seleccionar el catálogo en la primera ventana y clickeando “Agregar seleccionadas”, las colecciones pasarán a la segunda ventana. Para avanzar con estas preferencias, clickear en “Aceptar”.

#### Eliminar catálogos y colecciones
En caso que el usuario quiera no consultar las colecciones que había establecido con anterioridad, deberá volver a abrir la ventana de Selección de Catálogos, seleccionar las “Colecciones seleccionadas” y eliminarlas, para posteriormente Aceptar los cambios.



### Filtros
Antes de realizar la búsqueda de colecciones, se pueden establecer varios criterios de búsqueda complementarios:
+ Fecha desde
+ Fecha hasta
+ Nubosidad
+ Límite de registros

#### Fecha desde y Fecha hasta
En este caso, se puede determinar la amplitud de fechas desde y hasta las cuales el plugin buscará las imágenes.

Por default, el plugin busca imágenes desde 7 (siete) días antes de la fecha de consulta.

#### Nubosidad
Se puede determinar el porcentaje máximo de nubosidad que tendrían que tener las colecciones filtradas.

#### Límite de registros
Se puede establecer un límite máximo de registros sobre colecciones buscadas. El plugin viene configurado con 10 registros máximo, pero el usuario puede modificarlo a gusto.

### Buscar y listado
Una vez establecido el área de búsqueda, los catálogos y colecciones y los filtros, se procede a realizar la búsqueda.

Los resultados de la búsqueda serán, como máximo, 10 (diez) registros, de acuerdo a lo seteado en los Filtros.

Los resultados pueden ordenarse ascendente o descendente según la fecha de adquisición.

### Funciones de los resultados
Se pueden ver tres funciones:
+ Información
+ Vista rápida
+ Descarga

#### Información
El ícono de la “i” hace referencia a la información general de la colección seleccionada.

Se abrirá la ventana con información complementaria


#### Vista rápida
Mediante el botón del ojo, el usuario podrá observar una vista rápida de la imagen seleccionada. La vista rápida consiste en una pisada (alcance de la imagen) y una previsualización del ráster.



#### Descarga
A desarrollar.


