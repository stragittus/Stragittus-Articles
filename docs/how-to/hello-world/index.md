---

title: "Hello World — How-To"
type: how-to
status: living
--------------

# Hello World — How-To

Ce guide explique comment ajouter un nouveau contenu (article ou how-to) sur ce site.

---

## Étapes

### 1. Créer le dossier

```text
docs/articles/YYYY/YYYY-MM-slug/
```

ou

```text
docs/how-to/slug/
```

---

### 2. Ajouter un `index.md`

* Utiliser le **template canonique** pour un article
* Utiliser une structure simple pour un how-to

---

### 3. Ajouter les assets

```text
assets/
  cover.png
  why-fr.png
  why-en.png
  ...
```

---

### 4. Tester en local

```bash
mkdocs serve
```

---

### 5. Commit & push

```bash
git add .
git commit -m "Add <title>"
git push
```

GitHub Actions se charge du reste.

---

## Notes

* Les how-to sont **évolutifs**
* Ils peuvent être mis à jour sans notion d’“œuvre figée”
* Pas de PDF obligatoire
