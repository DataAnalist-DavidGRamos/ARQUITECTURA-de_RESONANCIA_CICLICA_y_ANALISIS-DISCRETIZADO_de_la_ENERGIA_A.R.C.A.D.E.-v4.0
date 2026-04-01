# 🛰️ Pilar 04: Signal Intelligence & Forensic Analysis
## ADN de la Ignición y Minería de Contraste

Este paso final es la **Capa de Inteligencia Estructural**. Aquí se busca el "ADN" que define a una señal ganadora (Spike) y se contrasta estadísticamente con los fallos para crear filtros de bloqueo ("Locking Filters").

---

### 🧠 Conceptos Técnicos Implementados

1.  **Minería de Contraste (Success vs. Failure):** 
    Comparación de las firmas de **Éxito** (Ignición Real) contra las de **Fallo** (Saturación Estéril). Este análisis demostró que las señales exitosas poseen una **Energía 28 veces superior** (21k vs 700) en el momento exacto de la ignición. 

2.  **ADN de Ignición (Pre-Spike):** 
    Estudio forense de la vela un tick antes de la explosión. Se analizan los umbrales de percentiles (P10, P50, P90) de energía y tensión ($\Upsilon$) para garantizar que la "mecha" esté encendida.

3.  **Detección "Grand Colossus":** 
    Identificación de tendencias que superan los **120 minutos** de duración constante. Estos eventos no son simples spikes; son **rupturas de nivel estructural** que suelen originarse en nodos de la malla H6.

---

### 📓 Notebooks Incluidos

*   `09_ARC_Forensic_Backtest_Audit.ipynb`: Validador forense que calcula métricas de supervivencia de la cuenta: Win Rate, Drawdown Máximo y Runup Promedio.
*   `10_ARC_Signature_Contrast.ipynb`: Script de minería que genera los archivos de firma `SUCCESS.csv` y `FAILURE.csv` para entrenar los filtros del EA.
*   `11_ARC_Ignition_DNA_Analyzer.ipynb`: Analizador profundo del estado previo a la ignición. Establece los "Mínimos Necesarios" de energía para cada activo.
*   `12_ARC_Grand_Colossus_Trends.ipynb`: Detector especializado en tendencias masivas y de larga duración, enfocado en maximizar los beneficios de los grandes recorridos.

---
> **"Un spike es ruido si no tiene ADN de ignición. La inteligencia ARC es el filtro entre el azar y la probabilidad cuántica."**  
> *— Tesis ARC*
