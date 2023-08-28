# Azure SonarQube Terraform Kubernetes Module

<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_azurerm"></a> [azurerm](#provider\_azurerm) | 3.71.0 |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_sonarqube"></a> [sonarqube](#module\_sonarqube) | https://github.com/sq-ia/terraform-kubernetes-sonarqube.git | n/a |

## Resources

| Name | Type |
|------|------|
| [azurerm_kubernetes_cluster.primary](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/data-sources/kubernetes_cluster) | data source |

## Inputs

No inputs.

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_postgresql_password"></a> [postgresql\_password](#output\_postgresql\_password) | Password for the PostgreSQL database deployed with SonarQube |
| <a name="output_postgresql_username"></a> [postgresql\_username](#output\_postgresql\_username) | Username for the PostgreSQL database deployed with SonarQube |
| <a name="output_sonarqube"></a> [sonarqube](#output\_sonarqube) | Sonarqube\_Info |
<!-- END_TF_DOCS -->