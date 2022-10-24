# Herramientas útiles y plug-ins

- [Wikipedia Preview](https://www.youtube.com/watch?v=_m6YzR0j8Fs&ab_channel=WikimediaFoundation) 🡒 Pone en un sitio web ayuda contextual para explicar palabras y conceptos.

- [Kwix (wikipedia descargada)](https://es.wikipedia.org/wiki/Wikipedia:Descargas) 🡒 Aplicación para consultar offline la wikipedia. 


- [Wikiwand](https://www.wikiwand.com/) 🡒 Wikipedia Modernized, The world's leading Wikipedia reader 

## lilypond

## Quarry

Consultando a la base de datos de la Wikipedia vemos cuantas ediciones hemos hecho

https://quarry.wmcloud.org/query/runs/all

#### número de ediciones que han hecho estos usuarios
Database: eswiki
``` mysql
select sum(user_editcount) from user where user_name in ('JescuderoBUS', 'Jeioncs');
```

#### en qué páginas han editado estos usuarios
Database: eswiki




![Database Schema](https://upload.wikimedia.org/wikipedia/commons/9/94/MediaWiki_1.28.0_database_schema.svg)


https://quarry.wmcloud.org/query/18061