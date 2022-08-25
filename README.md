:herb: DESCRIPCIÓN DEL PROYECTO: :herb:

En este proyecto se desarrollarán pruebas con Karate para probar los diversos Endpoints de la siguiente API: "https://reqres.in/api/" :alien:

Los Endpoints que se probarán son los siguientes:
#
:boom: Get: "https://reqres.in/api//users/2", sirve para traer la información del usuario que ha sido registrado.
# 
:boom: Post: "https://reqres.in/api//users", sirve para enviar la información del usuario a la base de datos.
# 
:boom: Delete: "https://reqres.in/api//users/{id}", sirve para eliminar la información del usuario de la base de datos.
# 
:boom: Put: "https://reqres.in/api//users{id}", sirve para actualizar la información del usuario en la base de datos.
# 
#
:calling: A TENER EN CUENTA: :calling:

Con el fin de aplicar buenas prácticas se decidió utilizar los siguientes patrones de diseño:
#
:capital_abcd: Patrón Objet Model  
#
:capital_abcd: Patrón ScreenPlay
#
Y además se hizo uso de :recycle: la programación orientada a objetos :recycle: en la estructura del código.
#
#

:violin: PRERREQUISITOS: :violin:

Para poder ejecutar el proyecto se requieren las siguientes especificaciones:
#
:heavy_check_mark: Java con la versión de 1.8
#
:heavy_check_mark: Maven con la versión 3.6.0
#
:heavy_check_mark: Karate con la versión 0.9.6
#
:heavy_check_mark: karate-apache con la última versión
#
:heavy_check_mark: karate-junit5 con la última versión
#
:heavy_check_mark: cucumber-reporting con la última versión
#
#

:metro: EJECUCIÓN: :metro:

Para ejecutar cualquier feature individual se requiere correr el Runners correspondiente de las clases de Java. En nuestro caso tenemos la siguiente relación:
#

:soon: Client.java  => client.feature
#
:soon: Create.java  => create.feature
#
:soon: Delete.java  => delete.feature
#
:soon: Update.java  => update.feature
#
Por otro lado, si queremos ejecutar todas las features de manera paralela ejecutamos la siguiente clase de Java:
#
:on: AllFeaturesTest.java
#
Por último, si queremos ver los reportes desde el navegador seguimos los siguientes pasos:
#
:white_circle: Nos dirigimos a la carpeta Target y la desplegamos
#
:white_circle:  Desplegamos la carpeta "Cucumber-html-reports"
#
:white_circle: Dar click derecho al archivo "overview-features.html", seleccionar la opción "Open in", luego "Browser" y seleccionar el navegador de preferencia.

#

:man:AUTOR::man:

Ismael Alexander Carvajal González


