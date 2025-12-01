# AGENTS.md

This document provides guidance for AI agents (like opencode) on how to interact with this repository and its submodules.

## Repository Structure

This repository (`brand`) is the main project containing multiple submodules:

- `github/`: Submodule pointing to the GitHub profile repository (`veracioux/veracioux`). This contains the GitHub README.md, profile icons, and other GitHub-specific content.
- `website/`: Submodule containing the personal website code and assets.

## Submodule Handling

### Important Rules

1. **Do not automatically update submodules**: Never run `git submodule update`, `git submodule sync`, or similar commands without explicit user request.

2. **Do not commit changes automatically**: Never commit or push changes to any repository (main or submodules) unless explicitly instructed by the user.

### Remote Preview of GitHub profile repository

To preview the GitHub README.md remotely in Firefox, run `firefox https://github.com/veracioux/veracioux/blob/preview/README.md`
