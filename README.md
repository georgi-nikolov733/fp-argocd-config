# Kubernetes configuration

Basic Kubernetes configuration using an image from Dockerhub for a GitOps deployment with ArgoCD.

To run ArgoCD locally you need the following prerequisites:

Install the [Kubernetes CLI](https://kubernetes.io/docs/tasks/tools/)

Set up [Minikube](https://minikube.sigs.k8s.io/docs/start/)

Install [ArgoCD](https://argo-cd.readthedocs.io/en/stable/getting_started/#1-install-argo-cd)

Download the [ArgoCD CLI](https://argo-cd.readthedocs.io/en/stable/getting_started/#2-download-argo-cd-cli)

After the initial setup we need to [access the Argo CD API server](https://argo-cd.readthedocs.io/en/stable/getting_started/#3-access-the-argo-cd-api-server)
in this case connecting to it using [Port Forwarding](https://argo-cd.readthedocs.io/en/stable/getting_started/#port-forwarding) and logging in using the [CLI](https://argo-cd.readthedocs.io/en/stable/getting_started/#4-login-using-the-cli). 

To grant access for ArgoCD to the GitHub repository a [deploy key](https://docs.github.com/en/developers/overview/managing-deploy-keys) is used.