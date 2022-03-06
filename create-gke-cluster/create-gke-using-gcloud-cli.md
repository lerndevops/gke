## Create GKE Using Google Cloud CLI

### setup google cloud environment

1) Set the default project:
```
gcloud config set project [PROJECT_ID](https://support.google.com/cloud/answer/6158840)
```

2) Set the default zone:
```
gcloud config set compute/zone [COMPUTE_ZONE](https://cloud.google.com/compute/docs/regions-zones/regions-zones#available)
```
3) Set the default region:
```
gcloud config set compute/region [COMPUTE_REGION](https://cloud.google.com/compute/docs/regions-zones/regions-zones#available)
```

### Create a GKE cluster

```
### Standard Cluster
> gcloud container clusters create cluster-1 --num-nodes=1

### Get authentication credentials for the cluster
> gcloud container clusters get-credentials cluster-1
```
