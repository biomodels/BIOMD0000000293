# BIOMD0000000293: Proctor2010_UCHL1_ProteinAggregation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000293.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000293.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000293 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Modelling the Role of UCH-L1 on Protein Aggregation in Age-Related Neurodegeneration.**   
Proctor CJ, Tangeman PJ, Ardley HC. _PLoS One._ 2010 Oct 6;5(10):e13175
[20949132](http://www.ncbi.nlm.nih.gov/pubmed/20949132) ,  
**Abstract:**   
Overexpression of the de-ubiquitinating enzyme UCH-L1 leads to inclusion
formation in response to proteasome impairment. These inclusions contain
components of the ubiquitin-proteasome system and α-synuclein confirming that
the ubiquitin-proteasome system plays an important role in protein
aggregation. The processes involved are very complex and so we have chosen to
take a systems biology approach to examine the system whereby we combine
mathematical modelling with experiments in an iterative process. The
experiments show that cells are very heterogeneous with respect to inclusion
formation and so we use stochastic simulation. The model shows that the
variability is partly due to stochastic effects but also depends on protein
expression levels of UCH-L1 within cells. The model also indicates that the
aggregation process can start even before any proteasome inhibition is
present, but that proteasome inhibition greatly accelerates aggregation
progression. This leads to less efficient protein degradation and hence more
aggregation suggesting that there is a vicious cycle. However, proteasome
inhibition may not necessarily be the initiating event. Our combined modelling
and experimental approach show that stochastic effects play an important role
in the aggregation process and could explain the variability in the age of
disease onset. Furthermore, our model provides a valuable tool, as it can be
easily modified and extended to incorporate new experimental data, test
hypotheses and make testable predictions.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


