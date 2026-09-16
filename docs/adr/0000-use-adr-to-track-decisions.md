# ADR-0000 : Quel format d'ADR pour justifier les décisions

## Statut

Accepted

## Contexte et problème

Nous avons besoin de tracer les décisions lourdes prises pendant le projet. 

## Critères de décisions

* tracabilité
* simplicité

## Options considérées

### Option 1 : Template original ADR

[Michael Nygard’s template](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) – Le format original des “ADR”

**Avantages** :
- Format simple

**Inconvénients** :
- tracabilité limitée

### Option 2 : The Markdown Architectural Decision Records

[MADR](https://adr.github.io/madr/) 4.0.0 – The Markdown Architectural Decision Records

**Avantages** :
- tracabilité accrue

**Inconvénients** :
- Format un peu plus lourd

### Option 3 : custom format

**Avantages** :
- tracabilité accrue
- simplicité souhaitée et évolution possible

**Inconvénients** :
- Format non standard

## Décision

**Nous choisissons un custom format** pour toutes les nouvelles ADR.

Raisons principales :
1. La tracabilité ajouté surpasse la complexité apportée

## Conséquences

### Positives

- un outil simple pour suivre les décisions importantes
- une tracabilité accrue

### Négatives

- format à définir
