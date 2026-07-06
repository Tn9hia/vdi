# CLAUDE.md

## Target

- Target for this project is to create a step by step guide to build VDI system in the airgap environment with security, production in mind

## Techstack

- VMware vSphere 8 
- vSAN ESA
- Connection to the internet is limited throught proxy

## Rule

- Language: Vietnamese
- Technical word should be in English
- Do not use icon
- No numbering for steps

### Template

```
# Name the tools/application to install
- Short decription
- short purpose of this components in the system
# Prerequisites
- Prerequisites to install (included system requirement, resource planing, components)
# Diagram (optional)
Diagram to visualize the component need to install, and their relationships in mermaid.(Ex: install Squid need to have diagram show clinet go through squid to connect the internet)
---
# Installation

Step by step to install, short description if necessary, and any prerequisites.
```

- Treat each each tech stack as a small components of the overall system. When complete all components = the system is fully installed.
- Installation steps should have description and clear instructions.
