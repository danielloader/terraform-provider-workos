# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.0](https://github.com/danielloader/terraform-provider-workos/compare/v2.1.0...v2.2.0) (2026-03-22)


### Features

* add external_id and metadata to organization resource ([4bde9d4](https://github.com/danielloader/terraform-provider-workos/commit/4bde9d43ca0edf89c938f20797bc74f6e21c352b))
* add external_id and metadata to organization resource ([beb9dbd](https://github.com/danielloader/terraform-provider-workos/commit/beb9dbdac487ab15e502dd04cedb227d2ae45ff4))
* add external_id lookup to organization data source ([d9f645b](https://github.com/danielloader/terraform-provider-workos/commit/d9f645b0fced2b2c3db295b5121e45c645309a8e))
* add permission resource, data source, and organization role permission resource ([d9ded58](https://github.com/danielloader/terraform-provider-workos/commit/d9ded58b3a1a4890872eafcf2109effda3cc6c7a))
* add permission resource, data source, and organization role permission resource ([10fd884](https://github.com/danielloader/terraform-provider-workos/commit/10fd884c8de8e31aef2c635ad721392bf9dc3da3))
* add workos_organization_role resource and data source ([bca489a](https://github.com/danielloader/terraform-provider-workos/commit/bca489a7bf76712d08dc39866c7282623c5e30ad))
* add workos_organization_role resource and data source ([394c45d](https://github.com/danielloader/terraform-provider-workos/commit/394c45d38fd874252f8d8afe30c6d87141c362df))
* Initial release of WorkOS Terraform Provider v1.0.0 ([0e50a3b](https://github.com/danielloader/terraform-provider-workos/commit/0e50a3bec5992d443f9a9b5092e7087dbb8a432c))


### Bug Fixes

* **ci:** Add golangci-lint config and tools dependency ([d5bd48d](https://github.com/danielloader/terraform-provider-workos/commit/d5bd48d3485eaad04d088c7f635a030c667ceb63))
* **ci:** Add Terraform setup and fix goreleaser deprecation ([e8cdc5c](https://github.com/danielloader/terraform-provider-workos/commit/e8cdc5cf82d326c30cc59a0499a395b013877d78))
* **ci:** Update GoReleaser action to v2 for version 2 config ([7085010](https://github.com/danielloader/terraform-provider-workos/commit/7085010d57e871153edae6586b3686da4322f005))
* prefix organization role slugs with 'org-' per WorkOS API requirement ([1e700d0](https://github.com/danielloader/terraform-provider-workos/commit/1e700d098989a3cf1a5727cd57246bdbc490fb5f))
* prevent updated_at drift and allow clearing description on permission resource ([0df2991](https://github.com/danielloader/terraform-provider-workos/commit/0df2991c8d4ec86bcc174b39518e1da4f82b18cf))
* prevent updated_at drift on re-apply ([36a1b9e](https://github.com/danielloader/terraform-provider-workos/commit/36a1b9ea3b3e0b500dd563f8c8848986013cca66))
* prevent updated_at drift on re-apply of unchanged state ([1ad7f91](https://github.com/danielloader/terraform-provider-workos/commit/1ad7f9116917cccb880521d217b5429e52bf1627)), closes [#5](https://github.com/danielloader/terraform-provider-workos/issues/5)
* regenerate docs to match go generate output ([ea88f08](https://github.com/danielloader/terraform-provider-workos/commit/ea88f087e52f0630509735cec14064b5186dffb2))
* remove unsupported resources and fix acceptance test failures ([8555547](https://github.com/danielloader/terraform-provider-workos/commit/85555472f4102b5eb4a0e8f832a963bd92281157))
* remove unsupported resources and fix acceptance test failures ([94dcad4](https://github.com/danielloader/terraform-provider-workos/commit/94dcad47f7ba7d1682f0a8763ff13b05379c1e4d))
* resolve updated_at drift on update and email_verified reset ([3f93787](https://github.com/danielloader/terraform-provider-workos/commit/3f937874700ecbf6fe6d1fb2cb3c15e9a20baeed))
* validate domain uniqueness across organizations ([0658b1f](https://github.com/danielloader/terraform-provider-workos/commit/0658b1fb8868e097358d77c11887421f8aa883a0))
* validate domain uniqueness across organizations ([14e5d2e](https://github.com/danielloader/terraform-provider-workos/commit/14e5d2ebcf6d35b6c85286ff7fac8c075523f68e)), closes [#8](https://github.com/danielloader/terraform-provider-workos/issues/8)

## [2.1.0](https://github.com/osodevops/terraform-provider-workos/compare/v2.0.0...v2.1.0) (2026-03-13)


### Features

* add external_id and metadata to organization resource ([4bde9d4](https://github.com/osodevops/terraform-provider-workos/commit/4bde9d43ca0edf89c938f20797bc74f6e21c352b))
* add external_id and metadata to organization resource ([beb9dbd](https://github.com/osodevops/terraform-provider-workos/commit/beb9dbdac487ab15e502dd04cedb227d2ae45ff4))
* add external_id lookup to organization data source ([d9f645b](https://github.com/osodevops/terraform-provider-workos/commit/d9f645b0fced2b2c3db295b5121e45c645309a8e))
* add permission resource, data source, and organization role permission resource ([d9ded58](https://github.com/osodevops/terraform-provider-workos/commit/d9ded58b3a1a4890872eafcf2109effda3cc6c7a))
* add permission resource, data source, and organization role permission resource ([10fd884](https://github.com/osodevops/terraform-provider-workos/commit/10fd884c8de8e31aef2c635ad721392bf9dc3da3))


### Bug Fixes

* prevent updated_at drift and allow clearing description on permission resource ([0df2991](https://github.com/osodevops/terraform-provider-workos/commit/0df2991c8d4ec86bcc174b39518e1da4f82b18cf))
* prevent updated_at drift on re-apply ([36a1b9e](https://github.com/osodevops/terraform-provider-workos/commit/36a1b9ea3b3e0b500dd563f8c8848986013cca66))
* prevent updated_at drift on re-apply of unchanged state ([1ad7f91](https://github.com/osodevops/terraform-provider-workos/commit/1ad7f9116917cccb880521d217b5429e52bf1627)), closes [#5](https://github.com/osodevops/terraform-provider-workos/issues/5)
* resolve updated_at drift on update and email_verified reset ([3f93787](https://github.com/osodevops/terraform-provider-workos/commit/3f937874700ecbf6fe6d1fb2cb3c15e9a20baeed))
* validate domain uniqueness across organizations ([0658b1f](https://github.com/osodevops/terraform-provider-workos/commit/0658b1fb8868e097358d77c11887421f8aa883a0))
* validate domain uniqueness across organizations ([14e5d2e](https://github.com/osodevops/terraform-provider-workos/commit/14e5d2ebcf6d35b6c85286ff7fac8c075523f68e)), closes [#8](https://github.com/osodevops/terraform-provider-workos/issues/8)

## [2.0.0] - 2026-02-24

### Added
- `workos_organization_role` resource - Manage organization authorization roles
- `workos_organization_role` data source - Look up organization roles by slug or ID

### Removed
- **BREAKING:** `workos_connection` resource - WorkOS API does not support creating/updating connections via API; use the Dashboard instead. The read-only data source is still available.
- **BREAKING:** `workos_directory` resource - WorkOS API does not support creating/updating directories via API; use the Dashboard instead. The read-only data source is still available.
- **BREAKING:** `workos_webhook` resource - WorkOS has no public webhook management API; use the Dashboard instead.
- **BREAKING:** `allow_profiles_outside_organization` attribute on `workos_organization` resource and data source - WorkOS API no longer accepts this parameter.

### Fixed
- `workos_user` resource: `email_verified` is now always sent on updates, preventing drift when email changes reset verification status
- `workos_organization_membership` resource: `role_slug` is preserved from plan/state when the API omits it from responses
- `workos_user` data source tests: replaced hardcoded placeholder IDs with dynamically created resources
- `workos_organization_role` resource: slug is now prefixed with `org-` per WorkOS API requirement

## [1.0.0] - 2026-02-01

### Added

#### Provider
- Provider configuration with `api_key`, `client_id`, and `base_url` attributes
- Environment variable support: `WORKOS_API_KEY`, `WORKOS_CLIENT_ID`, `WORKOS_BASE_URL`
- Rate limiting with exponential backoff and Retry-After header support
- Comprehensive error handling with typed errors

#### Resources
- `workos_organization` - Manage WorkOS organizations
  - Full CRUD operations
  - Domain management
  - Import support

- `workos_user` - Manage AuthKit users
  - Email and name management
  - Password and password hash support for authentication
  - Email verification status
  - Import support

- `workos_organization_membership` - Manage user-organization associations
  - User and organization linking
  - Role assignment support
  - Import support

#### Data Sources
- `workos_organization` - Look up organizations by ID or domain
- `workos_connection` - Look up SSO connections by ID or organization/type (read-only)
- `workos_directory` - Look up directories by ID or organization (read-only)
- `workos_directory_user` - Look up directory-synced users by ID or email
- `workos_directory_group` - Look up directory-synced groups by ID or name
- `workos_user` - Look up AuthKit users by ID or email

#### Documentation
- Auto-generated documentation using terraform-plugin-docs
- Comprehensive examples for all resources and data sources
- Schema descriptions with Markdown support

### Security
- API keys marked as sensitive and never logged
- User passwords marked as sensitive (write-only)
