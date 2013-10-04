federal-election-commision-aggregation
======================================

raw and aggregated data in an easy to use format to document the flow of money in us politics

This data is being produced from the sourcecode :
     github.com/h4ck3rm1k3/rootstrikers-wikipedia

Reading the FEC zip files and parsing them, using a codified description of the data:
     github.com/h4ck3rm1k3/FEC-Field-Documentation

First Example of data located in this directory :
committee/C00136853/info.yml and that refrences on file  committee/C00136853/2000/10/15/7128.fec.yml

There are some more yaml files in the root dir, Template.yml is designed to be imported by the main info.yml and the fecid replaced. 
Sources.yml contains some sources of data in general.

More raw data that needs to be reviewed in the branch : master produced by running the code from the main rootstrikers-wikipedia fech.py.

Contains some code from the fech ruby lib, but most has been rewritten. 

New C++ Code for reading the yaml files in progress:
https://bitbucket.org/h4ck3rm1k3/yaml-cpp
