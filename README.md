# nf-core/bacass
**Simple bacterial assembly and annotation pipeline**

[![Build Status](https://travis-ci.org/nf-core/bacass.svg?branch=master)](https://travis-ci.org/nf-core/bacass)
[![Nextflow](https://img.shields.io/badge/nextflow-%E2%89%A518.10.1-brightgreen.svg)](https://www.nextflow.io/)

[![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg)](http://bioconda.github.io/)
[![Docker](https://img.shields.io/docker/automated/nfcore/bacass.svg)](https://hub.docker.com/r/nfcore/bacass)
![Singularity Container available](
https://img.shields.io/badge/singularity-available-7E4C74.svg)

### Introduction


This pipeline is for bacterial assembly of next-gen sequencing reads. It quality-trims your reads, runs QC, including a
metagenomics classifier on your reads to check for purity, assembles the reads with
Unicycler, annotates the assembly with Prokka and runs Quast on the assembly for quality check.

The pipeline is built using [Nextflow](https://www.nextflow.io), a workflow tool to run tasks across multiple compute infrastructures in a very portable manner. It comes with docker / singularity containers making installation trivial and results highly reproducible.


### Documentation
The nf-core/bacass pipeline comes with documentation about the pipeline, found in the `docs/` directory:

1. [Installation](docs/installation.md)
2. Pipeline configuration
    * [Local installation](docs/configuration/local.md)
    * [Adding your own system](docs/configuration/adding_your_own.md)
    * [Reference genomes](docs/configuration/reference_genomes.md)  
3. [Running the pipeline](docs/usage.md)
4. [Output and how to interpret the results](docs/output.md)
5. [Troubleshooting](docs/troubleshooting.md)


### Credits
nf-core/bacass was originally written by Andreas Wilm.
