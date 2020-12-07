# UNIVERSIDAD CENTROAMERICANA
# “JOSÉ SIMEÓN CAÑAS”
 
## FACULTAD DE INGENIERÍA Y ARQUITECTURA

[Pagina Oficial](http://www.uca.edu.sv/)
 
## FULL STACK WEB COURSE
### LEO SOLORZANO
 
## FECHA: MARTES 20 DE OCTUBRE DE 2020


## Planeación

### Objetivo
-- Crear una página web para un curso, poseerá la funcionalidad de poder mostrar, agregar, quitar y buscar la información de los usuarios, partidas entre estudiantes y modificar los perfiles, utilizando las tecnologías HTML, CSS/SASS JS, Bootstrap, entre otros.


-- Mantener un trabajo en equipo, cooperativo y motivador al resolver problemas y/o diseñar código

### Instrucciones para Correr el Proyecto

~~~
Para la Creación de React Page
~~~

#### Se hace el uso de los siguientes comandos:
~~~
Deben de seguirse en ese mismo orden
~~~

* npx create-react-app github-proyecto-p --template cra-template-pwa
* cd github-proyecto-p
* git status
* git log
* code .
* npm install -g serve
* serve -s build
* npm install curl
* npm install styled-components
* npm run build
* serve -s build

~~~
En este caso el proyecto ya esta finalizado
Para provarlo solo debe ejecuta `npm i` y `npm start` :D
~~~

# 

~~~
Para Backend WEB
~~~

### Variables de entorno:
PORT=3001
MONGO_URI=mongodb+srv://Diego:temp_password@minidashboard-db-test.wugdf.mongodb.net/MiniDashboard-DB-Test?retryWrites=true&w=majority
DEBUG=mini-dashboard-backend:* 
JWT_SECRET=@@asdfghrtyu2345@@!!cnscjkdb

#### Se hace el uso de los siguientes comandos:
~~~
Deben de seguirse en ese mismo orden
~~~

* npm i express-generator -g
* express -h
* express --git --no-view proyecto-p
* cd proyecto-p
* ls
* code .
* npm i
* npm start
* `DEBUG=proyecto-p:* npm start`
* npm install nodemon -D
* Añadir en los scripts de package.json `"start-dev": "nodemon./bin/www`
* npm run start: dev
* npm install dotenv
* npm install cors
* npm install mongoose --save
* npm install jsonwebtoken express-jwt

~~~
En este caso el proyecto ya esta finalizado
Para provarlo solo debe ejecuta `npm i` y `npm run start: dev` :D
~~~

### DEMO
Video de YouTube que contiene: 
`
* Una breve introduccion del proyecto
* La presentacion del grupo
* Una Demo de: Categoría de Juego y Categoría Administrativa
`
[Link del Video:](#)

### Consideraciones
* El editor de texto de Visual Studio Code
* Y los recursos de, Bootstrap, Github-Project 
* Esto no sería posible sin la ayuda de MDN, W3, StackOverflow, Google, CSS-TRICKS.

### WORKFLOW
-- La división del trabajo será crear mockups de las vistas y hacer la estructura HTML, luego se creara el estilo de las vistas usando Bootstrap, al final se le dará funcionalidad a las vistas con el uso de JavaScript y React.

### La estructura primordial del proyecto será:
* CSS
* IMG
* JS
* LIB
* PRIVATE
* PUBLIC
* SASS
* HTML
* PACKAGE.JSON

### Descripción
--La página iniciara con una vista de todas las mesas.


--En el Navbar se encontrará además de las mesas, un enlace para ajustes, estadísticas, usuarios y mi perfil. En donde cada página tendra un funcionamiento distinto.


--Cada página permite guardar cambios o mostrar datos para los usuarios. Tambien se podrán modificar las caracteristicas de la pagina. Y generar un mantenimiento de usuarios. Realizar la jugada, mostrar las mesas y sus distintas descripciones de acuerdo al juego. 


--Por último, en cada página se encuentra el Footer, con información importante de todos los eventos que se imparten por Project Management Institute Educational Foundation.