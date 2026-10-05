# Ciencia de Datos

Trabajos de la materia Ciencia de Datos de la Tecnicatura en Análisis de Datos e Inteligencia Artificial: casos prácticos de implementación de modelos y un tablero en Power BI.

## Contenido

| Archivo | Descripción |
|---------|-------------|
| [casos_practicos_implementacion_cdd2.py](casos_practicos_implementacion_cdd2.py) | Casos prácticos de implementación (Grupo 2): clasificación de dígitos con red neuronal, ajuste de hiperparámetros de bosques aleatorios, efecto de `max_depth` en árboles de decisión, con métricas y gráficos. Exportado desde Google Colab. |
| [informes/informe_casos_practicos_implementacion.pdf](informes/informe_casos_practicos_implementacion.pdf) | Informe de los casos prácticos: metodología, resultados y conclusiones. |
| [Inmuebles_II.pbix.zip](Inmuebles_II.pbix.zip) | Tablero de Power BI (Inmuebles II) descomprimido como `.pbix`. |

## Cómo ejecutar el script

```bash
pip install numpy pandas matplotlib scikit-learn
python casos_practicos_implementacion_cdd2.py
```

Los datasets se generan o descargan desde scikit-learn: no se requieren archivos locales.

## Temas cubiertos

- Redes neuronales para clasificación de patrones (dígitos)
- Bosques aleatorios: efecto de sus hiperparámetros en la precisión
- Árboles de decisión: complejidad, ajuste y sobreajuste
- Métricas de clasificación y visualización de resultados
- Dashboards con Power BI

## Licencia

MIT
