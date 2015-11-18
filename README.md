En el artículo de la Wikipedia [La crisis migratoria en Europa](https://es.wikipedia.org/wiki/Crisis_migratoria_en_Europa), hay un gráfico de [Chumwa](https://de.wikipedia.org/wiki/User:Chumwa) con un mapa que combina una serie de datos:

-   Gráfico de barras de países de origen de lxs refugiadxs, divididas las peticiones de asilo si son la primera vez o si repiten.
-   Gráfico de barras sobre los países con el número de peticiones de asilo durante los seis primeros meses de 2015, con la misma división.
-   Cartograma con cloropetas en función de las peticiones de asilo por cada 10.000 habitantes
-   Flechas más o menos gruesas sobre el mapa con las rutas migratorias más importantes.
-   Gráfico de áreas con el número de solicitudes por mes, con la misma división.

El gráfico completo de 2192 x 2040 pixels se encuentra [aquí](https://upload.wikimedia.org/wikipedia/commons/8/80/Map_of_the_European_Migrant_Crisis_2015.png).

# Fuentes de datos

Las fuentes del mapa son varias:

-   Datos de peticiones de asilo de Eurostat: <http://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=migr_asyappctzm>
-   Datos de población de países de Europa de Eurostat: <http://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=tps00001>
-   Rutas migratorias según FRONTEX: <http://frontex.europa.eu/trends-and-routes/migratory-routes-map/>

# Peticiones de asilo

Siguiendo los datos de peticiones de asilo, he creado este [gráfico](https://flowsta.github.io/refugees-wellcome/) en Datawrapper sobre las peticiones de asilo aprobadas en países europeos:

Dado que [Datawrapper](https://datawrapper.de) cambió en diciembre de 2014 sus [condiciones de publicación](http://blog.datawrapper.de/2014/new-usage-guidelines-for-datawrapper/) y como usuarix gratuito te permite descargarte un *zip* con el proyecto, he creado una rama en el proyecto de GitHub llamada *gh-pages* para publicar el contenido del *zip*, que está publicado aquí:

<https://flowsta.github.io/refugees-wellcome/>

Si se quiere embeber en una página, se puede incluir este código:

\#+BEGIN\_SRC html
<iframe src="<https://flowsta.github.io/refugees-wellcome/>" width="600" height="980" frameborder="0" allowfullscreen="allowfullscreen">iframe</iframe>
\\#+END\_SRC html
