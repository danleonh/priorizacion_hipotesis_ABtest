# Proyecto 10 – Priorización de Hipótesis y Análisis de Resultados A/B Testing

## 📋 Descripción general
El objetivo de este proyecto fue **priorizar hipótesis de negocio y analizar los resultados de una prueba A/B** para una tienda en línea.  
A través de técnicas estadísticas y visualizaciones, se buscó determinar qué grupo presentó un mejor rendimiento en términos de conversión e ingresos, validando si las diferencias observadas son estadísticamente significativas.

---

## 🎯 Objetivos
- Aplicar los frameworks **ICE** y **RICE** para priorizar hipótesis de crecimiento.  
- Evaluar los resultados del experimento A/B y comparar métricas clave entre los grupos A y B.  
- Analizar la **conversión, ingresos promedio y comportamiento de los usuarios**.  
- Identificar el grupo con mejor desempeño y emitir una recomendación final basada en evidencia.

---

## 🧮 Datos utilizados
**Datasets principales:**
- `hypotheses_us.csv` – Hipótesis con sus puntuaciones de Impact, Confidence, Effort y Reach.  
- `orders_us.csv` – Registros de pedidos: ID de transacción, usuario, fecha, ingresos y grupo experimental.  
- `visits_us.csv` – Cantidad de visitas por fecha y grupo.  

Periodo analizado: junio a agosto de 2019.

---

## 🧰 Herramientas y librerías
- Python  
- pandas, numpy, scipy  
- matplotlib, seaborn, plotly  
- Jupyter Notebook  

---

## 📊 Etapas del análisis
1. **Priorización de hipótesis** mediante los métodos **ICE** y **RICE**.  
2. **Análisis exploratorio** de los datos de pedidos y visitas.  
3. **Cálculo de ingresos acumulados** y tasa de conversión por grupo.  
4. **Identificación de outliers** en ingresos y número de pedidos por usuario.  
5. **Pruebas estadísticas** (Mann–Whitney U Test) para comparar conversiones e ingresos.  
6. **Conclusiones sobre la efectividad del experimento.**

---

## 🔍 Resultados principales
- La priorización con **RICE** modificó el orden de importancia respecto a **ICE**, al considerar el factor *Reach*.  
- El grupo **B** mostró un incremento del **16 % en la tasa de conversión** frente al grupo A.  
- Se observó **diferencia estadísticamente significativa (p < 0.05)** en la conversión entre grupos.  
- No hubo diferencias significativas en el tamaño promedio de pedido después de eliminar outliers.  

---

## 💡 Conclusiones
- Se recomienda **adoptar la estrategia implementada en el grupo B**, dado su mejor desempeño en conversión.  
- El uso del método **RICE** es más efectivo para priorizar hipótesis en entornos con múltiples variables.  
- La exclusión de valores atípicos permitió obtener resultados más consistentes y confiables.  


