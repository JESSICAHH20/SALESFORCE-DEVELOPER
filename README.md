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
![image](https://user-images.githubusercontent.com/67445610/151274676-0807dc5e-2e37-4fa3-ac4a-5fcb074b6175.png)
### POST
2.	Realizar un request POST a la URL anterior, y con body:
![image](https://user-images.githubusercontent.com/67445610/151275362-ab3ef430-cbc2-44b9-a60e-f50d4d950310.png)
3. Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
![image](https://user-images.githubusercontent.com/67445610/151275607-b8ed95d0-cebe-4bad-a7aa-3f1216936db6.png)
<br>
Las diferencias observadas dentro del primer GET es que solo extrajo la información que contenia el HTTP, mientras que al generar el POST en el HTTP este permitio poder realizar la inserción de un nuevo dato, que después de ejecutar un GET por segunda vez este lo mostro de forma correcta.

## 👨‍💻 Ejercicio 4
## 👨‍💻 Ejercicio 5
## 👨‍💻 Ejercicio 6

<h4 align="center">A desktop menubar app based on <a href="http://electron.atom.io" target="_blank">Electron</a>.</h4>

