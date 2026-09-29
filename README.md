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

<H3>Comandos grep</H3>
https://www.arsys.es/blog/el-comando-grep-en-linux

El símbolo ^ en expresiones regulares indica el inicio de la línea
Ej: Si buscas la CI 1234; sin el ^, grep te devolvería por error a alguien con el teléfono 0991234;, mientras que con ^1234; solo trae la línea que arranca exactamente con esa cédula al inicio

el parámetro "-q" sirve para que no muestre nada en la terminal, en el caso que lo utilizamos en nuestro proyecto  solo comprueba si la cédula existe para que el if tome la decisión.

El parametro "-v" sirve para invertir el funcionamiento del grep, o sea, muestra todas las que no coinciden con lo buscado.

<h3>parametros IF </h3>
https://atareao.es/tutorial/scripts-en-bash/condicionales-en-bash/
<br>
-z Sirve para verificar si una cadena de texto esta vacía, -n verifica lo contrariox|
