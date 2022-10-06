---
layout: default
---

## The SIMToolbox project

SIMToolbox is an open-source, modular set of functions for MATLAB designed for processing data acquired by structured illumination microscopy. Both optical sectioning and super-resolution applications are supported. The software is also capable of maximum a posteriori probability image estimation (MAP-SIM), an alternative method for reconstruction of structured illumination images. MAP-SIM can potentially reduce reconstruction artifacts, which commonly occur due to refractive index mismatch within the sample and to imperfections in the illumination.

If you use SIMToolbox for your research or education, please cite our *associated publications*:

> T. Lukeš, P. Křížek, Z. Švindrych, J. Benda, M. Ovesný, K. Fliegel, M. Klíma, G. M. Hagen,  _Three-dimensional super-resolution structured illumination microscopy with maximum a posteriori probability image estimation_, Optics Express, 22(24), 29805-29817, (2014). [doi:10.1364/OE.22.029805](https://doi.org/10.1364/OE.22.029805)

> P. Křížek, T. Lukeš, M. Ovesný, K. Fliegel, G. M. Hagen,  _SIMToolbox: A MATLAB toolbox for structured illumination fluorescence microscopy_. Bioinformatics, 32(2), 318–320, (2016). [doi:10.1093/bioinformatics/btv576](https://doi.org/10.1093/bioinformatics/btv576)

> J. Pospíšil, T. Lukeš, J. Bendesky, K. Fliegel, K. Spendier, G.M. Hagen _Imaging tissues and cells beyond the diffraction limit with structured illumination microscopy and Bayesian image reconstruction_, GigaScience, 8(1), 1-12, (2019). [doi:10.1093/gigascience/giy126](https://doi.org/10.1093/gigascience/giy126)

## Downloads

* The installer of the latest version can be found [here](https://drive.google.com/file/d/1Hmhm3Val_ckNKWkxnz2O9WDBYy9Wmvtl/view?usp=sharing) ([all releases](https://drive.google.com/drive/folders/1Kjs0F8ce0zOW5vhxr6i4A387n1godCyt?usp=sharing) of SIMToolbox)
* The source MATLAB codes of all versions are located in SIMToolbox [github repository](https://github.com/simtoolbox/SIMToolbox)
* Documentation and quick start guides for the [first](https://drive.google.com/drive/folders/1Tk6vLwmEWrc8YiYASAswL-5YCfzHAELl?usp=sharing) and the [second](https://drive.google.com/drive/folders/1gfnQiepMmLAMiP8L2tdlxJ3EzWsdkSsB?usp=sharing) generation are available on the project's [Google Drive](https://drive.google.com/drive/folders/12Ra7U7hotTqoPlDvDLk0IdOBRMBS55_6?usp=sharing)

## Compatibility notes
The GUI is a stand-alone program and does not require MATLAB to be installed. To use the MATLAB functions within SIMToolbox (i.e., without the GUI), MATLAB must be installed. When using SIMToolbox functions without the GUI, the MATLAB ''Image Processing Toolbox'' is required. SIMToolbox also requires the ''MATLAB YAML'' package by Kota Yamaguchi [1] to convert MATLAB objects to/from YAML file format. Note that this package is installed automatically when using the GUI.

[1] K. Yamaguchi. Matlab YAML. Graduate School of Information Sciences, Tohoku University, Japan. 2011.

### Version 2
* The functions were mainly developed with 64bit MATLAB version 2017a in Windows 10.
* The SIMToolbox GUI was compiled with MATLAB 2017a and tested in Windows 7, 8 and 10.
* Latest version of SIMToolbox was testet in 64bit MATLAB versions 2017a-2022a using a conventional computer (Intel® CoreTM i7-4770 CPU, 3.40 GHz; NVIDIA® Quadro® K2000 GPU, 2 GB; RAM 32 GB).

### Version 1
* The functions were mainly developed with 64bit MATLAB versions 2012b-2015a in Windows 7.
* The SIMToolbox GUI was compiled with MATLAB 2015a and tested in Windows 7 and 8.

## Testing Dataset

* [Actin (green LED) LCOS](https://zenodo.org/record/4044159/files/Actin%20%28green%20LED%29%20LCOS.zip?download=1)
  - [calibration (green LED)](https://zenodo.org/record/4044159/files/calibration%20%28green%20LED%29.zip?download=1)
* [Actin_Nikon.tif](https://zenodo.org/record/4044159/files/Actin_Nikon.tif?download=1)
* [Actin_Nikon_z-angle-phase-t.tif](https://zenodo.org/record/4044159/files/Actin_Nikon_z-angle-phase-t.tif?download=1)
* [Mito_Zeiss.tif](https://zenodo.org/record/4044159/files/Mito_Zeiss.tif?download=1)

All testing data can be found on [Zenodo](https://zenodo.org/record/4044159).

## Funding

This project has received funding from:

* UCCS center for the BioFrontiers Institute
* Czech Science Foundation
  - GA17-05840S - Multimedia optimization of shift-variant imaging system models
* Czech Technical University in Prague
  - SGS14/148/OHK3/2T/13 - Super-resolution microscopy imaging of mitochondrial networks
  - SGS16/167/OHK3/2T/13 - Algorithms for video-sequenced live cell super-resolution microscopy
  - SGS18/141/OHK3/2T/13 - Analysis and advanced algorithms for ultra-wide imaging systems

<p align="center">
  <img src="media/mmtg.svg" alt="MMTG" height="30px" style="float:left">
  <img src="media/electrical_engineering.svg" alt="FEE, CTU in Prague" height="30px" style="float:center">
  <img src="media/UCCS_Signature.svg" alt="UCCS" height="30px" style="float:right">
  <br>
</p>

## Contacts

Guy M. Hagen
* web: [HagenLab](https://sites.google.com/view/hagen-lab), [BioFrontiers](https://biofrontiers.uccs.edu/)
* e-mail: [ghagen@uccs.edu](mailto:ghagen@uccs.edu)
* ORCID: [0000-0002-4802-9481](https://orcid.org/0000-0002-4802-9481)
* Google Scholar: [Guy M. Hagen](https://scholar.google.com/citations?user=dOeqmE0AAAAJ&hl=en)
* ResearchGate: [Guy M. Hagen](https://www.researchgate.net/profile/Guy_Hagen)
* WoS: [Guy M. Hagen](https://app.webofknowledge.com/author/record/170726?lang=en_US&SID=F2ZIIVRn7by1Egvjp9K)

Jakub Pospíšil
* e-mail: [jakub.pospisil@uit.no](mailto:jakub.pospisil@uit.no)
* Google Scholar: [Jakub Pospíšil](https://scholar.google.com/citations?user=zz6YRgcAAAAJ&hl=en&oi=sra)

Tomáš Lukeš
* e-mail: [tomas.lukes@epfl.ch](mailto:tomas.lukes@epfl.ch)
