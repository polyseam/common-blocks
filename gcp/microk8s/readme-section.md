## gcp

This cluster will be deployed on
[Google Cloud Platform](https://cloud.google.com/gcp). When your cluster is
initialized the next step is to go to your domain registrar and create an `A`
record for ArgoCD which points to the loadbalancer that was created for your
cluster found on the
[GCP Load Balancers Page](https://console.cloud.google.com/net-services/loadbalancing)

## microk8s on google compute engine

You can visit the
[GCP Compute Engine Dashboard](https://console.cloud.google.com/compute/instances)
to see the status of the nodes that make up your cluster.
