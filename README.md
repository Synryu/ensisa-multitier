# Exemple pour les supports de cours avec Marp

**Des supports versionnés, distribuables et hébergés par GitHub.**

- Rédaction du contenu en Markdown [Marp].
- Versionnage assuré par Git.
- Hébergement via déploiement automatique dans les [gitHub pages].

[marp]: https://marp.app/
[github pages]: https://pages.github.com/

## Voir le support publié

<p align="center">
  <a href="https://synryu.github.io/ensisa-multitier"><img src="https://synryu.github.io/ensisa-multitier/og-image.jpg" width="500" /></a>
</p>


- <img src="https://icongr.am/octicons/mark-github.svg" width="24" height="24" valign="bottom" /> **[GitHub Pages]**: https://synryu.github.io/ensisa-multitier

## Usage

Le déploiement des pages est déclenché via un merge sur **master**.

### <img src="https://icongr.am/octicons/mark-github.svg" width="24" height="24" valign="bottom" /> [GitHub Pages]

## Comment ajouter du contenu

La documentation officielle de [Marpit Markdown](https://marpit.marp.app/markdown) est le point départ.

L'installation des dépendances n'est utile que pour générer le html en local.

Sinon, modifier les fichiers md contenu dans les **[`Sources`](./Sources)**!

### Aperçu

L'extension **[Marp for VS Code]** est tout ce qu'il pour avoir un aperçu dynamique directement dans VS Code..

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode">
    <img src="https://raw.githubusercontent.com/marp-team/marp-vscode/master/docs/screenshot.png" width="500" />
  </a>
</p>

### Assets et thèmes

- le dossier `assets` contient les éléments externes utilisés dans les slides. (comme les images par exemple)
- le dossier `thèmes` contient les [thèmes CSS personnalisés](https://marpit.marp.app/theme-css). Pour appliquer un thème, modifier la directive globale `theme`.

### Build local via CLI

```bash
npm run build
```

Les fichiers générés iront dans le dossier `public`.

#### Build partiel

```bash
npm run deck      # Génère l'HTML statique dans public/index.html
npm run og-image  # Génère l'image pour Open Graph dans public/og-image.jpg
```

## LICENSE

[WTFPL](/LICENSE)
