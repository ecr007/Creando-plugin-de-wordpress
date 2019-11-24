# Creando plugin de wordpress

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

