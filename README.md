# 34_Introduction_modeles_generatifs_auto-encodeurs_variationnels

Contexte du projet
Les modèles génératifs sont aujourd'hui considérés comme parmi les plus prometteurs dans le domaine de l'Intelligence Artificielle (l'année 2023 est d'ailleurs souvent qualifiée comme année de l'IA générative). Nous avons acquéri les bases des modèles génératifs au travers de l'étude d'un premier modèle : l'auto-encodeur. Dans ce brief, nous rentrons dans le vif du sujet : les auto-encodeurs variationnels. Ainsi, il va falloir tout d'abord construire une présentation de type Powerpoint se déroulant selon le plan suivant :

* Qu'est-ce qui différencie(nt) un auto-encodeur d'un auto-encodeur variationnel ?

* A quoi sert principalement un auto-encodeur variationnel ?

* Décrire brièvement les notions d'espace latent et de vecteur latent.
* A quoi correspondent-ils dans le cas de l'auto-encodeur variationnel ?
* En profiter pour faire un rappel sur ce qu'est une distribution normale à une dimension puis à n dimensions !
* Qu'est-ce que et surtout à quoi sert la "Kullback-Leibler (KL) divergence" ? (vulgariser)
* Quelle est enfin la démarche à suivre pour générer de nouvelles données une fois l'autoencodeur entrainé ?

Afin de s'exercer et de s'approprier toutes ces notions, il faudra en parallèle les illustrer au travers d'un Jupyter Notebook sur la base de données MNIST pour générer des images synthétiques (i.e. des images virtuelles, qui n'existent pas et non pas été construites ou mesurées dans le monde réel), selon par exemple le plan suivant :

* Chargement des données

* Preprocessing

* Construction de l'encodeur

* Construction du décodeur

* Construction de l'autoencodeur variationnel (dimension de l'espace latent = 2)

* Entrainement du modèle

* Génération d'images synthétiques (utilisation du modèle en inférence)

* Affichage de l'espace latent



NB Pour celles et ceux qui sont lassé.e.s de la MNIST, vous pouvez utiliser la base de données "CelebFaces Attributes (CelebA)". Attention les images en couleur de cette base de données sont bien plus complexes que celles en N&B de la MNIST. L'exercice est toutefois beaucoup plus divertissant avec le dataset CelebA.

Livrables
Une présentation de type Powerpoint et un Jupyter Notebook.

Critères de performance
La présentation doit être complète et didactique, l'autoencodeur 100% fonctionnel en inférence.
