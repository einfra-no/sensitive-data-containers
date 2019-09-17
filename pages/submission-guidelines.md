## Contribution guidelines
Begin by requesting access to this sensitive-data-containers github repo from [Oskar Vidarsson](mailto:oskar.vidarsson@uib.no), [Kim Brugger](mailto:kim.brugger@uib.no) or [Kjell Petersen](mailto:kjell.petersen@uib.no).

Then you can either clone [the repository](https://github.com/einfra-no/sensitive-data-containers) and follow the instructions below, or edit in your contributions directly through the github web gui for the repo.

### Container documentation
These instructions describe the steps necessary to create a new page for your container.

1. Create a new directory in the `pages` directory, naming convention: yourcontainer-infrastructurename, i.e. selma-tsd
2. Copy the `basic-documentation.md` file from the `templates` directory into the new directory in the `pages` directory.  
3. Follow the instructions in the template to document the testing of your container in a specific sensitive data infrastructure.  
	1. If you already have extensive documentation for your container elsewhere, you can link to relevant parts of it from the different sections of the template. 
4. Save the document with a new name such as `containername.md` or similar.  


### Information for the table
Open the README.md file and add the following information to the table:  
1. Name  
	1. Add a link to the name so the user can go straight to the documentation page?
2. Up to 5 words describing what the container or workflow does  
3. Either a version number or a description of the maturity level such as alpha, beta, first release etc.  
4. Link to the documentation page, that you created with the instructions above, for the container on this page. The link is not the complete url, it's as simple as `pages/name/name.md`.  
5. If editing a local clone: Push the changes to the repository to publish your additions etc to the website, else if editing online: comment your changes and commit. 
6. Verify that all links work as they are supposed to.  
