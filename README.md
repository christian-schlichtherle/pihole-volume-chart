# Pi-hole Volume Chart

This is a Helm chart for deploying the [Pi-hole](https://pi-hole.net) volume to a Kubernetes cluster.

## How to configure

Check the file `values.yaml`.
Consider this file being read-only and put your customizations into a file named `custom.yaml` instead, so that you
don't get merge conflicts when you pull the changes from this repository.
The files are merged before deployment so that `custom.yaml` gains priority over `values.yaml`.

## Synopsis

### Installation

    make [up] 

### Uninstallation

    make down
