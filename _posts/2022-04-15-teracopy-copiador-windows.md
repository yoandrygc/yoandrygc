---
layout: post
title:  "Teracopy, un copiador para Windows"
date:   2022-04-15 01:01:32 -0400
categories: es soft
---
Una de las tareas que más a menudo realizamos en nuestra PC es copiar y pegar ficheros/carpetas. Para Windows existen varios programas que mejoran el mecanismo de copia de ficheros que este sistema operativo trae por defecto, entre las alternativas tenemos a Supercopier, Ultracopier, Teracopy, etc.

En este artículo veremos a Teracopy, un copiador de ficheros para Windows que cuenta con todas las funciones que pudiésemos necesitar. Permite que las transferencias sean más rápidas, óptimas y seguras. Este se centra en la integridad de la información, confiabilidad en las transferencias, y la capacidad de pausar y reanudarlas.

[Aquí](https://codesector.com/teracopy) su web para más información, y [acá](https://codesector.com/downloads) para descargar la última versión.

<img src="/files/photos/Teracopy2.png"  />

### Funciones:

* Transferencia asíncrona para mayor rapidez.
* Comprobación de espacio libre en el destino.
* En caso de error, intentará recuperarse de la mejor manera.
* Posibilidad de verificación para asegurar que lo transferido y el original son idénticos.
* Reemplazo de la forma en que Windows hace transferencias por defecto.
* Preservación de marcas de tiempo (*timestamps*).
* Copia de ficheros bloqueados.
* Ejecución de operaciones al finalizar la transferencia: apagar, hibernar, suspender la PC; mantener abierta, cerrar Teracopy; y mostrará los scripts en formato PowerShell que haya reconocido, los cuales se ejecutarán al hacer click.
* Para más información, ver el fichero Whatsnew.txt en la carpeta donde está instalado.

### Para desarrolladores de software:

Teracopy permite especificar opciones de línea de comandos. Esto permite a los desarrolladores tomar ventaja de esta característica desde otras aplicaciones, incluyendo el Command Prompt (cmd.exe).

El comando general tiene la siguiente forma:

```powershell
TeraCopy.exe <Operation> [*]Source Target [/SkipAll] [/OverwriteOlder] [/RenameAll] [/OverwriteAll] [/NoClose] [/Close]
```

Nota: es posible que tenga que especificar el camino completo del ejecutable, algo así como ***"C:\Program Files\TeraCopy\TeraCopy.exe"***.

El  * (asterisco) es para indicar que Source es un fichero que contiene una lista de ficheros. Los caminos dentro de este tipo de fichero pueden contener espacios y no requieren comillas. Deben aparecer uno por línea. 

TeraCopy soporta las siguientes operaciones: **Copy, Move, Delete, Test, Check and AddList**.

**Ejemplos:**

- TeraCopy.exe Copy "C:\My Documents" D:\Total
- TeraCopy.exe Copy C:\movie.mkv "D:\My Stuff"
- TeraCopy.exe Copy C:\Projects F:\Projects /OverwriteOlder /Close
- TeraCopy.exe Move *C:\Copier\afilelist.lst "C:\My movies" /OverwriteAll /NoClose
- TeraCopy.exe AddList *C:\All\afilelist.lst
- TeraCopy.exe Test C:\avengers.mp4
- TeraCopy.exe Check C:\achecksum.md5

#### ¿Cómo añadir scripts PowerShell a Teracopy para su ejecución al finalizar la transferencia?

En **C:\Users\<YOUR_USERNAME>\AppData\Roaming\TeraCopy** se almacenan datos importantes de Teracopy, entre ellos los scripts PowerShell que se muestran en el menú *Al finalizar* (esquina superior derecha). Al añadir un nuevo script, Teracopy lo reconoce automáticamente.

#### Para más personalización y ajustes:

Ver el fichero **C:\Users\<YOUR_USERNAME>\AppData\Roaming\TeraCopy\Options.ini**