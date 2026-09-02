# ADR-XXXX : Question pour un problème à résoudre

## Statut

| Etat | date | remarque |
| --- | --- | --- |
| Accepté | 02/09/2026 | --- |

## Contexte et problème

Le cahier des charges indique qu'il faut mettre en place une pipeline d'intégration continue afin de "fiabiliser l'organisation du développement"

## Critères de décisions

- connaissances actuelles de l'équipe
- maturité de l'outils
- coût

## Options considérées

- [comparatif sur northflank.com](https://northflank.com/blog/github-actions-alternatives#quick-comparison-of-github-actions-alternatives)
- [discussion reddit](https://www.reddit.com/r/devops/comments/1ph3dca/looking_to_migrate_company_off_github_whats_the/)

### Option 1 : Github Actions

Proposé par github et largement adopté

**Avantages** :
- Connaissance d'un membre de l'équipe
- système mature
- l'écosystème github est plus mature autour de git

**Inconvénients** :
- coûts non maitrisé si la pipeline devien complexe

### Option 1 : Gitlab CI/CD

Proposé par gitlab et est l'alternative la plus mature

**Avantages** :
- couts moindre à l'utilisation

**Inconvénients** :
- coûts d'abonnement plus important
- fonctionnalités git moins évoluées


## Décision

**Nous choisissons github actions**

Raisons principales :
1. Connaissance d'un membre de l'équipe
2. l'environnement global de github est plus mature et plus fonctionnel

## Conséquences

### Positives

- Connaissance de l'équipe

### Négatives

- Il faudra faire attention à la maitrise des coûts 
