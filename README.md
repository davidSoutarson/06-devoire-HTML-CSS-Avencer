# Devoir 6 : HTML & CSS Avancé

## Exercice n°2 — Intégration HTML/CSS

**Auteur :** David Soutarson  
**Élève n°229855 — ESECAD**  
**Formation : Intégrateur / Développeur Web**

---

## Consignes de l'exercice

Vous devez respecter le cahier des charges suivant :

- **Largeur du site :** 990 px  
- **Colonne de gauche :** 630 px  
- **Colonne de droite :** 300 px  
- **Les autres dimensions ou couleurs sont libres.**

### Contraintes techniques :

- Utiliser les balises structurantes : `<header>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<aside>`  
- Le HTML doit être commenté en **français**  
- Les noms de **classes** doivent être explicites et rédigés en **anglais**  
- Le **positionnement** des éléments se fait à l'aide d'**IDs** et de **classes**

---

## Structure recommandée

```html
<body id="wrapper">
  <header>...</header>
  <main>
    <section>
      <article class="column-left">...</article>
      <aside class="column-right">...</aside>
    </section>
  </main>
  <footer>...</footer>
</body>
