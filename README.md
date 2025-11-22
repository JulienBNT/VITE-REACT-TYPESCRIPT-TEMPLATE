# Vite React TypeScript Template

Ce projet est un template minimal pour démarrer une application avec Vite, React et TypeScript. Il contient une structure de base, la configuration Vite/TypeScript, et des dépendances courantes (Tailwind, React Router, axios, etc.).

## **Structure Du Projet**

```
vite-react-ts-template
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   ├── callApi/
│   ├── components/
│   ├── constants/
│   │   └── AppName.tsx
│   ├── hooks/
│   ├── pages/
│   │   └── Home.tsx
│   ├── utils/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── postcss.config.js
├── tailwind.config.ts
└── README.md
```

## **Packages Intégrées**

- **Dépendances (runtime):**
  - `react`: ^19.0.0
  - `react-dom`: ^19.0.0
  - `react-router-dom`: ^7.4.0
  - `axios`: ^1.8.4
  - `framer-motion`: ^12.5.0
  - `react-icons`: ^5.5.0
  - `tailwindcss`: ^4.0.15
  - `@tailwindcss/vite`: ^4.0.15
  - `dotenv`: ^16.4.7

- **Dépendances de développement:**
  - `vite`: ^6.2.0
  - `@vitejs/plugin-react`: ^4.3.4
  - `typescript`: ~5.7.2
  - `eslint`: ^9.21.0
  - `@eslint/js`: ^9.21.0
  - `eslint-plugin-react-hooks`: ^5.1.0
  - `eslint-plugin-react-refresh`: ^0.4.19
  - `autoprefixer`: ^10.4.22
  - `globals`: ^15.15.0
  - `@types/react`: ^19.0.10
  - `@types/react-dom`: ^19.0.4
  - `@types/js-cookie`: ^3.0.6
  - `typescript-eslint`: ^8.24.1

> Les versions ci-dessus proviennent du fichier `package.json` du projet. Mettez à jour les versions si vous souhaitez des versions plus récentes.

## **Démarrer Le Projet**

- Prérequis : Node.js (12+ recommandé, préférez la dernière LTS). Assurez-vous que `npm` est disponible.

- Installer les dépendances :

```powershell
npm install
```

- Lancer le serveur de développement :

```powershell
npm run dev
```

- Construire pour la production :

```powershell
npm run build
```

- Prévisualiser le build de production :

```powershell
npm run preview
```

## **Scripts utiles (dans `package.json`)**

- `dev` : démarre Vite en mode développement.
- `build` : lance TypeScript build et `vite build`.
- `preview` : prévisualise le build de production.
- `lint` : lance ESLint sur le projet.

## **Licence**

Ce projet est distribué sous licence MIT.

---

Faites-moi savoir si vous voulez que j'ajoute une section pour les conventions de commit, CI/CD, ou des exemples d'utilisation des pages/components.# Vite React TypeScript Template

This project is a template for building applications using Vite, React, and TypeScript. It provides a basic structure and setup to help you get started quickly.

## Project Structure

```
vite-react-ts-template
├── src
│   ├── main.tsx          # Entry point of the application
│   ├── App.tsx           # Main application component
│   ├── index.css         # Global CSS styles
│   ├── components        # Reusable components
│   │   └── Header.tsx    # Header component
│   ├── pages             # Application pages
│   │   └── Home.tsx      # Home page component
│   ├── hooks             # Custom hooks
│   │   └── useExample.ts  # Example custom hook
│   ├── types             # TypeScript types and interfaces
│   │   └── index.ts      # Type definitions
│   └── vite-env.d.ts     # Vite-specific TypeScript definitions
├── public
│   └── index.html        # Main HTML template
├── package.json          # NPM configuration
├── tsconfig.json         # TypeScript configuration
├── vite.config.ts        # Vite configuration
├── .eslintrc.cjs         # ESLint configuration
├── .gitignore            # Git ignore file
└── README.md             # Project documentation
```

## Getting Started

To get started with this template, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd vite-react-ts-template
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Launch the development server:
   ```
   npm run dev
   ```

Your application should now be running on `http://localhost:3000` (or another port if specified).

## Features

- Fast development with Vite
- TypeScript support for type safety
- React components for building UI
- Custom hooks for reusable logic
- ESLint for code quality

## License

This project is licensed under the MIT License.