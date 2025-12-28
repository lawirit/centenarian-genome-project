# Centenarian Genome Project

This repository contains scripts for analyzing Single Nucleotide Polymorphisms (SNPs) associated with human longevity.

## Project Structure

- `data/`: contains CSV dataset `longevity_snps.csv`
- `scripts/`: analysis script `analyze.py`

## Usage

Run the analysis script:
```bash
python scripts/analyze.py data/longevity_snps.csv
```

## Dataset

The dataset includes columns: `snp_id`, `chromosome`, `position`, `allele`, `frequency`, `longevity_status`.

## License

MIT