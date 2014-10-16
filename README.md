# BIOMD0000000189: BIOMD0000000189

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000189.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000189.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000189 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Proctor2008 - p53/Mdm2 circuit - p53 stabilisation by p14ARF

This model is described in the article:

[Explaining oscillations and variability in the p53-Mdm2
system.](http://identifiers.org/pubmed/18706112)

Proctor CJ, Gray DA.

BMC Syst Biol 2008; 2: 75

Abstract:

BACKGROUND: In individual living cells p53 has been found to be expressed in a
series of discrete pulses after DNA damage. Its negative regulator Mdm2 also
demonstrates oscillatory behaviour. Attempts have been made recently to
explain this behaviour by mathematical models but these have not addressed
explicit molecular mechanisms. We describe two stochastic mechanistic models
of the p53/Mdm2 circuit and show that sustained oscillations result directly
from the key biological features, without assuming complicated mathematical
functions or requiring more than one feedback loop. Each model examines a
different mechanism for providing a negative feedback loop which results in
p53 activation after DNA damage. The first model (ARF model) looks at the
mechanism of p14ARF which sequesters Mdm2 and leads to stabilisation of p53.
The second model (ATM model) examines the mechanism of ATM activation which
leads to phosphorylation of both p53 and Mdm2 and increased degradation of
Mdm2, which again results in p53 stabilisation. The models can readily be
modified as further information becomes available, and linked to other models
of cellular ageing. RESULTS: The ARF model is robust to changes in its
parameters and predicts undamped oscillations after DNA damage so long as the
signal persists. It also predicts that if there is a gradual accumulation of
DNA damage, such as may occur in ageing, oscillations break out once a
threshold level of damage is acquired. The ATM model requires an additional
step for p53 synthesis for sustained oscillations to develop. The ATM model
shows much more variability in the oscillatory behaviour and this variability
is observed over a wide range of parameter values. This may account for the
large variability seen in the experimental data which so far has examined ARF
negative cells. CONCLUSION: The models predict more regular oscillations if
ARF is present and suggest the need for further experiments in ARF positive
cells to test these predictions. Our work illustrates the importance of
systems biology approaches to understanding the complex role of p53 in both
ageing and cancer.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000188](http://identifiers.org/biomodels.db/BIOMD0000000188).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


