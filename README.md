## Containers for use on TSD
N.B: This is a curated list of [Singularity](https://www.sylabs.io/singularity/) containers that are verified to work on TSD.

| Name | Purpose                  | Workflow language | Major features                     |
|------|--------------------------|-------------------|------------------------------------|
| [GVCP](https://github.com/elixir-no-nels/snakemake_germline) | Germline variant calling | Snakemake         | Highly parallelized, based on GATK                     |
| [rbFlow-Germline](https://github.com/elixir-no-nels/snakemake_germline) | Germline variant calling | rbFlow lite | Based on GATK |
|      |                          |                   |                                    |
|      |                          |                   |                                    |

## [GVCP](https://github.com/elixir-no-nels/snakemake_germline)
### Features
* Germline variant calling for individual genomes
* Multi sample support 
* Slurm status reporting
* Highly parallelized execution

