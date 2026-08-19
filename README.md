# sprint7-final-project
# Análisis Exploratorio de Datos y Segmentación de Clientes - ConnectaTel

## 🎯 Objetivo del Proyecto
El propósito de este proyecto es analizar el comportamiento de consumo de los usuarios de telecomunicaciones de ConnectaTel, identificando patrones de uso (mensajes, llamadas y minutos consumidos), analizando la presencia de valores atípicos (*outliers*) y segmentando a la base de clientes por edad y nivel de consumo para brindar recomendaciones estratégicas de negocio.

---

## 📊 Datasets Utilizados
El análisis se fundamenta en los datos consolidados de perfiles de usuario (`user_profile`):
* **`user_id`**: Identificador único del cliente.
* **`age`**: Edad del usuario.
* **`city`**: Ciudad de residencia.
* **`plan`**: Tipo de plan contratado (*Básico* o *Premium*).
* **`cant_mensajes`**: Cantidad de mensajes enviados.
* **`cant_llamadas`**: Cantidad de llamadas realizadas.
* **`cant_minutos_llamada`**: Total de minutos consumidos en llamadas.

---

## 🛠️ Etapas del Análisis
1. **Limpieza y Preparación de Datos:** Tratamiento de valores nulos, corrección de tipos de datos y verificación de consistencia.
2. **Análisis Exploratorio de Datos (EDA):** Evaluación de distribuciones mediante histogramas y análisis de sesgo por tipo de plan.
3. **Análisis de Outliers (IQR):** Detección de valores extremos mediante Diagramas de Caja (*Boxplots*) y cálculo de límites con el Rango Intercuartílico (*IQR*).
4. **Segmentación de Clientes:**
   * **Por Uso:** Categorización en *Bajo uso*, *Uso medio* y *Alto uso* según métricas de llamadas y mensajes.
   * **Por Edad:** Clasificación en *Joven*, *Adulto* y *Adulto Mayor*.
5. **Insights Ejecutivos y Recomendaciones:** Formulación de estrategias orientadas a *upselling* y diseño de planes para usuarios intensivos.

---

## 🚀 Cómo Ejecutar el Notebook
1. Clona este repositorio o descarga el archivo `.ipynb`.
2. Abre el proyecto en **Google Colab** o en **Jupyter Notebook**.
3. Asegúrate de tener instaladas las librerías necesarias:
   ```bash
   pip install pandas numpy matplotlib seaborn
