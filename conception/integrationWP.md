# Intégration MCD dans Modèle de données Wordpress

### Jardinier
- Table => wp_users
- Propriétés
  - username => user_nicename
  - password => user_pass
  - email => user_email

### Plante
- Table => wp_posts
- Propriétés
  - titre => post_title
  - description => post_content
  - statut => post_status

### Ensoleillement
- Table => taxonomy
- Propriétés
  - nom => taxonomy
- Hiérarchique => non

### Facilité d'entretien
- Table => taxonomy
- Propriétés
  - nom => taxonomy
- Hiérarchique => non