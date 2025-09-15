# 🗓️ Roadmap de Aprendizaje en MQL5

Este documento resume el plan de aprendizaje dividido en 4 semanas, con teoría, práctica y entregables.  
Se presenta en dos formatos: **lista detallada** y **calendario visual (Gantt)**.

---

## 📋 Roadmap por semanas

### 🔹 Semana 1 (Fundamentos)
- [ ] Instalar MetaTrader 5 + MetaEditor
- [ ] Leer manual oficial (cap. 1–3)
- [ ] Revisar libro de Korotky (secciones iniciales)
- [ ] Script **Hello World** en gráfico
- [ ] Script de alerta por precio (EURUSD > 1.10)
- [ ] Indicador SMA con periodo configurable (14/50/200)

---

### 🔹 Semana 2 (Primer Expert Advisor)
- [ ] Estudiar gestión de órdenes (OrderSend/OrderClose)
- [ ] Estudiar series temporales y buffers (OHLC)
- [ ] Curso BitDegree — primeros módulos
- [ ] EA cruces de medias (20/50)
- [ ] Añadir parámetros configurables (SMA/SL/TP)
- [ ] Lotaje dinámico (1% riesgo por operación)

---

### 🔹 Semana 3 (Estrategias y optimización)
- [ ] Diseño de estrategias (Korotky)
- [ ] Revisar ejemplos en MQL5.com (RSI, MACD, Bollinger)
- [ ] EA basado en RSI (compra RSI<30 / venta RSI>70)
- [ ] Añadir trailing stop al EA RSI
- [ ] EA RSI + EMA (confirmación de tendencia)
- [ ] Backtesting en Strategy Tester
- [ ] Optimización de parámetros (RSI=14/20, EMA=50/100)
- [ ] Exportar reporte de backtest a `/docs/backtests`

---

### 🔹 Semana 4 (Proyecto final)
- [ ] Repasar manual completo (funciones avanzadas)
- [ ] Completar curso BitDegree
- [ ] Revisar Jobs y Market en MQL5.com
- [ ] EA MACD + RSI + gestión de riesgo (máx. 2% por operación)
- [ ] Stop Loss dinámico con ATR
- [ ] Dashboard/indicador (RSI, MACD, tendencia EMA)
- [ ] Script de simulación de portafolio (EURUSD y GBPUSD)
- [ ] Documentación de código estilo producción

---

## 📊 Roadmap visual (Gantt)

> **Nota:** Este diagrama usa colores de **alto contraste** por semana y un marcador de “hoy”.
> Si no se ve correctamente en tu tema de GitHub, prueba a cambiar a tema claro/oscuro del navegador.

```mermaid
gantt
    title Roadmap de Aprendizaje MQL5
    dateFormat  YYYY-MM-DD
    axisFormat  %d-%b
    todayMarker stroke:#d62728,stroke-width:2px

    %% Bloques por semana (fechas orientativas)
    section Semana 1
    Fundamentos                :s1, 2025-09-15, 7d

    section Semana 2
    Primer Expert Advisor      :s2, 2025-09-22, 7d

    section Semana 3
    Estrategias y optimización :s3, 2025-09-29, 7d

    section Semana 4
    Proyecto final             :s4, 2025-10-06, 7d

    %% Estilos de alto contraste por semana
    classDef w1 fill:#1f77b4,stroke:#000,color:#fff   %% Azul
    classDef w2 fill:#2ca02c,stroke:#000,color:#fff   %% Verde
    classDef w3 fill:#ff7f0e,stroke:#000,color:#111   %% Naranja (texto oscuro para más contraste)
    classDef w4 fill:#9467bd,stroke:#000,color:#fff   %% Morado

    %% Asignación de estilos a tareas
    class s1 w1
    class s2 w2
    class s3 w3
    class s4 w4
