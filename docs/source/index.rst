HELP
============

1.What information is available in SpatialRef?
~~~~~~~~~~~~~~~

Spatial omics can capture molecular characteristics, tissue morphology, spatial locations, and the three-dimensional proximity of biological entities, making it possible to create detailed spatial maps and blueprints. Accurate cell type annotation of these spatial spots and domains is a fundamental task in cell and tissue biology. This is crucial for various downstream analyses in spatial omics research. Here, we have developed a SpatialRef 
`(https://bio.liclab.net/spatialref/) <https://bio.liclab.net/spatialref/>`_, a manually curated spatial omics database. SpatialRef provides expertly annotated spatial omic data and integrates diverse functions for analyzing and displaying the spatial information related to spots or tissues. SpatialRef analyzes these manually annotated spot types to identify and display spot type-specific marker genes, perform GO and KEGG pathway enrichment, explore spatial communication, and spatial trajectory.

2.Data Content in SpatialRef?
~~~~~~~~~~~~~~~
The current version of SpatialRef aggregates approximately 3 million spots across 11 human and mouse tissue types, further categorized into 182 spot types or spatial domains. These data originate from multiple platforms, including NCBI, HCA, EMBL-EBI, GitHub, and Zenodo, and cover technologies such as MERFISH, 10X Visium, Slide-seq, Slide-seqV2, ST, seqFISH, and CODEX. Notably, the known spot types within SpatialRef adhere to original paper annotations, ensuring accuracy and reliability. Additionally, SpatialRef analyzes these manually annotated spot types to identify and display spot type-specific marker genes, perform GO and KEGG pathway enrichment, explore spatial communication, and spatial trajectory.

3.How to use the SpatialRef?
~~~~~~~~~~~~~~~
3.1.Data-Browse
^^^^^^^^^^^^^^^^^^^^^
The “Data-Browser” page adopts an interactive, alphanumeric-sorted table format. The browser table displays Sample ID, Known Spot/Domain Type, Technology, Tissue, PMID, Disease status, Species, Sample Name, and Spot Number, Annotation strategy from Original Article, Spot/Domain. Users can quickly search samples and customize filter criteria through “Species”, “Technology”, “Tissue”, “Disease Status”, “Spot/Domain”, “SpatialQC score” and “Known Spot Type”. Users can use the dropdown menu at the bottom of the table to change the number of entries displayed per page. Simply clicking on the “Sample ID” allows users to view the detailed information of a given sample.

.. image:: ../help/Browse.png
    :width: 80%
    :align: center
    :alt: this is a Browse image

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
   test
