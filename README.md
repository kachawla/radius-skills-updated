# Radius Skills

Reusable AI agent skills for [Radius](https://github.com/radius-project/radius). These skills teach AI coding agents how to work with Radius applications, from modeling and deployment to cloud-native workflows.

## Install

```
npx skills add kachawla/radius-skills-updated
```

## Available Skills

| Skill | Description |
|---|---|
| [app-modeling](skills/app-modeling/SKILL.md) | Analyze a source code repository and generate a Radius application definition (`.radius/app.bicep`) |

## How It Works

Each skill is a self-contained set of instructions that an AI agent reads and follows. Skills include reference files with architecture patterns, naming conventions, and validation rules to produce consistent, high-quality output.

## Repository Layout

```
skills/
└── app-modeling/
    ├── SKILL.md              # Main skill instructions
    └── references/           # Supporting reference files
        ├── architecture-patterns.md
        ├── bicep-structure-rules.md
        ├── connection-conventions.md
        ├── naming-conventions.md
        ├── secrets-handling.md
        └── todo-list-app-example.md
```

## License

This project is licensed under the [Apache License 2.0](LICENSE).
