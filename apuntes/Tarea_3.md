# Descargar Fits
La forma inicial para bajar los fts.. era usando:
[broken link](http:/sechi.nrl.navy.mil/cgi-bin/swdbi/secchi_flight/images/form)
Sin embargo, ya no puedes accesar a este link...


Ahora es a través de la página que encontraste y específicamente  en: 
[secchi fits](https://secchi.nrl.navy.mil/secchi_flight/images)

Solo tengo que comentarte un detalle al bajarlas... en las opciones, tiene que:
- Tener palomita Wavelength/Polarizer
- Image cadence 10 min  (o si no 15 min, siempre la menor, si no hay menos de 1 hr no sirve para el análisis de Alejandro)
- Detector COR2
- Observatory SC-A

Y en Advanced Options, asegurate que estén las siguientes:
- Palomita en SEB opción all
- Palomita en Naxis1 y Naxis2 pero sin escribir nada
- Palomita en Downlink con la opción SSR1

Le das Submit y entonces verás que se descarga la lista y ahora si estas opciones te permiten ver las características del archivo antes de bajarlas.

Elige aquellas que NO son sequence o dark, con el tamaño de la imagen simétrico, es decir, 256 x 256, 1024 x 1024, 2048 x 2048 y polar quad en 0 deg.

Todo esto se evitaba pero pues ahora es de nuevo así. 

