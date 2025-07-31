# Análisis Fundamental Financiero Automatizado

## Descripción
Repositorio de análisis fundamental financiero automatizado que incluye múltiples metodologías de valoración y análisis de inversión.

## Estructura del Proyecto

### Módulos de Análisis

#### 01-Analisis-Multiplos/
Análisis de múltiplos de valoración (P/E, EV/EBITDA, P/B, etc.) con comparación sectorial.

#### 02-DCF-MonteCarlo/
Modelo DCF con simulación Monte Carlo para incorporar incertidumbre en valoraciones.

#### 03-Calidad-Ganancias/
Análisis de calidad de ganancias usando Beneish M-Score y métricas de detección de manipulación contable.

#### 04-Modelos-Rentabilidad/
Análisis avanzado de rentabilidad incluyendo ROIC, WACC, EVA y análisis DuPont.

#### 05-Modelos-Cuantitativos/
Modelos cuantitativos con backtesting de estrategias y optimización de portafolios.

## Requisitos

### APIs Necesarias
- **Alpha Vantage**: Para datos fundamentales
- **Financial Modeling Prep**: Para métricas avanzadas y ratios

### Librerías Python
```bash
pip install pandas numpy matplotlib seaborn requests
pip install yfinance alpha_vantage scipy
pip install bt
```

## Uso

1. **Configurar APIs**: Obtener y configurar las API keys necesarias
2. **Seleccionar análisis**: Elegir el módulo de análisis apropiado
3. **Configurar parámetros**: Especificar ticker objetivo y parámetros
4. **Ejecutar análisis**: Correr el notebook correspondiente
5. **Interpretar resultados**: Revisar métricas y gráficos generados

## Características

- Análisis de múltiplos de valoración
- Modelo DCF con simulación Monte Carlo
- Detección de manipulación contable
- Análisis de rentabilidad avanzado
- Modelos cuantitativos con backtesting

## Notas

- Todos los análisis están en Jupyter Notebooks para facilitar la reproducción
- Los comentarios están en inglés para mantener consistencia
- Cada módulo es independiente y puede ejecutarse por separado
- Los resultados incluyen visualizaciones y métricas clave 