# GitHub Contributions Automation

This repository contains a GitHub Actions workflow that automatically creates daily commits to keep your GitHub contributions graph active and green.

## How it Works

- A GitHub Action runs automatically every day at midnight (UTC)
- It creates a new file with a timestamp in the `commits` directory
- The changes are automatically committed and pushed
- This keeps your GitHub contributions graph active

## Manual Trigger

You can also manually trigger the workflow through the GitHub Actions tab if needed.

## Important Note

This is for educational purposes. Make sure to comply with GitHub's terms of service and use this responsibly.

## Setup

1. Fork this repository
2. Enable GitHub Actions in your forked repository
3. Make sure the repository has the necessary permissions to create commits
4. The automation will start running daily

The workflow will automatically commit changes using the GitHub Actions bot account. 