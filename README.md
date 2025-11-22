<h1 align="center">Vite React TypeScript Template</h1>
<p align="center">
   <a href="https://vitejs.dev">
      <img alt="Vite" src="https://img.shields.io/badge/Vite-%234646ff?style=for-the-badge&logo=vite&logoColor=white" />
   </a>
   <a href="https://reactjs.org">
      <img alt="React" src="https://img.shields.io/badge/React-%2361DAFB?style=for-the-badge&logo=react&logoColor=white" />
   </a>
   <a href="https://tailwindcss.com">
      <img alt="Tailwind CSS" src="https://img.shields.io/badge/TailwindCSS-%2338B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
   </a>
   <a href="https://www.typescriptlang.org">
      <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-%23007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
   </a>
</p>

<p align="center">
   Template basé sur Vite • React • Tailwind CSS • TypeScript
</p>

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

## **Packages**

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