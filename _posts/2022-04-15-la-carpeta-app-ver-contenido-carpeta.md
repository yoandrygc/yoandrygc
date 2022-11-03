---
layout: post
title:  "La Carpeta.y: una App para  visualizar carpetas estructuralmente"
date:   2022-04-15 01:01:32 -0400
categories: es soft
---
### **La Carpeta.y: una App para  visualizar carpetas estructuralmente.**



<img src="/files/carpeta/6. Escogiendo.jpg" alt="Vista" style="zoom:25%;" />

**Uso general:**

Tiene como propósito visualizar estructuralmente el contenido de una carpeta que se encuentre en otro dispositivo. Su funcionamiento no requiere conexión a Internet, excepto, quizá, para obtener el fichero de entrada. 

Si alguien tiene una carpeta en su computadora y Ud quiere ver el contenido desde donde se encuentre ¿Cómo lo haría?

---

**Uso específico #1**: Mejorar el punto de copia del paquete semanal (Cuba).

El "punto de copia" es la ubicación donde los cuentapropistas con licencia "Grabador de discos" ejercen su labor.

Es un lugar muy visitado porque ver novelas, series, películas y otros audiovisuales es un pasatiempo popular.  

**Proceso:**

Lo usual es que un cliente se dirija al punto, haga la cola, y cuando le toque el turno se informe verbalmente de lo que hay. El copiador le va respondiendo mientras copia y lleva el control del espacio que queda en el dispositivo.

Lo anterior puede automatizarse completamente, y en consecuencia disfrutar de varios beneficios.

**Idea para mejorar el proceso anterior:**

1. Para la parte del cliente: una app, para teléfonos con Android, para ver lo que haya salido.
2. Para la parte del copiador: sólo necesitará el fichero que genera la app que tiene el cliente, y ejecutar un comando o dar click, para comenzar la copia.

**Idea implementada - el proceso mejorado (automatizado) - quedaría:**

1. El copiador comparte con los clientes lo que hay para copiar: es un fichero. Puede ser por wifi, bluetooth, un grupo en whatsapp o telegram, etc.
2. El cliente abre en la app el fichero compartido por el copiador. 
3. Usando la app, el cliente selecciona lo que quiere.
4. El cliente comparte con el copiador su selección.
5. El copiador copia en el dispositivo del cliente (memoria, disco duro, etc) la selección, automáticamente.

**Ventajas que provee la app**:

* Ver desde el teléfono lo que hay para copiar. Desde casa, trabajo o cualquier otro lugar.
* Seleccionar desde el mismo teléfono lo que se quiere copiar.
* Al llegar al punto solamente es necesario compartir con el copiador un fichero que la app exporta (deja guardar).
* Ahorro en tiempo de espera - en caso de que haya cola - y en preguntar lo que hay y pedir que copiar.

... y muchas otras por descubrir e ir incorporando.

**Guía visual**:

1. Para abrir la app desde el lanzador (se puede filtrar con ".y") 

<img src="/files/carpeta/1. En el menu de apps.jpg" style="zoom:25%;" />

2. Pantalla principal de la app:

<img src="/files/carpeta/2. Pantalla principal.jpg" alt="2. Pantalla principal" style="zoom:25%;" />

3. Desplegando el menú de opciones, tocar botón verde redondo en esquina inferior derecha:

   <img src="/files/carpeta/3. Menú de opciones.jpg" alt="3. Menú de opciones" style="zoom:25%;" />

      

4. Escoger la primera opción "Abrir archivo de carpetas". Se abre un diálogo en el que se escoge un archivo (ver al final del documento de donde sale): 

<img src="/files/carpeta/4. Tocando la primera opción.jpg" alt="4. Tocando la primera opción" style="zoom:25%;" />

5. La app mostrará un diálogo que indica el progreso de lectura del archivo seleccionado:

<img src="/files/carpeta/5. Dialogo de progreso.jpg" alt="5. Dialogo de progreso" style="zoom:25%;" />

6. A continuación se procede a marcar lo que queremos que nos copien (puede marcarse/desmarcarse tocando el cuadro que aparece antes de cada elemento):

<img src="/files/carpeta/6. Escogiendo.jpg" alt="6. Escogiendo" style="zoom:25%;" />

La pestaña "Selección" muestra en otro formato lo que se ha seleccionado:

<img src="/files/carpeta/6.1 Escogiendo.jpg" alt="6. Escogiendo" style="zoom:25%;" />

7. Una vez que ha seleccionado todo lo que va a copiar, entonces queda guardar o compartir dicha selección para hacerla llegar al que la copiará.
	

Se puede guardar o compartir la selección. La app tiene 3 variantes de guardar e igual número para compartir (por ejemplo: en whatsapp, telegram, messenger).

- Guardar selección para lectura: guarda la selección para que pueda ser leída por cualquier persona.
- Guardar selección para Teracopy: guarda la selección para que pueda ser leída por el programa de copia Teracopy y sólo quede escoger el destino de la copia.
- Guardar selección para Ultracopier: guarda la selección para que pueda ser leída por el programa de copia Ultracopier (Supercopier está basado en ese) y sólo quede escoger el destino de la copia.
- Compartir selección para lectura: abre un diálogo para escoger de que manera compartir la selección para que puede ser leída por una persona.
- Compartir selección para Teracopy: abre un diálogo para escoger de que manera compartir la selección en formato legible para Teracopy.
- Compartir selección para Ultracopier: abre un diálogo para escoger de que manera compartir la selección en formato legible para Ultracopier.

Así luce el escoger alguna variante de compartir:

<img src="/files/carpeta/7. Compartiendo.jpg" alt="7. Compartiendo" style="zoom:25%;" />

8. Una vez que el copiador tiene el fichero generado por la app, queda que ejecute un comando* para que inicie la copia.

**¿Cómo un copiador genera el fichero de lo que hay?**

1. En Everything, si quiero compartir lo que tengo en *C:\Me\Acopiar* pongo *"C:\Me\Acopiar\\"*. Notar la barra invertida (\\) al final del camino: 

![Guardando con Everything](/files/carpeta/Guardando con Everything.jpg)


2. En Everything, haga click en File > Export, y luego guarde el fichero con el nombre que desee y el tipo *.csv: 

![](/files/carpeta/Guardando con Everything1.jpg)

Lo siguiente sería compartir de algún modo dicho fichero para que los clientes lo reciban, pudiese ser a través de algún grupo en whatsapp o telegram creado para tal propósito. Si el grupo se llama "Punto de xyz", xyz puede ser el nombre de una persona o lugar, entonces los clientes se le unen y cada vez que entre contenido nuevo el copiador lo comparte y los clientes son notificados de ello.

