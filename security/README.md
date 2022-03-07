### This page describes the supported authentication methods when connecting to the Kubernetes API server in Google Kubernetes Engine (GKE)

> There are several [methods for authenticating](https://kubernetes.io/docs/reference/access-authn-authz/authentication/) to a Kubernetes API server. 

> In GKE, `OAuth authentication` is recommended for cluster authentication and is automatically configured for you.


### Use Transport Layer Security (TLS) for all API traffic

> Kubernetes expects that all API communication in the cluster is encrypted by default with TLS, and the majority of installation methods will allow the necessary certificates to be created and distributed to the cluster components.

### API Authentication

> Choose an authentication mechanism for the API servers to use that matches the common access patterns when you install a cluster. For instance, small single user clusters may wish to use a simple certificate or static Bearer token approach. Larger clusters may wish to integrate an existing OIDC or LDAP server that allow users to be subdivided into groups.

> All API clients must be authenticated, even those that are part of the infrastructure like nodes, proxies, the scheduler, and volume plugins. These clients are typically `service accounts` or use `x509 client certificates`, and they are created automatically at cluster startup or are setup as part of the cluster installation.
