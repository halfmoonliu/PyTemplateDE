[![Tested with GitHub Actions](https://github.com/halfmoonliu/PyTemplateDE/actions/workflows/cicd.yml/badge.svg)](https://github.com/halfmoonliu/PyTemplateDE/actions/workflows/cicd.yml)
## Python template for Data Engineering

This is a python template repository doing the following:

1. Set up enviroment for development:
  File a. **.devcontainer**: contains devcontainer (used CodeSpace defaut python default), setting up the environment for development, specifying things like extentions needed.
  File b. **.gitignore**: specified information to ignore (used GitHub default)
  File c. **requirements**.txt: list required packages for the project.

2. Specify GitHub Actions and Timing
  File d. **Makefile**: when pushed/ pulled to main branch, install packages specified in requirements, then lint, format and test python files in the branch.

3. Provide example python function and test functions 
   File e. **main**.py: contains main functions.
   File f. **test_main**.py: contains test functions for main.

4. Provide an overview of the template
   File g. **README**.md: THIS FILE, explaining the purpose of the directory.
