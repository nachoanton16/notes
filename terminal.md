#Terminal
cal:calendario.

bc: calculadora básica. 

##Redirecciones

&gt; : redirección de salida. Crea un fichero nuevo

&gt;&gt;: Doble redirección de S. Anexa a un fichero.

&lt;: Redirigir la entrada.

&lt;&lt;:Here Document.

&lt;&lt;&lt;: Here string.

2>: Redirigir stderr

|: Pipe, tubería (usa en secreto un fichero anónimo)

Redirección de copia.

##Metacaracteres
	
$: Dime el valor de una variable.
\#: Cantidad de parámetros. 
\`: Ejecutar un comando y sustituir por el resultado.
\&: Ejecutar una cosa en segundo plano.

### Sistema de Ficheros

~: Mi directorio HOME.

.: Directorio actual.

..: El directorio de arriba.

\*: Cualquier secuencia de caracteres.
?: Cualquier caracter.
[]: Conjunto de selección.
{}: Combinaciones de secuencias.

### Opciones
" ": Quitan el poder a todos los meta, menos al $

- (A veces el fichero que representa la terminal)

(A veces le quitan el poder a casi todos los metacaracteres)

\\: Secuencia de escape -> La Criptonita de los metacaracteres.

' ': Quitan el poder a todos los meta.

##Otros
!!: El último comando.

#! Shebang: Intérprete con el que hay que ejecutar el archivo.

!\*: Los últimos parámetros

&&: AND

||: OR

!: NOT
