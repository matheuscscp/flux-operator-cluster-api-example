# flux-operator-cluster-api-example

Using ResourceSets to deploy clusters and things inside them
without sharing the Cluster API kubeconfig Secret with tenants.

## Required CLI tools

* `make`
* `kind`
* `helm`
* `kubectl`
* `clusterctl` (Needed only for generating/upgrading Cluster API manifests)

## Usage

`make help`
