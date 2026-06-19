# humungit

## Summary

`humungit` is a Git repository orchestrator for polyrepo projects — where one
logical product is divided across several Git repositories. It coordinates
common Git operations across all of a project's repositories from one place.

## Status

Proof of concept

## Purpose

In a polyrepo project, a single product is split into multiple Git repositories
(for example: frontend, backend, shared libraries, and infrastructure). Running
the same Git operations in each repository by hand is repetitive and
error-prone. `humungit` treats the whole set as one workspace so operations can
be run and coordinated across every repository at once.

- **Problem it solves:** the friction of managing a polyrepo product
  repository-by-repository.
- **Who uses it:** developers working on products spread across multiple Git
  repositories.
- **Current state:** proof of concept — example files and working code are being
  added.

## Repository Layout

```
humungit/
├── .gitignore
├── LICENSE     # Apache License 2.0
└── README.md   # this file
```

> Example files and tooling will be added; update this layout as the repository
> grows.

## License

Licensed under the [Apache License 2.0](LICENSE).
