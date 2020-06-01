# Resaltado de sintaxis para Pseudocódigo
## Instalación
Debido a que la utilidad de esta extensión es muy acotada he decidido no subirla oficialmente al repositorio de extensiones de Visual Studio Code. De todas formas puedes disfrutarla descargando este proyecto y moviendo la carpeta vscode-pseudocodigo-syntax-highlighting en el directorio en el que Visual Studio guarda las extensiones descargadas, es decir .vscode/extensions.
La localización de esta carpeta dependerá de tu sistema operativo, normalmente la podrás encontrar bajo las siguientes rutas:

- `Windows` %USERPROFILE%\.vscode\extensions
- `Mac` $HOME/.vscode/extensions
- `Linux` $HOME/.vscode/extensions

Una vez hayas hecho esto podrás seleccionar el lenguaje "Pseudocódigo (UNPSJB Version)" para resaltar tu código.
Puedes guardar los archivos con extensión **.pscd** y Visual Studio activará automaticamente la extensión para este tipo de archivos.

## Snippets
La extensión viene acompañada de algunos snippets que pueden ayudarte a escribir código más fácil y rápidamente. A continuación encontrarás una tabla que contiene las palabras clave de los snippets y su contenido.
| Snippet | Contenido |
| ------- | ------- |
| `Algoritmo` | Estructura general de un Algoritmo |
| `Subalgoritmo` | Estructura general de un Subalgoritmo |
| `Si` | Bloque Si |
| `Sisino` | Bloque Si con sino |
| `Según` | Bloque Según |
| `Mientras` | Bloque Mientras |
| `Desde` | Bloque Desde |
| `Repetir` | Bloque Repetir |
| `Mostrar` | Función Mostrar |
| `Ingresar` | Función Ingresar |
