[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/anapsix)](https://artifacthub.io/packages/search?repo=anapsix)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:
```shell
helm repo add anapsix https://charts.random.io
```

## Listing available Charts

### Helm 3.x
```shell
helm search repo -l anapsix
```

### Helm 2.x
```shell
helm search -l -r anapsix/
```
