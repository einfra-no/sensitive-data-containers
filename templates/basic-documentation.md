# "Name of your container(workflow/tool/service etc)" in "the infrastructure it's been tested in"
Logo or other image if it exists

## Description
Write a few key sentences here about what the container provides, and that this page documents how it was tested on which sensitive data infrastructure.

## Homepage of container
Link to the generic home of the container.

## Container version/release
* Version of the container itself (and its full set of related code)

## Other relevant versions
* Version of the container technology that was used for testing
* Versions of any other dependencies on the system that the container was run/tested on, that is known to be relevant.
* For workflows, versions of major tools in the workflow.

## Installation instructions
Document how to install the software on the sensitive data platform it has been tested on  
* TSD instructions, or HUNT-Cloud instructions, or SAFE etc
* Each platform will have its own separate test web page like this.

## Usage instructions
* Brief instructions on how to run the container (and/or link to more documentation)

## Hardware/resource requirements
* Describe resources typically required for production use (often the same as chosen for the actual test below).

## How the container was tested and results

### Test data
Describe briefly the test data selected.
* A mandatory real size dataset that will give an impression of the running time and corresponding needed resources to complete the anlaysis in this infrastructure. Include instruction on obtaining the input data (i.e. from a shared area in the infrastructure or online location).
* Preferably also have a small toy dataset to simply start a small (complete) test run of the container, without doing the full scale test.

### Execution details for the "real size" data test 
Instructions for how to run the workflow or container with the real size test data to produce the results referred to in the next section. Preferably a ready command-line or similar to run the exact same test, and not simply a link to the same documentation as under "Usage instructions" above.

### Results for the "real size" dataset 
The running time, memory consumption, cpu usage, input size and output size of the test run on this infrastructure. "Rule of thumb guideline results", not exact benchmark results.

## Any additional useful information

### Support
Contact information for support questions
You can use `[Name Nameson](mailto:name.nameson@address.domain)` to make a nice looking clickable email address like this: [Name Nameson](mailto:name.nameson@address.domain)
