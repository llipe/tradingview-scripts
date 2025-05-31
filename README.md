# TradingView Scripts, Ideas and Strategies

Este repositorio contiene una colección de scripts de TradingView desarrollados para estrategias de trading, indicadores personalizados e ideas de análisis técnico. Su enfoque principal son estrategias para scalping, cruces de medias móviles, señales basadas en ADX/MACD y otras herramientas útiles para traders en marcos de tiempo bajos y altos.

---

## 📈 Indicadores Disponibles

### 1. Señales Scalping BTC M1/M5 - EMA + ADX

- **Versión:** v1.1.4  
- **Fecha:** 2025-05-30  
- **Descripción:**  
  Indicador diseñado para generar señales de compra y venta en gráficos de 1 minuto, utilizando la pendiente del MACD en 5 minutos para determinar la dirección (long/short). Emplea cruces de EMAs, precios de cierre y el ADX para validar la entrada.

  **Características:**
  - Entrada de compra (long): EMA rápida sobre la lenta, cierre mayor al máximo previo, ADX alto y pendiente positiva del MACD (en timeframe superior).
  - Entrada de venta (short): EMA rápida bajo la lenta, cierre menor al mínimo previo, ADX bajo y pendiente negativa del MACD.
  - Señales visuales (labels) para entradas y salidas.
  - Alertas integradas para TradingView.
  - Parámetros completamente configurables:
    - Longitudes de EMAs
    - Periodo y suavizado de ADX/DMI
    - Periodo de ATR
    - Umbral mínimo para ADX
    - Visualización opcional de EMAs
    - Parámetros y timeframe para MACD

### 2. Simple EMA Crossing + Signals

- Indicador publicado en TradingView.
- Genera señales sencillas a partir de cruces de medias móviles exponenciales.

### 3. Directional Index Crossing Signal

- Idea basada en el cruce entre DI+ y DI- para señalizar cambios de tendencia.

### 4. Supertrend + Squeeze Momentum + ADX Strategy

- Estrategia que combina Supertrend, Squeeze Momentum y ADX.
- Nota: Las señales de entrada pueden ser tardías y requieren ajuste.

---

## 📂 Estructura del Repositorio

```text
/
├── indicator-scalping-1m-5m-EMA-ADX.pine
├── [otros scripts .pine]
└── README.md
