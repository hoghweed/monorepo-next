# monorepo-next

A simple monorepo sample reference using [turborepo](https://turborepo.org/), [lernajs](https://github.com/lerna/lerna) and [pnpm](https://pnpm.io/)

- [monorepo-next](#monorepo-next)
  - [Getting started](#getting-started)
  - [What's inside](#whats-inside)
  - [Configuration](#configuration)
    - [Package management - Pnpm](#package-management---pnpm)
    - [Monorepo management - Lerna](#monorepo-management---lerna)
    - [Build system - Turborepo](#build-system---turborepo)
  - [Structure](#structure)
  - [Sample packages](#sample-packages)
  - [Scripts](#scripts)


## Getting started

Managing monorepos has become more than a trending topic but a key argument to consider and to master in managing large and complex projects, or even projects including multiple packages. There is a huge literature all around about techniques, management, pros&cons, benefits and more, a good place to find references could be [Awesome monorepo](https://github.com/korfuri/awesome-monorepo).

Usually managing monorepos in nodejs/javascript is often made using [lernajs](https://github.com/lerna/lerna) althought some alternatives during the time has been implemented, The basic toolchain usually relied on lerna and a package manager between **npm** and **yarn**.  

Althought there are several tools and farmeworks too to manage monorepos for several languages & runtimes, this repository aim to provide a simple *sample reference* for nodejs monorepos considering a powerful and strong toolchain splitting the responsibilities in:

1. Build system
2. Monorepo management
3. Package management

## What's inside

This monorepo configuration makes use of the following packages per feature:

| Feat                | Name            | Package(s)                            | Scope | Notes |
| ------------------- | --------------- | ------------------------------------- | ----- | ----- |
| Build System        | **Turborepo**   | ```turbo```                           |       |       |
| Monorepo Management | **Lerna**       | ```lerna```                           |       |       |
|                     |                 | ```@lerna/project```                  |       |       |
| Package Management  | **Pnpm**        | ```-```                               |       |       |
| Commit rules        | **Committizen** | ```commitizen```                      |       |       |
|                     |                 | ```cz-conventional-changelog```       |       |       |
|                     |                 | ```cz-lerna-changelog```              |       |       |
| Commit linter       | **Commitlint**  | ```@commitlint/cli```                 |       |       |
|                     |                 | ```@commitlint/config-conventional``` |       |       |
|                     |                 | ```@commitlint/core"```               |       |       |
|                     |                 | ```@commitlint/prompt```              |       |       |
| Git hooks           | **Husky**       | ```husky```                           |       |       |

## Configuration

### Package management - Pnpm

1. **Workspaces**
   To enable Pnpm workspaces management 
2. **Package resolution**
### Monorepo management - Lerna

### Build system - Turborepo

Although Turborepo support a [rich and versatile configuration and toolchain for managing monorepos](https://turborepo.org/docs/guides/complimentary-tools), this monorepo is configured for minimal integration alongside to lernajs for **versioning and changelog generation**. 

***At present, a sample [pipeline](https://turborepo.org/docs/features/pipelines) is not yet configured.***

## Structure

## Sample packages
## Scripts
