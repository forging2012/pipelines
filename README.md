[![Build Status](https://travis-ci.com/kubeflow/pipelines.svg?token=JjfzFsYGxZwkHvXFCpwt&branch=master)](https://travis-ci.com/kubeflow/pipelines)
[![Coverage Status](https://coveralls.io/repos/github/kubeflow/pipelines/badge.svg)](https://coveralls.io/github/kubeflow/pipelines?branch=yebrahim%2Fcoveralls)

## Overview of the Kubeflow pipelines service

[Kubeflow](https://www.kubeflow.org/) is a machine learning (ML) toolkit that is dedicated to making deployments of ML workflows on Kubernetes simple, portable, and scalable. 

**Kubeflow pipelines** are reusable end-to-end ML workflows built using the Kubeflow Pipelines SDK.

The Kubeflow pipelines service has the following goals:

* End to end orchestration: enabling and simplifying the orchestration of end to end machine learning pipelines
* Easy experimentation: making it easy for you to try numerous ideas and techniques, and manage your various trials/experiments.
* Easy re-use: enabling you to re-use components and pipelines to quickly cobble together end to end solutions, without having to re-build each time.

## Documentation

Get started with your first pipeline and read further information in the [documentation](https://github.com/kubeflow/pipelines/wiki).

## Acknowledgments

Kubeflow pipelines uses [Argo](https://github.com/argoproj/argo) under the hood to orchestrate Kubernetes resources. The Argo community has been very supportive and we are very grateful.
