## Contribution guidelines
Begin by requesting access to this sensitive-data-containers github repo from Oskar.Vidarsson _at_ uib.no, Kim.Brugger _at_ uib.no or Kjell.Petersen _at_ uib.no.

Then you can either clone [the repository](https://github.com/einfra-no/sensitive-data-containers) and follow the instructions below, or edit in your contributions directly through the github web gui for the repo.

This website aims at collecting useful workflows/tools etc for analysis of sensitive data, all implemented using containers for easy portability and testing. In the following text, we refer to a useful resource such as a workflow or tool and all its relevant code such as config and setup scripts, as a container.

### Container documentation
These instructions describe the steps necessary to create a new page for your container.

1. Create a new directory in the `pages` directory, naming convention: yourcontainername-infrastructurename, i.e. selma-tsd.
2. Copy the `basic-documentation.md` file from the `templates` directory into the new directory in the `pages` directory.  
3. Follow the instructions in the template to document the testing of your container in a specific sensitive data infrastructure.  
	1. If you already have extensive documentation for your container elsewhere, you can link to relevant parts of it from the different sections of the template. 
4. Save the document with a new name such as `yourcontainername.md` or similar.  


### Information for the table
Open the README.md file and add the following information to the table:  
1. Name  
	1. Do _not_ add a link to container homepage, will be part of the container specific tes/usage page instead.
2. Up to 5 words describing what the container or workflow does  
3. Either a version number or a description of the maturity level such as alpha, beta, first release etc.  
4. Link to the documentation page, that you created with the instructions above, for the container on this page. The link is not the complete url, it's as simple as `pages/yourcontainername-infrastructurename/yourcontainername.md`. NB: Multiple links for different infrastructures and same container would go into this same "Usage documentation column", with different named links, reflecting the infrastructure and container combination. i.e. "TSD Selma documentation". 
5. If editing a local clone: Push the changes to the repository to publish your additions etc to the website, else if editing online: comment your changes and commit. 
6. Verify that all links work as they are supposed to.  
