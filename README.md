# Bioinformatics-and-R

This notebook takes a practical approach to R to derive biological understanding from large amounts of data. Most biologists can analyze their data using Microsoft Excel or more sophisticated tools such as SPSS but with the increasing usage of large sequencing datasets and computational tools to analyze genomic's data it is necessary to ensure that these automated methods are still as reproducible and robust as any other experimental approaches. For example after running a RNA-seq there are 10,000's of genes and the level of expression has to be measured across a dozens of samples. Typical questions are:
Which genes are differentially expressed over dozen of samples between control tests environment and treatment?
How can we normalize the RNA-seq counts between samples?
What is the correct model of statistical error to describe the distribution of counted data across samples?
We measure thousands of genes on a only a few dozen samples, how can we perform statistical tests to extract relevant information on a relatively small experimental design? ... My intern research lab experience at both UCSB Reese lab, Neuroscience Research Institute and undergraduate UC Berkeley Coates Lab, Energy Bioscience Institute have taught me couple of facts:
bioinformaticians have to rerun an analysis more than once with eventually new or changed data.
team members be they bioinformaticians collaborators, advisor or software engineers will need to look into your project and understand it. Hence documentint the project in a non cryptic way is essential. It is like keeping a detailed lab notebook.
Reuse of existing software libraries. writing your own code is always exciting but code quality and speed is the essence here. R, Python have open source libraries that have been tested with a wider audience and consequently have less bugs.
For all the above reasons this project will use jupyter notebook as an authoring tool.Jupyter was designed to enable sharing of notebooks with other people. The idea is that you can write some code, mix some text with the code, and publish this as a notebook. In the notebook they can see the code as well as the actual results of running the code.

Why R and not Python? I am coming into this jupyter notebook with both a biosciences and pyschology coursework background and practical research lab experiences. Most labs have gained tremendous experimental reproducible research discipline using tools such as SPSS, Excel (yes) and it is only lately that with the increase in big datasets from both high throughput data sequencing and social media big data that the need for more computer sciences engineering driven tools such as Python and R are becoming a necessity.
In this first phase of this project R extensive statistical libraries and documentation is the best tool to have bioinformaticians work with software engineers as a team. In the second phase, as we move into larger data sets and more intensive compute based on machine learning we will use a combination of R and Python.

From a bioinformatics standpoint though the main goal is add collaboration and sharing capabilities such as adding discussions and saved them in the project itself, being able to access and build upon other bioinformatics project. The utlimate end game is to be able to have new team members ramp up faster via collaboration and sharing capabilities.

As in many of my personal previous experience learning by doing practical small projects was the best way for me to learn hence I will be applying the same principles here.
We will start familiarizing ourselves with R basic scripts by exploring classical internal R data sets such as the Iris and the Body Fat dataset and move the Bioconductor.org datasets
