# Hello World: Vault

Resources to get started with Hashicorp Vault on Red Hat OpenShift. Most resources can be applied to other Kubernetes distributions though some will require modifications to run outside of OpenShift.

## Initialize Vault

- vault-init
	- Deploy and initialize Vault on a Red Hat OpenShift cluster

## Configure Vault

- vault-in-cluster-config
	- Configure Vault for in-cluster Kubernetes authentication 
- vault-out-of-cluster-config
	- Configure Vault for out-of-cluster Kubernetes authentication
- vault-role-namespace-sync
	- Automatically create Vault roles for namespaces in a Kubernetes cluster 

## Sync Secrets to OpenShift

- external-secrets-operator-example
	- Example code to integrate Hashicorp Vault and OpenShift GitOps (Argo CD) to deploy secrets from Vault to an OpenShift cluster using External Secrets Operator.
- argocd-vault-plugin-example
	- Example code to integrate Hashicorp Vault and OpenShift GitOps (Argo CD) to deploy secrets from Vault to an OpenShift cluster using the argocd-vault-plugin. 
