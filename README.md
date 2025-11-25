# Éval EPS - Application PWA

Application d'évaluation EPS par code couleurs.

## 📱 Déployer sur GitHub Pages (5 minutes)

### Étape 1 : Créer le repository

1. Va sur **github.com** et connecte-toi
2. Clique sur le **+** en haut à droite → **New repository**
3. Nom : `eval-eps` (ou ce que tu veux)
4. Laisse en **Public**
5. Clique **Create repository**

### Étape 2 : Uploader les fichiers

1. Sur la page du repo vide, clique **uploading an existing file**
2. Glisse les 5 fichiers de ce dossier :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Clique **Commit changes**

### Étape 3 : Activer GitHub Pages

1. Va dans **Settings** (onglet en haut du repo)
2. Dans le menu à gauche, clique **Pages**
3. Sous "Source", sélectionne **main** et **/ (root)**
4. Clique **Save**
5. Attends 1-2 minutes

### Étape 4 : Accéder à ton app

Ton app sera disponible à :
```
https://TON-USERNAME.github.io/eval-eps/
```

### Étape 5 : Installer sur Android

1. Ouvre le lien dans Chrome
2. Chrome va proposer "Ajouter à l'écran d'accueil" (ou via le menu ⋮)
3. L'app s'installe avec son icône !

## ✅ Fonctionnalités

- ✅ Fonctionne hors-ligne
- ✅ Partage Quick Share des CSV
- ✅ Installation comme app native
- ✅ Données sauvegardées localement

## 🔄 Mettre à jour

Pour mettre à jour l'app, il suffit de remplacer les fichiers sur GitHub.
Pense à changer `CACHE_NAME` dans `sw.js` (ex: `eval-eps-v2`) pour forcer le rafraîchissement.
