# Dataset-JSON Hackathon Notebook

## Introduction
This notebook was developed as part of the COSA Dataset-JSON Hackathon. It is experimental and meant as an 
exercise to explore working with Dataset-JSON in Python. This notebook demonstrates using Python Pandas to 
convert Dataset-JSON files to dataframes that are then stored as a CSV file. Some examples that use streaming to 
iteratively process the Dataset-JSON files are included to show how files too big to fit into memory could be 
processed, though this has not been tested with a very large dataset. A Pandas dataframe is then converted back into 
Dataset-JSON to demonstrate creating a Dataset-JSON file from a dataframe.

## Limitations
This notebook was created to experiment with the (currently) draft Dataset-JSON standard. It has not been well tested and
might be extended to try out some new things with Dataset-JSON. Since the Dataset-JSON standard will likely undergo 
revisions prior to being published as a final standard, this notebook may be updated to use new versions of standard.
