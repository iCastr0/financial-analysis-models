# Análisis de Calidad de Ganancias

## Descripción
Este módulo implementa análisis de calidad de ganancias para detectar posibles manipulaciones contables y evaluar la sostenibilidad de las ganancias reportadas.

## Archivos
- `Calidad-Ganancias.ipynb`: Notebook principal con análisis de calidad de ganancias

## Funcionalidades
- **Beneish M-Score**:
  - Detección de manipulación contable
  - Análisis de accruals vs. cash flow
  - Evaluación de calidad de ganancias

- **Métricas de calidad**:
  - Sloan Ratio (acruales/activos)
  - Cash Conversion Ratio (CFO/Net Income)
  - CapEx/CFO ratio
  - Análisis de crecimiento CFO vs. Net Income

- **Indicadores de alerta**:
  - Detección de deterioro en calidad de ganancias
  - Análisis de consistencia temporal
  - Comparación con estándares del sector

## Uso
1. Configurar API key de Alpha Vantage
2. Especificar ticker objetivo
3. Ejecutar análisis de calidad de ganancias
4. Revisar indicadores de manipulación contable
5. Evaluar sostenibilidad de ganancias 