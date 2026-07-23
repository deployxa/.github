# Contributing to Deployxa

Thank you for your interest in contributing to **Deployxa**! We are building an open-source, AI-native cloud platform to eliminate infrastructure friction for software teams worldwide.

Whether you are fixing a typo in documentation, reporting a bug, writing a framework starter template, or submitting a feature pull request, your contributions are invaluable.

---

## Code of Conduct

All contributors and community members are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before participating.

---

## How to Contribute

### 1. Reporting Bugs
- Search existing [GitHub Issues](https://github.com/deployxa/deployxa-engine/issues) to avoid duplicates.
- Open a new issue using our **Bug Report** template.
- Include OS version, Node.js version, `@deployxa/cli` version, command executed, and expected vs actual output.

### 2. Requesting Features
- Open an issue using our **Feature Request** template or join [GitHub Discussions](https://github.com/deployxa/deployxa-engine/discussions).
- Explain the problem, proposed solution, and alternative approaches considered.

### 3. Submitting Pull Requests
1. Fork the repository you want to contribute to (e.g. `deployxa-engine`, `deployxa-dashboard`, `@deployxa/cli`).
2. Create a topic branch (`git checkout -b feat/my-awesome-feature`).
3. Ensure all tests pass (`npm test` or `go test ./...`).
4. Commit your changes with clear, semantic commit messages (`feat: add custom domain validation`, `fix: resolve container port binding error`).
5. Push to your fork and submit a Pull Request targeting the `main` branch.

---

## Development Setup

### CLI (`@deployxa/cli`)
```bash
git clone https://github.com/deployxa/deployxa-cli.git
cd deployxa-cli
npm install
npm run build
npm link
```

### Dashboard (`deployxa-dashboard`)
```bash
git clone https://github.com/deployxa/deployxa-dashboard.git
cd deployxa-dashboard
npm install
npm run dev
```

---

## Questions & Support

Have questions? Join our active community on [Discord](https://discord.gg/deployxa) or start a discussion on [GitHub Discussions](https://github.com/deployxa/deployxa-engine/discussions).
