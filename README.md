# Exozodi

This repository contains the analysis code and configuration files for the article "Correction Factors for Habitable Exoplanet Direct Imaging: Consider the
Exozodiacal Dust inside Inner Working Angle" (Yu-Chia Lin et al. 2025). The code is used to generate and analyze simulated images of exozodiacal dust disks.

## Repository Structure

This repository is organized into several directories, each corresponding to a different part of the analysis.

*   [`one_zodi/`](Exozodi/one_zodi/): Contains notebooks and parameter files for modeling a 1-zodi exozodiacal disk using different simulation tools

*   [`Coronagraphic_PSFs/`](Exozodi/Coronagraphic_PSFs/): Contains notebooks and data for generating the Apodized Pupil Lyot Coronagraph (APLC) and Vortex Coronagraph (VC) Point Spread Functions (PSFs).

*   [`Images/`](Exozodi/Images/): The [`images.ipynb`](Exozodi/Images/images.ipynb) notebook contains the code to generate the figures used in the paper.

*   [`Convolution/`](Exozodi/Convolution/): The [`release.ipynb`](Exozodi/Convolution/release.ipynb) notebook details the process of convolving the model images with the coronagraphic PSFs.

## Requirements

To run the notebooks in this repository, you will need to install several external packages:

*   [MCFOST](https://github.com/cpinte/mcfost)
*   [ExoVista](https://github.com/dreamjade/ExoVista), forked from [alexrhowe/ExoVista](https://github.com/alexrhowe/ExoVista)
*   [ZODIPIC](https://irsa.ipac.caltech.edu/data/SPITZER/docs/dataanalysistools/tools/contributed/general/zodipic/)
*   A modified version of [mcfost-python](https://github.com/dreamjade/mcfost-python), forked from [mperrin/mcfost-python](https://github.com/mperrin/mcfost-python)

## Citation

If you use this code in your research, please cite the following paper:
