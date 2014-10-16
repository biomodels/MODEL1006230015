# MODEL1006230015: Lindblad1996_ActionPotential_AtrialMyocyte

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230015.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230015.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230015 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A model of the action potential and underlying membrane currents in a rabbit atrial cell.**   
Lindblad DS, Murphey CR, Clark JW, Giles WR. _Am J Physiol_ 1996 Oct;271(4 Pt
2):H1666-96 [8897964](http://www.ncbi.nlm.nih.gov/pubmed/8897964) ,  
**Abstract:**   
We have developed a mathematical model of the rabbit atrial myocyte and have
used it in an examination of the ionic basis of the atrial action potential.
Available biophysical data have been incorporated into the model to quantify
the specific ultrastructural morphology, intracellular ion buffering, and
time- and voltage-dependent currents and transport mechanisms of the rabbit
atrial cell. When possible, mathematical expressions describing ionic currents
identified in rabbit atrium are based on whole cell voltage-clamp data from
enzymatically isolated rabbit atrial myocytes. This membrane model is coupled
to equations describing Na+, K+, and Ca2+ homeostasis, including the uptake
and release of Ca2+ by the sarcoplasmic reticulum and Ca2+ buffering. The
resulting formulation can accurately simulate the whole cell voltage-clamp
data on which it is based and provides fits to a family of rabbit atrial cell
action potentials obtained at 35 degrees C over a range of stimulus rates
(0.2-3.0 Hz). The model is utilized to provide a qualitative prediction of the
intracellular Ca2+ concentration transient during the action potential and to
illustrate the interactions between membrane currents that underlie
repolarization in the rabbit atrial myocyte.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Lindblad DS, Murphey CR, Clark JW, Giles WR.
(1996) - version=1.0**
](http://models.cellml.org/exposure/036dcdf013d736a376bf4d8f429bb804)  
The original CellML model was created by:  
**Penny Noble**   
penny.noble@dpag.ox.ac.uk  
The University of Oxford  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


