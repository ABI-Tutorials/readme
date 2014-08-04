Introduction
======

The goal of this organisation is to collect the tutorials developed at the ABI into one place to better manage their developement and modification for each new tutorial delivered. We aim to develop the tutorials using reStructuredText and Sphinx.

Concepts
=======

The basic idea is to have a collection of tutorial "modules" that describe specific tasks that users might want to complete using the software tools or data encoding technologies developed at the ABI and with our collaborators. Each module will be housed in a GitHub repository, and each instance of the module will be a branch in that repository. For example, a module might be loading a CellML model into OpenCOR, running a simulation, and plotting some results. The basic description for this task is common to all CellML models, but different instances of the tutorial will likely exist which perform this task with different CellML models. A given tutorial will then make use of the particular branch which presents the task using the model best suited for target audience of the tutorial (e.g., cardiac electrophysiology, mechanical constitutive relation, kidney, lung, etc...).

Each tutorial will be a separate GitHub repository under this organisation. Ideally, as we get more practiced in pulling tutorials together, the actual preparation of the tutorial will be more on the individual modules that are simply pulled together rather than the overarching tutorial framework. A given tutorial will consist of the actual software documentation for the corresponding version of each of the software tools used in the tutorial (Physiome Repository, PMR2, OpenCOR, MAPClient, etc.) and the specific tasks to be demonstrated.

Ideally, the software tool documentation will simply require the embedding in the git repository of the software tool's own documentation at the appropriate version for the tool being used in the tutorial. For example, using git submodules. In some cases, we may need to take the actual tool documentation and convert it to rST/Sphinx (see the [OpenCOR issue] (https://github.com/opencor/opencor/issues/431) for example). Similarly, the various task tutorial modules can simply embed the appropriate branch of module's repository.
