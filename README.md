# Kubernetes CLI Plugin - kubeplugin

## Description
This kubectl plugin shows CPU and Memory usage of Kubernetes resources.

## Usage

kubectl kubeplugin <resource> <namespace>

## Example

kubectl kubeplugin pods kube-system

## Output format

Resource, Namespace, Name, CPU, Memory

## Requirements

- kubectl
- metrics-server installed in cluster

## Installation

1. Copy script to PATH:
   sudo mv scripts/kubeplugin /usr/local/bin/

2. Make executable:
   chmod +x /usr/local/bin/kubeplugin

3. Run:
   kubectl kubeplugin pods kube-system
