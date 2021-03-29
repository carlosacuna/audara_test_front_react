# TEST REACT AUDARA

_Prueba básica para desarrollador FrontEnd React 16.*._


## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósito de la prueba._


### Pre-requisitos 📋

* [Nodejs v10.* o superiores](https://nodejs.org/es/)
* [Git](https://git-scm.com/)
* [Github](https://github.com/)



### Instalación 🔧

_Clona el proyecto en tu máquina local para iniciar la prueba._

```
git clone https://github.com/roncertain/audara_v5_CA.git
```

_Si deseas descargarlo directamente puedes ingresar al siguiente link [https://github.com/roncertain/audara_v5_CA](https://github.com/roncertain/audara_v5_CA)._

_Una vez el proyecto esté en tu máquina es necesario instalar las dependencias que se encuentran en el archivo ``package.json`` y lo puedes hacer con el siguiente comando en tu terminal._

```
npm install
```


### Despliegue 🛫

_La prueba esta elaborada en react create app._

_Ya estamos listos para iniciar el proyecto, para encenderlo en modo desarrollo es necesario ejecutar en la terminal el siguiente comando._

```
npm run start
```



_Si todo esta bien, ya estarás listo para iniciar la prueba!!. ☕🤓_



### Tareas a realizar en la prueba 📄

_La prueba está diseñada para no ser necesario instalar nuevas librerias en lo posible._

_En el archivo ``src/App.js`` encontraras las rutas de los componentes que debes trabajar. El test tiene incluida la libreria de React Router para que no tengas que preocuparte por las rutas, solo dedicate a realizar los componentes._

_En el directorio ``src/components`` encontraras las carpetas de los componentes que debes realizar._

*  1.Count Down timer: Es necesario crear un componente que realice el llamado a una API para obtener el current timestamp unix, a esa fecha se le deben agregar 20 segundos y después se debe comenzar un conteo regresivo hasta llegar a 00:00:00. Cuando la cantidad de segundos agregados den 00:00:00 debes marcar el timer down en rojo y se comenzará a incrementar el tiempo. 
Te recomendamos utilizar ``http://worldtimeapi.org/`` con el timezone de Bogotá Colombia. 
En el timer solo deben aparecer Horas:Minutos:segundos.

*  2.Multi select Storage: Debes crear 3 ``<select>`` con valores por defecto diferentes, cada select debe tener los mismo 5 options que están en estados global. Cada vez que se seleccione una opción del select se deben guardar en localstorage y si se refresca la página y existen valores guardados en storage se deben tomar por defecto, de lo contrario debe tomar los valores antes establecidos. También se debe tener un botón para borrar el storage de todos los selects.

*  3.Load CSV table: En el directorio ``csv/`` encontrarás un archivo ``testCSVTable`.csv`` el cual debes cargar en el sistema y crear una ``<tabla>`` con los datos contenidos. 
La fila 1 son los títulos de las columnas. En cada titulo de columna ``<th>`` debes agregar un checkboxs para seleccionar la columna. 
En la fila número 2 debes agregar un select para seleccionar el tipo de dato que contiene la columna, los tipos de opciones que se pueden seleccionar son (Name, Email, Phone, Address). 
También debes crear un botón  debajo de la tabla donde se debe hacer un console log con las columnas seleccionadas con check. Por defecto el botón debe estar oculto hasta que en algunas columnas se seleccionen los tipos Name  y phone.




### Una vez realizada la prueba ✅

_Crea un repositorio publico en [Github](https://github.com/) con tus respuestas._

_Envía el link del repositorio antes mencionado al mismo correo electrónico de donde te enviaron la prueba._


### Te deseamos mucha suerte 🍀🍀⭐
