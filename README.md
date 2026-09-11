# Huddle landing page with curved sections — version Sass (Frontend Mentor)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-SCSS-CC6699?logo=sass&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)
![Frontend Mentor](https://img.shields.io/badge/Frontend_Mentor-Challenge-3F54A3)

🔗 **Démo en ligne** : <https://huddle-landing-sass.vercel.app>
📦 **Code source** : <https://github.com/Georginio-prod/Huddle-landing-page>
🎯 **Défi** : [Huddle landing page with curved sections](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2) (niveau *Junior*)

---

## 📌 Présentation

Landing page **Huddle** intégrée en **Sass (SCSS)**. Version jumelle de [Huddle-landing-](https://github.com/Georginio-prod/Huddle-landing-) (Tailwind). Sections aux bords incurvés, statistiques, blocs alternés et footer avec newsletter.

Réalisé en **HTML sémantique + Sass**, servi par **Vite** (rechargement à chaud et build optimisé),
sans framework JavaScript : l'objectif est la maîtrise du CSS et du responsive.

## ✨ Fonctionnalités

- Héros, statistiques, 3 sections alternées séparées par des courbes SVG, CTA, footer.
- Feuille `sass/style.scss` avec variables (Poppins / Open Sans, palette rose / cyan).
- Formulaire newsletter avec message d'erreur.

## 🛠️ Stack

| Élément | Détail |
|---|---|
| Structure | HTML5 sémantique |
| Styles | Sass / SCSS compilé par Vite |
| Outils | Vite 5 (dev server + build) |
| Maquette | Frontend Mentor — mobile 375px / desktop 1440px |

## 📁 Structure

```
Huddle-landing-page/
├── index.html              # Toute la structure de la page
├── sass/style.scss         # Feuille de style SCSS (variables, imbrication, media queries)
├── main.js                 # Importe le SCSS (point d'entrée Vite)
├── public/                 # Images, icônes, fonds de la maquette
└── package.json
```

## 🚀 Installation & lancement

```bash
git clone https://github.com/Georginio-prod/Huddle-landing-page.git
cd Huddle-landing-page
npm install
npm run dev          # http://localhost:5173
```

`npm run build` génère le site statique dans `dist/` ; `npm run preview` le prévisualise.

## 🌐 Déploiement

Déployé sur **Vercel** (framework Vite, sortie `dist/`) : <https://huddle-landing-sass.vercel.app>. Aucune variable d'environnement.

## 🎓 Ce que ce projet démontre

Écriture d'une landing page complète en SCSS structuré, gestion des images de transition et du responsive sans framework.

---

## 👤 Auteur

**Komla Etonam Georges EKLOU** (Georginio) — Développeur Full Stack Web & Web3

[![GitHub](https://img.shields.io/badge/GitHub-Georginio--prod-181717?logo=github)](https://github.com/Georginio-prod)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profil-0A66C2?logo=linkedin)](https://www.linkedin.com/in/komla-etonam-georges-eklou-68518b23b)
[![Portfolio](https://img.shields.io/badge/Portfolio-georginio.w3frame.com-6C63FF)](https://georginio.w3frame.com/)

> 📚 Tous mes projets sont listés et documentés sur mon [profil GitHub](https://github.com/Georginio-prod).
