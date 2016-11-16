1) Navigate to the wwwroot folder. Be sure it is this folder and NOT the project folder.

2) Type: `npm install`
    This installs the dependencies as defined in the package.json file.

NOTE: This process puts all of the files for the project into wwwroot to simplify learning.
	  When building a real application, consider moving the source files out of
	  wwwroot and building a script using something like Gulp to copy the resulting
	  .js files along with the templates and stylesheets to wwwroot.