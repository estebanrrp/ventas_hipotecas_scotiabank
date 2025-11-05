# 🏦 Market Intelligence Assessment — Scotiabank (Hipotecas México)

Este repositorio documenta el análisis de inteligencia de mercado realizado para **Scotiabank**, enfocado en la originación de hipotecas en México. El objetivo fue identificar insights estratégicos, evaluar la participación de mercado y detectar oportunidades de expansión geográfica y segmentación de clientes.

Se incluyen dos pdf para la presentación de resultados:

-One-Pager con la presentación de los resultados

-Reporte general del trabajo con el código generado (con comentarios) y los resultados obtenidos

---

## 📊 Objetivo del Proyecto

Procesar una base de datos mensual con datos de hipotecas otorgadas por bancos en México para:

- Calcular la participación de mercado de Scotiabank
- Analizar su evolución temporal
- Comparar con competidores
- Detectar concentración geográfica
- Identificar segmentos desatendidos
- Explorar regiones con tasas de interés elevadas

---

## 🛠️ Herramientas Utilizadas

- **Python**: análisis de datos con `pandas`, visualización con `matplotlib`, manipulación con `numpy`, entre otros
- **Jupyter Notebook**: desarrollo interactivo y documentación técnica
- **PowerPoint (One-Pager)**: presentación ejecutiva de resultados
---

## 🧠 ¿Qué hace el código?

El notebook realiza las siguientes tareas:

### 1. Preprocesamiento
- Limpieza de acentos y normalización de variables categóricas
- Filtrado de columnas relevantes

### 2. Cálculo de tasas ponderadas
- Agrupación por segmentos
- Cálculo de tasas de interés ponderadas por monto de crédito

### 3. Análisis de participación de mercado
- Cálculo mensual y evolución histórica
- Comparación con competidores

### 4. Concentración geográfica
- Identificación de estados donde Scotiabank supera al principal competidor (BBVA México)

### 5. Segmentación de clientes
- Clasificación por rangos de edad e ingreso
- Detección de segmentos con baja penetración

### 6. Análisis de tasas de interés
- Identificación de estados con tasas significativamente más altas que el promedio nacional

---

## 📈 Resultados Clave

| Métrica | Resultado |
|--------|-----------|
| Participación de Scotiabank (Nov 2023) | **21.02%** |
| Principal competidor | **BBVA México (22.81%)** |
| Estados donde Scotiabank supera a BBVA | Tlaxcala, Coahuila, Veracruz, CDMX, Yucatán |
| Estados con tasas elevadas | Tlaxcala (14.89%), Campeche, CDMX, Durango |
| Segmentos desatendidos | Jóvenes (<30 años) y bajos ingresos (<10k) |

---

## 📌 Aplicación Real

Este análisis puede ser utilizado por equipos de estrategia, producto y marketing de Scotiabank para:

- Ajustar tasas en regiones con alta competencia
- Diseñar campañas dirigidas a segmentos desatendidos
- Priorizar expansión en estados con alta participación relativa
- Monitorear evolución de mercado y posicionamiento competitivo

---

## 📁 Estructura del Repositorio

```bash
├── notebooks/
│   └── Market_Intelligence_Assessment_Scotiabank.pdf
│   └── Market_Intelligence_Assessment_Scotiabank_OnePager.pdf
├── README.md
