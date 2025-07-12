# Readme en cours de construction...

## algoNoel.py
Ce script organise un tirage au sort pour Noël, en générant une liste aléatoire de participants tout en respectant des règles de compatibilité entre groupes, puis crée des fichiers individuels pour chaque participant afin de garder le secret sur les destinataires des cadeaux.

## AlgoRepartitionGain.py
Ce script calcule une répartition équitable de gains entre un nombre donné d'individus, en utilisant un algorithme qui génère des listes de distribution. Il affiche les résultats sous forme de tableaux dans une interface graphique Tkinter, où chaque colonne représente la répartition pour un nombre croissant d'individus, tout en visualisant les valeurs et leurs sommes.
Le but étant de récompenser un maximum de personne sans qu'aucune d'entre elle ne reçoive la même somme et en minimisant le nombre de personne qui ne recevront rien. Le nombre d'unité distribués correspond au nombre de personnes. Par exemple 6 unités entre 6 personnes donnera : 3 2 1 0 0 0. Cela pourrait être utilisé pour la répartition des gains d'un tournoi de poker par exemple.

## blackJackSimple.py
Ce script implémente une version simplifiée du jeu de Blackjack. Il crée un deck de cartes, distribue des cartes au joueur et au croupier, et permet au joueur de choisir entre "Hit" (tirer une carte) ou "Stand" (arrêter). Le jeu continue jusqu'à ce que le joueur dépasse 21 (perd) ou décide de s'arrêter. Ensuite, le croupier joue en tirant des cartes jusqu'à atteindre ou dépasser 17. Enfin, le script détermine le gagnant en comparant les scores du joueur et du croupier, tout en affichant les étapes du jeu.

## courbesCovid19.py
Ce script analyse les données globales de cas confirmés de COVID-19 en les téléchargeant depuis une source en ligne. Il regroupe les données par pays, calcule le cumul des cas pour chaque pays, et permet à l'utilisateur de choisir un pays parmi une liste. Ensuite, il génère un graphique montrant l'évolution des cas confirmés pour le pays sélectionné.

## CryptoCarreVigenere.py
Ce script implémente un chiffrement et déchiffrement basé sur le carré de Vigenère. Il utilise une clé de sécurité pour générer une matrice de chiffrement, où chaque ligne est une permutation de l'alphabet basée sur les lettres de la clé. Le script permet de chiffrer un message en remplaçant chaque lettre selon la matrice et de déchiffrer un message en inversant ce processus. Il inclut une démonstration avec une clé de sécurité et un message à chiffrer/déchiffrer.

## Graphique Cotation bourse.py
Ce script génère un graphique représentant l'évolution d'une donnée boursière sur une période donnée, en utilisant les données extraites d'un fichier CSV. Il lit les données du fichier, sélectionne une plage de jours spécifiée, et trace un graphique avec les dates en abscisse et les valeurs en ordonnée. Le graphique est stylisé pour améliorer la lisibilité, avec des annotations sur chaque point pour afficher les valeurs correspondantes.

## jeuDeCartes.py
Ce script peut être utilisé comme base pour développer un jeu de poker en python.

## JeuSuitesNumeriques.py
Ce script implémente un jeu basé sur des suites numériques. Il génère une suite de nombres en utilisant l'une des trois méthodes de calcul aléatoires (multiplication, addition, ou soustraction). Le joueur doit deviner le prochain terme de la suite après avoir observé les cinq premiers termes. Si la réponse du joueur correspond au terme calculé, il gagne, sinon il perd. Le jeu affiche les termes de la suite et le résultat du joueur.

## ModelProiePredateur.py
Ce script modélise l'évolution des populations de proies et de prédateurs sur une période donnée en utilisant des taux de reproduction et de mortalité. À chaque étape, il calcule les variations des populations en fonction des interactions entre proies et prédateurs, puis met à jour les populations. Les résultats sont affichés sous forme de graphique, montrant l'évolution des deux populations au fil du temps, avec des annotations pour certains points et un résumé des paramètres utilisés.

## PublipostagePythonLatex.py
Ce script réalise un publipostage en générant des documents LaTeX à partir des données d'un fichier CSV. Il lit les données, les nettoie et les formate pour créer des fichiers `.tex` contenant des tableaux préformatés avec des informations spécifiques. Chaque fichier est compilé en PDF à l'aide de `pdflatex`. Enfin, les fichiers temporaires générés (log, aux, tex) sont supprimés pour ne conserver que les fichiers PDF.

## QCM_bayes.py
Ce script implémente un QCM (Questionnaire à Choix Multiples) où l'utilisateur doit répartir un score total de 100 entre plusieurs réponses possibles. Une fonction calcule le score final en comparant les réponses de l'utilisateur avec la réponse correcte, en utilisant une formule basée sur l'erreur quadratique. Le score final est affiché, indiquant la précision des réponses de l'utilisateur.

## ShuffleStudy.py
Ce script étudie le mélange de deux piles de jetons de couleurs différentes (bleu et vert) en simulant un processus de fusion alternée. Il calcule le nombre d'itérations nécessaires pour que les piles reviennent à leur état initial après plusieurs mélanges. Les résultats sont représentés graphiquement, montrant la relation entre le nombre de jetons et le nombre de mélanges nécessaires. Le script inclut également une fonction pour visualiser les étapes du mélange dans une interface graphique Tkinter.

## statsPrenom.py
Ce script analyse les données de prénoms enregistrées dans un fichier CSV, en les triant par sexe, année, et fréquence d'apparition. Il génère deux bases de données distinctes pour les prénoms masculins et féminins, puis permet de visualiser l'évolution de la popularité d'un prénom spécifique au fil des années. Le graphique généré affiche les statistiques sous forme de barres, avec des annotations pour le total des occurrences du prénom.

## StockPricePredicter.py
Ce script implémente un modèle de prédiction des prix d'actions basé sur un réseau de neurones récurrent (RNN) utilisant des couches LSTM. Il traite les données historiques d'une entreprise à partir d'un fichier CSV, les normalise, et crée des matrices de données pour l'entraînement. Le modèle est entraîné pour prédire les prix futurs des actions. Il permet également de sauvegarder et de charger le modèle, d'évaluer ses performances sur des données de test, et de visualiser les prix réels et prédits sous forme de graphique. Enfin, il peut prédire le prix d'une action pour le jour suivant.

## suiteConway.py
La suite de Conway est une séquence de nombres où chaque terme est construit en décrivant le précédent. Exemple : 1 11 21 1211 
Le script génère cette suite pour un nombre donné et un nombre de répétitions spécifié. Il utilise une fonction pour calculer chaque terme en décrivant les chiffres du terme précédent. Ensuite, il affiche les termes de la suite dans une interface graphique Tkinter, où chaque chiffre est représenté par une couleur spécifique.

## ToyModelPierrePapierCiseaux.py
Ce script implémente un modèle de réseau de neurones pour prédire les résultats du jeu "Pierre-Papier-Ciseaux" en fonction des données d'entrée. Il utilise un fichier CSV contenant des données de jeu, divise ces données en caractéristiques (x) et labels (y), et entraîne un modèle séquentiel avec deux couches denses. La première couche utilise une activation ReLU, et la seconde une activation sigmoïde. Le modèle est compilé avec l'optimiseur Adam et une fonction de perte `binary_crossentropy`. Après l'entraînement, il peut prédire les résultats pour de nouvelles données et sauvegarder le modèle pour une utilisation future.

## Testat.py
Ce script modélise un test diagnostique appliqué à une population donnée. Il calcule :
- le nombre de vrais positifs (malades testés positifs) et de faux négatifs,
- le nombre de vrais négatifs (sains testés négatifs) et de faux positifs,
- la probabilité d’être malade si le test est positif (valeur prédictive positive),
- la probabilité d’être sain si le test est négatif (valeur prédictive négative).
  
Le résultat est affiché sous forme de tableau NumPy et sous forme lisible via la méthode __str__().

## ToyModelPierrePapierCiseaux.py
Ce script implémente un modèle de réseau de neurones pour prédire les résultats du jeu "Pierre-Papier-Ciseaux" en fonction des données d'entrée. Il utilise un fichier CSV contenant des données de jeu, divise ces données en caractéristiques (x) et labels (y), et entraîne un modèle séquentiel avec deux couches denses. La première couche utilise une activation ReLU, et la seconde une activation sigmoïde. Le modèle est compilé avec l'optimiseur Adam et une fonction de perte `binary_crossentropy`. Après l'entraînement, il peut prédire les résultats pour de nouvelles données et sauvegarder le modèle pour une utilisation future.
