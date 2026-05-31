# Référence — Sauvegarde sur GitHub
**Projet :** RAO-simulation  
**Dépôt :** https://github.com/Fournier67/RAO-simulation  
**Site web :** https://Fournier67.github.io/RAO-simulation/rao-dispatch.html  
**Date de configuration :** 2026-05-25

---

## Informations du dépôt

| Élément | Valeur |
|---|---|
| Utilisateur GitHub | `Fournier67` |
| Nom du dépôt | `RAO-simulation` |
| Branche principale | `main` |
| Fichier principal | `rao-dispatch.html` |
| Fichier local | `C:\Users\fomi8\rao-dispatch.html` |
| Dossier git local | `C:\Users\fomi8\RAO-simulation\` |

---

## Token d'accès (Classic PAT)

- **Type :** Token classique (commence par `ghp_`)
- **Scope coché :** `repo` (accès complet aux dépôts)
- **Expiration :** 90 jours à partir de la création
- **Usage :** git push vers GitHub

> ⚠️ Quand le token expire, aller sur :
> https://github.com/settings/tokens/new
> - Note : `rao-dispatch-push`
> - Expiration : 90 days
> - Scope : cocher ✅ `repo`
> - Copier le nouveau `ghp_...` et le fournir à Claude

---

## Comment activer GitHub Pages (site web public)

1. Aller sur https://github.com/Fournier67/RAO-simulation
2. Cliquer sur **Settings**
3. Menu gauche → **Pages**
4. Sous **Branch** → sélectionner **`main`** et **`/ (root)`**
5. Cliquer **Save**
6. URL générée dans 30–60 secondes :
   `https://Fournier67.github.io/RAO-simulation/rao-dispatch.html`

---

## Flux de travail — Sauvegarder les modifications

```
1. Modifier le fichier local avec Claude
         C:\Users\fomi8\rao-dispatch.html

2. Dire à Claude : "sauvegarde sur GitHub"

3. Claude exécute automatiquement :
   - Copie du fichier dans C:\Users\fomi8\RAO-simulation\
   - git add rao-dispatch.html
   - git commit -m "..."
   - git push origin main

4. GitHub Pages se met à jour (~1 minute)
```

---

## Commandes git manuelles (si besoin sans Claude)

```bash
# Se placer dans le dossier du projet
cd C:\Users\fomi8\RAO-simulation

# Copier le fichier modifié
copy C:\Users\fomi8\rao-dispatch.html rao-dispatch.html

# Ajouter et commiter
git add rao-dispatch.html
git commit -m "Mise à jour RAO"

# Pousser vers GitHub
git push origin main
```

---

## Structure des fichiers

```
C:\Users\fomi8\
├── rao-dispatch.html          ← fichier de travail (modifié ici)
└── RAO-simulation\
    ├── rao-dispatch.html      ← copie synchronisée avec GitHub
    └── GITHUB-REFERENCE.md   ← ce fichier
```

---

## Important — Synchronisation

Les modifications faites au fichier local **ne sont PAS automatiquement**
reflétées sur GitHub. Il faut demander une sauvegarde explicitement.

| Fichier local | GitHub | Site web GitHub Pages |
|:---:|:---:|:---:|
| Mis à jour en temps réel | Mis à jour sur demande | Mis à jour ~1 min après push |
