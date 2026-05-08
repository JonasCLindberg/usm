# Biljettbevakare (GitHub Pages)

Denna sida finns i [index.html](index.html) och kan publiceras gratis med GitHub Pages.

## 1) Skapa repo pa GitHub

1. Skapa ett nytt repository pa GitHub, till exempel `biljett-bevakare`.
2. Kopiera URL:en till repot.

## 2) Publicera kod

Kor i projektmappen:

```bash
git add .
git commit -m "Prepare GitHub Pages"
git branch -M main
git remote add origin <DIN_REPO_URL>
git push -u origin main
```

Om `origin` redan finns:

```bash
git remote set-url origin <DIN_REPO_URL>
git push -u origin main
```

## 3) Aktivera Pages

1. Ga till repository -> Settings -> Pages.
2. Under Build and deployment:
3. Source: `Deploy from a branch`.
4. Branch: `main` och folder: `/ (root)`.
5. Spara.

Efter 1-2 minuter far du en URL i stil med:

`https://<ditt-namn>.github.io/<repo-namn>/`

## 4) Oppna pa mobilen

Oppna den publicerade URL:en i Safari/Chrome pa telefonen.

Tips: lagg till sidan pa hemskarmen for snabb oppning.
# biljett
# xxxbiljett
