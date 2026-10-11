# Portfolio de Yassine

Portfolio personnel en HTML, CSS et JavaScript, sans framework.

## Lancer le site
1. Décompresse `yassine-portfolio.zip`.
2. Ouvre le dossier dans Visual Studio Code.
3. Ouvre `index.html` dans ton navigateur. Tu peux aussi installer l'extension **Live Server** dans VS Code, puis faire clic droit sur `index.html` > **Open with Live Server**.

## Personnaliser le portfolio
- **Nom et texte** : modifie `index.html`.
- **Couleurs, espacements, tailles** : modifie les variables au début de `style.css`, dans `:root`.
- **Comportement du menu et animations** : modifie `script.js`.
- **Email** : cherche `ton.email@example.com` dans `index.html` et remplace-le par ton adresse.
- **Photo** : crée un dossier `images`, ajoute ta photo sous le nom `yassine.jpg`, puis dans `index.html`, remplace le bloc `<div class="avatar"...>...</div>` par :
  `<img class="profile-photo" src="images/yassine.jpg" alt="Photo de Yassine">`
  Ajoute ensuite dans `style.css` :
  `.profile-photo { width: 100%; height: 260px; object-fit: cover; border-radius: 10px; }`
- **Projets** : les projets actuels sont des exemples. Remplace les descriptions et liens par tes vrais projets avant de publier.

## Publier gratuitement avec GitHub Pages
1. Crée un dépôt GitHub public, par exemple `yassine-portfolio`.
2. Envoie `index.html`, `style.css` et `script.js` à la racine du dépôt.
3. Dans le dépôt, ouvre **Settings > Pages**.
4. Sous **Build and deployment**, choisis **Deploy from a branch**, sélectionne `main` et `/ (root)`, puis **Save**.
5. Attends la publication, puis ouvre l'adresse indiquée dans les réglages Pages.

Attention : le site publié est public. N'y ajoute pas ton adresse personnelle, numéro de carte d'identité ou autres informations sensibles.
