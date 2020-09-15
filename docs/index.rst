======================================
A Getting Started Guide to the Genomic Epidemiology of SARS-CoV-2
======================================

This template and tutorial will walk you through the process of running a basic phylogenetic analysis on SARS-CoV-2 data.
We've created these resources with the goal of enabling Departments of Public Health to start using Nextstrain to understand their SARS-CoV-2 genomic data within 1-2 hours.
In addition to the phylogenetic analysis described here, you can use our "drag-and-drop" tool for a clade assignment, mutations calling, and basic sequence quality checks at `clades.nextstrain.org <https://clades.nextstrain.org/>`__.

We also recommend `this 1-hour video overview <https://youtu.be/m4_F2tG58Pc>`__ by Heather Blankenship on how to deploy Nextstrain for a Public Health lab.

Overview: complete walkthrough
======================================

Getting started with analysis
--------------------------------------

The starting point for this section is a FASTA file with sequence data + a TSV file with metadata. You can alternately use our example data to start.

  1. `Setup and installation <setup.md>`__
  2. `Preparing your data <data-prep.md>`__
  3. `Orientation: analysis workflow <orientation-workflow.md>`__
  4. `Orientation: which files should I touch? <orientation-files.md>`__
  5. `Running & troubleshooting <running.md>`__
  6. `Customizing your analysis <customizing-analysis.md>`__
  7. `Customizing your visualization <customizing-visualization.md>`__

Getting started with visualization & interpretation
--------------------------------------

The starting point for this section is a JSON file. You can alternately use our examples to start.

  8. `Options for visualizing and sharing results <sharing.md>`__
  9. `Interpreting your results <interpretation.md>`__
  10. `Writing a narrative to highlight key findings <narratives.md>`__
  11. *Case studies: interpreting your data (coming soon!)*

Help
======================================

If something in this tutorial is broken or unclear, please `open an issue <https://github.com/nextstrain/ncov/issues/new/choose>`__ so we can improve it for everyone.

If you have a specific question, post a note over at the `discussion board <https://discussion.nextstrain.org/>`__ -- we're happy to help!

.. toctree::
   :maxdepth: 1
   :titlesonly:
   :caption: Table of contents
   
   setup
   data-prep
   orientation-workflow
   orientation-files
   running
   customizing-analysis
   customizing-visualization
   sharing
   interpretation
   narratives
