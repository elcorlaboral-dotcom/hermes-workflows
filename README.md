# Hermes Workflows

Templates de GitHub Actions, pipelines de CI/CD y automaciones.

## Estructura

```
hermes-workflows/
├── .github/
│   └── workflows/     # GitHub Actions workflows
│       ├── ci.yml         # CI basico (lint + test)
│       ├── deploy.yml     # Deploy automation
│       └── sync-skills.yml # Sync skills desde repo
├── scripts/         # Scripts de automation
│   └── deploy.sh
└── templates/       # Templates de workflow
```

## Workflows Disponibles

### CI Basico
Lint y test para cualquier proyecto Python/Node.

### Sync Skills
Sincroniza skills desde `hermes-skills` hacia la configuracion del agente.

### Deploy
Pipeline de deploy con rollback automatico.

## Uso

Copiar el workflow deseado a `.github/workflows/` del proyecto y ajustar variables.
