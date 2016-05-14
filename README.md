# Composer de 0 a 100
Para empezar con el curso, sería bueno que tengas composer instalado en tu sistema para así ahorrarnos tiempo en los videos :smile:

Si quieres, puedes entrar a la pagina de [Composer](https://getcomposer.org/download) y seguir los pasos de ellos ya que son la página oficial, pero para que no salgas de esta pantalla mejor te los escribimos aquí.

Lo primero que necesitas es tener el binario de PHP en tu PATH, luego de tenerlo todo funcionando puedes dirigirte a la consola y escribir esto:

````bash
php --version
````
Si el mensaje que te muestra es parecido a este:
````bash
PHP 7.0.0 (cli) (built: Dec  8 2015 16:39:19) ( NTS )
Copyright (c) 1997-2015 The PHP Group
Zend Engine v3.0.0, Copyright (c) 1998-2015 Zend Technologies
````
si el mensaje es parecido quiere decir que esta correctamente configurado, entonces procedemos a descargar el instalador, para los siguientes pasos tendras que mantener la consola abierta y escribir:
````bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
````
esto te descargara el instalador de composer, el composer-setup.php puedes renombrarlo por cualquier nombre de archivo eso no importa mucho...ahora instalemos:
````bash
php composer-setup.php
````
