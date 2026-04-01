# 🔱 ARC: Augmented Resonance & Cyclic Analysis
## 🛰️ Quantitative Trading Framework for Synthetic Indices

Este repositorio representa la culminación de más de 4 años de investigación en **Física de Mercados Fractales** y **Mallas de Resonancia Cíclica**, originalmente desarrollados en Google Colab para los índices sintéticos de Deriv (específicamente **Boom 1000**).

La arquitectura ARC no es un sistema de indicadores tradicionales; es un **Campo Discretizado** que mapea la partícula de precio dentro de una **Malla de 144 Nodos**, analizando su energía cinética y tensión superficial en tiempo real.

---

### 🧠 Arquitectura Core (Axiomas de la Tesis)

1.  **Discretización Nodal (Malla 1/144):** Espacio vertical del canal de regresión dividido en 144 estados discretos. El **Nodo 81** actúa como el centro de masa (Muro Principal).
2.  **Confluencia Pentagonal:** Análisis sincronizado en 5 dimensiones temporales (**M2, M10, H1, H6, H12**).
3.  **Física de la Ignición:** El sistema detecta la "Ignición" mediante la relación entre la Energía del Ticks ($\Delta P/\Delta t$) y el *Noise Floor* adaptativo.
4.  **Tensión Fractal ($\Upsilon$ - Upsilon):** Métrica de varianza que mide la saturación de la malla antes de una ruptura inminente.

---

### 📂 Estructura del Portafolio

Este laboratorio ha sido recuperado y profesionalizado en 12 módulos de investigación:

#### 1. Pilas de Análisis de Campo
*   `01_ARC_Master_Analyzer.ipynb`: Visualizador de señales sobre el mapa de fase.
*   `02_ARC_Node_Physics_Validator.ipynb`: Validador de la distribución de nodos y tensión $\Upsilon$.
*   `03_ARC_Miner_Escape_Theorem.ipynb`: Motor de desconstrucción de precio vs. malla (Teorema de Escape).

#### 2. Motores de Detección y Confluencia
*   `04_ARC_Ignition_Confluence.ipynb`: Identificación de zonas de ignición de alta probabilidad.
*   `05_ARC_Malla_Gold_Scanner.ipynb`: Escaneo persistente de la **"Zona de Gloria" (72-82)**.
*   `12_ARC_Grand_Colossus_Trends.ipynb`: Detección de tendencias masivas (>120M) mediante nodos H6.

#### 3. Auditoría Forense y Big Data
*   `06_ARC_Universal_Auditor_Tiers.ipynb`: Motor de procesamiento por bloques (Chunking) para datasets masivos.
*   `07_ARC_Fractal_Resonancia_Audit.ipynb`: Análisis de 15.3M de registros con la **Matriz Pentagonal de Eventos**.
*   `09_ARC_Forensic_Backtest_Audit.ipynb`: Cálculo avanzado de Win Rate, Drawdown y Runup.

#### 4. Inteligencia de ADN
*   `10_ARC_Signature_Contrast.ipynb`: Minería de contraste entre firmas de Éxito vs. Fallo.
*   `11_ARC_Ignition_DNA_Analyzer.ipynb`: Análisis del estado pre-spike (Percentiles de energía y tensión).

---

### 📊 Hallazgos Estatísticos Clave
*   **Zona Gloria (Nodos 72-82):** Se identificó una densidad de ignición positiva del **26.1%** concentrada en el Nodo 81.
*   **Firma de Ignición:** Los eventos de éxito presentan una Energía Promedio de **21,411** vs. **745** en fallos estériles.
*   **Invarianza Estructural:** El sistema demostró ser robusto ante cambios de régimen de volatilidad (2021 vs 2024) con una desviación de solo **0.2%** en la energía normalizada.

---

### 🛠️ Tecnología Utilizada
*   **Lenguajes:** Python (Base Analítica) y MQL5 (Ejecución Titanium).
*   **Stack Data Science:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

---
> **"El mercado es un sistema de memoria estructurada, no un campo de probabilidad uniforme."**  
> *— Tesis ARC v4.1*
