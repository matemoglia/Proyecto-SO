<h1>Proyecto-SO</h1>

<h3>Definicion de comandos aprendidos</h3>
echo -e "\e[31mRojo\e[0m"
<br>
echo -e "\e[32mVerde\e[0m"
<br>
echo -e "\e[33mAmarillo\e[0m"
<br>
echo -e "\e[34mAzul\e[0m"

el "-e" en el echo sirve para habilitar la interpretación de los caracteres de escape ( \ )  

Las llaves ${variable} sirven para delimitar el nombre de la variable y que no se mezcle con el texto que viene pegado inmediatamente después

sed -n sirve para mostrar específicamente de que linea a que linea mostrar 
p: Significa print (imprimir). Le ordena a sed que imprima únicamente el rango especificado.
,: Define un rango que va desde la línea indicada en ${linea1} hasta la indicadada en ${linea2}.
<H3>Comandos grep</H3>
https://www.arsys.es/blog/el-comando-grep-en-linux

El símbolo ^ en expresiones regulares indica el inicio de la línea
Ej: Si buscas la CI 1234; sin el ^, grep te devolvería por error a alguien con el teléfono 0991234;, mientras que con ^1234; solo trae la línea que arranca exactamente con esa cédula al inicio

el parámetro "-q" sirve para que no muestre nada en la terminal, en el caso que lo utilizamos en nuestro proyecto  solo comprueba si la cédula existe para que el if tome la decisión.

El parametro "-qw" sirve  para comprobar si una palabra exacta existe dentro de un texto o archivo (normalmente se utiliza en condicionales) 

El parametro "-v" sirve para invertir el funcionamiento del grep, o sea, muestra todas las que no coinciden con lo buscado.

<h3>parametros IF </h3>
https://atareao.es/tutorial/scripts-en-bash/condicionales-en-bash/
<br>
-z Sirve para verificar si una cadena de texto esta vacía, -n verifica lo contrario
-d  verifica si una ruta de directorio existe
-e verifica si el archivo y el directorio existe 
-r si Arch o Dir existe y si tiene permiso de lectura, -w de escritura y -x de ejecución
-s sirve para comprobar si un archivo existe Y NO está vacío

<h3>Otros</h3>
rm -rf --> sirve para eliminar directorios de forma forzada, es decir, sin importar que este vacio 
  
