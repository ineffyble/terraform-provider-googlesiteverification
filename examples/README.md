## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_googlesiteverification"></a> [googlesiteverification](#requirement\_googlesiteverification) | 0.x |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_google"></a> [google](#provider\_google) | 4.50.0 |
| <a name="provider_googlesiteverification"></a> [googlesiteverification](#provider\_googlesiteverification) | 0.x |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [google_dns_managed_zone.domain](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/dns_managed_zone) | resource |
| [google_dns_record_set.domain](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/dns_record_set) | resource |
| [google_dns_record_set.domain_ns_records](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/dns_record_set) | resource |
| [google_project_service.siteverification](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/project_service) | resource |
| [googlesiteverification_dns.domain](https://registry.terraform.io/providers/ineffyble/googlesiteverification/0.4.6/docs/resources/dns) | resource |
| [googlesiteverification_dns_token.domain](https://registry.terraform.io/providers/ineffyble/googlesiteverification/0.4.6/docs/data-sources/dns_token) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_domain_name"></a> [domain\_name](#input\_domain\_name) | n/a | `string` | n/a | yes |

## Outputs

No outputs.
