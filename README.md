# InstalacionOdoo
---
Tarea de Odoo
---

![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/odoologo.png)

En esta tarea, instalaremos Odoo a través de Docker Compose, utilizando un IDE como VS Code, PyCharm o cualquier otro de tu preferencia.

---
Preparar el IDE (VS Code, Pycharm u Otro)
---

Lo primero que tenemos que hacer es instalar un IDE. En mi caso, utilizaré VS Code porque es un entorno al que ya estoy acostumbrado, puesto que trabajé bastante con él.

    sudo apt update
    sudo snap install code --classic
Esta es la opción si tenemos Snap, la cual, para mí, es la más sencilla, pero se podrían usar otras opciones, como descargar un .deb o a través de apt.
Después de instalar nuestro editor, lo que debemos hacer es añadir algún plugin que nos ayude. 

El editor ya trae de forma nativa algunas herramientas para la creación de dockers, pero en el apartado de plugins existe una serie de herramientas destinadas a la gestión y control de contenedores, lo cual nos facilitará mucho el trabajo.

---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/plugin.png)
---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/pluginvisualizacion.png)
---


---
Instalar Odoo 18 Community y PgAdmin con Docker Compose
---

Como segunda parte de este trabajo, crearemos un archivo Docker Compose, el cual subiré al repositorio.

---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/compose.png)
---

Una vez que ejecutamos este compose, podemos ver que funciona correctamente y se han creado nuevos contenedores

---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/ComprobacionCompose.png)
---

---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/Desktop.png)
---

Una vez que hayamos comprobado que todo funciona, sigue un paso algo más complicado: entraremos en el navegador utilizando nuestra IP y los puertos necesarios, empezando por Odoo. Después de esto, crearemos la base de datos e iniciaremos sesión con las credenciales que hemos configurado. Finalmente, tendremos que iniciar sesión en pgAdmin y enlazar correctamente el nuevo servidor de bases de datos de Odoo para poder visualizarlo.

---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/odoo.png)
---

---
![alt text](https://github.com/Diego5RG-dev/InstalacionOdoo/blob/main/recursosOdoo/vistapgadmin.png)
---

---
Explorar Odoo con Datos de Demo
---
