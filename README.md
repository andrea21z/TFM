# TFM
En este repositorio están recogidos los datos y el código utilizados para la elaboración de mi TFM.
El trabajo se podría dividir en dos partes, por un lado la comparación estadística entre dos técnicas de secuenciación del transcriptoma en células individuales (FACS y DROPLET), y por otro la clasificación y segmentación de células de 9 tejidos diferentes.

## Comparación estadística
En esta carpeta se encuentran 9 Notebooks, uno para cada tejido, de Python. En cada uno de ellos se llevó a cabo el mismo proceso de análisis estadístico para poder ver que técnica de secuenciación es más fiable. Los datos utilizados son los del proyecto Tabula Muris y se puede acceder a ellos mediante el siguiente enlace: https://drive.google.com/open?id=1bEh7k6FOihHuaswKwNWsWq3MXC7G_CDz , están separados en dos carpetas, una para DROPLET y otra para FACS.

## Clasificación y segmentación de tejidos
Esta carpeta contiene todos los datasets creados para cada tejido con células seleccionadas en función de 3 caracaterísticas:

*· Media +/- desviación estándar de nº de genes que se expresan: _g_
*· Media +/- desviación estándar de lecturas: _r_
*· Media +/- desviación estándar de lecturas: _r2_

También se encuentran los 6 Notebooks (en R), uno para cada región y técnica, con los modelos utilizados de clasificación-predicción y segmentación.
