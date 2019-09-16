### Submission guidelines
Begin by requesting push access from [Oskar Vidarsson](mailto:oskar.vidarsson@uib.no), [Kim Brugger](mailto:kim.brugger@uib.no) or [Kjell Petersen](mailto:kjell.petersen@uib.no).

Then you can clone the repository and follow the instructions below.

#### End user documentation
These instructions describe the steps necessary to create a new page for your container.

-- Create a new directory with the same name as your workflow/tool/etc in the `docs` directory.  
-- Copy the `_config.yaml` and `basic-documentation.md` files from the `templates` directory into the new directory in the `pages` directory.  
    -- If you already have documented your container elsewhere, you can use [this example](https://github.com/einfra-no/sensitive-data-containers/blob/master/pages/Selma/Selma.md) as inspiration instead of documenting it twice.  
-- Follow the instructions in the template.  
-- Save the document with a new name such as `containername.md` or similar.  
-- Push the changes to the repository to publish the instructions etc to the website.  
-- Verify that all links work as they are supposed to.  

#### Information for the table
Open the README.md file and add the following information to the table:  
-- Name  
-- Up to 5 words describing what the container or workflow does  
-- Either a version number or a description of the maturity level such as alpha, beta, first release etc.  
-- Link to the documentation page, that you created with the instructions above, for the container on this page. The link is not the complete url, it's as simple as `pages/name/name.md`.  
