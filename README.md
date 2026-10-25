# Awesome-Document-Extraction-API

# Top Digital Negative (DNG) Conversion
**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on RAW to DNG Conversion, Camera Raw Processing, Universal RAW Formats & Desktop RAW Tools*

**Last updated: October 2026**

This repository tracks notable **commercial applications** and **open-source projects** for **Digital Negative (DNG) Conversion** and RAW file processing. These tools convert proprietary camera RAW formats into the open Adobe DNG standard or provide advanced RAW decoding and development capabilities.

**Examples** include Adobe DNG Converter, RawTherapee, darktable, DxO PureRAW, Capture One, FastRawViewer, Iridient Developer, dcraw, LibRaw, and ON1 NoNoise AI (the category leaders).

**Open-source emphasis**: DNG and RAW processing benefits from excellent open-source foundations. **LibRaw**, **dcraw**, **darktable**, **RawTherapee**, and related projects provide robust, fully free tools for converting, decoding, and processing camera RAW files. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Adobe DNG Converter](https://helpx.adobe.com/camera-raw/using/adobe-dng-converter.html)**  
  Official free utility from Adobe that converts proprietary camera RAW files into the open Digital Negative (DNG) format for better long-term compatibility and archival.

- **[DxO PureRAW](https://www.dxo.com/dxo-pureraw/)**  
  Specialized RAW processing tool focused on superior denoising, demosaicing, and optical corrections before exporting to DNG or other formats.

- **[Capture One](https://www.captureone.com/)**  
  Professional RAW editor that supports high-quality conversion and export to DNG alongside its advanced color and tethered workflow tools.

- **[FastRawViewer](https://www.fastrawviewer.com/)**  
  Fast RAW viewer and analysis tool that can work with DNG and proprietary RAW files, popular for culling and technical inspection.

- **[Iridient Developer](https://www.iridientdigital.com/)**  
  High-quality RAW developer known for excellent demosaicing and detail rendering, with strong DNG support.

- **[ON1 NoNoise AI / ON1 Photo RAW](https://www.on1.com/)**  
  AI-powered noise reduction and RAW processing tools that can output cleaned files in DNG and other formats.

- **[Adobe Camera Raw / Lightroom](https://www.adobe.com/products/photoshop-lightroom-classic.html)**  
  Industry-standard RAW processing engine that natively supports DNG and can convert other formats into DNG workflows.

- **[Affinity Photo](https://affinity.serif.com/photo/)**  
  Professional photo editor with solid RAW development capabilities and support for DNG files.

- **[Exposure X](https://exposure.software/)**  
  Creative RAW editor that works with DNG and proprietary formats, focused on non-destructive editing and film-inspired looks.

- **[PhotoLab (DxO)](https://www.dxo.com/dxo-photolab/)**  
  Advanced RAW converter with DeepPRIME technology that can process and export high-quality DNGs.

## Open-Source GitHub Projects
- **[LibRaw](https://github.com/LibRaw/LibRaw)**  
  Widely used open-source library for reading and processing RAW files from a broad range of digital cameras. Foundation for many RAW converters and DNG-related tools.

- **[dcraw](https://github.com)** (original by Dave Coffin) / modern forks  
  Classic open-source RAW decoder that pioneered support for many camera formats. Still influential and used as a reference or backend in various tools.

- **[darktable](https://github.com/darktable-org/darktable)**  
  Powerful open-source photography workflow application with excellent RAW support. Can import proprietary RAW files and work with or export DNG in professional pipelines.

- **[RawTherapee](https://github.com/Beep558/RawTherapee)**  
  Advanced open-source RAW image processing program with high-quality demosaicing, detailed controls, and support for DNG and many proprietary formats.

- **[ART (Another RawTherapee)](https://github.com/artpixls/ART)**  
  Actively maintained fork of RawTherapee focused on usability improvements and continued development of open-source RAW processing.

- **[ExifTool](https://github.com/exiftool/exiftool)**  
  Legendary open-source metadata tool that can read, write, and manipulate DNG and RAW metadata, essential for batch conversion workflows.

- **[rawspeed](https://github.com/darktable-org/rawspeed)**  
  Fast open-source RAW decoding library used by darktable and other projects for high-performance camera support.

- **[UFRaw](https://github.com)** (legacy) / modern successors  
  Earlier open-source RAW developer that integrated with GIMP; its ideas live on in current tools.

- **[RawPy](https://github.com/letmaik/rawpy)**  
  Python wrapper around LibRaw, making it easy to read and process RAW/DNG files in Python scripts and pipelines.

- **[DNG SDK related open tools](https://github.com)**  
  Community tools and scripts built around Adobe’s DNG specification for validation, conversion, and archival workflows.

### Additional Strong Open-Source Options
- Core decoding libraries: **LibRaw**, **rawspeed**, **dcraw** lineage.
- Full RAW editors with DNG support: **darktable**, **RawTherapee**, **ART**.
- Metadata & batch processing: **ExifTool**.
- Scripting / automation: **RawPy** and LibRaw bindings.
- Accepting that commercial tools (Adobe DNG Converter, DxO PureRAW, Capture One, Iridient Developer) still lead in ease of use, optical corrections, AI denoising, and polished one-click conversion for many photographers.

**Frameworks for building custom systems**:  
Use **LibRaw** or **rawspeed** for decoding → process with **darktable** or **RawTherapee/ART** → handle metadata with **ExifTool** → automate via **RawPy** or shell scripts. Ideal for photographers, archivists, and developers who want open, long-term accessible RAW/DNG pipelines without proprietary lock-in.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Camera RAW support varies by tool and camera model. Always verify compatibility with your specific camera files. DNG is an open standard, but conversion quality and feature support differ between applications. This list is not professional archival or photography advice.

---
**Made for photographers, digital archivists, and open-source imaging advocates.**

Let's keep RAW processing and DNG conversion open, reliable, and future-proof.
