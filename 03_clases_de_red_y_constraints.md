---
layout: default
title: Clases de red y reglas de diseño
nav_order: 4
---

## Net Classes y reglas (Board Setup)
En **PCB Editor** abre *File → Board Setup* y configura:

- **Design Rules → Constraints**: anchos/vías mínimas, clearance, copper-to-edge.
- **Predefined track widths** (0.25 mm, 0.4 mm, 0.6 mm…).
- **Net Classes**: `Default`, `Power`, etc. con su **Track width**/Via sizes.
- Asigna nets a clases (p. ej. `GND`, `+5V` → clase `Power`).

> Esto garantiza ruteo consistente y cumplimiento con tu fabricante.

**Imágenes sugeridas**:  
- `board-setup-constraints.png`: Ventana Constraints.  
- `net-classes.png`: Net classes con anchos/vías definidos.
