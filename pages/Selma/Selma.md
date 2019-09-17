# Selma
<h1 align="center">
  <br>
  <a href="https://github.com/elixir-no-nels/Selma"><img src="https://raw.githubusercontent.com/elixir-no-nels/Selma/master/.selma.svg?sanitize=true" alt="Selma" width="300"></a>
</h1>

## Description
Selma is a germline variant calling workflow developed at the University of Bergen. The workflow itself is based on Snakemake and all dependencies are handled by using Docker and Singularity container technology. The workflow has been tested on Colossus on TSD. Selma is named after the mythical Norwegian sea serpent that supposedly lives in Lake Seljord.

## Homepage of container
https://github.com/elixir-no-nels/Selma

## Tool versions
https://github.com/elixir-no-nels/Selma#tools
Selma container version: 19.09

## Dependencies
[Singularity](https://github.com/elixir-no-nels/Selma/blob/master/docs/developer-instructions.md#cloning-this-repository-and-building-the-singularity-image)
Docker: 19.03.2+

## Testing and installation instructions
All testing and installation documentation is located in the github repository:  
1. [TSD instructions](https://github.com/elixir-no-nels/Selma/blob/master/docs/TSD-instructions.md)  
2. [Developer instructions](https://github.com/elixir-no-nels/Selma/blob/master/docs/developer-instructions.md)  
3. [Instructions for local use](https://github.com/elixir-no-nels/Selma/blob/master/docs/instructions-for-local-use.md)  

## Test data
The provided test fastq files were produced by running `head -n 40000 input_R1.fastq > output_R1.fastq` and `head -n 40000 input_R2.fastq > output_R2.fastq` on a larger pair of fastq files.  
The workflow will run all but the last step due to a limitation in that tool, it requires a full scale vcf file as input which is 200MB+.

## Testing results with respect to resources
A test with the provided fastq files should take about 10 minutes on a 16 core and 16GB machine, the disk should have 10GB free space to fit the reference files and output files. For production use you should consider at least a 16 core 16GB+ server with 500GB intermediary storage. The final output files should be less than 100GB per sample.

### Support
Contact [Oskar Vidarsson](mailto:oskar.vidarsson@uib.no) or [Kjell Petersen](mailto:kjell.petersen@uib.no) for support enquiries. 
