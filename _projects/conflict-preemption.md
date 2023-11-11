---
title: "Resource Usage - Predictive Scheduling"
layout: single-portfolio
excerpt: "<img src='/images/projects/real_time_log_analytics.png' alt=''>"
collection: projects
order_number: 10
toc: true
toc_label: "My Table of Contents"
# toc_icon: "cog"
header: 
  og_image: "projects/real_time_log_analytics.png"
---



## Project Overview

📌 The primary objective of this project is to establish a framework for real-time predictive analytics for the efficient provisioning of cloud resources. 

📌 This framework is intended to assist organizations in transitioning towards a machine learning-based approach for resource provisioning, usage tracking, with a focus on making real-time predictions, automating resource scheduling.

📌 This shift is essential due to the considerable manual effort currently required for setting resource limits  provisioning, as companies grapple with the challenge of balancing cost minimization ensuring system uptime  availability.

📌 I leveraged the Grid Workloads Archive dataset, which contains valuable performance metrics from virtual machines in a distributed datacenter managed by Bitbrains. I worked on the development of a predictive model designed to offer more intelligent resource usage forecasts. This process involved a multifaceted approach, including time-series analysis, advanced regression techniques,  time series with cross-validation to characterize resource usage patterns and identify key predictive features.

📌 I harnessed the power of DeepAR on the AWS platform to enable real-time analytics, enhancing the capabilities of this framework.

<!-- > A brief aside on Git-speak: these periodic indented blocks will explain the terminology that Git uses to help you underst what each Git comm actually does.


To save yourself some time  do this faster, simply press <kbd>Ctrl</kbd>+<kbd>c</kbd>.[^2] -->

![](/images/posts/creating-website/p1_i1.png)

## Problem: Over provisioning

![](/images/posts/creating-website/p1_i2.png)

Conclusion: The average CPU usage is only about 7% of what was being provisioned

## Solution: Predictive Scheduling and provisioning of resources

![](/images/posts/creating-website/p1_i3.png)

Machine Learning Algorithm to predict in advance, the resource required to ensure smooth functioning.

[Link to project on Github](https://github.com/Gauthami25/Predictive-Forecasting/tree/main)



