# Comparación de algoritmos de aprendizaje supervisado: KNN, SVM y MLP

Comparación de tres clasificadores (KNN, SVM y red neuronal MLP) sobre el dataset *Wisconsin Diagnostic Breast Cancer*: 569 tumores descritos con 30 características, clasificados como benignos o malignos.

**Equipo:** Morales Mendez Shryley Nicoles, Jimenez Andrade Monserrat, Tejero Hernandez Rubi, Sarao Morales Rubi.
**Curso:** Fundamentos de inteligerncia artifical LITIID-71

## Contenido
| Archivo | Descripción |
|---|---|
| `Comparacion_KNN_SVM_MLP.ipynb` | Notebook con el desarrollo, resultados, gráficas y conclusiones |
| `data/wdbc.data`, `data/wdbc.names` | Dataset y su descripción |



## Resultados (conjunto de prueba, 114 casos)
| Modelo | Exactitud | Precisión | Exhaustividad | F1 | Errores |
|---|---|---|---|---|---|
| KNN | 0.9561 | 0.9744 | 0.9048 | 0.9383 | 5 |
| SVM | 0.9737 | 1.0000 | 0.9286 | 0.9630 | 3 |
| MLP | 0.9649 | 1.0000 | 0.9048 | 0.9500 | 4 |

La SVM obtuvo el mejor resultado; el análisis completo está en el notebook.