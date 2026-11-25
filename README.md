# Visualization-of-block-structured-mesh-data-using-Visualization-Toolkit-VTK

## Overview
Developed a Python-based workflow to convert block-structured CFD solver data into VTK formats for scientific visualization in ParaView.

## Methodology
- Processed block-structured grid data using NumPy.
- Reconstructed 2D spatial coordinates for individual grid blocks.
- Used VTK to generate `vtkStructuredGrid` objects.
- Combined multiple blocks into a `vtkMultiBlockDataSet`.
- Exported the data in `.vtm` format for visualization in ParaView.

## Tools & Libraries
- Python
- NumPy
- VTK (Visualization Toolkit)
- ParaView

## Results
- Successfully converted CFD solver output into ParaView-compatible VTK files.
- Visualized pressure contours and velocity vector fields.
- Reconstructed the computational mesh while preserving individual block structures and grid refinement.
- Enabled customizable scientific visualization and contour export through ParaView.
