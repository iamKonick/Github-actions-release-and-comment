# GitHub Actions for Automated Releases and Self-Review Comment on Pull Request

I have built a GitHub Actions workflow that automates the release process using the titles of pull requests. Additionally, this workflow ensures that developers are reminded to perform a self-review after every pull request.

## Features

- **Automated Releases**: The workflow uses the titles of merged pull requests to generate release notes and create a new release.
- **Self-Review Reminders**: After a pull request is created, the workflow adds a comment asking the developer to perform a self-review.

## Workflow Details

The workflow is triggered by pull request events and follows these steps:

1. **Check Pull Request Title**: Ensures that the pull request title follows the required format for release notes.
2. **Create Release**: Upon merging, the workflow uses the pull request titles to generate release notes and create a new release.
3. **Add Self-Review Comment**: When a pull request is created, the workflow adds a comment reminding the developer to perform a self-review.

