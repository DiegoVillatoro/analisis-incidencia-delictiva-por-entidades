# Analisis de la incidencia delictiva por entidades
<p>Se llevó a cabo un análisis con datos de la CONAPO y del SESNSP para evaluar los delitos absolutos, relativos y la tendencia de crímen por entidades.</p>
<p>Los datos de la CONAPO para la estimación de la población anual se obtuvieron de https://www.gob.mx/conapo/documentos/bases-de-datos-de-la-conciliacion-demografica-1950-a-2019-y-proyecciones-de-la-poblacion-de-mexico-2020-a-2070</p>
<p>Los datos de la incidencia delictiva del 2015-abril 2024 se obtuvieron de https://www.gob.mx/sesnsp/acciones-y-programas/datos-abiertos-de-incidencia-delictiva, la comparación con años anteriores se realizó con los datos disponibles de la metodología anterior quee se puede descargar en el mismo sitio.</p>

<p>Se usaron 3 métricas para evaluar la incidencia delitiva, los delitos absolutos, los delitos relativos por cada 100 000 habitantes y la tendencia del crímen en porcentaje (https://www.nj.gov/njsp/info/ucr2000/pdf/calc_ucr2000.pdf) que se obtiene comparando el año presente con el año anterior. </p>

$\text{delitos absolutos} = \text{Delitos totales cometidos por entidad}$
$\text{delitos relativos} = \frac{\text{Delitos absolutos}}{\text{Población/100 000}}$

$\text{delitos relativos año presente} = \frac{\text{Delitos año presente}}{\text{Población año presente}}$
$\text{delitos relativos año pasado} = \frac{\text{Delitos año pasado}}{\text{Población año pasado}}$
$\text{Tendencia de crímen} = \frac{\text{Delitos relativos año presente}-\text{delitos relativos año pasado}}{\text{delitos relativos año pasado}}$

<p>La gráfica contempla un delito, en cada columna se coloca cada una de las métricas mencionadas anteriormente y cada fila representa un año del 2016 al 2024. Para el cálculo de la tendencia del año 2024, se compara el total de delitos de enero-abril del 2024 con el total de delito de enero-abril del 2023. Al lado derecho se coloca la tendencia nacional del delito.</p>
![Homicidio doloso](https://github.com/DiegoVillatoro/analisis-incidencia-delictiva-por-entidades/assets/45828192/dbde410c-cb04-477d-bd55-aad531668e35)

<p>La coloración usada para representar los aumentos y decrementos de cada delitos fue:</p>

*Verde oscuro ('#548235') si el delito se redujo más del 40%
*Verde claro ('#B0DD7F') si el delito se redujo hasta un 40%
*Amarillo ('#E6AF00') si el delito se mantuvo igual (0%) o tuvo un aumento de menos del 10%
*Rojo claro ('#FFB3B3') si el delito aumentó entre el 10% y 60%
*Rojo oscuro ('#D00000') si el delito aumentó entre el 60% y 500%
*Rojo muy oscuro ('#8C0000') si el delito aumentó más del 500%

![calderon](https://github.com/DiegoVillatoro/analisis-incidencia-delictiva-por-entidades/assets/45828192/f9cce135-aa14-4c46-a112-dc34813a2687)
![epn](https://github.com/DiegoVillatoro/analisis-incidencia-delictiva-por-entidades/assets/45828192/a25868ad-cc92-4828-9f25-c5053580f8c9)
![amlo](https://github.com/DiegoVillatoro/analisis-incidencia-delictiva-por-entidades/assets/45828192/8843289f-874f-4438-846f-3900a43654be)
