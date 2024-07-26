![Alura_Latam](https://github.com/user-attachments/assets/f3fcd049-54a1-41b1-9bce-71e976633d89)
Variables y estructuras de datos

traduccion: Es un objeto que contiene las traducciones de las vocales a sus correspondientes cadenas cifradas. Por ejemplo, la vocal "a" se traduce a "ai", la vocal "e" se traduce a "enter", y así sucesivamente.
texto: Es la variable que almacena el texto que se va a cifrar o descifrar.
texto_out: Es la variable que almacena el texto cifrado o descifrado que se mostrará en la pantalla.
area_default y area_result: Son variables que se refieren a elementos HTML que se utilizan para mostrar u ocultar el área de entrada y salida de texto.
enc, des y copy: Son variables que se refieren a elementos HTML que se utilizan para activar las funciones de cifrado, descifrado y copia al portapapeles, respectivamente.

Funciones:
encriptar(traduccion)
Esta función cifra el texto de entrada reemplazando las vocales con sus correspondientes cadenas cifradas.

Primero, verifica si el texto de entrada está vacío y, si es así, devuelve sin hacer nada.
Luego, cambia la visibilidad del área de entrada y salida de texto.
Reemplaza cada vocal en el texto de entrada con su correspondiente cadena cifrada utilizando expresiones regulares. Por ejemplo, reemplaza todas las "a" con "ai", todas las "e" con "enter", y así sucesivamente.
Actualiza el texto de salida con el texto cifrado.
desencriptar(traduccion)
Esta función descifra el texto de entrada reemplazando las cadenas cifradas con sus correspondientes vocales.


clipboard():
Esta función copia el texto de salida al portapapeles.

Selecciona el texto de salida.
Utiliza la API navigator.clipboard para escribir el texto de salida en el portapapeles.

Eventos:
El código establece eventos para los botones de cifrado, descifrado y copia al portapapeles. Cuando se hace clic en cada botón, se llama a la función correspondiente.

Ejemplos de uso:
El usuario ingresa un mensaje en el área de entrada y hace clic en el botón "Cifrar". El texto cifrado se muestra en el área de salida.
El usuario hace clic en el botón "Descifrar" para descifrar el texto cifrado.
El usuario hace clic en el botón "Copiar" para copiar el texto descifrado al portapapeles.
