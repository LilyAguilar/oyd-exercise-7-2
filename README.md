# Exercise 7.2 — Multi-Env Layout and GitHub Environment Promotion

## Repository Structure


- [`.github/`](./.github/)
  - [`workflows/`](./.github/workflows/)
    - [`terraform-cd.yml`](./.github/workflows/terraform-cd.yml)
- [`evidence/`](./evidence/)
  - [`pr-url.txt`](./evidence/pr-url.txt)
- [`infra/`](./infra/)
  - [`main.tf`](./infra/main.tf)
  - [`mise.toml`](./infra/mise.toml)
  - [`provider.tf`](./infra/provider.tf)
  - [`variables.tf`](./infra/variables.tf)
  - [`envs/`](./infra/envs/)
    - [`dev/`](./infra/envs/dev/)
      - [`backend-dev.hcl`](./infra/envs/dev/backend-dev.hcl)
      - [`dev.tfvars`](./infra/envs/dev/dev.tfvars)
      - [`staging/`](./infra/envs/dev/staging/)
        - [`backend-staging.hcl`](./infra/envs/dev/staging/backend-staging.hcl)
        - [`staging.tfvars`](./infra/envs/dev/staging/staging.tfvars)

## Evidence

PR url:
https://github.com/LilyAguilar/oyd-exercise-7-2/pull/1
