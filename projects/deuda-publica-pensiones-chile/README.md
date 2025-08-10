<div style="text-align: justify; text-justify: inter-word;">

## 📊 Estimación de la deuda implícita en pensiones en Chile
<p>Este proyecto analiza la sostenibilidad del sistema de pensiones chileno mediante la estimación de la deuda implícita en pensiones, entendida como el valor presente de las obligaciones que el Estado mantiene con los pensionados actuales y futuros. El estudio se enmarca en un contexto de aumento sostenido en la esperanza de vida y disminución de las tasas de mortalidad, lo que genera presiones sobre el gasto fiscal y plantea desafíos para el financiamiento de las pensiones. La metodología empleada permite cuantificar estas obligaciones y proyectar su evolución en el tiempo.</p>

## 🛠️ Metodología y fuentes de datos
<p>El desarrollo del trabajo se basa en la proyección de tasas de mortalidad utilizando el modelo de Lee-Carter, ajustado a datos chilenos obtenidos de la Human Mortality Database (HMD), que provee tasas centrales de mortalidad específicas por edad para el período 1992-2019. Las proyecciones de población por edad y sexo provienen del World Population Prospects (ONU), aplicando el método de componentes de cohorte. Las tasas de interés reales se obtienen de la Comisión para el Mercado Financiero (CMF), usando el promedio de rentas vitalicias de vejez, vejez anticipada e invalidez. El gasto público en pensiones como porcentaje del PIB se extrae de las estadísticas de la OECD. Con estos insumos, se calcula el Capital Necesario Unitario (CNU) y, posteriormente, la deuda implícita en pensiones como porcentaje del PIB para distintos años.</p>

## 📈 Resultados principales
<p>Los resultados muestran que en Chile la deuda implícita en pensiones para 2019 equivale aproximadamente al 20% del PIB, con variaciones asociadas a cambios en la mortalidad y tasas de interés. Se observa que las mujeres presentan una deuda mayor que los hombres, debido a su mayor esperanza de vida, lo que eleva el CNU en comparación con el de los varones. Además, el análisis revela que el CNU tenderá a aumentar en las próximas décadas, impulsado por bajas tasas de mortalidad y de interés, encareciendo así el costo de financiar las pensiones.</p>

## 🎯 Conclusiones y proyecciones
<p>En conclusión, el estudio evidencia que el sistema chileno enfrenta un reto creciente de sostenibilidad financiera debido al envejecimiento poblacional y la prolongación de la vida post-jubilación. Medir y proyectar la deuda implícita permite anticipar escenarios y diseñar políticas públicas más efectivas, como ajustes en la edad de jubilación, promoción de ahorro previsional complementario y optimización en la gestión de fondos. El código en R incluido en este repositorio implementa todo el proceso: desde la limpieza y modelación de datos hasta la obtención de los indicadores y gráficos presentados.</p>

</div>
