# matriz
examen tecnico handcloud

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "Proyletras.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.


examen tecnico..

es un ejecutable jar. en la siguiente direccion
Proyletras\dist\Proyletras.jar

se ha hecho un vector de capacidad 10
con 10 caja de texto para que el usuario teclee las palabras que desea en listar

hay 3 listas.
la lista de en medio se llenara cuando el usuario haya llenado las cajas de texto con sus 10 respectivas palabas
dandole en el boton de llenar lista.

en la parte izquiera y derecha son el ordenamiento ascendente y descendente dandole clic en el boton de ordenar 
