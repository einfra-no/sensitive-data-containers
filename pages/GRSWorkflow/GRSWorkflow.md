# GRSWorkflow
<h1 align="center">
  <br>
  <a href="https://github.com/neicnordic/GRSworkflow/tree/optimized"><img src="https://raw.githubusercontent.com/neicnordic/GRSworkflow/optimized/.GRSworkflowDAG.png" alt="GRSWorkflow" width="720"></a>
</h1>

## Description
GRSWorkflow is a workflow for genetic risk score estimation developed by Lu Yi at Karolinska Institutet in Sweden and implemented for slurm execution by Oskar Vidarsson at the University of Bergen. All dependencies are handled by using Singularity container technology. 

## Homepage
[https://github.com/neicnordic/GRSworkflow/tree/optimized](https://github.com/neicnordic/GRSworkflow/tree/optimized)

## Software versions
See [the docker file](https://github.com/neicnordic/GRSworkflow/blob/optimized/Dockerfile) for exact versions.  
Container version 18.05

## Software dependencies
* Singularity 2.6.1
* Slurm for the optimized version

## Hardware requirements for testing
* 8GB RAM per node  
* 1 core per node  
* Disk: To be determined  
Note: Hardware requirements for production have not been determined yet.  

## Installation instructions
The installation documentation is located in the [github repository](https://github.com/neicnordic/GRSworkflow/tree/optimized). 

## Test data
The test data is simulated data and is not equivalent in size or run time compared with actual sensitive data.

## Testing instructions 
[Follow these instructions](https://github.com/neicnordic/GRSworkflow/tree/optimized#step-by-step-instructions-to-adapt-the-parallelized-workflow-to-your-local-slurm-setup)

## Testing results with respect to resources
The testing input data will produce insignificant amounts of output data and only requires 8GB RAM and one core per node.  

### Support
Contact [Lu Yi](mailto:lu.yi@ki.se) or [Oskar Vidarsson](mailto:oskar.vidarsson@uib.no) for support enquiries.  
