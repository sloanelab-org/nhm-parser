# Sloane Lab NHM Parser

This repository contains the parser that is used to import data from the [NHM Data Portal](https://data.nhm.ac.uk) into the [Sloane Lab](http://sloanelab.org/) knowledge base.

The main code of the parser is in the Jupyter notebook [NHM_CSV_to_RDF](https://github.com/sloanelab-org/nhm-parser/blob/main/NHM_CSV_to_RDF.ipynb). The following libraries are required:

* [Pandas](https://pandas.pydata.org/), to manipulate and analyse the data
* [RDFlib](http://rdflib.readthedocs.io), to create the RDF graph

The original data from the NHM Data Portal is stored in the [data/nhm](https://github.com/sloanelab-org/nhm-parser/tree/main/data/nhm) directory, and includes 10 NHM datasets that have been ingested into the Sloane Lab Knowledge Base.

The other Jupyter notebook ([NHM_JSON_to_RDF](https://github.com/sloanelab-org/nhm-parser/blob/main/NHM_JSON_to_RDF.ipynb)) was previously used to ingest sample data starting from the NHM JSON format.
