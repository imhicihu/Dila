<p align="center">
  <img src="https://github.com/imhicihu/dila/blob/d906cfac8423856f46f95ae2ba21f1659a9232ce/images/logo-dila.png?raw=true" alt="DILA logotipo"/>
</p>
<br> 
</br>

![portada](images/477405737-stability_work_in_progress.png)
![internal_use](images/3847436881-internal_use_stable.png)
# FUNDAMENTO #

* Este repositorio persigue simplemente el registro de los cambios llevados a cabo en la transición entre un servidor a otro, su flujo de trabajo y las estrategias digitales implicadas. Entre las herramientas _open source_ utilizadas están [Omeka](https://omeka.org/), servidores [Apache](https://es.wikipedia.org/wiki/Servidor_HTTP_Apache), base de datos [MySQL](https://es.wikipedia.org/wiki/MySQL), [Wordpress](https://wordpress.org/); lenguaje de programación PHP _et alia_.
* Es un repositorio con fines específicos y de **uso interno**.
![portada](images/portada.png)

## Transferencia ##

* Resumen del flujo de trabajo
    - Copia de seguridad del sitio web anterior.
    - Configuración del nuevo servidor: instalación de un servidor web compatible, configuración de bases de datos, etc.
    - Respaldo y transferencia de archivos: copia de todos los archivos del sitio web desde el servidor anterior al nuevo. Esto incluye archivos HTML, CSS, JavaScript, PHP, imágenes y cualquier otro recurso estático necesario.
    - Migración de la base de datos (vía FTP, Rsync): la base de datos del sitio web anterior se exportó en un formato compatible y se importó correctamente en la nueva base de datos del nuevo servidor. Se verificó que la migración se realizara sin errores y que los datos estuvieran íntegros. También se aseguró de mantener la estructura de directorios, los permisos de archivo pertinentes y las variables de entorno.
    - Configuración del [DNS](https://es.wikipedia.org/wiki/Sistema_de_nombres_de_dominio): se actualizaron los registros DNS correspondientes para apuntar el nombre de dominio del sitio web al nuevo servidor. Esto implica cambios en los registros A, [CNAME](https://es.wikipedia.org/wiki/Registro_CNAME), el [posicionamiento en los buscadores](https://es.wikipedia.org/wiki/Posicionamiento_en_buscadores) o cualquier otro registro necesario para redirigir el tráfico hacia la nueva dirección del servidor.
    - _Tests_ y verificación de enlaces internos, pruebas de rendimientos y puesta a punto final.
    - En una primera instancia, se han recabado estos [issues](Sugerencias.md) y posibles [actualizaciones](Misceláneas.md)

## Contribuciones ##

* Dado que este proyecto es de **uso interno**, las solicitudes de extracción (*pull requests*) están **restringidas** a aquellos involucrados en este proyecto.

## Legales ##

* Todas las marcas registradas son propiedad de sus respectivos propietarios.

## Código de conducta ##
* Por favor, revise nuestro [Código de conducta](codigo_de_conducta.md).

## Licencia ##

* Este repositorio se distribuye bajo la licencia ![MIT](images/2049852260-MIT-license-green.png), que especifica los términos y condiciones de uso. Consulte el archivo [LICENSE](LICENSE) para obtener más información.