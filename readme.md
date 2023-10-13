# Helm Chart Installation and Configuration Guide

This guide will walk you through the installation and configuration of the Helm chart for deploying the "meu-nginx" application. The Helm chart contains default values, and we will demonstrate how to customize these values during installation. Please ensure that you have [Helm](https://helm.sh/docs/intro/install/) and [Kubernetes](https://kubernetes.io/docs/setup/) configured in your environment before proceeding.

## Prerequisites

- [Helm](https://helm.sh/docs/intro/install/)
- [Kubernetes](https://kubernetes.io/docs/setup/)

## Step 1: Add Helm Repository

If you haven't already, add the Helm repository containing the "meu-nginx" chart to your Helm client:

```bash
helm repo add meu-nginx https://charts.example.com/meu-nginx
