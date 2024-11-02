# 🤝 Contributing to Codatta Frontier Standards

Thank you for your interest in contributing! This document provides guidelines for collaborating effectively on annotation standards within this repository.

## 📝 Contribution Workflow

1. **Clone the Repository**: Start by cloning the repo and creating a new branch from `develop`.
2. **Branch Naming**: Follow naming conventions like `feature/<frontier>-<description>` or `fix/<frontier>-<description>`.
3. **Documentation and Schema Changes**: Update `taxonomy-and-schema.md` for documentation changes and add or edit JSON schema files as needed.

### ➕ Adding a New Frontier

To add a new frontier, follow these steps:

1. **Create a Directory**: Create a new directory named `frontier-<frontier-name>` in the root, following the naming convention of existing frontier directories.
2. **Add Required Files**: Each frontier directory should contain the following files:
   - `taxonomy-and-schema.md`: Documentation outlining the taxonomy and schema.
   - `schema_v1.json`: JSON file that defines the schema for the new frontier.
   - `guidelines.md`: Task-specific guidelines for contributors working within the frontier.
3. **Update README**: 
   - Add a brief entry in the "Current Frontiers" section of the README to reflect the new frontier.
   - Include a one-line description to keep documentation consistent.
4. **Submit a Pull Request**: Once your changes are ready, open a pull request to `develop` with a description of the new frontier and a summary of any notable features.

## 🛠 Best Practices

- **Human-Driven Labeling**: Ensure that annotations are assigned meaningfully, applying human intelligence to achieve accurate categorizations.
- **Data Curation**: Maintain high standards for data quality and relevance, as data curation is critical to creating valuable training data for AI.
- **Collaborative Training and Quality Assurance**: All data added should go through quality assurance processes, ensuring reliable and consistent standards.

For questions or assistance, please contact the maintainers at **[dev-opensource@codatta.io](mailto:dev-opensource@codatta.io)**.

Thank you for contributing to Codatta’s collaborative approach to **data empowerment** and open standards!
