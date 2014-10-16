# MODEL1403250000: MODEL1403250000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1403250000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1403250000.git@20140916`

## Usage

Importing the model package.

`import MODEL1403250000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes

    
    
    This represents the reduced version of the "time course model" of Van Eunen et al (2013): Biochemical competition makes fatty-acid beta-oxidation vulnerable to substrate overload. The SBML was created from that of the original model and produces identical results when a time-course of 25 mins is run in COPASI


