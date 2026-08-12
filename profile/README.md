# <p align="center"><img src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/header_combined_slim.png" width="1000"></p> 
 
[![GitHub Stars](https://img.shields.io/github/stars/cgre-aachen/gempy.svg)](https://github.com/cgre-aachen/gempy/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/cgre-aachen/gempy.svg)](https://github.com/cgre-aachen/gempy/network)
[![PyPI](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/release/python-31013/)
[![PyPI](https://img.shields.io/badge/pypi-1.0-blue.svg)](https://pypi.org/project/gempy/)
[![license: EUPL v1.2](https://img.shields.io/badge/license-EUPL%20v1.2-blue.svg)](https://github.com/cgre-aachen/gempy/blob/master/LICENSE)
[![Documentation Status](https://assets.readthedocs.org/static/projects/badges/passing-flat.svg)](http://docs.gempy.org)
[![DOI](https://zenodo.org/badge/96211155.svg)](https://zenodo.org/badge/latestdoi/96211155)


## What's New: GemPy 2026.0.3 — June 2026

GemPy 2026.0.3 is the latest stable release of GemPy v3. It brings together matching releases of `gempy`, `gempy_engine`, and `gempy_viewer`, with updates across model setup, serialization, octree handling, PyTorch support, visualization, and example models.

For the full release notes, see the [GemPy 2026.0.3 release](https://github.com/gempy-project/gempy/releases/tag/v2026.0.3). For background on the GemPy v3 transition, see [What's New in GemPy v3](WhatsNewGemPy3.md).

GemPy v2 remains available as [gempy_legacy](https://github.com/gempy-project/gempy_legacy) for users who still depend on previous workflows. The core team is not developing new features for this version, but maintenance can continue based on community needs.

## Overview

[GemPy](https://www.gempy.org/) is a Python-based, **open-source geomodeling library**. It is
capable of constructing complex **3D geological models** of folded
structures, fault networks and unconformities, based on the underlying
powerful **implicit representation** approach. 

## Installation

We provide the latest release version of GemPy via PyPi package services. We highly recommend using PyPi,

`$ pip install gempy[base]`
 
## Resources

After installation, you can either check the [notebook tutorials](https://docs.gempy.org/getting_started/get_started.html#sphx-glr-getting-started-get-started-py) 
or the [video introduction](https://www.youtube.com/watch?v=n0btC5Zilyc) to get started.

Go to the [documentation site](http://docs.gempy.org/) for further information and enjoy the [tutorials and examples](https://www.gempy.org/tutorials).

For questions and support, please use [discussions](https://github.com/cgre-aachen/gempy/discussions).

If you find a bug or have a feature request, create an [issue](https://github.com/cgre-aachen/gempy/issues).

Follow these [guidelines](https://github.com/cgre-aachen/gempy/blob/WIP_readme-update-march21/CONTRIBUTING.md) to contribute to GemPy.



## Gallery
### Geometries

<p>
<table>
<tr>

  <td>
  <a href="https://docs.gempy.org/examples/geometries/a01_horizontal_stratigraphic.html#sphx-glr-examples-geometries-a01-horizontal-stratigraphic-py">
  <img alt="colormapped image plot thumbnail" src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/model1_nodata.png?raw=true)" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/examples/geometries/b02_fold.html#sphx-glr-examples-geometries-b02-fold-py">
  <img alt="colormapped image plot thumbnail" src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/model2_nodata.png?raw=true)" width="300" />
  </a>
  </td>
  
   <td>
  <a href="https://docs.gempy.org/examples/geometries/c03_recumbent_fold.html#sphx-glr-examples-geometries-c03-recumbent-fold-py">
  <img alt="colormapped image plot thumbnail" src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/model3_nodata.png?raw=true" width="300" />
  </a>
  </td>

</tr>
<tr>

  <td>
  <a href="https://docs.gempy.org/examples/geometries/d04_pinchout.html#sphx-glr-examples-geometries-d04-pinchout-py">
  <img alt="colormapped image plot thumbnail" src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/model4_nodata.png?raw=true" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/examples/geometries/e05_fault.html#sphx-glr-examples-geometries-e05-fault-py">
  <img alt="colormapped image plot thumbnail" src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/model5_nodata.png?raw=true" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/examples/geometries/f06_unconformity.html#sphx-glr-examples-geometries-f06-unconformity-py">
  <img alt="colormapped image plot thumbnail" src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/model6_nodata.png?raw=true" width="300" />
  </a>
  </td>

</tr>
</table>
</p>

### Features

<p>
<table>
<tr>
                                                                                                                                                                                                                               
  <td>
  <a href="https://docs.gempy.org/tutorials/b_fundamentals/d04_2d_visualization.html#sphx-glr-tutorials-b-fundamentals-d04-2d-visualization-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_d04_2d_visualization_thumb.png" width="300" />
  </a>
  </td>

  <td>
  <a href="https://docs.gempy.org/tutorials/b_fundamentals/e05_3d_visualization.html#sphx-glr-tutorials-b-fundamentals-e05-3d-visualization-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_e05_3d_visualization_thumb.png" width="300" />
  </a>
  </td>

  <td>
  <a href="https://docs.gempy.org/tutorials/b_fundamentals/b02_cross_section.html#sphx-glr-tutorials-b-fundamentals-b02-cross-section-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_b02_cross_section_thumb.png" width="300" />
  </a>
  </td>

</tr>
<tr>
 
  <td>
  <a href="https://docs.gempy.org/examples/geometries/g07_combination.html#sphx-glr-examples-geometries-g07-combination-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_g07_combination_005.png" width="300" />
  </a>
  </td>

  <td>
  <a href="https://docs.gempy.org/tutorials/c_advanced/c03_kriging.html#sphx-glr-tutorials-c-advanced-c03-kriging-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_c03_kriging_thumb.png" width="300" />
  </a>
  </td>

  <td>
  <a href="https://docs.gempy.org/tutorials/c_advanced/d04_topology.html#sphx-glr-tutorials-c-advanced-d04-topology-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_d04_topology_003.png" width="300" />
  </a>
  </td>

</tr>
</table>



### Case studies

<p>
<table>
<tr>

  <td>
  <a href="https://docs.gempy.org/examples/real/Alesmodel.html#sphx-glr-examples-real-alesmodel-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_Alesmodel_008.png" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/examples/real/Perth_basin.html#sphx-glr-examples-real-perth-basin-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_Perth_basin_006.png" width="300" />
  </a>
  </td>
  
   <td>
  <a href="https://docs.gempy.org/examples/real/Greenstone.html#sphx-glr-examples-real-greenstone-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_Greenstone_004.png" width="300" />
  </a>
  </td>
</tr>
</table>

<a name="ref"></a>


