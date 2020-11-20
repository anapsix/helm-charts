[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/anapsix)](https://artifacthub.io/packages/search?repo=anapsix)

## Adding Repo

To add repo to Helm use the following command
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
