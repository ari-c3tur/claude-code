# Label Organization Guide

This document provides a comprehensive guide to label organization in the Claude Code repository. Proper labeling helps with issue triage, visual organization, and contributor onboarding.

## Label Categories

Labels are organized into the following categories for consistent usage:

| Label Name | Category | Description |
|------------|----------|-------------|
| bug | Issue Type | Something isn't working |
| duplicate | Issue Type | This issue or pull request already exists |
| enhancement | Issue Type | New feature or request |
| question | Issue Type | Further information is requested |
| documentation | Issue Type | Improvements or additions to documentation |
| platform:macos | Platform | Issues specific to macOS platform |
| platform:linux | Platform | Issues specific to Linux platform |
| platform:windows | Platform | Issues specific to Windows platform |
| area:core | Area | Core functionality and architecture |
| area:tools | Area | Tool functionality and features |
| area:model | Area | Model-related functionality |
| area:ide | Area | IDE integration features |
| area:tui | Area | Terminal UI and interface |
| area:security | Area | Security-related features and concerns |
| area:mcp | Area | Model Context Protocol functionality |
| area:packaging | Area | Packaging and distribution |
| area:auth | Area | Authentication and authorization |
| area:api | Area | API-related functionality |
| has repro | Status | Issue has reproduction steps provided |
| memory | Performance | Related to memory usage or management |
| perf:memory | Performance | Performance issues related to memory |

## Usage Guidelines

### Issue Type Labels
- **bug**: Use for any functionality that is not working as expected
- **enhancement**: Use for new feature requests or improvements to existing functionality
- **question**: Use when seeking clarification or additional information
- **documentation**: Use for documentation improvements, corrections, or additions
- **duplicate**: Use when an issue or pull request duplicates an existing one

### Platform Labels
- **platform:macos**: Apply to issues specific to macOS operating system
- **platform:linux**: Apply to issues specific to Linux distributions
- **platform:windows**: Apply to issues specific to Windows operating system

### Area Labels
- **area:core**: For core system architecture, foundational components, and cross-cutting concerns
- **area:tools**: For specific tool functionality (Write, Edit, Bash, etc.)
- **area:model**: For issues related to model interactions, prompts, or AI behavior
- **area:ide**: For IDE integration features and plugins
- **area:tui**: For terminal user interface, display, and interactive elements
- **area:security**: For security features, vulnerabilities, and permission systems
- **area:mcp**: For Model Context Protocol servers, clients, and integrations
- **area:packaging**: For installation, distribution, and packaging concerns
- **area:auth**: For authentication, authorization, and API key management
- **area:api**: For API interactions, endpoints, and external integrations

### Status Labels
- **has repro**: Apply when reproduction steps are provided, making the issue easier to debug

### Performance Labels
- **memory**: Use for memory leaks, high memory usage, or memory management issues
- **perf:memory**: Specifically for performance issues related to memory allocation or garbage collection

### Best Practices
1. **Multiple Labels**: Issues can have multiple labels from different categories (e.g., `bug`, `platform:macos`, `area:tools`)
2. **Primary Category**: Always include at least one Issue Type label
3. **Platform Specificity**: Include platform labels only when the issue is platform-specific
4. **Area Precision**: Use the most specific area label that applies
5. **Reproduction**: Add `has repro` when reproduction steps are available to help maintainers

### Label Application Workflow
1. New issues should receive at least one Issue Type label
2. Add platform labels if the issue is platform-specific
3. Add one or more area labels to categorize the functional area
4. Add `has repro` if reproduction steps are included
5. Add performance labels if applicable

This label system enables efficient filtering, triage, and visualization of repository issues.