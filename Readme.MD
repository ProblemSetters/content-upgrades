# Content Upgrades Repository

This repository serves as a central location for managing content upgrade diff files across different stacks in the Problemsetters organization.

## Purpose

The repository works in conjunction with an automated script that:

1. Iterates through all repositories in the Problemsetters organization.
2. Identifies required content upgrades based on the stack.
3. Applies the diff files stored in this repository.
4. Creates Pull Requests in the original repositories for:
   - Question Upgrades
   - Solution Upgrades

## How it Works

The content upgrade process follows these steps:
1. SMEs or engineers test content upgrades on a sample question
2. After successful testing, they add the verified diff files to this repository, organized by stack
3. The automation script then:
   - Scans ProblemSetters repositories for upgrade requirements
   - Applies the appropriate diff files from this repository to original question repo.
   - Initiates PRs in the source repositories with the required changes.

## Structure

The repository is organized by stack types, with each having its own directory containing the relevant diff files for upgrades.
