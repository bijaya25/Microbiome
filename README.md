# Microbiome

Este repositorio contiene un pipeline para la identificación de especies patógenas en el microbioma respiratorio de pacientes diagnosticados con infecciones respiratorias. Se utiliza un conjunto de muestras metagenómicas de tipo Illumina para caracterizar la metagenómica patogénica.

## Hipótesis

La composición del microbioma bacteriano respiratorio en pacientes con infecciones respiratorias presenta una prevalencia aumentada de especies patógenas, lo que puede contribuir al desarrollo o agravamiento de las infecciones respiratorias. La identificación precisa de estos patógenos mediante el análisis metagenómico permitirá una mejor comprensión de la relación entre microbioma y enfermedades respiratorias.

## Objetivos

## Objetivo General: 

Desarrollar un pipeline para la identificación de especies patógenas en el microbioma bacteriano respiratorio mediante análisis metagenómico.

## Objetivos Específicos:

1. Implementar y adaptar el pipeline basado en el artículo Identificación de patógenos respiratorios utilizando secuencias metagenómicas a las características de las muestras de tipo Illumina.

2. Realizar un análisis comparativo de la diversidad bacteriana entre las muestras respiratorias de pacientes diagnosticados con infecciones respiratorias.

3. Identificar y clasificar especies bacterianas patógenas presentes en las muestras.

4. Evaluar la posible relación entre la presencia de ciertos patógenos y la severidad de las infecciones respiratorias en los pacientes.

## Método

El pipeline utilizado en este estudio se basa en el artículo BMC Research Notes que emplea una serie de herramientas bioinformáticas para la identificación de especies patógenas en muestras metagenómicas de tipo Illumina. Este pipeline se ha clonado y adaptado para ser ejecutado en el análisis de las 5 muestras de secuencias de tipo Illumina que se utilizarán en este estudio.

Para correr el pipeline, se recomienda tener instalado los siguientes paquetes y herramientas:

Python 3.x
Biopython
QIIME2
FastQC
Bowtie2
Kraken2
Otros requerimientos especificados en los scripts.


