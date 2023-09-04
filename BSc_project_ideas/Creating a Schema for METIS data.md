# Creating a Schema for METIS data

**Title**: Creating a Schema for METIS data

**Status**: Available from 1st October 2023

**Supervisor**: Dr. Hugo Buddelmeijer (Univ. Vienna)

**Contact information**: hugo.buddelmeijer@univie.ac.at

**Expected duration**: 6 months


## Project description

The University of Vienna has the lead in the creation of the data processing pipeline for the METIS instrument on the ELT.
The data processing workflow chains together several processing steps that exchange data through FITS files.

It would be useful to have a schema for the FITS files, because the data processing is becoming more complex than for earlier projects.

The schema would allow:

- Automatic verification whether individual processing steps create data in the proper format.
- Creation of tools to automatically load data according to the specification.
- Ensuring that the ScopeSim data simulator can produce data according to the schema.
- Automatic creation of databases based on the schema.
- Automatic creation of (web) API's interacting with such a database.

The schema can be based on the Virtual Observatory Data Modeling Language (VO-DML), and using tools like Schematron. Similar work has been done for MICADO, but not yet for METIS.


## Literature

- https://wiki.ivoa.net/bin/view/IVOA/VODML
- https://scopesim.readthedocs.io/en/latest/
- https://elt.eso.org/instrument/METIS/
- https://elt.eso.org/instrument/MICADO/
