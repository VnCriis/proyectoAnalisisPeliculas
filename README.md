PARA EL ANALIS DE DATOS DE ESTE TEMA SE CONCATENO 2 DASETS SOBRE LOS PREMIOS OSCAR 
SE UTILIZO EXCEL PARA ESTA FUNCION, SE GUARDO EL ARCHIVO TIPO CSV, AL MOMENTO DE CONVERTIR
EN DATAFRAME ME ARRoJO DISTINTOS ERRORES COMO QUE ALGUNA FILA TENIA ALGUN CARACTER INCORRECTO,
Y LOS CORREJI MANUALMENTE.
PARA LA LIMPIEZA DEL DATAFRAME PRIMERO BORRE LOS DATOS DUPLICADOS Y BUSQUE LOS VALORES NULOS, 
EN ESTE CASO YA QUE NO HABIA CANTIDADES EN LA COLUMANA DE LOS NULOS NOS E PUEDO INSERTAR UN PROMEDIO 
EN ESTE CASO SE ELIMINO LAS FILAS CON ESTOS VALORES, PERO GRACIAS A LA PRIMERA LIMPIEZA EN EXCEL 
NO HUBO MUCHOS CASO Y SOLO SE REDUJERO ALREDEDOR DE 15 FILAS.
EL DATAFRAME SE LOS GUARDO COMO CSV, PARA TRANSPORTARLO A AL GESTOR DE BASES DE DATOS, 
EL GESTOR UTILIZADO EN ESTE ESTUDIO FUE POSTGREE EN DONDE PRIMERO VERIFICO PRIMERO LA CONEXION Y 
UNA VEZ VERIFICADA LO ENVIO AL DATA LAKE.
