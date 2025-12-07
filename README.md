## Énoncé:

### Tirage de coupe du monde
C'est bientôt la coupe du monde! Pour vous amuser, vous avez décidé de créer un tirage fictif.

48 équipes participent à la coupe du monde. Chaque équipe possède un pot de tirage (1, 2, 3 et 4) et une région, qui est enregistré dans un fichier csv.

Ces 48 équipes doivent être mises dans 12 groupes (A-L) de 4 équipes.

Cependant, il y a quelques restrictions:

-  Pour que les groupes soient équlibrés, une équipe de chaque pot (1 à 4) doit se retrouver dans chaque groupe.
  
-  Le Mexique est garanti d'être dans le groupe A, le Canada dans le groupe B et les États-Unis dans le groupe D.
  
Il y a encore des équipes dont la présence à la coupe du monde ne sont pas encore confirmés parce qu'ils doivent passer par les barrages. Ces équipes sont enregistrés dans un fichier json.

Il y a aussi un fichier texte, qui traduit le nom de code d'une région en son nom complet (Ex. UEFA --> Europe).

Créez un programme qui fait un tirage fictif et affiche les résultats (incluant les équipes qui pourraient potentiellement se qualifier en barrage).

Exemple d'exécution:
```
Groupe A:
	-Mexique
	-Colombie
	-Ouzbékistan
	-Barrage Européen D (Tchéquie, Irlande, Danemark, Macédoine du Nord)
Groupe B:
	-Canada
	-Sénégal
	-Paraguay
	-Nouvelle-Zélande
Groupe C:
	-Allemagne
	-Équateur
	-Afrique du Sud
	-Haïti
Groupe D:
	-États-Unis
	-Iran
	-Tunisie
	-Barrage Européen B (Ukraine, Suède, Pologne, Albanie)
Groupe E:
	-Portugal
	-Maroc
	-Écosse
	-Barrage Intercontinental 1 (Iraq, Bolivie, Suriname)
Groupe F:
	-France
	-Croatie
	-Algérie
	-Curaçao
Groupe G:
	-Brésil
	-Australie
	-Norvège
	-Ghana
Groupe H:
	-Angleterre
	-Uruguay
	-Arabie saoudite
	-Cap-Vert
Groupe I:
	-Argentine
	-Japon
	-Égypte
	-Barrage Européen A (Pays de Galles, Bosnie-Herzégovine, Italie, Irlande du Nord)
Groupe J:
	-Espagne
	-Corée du Sud
	-Côte d’Ivoire
	-Barrage Européen C (Slovaquie, Kosovo, Turquie, Roumanie)
Groupe K:
	-Pays-Bas
	-Autriche
	-Panama
	-Jordanie
Groupe L:
	-Belgique
	-Suisse
	-Qatar
	-Barrage Intercontinental 2 (République Démocratique du Congo, Jamaïque, Nouvelle Calédonie)
Les résultats ont été enregistrés!
```

### Pour aller plus loin
-  Faire le tirage pas à pas de manière interactive.

-  Enregistrer les résultats du tirage dans un fichier.

### Défi optionnel
Pour rendre les choses plus excitantes, une règle à été ajouté au tirage: Un groupe ne peut pas contenir deux équipes de la même région.

Cependant, puisqu'il y a plus que 12 équipes dans la région européenne (UEFA), chaque groupe doit contenir au moins un (et parfois deux) équipes de la région UEFA.

Pour appliquer cette règle, il faut aussi tenir compte des participants des barrages intercontinentaux.

Le gagnant du barrage intercontinental #1 sera considéré comme faisant partie de l'Afrique (République Démocratique du Congo), de l'Océanie (Nouvelle Calédonie) et de l'Amérique du Nord (Jamaïque).

Le gagnant du barrage intercontinental #2 sera considéré comme faisant partie de l'Asie (Iraq), de l'Amérique du Sud (Bolivie) et de l'Amérique du Nord (Suriname).

(Note : L'Australie qui se retrouve dans la région asiatique n'est pas un bug.)
