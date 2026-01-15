---
title: ""
type: landing

sections:
  - block: markdown
    content:
      title: ""
      text: |
        # Prénom Nom

        Maître de conférences / Doctorant / Postdoc — Laboratoire, Université  
        **Mots-clés :** analyse, EDP, optimisation, …

        [CV (PDF)](/uploads/CV.pdf) · [Contact](#contact)
    design:
      columns: "1"

  - block: markdown
    content:
      title: "Recherche"
      text: |
        Je travaille sur …
    design:
      columns: "1"

  - block: markdown
    content:
      title: "Enseignement"
      text: |
        - Cours 1
        - Cours 2
        - Cours 3
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
        Email : **prenom.nom@univ.fr**
    design:
      columns: "1"
---
