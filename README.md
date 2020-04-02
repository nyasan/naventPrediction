# Rain Prediction

1.eliminamos valores nulos de la columna tipos de propiedad, provincia y ciudad





8:34
2) latitud y longitud de una propiedad Duplicar con respecto a propiedad de misma ciudad
8:35
3)
8:35
quitamos columna de descripción, tìtulo, direcciòn, fecha
8:35
4) eliminamos valores nulos de metros cubiertos
8:35
5) valoramos datos faltantes de garage como que no tiene y datos faltantes de baños como que hay 1. descartamos variable terreno (función "if" sacamos todo tipo de construcción. Lo tratamos como caso aparte del resto). Entrenamos el dataset primero con terreno y despuès sin terreno, y nos fijamos cuàl es la diferencia entre ambos entrenamientos
8:36
6) Descartamos la columna de Antigûedad ya que influye màs la ubicaciòn que la antigûedad
8:36
7) Limpiar metros cubiertos
8:37
8. Corregir casos de metros cubiertos > metros totales y completar metros totales faltantes duplicando el valor de metros cubiertos
8:37
9) Si es un terreno y el valor de metros cubiertos es NaN, podemos suponer que es cero metros cubiertos
8:37
10) Una vez hecho toda la limpieza del dataset, hacer gràfico de correlaciones. Agarramos los features màs importantes y vemos què mètodos
utilizar. Sugerencias: Hacer Linear Regression, calcular con el mètodo del logaritmo (y=precio, x=variables que querramos utilizar) y
luego utilizar Grid
