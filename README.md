jem
==============================

This repository contains JEM (JSON Electrophysiology Metadata form), a web-form for logging metadata during Patch-Seq slice electrophysiology experiments. On production rigs at the Allen Institute JEM is partially populated throughout the experiment by interacting with a workflow sequencing engine. This workflow sequencing engine coordinates technical processes such as image collection and electrophysiology stimulus presentations, as well as communication with our LIMS database. For experimental consistency, off-production users conducting Patch-Seq experiments (both internally at the Institute, as well as externally) should manually enter metadata into JEM.

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── jem-constants      <- Useful reference data (user library, roi dictionary, etc.)
    │
    ├── jem-examples       <- Examples of valid JEM data for different use cases.
    │
    └── src                <- Source code for use in this project.
