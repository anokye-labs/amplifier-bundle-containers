# Amplifier Bundle Containers

General-purpose container management for Amplifier agents. Spin up isolated Docker/Podman environments with a single tool call — complete with credential forwarding, smart language defaults, dotfiles integration, and user handoff.

## Tech Stack
- YAML and Markdown configuration
- Part of the Amplifier framework ecosystem


## Development
Bundles are declarative configurations. Edit YAML/Markdown files in gents/, ehaviors/, context/, and modules/ directories.

## Structure
This is an Amplifier bundle — a curated collection of agents, behaviors, context, and module configurations that extend Amplifier capabilities.

Key directories:
- `agents/` — Agent profiles and definitions
- `behaviors/` — Behavioral instructions
- `context/` — Context files and references
- `modules/` — Module configurations

## Conventions
- Follow existing YAML/Markdown patterns
- Keep bundle.md as the manifest
- Use descriptive names for agents and behaviors
