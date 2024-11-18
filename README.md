#**MODULO PROYECTO MBD**
## NOMBRE DE LA MAESTRÍA: MAESTRÍA EN INTELIGENCIA DE NEGOCIOS Y CIENCIA DE DATOS
## UNIVERSIDAD DE LAS AMÉRICAS
## NOMBRE DE LOS INTEGRANTES: PAUL ANGAMARCA Y OMAR VASQUEZ

### Problema a resolver: El problema radica en cómo utilizar de manera efectiva el historial de ventas y otras variables relevantes para generar proyecciones que puedan adaptarse a las fluctuaciones del mercado y las particularidades del negocio.
### Modelo seleccionado: Para este trabajo de titulación se seleccionó LSTM
### Base de datos: La base de datos pertenece a Armijos Romero Ltds., por lo que en caso de requerirla, contactar con los autores.

# Proyección de Presupuestos de Ventas: Optimización mediante Modelos Avanzados de Machine Learning

Este repositorio contiene el código y los recursos utilizados para el desarrollo del trabajo de titulación **"Proyección de Presupuestos de Ventas: Optimización mediante Modelos Avanzados de Machine Learning"**. Este proyecto fue realizado como parte de la **Maestría en Inteligencia de Negocios y Ciencia de Datos** de la **Universidad de las Américas**.

## Resumen

El objetivo principal de este proyecto es implementar modelos avanzados de predicción de ventas utilizando técnicas de Machine Learning (ML) y forecasting, como ARIMA, SARIMA, LSTM y Random Forest. La finalidad es mejorar la precisión en la proyección de presupuestos de ventas, optimizando la planificación estratégica y la asignación de recursos.

Los modelos se evalúan mediante métricas como MSE, RMSE, MAE y R². Los resultados demuestran que SARIMA y LSTM ofrecen un rendimiento destacado en términos de precisión y capacidad de adaptación a datos estacionales y temporales.

---

## Contenido del Repositorio

1. **Tesis**: Archivo PDF del trabajo de titulación con el marco teórico, metodología, resultados y conclusiones.
2. **Notebook**: 
    - `Forecasting_AR_RF_LSTM.ipynb`: Contiene el código fuente para la implementación y evaluación de los modelos predictivos.
3. **Resultados**: Gráficos, métricas de evaluación y predicciones generadas por los modelos.

---

## Modelos Implementados

1. **ARIMA (AutoRegressive Integrated Moving Average)**: 
   - Modelo estadístico para series temporales.
   - Adecuado para datos estacionarios.
2. **SARIMA (Seasonal ARIMA)**:
   - Extensión de ARIMA para manejar estacionalidad.
3. **LSTM (Long Short-Term Memory)**:
   - Modelo de redes neuronales recurrentes diseñado para datos secuenciales.
   - Especialmente útil para capturar patrones complejos y no lineales.
4. **Random Forest**:
   - Algoritmo de ensamble basado en árboles de decisión.
   - Robusto frente a ruido y adecuado para conjuntos de datos complejos.

---

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/repositorio.git
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

---

## Uso

1. Abre el notebook `Forecasting_AR_RF_LSTM.ipynb`.
2. Carga los datos de ventas históricos en el formato esperado (consulta la sección de preprocesamiento en el notebook).
3. Ejecuta las celdas para:
   - Procesar y visualizar los datos.
   - Entrenar y evaluar los modelos.
   - Generar predicciones para ventas futuras.

---

## Resultados

Los hallazgos clave incluyen:
- **SARIMA** y **LSTM** mostraron un desempeño superior en términos de precisión.
- La integración de estos modelos en procesos empresariales puede optimizar la planificación presupuestaria y la gestión de inventarios.

---

## Referencias

- **Autor(es)**: Álvaro Paúl Angamarca Pinos, Walter Omar Vásquez Jiménez
- **Profesor**: Manuel Eugenio Morocho, MSc. PhD.
- **Año**: 2024
- **Institución**: Universidad de las Américas (UDLA)

---

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
