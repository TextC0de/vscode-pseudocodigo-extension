# Resaltado de sintaxis para Pseudocódigo
## Instalación
Debido a que la utilidad de esta extensión es muy acotada he decidido no subirla oficialmente al repositorio de extensiones de Visual Studio Code. De todas formas puedes disfrutarla descargando este proyecto y moviendo la carpeta vscode-pseudocodigo-syntax-highlighting en el directorio en el que Visual Studio guarda las extensiones descargadas, es decir .vscode/extensions.
La localización de esta carpeta dependerá de tu sistema operativo, normalmente la podrás encontrar bajo las siguientes rutas:

- `Windows` %USERPROFILE%\.vscode\extensions
- `Mac` $HOME/.vscode/extensions
- `Linux` $HOME/.vscode/extensions

Una vez hayas hecho esto deberás de cerrar y volver a abrir Visual Studio Code en caso de que lo tuvieras abierto, la próxima vez que inicies el programa podrás seleccionar el lenguaje "Pseudocódigo" para resaltar tu código.
Puedes guardar los archivos con extensión **.pscd** y Visual Studio activará automáticamente la extensión para este tipo de archivos.

## Snippets
La extensión viene acompañada de algunos snippets que pueden ayudarte a escribir código más fácil y rápidamente. A continuación encontrarás una tabla que contiene las palabras clave de los snippets y su contenido.
| Snippet | Contenido |
| ------- | ------- |
| `algoritmo` | Estructura general de un Algoritmo |
| `subalgoritmo` | Estructura general de un Subalgoritmo |
| `si` | Bloque Si |
| `sisino` | Bloque Si con sino |
| `segun` | Bloque Según |
| `mientras` | Bloque Mientras |
| `desde` | Bloque Desde |
| `repetir` | Bloque Repetir |
| `mostrar` | Función Mostrar |
| `ingresar` | Función Ingresar |
