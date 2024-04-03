# Changelog
All notable changes to `cnj-logging-downstream` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.0.0] - 2024-04-03
### Changed
- upgraded Spring Boot to version 3.2.4
- upgraded Java to version 21
- upgraded Maven plugins and dependencies
- consolidated POM with other showcases
- consolidated system tests with other showcases
- commit-stage builds produce Docker images for linux/amd64 and linux/arm64/v8 platforms now
- Docker images use Generational Z garbage collector by default
- consolidated common dependencies
- upgraded common cloudtrain dependencies

## [2.1.0] - 2023-11-14
### Added
- Tagging of git branch
### Changed
- Upgraded to helm-maven-plugin version 5.0.0
- Now a helm chart is packaged and pushed as an artifact during the commit-stage build
- Now the helm chart is pulled before deploying during the integration-test-stage build
- Consolidated all Maven plugins
- Upgraded all Maven plugins
- Upgraded to Spring Boot 3.1.5 and upgraded all related dependencies
- Upgraded cnj-common-observability-spring to version 1.2.0
- Removed dependency on cnj-common-test-jakarta by using actual model in tests
- Removed some SonarQube issues

## [2.0.0] - 2023-06-09
### Changed
- moved to new AWS CodeBuild build pipeline
- moved to new CloudTrain EKS cluster
- upgraded everything

## [1.1.0] - 2022-03-12
### Added
### Changed
- re-release after repo split
