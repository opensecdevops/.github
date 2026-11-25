[English](https://github.com/opensecdevops/.github/blob/main/profile/README.md) | Español

# OpenSecDevOps (OSDO)

**Framework DevSecOps centrado en la seguridad para pipelines de CI/CD.**

OSDO ofrece acciones de seguridad componibles, workflows reutilizables y herramientas para integrar la seguridad en cada etapa del ciclo de vida de entrega de software.

## 🚀 Inicio rápido

```yaml
# Añadir a cualquier workflow de GitHub Actions
- uses: opensecdevops/osdo-sast@v2      # Análisis estático (SAST)
- uses: opensecdevops/osdo-sca@v2       # Análisis de dependencias (SCA)
- uses: opensecdevops/osdo-secrets-scan@v2  # Detección de secretos
```

O usa la CLI:
```bash
npm install -g @osdo/cli
osdo init --template basic
```

## 📦 Componentes

| Componente | Descripción |
|-----------|-------------|
| [osdo](https://github.com/opensecdevops/osdo) | Hub del framework — gobernanza, documentación, changelog |
| [osdo-cli](https://github.com/opensecdevops/osdo-cli) | CLI para generar y desplegar pipelines |
| [osdo-app](https://github.com/opensecdevops/osdo-app) | Dashboard web para gestionar pipelines |
| [osdo-actions](https://github.com/opensecdevops/osdo-actions) | 22 acciones de seguridad componibles |
| [osdo-workflows](https://github.com/opensecdevops/osdo-workflows) | 10 workflows de seguridad reutilizables |

## 🔒 Acciones de seguridad

| Acción | Propósito |
|--------|-----------|
| [osdo-sast](https://github.com/opensecdevops/osdo-sast) | SAST con Semgrep y CodeQL |
| [osdo-sca](https://github.com/opensecdevops/osdo-sca) | SCA con OSV-Scanner y Grype |
| [osdo-secrets-scan](https://github.com/opensecdevops/osdo-secrets-scan) | Detección de secretos con Gitleaks |
| [osdo-container-scan](https://github.com/opensecdevops/osdo-container-scan) | Escaneo de contenedores con Trivy |
| [osdo-iac-scan](https://github.com/opensecdevops/osdo-iac-scan) | Escaneo de IaC con Checkov |
| [osdo-sbom](https://github.com/opensecdevops/osdo-sbom) | Generación de SBOM (SPDX/CycloneDX) |
| [osdo-sign](https://github.com/opensecdevops/osdo-sign) | Firma de artefactos con Cosign |

## 📚 Recursos

- [Documentación](https://github.com/opensecdevops/documentation)
- [Primeros pasos](https://github.com/opensecdevops/documentation/blob/main/docs/getting-started/README.md)
- [Contribuir](https://github.com/opensecdevops/.github/blob/main/CONTRIBUTING.md)
- [Política de seguridad](https://github.com/opensecdevops/.github/blob/main/SECURITY.md)

## Mantenedores

OSDO (Open SecDevOps) fue creado y es mantenido por [Spectertj](https://github.com/Spectertj), que es su creador y mantenedor.

## Ecosistema

- HOLOS — kit de herramientas de ingeniería agéntica de código abierto, del mismo creador, desarrollado y publicado junto con OSDO

## Licencia

Apache-2.0 salvo que un repositorio indique otra cosa (algunos, p. ej. osdo-actions, son MIT). Consulta el LICENSE de cada repositorio.
