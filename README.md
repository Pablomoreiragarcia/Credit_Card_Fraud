En este notebook se analiza un conjunto de datos de transacciones con tarjeta de crédito con el objetivo de **detectar operaciones fraudulentas** mediante modelos de *Machine Learning* supervisado.

El flujo de trabajo será el siguiente:

1. **Análisis exploratorio de datos (AED)**  
   - Entender la estructura del dataset y las variables disponibles.  
   - Analizar la distribución de la clase objetivo (fraude / no fraude).  
   - Explorar distribuciones de variables relevantes y posibles patrones.

2. **Preprocesamiento**  
   - Selección y transformación de variables (por ejemplo, escalado de `Amount` y `Time`).  
   - Tratamiento del desbalanceo de clases (fraude es una clase minoritaria).

3. **Modelado**  
   - Entrenamiento de varios modelos de clasificación.  
   - Evaluación con métricas adecuadas para datos desbalanceados.  

4. **Conclusiones**  
   - Interpretación de los resultados.  
   - Posibles mejoras y líneas de trabajo futuras.
