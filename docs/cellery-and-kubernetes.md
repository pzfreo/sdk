# Cellery and Kubernetes

Cellery maps the concept of cells (from the [Cell Based Architecture](https://github.com/wso2/reference-architecture/blob/master/reference-architecture-cell-based.md)) into Kubernetes and Istio deployment approaches. Cellery CRDs and Controllers convert a cell image into a Kubenetes native deployment. The following diagram shows the mapping between a cell into Kubernetes building blocks. 

In the current deployment model, Components in the cell code become pods.

![Cellery K8S Arcitecture](https://github.com/lakwarus/sdk/blob/master/docs/images/cellery-k8s.png)
