# Violations

Red Hat Advanced Cluster Security for Kubernetes built-in policies identify a variety of security findings, including vulnerabilities (CVEs), violations of DevOps best practices, high-risk build and deployment practices, and suspicious runtime behaviors. 

Whether you use the default out-of-box security policies or use your own custom policies, Red Hat Advanced Cluster Security for Kubernetes reports a violation when an enabled policy fails.
## Categories

### DevOps Best Practices

The following examples are included in this category:

- 90-Day Image Age
- Latest tag
- No resource requests or limits specified

### Security Best Practices

The following examples are included in this category:

- Red Hat Package Manager in Image
- Ubuntu Package Manager in Image
- Mounting Sensitive Host Directories
- Pod Service Account Token Automatically Mounted
- Environment Variable Contains Secret

### Anomalous activities or Kubernetes events

This category includes specific situations in Openshift clusters.

The following examples are included in this category:

- OpenShift: Kubeadmin Secret Accessed
- OpenShift: Advanced Cluster Security Central Admin Secret Accessed

### Vulnerability Management

This category includes specific CVEs that affect container images.

The following examples are included in this category:

- Fixable CVE-2019-13734

### Docker CIS

The following examples are included in this category:

- Ensure That a User for the Container Has Been Created
- Ensure that the host's network namespace is not shared

### Custom

It is possible to define custom policies that trigger custom violations. In this aspects, it is required to review the specific environment.

## Author

Asier Cidon (@RedHat)