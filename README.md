# MS Amanda

<img src="logo/msamanda.jpg" align="left" width="175px"/>

**MS Amanda** is a scoring system to identify peptides out of tandem mass spectrometry data using a database of known proteins.

The MS Amanda algorithm is especially designed for high resolution and high accuracy tandem mass spectra. One advantage of MS Amanda is the high
speed of spectrum identification, especially since MS Amanda 2.0. In addition, MS Amanda is also very accurate, as we observe a high overlap of
identified spectra with gold-standard algorithms Mascot and SEQUEST.

To cite MS Amanda and for more detailed information on the algorithm please refer to
[Dorfer et al. J Proteome Res. 2014, 13(8)](https://doi.org/10.1021/pr500202e)
and
[Dorfer et al. Rapid Commun Mass Spectrom. 2021, 35(11)](https://doi.org/10.1002/rcm.9088)
.

## Installation of MS Amanda for Proteome Discoverer

The Proteome Discoverer Node of MS Amanda can be used with
[Thermo Scientific's Proteome Discoverer](https://www.thermofisher.com/at/en/home/industrial/mass-spectrometry/liquid-chromatography-mass-spectrometry-lc-ms/lc-ms-software/multi-omics-data-analysis/proteome-discoverer-software.html).
To install MS Amanda, please perform the following steps:

- Close Proteome Discoverer
- Download the latest MS Amanda installer:
  - Latest MS Amanda 3.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD3.1/latest/version.txt) for Proteome Discoverer 3.1: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD3.1/latest/latest.zip)
  - Latest MS Amanda 2.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD3.0/latest/version.txt) for Proteome Discoverer 3.0: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD3.0/latest/latest.zip)
  - Latest MS Amanda 2.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.5/latest/version.txt) for Proteome Discoverer 2.5: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.5/latest/latest.zip)
  - Latest MS Amanda 2.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.4/latest/version.txt) for Proteome Discoverer 2.4: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.4/latest/latest.zip)
  - Latest MS Amanda 2.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.3/latest/version.txt) for Proteome Discoverer 2.3: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.3/latest/latest.zip)
  - Latest MS Amanda 2.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.2/latest/version.txt) for Proteome Discoverer 2.2: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.2/latest/latest.zip)
  - Latest MS Amanda 2.0 [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.1/latest/version.txt) for Proteome Discoverer 2.1: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/pd/PD2.1/latest/latest.zip)
- Follow the installation instructions and carefully read the license agreement
- Restart Proteome Discoverer

MS Amanda 2.0/3.0 should now be successfully installed on your computer!

## Installation of MS Amanda 3.0 Standalone

MS Amanda 3.0 Standalone can be used from the command line or called from any already established proteomics pipelines.

To install MS Amanda 3.0 please perform the following steps:

- Carefully read the [license agreement](https://github.com/hgb-bin-proteomics/MSAmanda/blob/master/LICENSE) and proceed only if you agree to the terms and conditions.
- **Attention:** Please delete all subfolders in the `MSAmanda3.0` folder. For Mac and Linux users this folder is usually created in your home directory, for Windows users it should be created in `C:\ProgramData`, which is a hidden folder (see [How to view hidden files](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)).
- Please download the latest version for Windows, Linux, and Mac here:
  - Latest MS Amanda Standalone [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/version.txt) for Windows: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/win/latest.zip)
  - Latest MS Amanda Standalone [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/version.txt) for Linux: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/linux/latest.tar.gz)
  - Latest MS Amanda Standalone [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/version.txt) for macOS: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/mac/latest.tar.gz)
