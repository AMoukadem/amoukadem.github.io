---
title: ""
type: landing

sections:
  # =========================
  # Header académique (Markdown)
  # =========================
  - block: markdown
    content:
      title: ""
      text: |
        # [Prénom NOM]

        [Statut exact] — [Laboratoire], [Université / École]  
        [Ville], [Pays] · **Email :** [prenom.nom@univ.fr]

        **Domaines :** [3–6 mots-clés max, séparés par des virgules]

        [CV (PDF)](/uploads/CV.pdf) · [Publications](/publications/) · [Enseignement](/courses/) · [GitHub](https://github.com/[user]) · [Google Scholar]([lien])
    design:
      columns: "1"

  # =========================
  # Présentation courte
  # =========================
  - block: markdown
    content:
      title: "Présentation"
      text: |
        Je travaille sur **[thème 1]**, **[thème 2]** et **[thème 3]**, avec un focus sur **[objectif/angle]**.  
        Mes intérêts actuels : **[méthodes/objets]** et **[applications]**.

        - Point 1 : [une phrase claire, concrète]
        - Point 2 : [une phrase claire, concrète]
        - Point 3 : [une phrase claire, concrète]
    design:
      columns: "1"

  # =========================
  # Recherche (liens rapides)
  # =========================
  - block: markdown
    content:
      title: "Recherche"
      text: |
        - **Axe 1 —** [1 ligne]
        - **Axe 2 —** [1 ligne]
        - **Axe 3 —** [1 ligne, optionnel]

        👉 Voir : **[Projets](/projects/)**.
    design:
      columns: "1"

  # =========================
  # Publications récentes (auto)
  # =========================
  - block: collection
    content:
      title: "Publications récentes"
      filters:
        folders:
          - publications
      count: 5
    design:
      view: citation

  # =========================
  # Enseignement (aperçu)
  # =========================
  - block: markdown
    content:
      title: "Enseignement"
      text: |
        Je propose des cours en **[L1/L2/L3/M1/M2]** (analyse, algèbre, proba, méthodes numériques, …).

        - [Cours 1] — [niveau] — [année]
        - [Cours 2] — [niveau] — [année]
        - [Cours 3] — [niveau] — [année]

        👉 Voir : **[page Enseignement](/courses/)**.
    design:
      columns: "1"

  # =========================
  # Contact (ancre menu)
  # =========================
  - block: markdown
    id: contact
    content:
      title: "Contact"
      text: |
        **Email :** [prenom.nom@univ.fr]  
        **Bureau :** [bâtiment, salle]  
        **Adresse :** [adresse complète]

        - Google Scholar : [lien]
        - arXiv : [lien]
        - HAL : [lien]
        - GitHub : https://github.com/[user]
    design:
      columns: "1"
---
