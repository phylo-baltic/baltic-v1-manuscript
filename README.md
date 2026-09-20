# baltic: the **B**ackronymed **A**daptable **L**ightweight **T**ree v**I**sualisation **C**ode

#### Barney I. Potter<sup>1</sup>, Karthik Gangavarapu<sup>2</sup>, Sidney M. Bell<sup>3</sup>, María Fernanda Torres Jimenez<sup>4</sup>, Gytis Dudas<sup>5</sup>

<sup>1</sup> Yale School of Public Health, Yale University, New Haven, Connecticut, USA, 
<sup>2</sup> Department of Translational Medicine, Scripps Research Institute, San Diego, California, USA, 
<sup>3</sup> Chan Zuckerberg Initiative, Redwood City, California, USA, 
<sup>4</sup> Department of Zoology, Institute of Biosciences, Life Sciences Center, Vilnius University, Vilnius, Lithuania, 
<sup>5</sup> Department of Eukaryotic Gene Engineering, Institute of Biotechnology, Life Sciences Center, Vilnius University, Vilnius, Lithuania


### Abstract

For ten years, baltic (Backronymed Adaptable Lightweight Tree vIsualization Code) has been used to make annotated phylogeny figures in molecular epidemiology, including during the West African Ebola epidemic, the Zika epidemic in the Americas, and the SARS-CoV-2 pandemic, as well as other fields. At its core, baltic is a Python library used for the efficient parsing, traversal, manipulation, and visualisation of phylogenetic trees. It is a small library with few dependencies that reads tree formats common in phylodynamic analyses and gives the user leverage to interact with a lightweight tree data structure to produce publication-ready figures with matplotlib. 

We present baltic 1.0, its first formally released and documented version. baltic reads and writes BEAST Nexus, Newick, and Nextstrain/Auspice JSON, and can process large BEAST posterior tree files in parallel to extract user-defined posterior statistics. The same objects are used for tree manipulation and for plotting in a single script. New to this release: a set of rooting methods (midpoint rooting, rerooting on any branch, and root-to-tip regression); support for reticulate evolution, with reassortment and recombination edges; and composite figures that combine a tree with other data, such as Müller plots, skygrid plots, tanglegrams, and plots connecting trees to maps. The release includes a documentation site with an API reference, tutorials, and a matplotlib-style gallery of worked examples.