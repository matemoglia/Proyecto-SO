# Proyecto-SO
echo -e "\e[31mRojo\e[0m"
echo -e "\e[32mVerde\e[0m"
echo -e "\e[33mAmarillo\e[0m"
echo -e "\e[34mAzul\e[0m"

awk [opciones] 'patrón { acción }' archivo -->  divide automáticamente cada línea de entrada en campos (columnas) usando espacios en blanco como separador por defecto.

El símbolo ^ en expresiones regulares indica el inicio de la línea
Ej: Si buscas la CI 1234; sin el ^, grep te devolvería por error a alguien con el teléfono 0991234;, mientras que con ^1234; solo trae la línea que arranca exactamente con esa cédula al inicio
