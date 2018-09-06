jem
==============================

This repository contains JEM (JSON Electrophysiology Metadata form), a web-form for logging metadata during Patch-Seq slice electrophysiology experiments. On production rigs at the Allen Institute JEM is partially populated throughout the experiment by interacting with a workflow sequencing engine. This workflow sequencing engine coordinates technical processes such as image collection and electrophysiology stimulus presentations, as well as communication with our LIMS database. For experimental consistency, off-production users conducting Patch-Seq experiments (both internally at the Institute, as well as externally) should manually enter metadata into JEM.

We are planning on occasionally updating this tool, but with no fixed schedule and with limited support.  The community is welcome to submit issues, but you should not expect an active response.

This software was developed with support from the National Institute Of Mental Health of the National Institutes of Health and National Institute on Aging under Award Number U01MH114812. The content is solely the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

Project Organization
------------

    ├── CONTRIBUTING.md    <- Describes the terms for making contributions
    │
    ├── LICENSE            <- The fine print of this using/redistributing this project
    │
    ├── README.md          <- The top-level README for developers using this project.    
    │
    ├── jem-constants      <- Useful reference data (user library, roi dictionary, etc.)
    │
    ├── jem-examples       <- Examples of valid JEM data for different use cases.
    │
    └── src                <- Source code for use in this project.
