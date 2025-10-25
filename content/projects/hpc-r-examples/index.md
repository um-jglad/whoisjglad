---
title: "HPC Examples using R" 
date: 2025-07-15
url: "/projects/hpc-r-examples/"
tags: ["r", "hpc", "university of michigan", "great lakes", "armis2"]
author: ["Jacob Gladfelter"]
description: "A collection of examples demonstrating the use of R for high-performance computing tasks on the University of Michigan Great Lakes and Armis2 clusters." 
summary: "This project provides a variety of R scripts that illustrate best practices for leveraging HPC resources effectively."
cover:
    # image: "snippet.png"
    # alt: "Screen caputure of HPC Examples using R"
    # relative: true
editPost:
    URL: "https://github.com/umich-biostatistics/HPC-R-Examples"
    Text: "HPC R Examples"

---

---

## Summary

This repository provides example R and SLURM scripts demonstrating several methods for running bootstrap analyses on an HPC cluster. The examples range from basic single-core jobs to parallel and array-based workflows, including automated result combination.

---

## Example Job Types

| Job Type      | Definition                                                                                                    |
| ------------- | ------------------------------------------------------------------------------------------------------------- |
| simple        | A simple R and SLURM script that shows how to run your code on the cluster with no frills.                    |
| parallel      | How to run the same simple job, but use multiple cores to split up the work.                                  |
| array         | Split the simple job into a job array, spreading the work across multiple CPUs running in parallel            |
| csv | This example illustrates how to supply different parameters to each task in a SLURM job array by reading them from a CSV file.                                   |
| workflow      | Automate running the array and combine jobs in sequence, ensuring results are merged after all tasks complete |

---
