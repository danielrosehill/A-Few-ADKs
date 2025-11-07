# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repository serves as a curated index of Agent Development Kits (ADKs) and is updated periodically as new ADKs and SDKs come to market. Currently contains:
- A comprehensive README.md listing ADKs organized by provider (Google, Enterprise, Community)
- GitHub star badges and repository links for each ADK
- A banner image for the repository

**Planned additions**:
- Installation scripts for installing the various ADKs/SDKs
- These will be added to help automate setup and deployment of the listed tools

## Repository Inclusion/Exclusion Policy

**Inclusion criteria**:
- ADKs only - actual development kits and frameworks for agent development

**Exclusion criteria**:
- No demos, notebooks, or examples
- These are intentionally kept separate due to volume

## Maintenance Tasks

This repository is updated periodically as new ADKs and SDKs emerge in the market.

When updating this repository:

1. **Adding new ADKs**:
   - Add entries to the main table in README.md
   - Follow the existing format with GitHub stars badge, repository link, and description
   - Add to the appropriate "Organization by Provider" section (Google ADKs, Enterprise Solutions, or Community & Independent)
   - Consider creating an installation script for the new ADK

2. **Updating badges**:
   - GitHub star badges use format: `![GitHub stars](https://img.shields.io/github/stars/org/repo?style=for-the-badge&logo=github&logoColor=white)`
   - Repository badges use format: `[![Repo](https://img.shields.io/badge/GitHub-org%2Frepo-blue?style=flat&logo=github)](https://github.com/org/repo)`

3. **Date stamp**:
   - Update the "Last updated" timestamp at the bottom of README.md when making changes

4. **Installation scripts** (planned):
   - When adding installation scripts, organize them by ADK/SDK
   - Scripts should automate setup and deployment of the respective tools
   - Follow shell scripting best practices for Daniel's Ubuntu/KDE environment

## ADK Categories

The collection organizes ADKs into three main categories:

1. **Google ADKs**: Official Google ADKs (Python, Java, Web) and samples
2. **Enterprise Solutions**: IBM Watson, Axway, Volcengine enterprise offerings
3. **Community & Independent**: Community-driven projects like AIDC AI, Arcade AI, Nerve, Cognisphere, etc.
