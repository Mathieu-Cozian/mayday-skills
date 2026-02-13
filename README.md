# Mayday Skills

Plugin de skills pour créer et gérer la documentation produit Mayday.

## Description

Ce plugin regroupe les skills spécialisés pour produire de la documentation Mayday de qualité professionnelle, en respectant le style guide et les standards du centre d'aide Mayday (documentation.mayday.fr).

## Skills inclus

### 1. mayday-documentation

Créez des articles de documentation Mayday professionnels en français, formatés selon les standards du centre d'aide.

**Cas d'usage :**
- Créer de la documentation pour de nouvelles features après une release produit
- Structurer une feature complexe en plusieurs articles (Introduction + How-to)
- Actualiser la documentation existante

**Déclenchement :**
Le skill se déclenche quand vous mentionnez :
- "documentation Mayday"
- "articles d'aide"
- "centre d'aide"
- "help center"
- "doc produit"
- Ou quand vous fournissez un product brief/success toolkit

**Workflow :**

1. **Collecte des inputs** : Fournissez le product brief, success toolkit, et board d'user stories
2. **Validation du wording** : Le skill extrait et valide avec vous la terminologie exacte à utiliser
3. **Proposition de structure** : Suggestion du nombre d'articles et de leurs titres
4. **Plans détaillés** : Plans multi-niveaux pour chaque article
5. **Rédaction itérative** : Rédaction article par article avec feedback et validation
6. **Fichier consolidé** : Génération d'un markdown avec tous les articles validés

**Style Mayday :**
- ✅ Toujours en français avec vouvoiement
- ✅ Ton chaleureux et accessible
- ✅ Emojis obligatoires dans les titres
- ✅ Dividers (`---`) sous chaque titre
- ✅ Prose fluide plutôt que bullets excessifs
- ✅ Exemples concrets et réalistes

### 2. mayday-release-notes

Générez des release notes Mayday au format exact utilisé sur documentation.mayday.fr.

**Cas d'usage :**
- Créer des notes de release après un déploiement produit
- Documenter les nouveautés, améliorations et correctifs
- Publier les "Nouveautés" sur le centre d'aide

**Déclenchement :**
Le skill se déclenche quand vous mentionnez :
- "release notes"
- "notes de version"
- "nouveautés"
- "changelog"
- Ou quand vous demandez de rédiger une release note Mayday

**Workflow :**

1. **Collecte des informations** : Date de release, liste des features/améliorations/correctifs par produit
2. **Rédaction structurée** : Suivant le template exact Mayday avec sections fixes
3. **Formatage automatique** : Emojis, callouts, sections collapsibles
4. **Prêt à publier** : Document en français prêt pour documentation.mayday.fr

**Structure des release notes :**
- 💫 Titre avec date et headline
- 👋 Introduction chaleureuse + programme
- 🤩 Nouveautés globales
- 📚 Mayday Knowledge (Administrateurs + Conseillers)
- 🎓 Mayday Academy
- 🌐 Mayday Selfcare

## Installation

Pour installer ce plugin dans Cowork :

1. Téléchargez le fichier `mayday-skills.plugin`
2. Dans Cowork, ouvrez les paramètres des plugins
3. Cliquez sur "Install Plugin" et sélectionnez le fichier `.plugin`
4. Redémarrez Cowork si nécessaire

## Utilisation

Une fois installé, les skills sont disponibles automatiquement.

**Pour la documentation :**
```
Je dois créer la documentation pour notre nouvelle feature "contenus réutilisables".
Voici le product brief...
```

**Pour les release notes :**
```
Je dois rédiger la release note pour la mise en production du 13/02/2026.
Voici les nouveautés...
```

Les skills se déclencheront automatiquement et vous guideront à travers le processus.

## Évolutions futures

Ce plugin est conçu pour accueillir d'autres skills Mayday :
- Templates pour différents types de documentation
- Outils d'analyse de documentation existante
- Générateurs de diagrammes et captures d'écran
- Intégrations avec les outils Mayday

## Support

Pour toute question ou suggestion d'amélioration, contactez Mathieu Cozian.

## Version

**Version actuelle :** 0.1.0

**Changelog :**
- v0.1.0 (2026-02-13) : Version initiale avec skills `mayday-documentation` et `mayday-release-notes`
