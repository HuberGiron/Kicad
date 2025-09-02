---
layout: default
title: Agregar un logo (serigrafía o cobre)
nav_order: 9
---

## Opciones para logos
1. **Bitmap to Component** (herramienta de KiCad): convierte PNG/JPG a módulo para F.SilkS o capa de cobre.
2. **Importar DXF**: vectoriza tu logo y *File → Import → Graphics* en **F.SilkS** o **F.Cu**.
3. **Footprint personalizado**: crea un footprint con gráficos en la capa deseada.

> Para cobre, respeta **clearance** y grosor mínimo de trazos. Para serigrafía, evita superponer pads (usa “Subtract soldermask from silkscreen”).

**Imágenes sugeridas**:  
- `bitmap2component.png`: Conversión de imagen a módulo.  
- `logo-on-silk.png`: Logo en serigrafía F.SilkS.
