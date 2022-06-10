{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# A System-Level Analysis of Conference Peer Review\n",
    "\n",
    "This is the Python implementation of the analytical results and agent-based model (ABM) experiments of the paper under the same title which was accepted by ACM EC'22. \n",
    "\n",
    "## Guide of Usage\n",
    "First, to run our codes, the required packages include NumPy, SciPy, Random and Matplotlib, pandas, seaborn are required for plotting. All of the experiments are implemented on JuPyter Notebook version 6.1.4. with Anaconda Navigator 1.10.0 and Python 3.8.5.\n",
    "\n",
    "The role of the Python files are:\n",
    "* \"**Learning DS Model from ICLR Datasets.ipynb**\" uses the review datasets of ICLR 2020 and ICLR 2021 to estimate the prior of the paper quality of different categories and the confusion matrix;\n",
    "* \"**Continuous.ipynb**\", \"**Binary.ipynb**\" and \"**Categorical.ipynb**\" contain the codes of the analysis and ABM experiments of the continuous mode, binary model and categorical model, respectively;\n",
    "\n",
    "In \"**Datasets**\", we include the two ICLR datasets that we used. In \"**Learned Model**\", we save the learned models for usage so that users do not have to run \"Learning DS Model from ICLR Datasets.ipynb\". The \"**Results**\" folder saves some intermediate results that may takes hours to run. For those experiments, users could skip the codes that are used to generate these results."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
