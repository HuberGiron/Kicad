---
layout: default
title: Esquemático: símbolos, conexiones y ERC
nav_order: 3
---

## Crear el esquemático
1. Abre **Schematic Editor**.
2. Agrega símbolos: **Place Symbol** (tecla `A`).
3. Inserta **GND** y **VCC/5V/3V3** (según tu diseño): **Place Power Port**.
4. Conecta con **Place Wire** (`W`) y **Labels** (`L`) para organizar las nets.
5. **Annotate** (asignar designadores) → *Tools → Annotate Schematic*.
6. **Electrical Rules Check (ERC)**: *Inspect → Electrical Rules Checker* → resuelve advertencias.

> Mantén el esquemático limpio: usa **labels** y **net labels jerárquicas** si el circuito crece.

## Guardar y asociar footprints
1. **Assign Footprints**: *Tools → Assign Footprints* (CVPCB).
2. Para cada símbolo, elige un **footprint** acorde (p. ej., `R_0603`, `C_0805`, `PinHeader_1x04`, etc.).
3. Guarda.

**Imágenes sugeridas**:  
- `schematic-simple.png`: Esquemático básico con resistencias, capacitores, conector y GND/VCC.  
- `assign-footprints.png`: Ventana de asignación de footprints.
