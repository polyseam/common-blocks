## azure

This cluster will be deployed on
[Microsoft Azure](https://azure.microsoft.com/en-ca/). When your cluster is
initialized the next step is to go to your domain registrar and create an `A`
record for [ArgoCD](https://argo-cd.readthedocs.io/en/stable/).

## microk8s azure virtual machines

Your `A` record should point to the single load balancer that was created for
your cluster found on the
[Azure Load Balancers Page](https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.Network%2FloadBalancers).

You can visit the
[Azure Portal](https://portal.azure.com/#view/HubsExtension/BrowseResource/resourceType/Microsoft.Compute%2FVirtualMachines)
to see the status of the nodes that make up your cluster.
