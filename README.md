# Terraform provider for Google's site verification

A simple provider hitting this API: https://developers.google.com/site-verification

See https://registry.terraform.io/providers/ineffyble/googlesiteverification

Forked from [hectorj/terraform-provider-googlesiteverification](https://github.com/hectorj/terraform-provider-googlesiteverification) with a minimum-required package version bump so that Google auth via Workload Identity Federation (e.g. GitHub Actions OIDC) is supported.