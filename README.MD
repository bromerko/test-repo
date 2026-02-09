# Template Repository

## Overview

This repository provides a general configuration template for creating new repositories that comply with Nagomi's security policies.

The following GitHub Actions will be included in the cloned repository:

- **Required**: Secrets Scanning
- **Required**: Ticket Lint
- **Required**: Validate PR Commits
- **Required**: Static Code Analysis
- **Required**: Auto-Assign Author
- **Recommended/Optional**: Semantic Release

Please customize the `.pre-commit-config.yaml` file according to the programming language used in your project.

For more details, refer to the [Notion Page](https://www.notion.so/nagomi-security/How-To-Create-a-new-GitHub-Repository-12bd8d0a77574743b357bf71d31ab8f3).
