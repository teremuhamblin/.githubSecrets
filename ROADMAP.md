###### ROADMAP.md >> markdown 
# 🟨 ROADMAP
- `.githubSecrets`
### 🎯 Vision
Créer le dépôt de référence pour comprendre, maîtriser et optimiser le dossier `.github/` dans un environnement professionnel et militaire (dépôt de référence GitHub Enterprise pour documenter, automatiser et optimiser le dossier `.github/`.)

---

## 🧭 Versions
### 🟦 v1.x
>Construction & optimisation
- v1.0.0 : Initialisation
- v1.1.0 : Structure optimisée
- v1.2.0 : Workflows avancés
- v1.3.0 : Sécurité & conformité

### 🟩 v2.x
>Documentation & Enterprise
- v2.0.0 : Documentation PRO
- v2.5.0 : Version Enterprise
- v2.5.1 : Mise à jour essentielle
### 🔧 Corrections & améliorations v2.5.1
1. Correction critique : nom du template PR
- PULLREQUESTTEMPLATE.md → corrigé, normalisé, conforme GitHub  
- Avant : PULLREQUESTTEMPLATE.md (non conforme)  
- Après : PULLREQUESTTEMPLATE.md (format valide)

2. Normalisation interne
- Alignement des noms de fichiers .md  
- Cohérence stricte entre Badges.md, secrets-guide.md, ROADMAP.md  
- Vérification des extensions .yml vs .yaml (GitHub Actions → .yml)

3. Durcissement sécurité
- Ajout de règles mineures dans .gitignore.local  
- Vérification des patterns sensibles dans .gitignore.d/ci.gitignore  
- Renforcement des sections “Sensitive Paths” dans SECURITY.md

4. Documentation
- Mise à jour du CHANGELOG.md avec entrée v2.5.1  
- Ajout d’un bloc “Patch Notes” dans README.md  
- Ajout d’un badge “v2.5.1 Stable Patch” dans Badges.md

5. Workflows
- Correction mineure dans labels-auto.yml (typo sur un label)  
- Ajout d’un if: always() dans docs-build.yml pour éviter les skip intempestifs  
- Durcissement du workflow gitignore-sync.yml (validation pré‑merge)

---

### 🚀 Objectifs long terme
- Documentation GitHub Enterprise
- Workflows auto‑maintenance
- Système de labels intelligents
- Modules `.gitignore.d/` dynamiques
- Site GitHub Pages complet
