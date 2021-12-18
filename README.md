# Advantages vs. DisAdvantages for Monorepos

## DisAdvantages

- No way to restrict access only to some parts of the application
- Poor git performance when working on large-scale projects
- Git log will be a mess!
- Higher build time and more complex CI/CD
- What if we want to use other programming lauguages? Go? C++? Java?

## Advantages

- "One repo to rule them all"
- Easily implement/refactor global features with atomic commits.
- Re-use code with shared packages while still keeping them isolated.
