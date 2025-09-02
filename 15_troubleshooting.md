---
layout: default
title: Problemas comunes (FAQ)
nav_order: 16
---

### La zona GND no se rellena
- Presiona **`B`** (repour).
- Revisa **Net = GND** y **Priority**.
- `Copper to edge clearance` demasiado grande.
- La zona está **bloqueada** o hay un **keepout**.

### “Unconnected” que no encuentro
- Activa **Ratsnest** (airwires).
- *Inspect → Net Inspector* para ver longitud sin rutear.
- Usa **DRC** y doble-clic en el error.

### La serigrafía pisa pads
- Activa “**Subtract soldermask from silkscreen**” al plotear Gerbers.
- Mueve o reduce texto/escala del logo.

### El STEP no trae componentes
- Marca **Include 3D models**.
- Verifica que los footprints tengan modelos .step/.wrl asignados.

### El DXF sale a otra escala
- Usa **mm** y **Scale 1:1** al exportar.
