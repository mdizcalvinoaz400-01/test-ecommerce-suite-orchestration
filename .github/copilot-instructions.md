# Copilot Instructions for test-ecommerce-suite Orchestration

This is the orchestration repository for the test-ecommerce-suite project. It coordinates work across all department repositories.

## Repository Purpose

- Cross-repository feature coordination
- Issue tracking and synchronization
- Project-wide status reporting
- Dependency management

## Related Repositories

| Department | Repository | Tech Stack |
|------------|------------|------------|
| Frontend | [test-ecommerce-suite-frontend](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-frontend) | html |
| Backend | [test-ecommerce-suite-backend](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-backend) | python |
| Infrastructure | [test-ecommerce-suite-infrastructure](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-infrastructure) | aws |

## Available Agents

### @orchestrator
Use for coordinating work across repositories:
- Creating multi-department features
- Managing dependencies
- Cross-repo issue creation

### @tracker
Use for monitoring progress:
- Status reports
- Blocker detection
- Velocity metrics

## Labels

| Label | Purpose |
|-------|--------|
| `feature` | Parent feature issues |
| `cross-repo` | Involves multiple repos |
| `blocked` | Blocked by dependency |
| `priority-high` | High priority items |
