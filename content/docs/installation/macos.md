---
title: "MacOS"
description: "Installation de Mozart2 sur MacOS."
lead: "Installation de Mozart2 sur MacOS."
date: 2020-18-02T10:34:57+00:00
lastmod: 2020-18-02T10:34:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "Installation"
weight: 3
toc: true
---

## Prérequis

### Homebrew
Rendez-vous sur le site de [Homebrew](https://brew.sh/) et suivez les instructions d'installation disponibles sur la page d'accueil du site.

### Emacs
N'importe quelle version d'Emacs fera l'affaire cependant le professeur recommande celle-ci.

#### Aquamacs
```shell
brew install --cask aquamacs
```

## Installation

Clonez le répertoire qui contient Mozart2 en tapant la commande suivante dans votre terminal:
```shell
brew tap dskecse/tap
```
Installez Mozart2 avec la commande suivante:
```shell
brew install --cask mozart2
```
Une application se nommant Mozart2 devrait à présent se trouver dans votre dossier Applications.

Si MacOs vous empêche de la lancer, ouvrez Finder et cliquez droit sur l'application puis cliquez sur ouvrir

Une version d'Emacs configurée pour Mozart2 devrait alors s'ouvrir. Amusez-vous bien!
