# TokAuto — Site vitrine

Site légal pour le dossier d'audit TikTok API.

## Pages

| Page | URL après déploiement | Usage |
|---|---|---|
| `index.html` | `https://ton-username.github.io/tokauto-site/` | Vitrine |
| `terms.html` | `https://ton-username.github.io/tokauto-site/terms.html` | **Terms of Service URL** |
| `privacy.html` | `https://ton-username.github.io/tokauto-site/privacy.html` | **Privacy Policy URL** |

## Déploiement sur GitHub Pages (5 min)

```bash
# 1. Crée un repo GitHub nommé "tokauto-site"
# 2. Upload les 3 fichiers HTML
git init
git add .
git commit -m "Legal pages for TikTok API audit"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/tokauto-site.git
git push -u origin main

# 3. Dans GitHub : Settings → Pages → Source: main branch → Save
```

Tes URLs seront disponibles en ~2 minutes sur :
- Terms : https://TON_USERNAME.github.io/tokauto-site/terms.html
- Privacy : https://TON_USERNAME.github.io/tokauto-site/privacy.html

## Colle ces URLs dans le portail TikTok for Developers :
- **Terms of Service URL*** → `.../terms.html`
- **Privacy Policy URL*** → `.../privacy.html`
