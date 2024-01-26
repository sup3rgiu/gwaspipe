# GWASPipe

A Python tool, based on [GWASLab](https://cloufield.github.io/gwaslab/), for assembling a computational pipeline to standardize, QC, harmonize, convert, and plot your summary statistics.

## Requirements
see [environment.yml](environment.yml) and [Makefile](Makefile)

## Getting started

The script needs a configuration file, a summary statistics file and its format as input.

e.g.: `python src/gwaspipe.py -c examples/config_ldscore_pipe.yml -i ./data/seq.13392.13_res.gwas.regenie.gz -f regenie`

Input format can be: regenie, fastgwa, ldsc, fuma

There are some example configuration files in the [examples](examples) directory.
