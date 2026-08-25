# coderabbit

This repository provides the **organization-level default configuration**
for [CodeRabbit](https://www.coderabbit.ai/) across all repositories in the
[openstack-k8s-operators](https://github.com/openstack-k8s-operators) GitHub
organization.

CodeRabbit looks for a repository named `coderabbit` in an organization and
uses its `.coderabbit.yaml` as the default/base configuration, which
individual repositories then inherit from (and may override) via their own
`.coderabbit.yaml`. See the "Inheritance" section below.

## Contents

- [`.coderabbit.yaml`](./.coderabbit.yaml) — the org-wide default review
  configuration (path instructions, auto-review filters, knowledge base
  settings, etc.).

## Documentation

- [CodeRabbit Docs](https://docs.coderabbit.ai/)
- [Configuration file reference (`.coderabbit.yaml`)](https://docs.coderabbit.ai/reference/configuration)
- [Configuration schema](https://coderabbit.ai/integrations/schema.v2.json)
- [Organization-level settings / inheritance](https://docs.coderabbit.ai/guides/organization-settings)
- [Tools and integrations](https://docs.coderabbit.ai/integrations)
