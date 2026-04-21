# credential-expiry-reminder
Public repo for testing GitHub Actions expiry reminder workflows

This repository is used to test and validate GitHub Actions workflows that monitor expiration dates for secrets, certificates, or other time-sensitive credentials.

The goal is to safely verify reminder logic before using it in production repositories.

Scope of testing:
- reading expiration date from GitHub Variables
- calculating days remaining until expiry
- triggering reminders at defined thresholds
- creating GitHub issues without duplicates
- validating manual and scheduled workflow execution
