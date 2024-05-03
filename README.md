# kube-resource-analyzer

## Introduction

This repository contains the researchwork conducted for the internship project : Project 331: Optimizing Internal Apps Costs on Choreo through Optimized Resource allocations, and refers to the architecture email thread of the same name.

The project delves into an optmization for container sizes. This is achieved by rightsizing the containers by determining parameters such as cpu requests, memory requests, cpu limits and memory limits.

## Data Collection Notebook

The first notebook 1.Data Collection.ipynb has information on how to retrieve large result data sets from azure log analytics workspace and the queries neccessary to obtain this perf data.

## Recommendation Algorithm Notebook

The second notebook contains an implementation of the recommendation algorithm using the data collected from the first notebook.
