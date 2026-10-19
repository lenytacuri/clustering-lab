# Lab 08 — Clustering

Laboratorio de aprendizaje no supervisado con **K-Means, clustering jerárquico y mezclas gaussianas (GMM)**, desarrollado localmente con Python y `uv`.

## Contenido
- Segmentación de clientes de Online Retail mediante variables RFM: recencia, frecuencia y gasto.
- Transformación logarítmica, estandarización y visualización con PCA.
- Selección del número de grupos y comparación de inicializaciones, criterios de enlace y tipos de covarianza.
- Evaluación interna con Silhouette, Davies-Bouldin y Calinski-Harabasz; selección de GMM con BIC/AIC.
- Evaluación externa con ARI y NMI sobre actividades humanas del dataset HAR.
- Retos: cuantización de imágenes, experimentos con PCA y comparación de segmentos entre países.

## Objetivos de aprendizaje
- Preparar datos y construir variables adecuadas para clustering.
- Comprender las diferencias entre asignaciones rígidas y probabilísticas.
- Comparar modelos combinando métricas, interpretabilidad y contexto.
- Distinguir separación geométrica de correspondencia con categorías reales.
- Comunicar resultados y limitaciones sin confundir diferencias descriptivas con significancia estadística.

## Ejecución
Instalar las dependencias con `uv sync` y abrir el notebook con `uv run jupyter lab clustering.ipynb`.
