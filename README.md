# PHP-includes
Modelo básico de plantillas en PHP con includes

## modelo.php 
Pagina modelo, cada vez que generamos una nieva opcion, debemos guardar como este fichero  . Contine todos los includes.

## Documentos parciales
### cabecera.html 
Contiene los elementos de la cabecera del ```<body>```
### funciones.php
Libreria de funciones propias para usar en todas las aplicaciones. Va a consistir en una series de funciones 
```function Validar() {} ```
### header.php
Elementos comunes de las parte ```head``` de todas las páginas. ```<meta> <link> ...```
### navegacion.php 
Barra de navegación, cada vez qe hacemos una nueva página insertamos un ```<li><a href="nuevapagina.php">``` en este fichero
### pie.php
Todos los elementos comunes del pie de página


