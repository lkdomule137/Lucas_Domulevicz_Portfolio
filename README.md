# Lucas Domulevicz, Ph.D. Project Portfolio
I'm an Electrical Engineer and Physics professional with over 8 years of experience performing cutting edge research. Much of the work 
I have done involves leveraging methods in data science, machine learning, and deep neural networks to interpret complex data sets in the
fields of nano-electronics, nano-photonics, and chemical analysis. Below you'll find samples of some of the projects I've been involved in over the years 
in academia and for my own personal interests.

### Programming Languages and Software:
* Languages: Python, MATLAB, PostgreSQL, R, C, and LabView
* Packages: TensorFlow, scikit-learn, OpenCV, pandas, and Numpy
* Data Visualization and Illustration: Origin, Matplotlib, seaborn, MS PowerPoint, and GIMP

## [Project 1: Classification of Amino Acids with a Deep Neural Network](https://github.com/lkdomule137/neural_network_classification_of_amino_acids)
### Highlights:
* Utilized TensorFlow and scikit-learn in Python to build and optimize a deep neural network to classify 6 distinct amino acids based on 
spectroscopic and electrical data.
* Conducted exploratory data analysis in Python using Pandas, Matplotlib, and Seaborn to visual the data behavior in both the spectral 
and electrical domains.
* Performed feature engineering and constructed a data processing pipeline on an imbalanced data set containing ~1,000 features, to 
improve model performance.
* Extracted feature importance from a set of random forest binary classifiers, in R, for each species to assist in the interpretability of the data set.

*Raw data and neural network models can be found in the project repository. A Jupyter notebook containing a complete analysis is available upon request.*
![](/Images/neural_network_classification_of_amino_acids.PNG)


## [Project 2: Identifying Single-Molecule Spectroscopic Signals](https://github.com/lkdomule137/kmeans_clustering_of_spectroscopic_data)
### Overview: 
Raman spectroscopy is a tool that allows for the "fingerprinting" of molecular systems. Due to recent advances, it has become
one of the most useful tools for chemical analysis with the prospect of detecting signals from a single molecule. One prominent issue is
separating the signal originating from a single molecule from the background containing potentially trillions of molecules. This project
addresses this issue by utilizing unsupervised machine learning algorithms, namely K-means clustering, to separate these two signals and
explore differences in their representative spectral "fingerprint."  

### Highlights:
* Compiled electrical and spectral data from nearly 2 hours of times series measurements resulting in ~5,000 data points.
* Performed preprocessing (background adjustment, filtering, normalization) and feature extraction on data consisting of ~1,000 
features to prepare for modeling.
* Used K-means clustering to separate background signals from those originating from a single-molecule and identify distinguishing 
features between the clusters.
* Validated clustering model by constructing histograms of conductance data withheld from the model and comparing with 
independent data.
* Analysis was part of a high-impact peer-reviewed research paper and featured as the [**BACK COVER ARTICLE**](https://onlinelibrary.wiley.com/doi/10.1002/anie.202106779)

![](/Images/kmeans_project_overview_image.PNG)


## [Project 3: Simulating Electron Transmission and Current Flow in Molecular Wires](https://github.com/lkdomule137/molecular_wire_transmission_simulator)
### Overview: 
Molecules represent the fundamental limit of device scalability for nano electronics and understanding their conductive properties 
from a theoretical perspective is necessary for their successful implementation as viable commercial electronics. This project utilizes 
the output from commercial software for performing quantum mechanical simmulations of molecular systems to simulate electrical and thermal
properties of single-molecule electronic devices.

### Highlights:
* Software developed in MATLAB to parse output files from the Gaussian quantum chemistry software package and calculate properties of interest.
* Able to calculate transmission coefficient as a function of energy, conductance at zero bias voltage, as well as expected Seebeck coefficient.
* Calculations and results easily setup and managed through a simple GUI.

![](/Images/charge_transport_software_gui.PNG)

