<!-- Encabezado principal -->
<h1 align="center">🚕 Análisis de Viajes Uber – Relación Tiempo–Lugar</h1>

<!-- Contexto narrativo -->
<p align="justify">
Este proyecto analiza los patrones de continuidad de viajes en <strong>Uber</strong>, buscando responder a una pregunta clave: 
¿en qué ubicaciones un viaje finalizado es seguido por otro que inicia en el mismo punto dentro de un intervalo máximo de <strong>30 minutos</strong>?  
El objetivo es identificar zonas estratégicas de alta recurrencia, optimizar la asignación de conductores y anticipar la demanda en ubicaciones específicas.
</p>

<p align="justify">
El análisis combina técnicas de <em>Data Cleaning</em>, generación de variables derivadas (duración de viaje, intervalos, franjas horarias) y cálculos de percentiles para evaluar tiempos de espera.  
Posteriormente, los hallazgos se trasladan a un dashboard interactivo en <strong>Power BI</strong>, donde se visualizan los patrones espacio–temporales y las ubicaciones más representativas.
</p>

<!-- Enlace al reporte -->
<p align="center">
<a href="https://app.powerbi.com/view?r=eyJrIjoiNWFjMTQwZDUtNTg5Ni00MzE3LTlhNmMtOTVkN2Q2ZGYxOGUyIiwidCI6IjQ5ZWM5ZjUyLThlMjgtNGIyMC1hNDQxLTkyZWJmMjZjNTQ0YyIsImMiOjR9" style="font-size: 18px; text-decoration: none; color: #0056b3; font-weight: bold;">
📄 Ver Reporte Completo en Power BI
</a>
</p>

<hr>

<h2>🎯 Objetivo del Análisis</h2>
<p align="justify">
Evaluar la recurrencia de viajes en mismo lugar y tiempo bajo un umbral de 30 minutos, para:  
</p>
<ol>
  <li>📊 Medir la frecuencia global de coincidencias.</li>
  <li>🔍 Identificar ubicaciones con mayor probabilidad de reactivación.</li>
  <li>⏱ Analizar la distribución de intervalos con percentiles (25, 50 y 75).</li>
  <li>🌍 Visualizar patrones de demanda mediante mapas de calor y tablas dinámicas.</li>
</ol>

<hr>

<h2>💡 Hallazgos Clave</h2>
<ul>
  <li align="justify"><strong>% Coincidencia global:</strong> 19,65%. Aproximadamente 1 de cada 5 viajes se repite desde el mismo punto en ≤30 min.</li>
  <li align="justify"><strong>Percentiles:</strong> P25 = 32 min, P50 = 96 min, P75 = 544 min. Estos valores muestran cómo se distribuyen los tiempos de espera entre viajes consecutivos.</li>
  <li align="justify"><strong>Top ubicaciones con mínimo 10 viajes posteriores:</strong> 
    <ul>
      <li>Edgehill Farms → 50% de probabilidad, intervalo promedio 16,4 min.</li>
      <li>Westpark Place → 37,5% de probabilidad, intervalo promedio 42,9 min.</li>
      <li>Islamabad → 35,1% de probabilidad, intervalo promedio 122,8 min.</li>
      <li>Morrisville → 31,0% de probabilidad, intervalo promedio 176,8 min.</li>
    </ul>
  </li>
  <li align="justify"><strong>Mapa de calor:</strong> evidencia que las zonas con mayor concentración de viajes repetidos coinciden con hubs de alta movilidad.</li>
</ul>

<hr>

<h2>📌 Indicadores Clave</h2>
<ul>
  <li>📍 Total viajes analizados: 1.150</li>
  <li>📍 Millas recorridas: 121.198</li>
  <li>📍 Duración promedio: 23,3 min</li>
  <li>📍 Lift en zonas críticas: hasta 2,5 veces mayor que el promedio global</li>
</ul>

<hr>

<h2>📋 Conclusiones y Recomendaciones</h2>
<p align="justify">
El análisis muestra que, aunque la coincidencia global es relativamente baja (19%), existen <strong>zonas estratégicas</strong> con alta probabilidad de generar viajes consecutivos en menos de 30 minutos.  
Conocer estos patrones permite al negocio:
</p>
<ol>
  <li>🚀 Optimizar la asignación de conductores en ubicaciones clave.</li>
  <li>🕒 Reducir tiempos de espera al anticipar la reactivación de viajes.</li>
  <li>🌍 Identificar focos de movilidad recurrente con valor táctico y estratégico.</li>
  <li>📊 Usar percentiles como referencia práctica de “qué tan rápido” se reanudan los viajes, más allá del promedio.</li>
</ol>