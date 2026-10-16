# Site de candidature · Sara El Mountasser × BearingPoint

Site statique : deux pages HTML (`index.html`, `cv.html`), sans build.
Les bibliothèques (GSAP, Lenis, three.js) et les polices sont chargées depuis des CDN.

## Mettre en ligne sur Vercel

**Sans ligne de commande**
1. Crée un dépôt GitHub vide, puis dépose ces trois fichiers dedans (bouton « Add file › Upload files »).
2. Sur vercel.com/new, importe ce dépôt. Framework : « Other ». Pas de commande de build.
3. Clique sur « Deploy ».

**Avec la ligne de commande**
```
cd sara-bearingpoint-site
npx vercel --prod
```
