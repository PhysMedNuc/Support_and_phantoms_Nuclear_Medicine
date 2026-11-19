# 3D-Printed Support and Phantoms in Nuclear Medicine

This repository contains STL files for 3D-printed phantoms and supports designed for quality control and performance characterization of SPECT systems.

Each directory (and subdirectory, where applicable) contains all the printable components required to assemble a specific phantom or support.

The table below summarizes the number of copies of each STL file required to assemble the corresponding phantom or support.

## Required Printed Components

| Phantom / Support | STL Filename | Number of Prints |
|:---|:---|:---:|
| **Planar Spatial Resolution** | `Main_Part_Support.stl` | 1 |
| | `Extension_PSR.stl` | 2 |
| **Tomographic Spatial Resolution – Unscattered Medium** | `Base.stl` | 1 |
| | `Large_Rod.stl` | 1 |
| | `Medium_Rod.stl` | 1 |
| | `Small_Rod.stl` | 1 |
| | `Extension_TSR.stl` | 3 |
| **Tomographic Spatial Resolution – Scattering Medium** | `Bottom_circular_plate.stl` | 1 |
| | `Top_circular_plate.stl` | 1 |
| | `Jaszczak_phantom_fixing_screw.stl` | 6 |
| | `Structure_screw.stl` | 3 |
| | `Support_Rod.stl` | 3 |
| **Planar Sensitivity** | `Planar_Sensitivity_box.stl` | 1 |
| | `Planar_Sensitivity_screw1.stl` | 1 |
| | `Planar_Sensitivity_screw2.stl` | 1 |
| | `Planar_Sensitivity_top.stl` | 1 |
| **Jaszczak Fillable Spheres** | `Rod_Sphere_XXmm.stl` | 1 |
| | `Sphere_XXmm.stl` | 1 |
| **IEC Fillable Spheres** | `Sphere_XXmm.stl` | 1 |

*Note: `XX` in the filenames is a placeholder for the sphere diameter.*

## Repository Structure and Development Status

### `main` branch

The `main` branch contains only phantom and support designs that have undergone experimental validation and have been approved through peer review.

A reference paper describing these developments is currently under submission.

### `develop` branch

A `develop` branch will be made available soon. It will host phantoms and supports that are still under development or whose performance has not yet been experimentally validated.

## License

All hardware designs, 3D models, and associated design files provided in this repository are released under the CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S-2.0).

These designs may be freely used, reproduced, modified, manufactured, and commercially distributed, provided that all applicable requirements of the CERN-OHL-S-2.0 are respected.

In particular, any modified designs distributed publicly or incorporated into commercially distributed products must remain available under the same licence, together with their complete corresponding source files.

Full licence text: https://ohwr.org/cern_ohl_s_v2.txt

