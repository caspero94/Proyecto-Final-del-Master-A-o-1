![Imagen del dashboard](https://github.com/caspero94/Proyecto-Final-del-Master-Data-1/blob/3977ffb06694a3c187d92dc1a617678480063cc1/Dashboard.png)

---

# 📊 Proyecto Final Máster Data Analytics  
## Análisis del Paro en España (2021 - 2024)  

![España Paro](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Flag_of_Spain.svg/320px-Flag_of_Spain.svg.png)

---

## 📌 Descripción del Proyecto  

Este proyecto tiene como objetivo analizar la **evolución del desempleo en España entre 2021 y 2024**, aplicando técnicas de **transformación, limpieza, análisis exploratorio (EDA), análisis estadístico y visualización de datos**, culminando en un **dashboard interactivo**.  

Se han utilizado **fuentes oficiales de datos del paro registrado y del censo poblacional por municipios**, generando un dataset final con **más de 48.000 registros y 29 columnas**.  

---

## 🛠️ Metodología  

1. **Recolección de datos**  
   - 4 datasets de **paro registrado mensual** (2021-2024), desglosados por:
     - Sector económico (servicios, industria, construcción, agricultura, sin empleo previo).  
     - Género (hombres y mujeres).  
     - Rangos de edad (<25, 25-45, >45).  
   - 1 dataset del **censo oficial de población municipal por edad y sexo** (INE).  

2. **Transformación y limpieza**  
   - Unificación de criterios temporales (periodos mensuales).  
   - Agrupación de población activa en tres rangos de edad y por sexo para comparabilidad con los datos del paro.  
   - Generación de nuevas métricas como **tasa de paro relativa** y **población activa estimada**.  
   - Eliminación de redundancias y nulos.

3. **Análisis realizado**  
   - 📈 Análisis descriptivo de tendencias.  
   - 📊 Análisis estadístico de distribución por género, edad, sector y comunidad autónoma.  
   - 🌍 Comparación geográfica entre regiones con mayor y menor desempleo.  
   - 📉 Evolución de la población activa.  

4. **Visualización y Dashboard**  
   - Creación de gráficos exploratorios (líneas, barras, boxplots).  
   - Dashboard final en **Power BI** para interactuar con los datos y visualizar indicadores clave.  

---

## 🔎 Principales Conclusiones  

✅ **Tendencia general del paro**  
- El desempleo presenta una **clara tendencia descendente**.  
- La caída fue más pronunciada en **2021-2022**, con un ritmo de reducción más lento en **2023-2024**.  

✅ **Brecha de género**  
- El paro es **consistentemente más elevado en mujeres que en hombres**, confirmando una desigualdad estructural en el mercado laboral.  

✅ **Impacto por edad**  
- El desempleo se concentra en **mayores de 45 años** tanto en hombres como en mujeres.  
- El grupo <25 años representa menor volumen, aunque más inestable en variación.  

✅ **Distribución sectorial**  
- El **sector servicios** es el principal foco de desempleo, con amplia diferencia respecto a los demás.  
- Sectores **industria, construcción y sin empleo previo** se mantienen en niveles similares y descendentes.  
- El paro agrícola es **prácticamente insignificante**.  

✅ **Análisis territorial**  
- Comunidades con **menores tasas de paro**: Aragón, Islas Baleares, La Rioja, Madrid y Cataluña.  
- Regiones con **mayores tasas de paro**: Ceuta, Melilla y Andalucía.  

✅ **Evolución de la población activa**  
- Ligera **caída en 2022**, posiblemente asociada a recuperación pos-COVID y dinámicas migratorias.  
- Crecimiento sostenido en 2021, 2023 y 2024.  

---

## 📌 Nota metodológica  

> ⚠️ Este análisis no se basa en la **Encuesta de Población Activa (EPA)**, sino en el **censo oficial de población municipal**, con agrupaciones por edad y sexo diseñadas específicamente para este estudio.  
>
> Esto puede generar **ligeras divergencias respecto a las cifras del INE**, pero aporta una **mayor granularidad territorial (nivel municipal)** y un enfoque complementario para el análisis.  

---

## 📊 Dashboard  

📍 El dashboard final ha sido implementado en **Power BI**, permitiendo explorar:  
- Evolución temporal del paro por sector.  
- Comparativa por género y edad.  
- Mapas interactivos de comunidades autónomas.  
- Indicadores de población activa y tasa de paro relativa.  

🔗 *(https://app.powerbi.com/groups/me/reports/86a6bd35-44a4-4c4b-b075-785a5b68198e/92b0cd4005a668857a08?experience=power-bi)*  

---

## 🏆 Reflexión Final  

Este proyecto refleja la importancia de:  
- Integrar múltiples fuentes de datos.  
- Trabajar con criterios de **limpieza y homogeneización**.  
- Ir más allá del análisis descriptivo, aplicando comparaciones territoriales y poblacionales.  
- Presentar resultados en un **formato visual y accesible** para la toma de decisiones.  

📌 El paro en España sigue siendo un reto estructural, con mejoras progresivas, pero con focos de desigualdad por género, edad y región que requieren políticas diferenciadas.  

---

✒️ Autor: *Pedro P.*  
📅 Máster Data Analytics – Proyecto Final 2025  

---


