# DCF con Simulación Monte Carlo

## Descripción
Este módulo implementa un modelo de valoración DCF (Discounted Cash Flow) con simulación Monte Carlo para incorporar incertidumbre en las proyecciones financieras.

## Archivos
- `DCF-MonteCarlo.ipynb`: Notebook principal con modelo DCF y simulación Monte Carlo

## Funcionalidades
- **Análisis DCF tradicional**:
  - Proyección de flujos de caja libres
  - Cálculo del valor terminal
  - Determinación del valor intrínseco

- **Simulación Monte Carlo**:
  - Incorporación de incertidumbre en parámetros clave
  - Distribuciones de probabilidad para tasas de crecimiento
  - Análisis de sensibilidad avanzado

- **KPIs financieros**:
  - ROE, ROA, márgenes operativos
  - Ratios de deuda y liquidez
  - Métricas de eficiencia operativa

## Uso
1. Configurar API keys (Alpha Vantage, Financial Modeling Prep)
2. Especificar ticker objetivo
3. Ajustar parámetros de simulación
4. Ejecutar modelo DCF con Monte Carlo
5. Analizar distribución de valores estimados 