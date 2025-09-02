---
layout: default
title: Contorno, stackup y actualización desde esquemático
nav_order: 5
---

## Actualizar PCB desde el esquemático
- En PCB Editor: *Tools → Update PCB from Schematic*. Coloca componentes y ajusta orientación.

## Definir contorno de placa
1. Cambia a la capa **`Edge.Cuts`**.
2. Dibuja el contorno con líneas/arcos **cerrando el perímetro** (ancho 0.10 mm).
3. Para ranuras internas, dibuja loops adicionales en `Edge.Cuts`.

## Espesor y materiales (stackup)
- *Board Setup → Material Stackup* → **Board thickness** (típico 1.6 mm) y capas.
- Asegura **Copper to edge clearance** (0.3–0.5 mm típico).

**Imágenes sugeridas**:  
- `edge-cuts.png`: Contorno en Edge.Cuts.  
- `stackup.png`: Stackup con 2 capas y 1.6 mm.
