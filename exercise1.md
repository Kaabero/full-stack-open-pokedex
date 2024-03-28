In this exercise I assume that the application is coded with Python. 

In the Python ecosystem, there are several popular tools used for CI/CD to handle linting, testing and building. 

For linting the commonly used tools are Flake8 and Pylint. Flake8 checks Python code against style conventions outlined in PEP 8, 
identifies syntax error and flags common programming errors. Pylint checks style issues and performs code analysis to detect 
errors, potential bugs and maintainability issues. 

For testing the commonly used tools are pytest and unittest. Pytest is a testing framework for Python that allows writing simple 
and scalable test cases with support for fixtures, parameterization and various types of assertions. Unittest is more traditional 
Python's built-in unit testing framework. 

For building the commonly used tools are setuptools and pip. Setuptools is a package development process library that provides 
functions for building, packaging and distributing Python packages. Pip can be used for installing and managing dependencies. 

Besides Jenkins and GitHub Actions, there are several alternative CI/CD platforms and tools available that can be used to set up 
CI and that can be used with Python applications: Travis CI, CircleCI, GitLab CI/CD, Bitbucket Pipelines, Azure Pipelines and 
Bamboo.

The application is being worked on by a team of about 6 people. Therefor it can be assumed that the project is a small to medium 
project. If there isn't any special requirements, then the cloud-based solution would probably be the best. The configuration is 
simple and for smaller projects especially, this should be the cheaper option. For larger projects where more resources are needed 
or in larger companies a self-hosted CI setup is probably the better option.    
