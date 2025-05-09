# COVID-19
## Proyecto sobre el impacto del COVID-19

### El análisis comenzó con la exploración del dataset proporcionado por Ingeniería de Datos. Este contenía 12,216,057 registros y 50 columnas en formato CSV, lo que facilitó su manipulación respecto al dataset original de 21 GB. También se recibió un archivo complementario con información detallada sobre las variables seleccionadas, útil para la preparación y limpieza de los datos.

### Carga y verificación inicial de datos:
Se utilizó Python para leer el archivo y comprobar la coherencia del dataset con las especificaciones iniciales.
A través de numpy y pandas, se verificaron dimensiones y se identificaron valores faltantes.
### Se generaron filtros iniciales:
Para centrar el análisis en los seis países seleccionados (Argentina, Brasil, Chile, Colombia, México y Perú).
### Limpieza y filtrado de datos:
Se eliminó información irrelevante (datos asociados a subregiones) y se trabajó exclusivamente con registros relevantes para cada país.
Los pocos valores nulos se completaron con el valor 0 (cero).
Se estableció el 01/01/2021 como punto de inicio del análisis, eliminando datos irrelevantes previos.
### Por último utilicé el lenguane DAX en Power BI para la creación de métricas. 

![Image](https://github.com/user-attachments/assets/53fd6f16-01ed-4882-b669-ef046bb5819a)
![Image](https://github.com/user-attachments/assets/1afe13a1-e0aa-4e22-9176-2b2c0ab8d905)
![Image](https://github.com/user-attachments/assets/b99210df-c0da-405a-ba77-a8eb930f0fd4)
![Image](https://github.com/user-attachments/assets/8e371435-c72b-4df5-8702-9e87ecd606e5)
