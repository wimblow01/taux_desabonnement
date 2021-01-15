# taux_desabonnement

Pour le projet, j'ai dans un premier temps utilisé un RandomForest car on venait juste de l'utiliser dans un kata et que c'était encore frais dans ma tête.

Comme on a eu ensuite la consigne de passer par un réseau de neurone, j'ai repris l'architecture de mon réseau du brief sur la reconnaissance de chiffre que j'ai adapté à ce qui était demandé: 

* les deux premières couches la fonction "relu"
* la couche de sortie "sigmoid"

Pour avoir les meilleurs résutats, j'ai ensuite joué sur le batch_size et sur les epochs. Je n'ai pas réussi à dépasser 84,4% du coup j'ai gardé les valeurs correspondantes.
