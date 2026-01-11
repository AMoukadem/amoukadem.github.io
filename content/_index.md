---
title: ""
type: landing

sections:
  - block: hero
    content:
      title: "Prénom Nom"
      text: |
        Maître de conférences / Doctorant / Postdoc — Laboratoire, Université

        **Mots-clés :** analyse, EDP, optimisation, …
      primary_action:
        text: CV (PDF)
        url: uploads/CV.pdf
        icon: download
      secondary_action:
        text: Contact
        url: "#contact"
    design:
      background:
        color: white

  - block: markdown
    content:
      title: "Recherche"
      text: |
        Je travaille sur :
        - Axe 1 : …
        - Axe 2 : …
        - Axe 3 : …

        👉 Voir la page **Recherche**.
    design:
      columns: "1"

  - block: markdown
    content:
      title: "Enseignement"
      text: |
        Cours (L1–M2) : analyse, algèbre, méthodes numériques, …

        👉 Voir la page **Enseignement**.
    design:
      columns: "1"

  - block: collection
    content:
      title: "Publications récentes"
      filters:
        folders:
          - publications
      count: 5
    design:
      view: citation

  - block: markdown
    id: contact
    content:
      title: "Contact"
      text: |
        Email : **ton.email@univ.fr**  
        Bureau : [bâtiment / salle]  
        Adresse : [adresse]

        - Google Scholar : [lien]
        - arXiv : [lien]
        - GitHub : https://github.com/ton-user
    design:
      columns: "1"
---
