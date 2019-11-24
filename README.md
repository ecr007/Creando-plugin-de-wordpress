# Creando plugin de wordpress

## Bilerplate para iniciar un plugin

https://github.com/DevinVinson/WordPress-Plugin-Boilerplate

https://github.com/ecr007/WordPress-Plugin-Boilerplate

## General
1 - Nombres del directorio y el archivo principal de plugin deben ser los mismos.

## Rutas

plugin_dir_path() -> Retorna el path absoluto a la carpeta de los plugin

plugins_url () -> URL a la carpeta de los plugin

## Seguridad

Para solo permitir el acceso desde wordpress no desde afuera.
```php
defined( 'ABSPATH' ) or die( 'No script kiddies please!' );
```

## Archivo Readme

Este archivo es indispensable para crear un plugin es practicamente su cedula.

```shell
=== Tasa del dolar ===
Contributors: un developer
Tags: dolar,peso,cambio,rd,dom
Donate link: Link de donacion
Requires at least: 1.0
Tested up to: 1.0
Requires PHP: 5.6
Stable tag: trunk
License: Licencia publica
License URI: licencia.com

Descripción corta, de maximo 150 caracteres

== Description ==
Descripción muy larga

== Installation ==
Las instruncciónes para instalar el plugin

== Frequently Asked Questions ==
Preguntas frecuentes

== Screenshots ==
1. Link image no.1
2. Link image no.2
3. Link image no.3

== Changelog ==
Log de cambios

== Upgrade Notice ==
Noticias de la actualización, maximo 300 caracteres.
```
