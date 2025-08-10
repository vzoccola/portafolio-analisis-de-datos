<!-- Encabezado principal -->
<h1 align="center">📌 Predicción de Precios de Autos Usados en el Reino Unido</h1>

<p style="text-align: justify;">
El objetivo del proyecto es desarrollar un modelo de machine learning capaz de predecir el precio de autos usados en el Reino Unido, utilizando datos históricos de publicaciones reales.
</p>

<p style="text-align: justify;">
En el mercado automotriz de segunda mano, estimar de forma precisa el valor de un vehículo permite:
</p>

<ul style="text-align: justify;">
    <li>Optimizar la fijación de precios por parte de concesionarios y vendedores.</li>
    <li>Ayudar a compradores a identificar ofertas justas.</li>
    <li>Mejorar la competitividad de plataformas de venta online.</li>
</ul>

<p style="text-align: justify;">
El dataset utilizado fue extraído de 
<a href="https://www.kaggle.com/datasets/muhammadawaistayyab/used-cars-prices-in-uk/data" target="_blank">Kaggle</a>
y contiene <strong>3.685 registros</strong> con <strong>13 características</strong> por vehículo, incluyendo marca, modelo, año, kilometraje, tipo de combustible, transmisión, entre otros.
</p>

<h2>🔍 Metodología</h2>
<ol style="text-align: justify;">
    <li>
        <strong>Exploración y limpieza de datos</strong>
        <ul>
            <li>Eliminación de valores nulos e inconsistencias.</li>
            <li>Conversión de tipos de datos.</li>
            <li>Tratamiento de outliers.</li>
        </ul>
    </li>
    <li>
        <strong>Transformación de variables</strong>
        <ul>
            <li>Codificación de variables categóricas.</li>
            <li>Escalado y normalización de datos numéricos.</li>
        </ul>
    </li>
    <li>
        <strong>Entrenamiento del modelo</strong>
        <ul>
            <li>Algoritmo: Regresión Lineal.</li>
            <li>Separación en conjunto de entrenamiento y prueba.</li>
        </ul>
    </li>
    <li>
        <strong>Evaluación</strong>
        <ul>
            <li>Métricas: R², MAE, MSE, RMSE.</li>
        </ul>
    </li>
</ol>

<h2>📊 Resultados</h2>
<ul style="text-align: justify;">
    <li><strong>R²</strong> = 0,67 → El modelo explica un 67% de la variabilidad de los precios.</li>
    <li><strong>MAE</strong> ≈ £1.880 → Error absoluto medio.</li>
    <li><strong>RMSE</strong> ≈ £2.710 → Desviación típica del error.</li>
</ul>

<h2>🏁 Conclusión</h2>
<p style="text-align: justify;">
El modelo entrega predicciones razonablemente cercanas al valor real, con un margen de error que lo hace útil como herramienta de referencia para estimaciones rápidas. La ejecución de este proyecto demuestra competencias clave en limpieza de datos, transformación de variables, selección y aplicación de modelos, así como en la interpretación de métricas de rendimiento, asegurando un proceso de análisis reproducible y escalable para entornos de negocio reales.
</p>
