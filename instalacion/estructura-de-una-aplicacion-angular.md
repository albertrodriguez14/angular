# Estructura de una aplicación Angular

Una vez generada y comprobada la ejecución, toca estudiar cómo es la estructura de la aplicación. Para ello revisa carpeta a carpeta. Las malas noticias son que hay **una enorme cantidad de ficheros y carpetas**, las buenas son que como verás, casi todo es **configuración e infraestructura**.

### 3.1 Visual Studio Code <a id="3-1-Visual-Studio-Code"></a>

Para ver y editar los ficheros te vale cualquier editor de código, pero yo uso y te recomiendo VSCode. Es un **gran editor, gratuito y multiplataforma**. Viene con un terminal integrado y puedes mejorarlo instalando extensiones desde una galería del propio editor.

Te recomiendo instalar un paquete de extensiones ya configurado y preparado para el desarrollo de aplicaciones con _Angular_, se llama Angular Essentials. Con eso y el Material Icon Theme verás _Angular en colores_.

### 3.2 Carpetas y Ficheros principales <a id="3-2-Carpetas-y-Ficheros-principales"></a>

Volviendo a la **estructura de ficheros y carpetas** te encontrarás con muchos archivos de distintos tipos. Si eres completamente nuevo en Angular, te llamará la atención las extensiones `.ts`. Son para ficheros _TypeScript_, una evolución del _JavaScript_ con facilidades para el programador. Por ahora sólo tienes que familiarizarte con estos:

* **angular.json** _: configuración del propio CLI. La madre de todos los configuradores_
* **package.json** _: dependencias de librerías y scripts_
* **src/** _: la carpeta donde están los archivos fuentes_
  * **index.html** _: un fichero HTML índice estándar_
  * **main.ts** _: fichero TypeScript de arranque de la aplicación_
  * **app/** _: la carpeta con el código específico de tu aplicación_
    * **app.module.ts** _: la aplicación es un árbol de módulos, y este es su raíz_
    * **app.component.ts** _: la página es un árbol de componentes, y este es su raíz_
    * **app.component.html** _: tiene una parte visual, esta es su vista_

Echa un vistazo a estos ficheros, pronto los modificaremos para sentirnos programadores.

