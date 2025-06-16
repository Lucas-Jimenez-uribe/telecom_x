# telecom_x

Has sido contratado como asistente de análisis de datos en Telecom X y formarás parte del proyecto "Churn de Clientes". La empresa enfrenta una alta tasa de cancelaciones y necesita comprender los factores que llevan a la pérdida de clientes.

Tu desafío será recopilar, procesar y analizar los datos, utilizando Python y sus principales bibliotecas para extraer información valiosa. A partir de tu análisis, el equipo de Data Science podrá avanzar en modelos predictivos y desarrollar estrategias para reducir la evasión.

¿Qué vas a practicar?
✅ Importar y manipular datos desde una API de manera eficiente.
✅ Aplicar los conceptos de ETL (Extracción, Transformación y Carga) en la preparación de los datos.
✅ Crear visualizaciones estratégicas para identificar patrones y tendencias.
✅ Realizar un Análisis Exploratorio de Datos (EDA) y generar un informe con insights relevantes.

## 🧰 Herramientas y Tecnologías

- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Google Colab (opcional)
- Git / GitHub

## 📁 Estructura del Proyecto
📦 TelecomX LATAM
┣ 📂 graficas/ → Visualizaciones exportadas (PNG)

┣ 📄 datos_transformados.csv → Datos preprocesados para análisis

┣ 📄 TelecomX_Data.json → Dataset original en formato JSON

┣ 📄 TelecomX_LATAM.ipynb → Notebook principal con el análisis completo
┗ 📄 README.md → Este archivo


---

## 📌 Principales Hallazgos

- La **tasa de evasión general** es del **25.7%**.
- **Clientes con baja antigüedad** (menos de 7 meses) abandonan más (~50%).
- El contrato **“month-to-month”** está asociado a la mayor cantidad de cancelaciones (~41%).
- Los métodos automáticos de pago (tarjeta/crédito o transferencia bancaria) se correlacionan con menor cancelación.
- El género **no tiene impacto significativo** en la evasión.

---

## ✅ Recomendaciones

| Variable         | Riesgo identificado                | Recomendación                                   |
|------------------|-------------------------------------|-------------------------------------------------|
| Antigüedad       | Alta cancelación al inicio          | Mejorar onboarding de nuevos clientes           |
| Tipo de contrato | Alta evasión con contratos mensuales| Incentivar contratos anuales con beneficios     |
| Método de pago   | Electronic Check = + cancelaciones  | Promover pagos automáticos                      |
| Servicios diarios| Más cuentas, más evasión            | Simplificar o agrupar servicios ofrecidos       |

---

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/Lucas-Jimenez-uribe/TelecomX_LATAM.git
cd TelecomX_LATAM
```
2. Instala las dependencias:
```bash
pip install pandas matplotlib seaborn
```

## Autor
Lucas Jiménez Uribe

Análisis de Datos - 2025

Proyecto académico sobre retención de clientes
