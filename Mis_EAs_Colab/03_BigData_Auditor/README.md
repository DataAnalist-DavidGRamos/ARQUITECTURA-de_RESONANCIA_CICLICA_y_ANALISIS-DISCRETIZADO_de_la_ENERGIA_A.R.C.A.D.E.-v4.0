# 📁 Pilar 03: Big Data & Universal Auditing
## Procesamiento Masivo e Invarianza de Datos

Este módulo encapsula el motor de procesamiento para auditar años de historial de mercado. Para evitar sesgos (Look-ahead bias) y asegurar la **Invarianza Estructural**, el sistema se somete a pruebas de estrés sobre datasets de más de **2 GB** (15M+ de registros).

---

### 🧠 Conceptos Técnicos Implementados

1.  **Auditoría Universal por Tiers:** 
    Fragmentación de la rentabilidad según la calidad de la señal (**Tier 1 a Tier 5**). El sistema no busca "ganar siempre", sino identificar en qué tiers se encuentra el **Cisne Negro Positivo** de la estrategia.

2.  **Matriz Pentagonal de Resonancia:** 
    Auditoría cruzada entre 5 dimensiones de eventos (Tiempo, Nodo, Energía, Tensión y Volumen). Esta matriz permite ver qué intersecciones de datos son estructuralmente rentables a largo plazo.

3.  **Procesamiento por Bloques (Chunking):** 
    Implementación técnica para manejar datasets que exceden la memoria RAM de Google Colab, asegurando el procesamiento continuo sin degradación de rendimiento.

---

### 📓 Notebooks Incluidos

*   `06_ARC_Universal_Auditor_Tiers.ipynb`: Auditor de rentabilidad por tiers y segmentos. Desglosa cuánto se ganó o perdió en cada "Sexto" de la malla.
*   `07_ARC_Fractal_Resonancia_Audit.ipynb`: El motor de análisis más profundo del sistema. Audita 15.3M de registros buscando resonancia fractal en la matriz pentagonal.
*   `08_ARC_BigData_Unificator.ipynb`: Herramienta de fusión. Unifica todos los fragmentos de CSV generados por el MetaTrader 5 en un solo "Mega-DataFrame" maestro para análisis global.

---
> **"Un backtest de mil velas es una hipótesis. Una auditoría de quince millones de registros es una ley física."**  
> *— Tesis ARC*
