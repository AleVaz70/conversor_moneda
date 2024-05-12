Conversor de Monedas en Java

Este proyecto es un conversor de monedas implementado en Java. Utiliza la API de tasas de cambio Exchange Rate API para obtener las tasas de cambio actuales.

 Características

- Conversión entre varias monedas, incluyendo Dólares, Pesos argentinos, Pesos chilenos y Reales.
- Interfaz de usuario basada en texto que permite al usuario seleccionar la conversión que desea realizar e introducir la cantidad que desea convertir.
- Manejo de errores básico para opciones no válidas y cantidades no válidas.

 Cómo usar

1. Ejecute el programa. Se le presentará un menú con varias opciones de conversión.
2. Introduzca el número de la opción que desea seleccionar.
3. Introduzca la cantidad que desea convertir.
4. El programa mostrará el resultado de la conversión.

Código

- El código principal del conversor de monedas se encuentra en el archivo `Principal.java`. Este archivo contiene el bucle principal del programa, que presenta el menú al usuario, lee la opción del usuario y realiza la conversión correspondiente.
- La consulta a la API de tasas de cambio se realiza en el archivo `ConsultaAPI.java`. Este archivo contiene una función que realiza una solicitud HTTP a la API de tasas de cambio y devuelve el resultado.-
- La clase `Monedas` es un registro que representa una moneda y su tasa de cambio.
