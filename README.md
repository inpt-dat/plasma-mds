# Plasma Metadata Schema (Plasma-MDS)
This repository contains the schema and example files for Plasma-MDS.

## Aim

The Plasma Metadata Schema (Plasma-MDS) was developed to support the findability and reusability of research data in applied plasma physics and plasma medicine. So far, it is implemented in the [INPTDAT](https://www.inptdat.de/) data platform and the research data repository of the Research Department Plasmas with Complex Interactions at Ruhr Universität Bochum ([https://rdpcidat.rub.de](https://rdpcidat.rub.de/)).

This repository is intended to provide a way for collaborative advancement of the metadata schema by the community. Therefore, the folder `dev/` is prepared to collect flat listings of properties, e.g. for plasma sources, media, substrates, diagnostics etc., which are considered to be relevant for a proper documentation of these entities. Further information on the structure and how one can contribute is given in [dev/README.md](dev/README.md).

## Metadata Schema

Plasma-MDS aims to be a starting point for the development of a standard for the categorization and documentation of digital data obtained from research in plasma physics. It comprises various metadata fields related to the plasma source, the plasma medium, the plasma target and the diagnostics (experimental or computational methods) involved in the study. Furthermore, metadata fields related to published resource (data files) are included. Plasma-MDS aims to extend generic schemata like Dublin Core by domain specific metadata elements as illustrated in the following figure:

<img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41597-020-00771-0/MediaObjects/41597_2020_771_Fig1_HTML.png" width="500">

Overview of the schema elements and qualifiers of Plasma-MDS (blue). The sketch illustrates how the domain-specific schema extends general metadata of datasets according to basic metadata schemata like Dublin Core (DC), DataCite, or DCAT (from: [Franke, St. *et al.*, *Sci Data* **7**, 439 (2020)](https://rdcu.be/ccqQx)).

## Publications

* Documentation of the initial version v1.0.0: [Franke, St. *et al.*, *Sci Data* **7**, 439 (2020)](https://rdcu.be/ccqQx)
* Publication of the latest release: [![DOI](https://zenodo.org/badge/326775660.svg)](https://zenodo.org/badge/latestdoi/326775660)

## License

Plasma-MDS is distributed under a [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Acknowledgements

The development of the initial version of Plasma-MDS was funded by the Federal Ministry of Education and Research – BMBF under grant 16FDM005. The further development of the metadata schema is currently supported by BMBF under grant 16QK03A.
