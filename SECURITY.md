# Security Policy

## Overview

This repository is a **public** system status monitor for Streamliners services, built with [Upptime](https://upptime.js.org). While the repository is public to enable free GitHub Actions builds, access and modifications are strictly controlled.

## Access Control

### Repository Access
- This repository is **publicly viewable** but **write-protected**
- Only authorized Streamliners personnel can modify the repository
- All changes require review and approval from code owners
- See `.github/CODEOWNERS` for authorized maintainers

### Issue Tracking
- GitHub Issues are used exclusively for automated downtime incidents
- Manual issue creation is **disabled** for unauthorized users
- Only repository collaborators can comment on issues
- Issues are automatically locked to prevent spam and unauthorized modifications

### Pull Requests
- All pull requests require approval from authorized code owners
- Branch protection rules enforce code review requirements
- Unauthorized pull requests will be closed

## What's Public

The following information is intentionally public:
- Service uptime status and history
- Response time metrics and graphs
- Incident reports (downtime events)
- Configuration of monitored endpoints

## What's Protected

The following requires authorization:
- Modifying configuration files
- Adding or removing monitored services
- Changing workflows and automation
- Repository settings and security policies
- Accessing any internal Streamliners systems (monitoring is external-facing only)

## Security Best Practices

This repository follows these security practices:
1. **No Secrets in Code**: No API keys, passwords, or sensitive credentials are stored in this repository
2. **GitHub Secrets**: Sensitive information is stored in encrypted GitHub Secrets
3. **Automated Monitoring**: All checks run via GitHub Actions with no external servers
4. **Audit Trail**: All changes are tracked via git commit history
5. **Minimal Permissions**: GitHub Actions use minimal required permissions

## Reporting Security Issues

If you discover a security vulnerability in this repository or related Streamliners services:

1. **Do NOT** open a public issue
2. **Do NOT** disclose the vulnerability publicly
3. Contact Streamliners security team through our website: [www.streamliners.com](https://www.streamliners.com/)

## Scope

This repository monitors **public-facing** Streamliners services only. It does not have access to:
- Internal Streamliners infrastructure
- Customer data or private information
- Authentication systems or credentials
- Internal APIs or databases

## Compliance

This monitoring system:
- Uses only publicly available endpoints
- Does not collect or store personal data
- Complies with our open-source licensing (MIT)
- Follows GitHub's Terms of Service and security guidelines

## Updates

This security policy was last updated: **October 2025**

For questions about this policy, contact Streamliners through our website.

