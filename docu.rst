#this version is deprecated, but included to ascertain circumstances and part of the implementation approach
=============
Video 
============

Docker/Kubernetes

AWS Cost Management -> Budget alerts
IAM
1. Cloud9 Environment
    1. created Role: Cloud9_eksworkshop
	attached this role to Cloud9
   
2. EKS eksctl create CLuster
    -yaml myEKS_clustercreation.yaml for creating kubernetes CLuster
        including vpc (3 public and 3 private subnets)
        t3.small instances
        later updated with autoscaling group and so on

    -kubernetes dashboard
    -pods/nodes
    -ECR mywebping: pings a web url with head method every 3 seconds
    -some other demo apps of tutorial
    -RBAC
    -Prometheus
    -Grafana


3. CloudWatch Logging
    -ClusterLogging
	by enabling Logging options in EKS Cluster
    -Logging Container Insights		
	Cloud Watch Agent
	with Fluentd

   





