# OpenShift API (openshift)
A comprehensive API definition for Red Hat OpenShift, the enterprise Kubernetes platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/openshift/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - CI/CD, Cloud Native, Containers, DevOps, Enterprise, Kubernetes, PaaS

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### OpenShift REST API
Main REST API for managing OpenShift clusters, projects, and resources.

**Human URL:** [https://docs.openshift.com/](https://docs.openshift.com/)

#### Tags:

 - Cloud, Containers, Kubernetes, Platform

#### Properties

- [Documentation](https://docs.openshift.com/container-platform/latest/rest_api/index.html)
- [OpenAPI](https://api.openshift.com/api/swagger.json)
- [Authentication](https://docs.openshift.com/container-platform/latest/authentication/index.html)
- [Pricing](https://www.redhat.com/en/technologies/cloud-computing/openshift/pricing)
- [Support](https://access.redhat.com/support)
- [StatusPage](https://status.openshift.com/)
- [SDK](https://github.com/openshift/client-go)
- [RateLimits](https://docs.openshift.com/container-platform/latest/rest_api/understanding-api-support-tiers.html)
- [GettingStarted](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/index)

## Common Properties

- [GettingStarted](https://www.openshift.com/try)
- [Blog](https://www.openshift.com/blog)
- [GitHubOrganization](https://github.com/openshift)
- [TermsOfService](https://www.redhat.com/en/about/terms-use)
- [PrivacyPolicy](https://www.redhat.com/en/about/privacy-policy)
- [ChangeLog](https://docs.redhat.com/en/documentation/openshift_container_platform/4.17/html/release_notes/ocp-4-17-release-notes)
- [Login](https://console.redhat.com/openshift)

## Features

| Name | Description |
|------|-------------|
| Enterprise Kubernetes | Production-grade Kubernetes platform with built-in security, monitoring, and lifecycle management. |
| Source-to-Image Builds | Automated container image builds directly from source code repositories. |
| Operator Framework | Lifecycle management for complex applications through Kubernetes Operators and OperatorHub. |
| Multi-Cluster Management | Centralized management of multiple OpenShift clusters across cloud providers. |
| Built-in Monitoring | Integrated Prometheus, Alertmanager, and Grafana for cluster and application observability. |

## Use Cases

| Name | Description |
|------|-------------|
| Application Modernization | Migrate monolithic applications to containerized microservices on Kubernetes. |
| CI/CD Pipelines | Automate build, test, and deployment workflows with integrated pipeline capabilities. |
| Edge Computing | Deploy and manage applications at edge locations with lightweight OpenShift deployments. |
| Hybrid Cloud Deployment | Run consistent workloads across on-premise, public cloud, and edge environments. |

## Integrations

| Name | Description |
|------|-------------|
| Cloud Providers | Native integration with AWS (ROSA), Azure (ARO), GCP, and IBM Cloud for managed deployments. |
| CI/CD Tools | Integration with Jenkins, Tekton, GitLab CI, and GitHub Actions for automated pipelines. |
| Service Mesh | Integration with Istio-based service mesh for traffic management, security, and observability. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [OpenShift REST API](openapi/openshift-rest-api-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [REST API](capabilities/shared/rest-api.yaml) -- 13 operations for project, build, deployment, pod, and cluster resource management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Platform Management](capabilities/platform-management.yaml) | REST API | 13 | Platform Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
