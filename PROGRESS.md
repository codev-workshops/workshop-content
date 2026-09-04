# Workshop Progress Checklist

Tracks which files in this repo have been reviewed while working through the workshops.
Checkboxes in this file are not clickable on GitHub; tick them interactively in
[issue #4](https://github.com/codev-workshops/workshop-content/issues/4) instead (this file
is the committed copy — edit `[ ]` to `[x]` here if you want progress in git history).
Generated from `git ls-files` at the `baseline` tag (commit b48e486); regenerate the list
if files are added or removed.

## Which files have changed since baseline?

```bash
git fetch --tags
git diff --name-only baseline HEAD
```

Files not in that list have not been touched since the baseline was set.

## Files

### (root)

- [ ] `.gitignore`
- [ ] `AGENTS.md`
- [ ] `LICENSE`
- [ ] `README.md`
- [ ] `REVIEW.md`

### catalog

- [ ] `catalog/field-kit-offerings.md`
- [ ] `catalog/repos.md`
- [ ] `catalog/upstream-map.yaml`

### courses

- [ ] `courses/README.md`

### courses/foundations

- [ ] `courses/foundations/README.md`

### courses/foundations/concepts

- [ ] `courses/foundations/concepts/01-cloud-agent-vs-local-agent.md`
- [ ] `courses/foundations/concepts/02-event-driven-reactions.md`
- [ ] `courses/foundations/concepts/03-agent-orchestration.md`
- [ ] `courses/foundations/concepts/04-what-to-give-ai.md`
- [ ] `courses/foundations/concepts/README.md`

### courses/foundations/product

- [ ] `courses/foundations/product/README.md`

### courses/foundations/product/cloud

- [ ] `courses/foundations/product/cloud/05-deepwiki.md`
- [ ] `courses/foundations/product/cloud/06-devin-sessions.md`
- [ ] `courses/foundations/product/cloud/08-automations.md`
- [x] `courses/foundations/product/cloud/09-multi-agent-workers.md`
- [ ] `courses/foundations/product/cloud/devin-cloud.md`

### courses/foundations/product/local

- [ ] `courses/foundations/product/local/07-devin-cli.md`
- [ ] `courses/foundations/product/local/devin-cli-tour.md`
- [ ] `courses/foundations/product/local/devin-desktop.md`

### courses/tracks

- [ ] `courses/tracks/README.md`

### courses/tracks/engineering

- [ ] `courses/tracks/engineering/01-platform-fundamentals.md`
- [ ] `courses/tracks/engineering/02-prompt-engineering.md`
- [ ] `courses/tracks/engineering/03-environment-architecture.md`
- [ ] `courses/tracks/engineering/04-task-selection-framework.md`
- [ ] `courses/tracks/engineering/05-orchestration-patterns.md`
- [ ] `courses/tracks/engineering/06-working-with-agent-output.md`
- [ ] `courses/tracks/engineering/07-tactical-tips-troubleshooting.md`
- [ ] `courses/tracks/engineering/08-challenge-labs.md`
- [ ] `courses/tracks/engineering/09-debug-exercises.md`
- [ ] `courses/tracks/engineering/10-gaps-future-content.md`
- [ ] `courses/tracks/engineering/README.md`

### courses/tracks/sales

- [ ] `courses/tracks/sales/01-operating-model-transformation.md`
- [ ] `courses/tracks/sales/02-unit-of-work-economics.md`
- [ ] `courses/tracks/sales/03-value-narrative-selection.md`
- [ ] `courses/tracks/sales/04-engagement-scoping-and-estimation.md`
- [ ] `courses/tracks/sales/05-competitive-positioning.md`
- [ ] `courses/tracks/sales/06-decision-framework-for-sales.md`
- [ ] `courses/tracks/sales/07-case-study.md`
- [ ] `courses/tracks/sales/08-gaps-and-future-content.md`
- [ ] `courses/tracks/sales/README.md`

### courses/tracks/solutions

- [ ] `courses/tracks/solutions/01-platform-architecture-mastery.md`
- [ ] `courses/tracks/solutions/02-sdlc-integration-design.md`
- [ ] `courses/tracks/solutions/03-live-walkthrough-delivery.md`
- [ ] `courses/tracks/solutions/04-automation-topology-design.md`
- [ ] `courses/tracks/solutions/05-full-platform-configuration.md`
- [ ] `courses/tracks/solutions/06-handling-unexpected-outcomes.md`
- [ ] `courses/tracks/solutions/07-design-challenge.md`
- [ ] `courses/tracks/solutions/08-self-assessment-rubric.md`
- [ ] `courses/tracks/solutions/README.md`

### demos

- [ ] `demos/AGENTS.md`

### demos/application-development

- [ ] `demos/application-development/banking-feature-sdlc-demo.md`

### demos/data-engineering

- [ ] `demos/data-engineering/abinitio-lineage-analysis-demo.md`
- [ ] `demos/data-engineering/abinitio-to-databricks-demo.md`
- [ ] `demos/data-engineering/abinitio-to-pyspark-demo.md`
- [ ] `demos/data-engineering/sas-to-databricks-demo.md`
- [ ] `demos/data-engineering/sybase-to-sqlserver-demo.md`
- [ ] `demos/data-engineering/synthetic-testdata-generation-demo.md`
- [ ] `demos/data-engineering/teradata-to-bigquery-demo.md`

### demos/migration

- [ ] `demos/migration/aws-cloud-native-modernization-demo.md`
- [ ] `demos/migration/mulesoft-to-boomi-demo.md`
- [ ] `demos/migration/mulesoft-to-spring-boot-demo.md`

### demos/migration/scenarios

- [ ] `demos/migration/scenarios/app-modernization-delivery-phases.md`

### demos/migration

- [ ] `demos/migration/stored-procs-to-microservices-demo.md`
- [ ] `demos/migration/struts-to-microservices-demo.md`

### demos/security

- [ ] `demos/security/general.local.md`
- [ ] `demos/security/general.md`
- [ ] `demos/security/general.platform.md`

### demos/security/use-cases

- [ ] `demos/security/use-cases/application-threat-hunting-demo.md`
- [ ] `demos/security/use-cases/dast-remediation-demo.md`
- [ ] `demos/security/use-cases/dependency-cve-remediation-demo.md`
- [ ] `demos/security/use-cases/event-driven-sast-remediation-demo.md`
- [ ] `demos/security/use-cases/portfolio-scale-remediation-demo.md`
- [ ] `demos/security/use-cases/secure-refactor-equivalence-demo.md`
- [ ] `demos/security/use-cases/security-swarm-scan-demo.md`

### events

- [ ] `events/README.md`

### events/active

- [ ] `events/active/.gitkeep`

### events/active/2026-06-enterprise-modernization-workshop

- [ ] `events/active/2026-06-enterprise-modernization-workshop/README.md`

### events/active/agentic-sdlc-workshop

- [ ] `events/active/agentic-sdlc-workshop/README.md`

### events/active/banking-modernization-workshop

- [ ] `events/active/banking-modernization-workshop/README.md`

### events/active/enterprise-modernization-data-migration-workshop

- [ ] `events/active/enterprise-modernization-data-migration-workshop/README.md`

### events/active/financial-services-sandbox-enablement-workshop

- [ ] `events/active/financial-services-sandbox-enablement-workshop/README.md`

### events/archive/2026-03-09-oslo

- [ ] `events/archive/2026-03-09-oslo/README.md`

### events/archive/2026-03-09-san-francisco

- [ ] `events/archive/2026-03-09-san-francisco/README.md`

### events/archive/2026-03-13-washington-dc-2

- [ ] `events/archive/2026-03-13-washington-dc-2/README.md`

### events/archive/2026-03-17-zurich

- [ ] `events/archive/2026-03-17-zurich/README.md`

### events/archive/2026-03-25-remote-workshop

- [ ] `events/archive/2026-03-25-remote-workshop/README.md`
- [ ] `events/archive/2026-03-25-remote-workshop/TAKE-HOME.md`

### events/archive/2026-04-09-virtual-workshop

- [ ] `events/archive/2026-04-09-virtual-workshop/README.md`

### events/archive/2026-04-dc

- [ ] `events/archive/2026-04-dc/README.md`

### events/archive/2026-05-05-general-workshop

- [ ] `events/archive/2026-05-05-general-workshop/README.md`

### events/archive/2026-05-07-workshop

- [ ] `events/archive/2026-05-07-workshop/README.md`

### events/oracle-forms-modernization-workshop

- [ ] `events/oracle-forms-modernization-workshop/README.md`

### labs

- [ ] `labs/README.md`

### labs/ai-ml-engineering

- [ ] `labs/ai-ml-engineering/README.md`
- [ ] `labs/ai-ml-engineering/llm-integration-patterns.md`
- [ ] `labs/ai-ml-engineering/ml-pipeline-setup.md`
- [ ] `labs/ai-ml-engineering/model-evaluation-testing.md`

### labs/application-development

- [ ] `labs/application-development/README.md`
- [ ] `labs/application-development/bug-hunt-mern-ecommerce.md`
- [ ] `labs/application-development/database-schema-evolution.md`
- [ ] `labs/application-development/fix-data-bug.md`
- [ ] `labs/application-development/fix-runtime-bug.md`
- [ ] `labs/application-development/fix-ui-bug.md`
- [X] `labs/application-development/gather-requirements.md`
- [ ] `labs/application-development/new-feature-development.md`
- [ ] `labs/application-development/test-driven-development.md`

### labs/architecture-design

- [ ] `labs/architecture-design/README.md`
- [ ] `labs/architecture-design/api-consolidation.md`
- [ ] `labs/architecture-design/api-design-review.md`
- [ ] `labs/architecture-design/architecture-decision-records.md`
- [ ] `labs/architecture-design/code-refactoring-tech-debt.md`
- [ ] `labs/architecture-design/dependency-graph-analysis.md`

### labs/cloud-infrastructure

- [ ] `labs/cloud-infrastructure/README.md`
- [ ] `labs/cloud-infrastructure/cost-optimization-analysis.md`
- [ ] `labs/cloud-infrastructure/gitops-argocd-setup.md`
- [ ] `labs/cloud-infrastructure/iac-translation.md`
- [ ] `labs/cloud-infrastructure/kubernetes-manifest-generation.md`
- [ ] `labs/cloud-infrastructure/platform-conformant-microservice-decomposition.md`
- [ ] `labs/cloud-infrastructure/terraform-module-extraction.md`

### labs/compliance-governance

- [ ] `labs/compliance-governance/README.md`
- [ ] `labs/compliance-governance/gdpr-pii-detection.md`
- [ ] `labs/compliance-governance/license-compliance-audit.md`
- [ ] `labs/compliance-governance/regulatory-reporting.md`

### labs/data-engineering

- [ ] `labs/data-engineering/README.md`
- [ ] `labs/data-engineering/abinitio-lineage-impact-analysis.md`
- [ ] `labs/data-engineering/abinitio-migration-analysis.md`
- [ ] `labs/data-engineering/cobol-copybook-to-pyspark-json.md`
- [ ] `labs/data-engineering/data-quality-validation.md`
- [ ] `labs/data-engineering/data-source-migration.md`
- [ ] `labs/data-engineering/dw-migration-teradata-to-bigquery.md`
- [ ] `labs/data-engineering/dw-migration-teradata-to-snowflake.md`
- [ ] `labs/data-engineering/etl-pipeline-modernization.md`
- [ ] `labs/data-engineering/informatica-powercenter-analysis.md`
- [ ] `labs/data-engineering/informatica-to-snowflake-migration.md`
- [ ] `labs/data-engineering/sas-cicd-operationalization.md`
- [ ] `labs/data-engineering/sas-migration-analysis.md`
- [ ] `labs/data-engineering/sas-to-python-snowflake.md`

### labs/devin-features

- [ ] `labs/devin-features/README.md`

### labs/devops-cicd

- [ ] `labs/devops-cicd/README.md`
- [ ] `labs/devops-cicd/ci-failure-resolution.md`
- [ ] `labs/devops-cicd/cicd-pipeline.md`
- [ ] `labs/devops-cicd/configuration-management-feature-flags.md`
- [ ] `labs/devops-cicd/pr-review-automation.md`
- [ ] `labs/devops-cicd/release-management.md`

### labs/migration-modernization

- [ ] `labs/migration-modernization/README.md`
- [ ] `labs/migration-modernization/cloud-native-refactor.md`
- [ ] `labs/migration-modernization/cobol-migration-planning.md`
- [ ] `labs/migration-modernization/cobol-system-understanding.md`
- [ ] `labs/migration-modernization/cobol-to-java.md`
- [ ] `labs/migration-modernization/containerization-microservice-extraction.md`
- [ ] `labs/migration-modernization/cross-service-bug-investigation.md`
- [ ] `labs/migration-modernization/dotnet-monolith-decomposition.md`
- [ ] `labs/migration-modernization/framework-upgrade.md`
- [ ] `labs/migration-modernization/legacy-modernization-combined.md`
- [ ] `labs/migration-modernization/migration-test-harness.md`
- [ ] `labs/migration-modernization/one-shot-tech-debt-remediation.md`
- [ ] `labs/migration-modernization/oracle-forms-migration-planning.md`
- [ ] `labs/migration-modernization/oracle-forms-system-understanding.md`
- [ ] `labs/migration-modernization/oracle-forms-to-java.md`
- [ ] `labs/migration-modernization/repetitive-framework-upgrades.md`

### labs/observability-sre

- [ ] `labs/observability-sre/README.md`
- [ ] `labs/observability-sre/incident-response-triage.md`
- [ ] `labs/observability-sre/observability-monitoring.md`
- [ ] `labs/observability-sre/pod-remediation-credential-rotation.md`
- [ ] `labs/observability-sre/volume-anomaly-detection.md`

### labs/security

- [ ] `labs/security/README.md`
- [ ] `labs/security/event-driven-sast-remediation.md`
- [ ] `labs/security/mass-security-backlog-remediation.md`
- [ ] `labs/security/remediate-vulnerabilities.md`
- [ ] `labs/security/secrets-management-detection.md`
- [ ] `labs/security/security-antipatterns.md`
- [ ] `labs/security/shift-left-security.md`
- [ ] `labs/security/upgrade-dependencies.md`

### labs/technical-documentation

- [ ] `labs/technical-documentation/README.md`
- [ ] `labs/technical-documentation/api-documentation.md`
- [ ] `labs/technical-documentation/changelog-release-notes.md`
- [ ] `labs/technical-documentation/document-review-automation.md`
- [ ] `labs/technical-documentation/inline-documentation.md`
- [ ] `labs/technical-documentation/onboarding-guide-generation.md`
- [ ] `labs/technical-documentation/runbook-generation.md`

### labs/testing-qa

- [ ] `labs/testing-qa/README.md`
- [ ] `labs/testing-qa/accessibility-compliance.md`
- [ ] `labs/testing-qa/bdd-test-generation.md`
- [ ] `labs/testing-qa/continuous-quality-engineering.md`
- [ ] `labs/testing-qa/contract-testing.md`
- [ ] `labs/testing-qa/cross-service-integration-testing.md`
- [ ] `labs/testing-qa/end-to-end-testing.md`
- [ ] `labs/testing-qa/linting-static-analysis.md`
- [ ] `labs/testing-qa/load-testing-benchmarking.md`
- [ ] `labs/testing-qa/mutation-testing.md`
- [ ] `labs/testing-qa/performance-testing.md`
- [ ] `labs/testing-qa/test-framework-migration.md`
- [ ] `labs/testing-qa/unit-testing.md`
- [ ] `labs/testing-qa/visual-regression-testing.md`

### reference

- [ ] `reference/README.md`

### reference/general-themes

- [ ] `reference/general-themes/README.md`
- [x] `reference/general-themes/architecture-strengths.md`
- [ ] `reference/general-themes/cloud-vs-local-agents.md`
- [ ] `reference/general-themes/collaboration-model.md`
- [X] `reference/general-themes/design-patterns-for-devin.md`
- [x] `reference/general-themes/platform-capabilities.md`
- [ ] `reference/general-themes/value-narratives.md`
- [ ] `reference/general-themes/when-to-use-devin.md`

### reference

- [ ] `reference/runtime-resources.md`

### workshops

- [ ] `workshops/README.md`

### workshops/by-tech-domain

- [ ] `workshops/by-tech-domain/README.md`

### workshops/by-tech-domain/ai-and-automation/agentic-ai

- [ ] `workshops/by-tech-domain/ai-and-automation/agentic-ai/README.md`

### workshops/by-tech-domain/ai-and-automation/agentic-sdlc

- [ ] `workshops/by-tech-domain/ai-and-automation/agentic-sdlc/README.md`

### workshops/by-tech-domain/modernization/cobol

- [ ] `workshops/by-tech-domain/modernization/cobol/README.md`

### workshops/by-tech-domain/modernization/data-source-migration

- [ ] `workshops/by-tech-domain/modernization/data-source-migration/README.md`

### workshops/by-tech-domain/modernization/dotnet-cloud-native

- [ ] `workshops/by-tech-domain/modernization/dotnet-cloud-native/README.md`

### workshops/by-tech-domain/modernization/framework-upgrades

- [ ] `workshops/by-tech-domain/modernization/framework-upgrades/README.md`

### workshops/by-tech-domain/modernization/legacy

- [ ] `workshops/by-tech-domain/modernization/legacy/README.md`

### workshops/by-tech-domain/modernization/platform-decomposition

- [ ] `workshops/by-tech-domain/modernization/platform-decomposition/README.md`

### workshops/by-tech-domain/security/compliance

- [ ] `workshops/by-tech-domain/security/compliance/README.md`

### workshops/by-tech-domain/security/enterprise-automation

- [ ] `workshops/by-tech-domain/security/enterprise-automation/README.md`

### workshops/by-tech-role

- [ ] `workshops/by-tech-role/README.md`

### workshops/by-tech-role/development/app-maintenance

- [ ] `workshops/by-tech-role/development/app-maintenance/README.md`

### workshops/by-tech-role/development/feature-development

- [ ] `workshops/by-tech-role/development/feature-development/README.md`

### workshops/by-tech-role/digital-engineering

- [ ] `workshops/by-tech-role/digital-engineering/README.md`

### workshops/by-tech-role/quality-engineering/engineering-security

- [ ] `workshops/by-tech-role/quality-engineering/engineering-security/README.md`

### workshops/by-tech-role/quality-engineering/engineering

- [ ] `workshops/by-tech-role/quality-engineering/engineering/README.md`

### workshops/general

- [ ] `workshops/general/README.ja.md`
- [ ] `workshops/general/README.md`

### workshops/otterworks

- [ ] `workshops/otterworks/A1-etl-modernization.md`
- [ ] `workshops/otterworks/A2-framework-upgrade.md`
- [ ] `workshops/otterworks/A3-language-translation.md`
- [ ] `workshops/otterworks/B1-investigate-incident.md`
- [ ] `workshops/otterworks/B2-complete-runbooks.md`
- [ ] `workshops/otterworks/B3-add-observability.md`
- [ ] `workshops/otterworks/C1-security-sprint.md`
- [ ] `workshops/otterworks/C2-contract-audit.md`
- [ ] `workshops/otterworks/C3-test-coverage.md`
- [ ] `workshops/otterworks/README.md`

### workshops/otterworks/evaluation_scripts

- [ ] `workshops/otterworks/evaluation_scripts/A1-etl-modernization-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/A2-framework-upgrade-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/A3-language-translation-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/B1-investigate-incident-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/B2-complete-runbooks-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/B3-add-observability-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/C1-security-sprint-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/C2-contract-audit-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/C3-test-coverage-eval.md`
- [ ] `workshops/otterworks/evaluation_scripts/README.md`
