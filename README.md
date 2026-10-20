# PTERO Desktop — Official Releases

**PTERO** stands for **Proteomics Tool for Exploratory Research & Optimization**.

PTERO Desktop is a Windows application under active development for interactive exploration and analysis of mass spectrometry-based proteomics data.

This public repository hosts downloadable **Windows application builds only**. The PTERO source code is maintained separately in a private development repository.

## Download PTERO

Visit the [Releases page](https://github.com/AyehBlk/ptero-releases/releases) to download an available Windows build.

**Planned public beta:** PTERO Desktop v0.2.0. Availability will be announced when the release is published.

## Main features

PTERO is being developed to support:

- Import and organization of mass spectrometry data, including mzML files.
- Conversion of supported raw data into the PTERO Dataset format.
- Interactive exploration of mass spectra.
- Examination of protein identification results.
- Exploration of protein abundance and quantification results.

Feature availability may vary between beta builds.

## Installation (Windows)

1. Download the Windows ZIP archive from a published release.
2. Extract the **entire** ZIP archive into a folder on your computer.
3. Open the extracted folder and run `PTERO_v1_rc.exe` (or the executable named in that release).
4. Keep the supporting files and folders together.

PTERO is beta software and may contain bugs or incomplete functionality. Test with copies of important datasets.

## Data preparation

Thermo RAW files can be converted to mzML using [ProteoWizard MSConvert](https://proteowizard.sourceforge.io/). For workflows requiring MS1 and MS2, verify that conversion settings preserve both spectrum levels. Additional guidance will be available on the PTERO website.

## Feedback

Researchers are welcome to report reproducible issues and suggestions. Do not include confidential datasets, passwords, or personal information in public issue reports.

## Scientific development

PTERO is part of ongoing research into efficient storage, organization, and interactive exploration of mass spectrometry-based proteomics data. A scientific manuscript describing the architecture and evaluation methodology is in preparation.

## License and distribution

This repository distributes compiled application builds, **not open-source code**. Public download availability does not grant permission to modify or redistribute the software. Applicable end-user license terms should be included with each release before publication.

## Project status

- **Stage:** Public beta (planned)
- **Platform:** Windows
- **Planned version:** v0.2.0
- **Maintainer:** PTERO Development
