# A System-Level Analysis of Conference Peer Review

This is the Python implementation of the analytical results and agent-based model (ABM) experiments of the paper under the same title which was accepted by ACM EC'22. 

## Guide of Usage
First, to run our codes, the required packages include NumPy, SciPy, Random and Matplotlib, pandas, seaborn are required for plotting. All of the experiments are implemented on JuPyter Notebook version 6.1.4. with Anaconda Navigator 1.10.0 and Python 3.8.5.

The roles of the Python files are:
* "**Learning DS Model from ICLR Datasets.ipynb**" uses the review datasets of ICLR 2020 and ICLR 2021 to estimate the prior of the paper quality of different categories and the confusion matrix;
* "**Continuous.ipynb**", "**Binary.ipynb**" and "**Categorical.ipynb**" contain the codes of the analysis and ABM experiments of the continuous mode, binary model and categorical model, respectively;
* "**Blackwell_MLR_threshold_policy-Counterexamples.ipynb**" contain the codes of finding the counterexamples which illustrate that Blackwell dominance plus informativenss when m=1 does not imply better QB-tradeoffs when m=2.

In "**Datasets**", we include the two ICLR datasets that we used. In "**Learned Model**", we save the learned models for usage so that users do not have to run "Learning DS Model from ICLR Datasets.ipynb". The "**Results**" folder saves some intermediate results that may takes hours to run. For those experiments, users could skip the codes that are used to generate these results.
