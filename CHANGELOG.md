# Changelog

All notable changes to this project will be documented in this file.

## [2.8.0](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.7.3...v2.8.0) (2023-04-07)


### Features

* Add output for the CloudWatch log group name and ARN created for the Step Function ([#45](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/45)) ([62afe34](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/62afe3466501da24b6c94c92756334da69f16e3f))

### [2.7.3](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.7.2...v2.7.3) (2023-01-24)


### Bug Fixes

* Use a version for  to avoid GitHub API rate limiting on CI workflows ([#48](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/48)) ([a22efcb](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/a22efcb289e6305d1be3b2d6256065d580ee0cae))

### [2.7.2](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.7.1...v2.7.2) (2022-11-02)


### Bug Fixes

* Move default resources for events for AWS Batch service integration ([#44](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/44)) ([bb2186b](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/bb2186b4215461dad5675790c3125b0116030a81))

### [2.7.1](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.7.0...v2.7.1) (2022-10-27)


### Bug Fixes

* Update CI configuration files to use latest version ([#43](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/43)) ([9eea3d9](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/9eea3d9cf7c384955065ae3ca400d97428dfdfb0))

## [2.7.0](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.6.0...v2.7.0) (2022-04-13)


### Features

* Enabled tags for IAM policies ([#38](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/38)) ([f9d3a89](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/f9d3a894fb30cbcc298903cdf9d277e4835da9d8))

## [2.6.0](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.5.2...v2.6.0) (2022-04-11)


### Features

* Added default resources for events permissions ([#34](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/34)) ([698e4c1](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/698e4c1a4640ee80d810bd8f7e6e4db3acfd2b47))


### [2.5.2](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.5.1...v2.5.2) (2022-01-14)


### Bug Fixes

* True/false results had different types ([#30](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/30)) ([9f8c111](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/9f8c111b8c8daa8e0525525ca0110b3a8c43e577))

### [2.5.1](https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.5.0...v2.5.1) (2022-01-10)


### Bug Fixes

* update CI/CD process to enable auto-release workflow ([#26](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/26)) ([660d759](https://github.com/terraform-aws-modules/terraform-aws-step-functions/commit/660d759b68d2ae9817fd1bc138885cddc58dfd2e))


<a name="v2.5.0"></a>
## [v2.5.0] - 2021-09-15

- feat: Adding IAM PassRole for ECS tasks as it is required for Fargate ([#24](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/24))


<a name="v2.4.0"></a>
## [v2.4.0] - 2021-09-01

- feat: Enable X-Ray tracing on Step Function if set to true in service_integrations ([#22](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/22))


<a name="v2.3.0"></a>
## [v2.3.0] - 2021-05-25

- chore: Remove check boxes that don't render properly in module doc ([#18](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/18))


<a name="v2.2.0"></a>
## [v2.2.0] - 2021-05-15

- feat: Add support for EventBridge integration with PutEvents tasks ([#17](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/17))


<a name="v2.1.0"></a>
## [v2.1.0] - 2021-05-12

- fix: Fixed service_integration type conversion with tomap ([#16](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/16))
- chore: update CI/CD to use stable `terraform-docs` release artifact and discoverable Apache2.0 license ([#13](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/13))


<a name="v2.0.0"></a>
## [v2.0.0] - 2021-04-26

- feat: Shorten outputs (removing this_) ([#12](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/12))


<a name="v1.3.0"></a>
## [v1.3.0] - 2021-04-07

- feat: Configure cloudwatch logging for step functions module ([#9](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/9))
- chore: update documentation and pin `terraform_docs` version to avoid future changes ([#10](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/10))
- chore: align ci-cd static checks to use individual minimum Terraform versions ([#6](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/6))
- chore: Run pre-commit terraform_docs hook ([#5](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/5))
- chore: add ci-cd workflow for pre-commit checks ([#4](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/4))


<a name="v1.2.0"></a>
## [v1.2.0] - 2021-02-20

- chore: update documentation based on latest `terraform-docs` which includes module and resource sections ([#3](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/3))


<a name="v1.1.0"></a>
## [v1.1.0] - 2021-02-12

- feat: Add support for Step Function type - STANDARD (default) or EXPRESS ([#2](https://github.com/terraform-aws-modules/terraform-aws-step-functions/issues/2))


<a name="v1.0.0"></a>
## [v1.0.0] - 2020-11-21

- fix: IAM policy integration


<a name="v0.1.0"></a>
## v0.1.0 - 2020-11-21

- Initial commit


[Unreleased]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.5.0...HEAD
[v2.5.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.4.0...v2.5.0
[v2.4.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.3.0...v2.4.0
[v2.3.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.2.0...v2.3.0
[v2.2.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.1.0...v2.2.0
[v2.1.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v2.0.0...v2.1.0
[v2.0.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v1.3.0...v2.0.0
[v1.3.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v1.2.0...v1.3.0
[v1.2.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/terraform-aws-modules/terraform-aws-step-functions/compare/v0.1.0...v1.0.0
