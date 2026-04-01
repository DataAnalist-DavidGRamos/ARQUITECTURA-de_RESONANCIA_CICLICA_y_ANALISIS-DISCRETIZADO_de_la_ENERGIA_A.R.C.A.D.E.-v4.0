# ⚛️ Pilar 01: Market Physics & Space Discretization
## Bases Fundamentales de la Tesis ARC

Este módulo contiene la validación empírica de la **Axiomática del Campo Discretizado**. Antes de ejecutar cualquier operación, el sistema debe validar la integridad física de la malla fractal donde se desplaza el precio.

---

### 🧠 Conceptos Técnicos Implementados

1.  **Discretización Nodal (Malla 1/144):** 
    El espacio vertical entre el soporte y la resistencia de un canal de regresión se divide en **144 niveles discretos (Nodos)**. El **Nodo 81** actúa como el centro de masa y "Muro Principal". Cualquier interacción del precio en estos niveles es monitoreada mediante una firma estadística.

2.  **Tensión Superficial ($\Upsilon$ - Upsilon):** 
    Métrica de varianza calculada en una ventana rodante de 30 ticks. Un valor bajo de $\Upsilon$ (< 0.28) indica una **fase de saturación nodal**, lo que sugiere una explosión energética inminente (Spike).

3.  **Teorema de Escape:** 
    Definición matemática de cuándo el precio "rompe" la malla normalizada. Se analizan los ticks que exceden los límites del canal (Nodos > 144 o < 0) para detectar el inicio de nuevas octavas estructurales.

---

### 📓 Notebooks Incluidos

*   `01_ARC_Master_Analyzer.ipynb`: Motor de visualización maestro. Mapea las señales sobre el mapa de fase nodal para auditar la precisión visual de la estrategia.
*   `02_ARC_Node_Physics_Validator.ipynb`: Validador de la distribución de nodos. Confirma si el precio está respetando los sextos (1/6) y calcula la tensión $\Upsilon$ en tiempo real.
*   `03_ARC_Miner_Escape_Theorem.ipynb`: Script especializado en la detección de rupturas topológicas y la relación precio/malla discretizada.

---
> **"La física del mercado precede a la ganancia. Si la energía no está presente, la estructura es nula."**  
> *— Tesis ARC*
