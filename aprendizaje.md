Emiliano debe encontrar ejemplos de cómo utilizar cada uno de los puntos.

Diccionario
------------------------------------------------------------
package: paquete
manager: administrador
directorio raíz: /
directorio del usuario: /home/nombre_de_usuario
directorio del usuario: ~
virgulilla: ~

Computación
------------------------------------------------------------

## Cosas aprendidas

- ejecutar comandos como súper usuario `sudo`
- instalar paquetes `sudo pacman -S nombre_del_paquete` package_manager = pacman
- ubicaciones relativas 
    ```
    directorio padre: ..
    si estoy en /home, para ir a Downloads >
        cd Emidrilo/Downloads 
        cd ~/Downloads
    ```
- ubicaciones absolutas
  siempre lo indicas desde el directorio raíz (/)
    ```
    cambiar de directorio: /dir_1/dir_2/.../dir_destino

    ```

- cambiar el idioma del teclado
  Esto se configura en ~/.xinitrc con la instrucción `setxkbmap -layout us,es -option grp:win_space_toggle`
  Entonces para el cambio de idioma del teclado se hace con: `Win + Space`

- ejecutar dos comandos en una misma línea `|`
- modificar múltiples nombres de archivos o directorios `rm nombre*`
- abrir documentos de texto con nvim
- carpeta temporal en Linux `/tmp`

## Comandos
- cd `change directory, cambiar de directorio`
- ls `list, muestra el contenido de la carpeta, ejemplo: ls ~/Documents`
- mkdir `make directory, crear directorio`
- mv `move, mueve archivos o directorios, necesita un origen y destino, ej. mv ~/Documents/tarea1 ~/Downloads`
- rm `remove, borrar archivos o directorios`
- unzip `descomprimir archivos comprimidos, como parámetro necesita el nombre del archivo`
- 7z x `descomprimir archivos comprimidos, como parámetro necesita el nombre del archivo`
- cambiar el idioma del teclado:  `setxkbmap -layout us,es -option grp:win_space_toggle`
- imprimir el directorio donde estoy ubicado `pwd`

# Cosas por aprender

- crear archivos `touch`
- agregar texto a archivos `>>`
- formatos de archivos
- tipos de textos (crudos o con metadatos, word vs txt)
- editores de texto (vim, sublime, word, libre office)
- terminales


## Administrador de paquetes
- utilizar el administrador de paquetes
- instalar paquetes `sudo pacman -S paquete`
- desinstalar paquetes `sudo pacman -Rnn paquete`

Programación
------------------------------------------------------------
0. qué es un lenguaje de programación, para qué sirve.
1. funciones básicas:
    imprimir
    variables
    asignaciones
    sumas (aritmética)
    leer entradas del usuario
    ciclos / iteraciones
        romper un ciclo (break)
2. resolver problemas de matemáticas o física con programación
3. analizar datos (estadística)
4. crear scripts
5. ejecutar scripts
    5.1 archivos ejecutables y permisos de usuario
6. automatizar scripts
7. bases de datos

