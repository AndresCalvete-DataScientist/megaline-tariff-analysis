## 📱 Análisis comparativo de planes telefónicos Megaline

### 📌 Introducción

Este proyecto analiza el comportamiento de los clientes del operador de telecomunicaciones **Megaline**, el cual ofrece dos tarifas prepago: **Surf** y **Ultimate**. El objetivo es evaluar cuál de estas tarifas genera más ingresos y cómo varía el comportamiento de uso entre diferentes tipos de usuarios, mediante un análisis de llamadas, mensajes e internet.

### Objetivo

Analizar los patrones de consumo y los ingresos generados por los usuarios de Megaline para determinar:
- Cuál tarifa es más rentable.
- Si existen diferencias significativas entre regiones o planes.
- Qué plan debería recibir mayor inversión en publicidad.

---

### 🧠 Habilidades técnicas demostradas

Este proyecto demuestra competencias clave en ciencia de datos, particularmente en la exploración, análisis estadístico, visualización de datos y pruebas de hipótesis. Se aplicaron las siguientes habilidades:

- **Limpieza y transformación de datos**: tratamiento de nulos, conversión de formatos de fecha y categorización de planes.
- **Análisis exploratorio de datos (EDA)**: detección de patrones de uso por tipo de servicio (llamadas, mensajes, datos).
- **Funciones**: cálculo de ingresos personalizados por usuario a partir del uso mensual.
- **Agrupación y segmentación de datos**: análisis mensual por cliente.
- **Visualización de datos**: uso de `matplotlib` y `seaborn` para analizar comparaciones y distribuciones.
- **Pruebas de hipótesis estadísticas**: uso de `scipy.stats` para validar si las diferencias de ingresos son estadísticamente significativas.
- **Inteligencia de negocio**: recomendaciones basadas en datos para la toma de decisiones estratégicas.
- **Documentación clara**: estructuración del análisis y comentarios explicativos en el notebook.

---

### 🛠️ Tecnologías y herramientas utilizadas

- **Python**: lenguaje base del análisis.
- **pandas**: manipulación y análisis tabular.
- **matplotlib**: visualización de datos.
- **seaborn**: visualización avanzada y estilizada.
- **scipy.stats**: pruebas estadísticas.
- **Funciones clave**: `.groupby()`, `.merge()`, `.pivot_table()`, `.value_counts()`, `ttest_ind()`

---

### ✅ Resultados y conclusiones

- El plan **Surf** tiene un mayor número de usuarios que el plan **Ultimate**, lo que indica que es más popular entre los clientes.
- Las diferencias de ingresos entre los planes **Surf** y **Ultimate** son estadísticamente significativas, lo que respalda la decisión de priorizar el plan Surf en futuras campañas publicitarias.
- Los usuarios del plan **Ultimate** generan ingresos más estables que los de **Surf**.
- El comportamiento de uso no varía significativamente entre planes por tipo de servicio (llamadas, mensajes, internet).

---

### 📈 Posibles mejoras futuras

- Realizar segmentación de usuarios mediante clustering (`KMeans`) para detectar perfiles de clientes.
- Implementar modelos de predicción para anticipar ingresos por cliente.
- Implementar modelos de predicción para anticipar abandonos por cliente.

---

### 👨‍💻 Autor

**Andrés Calvete**  
Científico de Datos Junior  
[LinkedIn](https://www.linkedin.com/in/andrescalvete/)  
ascalvete@hotmail.com
