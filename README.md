# OpenShift (openshift)

A comprehensive API definition for Red Hat OpenShift, the enterprise Kubernetes platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CI/CD
- Cloud Native
- Containers
- DevOps
- Enterprise
- Kubernetes
- PaaS

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### OpenShift REST API

Main REST API for managing OpenShift clusters, projects, and resources.

- **Human URL:** [https://docs.openshift.com/](https://docs.openshift.com/)
- **Base URL:** `https://api.openshift.com`

#### Tags

- Cloud
- Containers
- Kubernetes
- Platform

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/rest_api/index.html)
- [OpenAPI](https://api.openshift.com/api/swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.openshift.com/container-platform/latest/authentication/index.html)
- [Pricing](https://www.redhat.com/en/technologies/cloud-computing/openshift/pricing)
- [Support](https://access.redhat.com/support)
- [Status Page](https://status.openshift.com/)
- [SDK](https://github.com/openshift/client-go)
- [Rate Limits](https://docs.openshift.com/container-platform/latest/rest_api/understanding-api-support-tiers.html)
- [Getting Started](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/index)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift OAuth API

OAuth authentication and authorization API for OpenShift.

- **Human URL:** [https://docs.openshift.com/container-platform/latest/authentication/understanding-authentication.html](https://docs.openshift.com/container-platform/latest/authentication/understanding-authentication.html)
- **Base URL:** `https://oauth-openshift.apps.openshift.com`

#### Tags

- Authentication
- OAuth
- Security

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/authentication/understanding-authentication.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Routes API

API for managing application routes and ingress.

- **Human URL:** [https://docs.openshift.com/container-platform/latest/networking/routes/route-configuration.html](https://docs.openshift.com/container-platform/latest/networking/routes/route-configuration.html)
- **Base URL:** `https://api.openshift.com/apis/route.openshift.io/v1`

#### Tags

- Ingress
- Networking
- Routing

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/networking/routes/route-configuration.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Build API

API for managing application builds and build configurations.

- **Human URL:** [https://docs.openshift.com/container-platform/latest/cicd/builds/understanding-builds.html](https://docs.openshift.com/container-platform/latest/cicd/builds/understanding-builds.html)
- **Base URL:** `https://api.openshift.com/apis/build.openshift.io/v1`

#### Tags

- Builds
- CI/CD
- Source-To-Image

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/cicd/builds/understanding-builds.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Image API

API for managing container images and image streams.

- **Human URL:** [https://docs.openshift.com/container-platform/latest/openshift_images/index.html](https://docs.openshift.com/container-platform/latest/openshift_images/index.html)
- **Base URL:** `https://api.openshift.com/apis/image.openshift.io/v1`

#### Tags

- Containers
- Images
- Registry

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/openshift_images/index.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Project API

API for managing OpenShift projects (namespace extensions).

- **Human URL:** [https://docs.openshift.com/container-platform/latest/applications/projects/working-with-projects.html](https://docs.openshift.com/container-platform/latest/applications/projects/working-with-projects.html)
- **Base URL:** `https://api.openshift.com/apis/project.openshift.io/v1`

#### Tags

- Multi-Tenancy
- Namespaces
- Projects

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/applications/projects/working-with-projects.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Workloads API

API for managing workload resources including Pods, Deployments, DeploymentConfigs, StatefulSets, Jobs, CronJobs, ReplicaSets, and DaemonSets.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/workloads_apis/workloads-apis](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/workloads_apis/workloads-apis)
- **Base URL:** `https://api.openshift.com/apis/apps/v1`

#### Tags

- Deployments
- Jobs
- Pods
- StatefulSets
- Workloads

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/workloads_apis/workloads-apis)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Network API

API for managing network configuration including Services, Endpoints, Ingress, NetworkPolicy, and EgressFirewall resources.

- **Human URL:** [https://docs.openshift.com/container-platform/4.17/rest_api/network_apis/network-apis-index.html](https://docs.openshift.com/container-platform/4.17/rest_api/network_apis/network-apis-index.html)
- **Base URL:** `https://api.openshift.com/apis/network.openshift.io/v1`

#### Tags

- Ingress
- Networking
- NetworkPolicy

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.17/rest_api/network_apis/network-apis-index.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Storage API

API for managing storage resources including PersistentVolumes, PersistentVolumeClaims, StorageClasses, CSI drivers, and VolumeSnapshots.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/storage_apis/persistentvolume-v1](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/storage_apis/persistentvolume-v1)
- **Base URL:** `https://api.openshift.com/api/v1`

#### Tags

- CSI
- PersistentVolumes
- Storage
- StorageClasses

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/storage_apis/persistentvolume-v1)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Authorization API

API for managing authorization resources including SubjectAccessReview, SelfSubjectAccessReview, LocalSubjectAccessReview, and TokenReview.

- **Human URL:** [https://docs.openshift.com/container-platform/4.17/rest_api/authorization_apis/selfsubjectreview-authentication-k8s-io-v1.html](https://docs.openshift.com/container-platform/4.17/rest_api/authorization_apis/selfsubjectreview-authentication-k8s-io-v1.html)
- **Base URL:** `https://api.openshift.com/apis/authorization.k8s.io/v1`

#### Tags

- Access Control
- Authorization
- Security

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.17/rest_api/authorization_apis/selfsubjectreview-authentication-k8s-io-v1.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Autoscale API

API for managing autoscaling resources including HorizontalPodAutoscaler, ClusterAutoscaler, and MachineAutoscaler.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/autoscale_apis/horizontalpodautoscaler-autoscaling-v2](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/autoscale_apis/horizontalpodautoscaler-autoscaling-v2)
- **Base URL:** `https://api.openshift.com/apis/autoscaling/v2`

#### Tags

- Autoscaling
- ClusterAutoscaler
- HPA

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/autoscale_apis/horizontalpodautoscaler-autoscaling-v2)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Config API

API for managing cluster configuration resources including APIServer, Authentication, Infrastructure, Ingress, Network, OAuth, and Scheduler configuration.

- **Human URL:** [https://docs.openshift.com/container-platform/4.17/rest_api/config_apis/infrastructure-config-openshift-io-v1.html](https://docs.openshift.com/container-platform/4.17/rest_api/config_apis/infrastructure-config-openshift-io-v1.html)
- **Base URL:** `https://api.openshift.com/apis/config.openshift.io/v1`

#### Tags

- Cluster Settings
- Configuration
- Infrastructure

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.17/rest_api/config_apis/infrastructure-config-openshift-io-v1.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Console API

API for managing OpenShift web console extensions including ConsoleCLIDownload, ConsoleExternalLogLink, ConsoleLink, ConsoleNotification, and ConsolePlugin.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/console_apis/index](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/console_apis/index)
- **Base URL:** `https://api.openshift.com/apis/console.openshift.io/v1`

#### Tags

- Console
- Extensions
- Plugins
- Web UI

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/console_apis/index)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Cluster API

API for managing cluster-level resources including ClusterVersion, ClusterOperator, and infrastructure resources.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/cluster_apis/cluster-apis](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/cluster_apis/cluster-apis)
- **Base URL:** `https://api.openshift.com/apis/config.openshift.io/v1`

#### Tags

- Cluster
- ClusterVersion
- Infrastructure

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/cluster_apis/cluster-apis)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Machine API

API for managing machine resources including Machine, MachineSet, MachineHealthCheck, and MachineAutoscaler for cluster node lifecycle management.

- **Human URL:** [https://docs.openshift.com/container-platform/4.9/rest_api/machine_apis/machineconfig-machineconfiguration-openshift-io-v1.html](https://docs.openshift.com/container-platform/4.9/rest_api/machine_apis/machineconfig-machineconfiguration-openshift-io-v1.html)
- **Base URL:** `https://api.openshift.com/apis/machine.openshift.io/v1beta1`

#### Tags

- Autoscaling
- Infrastructure
- Machines
- Nodes

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.9/rest_api/machine_apis/machineconfig-machineconfiguration-openshift-io-v1.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Operator API

API for managing OpenShift operator lifecycle and configuration including Etcd, Console, Network, DNS, IngressController, and other operator resources.

- **Human URL:** [https://docs.openshift.com/container-platform/4.8/rest_api/operator_apis/operator-apis-index.html](https://docs.openshift.com/container-platform/4.8/rest_api/operator_apis/operator-apis-index.html)
- **Base URL:** `https://api.openshift.com/apis/operator.openshift.io/v1`

#### Tags

- Cluster Services
- Lifecycle Management
- Operators

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.8/rest_api/operator_apis/operator-apis-index.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift OperatorHub API

API for managing OperatorHub resources including CatalogSources, Subscriptions, InstallPlans, and ClusterServiceVersions for the Operator Lifecycle Manager.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/operators/index](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/operators/index)
- **Base URL:** `https://api.openshift.com/apis/operators.coreos.com/v1alpha1`

#### Tags

- Catalog
- OLM
- OperatorHub
- Subscriptions

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html-single/operators/index)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Template API

API for managing templates that provide parameterized sets of objects for creating applications and services.

- **Human URL:** [https://docs.openshift.com/container-platform/4.17/rest_api/template_apis/template-template-openshift-io-v1.html](https://docs.openshift.com/container-platform/4.17/rest_api/template_apis/template-template-openshift-io-v1.html)
- **Base URL:** `https://api.openshift.com/apis/template.openshift.io/v1`

#### Tags

- Application Deployment
- Parameterization
- Templates

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.17/rest_api/template_apis/template-template-openshift-io-v1.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Security API

API for managing security resources including SecurityContextConstraints, RangeAllocation, and PodSecurityPolicyReview for controlling pod security.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/authentication_and_authorization/managing-pod-security-policies](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/authentication_and_authorization/managing-pod-security-policies)
- **Base URL:** `https://api.openshift.com/apis/security.openshift.io/v1`

#### Tags

- Access Control
- Pod Security
- SCC
- Security

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/authentication_and_authorization/managing-pod-security-policies)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift RBAC API

API for managing role-based access control resources including Roles, ClusterRoles, RoleBindings, and ClusterRoleBindings.

- **Human URL:** [https://docs.openshift.com/container-platform/4.8/authentication/using-rbac.html](https://docs.openshift.com/container-platform/4.8/authentication/using-rbac.html)
- **Base URL:** `https://api.openshift.com/apis/rbac.authorization.k8s.io/v1`

#### Tags

- Access Control
- Authorization
- RBAC
- Roles

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.8/authentication/using-rbac.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Node API

API for managing node-level resources including Node, RuntimeClass, and node configuration.

- **Human URL:** [https://docs.openshift.com/container-platform/4.17/rest_api/node_apis/node-apis-index.html](https://docs.openshift.com/container-platform/4.17/rest_api/node_apis/node-apis-index.html)
- **Base URL:** `https://api.openshift.com/api/v1`

#### Tags

- Infrastructure
- Nodes
- Runtime

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.17/rest_api/node_apis/node-apis-index.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Monitoring API

API for managing monitoring and observability resources including Prometheus, Alertmanager, ServiceMonitor, and PrometheusRule.

- **Human URL:** [https://docs.openshift.com/container-platform/4.17/observability/monitoring/accessing-third-party-monitoring-apis.html](https://docs.openshift.com/container-platform/4.17/observability/monitoring/accessing-third-party-monitoring-apis.html)
- **Base URL:** `https://api.openshift.com/apis/monitoring.coreos.com/v1`

#### Tags

- Alerting
- Monitoring
- Observability
- Prometheus

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.17/observability/monitoring/accessing-third-party-monitoring-apis.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Provisioning API

API for managing bare metal and infrastructure provisioning resources including BareMetalHost, Provisioning, and hardware management.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/provisioning_apis/index](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/provisioning_apis/index)
- **Base URL:** `https://api.openshift.com/apis/metal3.io/v1alpha1`

#### Tags

- Bare Metal
- Hardware
- Infrastructure
- Provisioning

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/provisioning_apis/index)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Schedule and Quota API

API for managing scheduling and quota resources including ResourceQuota, LimitRange, PriorityClass, and ClusterResourceQuota.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/schedule_and_quota_apis/schedule-and-quota-apis](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/schedule_and_quota_apis/schedule-and-quota-apis)
- **Base URL:** `https://api.openshift.com/api/v1`

#### Tags

- LimitRanges
- Quotas
- Resource Management
- Scheduling

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/schedule_and_quota_apis/schedule-and-quota-apis)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Metadata API

API for managing metadata resources including ConfigMaps, Secrets, Events, Namespaces, and ServiceAccounts.

- **Human URL:** [https://docs.openshift.com/container-platform/4.7/rest_api/metadata_apis/metadata-apis-index.html](https://docs.openshift.com/container-platform/4.7/rest_api/metadata_apis/metadata-apis-index.html)
- **Base URL:** `https://api.openshift.com/api/v1`

#### Tags

- ConfigMaps
- Events
- Metadata
- Secrets

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/4.7/rest_api/metadata_apis/metadata-apis-index.html)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenShift Cluster Manager API

Managed service API for installing, modifying, operating, and upgrading Red Hat OpenShift clusters across cloud providers.

- **Human URL:** [https://docs.redhat.com/en/documentation/openshift_cluster_manager/1-latest/html/managing_clusters/assembly-managing-clusters](https://docs.redhat.com/en/documentation/openshift_cluster_manager/1-latest/html/managing_clusters/assembly-managing-clusters)
- **Base URL:** `https://api.openshift.com/api/clusters_mgmt/v1`

#### Tags

- Cluster Management
- Managed Service
- Multi-Cloud
- ROSA

#### Properties

- [Documentation](https://docs.redhat.com/en/documentation/openshift_cluster_manager/1-latest/html/managing_clusters/assembly-managing-clusters)
- [GitHub Organization](https://github.com/openshift-online/ocm-api-model)
- [Postman Collection](collections/openshift-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openshift-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/red-hat-openshift)
- [Getting Started](https://www.openshift.com/try)
- [Blog](https://www.openshift.com/blog)
- [GitHub Organization](https://github.com/openshift)
- [Terms of Service](https://www.redhat.com/en/about/terms-use)
- [Privacy Policy](https://www.redhat.com/en/about/privacy-policy)
- [Changelog](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/ocp-4-17-release-notes)
- [Login](https://console.redhat.com/openshift)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
