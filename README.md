<p>Conversor De Moneda 

<b>Funcionalidades:</b>

* Se conecta a la api de exchangerate para obtener los datos de conversión de monedas.
* Menú de opciones para conversión de moneda.
* Lee la entrada del usuario para elegir opciones del menú.
* Lee la entrada del usuario para convertir la moneda que elija del menú.
* Convierte valores de una moneda en el valor equivalente de otro tipo de moneda.
* Muestra nuevamente el menú para que el usuario elija una nueva conversión.


## Dependencias

gson-2.10.1
Ver enlace: https://mvnrepository.com/artifact/com.google.code.gson/gson

Api del sitio: https://v6.exchangerate-api.com

Versiones probadas desde consola: openjdk-17 ; openjdk-21

## Nota:

El archivo apiKey.txt debe crearse o moverse dentro de la carpeta classes después de la compilación, dentro deberá contener la clave de la api del usuario y puedan realizarse las consultas. Tambien puede  asignarla directamente dentro del código y eliminando la funcionalidad de lectura de archivo.

## Prueba:

* Descargar y descomprimir archivo.
* Crear nuevo proyecto Java.

![Creando proyecto en Itelij](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/02d8b39a-4073-4ea0-bb5e-ac4f0664c1f7)

* Copiar la carpeta src ó desde /com/... a src del nuevo proyecto.
* Copiar o crear archivo apiKey en la raíz del proyecto y guardar la apiKey en el archivo apiKey.txt. Ver enlace para apikey: https://v6.exchangerate-api.com.
  
![image](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/9ddd6661-f410-432d-85d4-5e35be1135b8)

* Descargar gson-2.10.1.jar y agregar la ruta del paquete.

![image](https://github.com/Gercodex/conversor-de-moneda-challenge-one/assets/157858339/3c98f916-5f8b-4d16-be40-62cacc9db98e)

* Click en Run o presionar Crtl+Shift+F10 en la clase Principal.

  
