# Standardized Project Entry Template

This document outlines the standardized format for project entries in the awesome-aquarium-tech repository to ensure consistency and completeness of information.

## Standard Project Entry Format

```markdown
### [Project Name](repository_url) ![GitHub stars](star_badge) ![GitHub forks](fork_badge) ![License: LICENSE_TYPE](license_badge)
*Short, clear description of what the project does*

- **Platform**: [e.g., Arduino, Raspberry Pi, ESP32, PC-based, Mobile app]
- **Languages**: [e.g., Arduino/C++, Python, Go, JavaScript]
- **Hardware Required**: [List of essential hardware components]
- **Difficulty**: [Beginner, Intermediate, Advanced]
- **Last Updated**: [Date of last commit or YYYY-MM]
- **Maintenance Status**: [Active, Inactive, Looking for Maintainer, Archived]
- **Key Features**: 
  - Feature 1
  - Feature 2
  - Feature 3
- **Community Activity**: [Number of contributors, recent issues/PRs, forum activity]
- **Documentation Quality**: [Excellent, Good, Basic, Poor]
- **Installation Complexity**: [Simple, Moderate, Complex]
- **Ongoing Costs**: [None, Minimal, Moderate, Significant] (e.g., cloud services, consumables)
- **Pros**: 
  - Advantage 1
  - Advantage 2
- **Cons**:
  - Limitation 1
  - Limitation 2
- **Best For**: [Target audience/use case, e.g., reef tanks, freshwater, nano tanks, beginners]
```

## Example Implementation

```markdown
### [reef-pi](https://github.com/reef-pi/reef-pi) ![GitHub stars](https://img.shields.io/github/stars/reef-pi/reef-pi?style=social) ![GitHub forks](https://img.shields.io/github/forks/reef-pi/reef-pi?style=social) ![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-red.svg)
An open-source reef tank controller based on Raspberry Pi with modular design for affordable DIY automation.

- **Platform**: Raspberry Pi
- **Languages**: Go, Python
- **Hardware Required**: Raspberry Pi, relay board, various sensors, webcam
- **Difficulty**: Intermediate
- **Last Updated**: 2023-06
- **Maintenance Status**: Active
- **Key Features**: 
  - Web-based UI
  - Temperature/pH monitoring and control
  - Dosing pumps automation
  - Auto top-off
  - LED lighting automation
  - Email alerts, charts, and camera integration
- **Community Activity**: 150+ contributors, active issues and PRs
- **Documentation Quality**: Good
- **Installation Complexity**: Moderate
- **Ongoing Costs**: None
- **Pros**: 
  - Comprehensive feature set
  - Active community
- **Cons**:
  - Requires Raspberry Pi knowledge
  - Complex initial setup
- **Best For**: Reef tank enthusiasts looking for comprehensive automation
```

## Implementation Strategy

1. **Phase 1**: Create the standard template and update contribution guidelines
2. **Phase 2**: Update the top 20 most starred/popular projects first
3. **Phase 3**: Gradually update remaining projects over time
4. **Phase 4**: Implement automated checking to ensure new submissions follow the format

## Required Fields

Every project entry must include:
- Platform
- Languages
- Hardware Required
- Difficulty
- Key Features
- License

## Optional but Recommended Fields

- Last Updated
- Maintenance Status
- Community Activity
- Documentation Quality
- Installation Complexity
- Ongoing Costs
- Pros/Cons
- Best For

## Benefits of Standardization

- Consistent user experience when browsing projects
- Easier comparison between similar projects
- More informed decision-making for users
- Clear expectations about project requirements and complexity
- Better assessment of project viability and maintenance