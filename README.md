# Análisis de Evasión de Clientes (Churn) - Telecom X

## 📌 Descripción

Este proyecto analiza la **evasión de clientes (churn)** de la compañía **Telecom X** utilizando datos proporcionados en formato JSON.  
El objetivo es **identificar patrones y factores asociados a la cancelación de servicios**, y generar insights que permitan **reducir la evasión** mediante estrategias informadas.

Se realizó todo el análisis en **Python** usando **Pandas, Matplotlib y Seaborn** dentro de un **notebook de Google Colab**.

---

## 🧰 Tecnologías y librerías

- Python 3.12
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Contenido del repositorio

- `TelecomX_Churn_Analysis.ipynb` → Notebook principal con todo el análisis:
  - Importación y limpieza de datos
  - Exploración de variables categóricas y numéricas
  - Visualizaciones (boxplots, histogramas, countplots)
  - Conclusiones e insights
  - Recomendaciones estratégicas
- `README.md` → Este archivo

---

## 📝 Objetivos del análisis

1. Explorar los datos de clientes y servicios de Telecom X.  
2. Identificar variables asociadas con la **evasión de clientes**.  
3. Visualizar patrones de comportamiento mediante gráficos y estadísticas descriptivas.  
4. Proporcionar **recomendaciones estratégicas** para reducir churn.

---

## 📊 Análisis realizado

- Variables categóricas analizadas:  
  - Género, tipo de contrato, método de pago, servicios adicionales (internet, TV, seguridad, etc.)
- Variables numéricas analizadas:  
  - Total gastado (`account_charges_total`)  
  - Gasto mensual (`account_charges_monthly`)  
  - Tiempo de contrato / antigüedad (`tenure`)
- Visualizaciones:
  - **Countplots** para categorías vs churn  
  - **Boxplots y histogramas** para numéricas vs churn

> Los gráficos permiten identificar clientes con mayor riesgo de cancelación y patrones de comportamiento.

---

## 💡 Conclusiones e insights

1. La **antigüedad del cliente** y el **total gastado** son factores clave asociados a la evasión.  
2. Clientes con **contratos mensuales** presentan mayor riesgo de churn.  
3. Métodos de pago automatizados reducen la probabilidad de abandono.  
4. Género y algunas variables demográficas tienen menor impacto.

---

## 📈 Recomendaciones estratégicas

1. Incentivar **fidelización de clientes nuevos** con descuentos o beneficios iniciales.  
2. Promover **contratos a largo plazo** (anual o 2 años).  
3. Fomentar **pagos automáticos** para evitar cancelaciones por inconvenientes de facturación.  
4. Implementar **seguimiento personalizado** para clientes con menor antigüedad o gasto.  
5. Monitorear métricas clave para **detectar riesgos tempranos**.

---

## 🚀 Cómo ejecutar el notebook

1. Abrir `TelecomX_Churn_Analysis.ipynb` en **Google Colab**.  
2. Ejecutar todas las celdas para cargar los datos, procesarlos y generar los gráficos.  
3. Analizar los resultados y revisar las conclusiones y recomendaciones.

> Nota: Asegúrate de tener conexión a internet para acceder al JSON de la API.

---

## 📎 Referencias

- [GitHub - Datos de Telecom X](https://github.com/ingridcristh/challenge2-data-science-LATAM)  
- [Documentación Pandas](https://pandas.pydata.org/docs/)  
- [Documentación Seaborn](https://seaborn.pydata.org/)  
- [Documentación Matplotlib](https://matplotlib.org/stable/contents.html)

---

## 👤 Autor

**Fernando Aquino** - Proyecto de análisis de datos y visualización en Python
