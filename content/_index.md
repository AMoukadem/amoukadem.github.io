---
title: ""
type: landing

sections:
  - block: hero
    content:
      title: "[Prénom Nom]"
      text: |
        Maître de conférences / Doctorant / Postdoc — [Laboratoire, Université]

        **Mots-clés :** analyse, EDP, optimisation, apprentissage, …
      primary_action:
        text: CV (PDF)
        url: uploads/CV.pdf
        icon: download
      secondary_action:
        text: Contact
        url: "#contact"
      announcement:
        text: "Dernière mise à jour : 2026"
        link:
          text: ""
          url: ""
    design:
      background:
        color: white

  - block: markdown
    content:
      title: "Recherche"
      text: |
        Je travaille sur **[2–3 thèmes maximum]**.  
        Mon objectif : **[phrase claire, 1 ligne]**.

        - Thème 1 : …
        - Thème 2 : …
        - Thème 3 : …

        👉 Voir : **Projets** (menu « Recherche »).
    design:
      columns: "1"

  - block: markdown
    content:
      title: "Enseignement"
      text: |
        J’enseigne principalement en **[L1/L2/L3/M1/M2]** : analyse, algèbre, proba, méthodes numériques, …

        👉 Voir : **Enseignement** (menu).
    design:
      columns: "1"

  - block: collection
    id: publications
    content:
      title: "Publications récentes"
      filters:
        folders:
          - publications
      count: 5
    design:
      view: citation

  - block: contact
    id: contact
    content:
      title: Contact
      text: ""
      email: "[ton.email@univ.fr]"
      phone: ""
      address:
        street: "[Adresse]"
        city: "[Ville]"
        region: ""
        postcode: ""
        country: "France"
      coordinates:
        latitude: ""
        longitude: ""
      directions: ""
      office_hours: []
      contact_links:
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: "[lien]"
        - icon: arxiv
          icon_pack: ai
          name: arXiv
          link: "[lien]"
        - icon: github
          icon_pack: fab
          name: GitHub
          link: "https://github.com/[user]"
---

