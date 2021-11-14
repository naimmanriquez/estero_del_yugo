# Biodiversidad de aves
# Análisis de Biodiversidad en el Estero del Yugo

Este repositorio tiene como objetivo principal generar indicadores para el análisis básico de la biodiversidad. Los datos provienen de un censo de aves en el Estero del Yugo en el municipio de Mazatlán, México.

# Paquetes de R
Deben instalar los siguientes paquetes:

##### 1. vegan (requiere además: permute, lattice).
##### 2. kableExtra (para tablas).
##### 3. ggplot2 (para gráficas).
##### 4. BiodiversityR.

# 1. Indices de diversidad
Con la base de datos del censo se pretende calcular los índices más comunes de diversidad:
- Shannon–Weaver: Este índice se representa normalmente como H’ y se expresa con un número positivo, que en la mayoría de los ecosistemas naturales varía entre 0,5 y 5, aunque su valor normal está entre 2 y 3; valores inferiores a 2 se consideran bajos en diversidad y superiores a 3 son altos en diversidad de especies.
- Simpson: es uno de los parámetros que nos permiten medir la riqueza de organismos. En ecología, es también usado para cuantificar la biodiversidad de un hábitat. Toma un determinado número de especies presentes en el hábitat y su abundancia relativa. Cuanto más se acerca el valor de este índice a la unidad, existe una mayor posibilidad de dominancia de una especie y de una población; y cuanto más se acerque el valor de este índice a cero mayor es la biodiversidad de un hábitat.

# 2. Curvas de acumulación de especies
