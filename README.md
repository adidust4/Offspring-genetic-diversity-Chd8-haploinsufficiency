# Offspring genetic diversity regulates rearing experiences that predict differential susceptibility to Chd8 haploinsufficiency
**Authors**: Manal Tabbaa<sup>1,2*</sup>, Alexis Gamez<sup>1</sup>, A'di Dust<sup>3^</sup>, Maja Matarić<sup>3</sup>, Pat Levitt<sup>1,2</sup>

<sup>1</sup>Division of Neurology, Department of Pediatrics and Developmental Neuroscience and Neurogenetics Program, Children's Hospital of Los Angeles, The Saban Research Institute, Los Angeles, CA 90033, USA

<sup>2</sup> Keck School of Medicine of the University of Southern California, Los Angeles, CA 90033, USA

<sup>3</sup> Department of Computer Science, University of Southern California, Los Angeles, CA 90027, USA

<sup>*</sup> Lead Contact: mtabbaa@chla.usc

<sup>^</sup> Coding Contact: dust@usc.edu

## Project Abstract
Mouse models of human disease are often used to isolate the direct effects of genetic mutations on phenotypes related to clinical presentations. Loss of function mutations in the autism-associated CHD8 gene are highly penetrant for trait and behavioral abnormalities in children, but there is substantial clinical heterogeneity in the occurrence and extent of disruptions between individuals. Using a large genetic reference panel of mice, we recently showed that this heterogeneity is, in part, regulated by genetic background. Here, we hypothesized that genetic background may also influence early life experiences, further shaping individual susceptibility to neurodevelopmental disorders. To test this, we systematically observed the rearing environment by tracking the behavior of genetically diverse offspring raised by genetically identical dams. Biostatistical and machine learning analyses of the data reveal robust strain-dependent differences in both pup and maternal behaviors, which significantly predict sex-specific alterations in body and brain weights as well as social, anxiety-like, and cognitive trait disruptions due to Chd8 haploinsufficiency after weaning. These results suggest that phenotypic variability in disease models arises from an interaction between inherited mutations and genetically influenced early-life environments. This work highlights the value of incorporating genetic diversity into model systems to better understand the origins of heterogeneity in neurodevelopmental disorders.

## Code

### Background

This respository provides the code that produces SHAP (SHapley Additive exPlanations) dendrograms used in the journal article.

### File Descriptions

`data_visualization.ipynb`: Jupyter Notebook file that provides all necessary code to produce the graphs. Run this in order to reproduce the graphs.

`chd8_het_effects.xlsx`: Excel file containing mouse data.

`Images/`: A folder containing dendorgrams produced by the data visualization code.

### Requirements

Install the following in order to run the code (package installation pages linked):

- [pandas](https://pandas.pydata.org/docs/getting_started/install.html)
- [numpy](https://numpy.org/install/)
- [shap](https://shap.readthedocs.io/en/latest/)
- [scikit-learn](https://scikit-learn.org/stable/install.html)
- [matplotlib](https://matplotlib.org/stable/install/index.html)

## How to Cite

