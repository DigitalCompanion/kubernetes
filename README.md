Proposal setup for a modern dev environment using infrastructure as code (IaC)

Kubernetes development baseline platform
Propose to use a professional baseline for Kubernetes  https://github.com/bitnami/kube-prod-runtime
The Bitnami Kubernetes Production Runtime (BKPR) is a collection of services that makes it easy to run production workloads in Kubernetes.
BKPR comes with OAuth2 Proxy: A reverse proxy and static file server that provides authentication using Providers (Google, GitHub, and others) to validate accounts by email, domain or group.
Bitnami is well recognized and have plenty of well maintained helms ready to use on https://github.com/bitnami/charts which helps keeping focus on development.

Guiding principle:
Tech platform agnostic as far as possible. Kubernetes is the standard.

Can be used on

Google Kubernetes Engine (GKE)
Azure Kubernetes Service (AKS)
Amazon Elastic Container Service for Kubernetes (Amazon EKS)
On premise.


CI/CD pipeline is available for multiple established code languages and tools for linting, testing.

Supports local registry for docker, code and everything needed for a full offline development environment.
Evaluating https://jenkins-x.io/
Presentation: https://www.youtube.com/watch?v=BF3MhFjvBTU
(Jenkins X: Continuous Delivery for Kubernetes with James Strachan)
