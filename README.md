# PolyPhred genotype table

[PolyPhred](https://doi.org/10.1093/nar/25.14.2745) is a software automating the detection and genotyping of single nucleotide polymorphisms (SNPs) and insertions/deletions (indels) from classical Sanger sequencing reads. The main output file from PolyPhred is a complex multi-section report. This script processes this report to generate a summary table of genotypes, reads and scores of each variants for each sample.

## Prerequisites

To generate the genotype table, PolyPhred must be run first. Please, refer to the [PolyPhred](https://doi.org/10.1093/nar/25.14.2745) publication for more information.

## Installation

To download the latest version of the file:
```
git clone https://github.com/fdchevalier/trim_polyphred
```

For convenience, the script should be accessible system-wide by either including the folder in your `$PATH` or by moving the script in a folder present in your path (e.g. `$HOME/local/bin/`).

## Usage

A summary of available options can be obtained using `./trim_polyphred.sh -h`.

## License

This project is licensed under the [GPLv3](LICENSE).
