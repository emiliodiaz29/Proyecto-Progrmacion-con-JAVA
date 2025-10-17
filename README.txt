Para todos los archvos.java que se adjuntan es necesario compilarlos a traves del javac Nombredeldocumento.java
Después para ver el funcionamiento correcto de las clases Mensaje y Contestadora se adjuntan las pruebas: PruebaMensaje.java y PruebaContestadora.java que son las que se pueden ejecutar mediante el java PruebaMensaje y el java PruebaContestadora respectivamente, para ver como funcionan. 
*********************************************************************************

PruebaMensaje.java
El archivo PruebaMensaje.java es un programa que para ser utilizado
debera ser compilado mediante el javac PruebaMensaje.java para que una vez que se cree el archivo.class se pueda correr el programa mediante java PruebaMensaje.
El programa es una clase main que usa la clase Mensaje.java que crea una nueva instancia de la clase Mensaje a traves de la cual se dan un emisor, un nombre y un cuerpo del mensaje, despues se obtiene dicho mensaje.
*********************************************************************************
PruebaContestadora.java
El archivo PruebaContestadora.java es un programa que para ser utilizado
debera ser compilado mediante el javac PruebaContestadora.java para que una vez que se cree el archivo.class se pueda correr el programa mediante java PruebaContestadora.
El programa es una clase main que usa la clase Contestadora y las clases de las excepciones y de la clase Mensaje, para empezar a intentar crear una nueva instacia de la clase Contestadora que crea 10 mensajes y luego se intenta meter una mas, despues el catch atarapa la excepcion de cuando la constestadora ya esta llena. depsues el programa vuelve a intentar  leer los emsnajes segun las posiciones 0,4, pero al intenatr leer la del la poscion 10 el catch dice que no se puede leer el mesaje de dicha posicion.
depsues vuelev a intentar borrar mensajes segun las posiciones 2,4 pero al intentar leer la posicion 10 el catch atrapa la excepcion de una posicion invalida y el de mensaje inexistente, y por ultimo intenta vaciar la constetadora y el catch atarapa la situacion en la que ya esta vacia la contestadora. 
*********************************************************************************