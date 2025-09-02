---
layout: default
title: Plano de tierra (GND) y vías de costura
nav_order: 8
---

## Zonas de cobre (GND)
1. Herramienta **Add Filled Zone** (`Z`).
2. **Net** = `GND`, **Layer** = `F.Cu` o `B.Cu` (puedes hacer ambas).
3. Ajusta **Clearance**, **Min width**, **Thermal relief** y **Priority**.
4. Dibuja el polígono y presiona **`B`** para rellenar.

## Via Stitching (costura a GND)
- *Tools → Via Stitching / Shielding* (KiCad 7/8). Define paso (2–5 mm) y aplica.
- Alternativa: colocar **vías** manuales con **Net = GND**.

**Imágenes sugeridas**:  
- `zone-gnd.png`: Zona GND en F.Cu.  
- `via-stitching.png`: Diálogo de via stitching.
