<div align="center">

<img src="https://arborithm.github.io/Effortless/brand/pancake.svg" alt="Effortless" width="160" />

# Effortless

**Pilotez vos projets logiciels avec vos agents IA — sur votre poste.**

Cadrage, backlog, normes de développement, barre de qualité et livraison, de la première idée à la release.

[![Dernière version](https://img.shields.io/github/v/release/ArboRithm/Effortless?label=version&color=1F5A44)](https://github.com/ArboRithm/Effortless/releases/latest) [![Plateformes](https://img.shields.io/badge/macOS%20%C2%B7%20Windows-1F5A44?label=plateformes)](#télécharger) [![Documentation](https://img.shields.io/badge/doc-arborithm.github.io-AD8B4A)](https://arborithm.github.io/Effortless/)

[**Télécharger**](https://github.com/ArboRithm/Effortless/releases/latest) · [**Documentation**](https://arborithm.github.io/Effortless/) · [**Référence MCP**](https://arborithm.github.io/Effortless/reference/mcp/) · [English](README.md)

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://arborithm.github.io/Effortless/captures/fr/dark/dashboard.png" />
  <img src="https://arborithm.github.io/Effortless/captures/fr/light/dashboard.png" alt="Le tableau de bord d'Effortless : le travail en cours, ce qui attend votre décision, les statistiques et les tuiles" width="900" />
</picture>

</div>

## Pourquoi Effortless

Les agents IA écrivent du code vite. Garder un projet cadré, suivi et livrable, c'est autre chose. Effortless vous donne, à vous et à vos agents, une vue partagée et structurée du projet — ce qui est décidé, ce qui est en cours, ce qui suit — et une méthode pour le faire avancer, étape par étape.

Vous décidez. Votre agent exécute. Effortless tient l'ensemble en ordre.

## Points forts

- **Tableau de bord de reprise** — ouvrez un projet et voyez d'un coup d'œil ce qui est en cours, ce qui attend votre décision et ce qui suit. Composez vos propres tuiles.
- **Le cycle OPALE** — chaque story suit les mêmes phases (Observer, Positionner, Articuler, Lancer, Exécuter), gardées par le moteur plutôt que par la mémoire.
- **Backlog et registre des évolutions** — épics, stories et tâches, anomalies et demandes de fonctionnalités, et l'historique de vos sessions de travail.
- **Connaissance** — décisions, questions ouvertes et documents de cadrage, à l'échelle du projet, d'un épic ou d'une story.
- **La qualité mesurée** — dérive entre code et documentation, état du dépôt, normes de développement partagées.
- **Livraison** — version, tag et build, pour le projet entier ou module par module, après un récapitulatif que vous confirmez ; canaux interne et public.
- **Vos agents, branchés** — Effortless déploie son serveur MCP dans vos outils IA et leur fournit un guide à jour de tous les verbes qu'ils peuvent appeler.

## Avec vos agents

Effortless expose son moteur par le [Model Context Protocol](https://modelcontextprotocol.io). Les agents bâtis sur les modèles de pointe en tirent le meilleur parti — **Claude Code**, **Codex** ou **Antigravity**, par exemple ; l'intégration d'**opencode** est en cours.

Déployez-le depuis l'application (**Préférences › MCP & Skills**) ou demandez à votre agent d'appeler `effortless_deploy`. Il suffit ensuite de lui parler :

> *« Démarre un épic pour le module de facturation, avec une première story pour le formulaire de devis. »*

Chaque verbe est décrit dans la [référence MCP](https://arborithm.github.io/Effortless/reference/mcp/), et le [guide « Avec un agent »](https://arborithm.github.io/Effortless/agent/) part de cas d'usage concrets.

### La configuration recommandée

Effortless donne le meilleur de lui-même avec un **agent en ligne de commande — Claude Code, Codex ou Antigravity — lancé depuis la racine de votre projet**, le dossier qui contient `effortless.json` :

```sh
cd ~/Projets/mon-projet
claude        # ou codex, ou la commande de votre agent
```

Le serveur MCP d'Effortless reconnaît votre projet à partir de ce dossier, et votre agent y lit ses instructions. Gardez l'application Effortless ouverte à côté pour voir, en direct, ce que fait l'agent. Le terminal intégré de VS Code, ouvert sur le dossier du projet, est tout aussi confortable. [En savoir plus dans le guide « Avec un agent »](https://arborithm.github.io/Effortless/agent/#travailler-au-mieux-l-agent-ouvert-a-la-racine-du-projet).

Votre code peut vivre dans le projet, dans d'autres dépôts que vous développez, ou dans des **sources partagées** qu'Effortless laisse intactes — ni hook git, ni commit. Choisissez votre mode de travail et l'organisation du code avant de démarrer : [Choisir son organisation](https://arborithm.github.io/Effortless/guide/setup.html).

## Télécharger

| Plateforme | Configuration | Fichier |
|---|---|---|
| **macOS** | Apple Silicon, macOS 10.15 ou plus récent | `Effortless_<version>_standard_aarch64.dmg` |
| **Windows** | x64 | `Effortless_<version>_standard_x64-setup.exe` |
| **Windows** | ARM64 | `Effortless_<version>_standard_arm64-setup.exe` |

Ils sont dans la [dernière release](https://github.com/ArboRithm/Effortless/releases/latest). Effortless vous propose ensuite ses mises à jour — rien ne s'installe sans votre accord.

La version macOS est signée et notarisée par Apple. L'installeur Windows n'est pas encore signé : si SmartScreen vous avertit, choisissez **Informations complémentaires**, puis **Exécuter quand même**.

## Prise en main

1. **Installez** Effortless et créez votre profil au premier lancement.
2. **Ouvrez un projet** — créez-en un avec l'assistant de création, ou reprenez un dépôt existant.
3. **Branchez votre agent** depuis **Préférences › MCP & Skills**.
4. **Ouvrez un terminal à la racine du projet**, lancez-y votre agent, et parlez-lui.

Le [guide de prise en main](https://arborithm.github.io/Effortless/guide/) détaille chaque écran.

## Confidentialité

Effortless tourne sur votre poste. Vos projets restent dans vos dossiers et vous appartiennent. Aucune télémétrie, aucune collecte de données.

## Aide

- **Documentation** — [arborithm.github.io/Effortless](https://arborithm.github.io/Effortless/)
- **Bugs et suggestions** — [ouvrez une issue](https://github.com/ArboRithm/Effortless/issues)
- **Contact** — app@arborithm.fr

---

<sub>Effortless est un logiciel gratuit édité par ArboRithm, distribué selon les termes de son [contrat de licence](LICENSE.md).</sub>
