# Portfolio

Ce portfolio utilise le template créé par [Hrishikesh Paul](https://github.com/hrishikeshpaul/portfolio-template-v2). Ce template a été conçu pour aider les développeurs à créer rapidement et facilement un site portfolio moderne et attrayant.

## Structure du projet

Le projet est organisé en plusieurs dossiers et fichiers pour faciliter la personnalisation du contenu et la gestion des assets. Voici un aperçu des différents dossiers et leur utilité :

### Dossier `public`
Le dossier `public` contient tous les fichiers statiques de votre site. 
- **assets** : Ce sous-dossier contient toutes les images et fichiers multimédias utilisés sur le site. Vous pouvez remplacer les images ici pour personnaliser votre portfolio.

### Dossier `src`
Le dossier `src` contient le code source principal du site. Il est divisé en plusieurs sous-dossiers :

- **content** : C'est ici que vous trouverez tous les textes et informations de votre portfolio. Modifiez les fichiers dans ce dossier pour personnaliser les sections de votre site (présentation, compétences, projets, etc.).
  
- **pages** : Ce dossier contient les différentes pages du site (par exemple, la page d'accueil, la page des projets, etc.). Chaque fichier représente une page unique du portfolio.

- **shared** : Ce dossier contient des composants réutilisables à travers le site, comme les boutons, les cartes de présentation, ou d'autres éléments visuels qui peuvent être partagés entre plusieurs pages.

- **theme** : Ici, vous pouvez modifier les styles généraux du site. Si vous souhaitez personnaliser l'apparence du portfolio (couleurs, polices, etc.), c'est dans ce dossier que vous pouvez faire les ajustements.

### Dossier `components`
Ce dossier contient tous les composants spécifiques à certaines fonctionnalités du site. Ces composants sont des blocs réutilisables qui facilitent la mise en page et la gestion du contenu.

## Instructions d'utilisation

### Lancer le site en local
1. Installez `yarn` si ce n'est pas déjà fait :
   ```bash
   npm install --global yarn
2. Construisez le projet en local :
   ```bash
   yarn build
3. Démarrez le serveur local :
   ```bash
   yarn start

Le site sera accessible à l'adresse locale indiquée dans la console.

### Déployer le site sur un serveur

1. Assurez-vous d'avoir la dernière version du projet en effectuant:
    ```bash
   yarn build
2. Utilisez un logiciel FTP comme FileZilla pour glisser le contenu du dossier `build` dans le répertoire de votre serveur.

Cela déploiera la version actuelle de votre portfolio sur votre serveur.

