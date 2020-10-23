# Organiación de señales
___



IDbox. a traves de las 'Agrupaciones de puntos", permite almacenar y organizar de forma personalizada en una jerarquía todos los datos con los que se podré trabajar posteriormente. 
La Jerarquía de Agrupaciones permite localizar señales relacionadas entre si de una forma rapida y sencilla, aun cuando sus origenes sean dispositivos de diferente naturaleza (PLCs, CNCs, OPCServer, Ficheros, etc.). 
Señales Favoritas: El cliente web de IDbox ofrece la posibilidad de seleccionar cualquier señal de sus agrupaciones e incluirlas en un grupo de señales favoritas. 
La agrupación 'Mis Favoritos' se trata de una agrupación especial donde se listan todas las señales de consulta más frecuente y se visualiza, de forma automática, los datos históricos de las últimas horas en modo gráfica de tendencia. 

## Configuración del TAG

La ventana de Configuración del TAG permite leer o modificar la información de éste, según los permisos asignados.

Desde esta sección podemos visualizar información útil a la hora de configurar tanto la sensibilidad de las alarmas del sistema como la desviación típica, amplitud y 
valores máximos y mínimos, junto con el valor de mmuestreo de los últimos meses, permitiéndonos detectar la degradación de un sensor o una posible incidencia para un punto.

![Imagen Tags](../../resources/organizacionDeSenales/foto.PNG)


Las flechas que se encuentran a ambos lados de la ventana nos permiten desplazarnos entre los diferentes TAGs del listado de puntos.
**Desviación típica:** indica la variación esperada con respecto a la media aritmética. Refleja de forma gráfica la amplitd y los máximos  mínimos, permitiendo ver si hay muchos valores fuera de rango. También visualiza los valores máximos y mínimos configurados como límites

___

## Creación de agrupaciones

Se debe crear un documento de señales (Agrupaciones de puntos) que contendrá la agrupación de TAGs. Para ello:

1-Hacemos click con el botón derecho sobre la carpeta de "Agrupaciones" en la zona de menús y elegimos "Agregar"

![Imagen 1](../../resources/organizacionDeSenales/foto1.PNG)

2-Se puede crear una agrupación de señales bien en una "Carpeta de agrupación de TAGs" o bien en una "Carpeta de Contenido genérico". Debemos añadir un nombre, por ejemplo, "Carpeta" antes de pulasr sobre el icono de crear.

![Imagen 2(../../resources/organizacionDeSenales/foto2.PNG)

3-Sobre la carpeta que contendrá la agrupación, con el botón derecho dispondremos de nuevo de la opción agregar.

![Imagen 3](../../resources/organizacionDeSenales/foto3.PNG)

Seleccionamos un documento de señales, que nos permitirá guardar nuestra agrupación. En el apartado Nombre escribimos, por ejemplo, "Agrupación" y hacemos click en Crear.

![Imagen 4](../../resources/organizacionDeSenales/foto4.PNG)

___

## Asociación de los TAGs a las agrupaciones

Una vez creada la agrupación se le deben asociar los distintos TAGs. Para ello, pulse sobre la "Lista de TAGs" para que le muestre el listado de todos los TAGs del sistema. A continuación, seleccione los puntos que desee agregar. En la parte superior, pinche la flecha al lado de "Favoritos" y seleccione la carpeta y la agrupación en la que desee agregar los TAGs. Puede pulsarla o arrastrar los TAGs sobre ésta.

![Imagen 5](../../resources/organizacionDeSenales/foto5.PNG)

Si ha realizado correctamente los pasos anteriores, saldrá un mensaje de confirmación y con ello podrá visualizar los TAGs seleccionados en la agrupación elegida dentro del árbol jerárquico de la zona del menú.

![Imagen 6](../../resources/organizacionDeSenales/foto6.PNG)

___

## Ordenar elementos

Una vez creados los elementos, estos se mostrarán en el menú de árbol situado a la izquierda de la aplicación. Pulsando en el botón derecho sobre cualquiera de ellos podemos acceder a diversas opciones, una de ellas es la opción de ordenar nodos.

Esta opción nos mostrará un listado de los elementos que se encuentren al mismo nivel que nuestro elemento seleccionado permitiéndonos ordenarlos cuando los arrastremos.

![Imagen 7](../../resources/organizacionDeSenales/foto7.PNG)

___

## Privacidad de los documentos

### Publicar/Despublicar elementos

Siempre que cree un nuevo elemento(agrupaciones, sinópticos, mapas, etc), éste aparecerá por defecto despublicado, siendo únicamente accesible para el usuario hasta que lo de por concluido.

Una vez concluido el proceso, para hacerlo visible a otros usuarios, deberá de pulsar el botón derecho sobre el elemetno (en el árbol jerárquico de la zona de menú) y seleccionar la opción "Publicar".

![Imagen 8](../../resources/organizacionDeSenales/foto8.PNG)

**¡Atención!** Para que un documento de agrupación sea visible a los demás usuarios, es necesario que también estén publicadas sus carpetas padre

![Imagen 9](../../resources/organizacionDeSenales/foto9.PNG)

Si posteriormente desease volver a ocultar para los demás usuarios alguno de los documentos, puede volver a pulsar el botón derecho sobre el mismo y seleccionar la opción "Despublicar", que lo dejará visible únicamente para Ud.

![Imagen 10](../../resources/organizacionDeSenales/foto10.PNG)


### Compartir elementos entre clientes

En determinadas ocasiones, cuando esté trabajando con varios clientes y si dispone de los permisos adecuados, podrá compartir un documento con otros clientes, así como eliminar su acceso al mismo para los clientes que considere.
