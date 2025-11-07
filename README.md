# WineTypePredicition
Modéle de classification qui prédit si un vin de type vhino verde est rouge ou blanc.

On pourrait penser que distinguer un vin rouge d’un vin blanc ne mérite pas un modèle. Il suffit de regarder la couleur. En réalité, dans une chaîne de production, la couleur n’est pas toujours disponible, ni fiable. Les échantillons circulent dans des flacons opaques, la mesure est faite en ligne, au laboratoire on travaille sur des tableaux de résultats, et l’étiquette peut être erronée. Mon modèle répond à ce besoin concret, vérifier automatiquement que le profil chimique d’un lot est cohérent avec le type déclaré.

L’impact est triple. D’abord, assurance qualité. Le classifieur contrôle chaque lot à partir de mesures déjà réalisées, acidités, sulfates, dioxyde de soufre, densité, alcool. En cas d’incohérence, il déclenche une alerte avant l’embouteillage. On évite des mélanges involontaires et des erreurs d’étiquetage. Ensuite, réduction des coûts. Au lieu de lancer des analyses poussées sur tous les lots, on les réserve aux cas douteux identifiés par le modèle. Moins de réactifs, moins d’heures, des décisions plus rapides. Enfin, conformité et traçabilité. Le modèle agit comme un garde fou numérique. Il renforce la fiabilité des données, utile en audit ou en rappel préventif.

Ce projet produit une probabilité, accompagnée d’explications sur les variables clés. Par exemple, la relation entre densité et alcool, le rapport SO2 libre sur total, ou le rôle des acidités. On peut donc justifier chaque alerte auprès d’un œnologue ou d’un responsable qualité.

Au delà du rouge contre blanc, la valeur est réutilisable. Même pipeline, mêmes bonnes pratiques, pour d’autres contrôles, par exemple détection d’un style anormal, ou triage pour orienter des analyses plus coûteuses. En résumé, je transforme des mesures de routine en un filet de sécurité opérationnel. Moins d’erreurs, moins de coûts, plus de confiance dans la chaîne.
