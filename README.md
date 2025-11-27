# Análisis de base de datos de Empresa SRL

## Contexto
Este proyecto contiene el análisis y visualización de datos de la Empresa SRL, a través de Tableau. La base contine edatos personales de los empleados de la compañía SRL, que incluyen información detallada sobre la contratación, desempeño, y características demográficas de cada empleado. Estos datos son cruciales para el análisis y la toma de decisiones en el departamento de Recursos Humanos.

## Objetivo
Los analistas de Recursos Humanos necesitan un dashboard interactivo y dinámico que les permita identificar puntos clave, y con base en ellos, optimizar la gestión del talento y fomentar un entorno laboral más inclusivo y diverso.

## Contexto
- La base contiene 311 registros, con variables como: ID, nombre, sexo, departamento, fecha de ingreso, salida, evaluación, evaluación de desempeño, salario, puesto, etc.
- Los registros son del año 2010 al 2019, con personal activo como inactivo.
- Del total de empleados 135 son hombres ( 43.4%) y 176 mujeres (56.6%). 
- Los departamentos reportados son: Admin Offices, Executive Office, IT/IS, Production, Sales, Software Engineering. Siendo el departamento de Production el que más población tiene. 
   
## Resultados

**1. Departamento de producción**
- El departamento de Producción es el que **mayor cantidad de empleados tiene (67.2% del total)**, por ello se justifica el gasto en relación al salario. Incluso en el año 2010 y 2011 fue el único departamento reportado.
- Desde el 2010 hasta el 2019 refiere un gasto en salarios de: **$12,530,291 (representando el 51% del salario total de la empresa)**.
- En relación a la distribución del personal en relación al sexo, es muy similar a la población general. El 60% son mujeres y 40% hombres.
- La mayoría fueron reclutados a través de LinkedIn (29.1%), Indeed (23.4%) y Google Search (21.0%), Debido a los resultados obtenidos en la evaluación de desempeño se sugiere contemplar aspectos como referencias o incluir criterios más finos que ayuden a identificar al personal con las habilidades requeridas para el puesto. 

<img width="426" height="489" alt="image" src="https://github.com/user-attachments/assets/093abc50-7689-43dc-af81-a300bfaac7ed" />


**2. Ideed y LinkedIn son las mejores fuentes de contratación en relación a productividad**
  - Indeed representa el **27.4%** del total de las contrataciones **87**. LinkedIn con **76** representa el **24.4%**
  - Sin embargo del total del personal calificado en productividad como **excede**, el 32% fueron contratados a través de Indeed y un 24% por LinkedIn.
  - Dentro del criterio de **necesita mejorar**, el 22% corresponde a personal contratado a través de Indeed y un 16% por LinkedIn.
  - Sin embargo del total de personal contratado por **Career Builder, 23**,  ninguno resultó con rendimiento deficiente durante la evaluación.
    
<img width="700" height="237" alt="image" src="https://github.com/user-attachments/assets/e7265061-e755-4e8c-b221-95b07afeba5d" />


**3. Software Engineering e IT/IS son los departamentos evaluados con mejor satisfacción**
  - Todos los departamentos excepto Executive Office hubo personal que evaluó con nivel 5.
  - Los departamentos de **producción y ventas** fueron los que sus evaluaciones oscilan desde el nivel 1 hasta el 5, pero la mayoría de su población evaluó entre **2 y 4.**
  -  Los departamentos de **Software Engineering e IT/IS**, resultaron con las evaluaciones más altas. Ninguno de estos dos departamentos reportaron niveles de 1 y 2 en su evaluación. Por lo tanto se consideran los que mejor satisfacción tienen.
  -  Se sugiere crear un programa para los departamentos de Producción y Ventas, enfocado en identificar oportunidades de mejora que eleven su nivel de satisfacción. 

<img width="707" height="239" alt="image" src="https://github.com/user-attachments/assets/19325eec-43ea-4ab9-88fb-e7b7bba577ec" />

## Dashboard SRLCompanyAnalysis en Tableau
**https://public.tableau.com/app/profile/yunuen.cuevas/viz/SRLCompanyAnalysis/CompaaSRL?publish=yes**

## Contenido de archivos anexos (base datos y Tableau)
  - Base de datos 
  - Exploración y análisis de datos mediante Tableau
  - Cuadros y gráficas de análisis mediante Tableau
  - Dashboard con filtros en Tableau
