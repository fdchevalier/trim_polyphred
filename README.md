# PolyPhred genotype table

[PolyPhred](https://doi.org/10.1093/nar/25.14.2745) is a software automating the detection and genotyping of single nucleotide polymorphisms (SNPs) and insertions/deletions (indels) from classical Sanger sequencing reads. The main output file from PolyPhred is a complex multi-section report. This script aims to generate a simple genotype table from this report that indicates for each sample if the variant is supported by one or both reads.

## Prerequisites

To generate the genotype table, PolyPhred must be run first. Please, refer to the [PolyPhred](https://doi.org/10.1093/nar/25.14.2745) publication for more information.

## Installation

To download the latest version of the file:
```
git clone https://github.com/fdchevalier/trim_polyphred
```

For convenience, the script should be accessible system-wide by either including the folder in your `$PATH` or by moving the script in a folder present in your path (e.g. `$HOME/local/bin/`).

## License

This project is licensed under the [GPLv3](LICENSE).
