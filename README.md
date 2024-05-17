# kube-resource-analyzer

## Introduction

This repository contains the experimental scripts used to analyze kubernetes container workloads from azure kubernetes service and suggest appropriate request/limits for cpu and memory.

The project is focused on an optmization for container sizes. This is achieved by rightsizing the containers by determining parameters such as cpu requests, memory requests, cpu limits and memory limits.

## Data Collection Notebook

The first notebook `Data Collection.ipynb` has information on how to retrieve large result data sets from azure log analytics workspace and the KQL queries necessary to obtain this perf data.

## Recommendation Algorithm Notebook

The second notebook contains an implementation of the recommendation algorithm using the data collected from the first notebook.
