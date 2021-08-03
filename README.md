# Synthetic Biased Data Generation

[Introducing a Family of Synthetic Datasets for Research on Bias in Machine Learning](https://arxiv.org/abs/2107.08928)

Author: William Blanzeisky, Pádraig Cunningham

This repository contains datasets and notebook used in our paper "Introducing a Family of Synthetic Datasets for Research on Bias in Machine Learning". The Ipython notebook allows user to set parameter to vary the level of bias by adjusting the threshold on the class label Y to distinguish between those likely to repay Y= 1 and those likely to default on their financial obligation Y= 0 (class imbalance), and on the sensitive feature Age to separate privileged Y= 1 and unprivileged group S= 0 (feature imbalance). In addition,  a Gaussian random noise can also be added to Score to increase classification complexity and is controlled by user-defined parameter. 

The notebook used to specify parameters for generating new datasets is in "GenerateData.ipynb"

## Abstract
A significant impediment to progress in research on bias in machine learning (ML) is the availability of relevant datasets. This situation is unlikely to change muchgiven the sensitivity of such data. For this reason there is a role for synthetic datain this research. In this short paper we present one such family of synthetic datasets.  We provide an overview of the data, describe how the level of bias can bevaried and present a simple example of an experiment on the data.
