# DevOps Playground Notes

-Notes for Enterprise DevOps & Cloud Infrastructure

## Problems

### Organization Problems
- Structure responsibilities in groups and not individuals to allow for onboarding ease.


### Developer Problems
- Source Control
    - Repository and Branch Management (Lock down the main branch)

- Service Management
    - Empower developers to manage/deploy their own services, configurations and provisioning.
    - Save quality DevOps engineering time.

- Continuous Integration
    - Testing changes (cloud/local testing)
    - Caching branches
    - Burning Cloud money
    - Code coverage (write tests and coverage for everything)

- Logging and Metrics (Observability)
    - Have logs and metrics for each service (Grafana)
    - Ensure engineering teams know how to read logs and troubleshoot
    - Platform Ops: Ownership of platform core services with focus on logical parts, leaving developer related servoces to developers.


## GitOps

- Manage infrastructure and application management using Git.
- If you don't know what you did, you can't do it again.
- Infrastructure as a code - Tracking and reviewing changes - very important, everything has to be approved
- Automated deployments, reproducibility and rollbacks, collaboration.
- Exemplify the problem teams have dealt with and show how GitOps solves it.
- TLDR - Create a system, and if you want to change the system, change the repo.