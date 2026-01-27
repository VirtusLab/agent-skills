---
name: java-best-practices
description: A skill that provides Java coding best practices, style guides, and common pitfalls to avoid.
---

# Java Best Practices

This skill helps you write clean, efficient, and maintainable Java code.

## Usage

When you are writing or refactoring Java code, you can consult this skill for guidance on:
- Naming conventions
- Code structure
- Error handling
- Concurrency
- Performance

## Rules

1. **Naming**: Use `CamelCase` for classes and `camelCase` for variables and methods. Constants should be `UPPER_SNAKE_CASE`.
2. **Immutability**: Prefer immutable objects. Use `final` where applicable.
3. **Optional**: Avoid `null` checks where possible; use `java.util.Optional`.
4. **Exceptions**: Do not swallow exceptions. Log or rethrow them.
5. **Streams**: Use Java Streams API for collection processing where readable.

## Examples

Refer to the `examples/` directory for code snippets demonstrating these practices.
