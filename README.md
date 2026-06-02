# AcreetionOS Code — Base Template

This is the **AcreetionOS Code** template repository, providing a standardized
foundation for all AcreetionOS projects.

## Included Automation

### Pullfrog AI Review

All repositories created from this template include **Pullfrog AI** — an automated
code review agent that analyzes every pull request for:

- Code quality and style issues
- Security vulnerabilities
- Performance bottlenecks
- Architecture and design concerns
- Best practice violations

Pullfrog runs automatically on every PR, or on-demand by commenting `@pullfrog`.

## Secrets

The following secrets should be available in your repository or organization:

- `ORGANIZATION_OPENROUTER_KEY` — API key for OpenRouter (powers Pullfrog)
