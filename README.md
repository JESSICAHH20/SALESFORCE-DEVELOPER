<h1 align="center">
Salesforce-Developer <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="50">
</h1>

¡Hola<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">!, mi nombre es Jessica Hernández Hernández egresada de la carrera en Ingeniería en Tecnologías de la Información 💻 estoy en el interes de poner en practica mis aprendizajes,habilidades y de la misma forma de aprender dentro de la parte laboral junto con nuevas experiencias y entronos de desarrollo:rocket:.Es por ello que a continuación presento mi resolución a la paractica Salesforce- Developer. 
<br>
<br>
## 👨‍💻 Instalación del ambiente
### IDE Visual Studio Code  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/800px-Visual_Studio_Code_1.35_icon.svg.png" width="20">
1. Descargar https://code.visualstudio.com/docs/?dv=win64user o https://code.visualstudio.com/docs/?dv=win32user
2. Abra o descomprima el archivo y arrastre la aplicación a la carpeta `Aplicaciones`.
3. Haga doble clic sobre el instalador de Visual Studio Code para poner en marcha el asistente de instalación.
4. La primera pantalla exige aceptar la licencia de Visual Studio Code para continuar la instalación.
5. La segunda pantalla permite elegir el directorio de instalación (por tratarse de la versión User installer, el directorio de instalación está en la carpeta de usuario, no en Archivos de programa).
6. La tercera pantalla permite elegir el nombre de la carpeta del menú de inicio.
7. La cuarta pantalla permite elegir algunas tareas adicionales tras la instalación. Personalmente, aconsejo marcar las casillas "Agregar la acción ...".
8. Finalmente se muestran las opciones elegidas en las pantallas anteriores. Para iniciar la instalación, haga clic en Instalar.
9. A continuación, se instalará Visual Studio Code.
10. Una vez completada la instalación, se muestra la pantalla final. Si va a utilizar Git con Visual Studio Code, desmarque la casilla "Ejecutar Visual Studio Code", haga clic en Finalizar e instale Git.
11. ¡Listo! 
### GIT y GIT Bash <img src="https://vidabytes.com/wp-content/uploads/2021/09/Que-es-git-1.png" width="50"> <img src="https://quesignificaelerror.com/wp-content/uploads/2021/03/%C2%BFQue-es-Git-Bash-y-como-instalarlo-en-Windows.jpg" width="50">
1. Descarga el instalador de GIT para Windows en https://gitforwindows.org/.
2. Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla. Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación.
3. Ahora tienes que abrir el símbolo de sistema y escribir los siguientes comandos en la terminal:
```sh
git config --global user.name "Tu nombre"
git config --global user.email "ejemplo@email.com"
```
## 👨‍💻 Ejercicio 2
### HTTP.
Actualmente un servidor HTTP *(HyperText Transfer Protocol)* es conocido también como un servidor web, donde es posible alojar un sitio web o en otros casos cualquier tipo de archivos. Los verbos más conocidos son *Get, (Read), Post (Crear), Put (Actualizar), y Delete (Eliminar)*. Dentro del HTTP se encuentra el request denominado asi a la acción de enviar una petición al servidor, mientras que el *Response*, es la respuesta por parte del servidor, solicitada antes en el *request*. Considerando que dentro de esto estan los *headers*, encargados de describir el contenido del *response*. 
<br>
### queryString y Método GET y POST.
Un *queryString* es muy importante dentro de una url, ya que sin ellas sería imposible buscar ciertas url dentro de internet y no se podrían crear portales personalizables. Un *responseCode* permite visualizar el estado de nuestro response por ejemplo HTTP/1.1 301 movido permanentemente, significa que el recurso requerido fue movido permanentemente y redirigido a otro recurso. El método *GET* lleva los datos de forma "visible" al cliente (navegador web). El medio de envío es la URL y los datos los puede ver cualquiera. Mientras que el método *POST* consiste en datos "ocultos" (porque el cliente no los ve) enviados por un formulario cuyo método de envío es post. Es adecuado para formularios. Los datos no son visibles. Al utilizar el navegador cuando accedemos a una página web se está utilizando el método GET ya que es en base a una URL.
<br>
### Estructura JSON y XML
Las estructuras de la parte de JSON es más que nada enfocada a tener un ordenamiento de código y buena visualización. 
<br>
Ejemplo:
```sh
{
    “pieza”: {
        “tipo”: “A”
        “nombre”: “Tornillo”,
        “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
        “caracteristica”: {
            “tipo”: “metal”
            “tamanyo”: 10
        },
        “vacio”: “”
     }
}
```
Mientras que la parte de XML proporciona un dato menos ordenado, teniendo una visualización lineal. 
<br>
Ejemplo:
```sh
<pieza tipo="A">
    <nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras 
    </descripcion>
    <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
    </caracateristica>
    <vacio></vacio>
</pieza>
```
### Estandar SOAP Y REST FULL
REST, que es el acrónimo de Representational State Transfer. A diferencia de SOAP, más que un protocolo es una definición de arquitectura se donde nos indica cómo realizar el intercambio y manejo de datos a través de servicios web. A aquellos servicios web que siguen su definición se les conocen como RESTful Web services. El SOAP (Simple Object Access Protocol), es un protocolo que nos permitirá realizar servicios web sin estado, a través de TCP y con un formato XML.
<br>
El Content-Type es la propiedad de cabecera (header) usada para indicar el  media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado
## 👨‍💻 Ejercicio 3
### GET 
1.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![image](https://user-images.githubusercontent.com/67445610/151291547-c97763a7-1ccf-4854-8e69-2021dc97dd8a.png)
### POST
2.	Realizar un request POST a la URL anterior, y con body:
![image](https://user-images.githubusercontent.com/67445610/151291682-26ceb662-646d-4888-abc0-ed9ac47f94ee.png)
3. Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![image](https://user-images.githubusercontent.com/67445610/151291841-fd58a7d8-b028-406c-be4f-0b9c86fde3e9.png)
<br>
Las diferencias observadas dentro del primer GET es que solo extrajo la información que contenia el HTTP, mientras que al generar el POST en el HTTP este permitio poder realizar la inserción de un nuevo dato, que después de ejecutar un GET por segunda vez este lo mostro de forma correcta.

## 👨‍💻 Ejercicio 4
## 👨‍💻 Ejercicio 5
1.	Lead es un potencial cliente que demostró interés en un producto o servicio 
2.	Account almacenar información acerca de clientes o personas individuales con las que hace negocios.
3.	Contact permite identificar la relación entre las cuentas disponibles y el contacto.
4.	Opportunity son acuerdos en curso Los registros de oportunidad realizan un seguimiento de detalles acerca de acuerdos, incluyendo para qué cuentas son, quiénes son las personas implicadas y las cantidades de las ventas potenciales. 
5.	Product aquellos encargados de innovar el negocio.
6.	PriceBook es la lista maestra de todos sus productos y sus precios estándar predeterminados.
7.	Quote representan los precios propuestos de los productos y servicios de su empresa. Usted crea una cotización a partir de una oportunidad y sus productos. 
8.	Asset representan los productos específicos que sus clientes han comprado. 
9.	Case para ver cómo afectan el proceso de ventas. Responder a los casos mantiene contentos a sus clientes y mejora su marca.
10.	Article son aquellos elementos indispensables para el negocio.
#### Diagrama


## 👨‍💻 Ejercicio 6
### Soluciones de Salesforce  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Salesforce.com_logo.svg/1200px-Salesforce.com_logo.svg.png" width="40">
A.	¿Qué es Salesforce? Es una solución de gestión de relaciones con clientes que une empresas y clientes. Es una plataforma CRM integrada que brinda a todos tus departamentos, incluidos marketing, ventas, comercio y servicios, una vista única y compartida de cada cliente.
<br>
B.	¿Qué es Sales Cloud?
Herramienta de ventas personalizable, versátil y poderosa que te permitirá hacer un seguimiento de tus contactos y crear reportes en tiempo real.
<br>
C.	¿Qué es Service Cloud? La Plataforma de Servicio al Cliente Personalizable, Ágil y Potente
<br>
D.	¿Qué es Health Cloud? Desbloquea datos de sistemas heredados de registros y sistemas clínicos, y brinda a los profesionales de la salud las herramientas que necesitan para colaborar de manera más eficiente, comprender mejor a los pacientes y construir relaciones 1 a 1 a lo largo de recorridos completos.
<br>
E.	¿Qué es Marketing Cloud? Herramienta para construir estrategias de Marketing Automatizadas y personalizadas. Y sabiendo utilizarla al máximo, las opciones son innumerables y permite transformar por completo la forma de hacer campañas para ser más eficientes y eficaces. 
<br>
### Funcionalidades de Salesforce
A.	¿Qué es un RecordType? Esta palabra clave especifica el tipo de informe. Es obligatoria y el valor debe definirse en WebForm para que el archivo se cargue como script de formulario de datos.
<br>
B.	¿Qué es un Page Layout? Definida como una página de diseño.
<br>
C.	¿Qué es un Compact Layout? Un diseño compacto muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.
<br>
D.	¿Qué es un Perfil? Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación. Cuando cree usuarios, asigne un perfil a cada uno.
<br>
E.	¿Qué es un Rol? Los roles controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. Usuarios en cualquier función dada pueden ver, editar, e informar sobre todos los datos para funciones por debajo de ellos en la jerarquía de roles.
<br>
F.	¿Qué es un Validation Rule?Las reglas de validación verifican que los datos ingresados ​​por los usuarios en los registros cumplan con los estándares que usted especifique antes de que puedan guardarlos. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y devuelve un valor de "Verdadero" o "Falso".
<br>
G.	¿Qué diferencia hay entre una relación Master Detail y Lookup? Puede convertir una relación principal-detalle en una relación de búsqueda siempre que no existan campos de resumen acumulados en el objeto principal.
<br>
H.	¿Qué es un Sandbox? Un sandbox es un mecanismo de seguridad para disponer de un entorno aislado del resto del sistema operativo.
<br>
I.	¿Qué es un ChangeSet? Software de control de versiones, un conjunto de cambios es un conjunto de confirmaciones recopiladas formalmente que deben tratarse como un grupo.
<br>
J.	¿Para qué sirve el import Wizard de Salesforce? acilita la importación de datos para muchos objetos estándar de Salesforce, incluidas cuentas, contactos, clientes potenciales, soluciones, miembros de campaña y cuentas personales. También puede importar datos para objetos personalizados.
<br>
K.	¿Para qué sirve la funcionalidad Web to Lead? Web-to-Lead es una función incorporada de Salesforce que permite al propietario del sitio recopilar hasta 500 clientes potenciales por día con los datos de prospección de los visitantes del sitio web de su empresa. 
<br>
L.	¿Para qué sirve la funcionalidad Web to Case? Sirve para recopilar las solicitudes de servicio de atención al cliente directamente del sitio web de su compañía y genere automáticamente casos nuevos con Caso Web. 
<br>
M.	¿Para qué sirve la funcionalidad Omnichannel? OmniCanal toma los elementos de trabajo entrantes y los enruta a los agentes de asistencia más cualificados y disponibles empleando los criterios de enrutamiento que defina.
<br>
N.	¿Para qué sirve la funcionalidad Chatter? Chatter es la red social empresarial de la Plataforma EGA Futura, destinada a facilitar el trabajo colaborativo y la comunicación asincrónica en toda la organización. Esta red atraviesa la totalidad de la plataforma, se encuentra en todas las aplicaciones, está disponible también en la aplicación móvil. 

### Conceptos generales
A.	¿Qué significa SaaS? Software as a Service, es una forma de poner. a disposición softwares y soluciones de tecnología por medio de la internet, como un servicio.
<br>
B.	¿Salesforce es Saas? Si
<br>
C.	¿Qué significa que una solución sea Cloud? Es una solución con la integración de la infraestructura del internet y de tecnología.
<br>
D.	¿Qué significa que una solución sea On-Premise? Las infraestructuras on-premise son aquellas que se guardan y ejecutan en local en los servidores de las propias empresas.
<br>
E.	¿Qué es un pipeline de ventas? Es el sistema que produce una fuente de oportunidades comerciales de calidad para que un equipo pueda convertirlas en clientes reales y así incrementar las ganancias de la empresa. 
<br>
F.	¿Qué es un funnel de ventas? Es una representación gráfica del "camino" o las etapas por las que pasa un usuario en su proceso para convertirse en tu cliente.
<br>
G.	¿Qué significa Customer Experience? El Customer Experience es una de las disciplinas estratégicas más importantes a valorar en una compañía. Puede generar un valor a las empresas que eleve sus datos de ventas y consumidores.
<br>
H.	¿Qué significa omnicanalidad? La estrategia omnicanal es un concepto que en los últimos años se ha difundido ampliamente en el mundo del mercadeo.
<br>
I.	¿Qué significa que un negocio sea B2B?¿Qué es un KPI?
El B2B es un modelo de negocio que consiste en los servicios que una compañía entrega a otra con el objetivo de mejorar las ventas de los productos y bienes que ofrece.Un KPI (Key Performance Indicator) es, dicho de un modo sencillo, un indicador de medida que sirve para controlar la evolución de un proceso en relación a los objetivos de un proyecto.
<br>
J.	¿Qué es una API y en qué se diferencia de una Rest API? La API puede emplear cualquier método de comunicación. Por lo general, si se trata de una llamada a sistema, se emplean interrupciones de la API del Kernel de Linux.
<br>
K.	¿Qué es un Proceso Batch? El procesamiento batch o por lotes es el proceso mediante el cual una computadora completa lotes de trabajos, a menudo simultáneamente, en orden secuencial y sin parar. 
<br>
L.	¿Qué es Kanban? La palabra Kanban viene del japonés y traducida literalmente quiere decir tarjeta con signos o señal visual.
<br>
M.	¿Qué es un ERP? Un ERP (siglas de ‘Enterprise Resource Planning’ o ‘Planificación de Recursos Empresariales’) es un conjunto de aplicaciones de software integradas, que nos permiten automatizar la mayoría de las prácticas de negocio relacionadas con los aspectos operativos o productivos.
<br>
N.	¿Salesforce es un ERP? Si

## 👨‍💻 Ejercicio 7
A.	Consultar tu ID haciendo un GET con POSTMAN a este WS:
![image](https://user-images.githubusercontent.com/67445610/151289856-2e06db04-4b98-4675-bb11-9c0c30fa2feb.png)


<h4 align="center">A desktop menubar app based on <a href="http://electron.atom.io" target="_blank">Electron</a>.</h4>

