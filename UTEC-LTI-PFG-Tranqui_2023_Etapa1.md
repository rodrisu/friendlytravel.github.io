**Friendly Travel**

	

Diego Rosales

Alfredo López Pintos

Rodrigo Serrón

Universidad Tecnológica del Uruguay

Licenciatura en Tecnologías de la Información

Proyecto Final de Titulación



4. 
METODOLOGÍA Y RESULTADOS


    6. Alcance

Los siguientes requerimientos funcionales y no funcionales se han seleccionado cuidadosamente para el desarrollo e implementación del proyecto. Estos requerimientos están diseñados para ofrecer un producto que no solo asegure la calidad y el cumplimiento de los estándares, sino que también proporcionan funcionalidades que enriquecen la experiencia de los usuarios y agregan valor a la plataforma.



        1. Diagrama de contexto

El siguiente diagrama de contexto es una representación visual que muestra cómo nuestra plataforma interactúa con sus entornos externos, incluyendo otros sistemas y usuarios. Proporciona una vista de alto nivel de cómo se sitúa la plataforma en su contexto.

Figura 1. Diagrama de contexto



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")




        2. Diagrama de contenedores

El siguiente diagrama de contenedores es una herramienta que describe la estructura de la aplicación, mostrando los componentes principales y cómo se relacionan entre sí. Aporta claridad sobre la arquitectura y los servicios involucrados en la plataforma.

Figura 2. Diagrama de contenedores



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")




        3. Requerimientos funcionales

A continuación, se listan los requerimientos funcionales que guiarán el desarrollo de la plataforma:

Tabla 1. Requerimientos funcionales


<table>
  <tr>
   <td>ID
   </td>
   <td>Requerimiento
   </td>
   <td>Detalle
   </td>
   <td>Prioridad
   </td>
  </tr>
  <tr>
   <td>RF-01
   </td>
   <td>Registro de usuario
   </td>
   <td>
<ul>

<li>Todo usuario podrá registrarse en la aplicación

<li>Será necesario ingresar nombre, apellido, fecha de nacimiento, documento de identidad, email, teléfono.
</li>
</ul>
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RF-02
   </td>
   <td>Registro de vehículo
   </td>
   <td>- El usuario previamente registrado podrá registrar su vehículo para ofrecer viajes.
<p>
- Se le solicitarán datos extra como marca, modelo, entre otros.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RF-03
   </td>
   <td>Crear un viaje
   </td>
   <td>Un conductor registra un viaje para ser ofrecido a los usuarios, con origen, destino, fecha, plazas disponibles y precio.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RF-04
   </td>
   <td>Buscar un viaje
   </td>
   <td>Un usuario puede buscar viajes como pasajero indicando ciertos criterios de búsqueda
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RF-05
   </td>
   <td>Verificación de teléfono
   </td>
   <td>El sistema podrá verificar que el teléfono ingresado sea un número uruguayo mediante el envío de un código para corroborar que sea el utilizado por el usuario.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-06
   </td>
   <td>Verificación de email
   </td>
   <td>El sistema podrá verificar el email ingresado mediante el envío de un código para corroborar que sea el utilizado por el usuario.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-07
   </td>
   <td>Verificación de documento
   </td>
   <td>El sistema podrá verificar el documento ingresado mediante la solicitud de una fotografía de la cédula del usuario.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-08
   </td>
   <td>Inicio de sesión
   </td>
   <td>Un usuario previamente registrado podrá iniciar sesión, ingresando el email y la contraseña.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RF-09
   </td>
   <td>Listado de viajes / resultados
   </td>
   <td>Al realizar la acción de buscar un viaje, se listan sólo los viajes con plazas disponibles según el criterio indicado. Las acciones disponibles a realizar dependerán de si el usuario ha iniciado sesión en la plataforma o no.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-10
   </td>
   <td>Filtrar resultados
   </td>
   <td>[Opcional] En el listado de viajes, será posible filtrar los resultados por precio, origen, destino o cantidad de asientos.
   </td>
   <td>Baja
   </td>
  </tr>
  <tr>
   <td>RF-11
   </td>
   <td>Sistema de reputación
   </td>
   <td>Pasada la fecha del viaje, tanto el conductor como el pasajero, podrá puntuar a su contraparte. Para contribuir a enriquecer el sistema.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-12
   </td>
   <td>Contacto
   </td>
   <td>Será posible contactar a la contraparte mediante una redirección al sitio de WhatsApp
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-13
   </td>
   <td>Historial de viajes
   </td>
   <td>Es posible listar los viajes realizados por usuario
   </td>
   <td>Baja
   </td>
  </tr>
  <tr>
   <td>RF-14
   </td>
   <td>Ordenar resultados
   </td>
   <td>En el listado de viajes, será posible ordenar los resultados según ciertos criterios.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-15
   </td>
   <td>Mis viajes
   </td>
   <td>Cada usuario podrá ver los viajes por venir, tanto como conductor o pasajero
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RF-16
   </td>
   <td>Reservar viajes
   </td>
   <td>Los pasajeros podrán reservar el viaje que estén interesados.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RF-17
   </td>
   <td>Estadísticas
   </td>
   <td>[Opcional] Cada usuario podrá visualizar una sección de estadísticas respecto a los viajes realizados.
   </td>
   <td>Baja
   </td>
  </tr>
  <tr>
   <td>RF-18
   </td>
   <td>FAQs
   </td>
   <td>La aplicación contará con una sección de FAQs para evacuar dudas comunes de los usuarios.
   </td>
   <td>Baja
   </td>
  </tr>
</table>






        4. Diagramas de flujo

Figura 1. Diagrama de flujo RF01 - Registro de usuario.



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")




Figura 2. Diagrama de flujo RF02 - Registro de vehiculo



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


Figura 3. Diagrama de flujo RF03 - Crear viaje



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")


Figura 4. Diagrama de flujo RF04 y RF09 - Buscar y Listar viajes



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")


Figura 5. Diagrama de flujo RF11 - Sistema de reputación (Calificación)



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")


Figura 6. Diagrama de flujo RF12 - Contacto



<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")


Figura 7. Diagrama de flujo RF16 - Reserva de viaje



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")






        5. Requerimientos no funcionales

También se han definido requerimientos no funcionales para asegurar otros aspectos de la plataforma:

Tabla 2. Requerimientos no funcionales


<table>
  <tr>
   <td>ID
   </td>
   <td>Requerimiento
   </td>
   <td>Detalle
   </td>
   <td>Prioridad
   </td>
  </tr>
  <tr>
   <td>RNF-01
   </td>
   <td>Usabilidad
   </td>
   <td>Al menos el 90% de los usuarios en pruebas de usabilidad deberá calificar la aplicación como "fácil de usar".
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-02
   </td>
   <td>Consistencia e integridad
   </td>
   <td>La discrepancia en la presentación de datos en diferentes dispositivos y navegadores no debe superar el 5%.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-03
   </td>
   <td>Seguridad de datos
   </td>
   <td>La aplicación garantizará la confidencialidad, integridad y disponibilidad de los datos mediante medidas de seguridad, pruebas de seguridad regulares, cumplimiento de regulaciones de privacidad y auditorías anuales.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-04
   </td>
   <td>Velocidad
   </td>
   <td>La aplicación proporcionará tiempos de respuesta de 2 a 5 segundos para operaciones comunes en condiciones normales de uso.
   </td>
   <td>Media
   </td>
  </tr>
  <tr>
   <td>RNF-05
   </td>
   <td>Seguridad al usuario
   </td>
   <td>Se implementarán medidas de seguridad para proteger a los usuarios, incluyendo autenticación segura, comunicaciones cifradas, notificaciones claras, política de privacidad transparente, protección de datos sensibles y  actualizaciones de seguridad.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-06
   </td>
   <td>Confidencialidad
   </td>
   <td>La aplicación no almacenará información sensible, como contraseñas en texto plano o datos de tarjetas de crédito.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-07
   </td>
   <td>Responsabilidad
   </td>
   <td>La aplicación deberá contar con una política de términos y condiciones que exima a la empresa de responsabilidad por mal uso de la plataforma por parte de los usuarios, con revisión anual de los términos y condiciones.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-08
   </td>
   <td>Legislatividad
   </td>
   <td>La aplicación cumplirá con las leyes y regulaciones vigentes del país, incluyendo el Decreto N° 64/020 referente a la protección de datos y el artículo 1324 del Código Civil N° 16603.
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-09
   </td>
   <td>Costo
   </td>
   <td>La aplicación será gratuita para su uso, sin cargos ocultos ni compras dentro de la aplicación (in-app purchases).
   </td>
   <td>Alta
   </td>
  </tr>
  <tr>
   <td>RNF-10
   </td>
   <td>Recuperación de errores
   </td>
   <td>En caso de fallos del sistema, la aplicación deberá ser capaz de recuperarse automáticamente dentro de un máximo de 8 horas, minimizando la interrupción del servicio y la pérdida de datos.
   </td>
   <td>Media
   </td>
  </tr>
</table>


Fuente: Elaboración propia - https://iso25000.com/index.php/normas-iso-25000/iso-25010 <sup>17</sup>

Esta sección brinda una visión clara del alcance del proyecto, desde su contexto hasta su estructura interna, listando el conjunto de requerimientos funcionales y no funcionales que permitirán una experiencia completa y enriquecedora para los usuarios de nuestra plataforma y proporcionando un producto sólido y competitivo en el mercado.



    7. Tecnología

El proyecto consiste en desarrollar una aplicación serverless en la nube utilizando los servicios de AWS. Para lograr esto utilizaremos DynamoDB como base de datos no relacional, Java como lenguaje de programación en backend y ReactJS para el desarrollo del frontend.

Entre los servicios de AWS que serán utilizados se encuentran, el ya mencionado DynamoDB para la base de datos; Cognito para la administración, autenticación y autorización de los usuarios; funciones Lambda para el desarrollo y uso de las funcionalidades serverless; S3 para alojar los componentes web estáticos y documentos subidos por el usuario; API Gateway para desarrollar la API Rest, la cual será encargada de llamar a las funciones Lambda necesarias para realizar las acciones correspondientes. \
Otros servicios que estaremos utilizando, a modo de agregar mayor funcionalidades son, Textract como servicio OCR para la verificación de los documentos; CloudFront, donde será desplegado el frontend de la aplicación, será el punto de entrada de los usuarios; CloudWatch, para revisión de logs y métricas de la aplicación, así poder llevar un control de la performance, errores y mejorar la respuesta a solución de problemas. \
También contaremos con dos servicios de Google Cloud, siendo uno de ellos la API de Google Maps y, para implementar nuestra solución de CI/CD, levantaremos una instancia de Google Compute Engine la cual usaremos como nuestro servidor de Jenkins.



        6. Justificación

Decidimos usar ReactJS por su facilidad de aprendizaje y uso, además cuenta con amplia documentación y comunidad que respalda este framework.

Por otro lado, usamos Java para el backend ya que es un stack bastante conocido y ampliamente documentado lo cual nos facilita el desarrollo de nuestro backend, además es muy efectivo por su performance en ambientes cloud distribuidos, como será nuestro caso.

Al ser nuestra aplicación del tipo serverless es que utilizaremos servicios cloud, específicamente los servicios de AWS, principalmente por la razón que es el proveedor de servicios cloud más utilizado hoy en día, con muy buen soporte, documentación y ejemplos ampliamente variados, por lo que no será un impedimento para aprender sobre dichos servicios. Sumado a esto, cabe mencionar que AWS ofrece un nivel gratuito en varios de sus servicios, algunos gratuitos para siempre con un límite de uso, y otros por un período de tiempo limitado, entre ellos los servicios que serán implementados en nuestra aplicación.

DynamoDB como base de datos, por ser un servicio de AWS específico para aplicaciones serverless, su configuración y uso en la aplicación es bastante simple. Al ser una base de datos no relacional contamos con la ventaja de la flexibilidad y velocidad en las consultas que éstas brindan.

Como sistema de control de versiones utilizaremos GitHub, siguiendo el flujo de GitFlow y sus buenas prácticas. Se eligieron estos debido a su simplicidad y facilidad de uso. Otro factor que se tuvo en cuenta es el potencial de GitFlow para la organización de proyectos web y la amplia variedad de herramientas y plugins que ofrece GitHub.

La idea principal detrás de GitFlow es aislar el trabajo en diferentes tipos de branches, lo que le permite adaptarse muy bien al proceso colaborativo que necesita un equipo de desarrollo. GitFlow está basado principalmente en dos branches que tienen una vida infinita:



* main: contiene el código de producción.
* develop: contiene el código que ha finalizado desarrollo.

Adicional a estos branches principales, durante el desarrollo se crean otros branches de soporte que tienen una vida finita, es decir, existen mientras exista el desarrollo:



* feature: se crea a partir de develop cuando una nueva funcionalidad necesita ser desarrollada. Al finalizar el desarrollo se hace merge a develop nuevamente.
* release: se crea a partir de develop para preparar una nueva versión del código que debe ser liberada en producción. Al finalizar el desarrollo se hace merge a develop y a main.
* hotfix: se crea a partir de main cuando es necesario corregir un error detectado en producción de manera urgente. Al finalizar el desarrollo se hace merge a develop y a main.

El flujo de Gitflow que vamos a usar es el siguiente:



1. Se crea una rama develop a partir de main.
2. Se crea una rama release a partir de la develop.
3. Se crean ramas feature a partir de la develop.
4. Cuando se termina una rama feature, se fusiona en la rama develop.
5. Cuando la rama release está lista, se fusiona en las ramas develop y main.
6. Si se detecta un problema en main, se crea una rama hotfix a partir de main.
7. Una vez terminada la rama hotfix, esta se fusiona tanto en develop como en main.



Figura 8. Diagrama de arquitectura GIT.



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")


Fuente: [https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow](https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow) <sup>22</sup>



    8. Planificación

En esta sección se menciona la metodología aplicada, planificación del tiempo, riesgos, costos y calidad, los cuales son aspectos relevantes para el proyecto.



        7. Planificación del tiempo

Para lograr los objetivos, hemos propuesto un promedio de 40 horas semanales de trabajo por cada integrante del equipo, sumando un total de 240 horas hombre por sprint y 1440 horas hombre en total para la finalización del proyecto.

En la figura a continuación (figura 9) se muestra la planificación a nivel de sprints con sus fechas correspondientes, para apreciar de una manera más óptima la organización del proyecto.

Figura 9. Diagrama de Gantt resumido



<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")


En la figura a continuación (figura 10) se muestra la planificación de los sprints con sus actividades y fechas correspondientes, así como las entregas y/o eventos requeridos por la UTEC.



Figura 10. Diagrama de Gantt ([cronograma](https://drive.google.com/file/d/1NOZY5cGjsRK0ftDgBr_KJ2MLD_TvnBsL/view?usp=sharing)). <sup>20</sup>


        

<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")




        8. Riesgos

La meta principal del análisis de riesgos consiste en establecer las prioridades de los elementos de la lista de riesgos y determinar cuál de ellos justifica la reserva de recursos para el planeamiento. Por otro lado, la asignación de prioridades a los riesgos permitirá tratar en primer lugar los riesgos más importantes del proyecto. La Matriz de Riesgos es una herramienta de gestión que permite determinar objetivamente cuáles son los riesgos relevantes. La matriz determinada está conformada por los valores de impacto y probabilidad de ocurrencia estudiados detenidamente y basados en los siguientes parámetros.

Tabla 3. Parámetros frecuencia - impacto


<table>
  <tr>
   <td><strong>Frecuencia</strong>
   </td>
   <td><strong>Impacto</strong>
   </td>
  </tr>
  <tr>
   <td>1. Improbable
   </td>
   <td>1. Insignificante
   </td>
  </tr>
  <tr>
   <td>2. Posible
   </td>
   <td>2. Menor
   </td>
  </tr>
  <tr>
   <td>3. Ocasional
   </td>
   <td>3. Moderado
   </td>
  </tr>
  <tr>
   <td>4. Probable
   </td>
   <td>4. Mayor
   </td>
  </tr>
  <tr>
   <td>5. Frecuente
   </td>
   <td>5. Catastrófico
   </td>
  </tr>
</table>


La evaluación de riesgos es el proceso de comparar el riesgo estimado con un criterio preestablecido para determinar su importancia. El riesgo se expresa en términos que combinen la probabilidad con las consecuencias de un evento no deseado.

En la siguiente tabla (tabla 4) se representan los riesgos evaluados y las posibles respuestas ante estos.Tabla 4. Evaluación de riesgos.


<table>
  <tr>
   <td><strong>ID</strong>
   </td>
   <td><strong>Nombre</strong>
   </td>
   <td><strong>Frecuencia</strong>
   </td>
   <td><strong>Impacto</strong>
   </td>
   <td><strong>Valoración</strong>
   </td>
   <td><strong>Respuesta</strong>
   </td>
  </tr>
  <tr>
   <td>R001
   </td>
   <td>Requerimientos incompletos o ambiguos
   </td>
   <td>3
   </td>
   <td>5
   </td>
   <td>

<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image13.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Ingeniería de requerimientos al comienzo del proyecto y validaciones con el cliente durante todo el proyecto
   </td>
  </tr>
  <tr>
   <td>R002
   </td>
   <td>No alcanzar la calidad del producto 
   </td>
   <td>4
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image14.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Realización de instancias de
<p>
validación con cada uno de los
<p>
interesados
   </td>
  </tr>
  <tr>
   <td>R003
   </td>
   <td>No alcanzar la calidad en usabilidad
   </td>
   <td>4
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image15.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Planificar esta cualidad y capacitar al equipo para cumplirmiento
   </td>
  </tr>
  <tr>
   <td>R004
   </td>
   <td>Retrasos en la esp. de requerimientos
   </td>
   <td>4
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image16.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Reuniones tempranas y continuas con el cliente
   </td>
  </tr>
  <tr>
   <td>R005
   </td>
   <td>Incorporación continua de nuevos requerimientos
   </td>
   <td>3
   </td>
   <td>5
   </td>
   <td>

<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image17.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Pautar con el cliente y comunicar la problemática del cambio
   </td>
  </tr>
  <tr>
   <td>R006
   </td>
   <td>Entendimiento errado de los requerimientos
   </td>
   <td>3
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image18.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Estudiar este documento y unificar conceptos con todo el equipo
   </td>
  </tr>
  <tr>
   <td>R007
   </td>
   <td>Incorrecta definición y estructuración de datos
   </td>
   <td>3
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image19.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Evaluar una estrategia en este sentido, unificar conceptos con equipo
   </td>
  </tr>
  <tr>
   <td>R008
   </td>
   <td>Diseño de interfaces incompleto
   </td>
   <td>3
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image20.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Planificar el cronograma para la culminación en forma de esta tarea
   </td>
  </tr>
  <tr>
   <td>R009
   </td>
   <td>Desconocimiento de la lógica de negocio
   </td>
   <td>2
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image21.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image21.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Reuniones periódicas con el cliente para estar al día con la idea
   </td>
  </tr>
  <tr>
   <td>R010
   </td>
   <td>Manejo inadecuado en liberación de versiones
   </td>
   <td>2
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image22.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image22.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Manejar eficientemente el versionado en herramientas como git
   </td>
  </tr>
  <tr>
   <td>R011
   </td>
   <td>Falta de documentación en código fuente
   </td>
   <td>3
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image23.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image23.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Apegarse a las buenas prácticas de documentación del código
   </td>
  </tr>
  <tr>
   <td>R012
   </td>
   <td>Modificación del  cronograma actividades 
   </td>
   <td>4
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert24" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image24.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert25">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image24.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Buena planificación. apegarse a rutas críticas y holguras establecidas
   </td>
  </tr>
  <tr>
   <td>R013
   </td>
   <td>No disponibilidad de hardware y/o software
   </td>
   <td>1
   </td>
   <td>2
   </td>
   <td>

<p id="gdcalert25" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image25.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert26">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image25.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R014
   </td>
   <td>El Software es complejo de implementar
   </td>
   <td>2
   </td>
   <td>2
   </td>
   <td>

<p id="gdcalert26" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image26.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert27">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image26.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R015
   </td>
   <td>Retiro de integrantes con conocimiento y exp.
   </td>
   <td>1
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert27" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image27.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert28">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image27.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R016
   </td>
   <td>Mala comunicación y/o sinergia en el equipo
   </td>
   <td>1
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert28" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image28.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert29">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image28.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R017
   </td>
   <td>Falta de conocimiento sobre las tareas y herr.
   </td>
   <td>3
   </td>
   <td>2
   </td>
   <td>

<p id="gdcalert29" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image29.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert30">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image29.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Realizar un estudio previo a la etapa de codificación para evaluación
   </td>
  </tr>
  <tr>
   <td>R018
   </td>
   <td>Alcance de las pruebas no definido completamente
   </td>
   <td>2
   </td>
   <td>2
   </td>
   <td>

<p id="gdcalert30" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image30.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert31">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image30.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R019
   </td>
   <td>Doc. de requisitos insuficiente para pruebas 
   </td>
   <td>2
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert31" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image31.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert32">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image31.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Realizar los documentos teóricos en tiempo y forma para el posterior uso
   </td>
  </tr>
  <tr>
   <td>R020
   </td>
   <td>Realizar pruebas en ambiente desarrollo 
   </td>
   <td>2
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert32" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image32.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert33">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image32.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Contar con etapa de pruebas en ambiente destinado para este propósito
   </td>
  </tr>
  <tr>
   <td>R021
   </td>
   <td>No se realiza completitud en las pruebas
   </td>
   <td>3
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert33" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image33.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert34">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image33.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Buena planificación para poder cumplir con la misma de la mejor manera
   </td>
  </tr>
  <tr>
   <td>R022
   </td>
   <td>No se realiza priorización en ejecución de pruebas 
   </td>
   <td>2
   </td>
   <td>2
   </td>
   <td>

<p id="gdcalert34" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image34.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert35">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image34.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R023
   </td>
   <td>Doc. escasa sobre el uso de la aplicación
   </td>
   <td>2
   </td>
   <td>1
   </td>
   <td>

<p id="gdcalert35" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image35.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert36">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image35.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Aceptar y monitorear
   </td>
  </tr>
  <tr>
   <td>R024
   </td>
   <td>Vulnerabilidades presentes en producción
   </td>
   <td>3
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert36" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image36.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert37">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image36.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Capacitar al equipo en temas de seguridad y aplicar este ambiente
   </td>
  </tr>
  <tr>
   <td>R025
   </td>
   <td>Contiene errores cuando se entrega al cliente
   </td>
   <td>2
   </td>
   <td>4
   </td>
   <td>

<p id="gdcalert37" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image37.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert38">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image37.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Estudiar los entregables y someterlos a pruebas antes de entregar
   </td>
  </tr>
  <tr>
   <td>R026
   </td>
   <td>Presentación de defectos en ambiente producción
   </td>
   <td>3
   </td>
   <td>5
   </td>
   <td>

<p id="gdcalert38" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image38.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert39">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image38.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Optimizar procesos de testing y reporte de bugs para evitar fallos en producción
   </td>
  </tr>
  <tr>
   <td>R027
   </td>
   <td>Mal cálculo del presupuesto
   </td>
   <td>4
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert39" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image39.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert40">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image39.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Documentar ante posibles variaciones en el mismo
   </td>
  </tr>
  <tr>
   <td>R028
   </td>
   <td>Pérdida de datos
   </td>
   <td>4
   </td>
   <td>5
   </td>
   <td>

<p id="gdcalert40" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image40.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert41">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image40.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Sólida política de respaldos y alta disponibilidad
   </td>
  </tr>
  <tr>
   <td>R029
   </td>
   <td>Seleccion erronea de herramientas
   </td>
   <td>2
   </td>
   <td>3
   </td>
   <td>

<p id="gdcalert41" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image41.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert42">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image41.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Realizar estudio previo y seleccionar aquellas que resulten idóneas
   </td>
  </tr>
  <tr>
   <td>R030
   </td>
   <td>No tener conocimiento adecuado en cloud
   </td>
   <td>3
   </td>
   <td>2
   </td>
   <td>

<p id="gdcalert42" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image42.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert43">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image42.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>Mitigar. Capacitar al equipo en este tema y certificar en el proveedor seleccionado
   </td>
  </tr>
</table>


En la figura siguiente (figura 6) se muestra la matriz frecuencia-impacto en forma de mapa de calor, generado con la herramienta Pirani <sup>21</sup>, en donde se representan la cantidad de riesgos ubicados en las zonas correspondientes en base a los atributos antes mencionados.

Figura 11. Matriz de riesgos frecuencia-impacto.

Fuente: [https://appweb.pirani.co/reports/#/dashboard](https://appweb.pirani.co/reports/#/dashboard)** <sup>21</sup>**



        9. Costos

La estimación de costos en el campo de la Ingeniería del Software es una tarea fundamental que requiere una atención meticulosa. Este proceso desempeña un papel crucial para establecer una estrategia efectiva que aborde los aspectos relacionados con el esfuerzo, el costo y el tiempo asociados a las actividades de un proyecto de desarrollo de software.

Los valores presentados en la tabla de costos (tabla 5) reflejan los costos actuales del mercado y están respaldados por el cronograma previamente establecido. Además, se ha asignado un margen de reserva de contingencia del 5% para abordar posibles riesgos conocidos y garantizar la continuidad exitosa de los objetivos del proyecto.

A continuación se presenta un resumen categorizado para proporcionar una vista general de los costos agrupados por tipo.



* **Costos de Infraestructura (Subtotal: USD 8.799,00):**
    * Alquiler de Oficina: USD 1.875,00 (3 meses)
    * Consumo Eléctrico: USD 270,00 (3 meses)
    * Computadoras Personales: USD 6.000,00 (3 unidades)
    * Servicio de Internet: USD 150,00 (3 meses)
    * Gastos Comunes: USD 300,00 (3 meses)
    * Licenciamiento Windows: USD 204,00 (3 unidades)
* **Costos de Servicios en la Nube (Cloud Services) (Subtotal: USD 1.105,56):**
    * Almacenamiento AWS S3: USD 147,45 (3 meses)
    * AWS CloudFront: USD 160,50 (3 meses)
    * AWS Lambda: USD 156,00 (3 meses)
    * AWS API Gateway: USD 105,00 (3 meses)
    * AWS DynamoDB: USD 156,42 (3 meses)
    * AWS CloudWatch: USD 130,77 (3 meses)
    * AWS Cognito: USD 87,75 (3 meses)
    * AWS Textract: USD 13,50 (3 meses)
    * Google Cloud Jenkins Server: USD 148,17 (3 meses)
* **Costos de Desarrollo y Personal (Subtotal: USD 40.083,00):**
    * Costo Backend (BackEnd dev.): USD 12.000,00 (400 horas)
    * Costo Frontend (FrontEnd dev.): USD 9.200,00 (368 horas)
    * Costo Arquitectura (SW Architect): USD 4.560,00 (114 horas)
    * Costo Datos (Data Scientist): USD 3.686,00 (97 horas)
    * Costo Despliegue (DevSecOps): USD 5.842,00 (127 horas)
    * Costo Pruebas (QA Automation): USD 4.795,00 (137 horas)

**Subtotal de Costos: USD 49.987,56**

**Reserva de Contingencia (5%): USD 2.499,40**

**Total de Costos: USD 52.486,96**

Tabla 5. Costos.


<table>
  <tr>
   <td><strong>Concepto</strong>
   </td>
   <td><strong>Tipo costo</strong>
   </td>
   <td><p style="text-align: right">
<strong>Costo unitario/hora</strong></p>

   </td>
   <td><p style="text-align: right">
<strong>Cantidad</strong></p>

   </td>
   <td><p style="text-align: right">
<strong>Total</strong></p>

   </td>
   <td><p style="text-align: right">
<strong>Detalle</strong></p>

   </td>
  </tr>
  <tr>
   <td>Alquiler de oficina
   </td>
   <td>Fijo indirecto
   </td>
   <td><p style="text-align: right">
USD 625,00</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 1.875,00</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>Consumo eléctrico
   </td>
   <td>Fijo indirecto
   </td>
   <td><p style="text-align: right">
USD 90,00</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 270,00</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>Computadoras personales
   </td>
   <td>Fijo directo
   </td>
   <td><p style="text-align: right">
USD 2.000,00</p>

   </td>
   <td><p style="text-align: right">
3 units</p>

   </td>
   <td><p style="text-align: right">
USD 6.000,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Servicio Internet
   </td>
   <td>Fijo directo
   </td>
   <td><p style="text-align: right">
USD 50,00</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 150,00</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>Gastos Comunes
   </td>
   <td>Fijo indirecto
   </td>
   <td><p style="text-align: right">
USD 100,00</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 300,00</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>Licenciamiento Windows
   </td>
   <td>Fijo directo
   </td>
   <td><p style="text-align: right">
USD 68,00</p>

   </td>
   <td><p style="text-align: right">
3 units</p>

   </td>
   <td><p style="text-align: right">
USD 204,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Almacenamiento AWS S3 **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 49,15</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 147,45</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS CloudFront **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 53,50</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 160,50</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS Lambda **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 52,00</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 156,00</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS API Gateway **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 35,00</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 105,00</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS DynamoDB **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 52,14</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 156,42</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS CloudWatch **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 43,59</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 130,77</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS Cognito **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 29,25</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 87,75</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>AWS Textract **
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 4,50</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 13,50</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>Google Cloud Jenkins Server **
   </td>
   <td>Fijo directo
   </td>
   <td><p style="text-align: right">
USD 49,39</p>

   </td>
   <td><p style="text-align: right">
3 meses</p>

   </td>
   <td><p style="text-align: right">
USD 148,17</p>

   </td>
   <td><p style="text-align: right">
Mensual</p>

   </td>
  </tr>
  <tr>
   <td>Costo Backend (BackEnd dev.) *
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 30,00</p>

   </td>
   <td><p style="text-align: right">
400 hs.</p>

   </td>
   <td><p style="text-align: right">
USD 12.000,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Costo Frontend (FrontEnd dev.) *
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 25,00</p>

   </td>
   <td><p style="text-align: right">
368 hs.</p>

   </td>
   <td><p style="text-align: right">
USD 9.200,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Costo Arquitectura (SW Architect) *
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 40,00</p>

   </td>
   <td><p style="text-align: right">
114 hs.</p>

   </td>
   <td><p style="text-align: right">
USD 4.560,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Costo Datos (Data Scientist) *
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 38,00</p>

   </td>
   <td><p style="text-align: right">
97 hs.</p>

   </td>
   <td><p style="text-align: right">
USD 3.686,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Costo Despliegue (DevSecOps) * 
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 46,00</p>

   </td>
   <td><p style="text-align: right">
127 hs.</p>

   </td>
   <td><p style="text-align: right">
USD 5.842,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>Costo Pruebas (QA Automation) *
   </td>
   <td>Variable directo
   </td>
   <td><p style="text-align: right">
USD 35,00</p>

   </td>
   <td><p style="text-align: right">
137 hs.</p>

   </td>
   <td><p style="text-align: right">
USD 4.795,00</p>

   </td>
   <td><p style="text-align: right">
Total</p>

   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="3" >Sub Total
   </td>
   <td><p style="text-align: right">
1243 hs.</p>

   </td>
   <td colspan="2" ><p style="text-align: right">
 USD 49.987,56</p>

   </td>
  </tr>
  <tr>
   <td colspan="3" >Reserva de contingencia
   </td>
   <td><p style="text-align: right">
5%</p>

   </td>
   <td colspan="2" ><p style="text-align: right">
USD 2.499,40</p>

   </td>
  </tr>
  <tr>
   <td colspan="3" ><strong>TOTAL</strong>
   </td>
   <td>
   </td>
   <td colspan="2" ><p style="text-align: right">
<strong>USD 52.486,96</strong></p>

   </td>
  </tr>
</table>


Fuente: Elaboración propia

* Costo Desarrollo: 3 integrantes x 3 meses de 25 jornales cada uno x aproximadamente 6 horas diarias de labor. Total horas: 1243, las cuales dividimos en las tareas/roles que vamos a realizar.

 Los costos fueron calculados por períodos de tres meses, ya que es el tiempo que contaremos para el desarrollo completo del proyecto. Se llegó a este número por la duración del semestre que será poco menos de 4 meses, a esto restado las semanas de capacitación en las nuevas tecnologías a utilizar para poder comenzar el desarrollo con suficientes conocimientos.


### 



            1. Detalle de costos
* **Alquiler de oficina**: contabilizaremos este gasto solo durante el proceso de desarrollo de la aplicación, de ser necesario extender este gasto se analizará cuando corresponda.
* **Consumo eléctrico**: consumo promedio teniendo en cuenta los posibles artefactos electrónicos en la oficina, computadoras, iluminación, aire acondicionado, entre otros.
* **Computadoras personales**: se le proporcionará a los desarrolladores los insumos necesarios para realizar su trabajo.
* **Servicio Internet**: tarifa de internet correspondiente a fibra óptica de velocidad acorde a las necesidades.
* **Gastos Comunes**: gastos inherentes al alquiler del inmueble, con servicios necesarios para el desarrollo del proyecto.
* **Licenciamiento Windows**: claves digitales a obtener de cualquiera de los principales e-commerce.
* **Almacenamiento AWS S3**: servicio a contratar para almacenamiento de grandes volúmenes de datos para su posterior análisis, así como el alojamiento del backend y frontend de la aplicación y los archivos subidos por los usuarios.
* **AWS CloudFront**: tarifa para levantar el frontend de nuestra aplicación y distribuir su contenido a usuarios finales con baja latencia y una gran velocidad de transferencia. 
* **AWS Lambda**: servicio para ejecutar el código como respuesta a eventos y se administran los recursos informáticos de manera automática.
* **AWS API Gateway**: servicio para mantener la API de nuestra aplicación, a través de ella serán llamadas las funciones Lambda.
* **AWS DynamoDB**: Base de datos NoSQL para el almacenamiento de los datos.
* **AWS CloudWatch**: Servicio para monitorización de los recursos de la infraestructura.
* **AWS Cognito**: Servicio para control de acceso, inicio de sesión y registro de los usuarios a nuestra aplicación web.
* **AWS Textract**: Servicio de aprendizaje automático para extraer texto de documentos escaneados. En nuestro caso se utilizó para la verificación del documento.
* **Google Cloud Jenkins Server**: Instancia virtual del tipo e2-standard-2 con Jenkins y demás software necesario para automatizar la pipeline del frontend y backend.
* **Costo Backend**: aquí están estimados los costos y las horas que llevará el desarrollo de los servicios de backend asociados a las funcionalidades de nuestra aplicación(backend de: registro de viaje, buscar viaje, validar usuarios, login, entre otros. Detallados por sprint en el Gantt).
* **Costo Frontend**: están estimados los costos y las horas que llevará el desarrollo de los servicios de frontend asociados a las funcionalidades de nuestra aplicación (landing page, registro de usuario, buscar viajes, entre otros. Detallados por sprint en el Gantt).
* **Costo Arquitectura**: estos costos se relacionan directamente con la arquitectura y estructuración de nuestro aplicativo en la nube, comunicación entre módulos, funcionalidades, etc
* **Costo Datos**: costos asociados al almacenamiento y análisis de grandes cantidades de datos para su posterior apoyo en la toma de decisiones.
* **Costo Despliegue**: aquí se especifica el costo de despliegue y monitorización de la aplicación y cuestiones relacionadas a la seguridad informática.
* **Costo Pruebas**: costo asociado al análisis y planificación del área de pruebas, a lo largo de todo el ciclo de vida del proyecto se ejecutarán las mismas en cada sprint.
        10. **Plan de Calidad**
                1. Propósito

El propósito de este plan es especificar cómo el plan de de la calidad va a ser implementado durante el proceso de desarrollo del software. 

Este plan describe las actividades a realizar por el equipo de QA y define un conjunto de estándares a seguir para asegurar la calidad del proyecto.



                2. Gestión
                    1. Actividades

**Ciclos de vida de nuevos desarrollos implicados en el plan**

Las etapas más importantes del ciclo de vida cubiertos son el relevamiento de requerimientos, el análisis de metodologías a utilizar, la etapa de diseño dado y analizado por las diferentes áreas, y las revisiones de la calidad del producto en proceso y una vez finalizado el mismo; comprendiendo un ciclo de mejora continua. 

Los productos del proyecto a analizar serán todo entregable según el modelo de proceso seleccionado. En tanto deben comprenderse los mínimos entregables para poder cuantificar la calidad, en los siguientes:



*  Especificación de Requerimientos
*  Definición de diseño – Metodología aplicable
*  Descripción de la Arquitectura y Alcance – bordes y límites
*  Plan de Verificación de los productos
*  Plan de revisión de productos

**Actividades de calidad a realizarse**

Las tareas a ser llevadas a cabo deberán reflejar las evaluaciones finales, los estándares a seguir, los productos a revisar, los procedimientos a seguir en la elaboración de los distintos productos y los procedimientos para informar de los defectos detectados a sus responsables y realizar el seguimiento de los mismos hasta su corrección.

Las actividades que se realizarán son:



*  Revisar cada producto
*  Revisar el ajuste al proceso
*  Asegurar que las desviaciones son documentadas
*  Presentar las métricas y desvíos compartiendo los resultados
*  Aplicar las medidas correctivas correspondientes

**Revisar cada producto**

En esta actividad se revisan los productos que se definieron como claves para verificar en el Plan de calidad. 

Se debe verificar que no queden correcciones sin resolver en los informes de revisión previos, si se encuentra alguna no resuelta, debe ser incluida en la siguiente revisión como inicio y detallados en el Plan de riesgos. 

Se revisan los productos contra los estándares  determinados, utilizando la checklist definida para el producto. 

Se debe identificar y documentar las desviaciones encontradas y verificar que se hayan realizado las correcciones. 

Como salida se obtiene el Informe de revisión. Este informe debe ser distribuido a los responsables del producto y se debe asegurar de que son conscientes de desviaciones o discrepancias encontradas.

**Revisar el ajuste al proceso**

En esta actividad se revisan los productos que se definieron como claves para verificar el cumplimiento de las actividades definidas en el proceso. Con el fin de asegurar la calidad en el producto final del desarrollo, se deben llevar a cabo revisiones sobre los productos durante todo el ciclo de vida del producto.

Se debe recoger la información necesaria de cada producto, buscando hacia atrás los productos previos que deberían haberse generado, para poder establecer los criterios de revisión y evaluar si el producto cumple con las especificaciones definidas.

Esta información se obtiene de los siguientes documentos: 

Plan del Proyecto y Plan de Verificación.

Antes de comenzar, se debe verificar en los informes de revisión previos que todas las desviaciones fueron corregidas, si no es así, las faltantes se incluyen para ser evaluadas.

Como salida se obtiene el Informe de revisión correspondiente a la evaluación de ajuste al Proceso, este informe debe ser distribuido a los responsables de las actividades y se debe asegurar de que son conscientes de desviaciones o discrepancias encontradas.

**Asegurar que las desviaciones son documentadas**

En esta actividad se revisan las desviaciones que han sido encontradas, tanto para productos previos relacionados como así también los detectados al momento de finalizar cada revisión. La documentación de las desviaciones debe ser compartida y presentadas en cada proyecto de manera de poder ser informadas y distribuidas de manera que todos los participantes tengan conocimientos y puedan observar la falta de cumplimiento de las actividades definidas.

Previo a comenzar un proyecto, debe revisar las previas desviaciones y realizar las actividades correctivas en busca de mejorar o no comprometer con más desviaciones

ya detectadas el nuevo producto.

Como salida se obtiene un Informe con las posibles desviaciones, tanto incluidas las anteriores como las nuevas y determinar el avance en este respecto.

**Presentar las métricas y desvíos compartiendo los resultados**

En esta actividad se debe presentar los indicadores de calidad y de desvíos siguiendo el cronograma estipulado para el proyecto.

Es importante que se presenten de forma clara, manteniendo la objetividad numérica. Estos instrumentos serán la entrada a los reportes de calidad seleccionados para cada proyecto, en donde se definen los equipos de trabajo y las responsabilidades de cada uno.

Cada proyecto debe determinar un ciclo de presentación de estos documentos para ir observando el avance y los desvíos, y en el caso, realizar reuniones donde se ajustarán o revisarán los procedimientos para poder encontrar las causales de desvíos si los hubiese. Luego en el plan de seguimiento del proyecto se deben incluir las reuniones y las minutas tomadas.

**Aplicar las medidas correctivas correspondientes**

Siguiendo el plan de mejora, las métricas presentadas, los posibles desvíos, es necesario revisar los objetivos centrales y llevar a cabo las medidas necesarias para corregir las desviaciones encontradas.

Estas deben ser documentadas ya que se utilizarán como entrada para nuevos proyectos evolutivos de anteriores, como así también los que puedan interactuar, definiendo de esta manera una base de partida para la evolución y mejora continua.

Puede ser necesario revisar la correctitud de la metodología definida para el proyecto como así también decisiones no bien tomadas, o la falta de las mismas. Toda medida correctiva debe ser correctamente documentada e informada, impactando en la documentación ya realizada en el proyecto si esta existiese.



                    2. Responsables
*  Project Manager (PM)
*  Líder de QA
*  Líder de Arquitectura
*  Gerencia de Proyecto
*  Los definidos en el Plan de Proyecto
                3. Modelo de Calidad

Se utilizará la norma ISO/IEC 25010 como modelo de calidad en torno a la cual se establecerá un marco de trabajo para la evaluación de la calidad de los productos. En este modelo se determinan las características de calidad que se van a tener en cuenta a la hora de evaluar las propiedades de los productos de software a desarrollar. 

El modelo de calidad del producto definido por la ISO/IEC 25010 se encuentra compuesto por 8 características de calidad. A partir de estas, se deberán definir las métricas a tener en cuenta como requerimientos de calidad del producto a construir que tienen incidencia sobre la calidad.

Figura 12. Características ISO/IEC 25010

Fuente: [https://iso25000.com/index.php/normas-iso-25000/iso-25010](https://iso25000.com/index.php/normas-iso-25000/iso-25010)<sup>17</sup>



                4. Documentación
                    3. Propósito

Identificación de la documentación relativa al desarrollo, verificación y validación, uso y mantenimiento del software. 

Establecer como los documentos van a ser revisados para chequear consistencia: se confirman criterios e identificación de las revisiones.

**Especificaciones de Requerimientos del Software**

El documento de especificación de requerimientos deberá describir, de forma clara y precisa, cada uno de los requerimientos esenciales del software además de las interfaces externas. 

El cliente deberá obtener como resultado del proyecto una especificación adecuada a sus necesidades en el área de alcance del proyecto, de acuerdo al compromiso inicial del trabajo y a los cambios que este haya sufrido a lo largo del proyecto, que cubra aquellos aspectos que se haya acordado detallar. 

La especificación debe: 



* Ser completa. 
* Ser consistente, no pueden haber elementos contradictorios. 
* No ser ambiguo, todo término referido al área de aplicación debe estar definido en un glosario. 
* Ser verificable, debe ser posible verificar si el producto final cumple o no con cada requerimiento. 
* Incluir requerimientos de calidad del producto a construir.

**Descripción del Diseño del Software**

El documento de diseño especifica como el software será construido para satisfacer los requerimientos. 

Deberá describir los componentes y subcomponentes del diseño del software, incluyendo interfaces internas. 

Como resultado del proyecto, se obtendrá el diseño de un producto de software que cubra aquellos aspectos que se haya acordado incorporar al diseño, en función de la importancia que estos presenten y de sus conexiones lógicas. 

El diseño debe: 



* Corresponder a los requerimientos a incorporar: 
    * Todo elemento del diseño debe contribuir a algún requerimiento 
    * La implementación de todo requerimiento a incorporar debe estar contemplada en por lo menos un elemento del diseño. 
* Ser consistente con la calidad del producto

**Plan de Verificación y Validación**

El Plan deberá identificar y describir los métodos a ser utilizados en la verificación de que los requerimientos descritos en el documento de requerimientos han sido aprobados por una autoridad apropiada. 

Se deberá verificar que:



* Los requerimientos descritos en el documento de requerimientos son implementados en el diseño expresado en el documento de diseño.
* El diseño expresado en el documento de diseño está implementado en código.
* Validar que el código, cuando es ejecutado, se adecua a los requerimientos expresados en el documento de requerimientos.

**Reportes de Verificación y Validación**

Estos documentos deben especificar los resultados de la ejecución de los procesos descritos en el Plan de verificación y validación.

**Documentación de Usuario**

La documentación de usuario debe especificar y describir los datos y entradas de control requeridos, así como la secuencia de entradas, opciones, limitaciones de programa y otros elementos necesarios para la ejecución exitosa del software. 

Todos los errores deben ser identificados y las acciones correctivas descritas. 

Como resultado del proyecto el cliente obtendrá una documentación para el usuario de acuerdo a los requerimientos específicos del proyecto.

**Plan de Gestión de Configuración**

Se deberá identificar componentes de software, control e implementación de cambios, registro y reporte del estado de los cambios implementados.



                5. Estándares, prácticas, convenciones y métricas

**Estandares de documentacion**

Como estándares de documentación se definirán dos documentos:



* Estándar de documentación técnica y
* Estándar de documentación de usuario.

La documentación técnica del producto debe:



* Ser adecuada para que un grupo independiente de desarrollo pueda encarar el mantenimiento del producto.
* Incluir fuentes, Modelos de Casos de Uso, Objetos.

Para la escritura de documentos se han definido plantillas para ser utilizadas en la elaboración de entregables.

En estas plantillas se definen:



* Encabezados y pie de página.
* Fuente y tamaño de fuente para estilo normal
* Fuente y tamaño de fuente para los títulos y subtítulos a utilizar 
* Datos mínimos que se deben incluir: fecha, versión y responsables.
                6. Revisión y auditorías

El equipo debe analizar y evaluar los datos y la información obtenida por el seguimiento, la medición y otras fuentes. Los resultados del análisis y la evaluación deben utilizarse para: 



* Demostrar que los productos y servicios ofrecidos están acorde a los requerimientos de los clientes.  
* Evaluar y aumentar la satisfacción del cliente.  
* Asegurarse de la conformidad y eficacia del sistema de gestión de calidad.  
* Demostrar que lo planificado se ha implementado de forma exitosa.  
* Evaluar el desempeño de los procesos.  
* Evaluar el desempeño de los proveedores.  
* Determinar la necesidad de oportunidades de mejora dentro del sistema de gestión de la calidad. 

**Objetivos**

Estos resultados del análisis y la evaluación tienen como objetivo proporcionar elementos que sirvan como base, en el proceso de la revisión realizada por la dirección. Como novedad, este apartado de la norma incluye el ítem de “demostrar que lo planificado se ha implementado de forma exitosa” Para ello, se debe analizar la eficacia de las acciones tomadas en el informe de la dirección.

**Requerimientos mínimos**

1.	Revisión de requerimientos

Esta revisión se realiza para asegurar que se cumplió con los requerimientos especificados por el Cliente.

2.	Revisión de diseño preliminar

Esta revisión se realiza para asegurar la consistencia y suficiencia técnica del diseño preliminar del software.

3.	Revisión de diseño crítico

Esta revisión se realiza para asegurar la consistencia del diseño detallado con la especificación de requerimientos.

4.	Revisión del Plan de Verificación & Validación

Esta revisión se realiza para asegurar la consistencia y completitud de los métodos especificados en el Plan de V & V.

5.	Auditoría funcional

Esta auditoría se realiza previa a la liberación del software, para verificar que todos los requerimientos especificados en el documento de requerimientos fueron cumplidos.

6.	Auditoría física

Esta revisión se realiza para verificar que el software y la documentación son consistentes y están aptos para la liberación.

7.	Auditorías internas al proceso

Estas auditorías son para verificar la consistencia del código versus el documento de diseño, especificaciones de interfaz, implementaciones de diseño versus requerimientos funcionales, requerimientos funcionales versus descripciones de testeo.

8.	Revisiones de gestión

Estas revisiones se realizan periódicamente para asegurar la ejecución de todas las actividades identificadas en este Plan. Deben realizarse por una persona ajena al grupo de trabajo (en caso de que sea posible).

9.	Revisión del Plan de gestión de configuración

Esta revisión se realiza para asegurar la consistencia y completitud de los métodos especificados en el Plan de gestión de configuración.

10. 	Revisión Post Mortem

Esta revisión se realiza al concluir el proyecto para especificar las actividades de desarrollo implementadas durante el proyecto y para proveer recomendaciones.



                7. Reporte de Problemas
* No se toman mediciones de calidad en el sentido amplio.
* Solo se invertirá en las áreas de Proyectos y Soporte a Usuarios.
* No se utiliza un correcto versionado de las liberaciones que realizan. 
* No se realizan mediciones de ninguna índole, a la hora de dar seguimiento al proyecto.
* Se comienzan a sentir reclamos por parte de los usuarios de la calidad resultante de cada proyecto.
* No se utiliza la potencialidad de las herramientas de QA.
* En infraestructura, restan definir elementos para monitorear.  
* No se dispone de información si cumple o no con lo pactado, a la hora de monitorear los servicios externos contratados.
* A la hora de registrar un incidente, la información que se registra es básica.
* Los usuarios están disconformes con los servicios ya que la resolución nunca llega a tiempo.
                8. Herramientas y Metodologías

**Herramientas**

Las herramientas que utilizaremos para medir la calidad del software son:

Diagramas de flujo.- También denominados mapas de procesos, porque muestran la secuencia de pasos (utiliza símbolos y las posibilidades de ramificaciones que existen en un proceso que transforma una o más entradas en una o más salidas.

Hojas de verificación.- También conocidas como hojas de control, es una herramienta estructurada, por lo general específica de cada componente, que se utiliza para verificar que se hayan llevado a cabo una serie de pasos necesarios.

Jira, AIO Test. Para la gestión de pruebas de software y registro de defectos.

Testim. Para la automatización de pruebas de software.

K6. Para las pruebas de performance de la infraestructura.

**Metodología**

La metodología a ser utilizada para el plan de gestión de la calidad será SCRUM, de esta aseguraremos un producto resultante de calidad, ayudando a evitar varios reclamos por parte de los usuarios.



                9. Gestión de Riesgos

En la sección de riesgos se realizará  la identificación y análisis de los riesgos en base al documento presentado. Se definirán las probabilidades e impactos de los riesgos para realizar el análisis cualitativo, así como también indicar las acciones para mitigarlos. 

Los riesgos detectados se presentarán en una tabla con el análisis de los riesgos identificados, su categorización y la lista de supuestos o asunciones que se realizaron durante el análisis. 

La gestión de los riesgos se lleva a cabo en la plataforma Pirani para la cual contamos con una licencia, en ella se detallan cada uno de los riesgos identificados, así como también las estrategias para tratar con cada uno de ellos(estrategias, eventos, planes de acción, controles, disparadores, etc).



                10. Indicadores

Se presentan los indicadores que se consideran de importancia y aportan valor al negocio y la calidad del mismo.

Tabla 6. Indicadores de calidad.


<table>
  <tr>
   <td><strong>Id Indicador</strong>
   </td>
   <td><strong>Nombre de Indicador</strong>
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>Porcentaje de Disminución de Defectos (%DD)
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>Grado de Eficacia en Eliminación de Defectos (EED)
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>Grado de Validación de los Requerimientos (VR)
   </td>
  </tr>
  <tr>
   <td>5
   </td>
   <td>Porcentaje de Usuarios Finales Satisfechos (%SUF)
   </td>
  </tr>
  <tr>
   <td>6
   </td>
   <td>Porcentaje de incidencias ingresadas (%IR)
   </td>
  </tr>
  <tr>
   <td>7
   </td>
   <td>Tiempo promedio de resolución de incidencias (TPir)
   </td>
  </tr>
  <tr>
   <td>8
   </td>
   <td>Horas-Programador diarias (HPD)
   </td>
  </tr>
  <tr>
   <td>9
   </td>
   <td>Horas-Programador totales (HPT)
   </td>
  </tr>
  <tr>
   <td>10
   </td>
   <td>Coste por Hora-Programador, en unidades monetarias (CHP)
   </td>
  </tr>
  <tr>
   <td>11
   </td>
   <td>Coste total actual del proyecto, en unidades monetarias (CTP)
   </td>
  </tr>
  <tr>
   <td>14
   </td>
   <td>Líneas de código fuente escritas (LCF)
   </td>
  </tr>
  <tr>
   <td>15
   </td>
   <td>Líneas de código fuente por hora de programador (LCFH)
   </td>
  </tr>
  <tr>
   <td>16
   </td>
   <td>Coste por línea de código fuente (CLCF)
   </td>
  </tr>
  <tr>
   <td>17
   </td>
   <td>Productividad de los programadores (PROD)
   </td>
  </tr>
  <tr>
   <td>19
   </td>
   <td>Tasa de éxito de la meta del sprint (TES)
   </td>
  </tr>
  <tr>
   <td>20
   </td>
   <td>Fiabilidad, disponibilidad y capacidad de servicio (RAS)
   </td>
  </tr>
  <tr>
   <td>21
   </td>
   <td>Porcentaje de incidencias críticas ingresadas (%IRC)
   </td>
  </tr>
</table>


Fuente: Elaboración propia



5. 
ARQUITECTURA
Desarrollaremos una aplicación serverless, por lo que no nos centraremos en la administración de los servidores y sus recursos, sino que delegamos dicha responsabilidad a nuestro proveedor, en este caso AWS.

Se optó por este tipo de arquitectura por varios beneficios que brinda, como por ejemplo lo antes mencionado, no se administran los servidores ni infraestructura, esto acompaña al siguiente beneficio, que es la escalabilidad automática; no hay costos de contratación, ya que solo se paga por lo que se usa; mayor seguridad y fiabilidad al contar con un proveedor como es AWS.

Es decir, podremos desplegar una aplicación web con una infraestructura sólida sin invertir demasiado en ésta última y pagando solamente por lo que se utilice.



    9. Aplicación

La arquitectura de la aplicación desarrollada se basa en una arquitectura en capas siguiendo el patrón de arquitectura MVC, en donde se utilizan distintos servicios de AWS en cada una de ellas, así como la utilización del patrón DTO para la comunicación entre la capa de presentación y de aplicación.

Figura 13. Diagrama de arquitectura con tecnologías utilizadas.



<p id="gdcalert43" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image43.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert44">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image43.png "image_tooltip")


Fuente: Elaboración propia.

Los servicios básicos de AWS para una aplicación serverless son:



* **S3**: servicio donde se alojarán archivos estáticos, como imágenes, html, css, JavaScript, etc.
* **Cognito**: servicio de autenticación, autorización y administración de usuarios.
* **API Gateway**: servicio que disparará las peticiones HTTP las cuales invocarán a las funciones Lambda.
* **Lambda**: servicio para el desarrollo de las funciones, cada función consistirá en una funcionalidad.
* **DynamoDB**: servicio de base de datos NoSQL para almacenar la información necesaria. En caso que sea necesario guardar una imagen, se guardará la ruta de S3 en donde está ubicada la misma.



Figura 14. Diagrama de arquitectura con servicios AWS y GCP.



<p id="gdcalert44" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image44.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert45">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image44.png "image_tooltip")


Fuente: Elaboración propia

En la arquitectura diseñada se realizan cinco pasos principales, los cuales se describen a continuación.



1. Se obtienen los recursos estáticos del FrontEnd.
2. El usuario accede al FrontEnd a través del servicio CloudFront.
3. El usuario solicita autenticación / Cognito devuelve token si la autenticación fue exitosa.
4. El usuario realiza alguna actividad a través de CloudFront llamando a la API, la cual es la encargada de invocar a la función Lambda correspondiente a la funcionalidad necesaria para completar la acción.
5. La función Lambda solicita o guarda datos en DynamoDB o, en el caso de funciones particulares, guarda un objeto en S3 o utiliza un servicio especial de AWS.
6. Como extra contamos con CloudWatch para los registros y métricas, las cuales llevarán seguimiento de todos los servicios utilizados.



    10. 
DevOps
Figura 15. Diagrama de pipeline CI/CD.



<p id="gdcalert45" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image45.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert46">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image45.png "image_tooltip")


Fuente: Elaboración propia



    11. 
Base de datos
DynamoDB es una base de datos no relacional del tipo clave-valor, por lo que su diseño es muy flexible y adaptable a la realidad de cada negocio.

DynamoDB ofrece la posibilidad de diseñar la arquitectura de la base de datos de dos maneras distintas, en una tabla o en varias tablas. En nuestro caso se trabajó en el diseño de una tabla, separando las entidades por la clave principal.

En la figura a continuación se muestra el diseño de la tabla con datos de ejemplo.


        Figura 16. Diseño de la tabla de ejemplo.



<p id="gdcalert46" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image46.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert47">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image46.png "image_tooltip")


A su vez, este servicio ofrece la posibilidad de crear índices totalmente personalizables, lo que facilita la búsqueda de registros, así ahorrando en gran medida costos y tiempo al buscar en gran cantidad de datos.

En nuestro diseño se crearon cuatro índices para diferentes finalidades, por origen - destino, por tipo, por vehículo - usuario y por tripId.


        Figura 17. Índices en DynamoDB.



<p id="gdcalert47" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image47.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert48">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image47.png "image_tooltip")


En las figuras a continuación se muestran los resultados obtenidos al buscar por los índices antes mencionados.


        Figura 18. Búsqueda por índice origen-destino.



<p id="gdcalert48" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image48.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert49">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image48.png "image_tooltip")



        Figura 19. Búsqueda por índice tipo.



<p id="gdcalert49" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image49.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert50">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image49.png "image_tooltip")



        Figura 20. Búsqueda por índice vehículo-usuario.



<p id="gdcalert50" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image50.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert51">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image50.png "image_tooltip")



        Figura 21. Búsqueda por índice por tripId.



<p id="gdcalert51" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image51.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert52">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image51.png "image_tooltip")



        Herramienta utilizada: https://rh-web-bucket.s3.amazonaws.com/index.html <sup>18</sup>



6. 
TESTING Y QA


    12. Estrategia

Esta sección describe las definiciones adoptadas y la ejecución de pruebas realizadas por el equipo con el objetivo de evaluar la calidad del producto.

Desde un comienzo la perspectiva de calidad estuvo presente durante todo el ciclo de vida del proyecto, ya que en la planificación de las funcionalidades a desarrollar, se planificaba su correspondiente esfuerzo por parte del diseño y ejecución de las pruebas.



    13. Herramientas de apoyo

**Postman**

Postman es una aplicación que nos permite testear APIs a través de una interfaz gráfica de usuario. Entre las ventajas que tiene Postman encontramos la capacidad de crear colecciones y distintos ambientes de pruebas. Es una herramienta fácil de usar que nos ayuda a optimizar el tiempo de ejecución de pruebas.

Herramienta que hemos utilizado a lo largo de todo el ciclo de desarrollo, ya que nos permite no solo testear nuestras APIs Rest y evaluar las respuestas que nos retorna AWS, sino que también la hemos utilizado para la generación de datos, a los efectos de poblar nuestras bases de datos, lo cual nos es de importancia para ejecutar otros tipos de pruebas.

**AIO Test**

Es un Plugin de Jira, el cual nos permite gestionar de forma integral el ciclo de vida de los casos de prueba, hecha a medida para los equipos modernos de control de calidad. Las organizaciones pueden simplificar sus actividades de gestión de pruebas sin perder tiempo.

Luego de evaluar varias herramientas, nos inclinamos por esta ya que aparte de todas sus funcionalidades, para equipos pequeños, de nuestro tamaño, es totalmente gratis. Algunas de sus principales ventajas son: nuclear todo el ciclo de vida de desarrollo y pruebas en la misma aplicación. Los incidentes se registran dentro de Jira, las vinculaciones con las historias de usuario se dan de manera natural. El flujo de trabajo es más llevadero con estas herramientas integradas entre sí. que utilizando herramientas separadas.

**Pirani**

Software que permite gestionar riesgos operativos de forma simple. Con Pirani podremos mapear los procesos, identificar riesgos y establecer controles y planes de acción para mitigarlos.

Luego de evaluar varias herramientas, nos inclinamos por esta ya que aparte de todas sus funcionalidades, logramos obtener una licencia de uso por todo el periodo que dura el proyecto. Esta plataforma la hemos utilizado no solo para el registro y seguimiento de los riesgos detectados, sino también para priorizar los mismos y en base a ello diseñar casos de pruebas más específicos a los efectos de controlar mejor aquellos riesgos de alto nivel.

**k6**

Es un software de código abierto, una aplicación hecha en JavaScript, diseñada para cargar, probar el comportamiento funcional y medir el rendimiento. Originalmente fue diseñado para probar aplicaciones web, pero desde entonces se ha expandido a otras funciones de prueba.

Lo utilizamos para someter a nuestras APIs a distintos tipos de pruebas de rendimiento, como pueden ser de estabilidad o estrés, entre otras.

**AWS**

Los servicios de aws nos permiten monitorear las pruebas ejecutadas mediante jMeter y ver cómo impactan en nuestros servidores, también lo utilizamos para la verificación de las pruebas end to end y validar en las bases de datos los datos almacenados durante estas pruebas.

**Testim**

Testim es una plataforma de automatización de pruebas integral y gratuita para pruebas web, móviles y de API que cuenta con el respaldo de una gran comunidad

Para la ejecución de pruebas automatizadas seleccionamos esta reciente herramienta ya que entre otras cosas ofrece la posibilidad de crear tests de forma codeless, entre otras ventajas por sobre otras herramientas como lo son selenium por ejemplo.



    14. Tipos de Pruebas

A continuación se describen los tipos de actividades realizadas, su justificación, en qué

momento ocurrieron y los resultados obtenidos.

**Pruebas Unitarias**

Realizadas por el desarrollador. Una vez que el desarrollador considera que ha realizado suficientes pruebas unitarias, la funcionalidad estaba lista para el testing funcional.

**Pruebas Funcionales**

Realizadas por el tester, a partir de una entrada o acción se verifica que la salida de información o comportamiento de la aplicación es el esperado. El responsable de realizar cada prueba funcional fue una persona distinta a la que desarrolló la funcionalidad, a los efectos de evitar posibles sesgos.

**Pruebas de integración**

Realizadas por el tester, cada vez que se libera una funcionalidad, se prueba el funcionamiento en conjunto con otras funcionalidades con el objetivo de identificar comportamientos no deseados.

**Pruebas de carga**

Realizadas por el tester, utilizadas para probar las funcionalidades de nuestras APIs, proporcionada por el Backend, con el objetivo de verificar cómo responde la aplicación en caso de un grán número de usuarios concurrentes. 

**Pruebas automatizadas**

Realizadas por el tester, con la integración de DevOps y la realización de despliegues automatizados se incluyó la ejecución de pruebas automatizadas para evaluar la calidad del código de la aplicación. Estas pruebas nos permiten ahorrar tiempo de ejecución a la hora de ejecutar pruebas de regresión.

**Pruebas de humo**

Realizadas por el tester. Utilizadas frecuentemente, en dichas pruebas se realizaban revisiones rápidas de la solución con el objetivo de una evaluación inicial del producto.

**Pruebas de extremo a extremo**

Es una metodología que comprueba el funcionamiento de toda una aplicación, de principio a fin, por ello, se le conoce como pruebas de extremo a extremo o pruebas end-to-end (e2e). Las pruebas e2e garantizan que el flujo de una aplicación funcione como se esperaría ante la interacción de un usuario real.

**Pruebas no funcionales**

Las pruebas no funcionales son un tipo de prueba para verificar el área de aplicación no funcional en términos de rendimiento, confiabilidad, eficiencia, UX, UI, etc.



    15. Ejecución

Tal como hemos definido en la planificación, durante todos los sprints se diseñaron y ejecutaron pruebas, distintos tipos de ellas dependiendo el avance de las funcionalidades y del proyecto en sí. Las pruebas unitarias, de integración, funcionales y de humo se ejecutaron en todos los sprints. Previo a la finalización de cada sprint se liberaron para testear las funcionalidades comprendidas en el mismo y habiendo realizado el diseño de los casos de prueba. Además de los casos previstos para las pruebas, los responsables de los testeos ejecutaban las pruebas y reportaban los defectos encontrados juntos a los aspectos de mejora que identificaron.



7. BIBLIOGRAFÍA
1. Transporte público. (9 de junio de 2022). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Transporte_p%C3%BAblico&oldid=144092122](https://es.wikipedia.org/w/index.php?title=Transporte_p%C3%BAblico&oldid=144092122)
2. Carpooling. (15 de enero de 2022). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Veh%C3%ADculo_compartido&oldid=140970635](https://es.wikipedia.org/w/index.php?title=Veh%C3%ADculo_compartido&oldid=140970635)
3. CO2. (19 de agosto de 2022). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Di%C3%B3xido_de_carbono&oldid=145454146](https://es.wikipedia.org/w/index.php?title=Di%C3%B3xido_de_carbono&oldid=145454146)
4. Aplicación web. (1 de septiembre de 2022). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Aplicaci%C3%B3n_web&oldid=145698860](https://es.wikipedia.org/w/index.php?title=Aplicaci%C3%B3n_web&oldid=145698860)
5. Costos de pasajes en Uruguay. Urubus. (2022). Urubus Tus pasajes online. [Aplicación Web] [https://www.urubus.com.uy/es/](https://www.urubus.com.uy/es/)
6. AWS, Amazon Web Services. ([https://aws.amazon.com/es/](https://aws.amazon.com/es/))
7. IDE. (18 de febrero de 2022). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Entorno_de_desarrollo_integrado&oldid=141766211](https://es.wikipedia.org/w/index.php?title=Entorno_de_desarrollo_integrado&oldid=141766211)
8. NodeJS. (25 de agosto de 2022). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Node.js&oldid=145586811](https://es.wikipedia.org/w/index.php?title=Node.js&oldid=145586811)
9. Jenkins. (12 de diciembre de 2021). En Wikipedia. [https://es.wikipedia.org/w/index.php?title=Jenkins&oldid=140303097](https://es.wikipedia.org/w/index.php?title=Jenkins&oldid=140303097)
10. José Samar. (17 de febrero de 2018). Carpooling (I): ¿Qué son, cómo surgieron y cómo funcionan?. [https://movilidadconectada.com/2018/02/17/carpooling-i-que-son-como-surgieron-y-como-funcionan/](https://movilidadconectada.com/2018/02/17/carpooling-i-que-son-como-surgieron-y-como-funcionan/)
11. Hoop Solutions. (2019). HoopCarpool [Aplicación web]. [https://hoopcarpool.com/](https://hoopcarpool.com/)
12. STS Rosario. (Recuperado el 9 de septiembre de 2022). Carpoolear [Aplicación web]. [https://carpoolear.com.ar/](https://carpoolear.com.ar/)
13. BlaBlaCar. (2022). BlaBlaCar [Aplicación web]. [https://www.blablacar.es/](https://www.blablacar.es/)
14. Carpoolea. (2016). Carpoolea [Página Web]. [http://carpoolea.com/](http://carpoolea.com/)
15. VoyADedo [@voyadedo]. (s.f.). Cuenta oficial VoyADedo. Twitter. [https://twitter.com/voyadedo?lang=es](https://twitter.com/voyadedo?lang=es)
16. Viatik. (2022). Viatik [Aplicación web]. [https://www.viatik.com.uy/](https://www.viatik.com.uy/)
17. Planttext. (s.f.). Planttext. [Aplicación web]. https://www.planttext.com/  
18. PlantUML. (s.f.). C4-PlantUML. Recuperado de https://github.com/plantuml-stdlib/C4-PlantUML  
19. Vivanco, J. (2019, 14 de mayo). El modelo C4 de documentación para la arquitectura de software. Medium. https://medium.com/@javiervivanco/el-modelo-c4-de-documentaci%C3%B3n-para-la-arquitectura-de-software-424704528390
20. ISO/IEC 25010. (s.f.). [https://iso25000.com/index.php/normas-iso-25000/iso-25010](https://iso25000.com/index.php/normas-iso-25000/iso-25010)
21. Amazon DynamoDB Data Modeler. (s.f.). Amazon DynamoDB Data Modeler. [Aplicación Web]. https://rh-web-bucket.s3.amazonaws.com/index.html
22. Usama Naseem, Arun Gupta, and Salman Paracha. (14 de octubre de 2019). How AWS built a production service using serverless technologies. [https://aws.amazon.com/es/blogs/opensource/real-world-serverless-application/](https://aws.amazon.com/es/blogs/opensource/real-world-serverless-application/)
23. Online Gantt. (s.f.). Free Online Gantt Chart Software. [Aplicación Web]. [https://www.onlinegantt.com/](https://www.onlinegantt.com/)
24. Pirani. (s.f.). Software de Gestión de Riesgos Empresariales [Aplicación Web] [https://appweb.pirani.co/](https://appweb.pirani.co/)
25. Atlassian. (s. f.). Flujo de trabajo de Gitflow | Atlassian Git Tutorial. [https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow](https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow)
26. Priorización de proyectos. (2016). [http://www.juansimo.com/del-plan-estrategico-al-programa-de-proyectos-la-tactica-priorizacion-de-proyectos/](http://www.juansimo.com/del-plan-estrategico-al-programa-de-proyectos-la-tactica-priorizacion-de-proyectos/)
27. Branching con GitFlow, GitLab Flow, OneFlow y GitHub Flow. (2021, 6 octubre). OpenWebinars.net. [https://openwebinars.net/blog/estrategias-de-branching-gitflow-gitlab-flow-oneflow-github-flow/](https://openwebinars.net/blog/estrategias-de-branching-gitflow-gitlab-flow-oneflow-github-flow/)
28. AWS Products. (2022). Productos en la nube de AWS. [Aplicación web]. [https://aws.amazon.com/es/products/](https://aws.amazon.com/es/products/)
29. AWS Pricing calculator. (2022). AWS Pricing calculator. [Aplicación web]. [https://calculator.aws/](https://calculator.aws/)
30. Stefano Stasuzzo. (17 de noviembre de 2020). Designing Serverless Web Applications with Amazon Web Services. [https://medium.com/quantyca/designing-serverless-web-applications-with-amazon-web-services-1ccad3099d91](https://medium.com/quantyca/designing-serverless-web-applications-with-amazon-web-services-1ccad3099d91)
31. Google Cloud Platform Console. (2022). [Aplicación web]. [https://console.cloud.google.com/](https://console.cloud.google.com/)
32. Getting Started with k6. [Aplicación Web] 

<span style="text-decoration:underline;">https://k6.io/docs/</span>



33. Testim documentation. [Aplicación Web]

    [https://www.testim.io/resources/](https://www.testim.io/resources/)

34. PlantUML. (s.f.). Activity diagram beta. [Diagrama de actividades]. [https://plantuml.com/es/activity-diagram-beta](https://plantuml.com/es/activity-diagram-beta)
35. PlantUML. (s.f.). Activity diagram legacy. [Diagrama de actividades]. https://plantuml.com/es/activity-diagram-legacy