# 🗺️ Roadmap Profesional de Aprendizaje en MQL5 (Organizado por Niveles)

Este documento presenta un **plan de aprendizaje estructurado desde el
Nivel 0 hasta el Nivel 4**, alineado con la organización del
repositorio.\
Incluye teoría, práctica guiada, creación de scripts, indicadores, EAs,
optimización y documentación profesional.

El roadmap está diseñado para construir un **portafolio sólido y
demostrable** de habilidades en MQL5.

------------------------------------------------------------------------

# 🎯 Resumen general por niveles

-   **Nivel 0 -- Preparación del entorno:** Instalación de MetaTrader 5,
    MetaEditor y configuración inicial.
-   **Nivel 1 -- Fundamentos:** Scripts, indicadores simples, conceptos
    base del lenguaje.
-   **Nivel 2 -- Primer Expert Advisor:** Órdenes, series temporales,
    primer EA funcional.
-   **Nivel 3 -- Estrategias y Optimización:** Indicadores avanzados,
    backtesting, optimización.
-   **Nivel 4 -- Proyecto Avanzado:** EA profesional con gestión de
    riesgo, dashboard y documentación final.

------------------------------------------------------------------------

# 📘 Detalle del Roadmap por Niveles

------------------------------------------------------------------------

## ⚪ Nivel 0 --- Preparación del entorno

Objetivo: Tener listo un entorno de trabajo totalmente funcional.

### **Tareas**

-   [ ] Instalar MetaTrader 5\
-   [ ] Instalar MetaEditor\
-   [ ] Entender estructura de carpetas (`MQL5/Indicators`, `Experts`,
    `Scripts`)\
-   [ ] Configurar gráficos y plantillas básicas\
-   [ ] Conocer el probador de estrategias (Strategy Tester)\
-   [ ] Crear y ejecutar el primer script vacío

### **Entrega del nivel**

-   Carpeta: `nivel0-entorno`\
-   Scripts y capturas del entorno configurado.

------------------------------------------------------------------------

## 🔵 Nivel 1 --- Fundamentos de MQL5

Objetivo: Aprender la estructura del lenguaje y crear los primeros
programas funcionales.

### **Teoría**

-   [ ] Definición de eventos (`OnStart`, `OnTick`, `OnCalculate`)\
-   [ ] Tipos de programas (Script / Indicador / EA)\
-   [ ] Series temporales (OHLC, buffers)\
-   [ ] Capítulos 1--3 del manual oficial\
-   [ ] Secciones introductorias del libro de Korotky

### **Práctica**

-   [ ] Script **Hello World**\
-   [ ] Script de alerta por precio\
-   [ ] Indicador SMA configurable (14 / 50 / 200)

### **Entrega del nivel**

-   Carpeta: `nivel1-fundamentos`\
-   3 scripts + 1 indicador completamente funcional.

------------------------------------------------------------------------

## 🟣 Nivel 2 --- Primer Expert Advisor (EA)

Objetivo: Crear el primer sistema de trading automatizado.

### **Teoría**

-   [ ] Uso de `CTrade`, `OrderSend`, `OrderClose`\
-   [ ] Manejo de OHLC y buffers\
-   [ ] Curso de BitDegree --- módulos iniciales

### **Práctica**

-   [ ] EA cruces de medias (20 / 50)\
-   [ ] Parámetros configurables: SMA, SL, TP\
-   [ ] Lotaje dinámico (1% por operación)

### **Entrega del nivel**

-   Carpeta: `nivel2-primer-ea`\
-   EA funcional con parámetros y documentación interna.

------------------------------------------------------------------------

## 🟠 Nivel 3 --- Estrategias y Optimización

Objetivo: Trabajar como un trader cuantitativo profesional.

### **Teoría**

-   [ ] Diseño de estrategias (Korotky)\
-   [ ] Estudio de ejemplos oficiales: RSI, MACD, Bollinger\
-   [ ] Conceptos de backtesting y optimización

### **Práctica**

-   [ ] EA RSI (RSI\<30 compra / RSI\>70 venta)\
-   [ ] Añadir trailing stop\
-   [ ] Estrategia RSI + EMA\
-   [ ] Backtesting en Strategy Tester\
-   [ ] Optimización de parámetros\
-   [ ] Exportación de reportes a `/docs/reportes_backtest/`

### **Entrega del nivel**

-   Carpeta: `nivel3-estrategias`\
-   EAs optimizados + reportes completos.

------------------------------------------------------------------------

## 🔴 Nivel 4 --- Proyecto Avanzado

Objetivo: Construir un EA de nivel profesional con documentación de
producción.

### **Teoría**

-   [ ] Revisión del manual MQL5 (avanzado)\
-   [ ] Completar curso BitDegree\
-   [ ] Estudio de Market & Jobs de MQL5.com

### **Práctica**

-   [ ] EA MACD + RSI + Gestión de riesgo (2% por operación)\
-   [ ] Stop Loss dinámico con ATR\
-   [ ] Dashboard técnico (RSI, MACD, EMA, tendencia)\
-   [ ] Script de simulación de portafolio multi-par\
-   [ ] Documentación profesional del EA

### **Entrega del nivel**

-   Carpeta: `nivel4-proyecto-avanzado`\
-   EA final, dashboard y documentación estilo producción.

------------------------------------------------------------------------

# 📦 Entregables globales

Todos los niveles incluyen: - Código bien estructurado\
- Capturas del funcionamiento (`/docs/capturas`)\
- Backtests y optimizaciones (`/docs/reportes_backtest`)\
- README por carpeta explicando la lógica del código

------------------------------------------------------------------------

# 🗂️ Calendario visual (Estilo Gantt)

Disponible en GitHub Projects:\
👉 https://github.com/users/firlixkl/projects/2

------------------------------------------------------------------------

# 📑 Cierre

Este roadmap sirve como guía profesional para demostrar competencias en
trading algorítmico, buenas prácticas de desarrollo y capacidad de
análisis cuantitativo con MQL5.
