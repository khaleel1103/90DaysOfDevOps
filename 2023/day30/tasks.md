
## Day 30 Task: Kubernetes Architecture

  

<p  align="center"><img  align="center"  src="https://kubernetes.io/images/kubernetes-horizontal-color.png"  /></p>

  

## Kubernetes Overview

With the widespread adoption of [containers](https://cloud.google.com/containers) among organizations, Kubernetes, the container-centric management software, has become a standard to deploy and operate containerized applications and is one of the most important parts of DevOps. 

Originally developed at Google and released as open-source in 2014. Kubernetes builds on 15 years of running Google's containerized workloads and the valuable contributions from the open-source community. Inspired by Google’s internal cluster management system, [Borg](https://research.google.com/pubs/pub43438.html), 


## Tasks

  

1. What is Kubernetes? Write in your own words and why do we call it k8s?

Ans: Kubernetes is an open source container orchestration engine for automating deployment, scaling, and management of containerized applications.
we call it k8s it abbreviation kas a starting alphabats and 8-represents the (ubernete) 8 in between alphabats of Kubernetes and s is the last alphabat of the Kubernetes so to call in sort it is k8s

2. What are the benefits of using k8s?

Ans: 1)It provides the high avaliability to the application.
2) Application stability and aavilabilty in a cloud environment.
3)Its a container orchestration Saving tool.
4)It increases the micro architecture efficiency.
5)we can deploy in multicloud environments.
6)Automate the deployment and scalablity.


3. Explain the architecture of Kubernetes, refer to [this video](https://youtu.be/FqfoDUhzyDo)

4. What is Control Plane?

Ans: Control Plane in k8s is the controller with the Different compounents. control plane manges the workernodes and pods in the k8s cluster. 

5. Write the difference between kubectl and kubelets.

Ans: Kuberctl is the command-line interface(CLI) through which we command to do the specfic operations.
Kubelets is the component present in the worker Nodes which interacts with the master component API Server with the create,updates,status and destroy of the containers in the kubernetes node.

6. Explain the role of the API server.

Ans: API Server ( application programming interface) its present in the master of the kubernetes cluster it determines request is valid and then processes it talks to the every components of the control plane checks the update of the nodes and pods accepts the request check the status forward to the manger schedular process it.

Kubernetes architecture is important, so make sure you spend a day understanding it. [This video](https://youtu.be/FqfoDUhzyDo) will surely help you.

  

*Happy Learning :)*