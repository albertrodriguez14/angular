# Crear un aplicación

## Crear y ejecutar una aplicación Angular 9 <a id="2-Crear-y-ejecutar-una-aplicacion-Angular-9"></a>

Una vez que hayas instalado el CLI de manera global ya puedes empezar a usarlo en tu directorio de trabajo. El primer comando será `ng new` que te va a **generar toda una aplicación funcional** y las configuraciones necesarias para su depuración, pruebas y ejecución.

Como novedad, en las últimas versiones, el CLI te preguntará por algunas opciones para crear tu aplicación. Eso es porque no todos los desarrollos son iguales. Se puede configurar el tipo, el estilo y muchas más cosas, tanto de forma interactiva como mediante opciones en línea de comandos.

Lo más habitual es usar la configuración que viene por defecto, pero también se pueden crear soluciones a medida. Te muestro unos ejemplos para que pruebes y te familiarices con la herramienta. Para más información mira la documentación del comando [ng new](https://angular.io/cli/new).

### Básica <a id="2-1-Basica"></a>

```text
ng new unaAppMuyCorriente
cd unaAppMuyCorriente
npm start
```

primero nos ubicamos en el directorio que estará alojado el proyecto

![](../.gitbook/assets/image%20%283%29.png)

![preguntara si el proyecto se agregara rutas le respondes  que si Y](../.gitbook/assets/image%20%284%29.png)

![despues pregunta si los archivo de estilo sera css o sass escoger una de las opciones ](../.gitbook/assets/image%20%285%29.png)

![](../.gitbook/assets/image%20%286%29.png)

para correr el serve nos dirigimos al directorio del proyecto con la consola y ejecutamos ng serve.

### 2.2 Minimalista <a id="2-2-Minimalista"></a>

```text
ng new minimalista -s -S -t
cd minimalista
npm start
```

### 2.3 Profesional <a id="2-3-Profesional"></a>

```text
ng new profesional -p acme --routing true
cd profesional
npm start
```

### 2.4 Empresarial <a id="2-4-Empresarial"></a>

```text
ng new empresarial --create-application false
cd empresarial
ng generate application compras -p acme --routing true
npm start
```

Una vez finalizada la instalación de todas las librerías necesarias puedes bajar a la carpeta recién creada y ejecutar el comando standard de _npm_ para el arranque de cualquier aplicación: `npm start`. Si todo va bien, en unos segundo podrás visitar [http://localhost:4000](http://localhost:4000/) para ver en marcha la aplicación. Lo veremos con más detalle en el apartado de configuración.

