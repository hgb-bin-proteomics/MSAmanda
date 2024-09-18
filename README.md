# MS Amanda

<img src="logo/msamanda.jpg" align="left" width="175px"/>

**MS Amanda** is a scoring system to identify peptides out of tandem mass spectrometry data using a database of known proteins.

The MS Amanda algorithm is especially designed for high resolution and high accuracy tandem mass spectra. One advantage of MS Amanda is the high
speed of spectrum identification, especially since MS Amanda 2.0. In addition, MS Amanda is also very accurate, as we observe a high overlap of
identified spectra with gold-standard algorithms Mascot and SEQUEST.

To cite MS Amanda and for more detailed information on the algorithm please refer to
[Dorfer et al. J Proteome Res. 2014, 13(8)](https://doi.org/10.1021/pr500202e),
[Dorfer et al. Rapid Commun Mass Spectrom. 2021, 35(11)](https://doi.org/10.1002/rcm.9088)
and
[Buur et al. J Proteome Res. 2024, 23(8)](https://doi.org/10.1021/acs.jproteome.3c00785).

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

*Older MS Amanda versions for Proteome Discoverer can be found [here](https://github.com/hgb-bin-proteomics/MSAmanda/tree/master/release/pd).*

## Installation of MS Amanda 3.0 Standalone

MS Amanda 3.0 Standalone can be used from the command line or called from any already established proteomics pipelines.

To install MS Amanda 3.0 please perform the following steps:

- Carefully read the [license agreement](https://github.com/hgb-bin-proteomics/MSAmanda/blob/master/LICENSE) and proceed only if you agree to the terms and conditions.
- **Attention:** Please delete all subfolders in the `MSAmanda3.0` folder. For Mac and Linux users this folder is usually created in your home directory, for Windows users it should be created in `C:\ProgramData`, which is a hidden folder (see [How to view hidden files](https://support.microsoft.com/en-us/windows/view-hidden-files-and-folders-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)).
- Please download the latest version for Windows, Linux, and Mac here:
  - Latest MS Amanda Standalone [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/version.txt) for Windows: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/win/latest.zip)
  - Latest MS Amanda Standalone [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/version.txt) for Linux: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/linux/latest.tar.gz)
  - Latest MS Amanda Standalone [version](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/version.txt) for macOS: [**download**](https://github.com/hgb-bin-proteomics/MSAmanda/raw/master/release/sa/latest/mac/latest.tar.gz)

*Older MS Amanda versions can be found [here](https://github.com/hgb-bin-proteomics/MSAmanda/tree/master/release/sa).*

### Installation on Windows

- Right click on the downloaded `.zip` file and select the menu item `Properties` in the context menu.
- If visible, click `Unblock` at the bottom right of the `Properties` window.
- Click `OK` to close the `Properties` window.
- Extract the downloaded `.zip` file.
- Open a commandline and navigate to the extracted MS Amanda folder.
- Run MS Amanda by calling:
  ```bash
  MSAmanda.exe -s spectrumFile -d proteinDatabase -e settings.xml [-f fileformat] [-o outputfilename]
  ```

### Installation on Linux

- The new version of MS Amanda no longer requires `mono`.
- Extract the MS Amanda archive and navigate to the extracted folder in a terminal.
- MS Amanda for linux can be used the same way as on windows platforms.
- To run MS Amanda please call:
  ```bash
  ./MSAmanda -s spectrumFile -d proteinDatabase -e settings.xml [-f fileformat] [-o outputfilename]
  ```

### Installation on macOS

- The new version of MS Amanda no longer requires `mono`.
- Extract the MS Amanda archive and navigate to the extracted folder in a terminal.
- MS Amanda for Mac can be used the same way as on windows platforms.
- To run MS Amanda please call:
  ```bash
  ./MSAmanda -s spectrumFile -d proteinDatabase -e settings.xml [-f fileformat] [-o outputfilename]
  ```

MS Amanda 3.0 Standalone is now ready for use!.

In addition, MS Amanda Standalone is also integrated in
[SearchGUI](http://compomics.github.io/projects/searchgui.html)
and
[PeptideShaker](http://compomics.github.io/projects/peptide-shaker.html)
!

## Getting Help

In case something isn't working or if you need any help with MS Amanda,
please don't hesitate to reach out to us! Please check out the
[MS Amanda Google Group](https://groups.google.com/d/forum/msamanda)!
Alternatively, you can open
up an issue [here](https://github.com/hgb-bin-proteomics/MSAmanda/issues) or
start a discussion
[there](https://github.com/hgb-bin-proteomics/MSAmanda/discussions).
We are usually fast to respond on GitHub and other users might be able to help
too! Alternatively, you can always drop us an email at the addresses
[below](#contact).

## Known Issues

[List of known issues](https://github.com/hgb-bin-proteomics/MSAmanda/issues)

## Citing

If you are using MS Amanda please cite:
```
MS Amanda, a Universal Identification Algorithm Optimized for High Accuracy Tandem Mass Spectra
Viktoria Dorfer, Peter Pichler, Thomas Stranzl, Johannes Stadlmann, Thomas Taus, Stephan Winkler, and Karl Mechtler
Journal of Proteome Research 2014 13 (8), 3679-3684
DOI: 10.1021/pr500202e
```
and/or
```
MS Amanda 2.0: Advancements in the standalone implementation
Viktoria Dorfer, Marina Strobl, Stephan Winkler, and Karl Mechtler
Rapid Communications in Mass Spectrometry 2021 35 (e9088)
DOI: 10.1002/rcm.9088
```
and/or
```
MS2Rescore 3.0 Is a Modular, Flexible, and User-Friendly Platform to Boost Peptide Identifications, as Showcased with MS Amanda 3.0
Louise M. Buur, Arthur Declercq, Marina Strobl, Robbin Bouwmeester, Sven Degroeve, Lennart Martens, Viktoria Dorfer, and Ralf Gabriels
Journal of Proteome Research 2024 23 (8), 3200-3207
DOI: 10.1021/acs.jproteome.3c00785
```

## Contact

- [marina.strobl@fh-hagenberg.at](mailto:marina.strobl@fh-hagenberg.at)
- [micha.birklbauer@fh-hagenberg.at](mailto:micha.birklbauer@fh-hagenberg.at)
- [louise.buur@fh-hagenberg.at](mailto:louise.buur@fh-hagenberg.at)
- [viktoria.dorfer@fh-hagenberg.at](mailto:viktoria.dorfer@fh-hagenberg.at)
