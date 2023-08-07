# Introduccion-bioinformatica-con-R
Material correspondiente al curso BT1013 "Análisis de biología computacional" del Tecnológico de Monterrey en 2020. Fue mi primer acercamiento al lenguaje R y a la bioinformática.

## Contenido
### Actividad 2

En esta actividad se trabaja primero con la base de datos de pacientes de nuevo ingreso al Instituto Nacional de Cancerología (INCAN) durante el 2016 (9_PACIENTES_DE_NUEVO_INGRESO). Con ella se realiza un análisis exploratorio sobre qué tumores hay y cómo se distribuyen entre los estados y municipios del país, enfocado en los tumores colorrectales.

Posteriormente se trabaja con los datos del artículo *Multiclass cancer diagnosis using tumor gene expression signatures* (Multi_Cancer_Data.RData) para encontrar qué genes muestran mayor diferencia de expresión entre un tejido normal y un tumor. 

### Actividad 3

El objetivo de la actividad es consultar la base de datos PUBMED para encontrar artículos científicos del área biomédica. Se realizó una búsqueda sobre pacientes jóvenes con cáncer de colon y se compararon los resultados del método manual y aquel que utiliza las herramientas de R. 

### Actividad 4

En esta actividad se emplea un archivo con datos de expresión de genes y clasificación de muestras "Young" y "Old" (TCGA_COADREAD_comp_data). Se aplican pruebas t de Student para encontrar diferencias de expresión entre las clases y se generan matrices con los resultados y p-values. Se filtran genes con poca expresión y se buscan coincidencias entre mayores diferencias de expresión y menores p-values. Se visualiza un heatmap para observar patrones de expresión. Finalmente, se seleccionan genes significativos con p-values < 0.01, revelando genes que son de especial interés como el GATA4, el PCSK1N, el PIWIL1, el PRND O el FZD9, ya que la brecha entre su expresión en jóvenes y adultos mayores es grande y simultáneamente su p value es significativo.

