# OpenShift (Hashicorp) Vault Integration

Resources to get started with Hashicorp Vault on Red Hat OpenShift. Most resources can be applied to other Kubernetes distributions though some will require modifications to run outside of OpenShift.

## Repositories

### Initialize Vault

- [vault-init]
	- Deploy and initialize Vault on a Red Hat OpenShift cluster

### Configure Vault

- [vault-in-cluster-config]
	- Configure Vault for in-cluster Kubernetes authentication
- <s>vault-out-of-cluster-config</s>
	- Configure Vault for out-of-cluster Kubernetes authentication
- [vault-role-namespace-sync]
	- Automatically create Vault roles for namespaces in a Kubernetes cluster

### Sync Secrets to OpenShift

- [external-secrets-custom-ca]
	- Use External Secrets Operator against a secret store using a TLS certificate signed by a custom certificate authority (CA)
- [external-secrets-operator-example]
	- Example code to integrate Hashicorp Vault and OpenShift GitOps (Argo CD) to deploy secrets from Vault to an OpenShift cluster using External Secrets Operator.
- [argocd-vault-plugin-example]
	- Example code to integrate Hashicorp Vault and OpenShift GitOps (Argo CD) to deploy secrets from Vault to an OpenShift cluster using the argocd-vault-plugin.

[argocd-vault-plugin-example]: https://github.com/hello-openshift-vault/argo-vault-plugin-example
[external-secrets-custom-ca]: https://github.com/hello-openshift-vault/external-secrets-custom-ca
[external-secrets-operator-example]: https://github.com/hello-openshift-vault/external-secrets-operator-example
[vault-in-cluster-config]: https://github.com/hello-openshift-vault/vault-in-cluster-config
[vault-init]: https://github.com/hello-openshift-vault/vault-init
[vault-role-namespace-sync]: https://github.com/hello-openshift-vault/vault-role-namespace-sync
