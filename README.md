# TP UI Component Libraries — projet de secours : Utilitaire (Tailwind CSS v4)

IMT Atlantique · 1re année alternance · cours « UI Component Libraries »

## À quoi sert ce dépôt

C'est le projet de départ `tp-ui-libs-vite`, avec **Tailwind CSS v4 déjà installé et configuré**.

Il sert de **secours** : votre enseignant vous le donne si l'installation de votre bibliothèque bloque encore au bout de 15 minutes. Vous pouvez ainsi passer directement au composant.

## Démarrer

Prérequis : Node.js 22 ou 24 (versions LTS), npm et git.

```bash
git clone https://github.com/Orodan/tp-ui-libs-vite-utilitaire
cd tp-ui-libs-vite-utilitaire
npm install
npm run dev        # http://localhost:5173
```

## Ce qui a déjà été fait

- `npm install tailwindcss @tailwindcss/vite`
- Dans `vite.config.js` : ajout du plugin `tailwindcss()`.
- Dans `src/style.css` : `@import "tailwindcss";`. Ajoutez vos couleurs et polices avec `@theme` (un exemple est en commentaire).

Prenez une minute pour regarder ces fichiers : c'est exactement ce que vous auriez dû faire vous-mêmes.

```
├── index.html          ← le contenu de la FAQ, à structurer
├── vite.config.js      ← plugin Tailwind
├── src/
│   ├── main.js
│   └── style.css       ← @import "tailwindcss" et vos @theme
├── public/assets/      ← images et polices
├── design/             ← maquettes
└── style-guide.md      ← couleurs, polices, tailles
```

## À vous de jouer

Construire l'accordéon FAQ avec Tailwind CSS v4, d'après les maquettes de `design/` et les couleurs et polices de `style-guide.md`.

Documentation officielle : <https://tailwindcss.com/docs>

## Ce qui est attendu

**Obligatoire**

- Fidèle à la maquette et responsive.
- Utilisable au clavier : Tab pour circuler, Entrée et Espace pour ouvrir et fermer.
- Le focus est visible sur chaque question.

**Bonus**

- Un seul panneau ouvert à la fois.

## La restitution

3 à 4 minutes par groupe :

1. Démo de votre accordéon.
2. Un test au clavier, en direct.
3. Votre choix : pourquoi cette techno, ou ce que vous auriez choisi.
4. Un avantage et une douleur de votre approche.

Puisque vous êtes passés par ce projet de secours, dites aussi **ce qui a bloqué pendant votre installation** : c'est une information précieuse pour la synthèse.

## Assistants IA

Les fichiers `AGENTS.md` et `CLAUDE.md` viennent de Frontend Mentor. La plupart des assistants IA les lisent automatiquement : ils vous guideront par questions et indices, sans écrire la solution à votre place.

## Crédits

Challenge par [Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Police Work Sans sous licence SIL Open Font License (`public/assets/fonts/OFL.txt`).
