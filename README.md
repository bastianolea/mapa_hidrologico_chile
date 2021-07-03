# Mapa hidrológico de Chile con R

Instrucciones para crear un mapa hidrológico de Chile (es decir, de sus ríos) por medio de R y obteniendo datos de Open Street Map.

Se descargan los mapas usando `osmdata` para las características hidrológicas de Chile, `chilemapas` para el mapa de Chile, y `rnaturalearth` para el mapa de sudamérica.

El archivo contiene un loop para obtener las coordenadas de las cajas donde se encuadran las regiones de Chile, otro loop donde se descargan los ríos para cada región, y finalmente un gráfico de `ggplot2` con una capa por región.

![Mapa hidrológico de Chile](https://raw.githubusercontent.com/bastianolea/mapa_hidrologico_chile/master/mapa_hidrologico_chile.jpg)

[Bastián Olea Herrera](http://bastian.olea.biz), @Bastimapache
