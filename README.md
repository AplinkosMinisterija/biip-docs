# BĮIP Project Documentation

Welcome to the official documentation for the BĮIP project.

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/AplinkosMinisterija/biip-docs/badge)](https://securityscorecards.dev/viewer/?platform=github.com&org={AplinkosMinisterija}&repo={biip-docs})
[![License](https://img.shields.io/github/license/AplinkosMinisterija/biip-docs)](https://github.com/AplinkosMinisterija/biip-docs/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/AplinkosMinisterija/biip-docs)](https://github.com/AplinkosMinisterija/biip-docs/issues)
[![GitHub stars](https://img.shields.io/github/stars/AplinkosMinisterija/biip-docs)](https://github.com/AplinkosMinisterija/biip-docs/stargazers)

## Table of Contents

- [Getting Started](#getting-started)
    - [Installation](#installation)
    - [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

If you're new to the BĮIP documentation, here's how to get started:

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AplinkosMinisterija/biip-docs.git
   ```

2. Ensure you have Rust and Cargo installed. You can follow the instructions on
   the [Rust installation page](https://www.rust-lang.org/tools/install).

3. Install `mdbook` and required dependencies:
   ```bash
   cargo install mdbook mdbook-mermaid mdbook-linkcheck
   ```

### Usage

To use the documentation:

1. Preview documentation (additional commands in `package.json`):
   ```bash
   mdbook serve
   ```

## Deployment

### Preview

Each commit automatically creates a new preview environment on pull requests to the `main` branch.

## Contributing

We welcome contributions! If you encounter issues or have suggestions for improvements, feel free to open
an issue or submit a pull request. For more information, please refer to
the [contribution guidelines](https://github.com/AplinkosMinisterija/.github/blob/main/CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](./LICENSE).
