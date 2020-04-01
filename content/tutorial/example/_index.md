---
# Course title, summary, and position.
linktitle: An Example Course
summary: Learn how to use Academic's docs layout for publishing online courses, software documentation, and tutorials.
weight: 1

# Page metadata.
title: Overview
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: Overview
    weight: 1
---

## Overview

This document provides a guide for the policy evaluation project. This project asks you to us the [Correlates of State Policy](http://ippsr.msu.edu/public-policy/correlates-state-policy) data available from the Institute for Public Policy and Social Research College of Social Science.  

You will develop a project using this data set and write a 10 page (double-spaced, 12 point font, printed and stapled) memo that shows the knowledge you gained from this class. To do this project, you will need to first download the codebook describing the data, and then develop a research question that you will be able to answer using the data. You will do the analysis using both regression and difference-in-differences and compare the results. The memo will have four sections: 1) the problem and the policy intervention that the study substantively focuses on; 2) the methods you use to evaluate the impact of the intervention; 3) the findings of your analysis; and 4) a discussion of the importance of the evaluation. The memo must include a minimum of five cites to academic research to justify your hypothesis (you can cite blogs, websites and newspapers but these will not count toward the academic cites).

This document will walk you though the steps required to conduct a policy evaluation project. In general, every project involves the following steps:

1. Obtain policy data and familiarize yourself with the variables, how they are measured, and their availability
2. Read the data into your statistical software and prepare it for analysis
3. Explore the data but plotting variables of interest and calculate summary statistics
4. Develop your statistical model and analyse your data
5. Explain your findings


# Workflow

As a data analyst, it is absolutely essential that you keep detailed documentation of your analysis process. This means saving all of the code that you use for a project somewhere convenient so that you or anyone else can quickly and easily exactly reproduce your original results. In addition to saving your code, you should also provide explanations for your procedures and code so that you will always remember your data sources, what each line of code is doing, and why you analysed the data the way that you did. Not only will this help you remember the details about your project, but it will also make it easy for others to read through your code and validate your methodology. Practically, your code should be saved in a script file, though I strongly recommend using Rmarkdown since it allows you to create complete documents and execute code at the same time, exactly like this guide!

To create an Rmarkdown document go to file -> New File -> R notebook:
