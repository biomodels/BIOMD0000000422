# BIOMD0000000422: Middleton2012_GibberellinSignalling

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000422.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000422.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000422 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Mathematical modeling elucidates the role of transcriptional feedback in gibberellin signaling.**   
Middleton AM , Úbeda-Tomás S , Griffiths J , Holman T , Hedden P , Thomas SG ,
Phillips AL , Holdsworth MJ , Bennett MJ , King JR, Owen MR _Proc. Natl. Acad.
Sci. U.S.A._ 2012 May; 109(19): 7571-6
[22523240](http://www.ncbi.nlm.nih.gov/pubmed/22523240) ,  
**Abstract:**   
The hormone gibberellin (GA) is a key regulator of plant growth. Many of the
components of the gibberellin signal transduction [e.g., GIBBERELLIN
INSENSITIVE DWARF 1 (GID1) and DELLA], biosynthesis [e.g., GA 20-oxidase
(GA20ox) and GA3ox], and deactivation pathways have been identified.
Gibberellin binds its receptor, GID1, to form a complex that mediates the
degradation of DELLA proteins. In this way, gibberellin relieves DELLA-
dependent growth repression. However, gibberellin regulates expression of
GID1, GA20ox, and GA3ox, and there is also evidence that it regulates DELLA
expression. In this paper, we use integrated mathematical modeling and
experiments to understand how these feedback loops interact to control
gibberellin signaling. Model simulations are in good agreement with in vitro
data on the signal transduction and biosynthesis pathways and in vivo data on
the expression levels of gibberellin-responsive genes. We find that GA-GID1
interactions are characterized by two timescales (because of a lid on GID1
that can open and close slowly relative to GA-GID1 binding and dissociation).
Furthermore, the model accurately predicts the response to exogenous
gibberellin after a number of chemical and genetic perturbations. Finally, we
investigate the role of the various feedback loops in gibberellin signaling.
We find that regulation of GA20ox transcription plays a significant role in
both modulating the level of endogenous gibberellin and generating overshoots
after the removal of exogenous gibberellin. Moreover, although the
contribution of other individual feedback loops seems relatively small, GID1
and DELLA transcriptional regulation acts synergistically with GA20ox
feedback.


