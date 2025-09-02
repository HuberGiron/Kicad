---
layout: default
title: Gerbers y Archivos de taladro (Drill)
nav_order: 13
---

## Generar Gerbers
1. *File → Plot…* → **Gerber** (marca Gerber X2 si está disponible).
2. Capas mínimas (2 capas): `F.Cu`, `B.Cu`, `F.Mask`, `B.Mask`, `F.SilkS`, `B.SilkS`, `Edge.Cuts`.
3. Opciones: “**Subtract soldermask from silkscreen**”, “**Use Protel extensions**”.
4. **Plot**.

## Generar Drill (Excellon)
1. En la ventana Plot, **Generate Drill Files…**.
2. **Units: mm**, **Format: Excellon**. `Merged PTH/NPTH` (o `Separate` según fab).
3. **Generate Drill** y **Map** (opcional).

## Revisar en Gerber Viewer
- *File → Gerber Viewer* → carga todos los `.g??` + `.drl`.

## Empaquetar
- Comprime **solo** los Gerbers + Drill en un **ZIP** y súbelo a tu fabricante.

**Imágenes sugeridas**:  
- `plot-gerbers.png`: Selección de capas.  
- `drill-dialog.png`: Diálogo de Excellon Drill.
