# Análisis de Ventas 2024–2026 — Excel

Proyecto de **Data Analytics aplicado a ventas**, desarrollado en Excel a partir de un dataset de 301 operaciones comerciales.

## Objetivo

Analizar el desempeño comercial del período 2024–2026 para identificar los principales motores de facturación, evolución temporal, concentración por producto/canal/ciudad/segmento y oportunidades de análisis.

## Dataset

- **301 operaciones**
- **2024–2026**
- 5 productos
- 5 ciudades
- 4 vendedores
- 2 canales
- 4 métodos de pago
- 3 segmentos de clientes

## Herramientas utilizadas

- Excel
- Tablas estructuradas
- Fórmulas y columnas calculadas
- Validación de datos
- Tablas dinámicas
- Gráficos dinámicos
- Segmentadores
- Dashboard interactivo
- Macros VBA
- Funciones financieras
- Power Query
- Power Pivot / Modelo de datos

## Flujo de trabajo

```text
Datos
  ↓
Estructuración y validación
  ↓
Cálculos comerciales
  ↓
Tablas dinámicas y análisis
  ↓
Dashboard
  ↓
Insights
  ↓
Conclusiones para negocio
```

## KPIs principales

| KPI | Resultado |
|---|---:|
| Facturación total | $160.678.100 |
| Ganancia total | $45.716.100 |
| Operaciones | 301 |
| Unidades vendidas | 1.291 |
| Margen promedio | 39,59% |

> El margen mostrado corresponde al promedio de la columna Margen utilizada en el dashboard; no es el margen ponderado calculado como ganancia total / facturación total.

## Principales insights

1. **Notebook** concentra el **55,12%** de la facturación y genera $88.560.000.
2. El canal **Online** concentra el **67,89%** de la facturación.
3. **Buenos Aires** representa el **49,18%** de la facturación total.
4. La facturación creció **371,07%** entre 2024 y 2025 y cayó **16,74%** entre 2025 y 2026.
5. En 2026 la facturación fue **3,92 veces** la de 2024, equivalente a un crecimiento acumulado de **292,19%**.
6. La facturación de Notebook cayó de $44.880.000 en 2025 a $32.160.000 en 2026 (**-28,34%**). Esa reducción explica aproximadamente el **96,7% de la caída neta** de facturación entre ambos años.

## Estructura del archivo

- `Inicio`: portada, navegación y resumen ejecutivo.
- `Datos`: dataset estructurado y validado.
- `analisis`: tablas dinámicas y análisis de negocio.
- `Dashboard`: KPIs, gráficos y segmentadores.
- `Finanzas`: simulador financiero y funciones financieras.

## Resultado

El proyecto integra en un único archivo un flujo completo de análisis comercial: desde la estructuración y control de datos hasta la visualización y comunicación de insights.

El archivo `.xlsm` conserva las macros VBA desarrolladas durante el proyecto.

## Limitaciones

El dataset es un conjunto de práctica orientado al aprendizaje de Data Analytics. Las conclusiones describen los datos disponibles y no incorporan variables externas como inventario, precios de mercado, campañas, estacionalidad externa, inflación o información financiera completa de la empresa.

## Autor

Proyecto desarrollado como parte de una formación práctica en **Data Analytics con Excel**.
