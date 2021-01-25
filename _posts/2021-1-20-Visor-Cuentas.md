---
layout: post
title: Visor de cuentas
---

Aplicación para visualizar información de cuentas bancarias almacenadas en una base de datos MariaDB. El proyecto de IntelliJ IDEA puede ser descargado desde [aquí](https://github.com/JoMaGaBa1/Portfolio/tree/main/Visor). Está desarrollado íntegramente en Java y JavaFX con integración para JasperReports exportables a HTML o PDF.

![_config.yml]({{ site.baseurl }}/images/visor.png)

La ventana inicial nos muestra la información de la primera cuenta almacenada sin posibilidad de modificarla. Si navegamos hacia los registros siguientes, cuando lleguemos al último nos dará la opción de insertar una nueva.

A la hora de introducir los datos de la nueva cuenta, los campos nos indicarán si los datos que introducimos son válidos o no, y una vez sean válidos nos dará la opción de aceptar la inserción. En todo momento podremos cancelar este proceso.

Cuando generemos el reporte, las cuentas nos aparecerán por orden cronológico de apertura.
