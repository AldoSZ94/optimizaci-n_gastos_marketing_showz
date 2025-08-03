# 📊 Proyecto Sprint 9: Optimización de Gastos de Marketing en Showz

## Descripción  
Este es mi proyecto correspondiente al **Sprint N.º 9** dentro de mi formación como **Analista de Datos Jr. en TripleTen**. Se desarrolla para **Showz**, una empresa dedicada a la venta de entradas para eventos.

El objetivo es analizar datos históricos de visitas, pedidos y gastos de marketing para comprender el comportamiento de los clientes, evaluar la efectividad de las fuentes de adquisición y optimizar la inversión en marketing.

---

## Objetivos principales  

- Analizar el uso del servicio por parte de los clientes (visitas y sesiones).  
- Determinar cuándo los usuarios comienzan a comprar y su valor monetario (LTV).  
- Calcular el costo de adquisición por fuente de marketing.  
- Evaluar la rentabilidad de las inversiones (ROMI).  
- Recomendar estrategias de inversión basadas en métricas clave y patrones detectados.

---

## Metodología  

1. **Preparación y limpieza de datos**  
   Carga y optimización de datasets (`visits_log_us.csv`, `orders_log_us.csv`, `costs_us.csv`). Asegurar tipos de datos correctos para análisis.

2. **Análisis exploratorio y métricas clave**  
   - Visitas: usuarios diarios, sesiones, duración y frecuencia de regreso.  
   - Ventas: tiempo hasta la primera compra, número y tamaño promedio de pedidos, LTV.  
   - Marketing: gastos totales y por fuente, costo de adquisición y rentabilidad (ROMI).  
   Visualización de resultados y análisis por dispositivo y fuente.

3. **Conclusiones y recomendaciones**  
   Basadas en las métricas y tendencias halladas, se aconseja a los expertos de marketing sobre dónde y cuánto invertir.

---

## Datos utilizados  

- **visits_log_us.csv**: registros de visitas y sesiones de usuarios entre enero 2017 y diciembre 2018.  
- **orders_log_us.csv**: información de pedidos realizados por los usuarios en el mismo período.  
- **costs_us.csv**: gastos diarios en diferentes fuentes de marketing.

---

## Herramientas y tecnologías  

- Python (pandas, matplotlib, seaborn)  
- Jupyter Notebook  
- Análisis estadístico y visualización de datos  

---

## Formato del proyecto  

El análisis se presenta en un Jupyter Notebook con código en celdas de tipo *code* y explicaciones en *markdown*, aplicando formato y encabezados claros para facilitar la comprensión.

---

## Conclusión  

Este estudio permitirá optimizar la inversión en marketing para Showz, recomendando las fuentes y estrategias más rentables según el comportamiento real de los usuarios y el retorno sobre la inversión.

