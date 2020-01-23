+++
title = "Part 4: Distributed Training with Kubeflow on Amazon EKS"
date = 2019-10-21T13:21:28-07:00
weight = 5
chapter = true
#pre = "<b>2. </b>"
+++

# Part 4: Distributed Training with Kubeflow on Amazon EKS

In this section, we’ll run distributed training on Amazon Elastic Kubernetes Service (Amazon EKS). Amazon EKS makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS. To run deep learning workloads on Amazon EKS, we'll install Kubeflow. The Kubeflow project includes capabilities that make deployments of machine learning (ML) workflows on Kubernetes easy. With EKS and Kubeflow, you'll still need to manage the underlying CPU and GPU instances that form your cluster. EKS and Kubeflow make it easy to manage and schedule machine learning workloads on your cluster.