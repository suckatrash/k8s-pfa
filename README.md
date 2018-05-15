### Usage

#### Required for persistant volumes:

```
gcloud compute disks create --size 50GB pipelines-pfa-mysql --project YOUR_GCLOUD_PROJECT --zone YOUR_K8S_ZONE

gcloud compute disks create --size 50GB pipelines-pfa-artifacoty --project YOUR_GCLOUD_PROJECT --zone YOUR_K8S_ZONE
```

Put this in a kubernetes cluster by cloning the project and then running `kubectl create -R -f .` from the project directory.
