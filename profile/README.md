# OpenSecDevOps (OSDO)

**Security-first DevOps framework for CI/CD pipelines.**

OSDO provides composable security actions, reusable workflows, and tooling to embed security into every stage of your software delivery lifecycle.

## 🚀 Quick Start

```yaml
# Add to any GitHub Actions workflow
- uses: opensecdevops/osdo-sast@v2      # Static Analysis
- uses: opensecdevops/osdo-sca@v2       # Dependency Scanning
- uses: opensecdevops/osdo-secrets-scan@v2  # Secret Detection
```

Or use the CLI:
```bash
npm install -g @osdo/cli
osdo init --template basic
```

## 📦 Components

| Component | Description |
|-----------|-------------|
| [osdo](https://github.com/opensecdevops/osdo) | Framework hub — governance, docs, changelog |
| [osdo-cli](https://github.com/opensecdevops/osdo-cli) | CLI for pipeline generation & deployment |
| [osdo-app](https://github.com/opensecdevops/osdo-app) | Web dashboard for pipeline management |
| [osdo-actions](https://github.com/opensecdevops/osdo-actions) | 22 composable security actions |
| [osdo-workflows](https://github.com/opensecdevops/osdo-workflows) | 10 reusable security workflows |

## 🔒 Security Actions

| Action | Purpose |
|--------|---------|
| [osdo-sast](https://github.com/opensecdevops/osdo-sast) | SAST with Semgrep & CodeQL |
| [osdo-sca](https://github.com/opensecdevops/osdo-sca) | SCA with OSV-Scanner & Grype |
| [osdo-secrets-scan](https://github.com/opensecdevops/osdo-secrets-scan) | Secrets detection with Gitleaks |
| [osdo-container-scan](https://github.com/opensecdevops/osdo-container-scan) | Container scanning with Trivy |
| [osdo-iac-scan](https://github.com/opensecdevops/osdo-iac-scan) | IaC scanning with Checkov |
| [osdo-sbom](https://github.com/opensecdevops/osdo-sbom) | SBOM generation (SPDX/CycloneDX) |
| [osdo-sign](https://github.com/opensecdevops/osdo-sign) | Artifact signing with Cosign |

## 📚 Resources

- [Documentation](https://github.com/opensecdevops/documentation)
- [Getting Started](https://github.com/opensecdevops/documentation/blob/main/docs/getting-started/README.md)
- [Contributing](https://github.com/opensecdevops/.github/blob/main/CONTRIBUTING.md)
- [Security Policy](https://github.com/opensecdevops/.github/blob/main/SECURITY.md)

## License

MIT — See individual repositories for details.
