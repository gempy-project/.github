# <p align="center"><img src="https://github.com/gempy-project/gempy/blob/main/docs/readme_images/header_combined_slim.png" width="1000"></p> 
 
[![GitHub Stars](https://img.shields.io/github/stars/cgre-aachen/gempy.svg)](https://github.com/cgre-aachen/gempy/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/cgre-aachen/gempy.svg)](https://github.com/cgre-aachen/gempy/network)
[![PyPI](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/release/python-31013/)
[![PyPI](https://img.shields.io/badge/pypi-1.0-blue.svg)](https://pypi.org/project/gempy/)
[![license: EUPL v1.2](https://img.shields.io/badge/license-EUPL%20v1.2-blue.svg)](https://github.com/cgre-aachen/gempy/blob/master/LICENSE)
[![Documentation Status](https://assets.readthedocs.org/static/projects/badges/passing-flat.svg)](http://docs.gempy.org)
[![DOI](https://zenodo.org/badge/96211155.svg)](https://zenodo.org/badge/latestdoi/96211155)


## What's New: GemPy 2024.1 (a.k.a GemPy v3) Release!


Welcome to the era of GemPy v3! We are thrilled to announce the release of the latest version, a product of meticulous planning, redesign, and rigorous testing. While the core essence remains intact, v3 brings significant enhancements and novelties that promise to revolutionize your geomodeling experience.

Delve into the exciting new features in the [What's New in GemPy v3](https://github.com/gempy-project/gempy/blob/main/WhatsNewGemPy3.md).

The journey from GemPy v2 to v3 has been transformative. To ensure that our users don't lose out on any previous functionalities, we've shifted v2 to a package named [gempy_legacy](https://github.com/gempy-project/gempy_legacy). While the core team will not develop any new features for this version, we'll continue maintaining it based on community requests.

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
  <a href="https://docs.gempy.org/tutorials/ch1_fundamentals/ch1_3b_cross_sections.html#sphx-glr-tutorials-ch1-fundamentals-ch1-3b-cross-sections-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_ch1_3b_cross_sections_004.png" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/tutorials/ch1_fundamentals/ch1_4_onlap_relations.html#sphx-glr-tutorials-ch1-fundamentals-ch1-4-onlap-relations-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_ch1_4_onlap_relations_002.png" width="300" />
  </a>
  </td>
  
   <td>
  <a href="https://docs.gempy.org/examples/geometries/g07_combination.html#sphx-glr-examples-geometries-g07-combination-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_g07_combination_005.png" width="300" />
  </a>
  </td>

</tr>
<tr>
  <td>
  <a href="https://docs.gempy.org/tutorials/ch3-Interpolations/ch3_1_kriging_interpolation_and_simulation.html#sphx-glr-tutorials-ch3-interpolations-ch3-1-kriging-interpolation-and-simulation-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_ch3_1_kriging_interpolation_and_simulation_003.png" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/tutorials/ch4-Topology/ch4-1-Topology.html#sphx-glr-tutorials-ch4-topology-ch4-1-topology-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_ch4-1-Topology_005.png" width="300" />
  </a>
  </td>
  
  <td>
  <a href="https://docs.gempy.org/tutorials/ch4-Topology/ch4-1-Topology.html#sphx-glr-tutorials-ch4-topology-ch4-1-topology-py">
  <img alt="colormapped image plot thumbnail" src="https://docs.gempy.org/_images/sphx_glr_ch4-1-Topology_004.png" width="300" />
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


