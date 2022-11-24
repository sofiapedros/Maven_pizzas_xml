# Maven_pizzas_xml
"etl.py": Programa que, dado un conjunto de datos de una pizzería como ficheros csv, calcula los ingredientes que debe comprar esa pizzería en una semana, suponiendo que el número de ventas de la pizzería en una semana sea regular (utiliza los datos de la primera semana de enero). Además, supone que la cantidad de ingredientes de una pizza es 1 ración para la pizza pequeña, 2 para la mediana, 3 para la grande y 4 para tamaños superiores. Guarda la lista de los ingredientes a comprar con el número de raciones necesarias en un csv llamado "lista_ingredientes.xml". Realiza esta funcionalidad como una etl: primero extrae los datos, después los tranforma, y por último obtiene un resultado en forma de un xml.

"analisis_de_los_datos.py": programa que guarda en un xml un análisis de los datos proporcionados por la pizzería. Guarda en un xml el número de NaN y nulls totales y por columna así como el tipo de datos de cada columna.

"Fechas_limpias.csv" es el fichero de "orders.csv" limpio

"Datos_limpios.cvs" es el fichero de "order_details.csv" limpio
