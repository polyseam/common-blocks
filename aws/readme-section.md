## aws

This cluster will be deployed on [Amazon Web Services](https://aws.com). When
your cluster is initialized the next step is to go to your domain registrar and
create an CNAME record for ArgoCD. Both entries should point to the single load
balancer that was created for your cluster found on the
[AWS Load Balancers Page](https://console.aws.amazon.com/ec2/v2/home?#LoadBalancers).

You can visit the
[AWS EC2 Dashboard](https://console.aws.amazon.com/ec2/home?#Instances:instanceState=running;v=3)
to see the status of the nodes that make up your cluster.

## a different header

Is above