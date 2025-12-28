# Alchira Tutorial

## End-User License Agreement (EULA)

By using this software, you agree to the terms and conditions outlined in the [End-User License Agreement](https://github.com/alchira/agreements/license).
For details, please read the full EULA document provided in this repository.

---

## What is Alchira?

![Preview](./assets/preview.png)

Alchira is a constraint-driven CSS build-time kernel designed to be the foundational engine for building custom CSS frameworks. Rather than being a traditional CSS framework loaded with predefined classes, Alchira provides a powerful structural abstraction that preserves the full flexibility of vanilla CSS while adding native dependency management and modular composition. It works seamlessly across any text-based environment, is framework agnostic, and integrates effortlessly with existing design systems and token libraries.

By focusing on modular style blocks, logical constraint-based syntax, and automatic cascading and dependency resolution, Alchira empowers teams to build maintainable, predictable, and optimized stylesheets tailored precisely to their project needs.

## Why Use Alchira?

Alchira strikes a careful balance between raw flexibility and developer experience without sacrificing either. It:

- Enables fully customizable framework creation with minimal initial setup, reducing context switching between CSS and HTML.
- Resolves style dependencies and cascading order natively at build time, minimizing manual overrides and conflicts.
- Supports reusable modular blocks that grow with your application, eliminating brittle selectors and tangled overrides.
- Delivers production-ready optimized builds with debloated, dependency-aware styles for faster and cleaner deployment.
- Acts as a robust kernel platform, giving you complete control and transparency while providing structural best practices and optimization out of the box.

In short, Alchira is the essential, extensible core upon which efficient, scalable, and maintainable CSS frameworks can be built—offering the power and performance that modern design systems and large-scale projects demand.

Training and reference matririal for Alchira.

[Continue Locally](vscode://vscode.dev/clone?url=https://github.com/yshelldev/alchira-tutorial)

---

## Initialize

### Install Packages

- This repository is initilized with official minimal spin [Alchira Scaffold](https://www.npmjs.com/package/scaffold), Which also installs [Alchira Central](https://www.npmjs.com/package/alchira) along with it.

```sh
  # Install Alchira Scaffold and Alchira Central(dependency).
  npm install @alchira/scaffold 
  
  # Reconfigure Alchira Central with the installed flavour.
  alchira init @alchira/scaffold 
```

> If you want to go flavourless install [Alchira Central](https://www.npmjs.com/package/alchira), and start from scratch.

### Install Extension In your Editor.

Available in:

- [Visual studio marketplace](https://marketplace.visualstudio.com/items?itemName=yshelldev.alchira-client)
- [Open VSX Registary](https://open-vsx.org/extension/yshelldev/alchira-client)

After installation go through [tutorial](./tutorial/extention.md), to get familiar with shortcuts and features.

## Navigation

- [Go through setup directory.](./SETUP.md)