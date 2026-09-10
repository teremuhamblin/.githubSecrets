###### README.md >> markdown

[![CI](https://github.com/teremuhamblin/.githubSecrets/actions/workflows/ci.yml/badge.svg)](https://github.com/teremuhamblin/.githubSecrets/actions/workflows/ci.yml)

# .githubSecrets
- EXPLIQUE, DÉMONTRE et UTILISE tout ce que **GitHub** cache dans ***.github/***

---

### 🟩 Mise à jour **~/.github**
   - Projet ***.githubSecrets***

[![pages-build-deployment](https://github.com/teremuhamblin/.githubSecrets/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/teremuhamblin/.githubSecrets/actions/workflows/pages/pages-build-deployment)

Bienvenue dans .githubSecrets, un dépôt dédié à l'exploration complète du dossier .github/ et de tous ses mécanismes internes.

- Ce projet dévoile :
```md
   - les templates d’issues
   - les templates de pull requests
   - les workflows GitHub Actions
   - les CODEOWNERS
   - la politique de sécurité
   - le financement GitHub Sponsors
   - Dependabot
   - Documentation Github Pages dans docs/
   - et toutes les fonctionnalités cachées du dossier .github/
```

### 🟦 Structure complète 
```text
.githubSecrets/
├── README.md
├── .gitignore
├── .gitignore.local
├── .gitgnore.d/
    ├── .gitkeep
├── secrets-guide.md
└── docs/
    ├── Site docs
└── .github/
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.yml
    │   └── feature_request.yml
    ├── workflows/
    │   └── ci.yml
    ├── PULL_REQUEST_TEMPLATE.md
    ├── CODEOWNERS
    ├── SECURITY.md
    ├── CONTRIBUTING.md
    ├── FUNDING.yml
    └── dependabot.yml
```

---

###### Structure ***.gitignore*** / ***.gitignore.local*** / ***.gitignore.d/***.
### 🪖 Gestion avancée des fichiers
- .gitignore
      - Ce projet utilise une architecture modulaire pour contrôler précisément ce qui doit être ignoré dans l’environnement ***UserLAnd / Termux / multi‑langages***.  

>Elle repose sur trois niveaux complémentaires :
```md
1. .gitignore
- Fichier principal (niveau global)
   - Contient les règles officielles du dépôt.  
   - Compatible GitHub, CI/CD, Python, Node, Docker, Docs, Termux.  
   - Sert de source de vérité pour tous les environnements.  
   - Mis à jour manuellement ou via scripts (fusion des modules).

2. .gitignore.local
- Profil de l’appareil (non versionné)
   - Spécifique à ton Samsung A7 / Termux / UserLAnd.  
   - Contient les règles personnelles : chemins locaux, caches, fichiers temporaires de l’appareil.  
   - Jamais commit, il reste uniquement sur ta machine.  
   - Peut être fusionné dans le .gitignore principal via un script si nécessaire.

3. /.gitignore.d/
- Modules tactiques (niveau modulaire)
- Dossier contenant des fichiers
.gitignore spécialisés :  
  - python.gitignore  
  - node.gitignore  
  - docs.gitignore  
  - ci.gitignore  
  - military.gitignore (ops, scanners, intel…)  
   - Permet une construction progressive du .gitignore principal.  
   - Idéal pour les projets multi‑langages ou évolutifs.  
   - Peut être fusionné automatiquement via un script (ex : cat .gitignore.d/*.gitignore >> .gitignore).
```

---

### 🎯 Objectif de cette architecture
- Séparer les règles globales, les règles locales, et les modules spécialisés.  
- Faciliter la maintenance du dépôt.  
- Éviter les doublons et les conflits.  
- Garder un contrôle militaire sur les fichiers ignorés selon l’environnement.

---

```md
.githubSecrets est un guide complet pour maîtriser GitHub.
```
