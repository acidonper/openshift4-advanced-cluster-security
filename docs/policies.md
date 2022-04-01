# Policies

Red Hat Advanced Cluster Security for Kubernetes allows you to use out-of-the-box security policies and define custom multi-factor policies for your container environment. Configuring these policies enables you to automatically prevent high-risk service deployments in your environment and respond to runtime security incidents.

The default policies have preconfigured parameters and belong to categories such as:

- Anomalous Activity
- Cryptocurrency Mining
- DevOps Best Practices
- Kubernetes
- Network Tools
- Package Management
- Privileges
- Security Best Practices
- System Modification
- Vulnerability Management

You can edit these categories create your own categories. Please visit [violations](./violations.md) for more examples about included policies with Red Hat Advanced Cluster Security for Kubernetes default installation.

## Custom Policies

In addition to using the default policies, you can also create custom policies in Red Hat Advanced Cluster Security for Kubernetes.

To build a new policy, you can clone an existing policy or create a new one from scratch.

- You can also create policies based on the filter criteria in the Risk view in the RHACS portal.
- You can also use AND, OR, and NOT logical operators for policy criteria to create advanced policies.

WIP

## Author

Asier Cidon (@RedHat)