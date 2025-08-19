

<img width="500" height="500" alt="Badge-Conversor" src="https://github.com/user-attachments/assets/75ecad59-e771-4d07-940e-f0f9a44240ee" />



# conversordemonedas
alura -- pendiente proceso 
Conversor de Monedas 💵💱💶
Desarrollado como parte del Challenge Conversor de Monedas, propuesto por Alura Latam en colaboración con Oracle en el programa ONE, como parte de la especialización Back-End.

📌 Descripción

Se trata de una aplicación en Java que permite convertir entre distintas divisas utilizando una API de tasas de cambio en tiempo real.
El sistema realiza consultas a la API, procesa la respuesta en formato JSON, filtra las monedas de interés y muestra el resultado de forma clara al usuario.
Además, el programa mantiene un historial de conversiones con fecha y hora, lo que facilita llevar un registro de operaciones anteriores.

💻 Tecnologías utilizadas

Java como lenguaje principal.

API de tasas de cambio en tiempo real para obtener los valores actualizados de conversión.

Gson para interpretar y mapear el JSON de la API a objetos Java.

Git/GitHub como sistema de control de versiones y colaboración.

IntelliJ IDEA como entorno de desarrollo (IDE).

🧩 Clases principales y funcionalidades

Calculos.java → Contiene la lógica de las conversiones de divisas, almacenamiento de valores y generación de mensajes de salida.

ConsultaConversion.java → Gestiona la conexión con la API externa para obtener las tasas de cambio.
Instrucciones de Uso 🚀

Clona este repositorio en tu máquina local.
Abre el proyecto en IntelliJ IDEA u otro IDE de tu elección.
Ejecuta la clase Principal.java para iniciar el programa.
Sigue las instrucciones en pantalla para realizar conversiones de moneda.
¡Disfruta convirtiendo monedas!

GeneradorDeArchivos.java → Permite registrar en un archivo de texto el historial de consultas realizadas.

Principal.java → Clase principal del programa; maneja la interacción con el usuario en consola mediante un menú y coordina las operaciones de conversión.
