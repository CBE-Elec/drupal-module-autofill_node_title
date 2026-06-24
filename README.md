# drupal-module-autofill_node_title
Module Drupal pour remplissage automatique d'un titre de node

## Configuration

Chaque type de contenu peut activer son propre remplissage automatique dans l'onglet Parametres du formulaire d'edition du type de contenu.

Trois parametres sont disponibles :

- Remplissage automatique du titre : active ou non le remplissage par motif pour ce type de contenu.
- Motif de remplissage : texte utilise pour generer le titre quand le titre du node est vide.
- Mettre à jour : met à jour le titre d'un node existant quand un champ utilisé par le motif est modifié.

Les substitutions utilisent le nom machine des champs entre crochets. Exemple : `CACI de [field_membre] du [field_date_du_caci]`.

Le fonctionnement historique pour les contenus `message_du_forum` et `caci` est conserve comme solution de repli si aucun titre n'a ete genere par motif.
