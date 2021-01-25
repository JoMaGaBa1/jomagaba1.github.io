---
layout: post
title: Gestión de empresa
---

Esta fue una de las primeras aplicaciones CRUD desarrolladas durante el segundo curso del Grado Superior de DAM. El proyecto se llevo a cabo en IntelliJ IDEA y el código puede descargarse desde [aquí](https://github.com/JoMaGaBa1/Portfolio/tree/main/Empresa). El lenguaje en el que está escrita es Java, con una interfaz gráfica Swing y una base de datos MariaDB.

![_config.yml]({{ site.baseurl }}/images/crud.png)

Se nos presenta una interfaz sencilla con un título superior y dividida en 2 partes: la parte derecha para visualizar directamente los datos almacenados en la base de datos, y la parte izquierda para el control directo de estos datos, es decir, insertar, consultar, modificar y eliminar.

En los casos de modificación y borrado de datos, nos aparece una ventana preguntando si verdaderamente queremos realizar la acción, y en todos los casos aparece una ventana que nos confirma que la acción se ha llevado a cabo o si ha surgido algún error.

Todos los casos, excepto la inserción de datos, van en función al ID introducido en el correspondiente campo.
