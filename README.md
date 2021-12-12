# EX280 Red Hat Certified Specialist in OpenShift Administration Resources

## Manage OpenShift Container Platform

| Objectives | References |
| --- | --- |
| Use the command-line interface to manage and configure an OpenShift cluster |  |
| Use the web console to manage and configure an OpenShift cluster |  |
| Create and delete projects | [Working with projects](https://docs.openshift.com/container-platform/4.6/applications/projects/working-with-projects.html) |
| Import, export, and configure Kubernetes resources |  |
| Examine resources and cluster status | [Verifying node health](https://docs.openshift.com/container-platform/4.6/support/troubleshooting/verifying-node-health.html) |
| View logs |  |
| Monitor cluster events and alerts |  |
| Troubleshoot common cluster events and alerts |  |
| Use product documentation |  |

## Manage users and policies

| Objectives | References |
| --- | --- |
| Configure the HTPasswd identity provider for authentication | [Configuring an HTPasswd identity provider](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html/authentication_and_authorization/configuring-identity-providers#configuring-htpasswd-identity-provider) |
| Create and delete users | [Updating users for an HTPasswd identity provider](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html/authentication_and_authorization/configuring-identity-providers#identity-provider-htpasswd-update-users_configuring-htpasswd-identity-provider) |
| Modify user passwords |  |
| Modify user and group permissions | [RBAC overview](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#authorization-overview_using-rbac) |
| Create and manage groups |  |

## Control access to resources

| Objectives | References |
| --- | --- |
| Define role-based access controls | [RBAC overview](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#authorization-overview_using-rbac) |
| Apply permissions to users | [Adding roles to users](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#adding-roles_using-rbac)<br />[Local role binding commands](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#local-role-binding-commands_using-rbac)<br />[Cluster role binding commands](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#cluster-role-binding-commands_using-rbac)<br />[Creating a cluster admin](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#creating-cluster-admin_using-rbac)
| Create and apply secrets to manage sensitive information | (Providing sensitive data to pods)[https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/nodes/index#nodes-pods-secrets] |
| Create service accounts and apply permissions using security context constraints | [Creating service accounts](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#service-accounts-managing_using-service-accounts)<br />[About security context constraints](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/authentication_and_authorization/index#security-context-constraints-about_configuring-internal-oauth) |

## Configure networking components

| Objectives | References |
| --- | --- |
| Troubleshoot software defined networking | [Cluster Network Operator in OpenShift Container Platform](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/networking/index#cluster-network-operator) |
| Create and edit external routes | (Creating an HTTP-based route)[https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/networking/index#nw-creating-a-route_route-configuration]<br />[Kubernetes Ingress vs OpenShift Route — OpenShift Blog](https://cloud.redhat.com/blog/kubernetes-ingress-vs-openshift-route) |
| Control cluster network ingress | [Network policy](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/networking/index#network-policy)<br />[Network Policy Objects in Action — OpenShift Blog](https://cloud.redhat.com/blog/network-policy-objects-action) |
| Create a self signed certificate |  |
| Secure routes using TLS certificates | [Secured routes](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/networking/index#configuring-default-certificate) |

## Configure pod scheduling

| Objectives | References |
| --- | --- |
| Limit resource usage | [Resource quotas per project](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/applications/index#quotas-setting-per-project)<br />[Restrict resource consumption with limit ranges](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/nodes/index#nodes-cluster-limit-ranges) |
| Scale applications to meet increased demand | [Deployments — Scaling manually](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html/applications/deployments#deployments-scaling-manually_deployment-operations)<br />[Automatically scaling pods with the horizontal pod autoscaler](https://access.redhat.com/documentation/en-us/openshift_container_platform/4.6/html-single/nodes/index#nodes-pods-autoscaling) |

## Configure cluster scaling
| Objectives | References |
| --- | --- |
| Manually control the number of cluster workers |  |
| Automatically scale the number of cluster workers |  |

## Additional Resources

- [OpenShift Playground](https://www.katacoda.com/courses/openshift/playgrounds/openshift47)