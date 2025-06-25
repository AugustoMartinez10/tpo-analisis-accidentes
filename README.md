# TPO - Análisis de Accidentes de Tránsito en Argentina (2017 - 2023)

## Integrantes
- Augusto Martinez  
- Kalistenco Martin Alejo  
- Maximiliano Pagani Perri  
- Leguizamon Federico  
- Matilda Ana Ameijeiras  

## Objetivo del Proyecto

Este trabajo tiene como propósito analizar los accidentes de tránsito ocurridos en Argentina entre 2017 y 2023.  
A partir de un enfoque exploratorio y de minería de datos, se busca identificar patrones **temporales**, **geográficos** y **sociodemográficos** asociados a la siniestralidad vial.  
La finalidad es aportar información útil para la toma de decisiones en materia de prevención y seguridad vial.

## Hipótesis del Proyecto

**Hipótesis Principal:**  
Existen zonas geográficas y franjas horarias donde los accidentes de tránsito se concentran significativamente, lo que permite identificar puntos críticos de siniestralidad.

**Hipótesis Secundaria:**  
Las personas jóvenes (menores de 25 años) y los motociclistas presentan una mayor participación en los accidentes de tránsito en comparación con otros grupos etarios y tipos de vehículo.

## Dominio del Negocio y Relevancia

La siniestralidad vial representa un problema social y económico de alta relevancia en Argentina.  
El análisis de datos de accidentes permite generar conocimiento para autoridades de seguridad vial, municipios y organismos públicos, contribuyendo al diseño de políticas de prevención más eficaces y focalizadas.

## Técnica de Minería de Datos Aplicada

Para detectar zonas de alta concentración de accidentes se aplicó **Clustering Geográfico** mediante el algoritmo **KMeans**, lo que permitió identificar grupos de siniestros en función de su ubicación, generando conocimiento sobre los llamados "puntos calientes" de siniestralidad.

## Contenido del Repositorio

Dentro de este repositorio podrán encontrar:

✔ El pipeline que comienza con la carga y limpieza de un dataset de accidentes de tránsito.  
✔ Selección de variables relevantes, sanitización de datos y generación de variables adicionales (día, hora, etc.).  
✔ Análisis exploratorio mediante gráficos.  
✔ Aplicación de Clustering geográfico para identificar zonas críticas.  
✔ Exportación de resultados listos para su uso en Looker.

- Dataset original sin modificaciones: `"SAT-MV-BU_2017-2023.csv"`  
  Fuente: [Dataset de Muertes Viales - Argentina](https://datos.gob.ar/dataset/seguridad-muertes-viales-sistema-alerta-temprana-estadisticas-criminales-republica-argentina/archivo/seguridad_7.2)  

- Archivo del notebook exportado en `.py` (por limitaciones de peso en `.ipynb`):  
  [tpo_miercoles_nuevo.py](https://colab.research.google.com/drive/1Ux-tL65CVQUHia6x2HjlWOLPebk7BtJL?usp=sharing)  

- Informe Looker exportado en PDF:  
  [TPO_MIERCOLES_NUEVO.pdf](https://lookerstudio.google.com/reporting/9c6c4f46-133f-4330-8a57-479350025141)  

## Conclusiones Finales

El análisis exploratorio y la minería de datos permitieron identificar hallazgos relevantes:

✔ Los fines de semana y los horarios nocturnos concentran más accidentes.  
✔ Los motociclistas y personas jóvenes destacan por su alta participación en los siniestros.  
✔ Se identificaron zonas geográficas críticas mediante Clustering geográfico.

Estos resultados constituyen una base sólida para diseñar políticas de prevención focalizadas y optimizar la seguridad vial.
