# Guide de croisière — Norwegian Dawn 2026

Guide de voyage interactif (Barcelone → croisière Norwegian Dawn → Porto → Lisbonne, 22 août – 13 septembre 2026).

Ce dépôt contient un seul fichier statique, `index.html`, prêt à être publié sur Cloudflare Pages.

## Déployer sur Cloudflare Pages

1. Poussez ce dépôt sur GitHub (voir ci-dessous).
2. Dans le tableau de bord Cloudflare → **Workers & Pages** → **Créer une application** → **Pages** → **Connecter à Git**.
3. Sélectionnez ce dépôt GitHub.
4. Paramètres de build :
   - **Framework preset** : Aucun (None)
   - **Build command** : (laisser vide)
   - **Build output directory** : `/`
5. Cliquez sur **Déployer**. Un lien `*.pages.dev` sera généré automatiquement.
6. (Optionnel) Ajoutez un nom de domaine personnalisé dans l'onglet **Custom domains** du projet Pages.

Chaque futur `git push` sur la branche principale redéploiera automatiquement le site.
