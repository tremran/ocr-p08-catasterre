# ADR-XXXX : Question pour un problème à résoudre

## Statut

| Etat | date | remarque |
| --- | --- | --- |
| Accepté | 02/09/2026 | --- |

## Contexte et problème

Le cahier des charges indique qu'il faut "encapsuler l'application dans un container docker"

## Critères de décisions

- connaissances actuelles de l'équipe
- ecosysteme mature
- coût

## Options considérées

### Option 1 : Docker

Docker est le standard pour la conteneurisation d'application depuis 2014

**Avantages** :
- cout gratuit
- docker existe depuis 2014
- docker swarm permet d'orchestrer les conteneurs en restant dans le même écosysteme

**Inconvénients** :
- sécurité par défaut moins élevé que podman

### Option 2 : Podman

Podman a été créé par Redhat d'abord comme outils de debug puis a été proposé comme une alternative à Docker

**Avantages** :
- cout gratuit
- podman existe depuis 2019
- sécurité plus élevé par défaut car daemonless

**Inconvénients** :
- pas de connaissances spécifique dans l'équipe

## Décision

**Nous choisissons Docker**

Raisons principales :
1. Une personne déjà compétente dans l'équipe pourra former les autres membres
2. L'environnement est plus mature

## Conséquences

### Positives

- l'application sera scalable
- il sera possible d'aller plus loin dans le même écosystème

### Négatives

- Prévoir un temps de formation de l'équipe
- 
