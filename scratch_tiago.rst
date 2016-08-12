Online content
==============

- `github repo`_
- notebooks_
- Docker hub
- `course documentation`_
- `Genomics core`_
  - Explain what will be available


Python environment
==================

- git and github
- Docker
- Python **3**, not 2
- IPython
- Project Jupyter
- matplotlib
- scikit-learn
- numpy
- scipy
- pandas
  - R data-frames
- pytables
- dask

Data management
===============

- Very light introduction to the dataset

  - Whole Genome Sequencing of mosquitoes
- Meta-data exploration

  - matplotlib
  - pandas

- Data exploration (initial)
- Processing VCF files, speed
- The HDF format
- Converting to HDF5

    - vcfnp
    - refer dask (below)


Subsampling, language and concurrency issues
============================================

- HDF5 conversion with dask

  - Threads, cores, processes
  - Clusters
  - Get a better example! Too simple

- subsampling

  - filtering

    - iterators vs generators

      - range example
      - generator chaining
- Python specific

  - GIL

- Applicable to other languages

  - asyncio (after GIL)

Integrating with R
==================

- rpy2

Galaxy programming interface
============================

- bioblend

UMontana DBS specific stuff
===========================

- Server structure

  - carnation

    - Docker containers

      - architecture (LDAP, Cluster, Galaxy)
      - access
        - Galaxy
        - ssh
        - Jupyter
        - web apps

  - Jeff and John servers
  - Zac server

- File structure

  - NFS and network transparency
  - raw data, scratch, user directories
  - backups
  - Cluster (network transparency)
  - space on core server
  - GPU

.. _`github repo`: https://github.com/tiagoantao/data-science-teaching
.. _notebooks: http://nbviewer.jupyter.org/github/tiagoantao/data-science-teaching/blob/master/notebooks/Index.ipynb
.. _`course documentation`: https://github.com/tiagoantao/data-science-teaching
.. _`Genomics core`: http://hs.umt.edu/dbs/labs/genomics/
