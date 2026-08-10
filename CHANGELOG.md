# Changelog

All notable changes to this project will be documented in this file.

<!-- release-bot:start -->

## [1.0.0] - 2026-08-10

### Breaking Changes
- None

### Features
- [#123](https://github.com/opencloud-eu/helm/pull/123) feat: simple nginx-no-snippets preset (alternative to #112)
- [#84](https://github.com/opencloud-eu/helm/pull/84) feat: implement external Keycloak support (fixes #75, #82)
- [#50](https://github.com/opencloud-eu/helm/pull/50) feat: Add registry/repository split and global image overrides

### Fixes
- [#126](https://github.com/opencloud-eu/helm/pull/126) fix(opencloud): do not create minio pvc if minio disabled
- [#22](https://github.com/opencloud-eu/helm/pull/22) fix(opencloud): usage of opencloud.config.appRegistry and .csp
- [#27](https://github.com/opencloud-eu/helm/pull/27) fix(opencloud): allow to set proxy_basic_auth
- [#24](https://github.com/opencloud-eu/helm/pull/24) fix(opencloud): add option to set env and envFrom
- [#19](https://github.com/opencloud-eu/helm/pull/19) fix: gateway annotations on metadata

### Chore / Docs / CI / Other
- [#144](https://github.com/opencloud-eu/helm/pull/144) Fix to Version 4.00-rc.1
- [#142](https://github.com/opencloud-eu/helm/pull/142) Add Posix support
- [#141](https://github.com/opencloud-eu/helm/pull/141) Update README.md
- [#138](https://github.com/opencloud-eu/helm/pull/138) Community Charts – Not Officially Supported
- [#118](https://github.com/opencloud-eu/helm/pull/118) Add option to override gateway sectionName for all HTTPRoutes
- [#125](https://github.com/opencloud-eu/helm/pull/125) Add support for PosixFS storage
- [#127](https://github.com/opencloud-eu/helm/pull/127) Set fsGroupChangePolicy: OnRootMismatch to avoid a chown -R
- [#115](https://github.com/opencloud-eu/helm/pull/115) Fix oci url and fluxcd config values
- [#122](https://github.com/opencloud-eu/helm/pull/122) Fix collabora credentials
- [#113](https://github.com/opencloud-eu/helm/pull/113) Update MAINTAINERS.md with team roles and permissions
- [#119](https://github.com/opencloud-eu/helm/pull/119) Fix README.md Table of Contents
- [#117](https://github.com/opencloud-eu/helm/pull/117) Allow use of existing PVCs in values.yaml
- [#116](https://github.com/opencloud-eu/helm/pull/116) Use correct secret name for SMTP
- [#114](https://github.com/opencloud-eu/helm/pull/114) Add opencloud-microservices chart
- [#99](https://github.com/opencloud-eu/helm/pull/99) add missing edit account url
- [#92](https://github.com/opencloud-eu/helm/pull/92) support external nats
- [#95](https://github.com/opencloud-eu/helm/pull/95) fix s3
- [#63](https://github.com/opencloud-eu/helm/pull/63) Add support for existing secrets and replace plaintext values with secrets
- [#91](https://github.com/opencloud-eu/helm/pull/91) fix annotation preset
- [#89](https://github.com/opencloud-eu/helm/pull/89) document smtp config options
- [#87](https://github.com/opencloud-eu/helm/pull/87) fix - remove basic auth
- [#85](https://github.com/opencloud-eu/helm/pull/85) [opencloud] remove the enableBasicAuth variable, as Basic Auth should not be used
- [#62](https://github.com/opencloud-eu/helm/pull/62) charts/opencloud/values.yaml: do not set the cert-manager annotation by default
- [#83](https://github.com/opencloud-eu/helm/pull/83) Add kastl-ars and Tim-herbie as reviewers
- [#81](https://github.com/opencloud-eu/helm/pull/81) [opencloud] remove YAML code for Gateway from README.md, adapt helm install command to do the needful
- [#66](https://github.com/opencloud-eu/helm/pull/66) charts/opencloud/README.md: remove duplicate clusterIssuer
- [#56](https://github.com/opencloud-eu/helm/pull/56) charts/opencloud/README.md: add global.domain.wopi
- [#76](https://github.com/opencloud-eu/helm/pull/76) Fix inconsistent rendering of booleans
- [#61](https://github.com/opencloud-eu/helm/pull/61) README.md: remove actual installation steps, as those are describe in each chart's README.md
- [#80](https://github.com/opencloud-eu/helm/pull/80) use global.tls.enabled for gatewayAPI resources
- [#79](https://github.com/opencloud-eu/helm/pull/79) [opencloud] remove default for port 443, as that is set in the values.yaml as default already
- [#57](https://github.com/opencloud-eu/helm/pull/57) opencloud: use .Values.global.tls.secretName instead of hardcoded name
- [#43](https://github.com/opencloud-eu/helm/pull/43) Add OCI registry support via GitHub Actions workflow
- [#35](https://github.com/opencloud-eu/helm/pull/35) Add community governance structure
- [#29](https://github.com/opencloud-eu/helm/pull/29) delete unused httproutes
- [#26](https://github.com/opencloud-eu/helm/pull/26) Add Collabora Online Support
- [#45](https://github.com/opencloud-eu/helm/pull/45) fix volumeMount defined twice in opencloud-collaboration
- [#44](https://github.com/opencloud-eu/helm/pull/44) Fix service name inconsistency by using dynamic Release.Name
- [#37](https://github.com/opencloud-eu/helm/pull/37) Improve namespace handling by removing explicit definitions
- [#31](https://github.com/opencloud-eu/helm/pull/31) Move charts to standard Helm structure with charts directory
- [#18](https://github.com/opencloud-eu/helm/pull/18) fix custom gateway port
- [#17](https://github.com/opencloud-eu/helm/pull/17) use the opencloud.namespace to prevent using an empty namespace
- [#16](https://github.com/opencloud-eu/helm/pull/16) make gateway generic
- [#9](https://github.com/opencloud-eu/helm/pull/9) remove duplicate var
- [#8](https://github.com/opencloud-eu/helm/pull/8) Move opencloud-dev chart to root level for consistency
- [#4](https://github.com/opencloud-eu/helm/pull/4) Improve README organization and add Matrix community links
- [#2](https://github.com/opencloud-eu/helm/pull/2) Initial Release
- [#1](https://github.com/opencloud-eu/helm/pull/1) Helm Charts for DEV Version of OpenCloud 


## [2.4.7] - 2026-08-09

### Breaking Changes
- None

### Features
- None

### Fixes
- [#129](https://github.com/Tim-herbie/opencloud-helm/pull/129) fix: improve httproute and gateway usability

### Chore / Docs / CI / Other
- [#136](https://github.com/Tim-herbie/opencloud-helm/pull/136) chore(deps): update docker.io/collabora/code docker tag to v26.04.2.4.1
- [#139](https://github.com/Tim-herbie/opencloud-helm/pull/139) chore(deps): update docker.io/opencloudeu/opencloud-rolling docker tag to v7.4.0
- [#140](https://github.com/Tim-herbie/opencloud-helm/pull/140) chore(deps): update quay.io/keycloak/keycloak docker tag to v26.7.1
- [#135](https://github.com/Tim-herbie/opencloud-helm/pull/135) chore(deps): update opencloudeu/web-extensions docker tag
- [#134](https://github.com/Tim-herbie/opencloud-helm/pull/134) chore(deps): update dependency node to v24
- [#133](https://github.com/Tim-herbie/opencloud-helm/pull/133) chore(deps): update opencloudeu/web-extensions docker tag
- [#131](https://github.com/Tim-herbie/opencloud-helm/pull/131) chore(deps): update actions/upload-artifact action to v7
- [#130](https://github.com/Tim-herbie/opencloud-helm/pull/130) chore(deps): update actions/setup-node action to v7
- [#128](https://github.com/Tim-herbie/opencloud-helm/pull/128) chore(tests): add e2e tests
- [#126](https://github.com/Tim-herbie/opencloud-helm/pull/126) chore(docs): add minimal-setup docs example
- [#124](https://github.com/Tim-herbie/opencloud-helm/pull/124) chore: move set OC_ADMIN_USER_ID always instead only when oidc is ena…
- [#132](https://github.com/Tim-herbie/opencloud-helm/pull/132) Enable Renovate updates for web extension image tags


## [2.4.6] - 2026-07-17

### Breaking Changes
- None

### Features
- None

### Fixes
- [#117](https://github.com/Tim-herbie/opencloud-helm/pull/117) fix: collaboration nats connection to opencloud

### Chore / Docs / CI / Other
- None


## [2.4.5] - 2026-07-14

### Breaking Changes
- None

### Features
- None

### Fixes
- None

### Chore / Docs / CI / Other
- [#114](https://github.com/Tim-herbie/opencloud-helm/pull/114) chore(deps): update docker.io/opencloudeu/opencloud-rolling docker tag to v7.3.0
- [#111](https://github.com/Tim-herbie/opencloud-helm/pull/111) chore(deps): update quay.io/keycloak/keycloak docker tag to v26.7.0
- [#112](https://github.com/Tim-herbie/opencloud-helm/pull/112) chore(deps): update docker.io/collabora/code docker tag to v26.04.2.1.1


## [2.4.4] - 2026-06-25

### Breaking Changes
- None

### Features
- None

### Fixes
- None

### Chore / Docs / CI / Other
- [#108](https://github.com/Tim-herbie/opencloud-helm/pull/108) chore(deps): update actions/checkout action to v7
- [#104](https://github.com/Tim-herbie/opencloud-helm/pull/104) chore(deps): update docker.io/collabora/code docker tag to v26
- [#105](https://github.com/Tim-herbie/opencloud-helm/pull/105) chore(deps): update quay.io/keycloak/keycloak docker tag to v26.6.3
- [#109](https://github.com/Tim-herbie/opencloud-helm/pull/109) chore(deps): update docker.io/opencloudeu/opencloud-rolling docker tag to v7.2.0


## [2.4.3] - 2026-06-02

### Breaking Changes
- None

### Features
- None

### Fixes
- None

### Chore / Docs / CI / Other
- [#102](https://github.com/Tim-herbie/opencloud-helm/pull/102) chore(deps): update docker.io/opencloudeu/opencloud-rolling docker tag to v7.1.0
- [#99](https://github.com/Tim-herbie/opencloud-helm/pull/99) chore(deps): update docker.io/collabora/code docker tag to v25.04.10.3.1


## [2.4.2] - 2026-05-31

### Breaking Changes
- None

### Features
- None

### Fixes
- None

### Chore / Docs / CI / Other
- [#95](https://github.com/Tim-herbie/opencloud-helm/pull/95) chore(deps): update docker.io/library/busybox docker tag to v1.38
- [#96](https://github.com/Tim-herbie/opencloud-helm/pull/96) chore(deps): update docker.io/apache/tika docker tag to v3.3.1.0
- [#98](https://github.com/Tim-herbie/opencloud-helm/pull/98) Make credential migration hook configurable via `opencloud.migration.enabled`


## [2.4.1] - 2026-05-22

### Breaking Changes
- None

### Features
- None

### Fixes
- [#93](https://github.com/Tim-herbie/opencloud-helm/pull/93) fix: idm authentication #92

### Chore / Docs / CI / Other
- None


## [2.4.0] - 2026-05-22

### Breaking Changes
- None

### Features
- [#85](https://github.com/Tim-herbie/opencloud-helm/pull/85) Feature/add init secretes

### Fixes
- None

### Chore / Docs / CI / Other
- [#90](https://github.com/Tim-herbie/opencloud-helm/pull/90) chore(deps): update docker.io/opencloudeu/opencloud-rolling docker tag to v7
- [#89](https://github.com/Tim-herbie/opencloud-helm/pull/89) chore(deps): update quay.io/keycloak/keycloak docker tag to v26.6.2
- [#88](https://github.com/Tim-herbie/opencloud-helm/pull/88) Update OpenCloud web extension tags to latest available releases


## [2.3.0] - 2026-05-12

### Breaking Changes
- None

### Features
- [#83](https://github.com/Tim-herbie/opencloud-helm/pull/83) feat: Add helm-unittest pipeline test cases for web extensions, ingress, and gateway HTTPRoutes
- [#80](https://github.com/Tim-herbie/opencloud-helm/pull/80) Add new web extensions: arcade, calculator, cast, maps, pastebin

### Fixes
- None

### Chore / Docs / CI / Other
- [#84](https://github.com/Tim-herbie/opencloud-helm/pull/84) chore(deps): update docker.io/opencloudeu/opencloud-rolling docker tag to v6.2.0
- [#79](https://github.com/Tim-herbie/opencloud-helm/pull/79) chore(deps): update peter-evans/create-pull-request action to v8
- [#77](https://github.com/Tim-herbie/opencloud-helm/pull/77) Add release bot

<!-- release-bot:end -->
