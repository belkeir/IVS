# IVS

Pour ce projet, le bundle AppBundle est utilisé.
On y trouve :

- la classe Zone (entité doctrine) permettant de modéliser une zone d'intérêt déclarée dans AppBundle/Entity.

- un seul controlleur ZoneControlleur.php permettant de diriger les requêtes selon qu'on souhaite enregistrer une zone, toutes les lister, en sélectionner une, la modifier,
ou supprimer une zone.

- la classe generateSamples.php permet de simuler une acquisition de zones d'intérêt. Elle utilise la classe Coord permettant de spécifier les
coordonnées d'un point. Elles sont déclarées dans AppBundle/Utils.
