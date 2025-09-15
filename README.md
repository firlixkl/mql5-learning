# Roadmap de Aprendizaje en MQL5

Este repositorio documenta mi progreso en el aprendizaje de **MQL5 y MetaTrader 5** con un plan de 4 semanas, combinando teoría y práctica.  
El objetivo es obtener una base sólida en programación de Expert Advisors (EAs), indicadores y scripts, y tener varios proyectos listos para mostrar en entrevistas o trabajos.


---
## Tablero de progreso
Puedes seguir el avance en el tablero Kanban aquí 👉 [Roadmap MQL5 Project](https://github.com/firlixkl/mql5-learning/projects)

---

## Progreso por semanas

### Semana 1 – Fundamentos de MQL5 y MetaTrader 5
- [ ] Instalar MetaTrader 5 + MetaEditor  
- [ ] Leer capítulos 1–3 del manual oficial (sintaxis, scripts, indicadores, EAs)  
- [ ] Revisar primeras secciones del libro de Korotky  
- [ ] Script “Hello World” en gráfico  
- [ ] Script que muestre un `Alert()` cuando EURUSD > 1.10  
- [ ] Indicador SMA con periodo configurable (14, 50, 200)  

**Objetivo**: Familiarizarme con MetaEditor, compilar y crear scripts/indicadores simples.  

---

### Semana 2 – Primer Expert Advisor
- [ ] Leer sobre funciones de gestión de órdenes (`OrderSend`, `OrderClose`)  
- [ ] Estudiar series temporales y buffers de datos (OHLC, candles)  
- [ ] Empezar curso de BitDegree (primeros módulos)  
- [ ] EA cruces de medias móviles (SMA rápida 20, SMA lenta 50)  
- [ ] Añadir parámetros configurables (SMA, SL, TP)  
- [ ] Implementar control de lotaje dinámico (ej. 1% del capital)  

**Objetivo**: Construir un EA funcional que abra/cierre operaciones automáticas.  

---

### Semana 3 – Estrategias con indicadores y optimización
- [ ] Leer más del libro de Korotky (diseño de estrategias)  
- [ ] Revisar ejemplos en MQL5.com (RSI, MACD, Bollinger)  
- [ ] EA basado en RSI (compra RSI<30, vende RSI>70)  
- [ ] Añadir trailing stop  
- [ ] EA RSI + EMA combinado  
- [ ] Backtesting en Strategy Tester  
- [ ] Optimización de parámetros (ej. RSI=14/20, EMA=50/100)  
- [ ] Exportar reporte con resultados  

**Objetivo**: Aprender a combinar indicadores, optimizar y demostrar mejoras con backtesting.  

---

### Semana 4 – Proyecto final y nivel profesional
- [ ] Repasar manual completo (posiciones múltiples, eventos de mercado)  
- [ ] Completar curso de BitDegree  
- [ ] Revisar Jobs y Market en MQL5.com  
- [ ] EA avanzado (MACD + RSI + gestión de riesgo, máx. 2% del capital)  
- [ ] Stop Loss dinámico basado en ATR  
- [ ] Dashboard/indicador que muestre RSI, MACD y tendencia EMA  
- [ ] Script de simulación de portafolio (ej. EURUSD y GBPUSD)  
- [ ] Documentar código como si fuera para producción  

**Objetivo**: Tener 2–3 EAs completos + un dashboard + reportes de backtest listos para mostrar en entrevista.  

---

## Resultado esperado
Al finalizar el roadmap deberías tener:
- [ ] EA simple: cruce de medias  
- [ ] EA intermedio: RSI + EMA optimizado  
- [ ] EA avanzado: MACD + RSI + gestión de riesgo + ATR  
- [ ] Indicador/dashboard  
- [ ] Reportes de backtest listos para enseñar  

---

## Estructura del repositorio
```bash
📦 mql5-learning-roadmap
 ┣ 📂 semana1-fundamentos
 ┣ 📂 semana2-primer-ea
 ┣ 📂 semana3-estrategias
 ┣ 📂 semana4-proyecto-final
 ┣ 📂 docs
 ┗ README.md
