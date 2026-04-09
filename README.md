# hazrodd.github.io - Site personnel

Ce site personnel retrace mon parcours d'ingenieur en systemes spatiaux et de research engineer en caracterisation ionospherique et space weather. J'y partage mes projets, publications et experiences autour du GNSS multi-recepteurs, de la detection et de l'estimation de vitesse des EPB, du machine learning et du traitement avance du signal spatial.

## 1) Prerequis

- Un compte GitHub
- Git installe localement
- Un depot GitHub cree (soit de type user site: `username.github.io`, soit un depot projet)

## 2) Utiliser ce template

Le template contient deja les pages principales:

- `index.html`
- `publications.html`
- `education.html`
- `contact.html`
- `style.css`
- `header.js`

Tu peux commencer par personnaliser:

- Le nom, la bio et la photo dans `header.js`
- Le contenu de chaque page HTML
- Les couleurs et styles dans `style.css`

## 3) Publier sur GitHub Pages

### Option A - Site utilisateur (recommande)

1. Cree un depot nomme exactement `username.github.io`
2. Place les fichiers du template a la racine du depot
3. Commit et push
4. Ton site sera disponible sur `https://username.github.io`

### Option B - Site projet

1. Cree un depot (ex: `mon-site`)
2. Push ce template dans le depot
3. Dans GitHub: Settings > Pages
4. Source: Deploy from a branch
5. Branche: `main` et dossier: `/ (root)`
6. Ton site sera disponible sur `https://username.github.io/mon-site`

## 4) Commandes Git (exemple)

```bash
git init
git add .
git commit -m "Initial site from SiteGitHub template"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

## 5) Points importants

- Le fichier d'entree doit etre `index.html`
- Les liens internes utilisent des chemins relatifs (deja le cas)
- Verifie que les ressources locales existent (ex: image de profil, CV PDF)

## 6) Mise a jour du site

Chaque `git push` sur la branche publiee mettra ton site a jour automatiquement.
