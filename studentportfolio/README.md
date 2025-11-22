## Student Portfolio Website

## Author: Jaskomal Kaur

## Overview

This project is a student portfolio website used for Modules 3–6 of the DevOps course. It demonstrates rapid development, containerization, Kubernetes deployment, and GitOps automation.

## What I Learned

Module 3: Built and customized the portfolio website
Module 4: Created Dockerfile, built/pushed images
Module 5: Converted project to Kubernetes (Deployments & Services)
Module 6: Implemented CI/CD using GitHub Actions & Argo CD

## How the Application Works

* iThe website runs as a Docker container
* Kubernetes manifests in the k8s/ directory define deployments
* CI pipeline builds and pushes a new image on every commit
* CD pipeline (Argo CD) updates the cluster automatically

## Project Contents

* index.html – portfolio webpage
* Dockerfile – container build instructions
* k8s/ – Kubernetes deployment and service files