# Solano-post2-u4

Implementación de un programa en lenguaje ensamblador NASM para DOS que demuestra
el uso de macros con parámetros y etiquetas locales, estructuras de control de flujo
con LOOP y CMP/Jcc, y procedimientos con CALL/RET, verificable en DOSBox.

Prerrequisitos
- NASM version 2.14 o superior (descargable desde https://www.nasm.us)
- ALINK enlazador para DOS (descargable desde https://alink.sourceforge.net)
- DOSBox 0.74 o superior para ejecutar el programa (descargable desde https://www.dosbox.com)
- Editor de texto plano (Notepad++, VS Code o similar)

Compilacion y ejecucion

- Paso 1: Ensamblar (desde CMD de windows)

  nasm -f obj programa2.asm -o prog2.obj -l programa2.lst

- Paso 2: Enlazar (desde CMD de Windows)

  alink prog2.obj -o prog2.exe -entry main

- Paso 3 - Ejecutar (desde DOSBox)

  MOUNT C C:(ruta)

  C:

  prog2.exe


Salida esperada

=== Macros y Control de Flujo ===

[Linea A] Primera impresion

[Linea A] Primera impresion

[Linea A] Primera impresion

[Linea B] Segunda impresion

[Linea B] Segunda impresion

El valor mayor es: 6

El valor mayor es: 9

Los valores son iguales.

Fin del programa.
