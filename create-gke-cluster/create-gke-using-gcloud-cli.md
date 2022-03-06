## Create GKE Using Google Cloud CLI

### 1) setup google cloud environment

* Set the default project:
```
gcloud config set project [PROJECT_ID]
```
Replace [PROJECT_ID](https://support.google.com/cloud/answer/6158840) with your project ID

* Set the default zone:
```
gcloud config set compute/zone [COMPUTE_ZONE]
```
Replace [COMPUTE_ZONE](https://cloud.google.com/compute/docs/regions-zones/regions-zones#available) with your compute zone, such as us-west1-a.

* Set the default region:
```
gcloud config set compute/region [COMPUTE_REGION]
```
Replace [COMPUTE_REGION](https://cloud.google.com/compute/docs/regions-zones/regions-zones#available) with your compute region, such as us-west1.


### 2) Create a GKE cluster

```
### Standard Cluster
> gcloud container clusters create cluster-1 --num-nodes=1

### Get authentication credentials for the cluster
> gcloud container clusters get-credentials cluster-1
```
