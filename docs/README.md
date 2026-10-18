# dgx-spark Documentation

Recipes, performance tweaks, deployment scripts, tips, and documentation for NVIDIA DGX Spark multi-node clusters.

## Documentation Map

```mermaid
flowchart TD
    Start["Start here"] --> Readme["../README.md"]
    Start --> Changelog["../CHANGELOG.md"]
    Start --> Dev["development/roadmap.md"]
    Start --> Adv["advisories/README.md"]
    Adv --> Deps["advisories/dependencies.md"]
    Adv --> Accepted["advisories/accepted.md"]
    Adv --> Resolved["advisories/resolved.md"]
```

## Current Surface

- Early repository scaffold
- Language-specific initialization
- Standard security, contributing, license, and advisory files

## Directory Structure

```text
docs/
├── README.md
├── advisories/
│   ├── README.md
│   ├── dependencies.md
│   ├── accepted.md
│   └── resolved.md
└── development/
    └── roadmap.md
```

## Conventions

- One concept per page.
- Filenames are lowercase and hyphenated.
- Mermaid diagrams are used where they clarify structure or flow.
- Docs should describe implemented behavior; planned work should be labeled.
