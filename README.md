# Codatta Frontier Standards

Welcome to the **Codatta Frontier Standards** repository! This repository is designed to host standards and schemas for multiple frontiers, providing a foundation for consistent, high-quality data labeling across diverse domains. Codatta’s goal is to facilitate **crowd annotation** and **data curation** efforts that support AI and industry applications through a collaborative and standardized approach.

## 🌐 About Codatta

This repository is part of the Codatta ecosystem, a platform dedicated to connecting **AI developers** with **data creators** to collaboratively train advanced AI. Codatta’s mission is to leverage **collaborative training**, **human-driven labeling**, and **quality assurance mechanisms** to co-train AI models toward Artificial General Intelligence (AGI). Learn more about our mission and other projects at [codatta.io](https://codatta.io).

For questions or to reach out to the maintainers, contact us at **[dev-opensource@codatta.io](mailto:dev-opensource@codatta.io)**.

## 📂 Repository Structure (Example)

Each frontier directory includes:
- **taxonomy-and-schema.md**: Documentation outlining the taxonomy and schema, providing a structured format for annotations and general guidance.
- **taxonomy_vX.json**: A JSON file containing detailed taxonomy definitions for account annotation. This file serves as the ground truth for the actual taxonomy adopted in systems, standardizing categories and attributes across data providers. Any discrepancies between this JSON file and `taxonomy-and-schema.md` should be resolved by referring to the JSON file as the authoritative source.
- **schema_vX.json**: JSON files that define the schema for data annotation. This schema file is considered the authoritative source for schema definitions, taking precedence over `taxonomy-and-schema.md`. If there are any differences between this JSON file and the `.md` file, `schema_vX.json` should be followed.
- **guidelines.md** (optional): Task-specific guidelines for contributors working within each frontier. This file is optional and can be included if additional guidance is necessary for the annotation tasks.

For example:
```
codatta-frontier-standards/ 
├── frontier-<name-of-frontier>/ 
│   ├── taxonomy-and-schema.md 
│   ├── schema_v1.json 
│   └── guidelines.md
```


This structure serves as a guideline for adding new frontiers, ensuring consistency across different domains.

## 🗂 Current Frontiers
The following frontiers have been added to the repository:
- **Crypto Account Annotation**

As new frontiers are introduced, they will be added to this list, expanding Codatta's collaborative annotation ecosystem.

## ➕ Adding a New Frontier
To expand this repository and introduce a new frontier:
1. **Create a new directory** named `frontier-<new-frontier-name>` following the existing structure.
2. **Add a brief entry in the "Current Frontiers" section** of this README to reflect the new frontier.
3. **Refer to the [CONTRIBUTING.md](CONTRIBUTING.md)** file for detailed instructions on adding files, formatting content, and submitting a pull request.

## 🚀 Getting Started
To contribute or propose changes, see our [CONTRIBUTING.md](CONTRIBUTING.md) document for detailed guidelines on making updates to the taxonomy, schema, or guidelines.

## 📜 License
All contributions are subject to the terms outlined in the [LICENSE](LICENSE) file.

Thank you for contributing to the Codatta ecosystem and supporting open, standardized annotation practices!
