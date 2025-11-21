# CLAUDE.md

This document provides guidance for Claude AI when working with the Rhodium Standard Repositories project.

## Project Overview

This repository is part of the Rhodium ecosystem, focusing on standard definitions, schemas, and reference implementations.

## Repository Structure

```
rhodium-standard-repositories/
├── CLAUDE.md           # This file - guidance for Claude AI
├── README.md           # Project documentation
├── standards/          # Standard definitions and schemas
├── examples/           # Example implementations
├── docs/              # Additional documentation
└── tests/             # Test suites
```

## Development Guidelines

### Code Style

- Follow consistent formatting and naming conventions
- Use clear, descriptive variable and function names
- Include comments for complex logic
- Maintain backwards compatibility when updating standards

### Documentation

- All standards should be well-documented
- Include examples for each standard
- Keep documentation up-to-date with code changes
- Use clear, concise language

### Version Control

- Write clear, descriptive commit messages
- Use conventional commit format when possible:
  - `feat:` for new features
  - `fix:` for bug fixes
  - `docs:` for documentation changes
  - `refactor:` for code refactoring
  - `test:` for test additions/changes
- Create feature branches for significant changes
- Keep commits focused and atomic

## Working with Standards

### Creating New Standards

1. Research existing similar standards
2. Define clear objectives and scope
3. Create schema/definition files
4. Write comprehensive documentation
5. Provide example implementations
6. Add validation tests

### Updating Existing Standards

1. Review current implementation
2. Document breaking vs non-breaking changes
3. Update version numbers appropriately
4. Maintain backwards compatibility when possible
5. Update all related documentation and examples

## Claude AI Interaction Guidelines

### When Asked to Add Features

1. Understand the existing structure first
2. Check for similar patterns in the codebase
3. Follow established conventions
4. Update documentation alongside code
5. Add tests for new functionality

### When Asked to Fix Issues

1. Reproduce the issue if possible
2. Identify root cause
3. Propose solution before implementing
4. Test thoroughly
5. Document the fix

### When Asked to Explain Code

1. Provide context about the file's purpose
2. Explain the overall structure first
3. Then dive into specific details
4. Use examples to clarify complex concepts
5. Reference related standards/documentation

### When Asked to Review Code

1. Check for adherence to project standards
2. Look for potential issues or bugs
3. Suggest improvements for clarity
4. Verify documentation is complete
5. Ensure tests are adequate

## Testing

- All standards should have validation tests
- Examples should be tested against standards
- Run tests before committing changes
- Add new tests for new functionality

## Communication

### With Users

- Be clear and concise
- Ask clarifying questions when requirements are ambiguous
- Explain technical decisions
- Provide alternatives when appropriate

### In Code

- Use meaningful commit messages
- Comment complex logic
- Document public APIs
- Keep code self-documenting where possible

## Best Practices

1. **Consistency**: Follow existing patterns and conventions
2. **Clarity**: Write code and documentation that is easy to understand
3. **Completeness**: Ensure all changes include tests and documentation
4. **Compatibility**: Consider impact on existing implementations
5. **Quality**: Maintain high standards for code and documentation

## Common Tasks

### Adding a New Standard

```bash
# 1. Create standard definition file
# 2. Write documentation
# 3. Create examples
# 4. Add validation tests
# 5. Update main README if needed
```

### Updating Documentation

```bash
# 1. Locate relevant documentation files
# 2. Make updates
# 3. Ensure consistency across all docs
# 4. Update examples if needed
```

### Running Tests

```bash
# Follow project-specific test commands
# Ensure all tests pass before committing
```

## Resources

- Repository: Hyperpolymath/rhodium-standard-repositories
- Main Branch: (to be determined)
- Issue Tracker: GitHub Issues

## Notes for Claude

- Always check existing patterns before creating new ones
- Prioritize clarity and maintainability
- When in doubt, ask for clarification
- Keep changes focused and well-documented
- Consider the broader Rhodium ecosystem when making decisions

---

*This document should be updated as the project evolves and new conventions are established.*
