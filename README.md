# DataCrunch Hackathon

## Thème : Analyse de Données et Algorithmes

Bienvenue au DataCrunch 2023 Hackathon, un événement passionnant où vous pouvez mettre à l'épreuve vos compétences en résolution de problèmes et en programmation. Vous devrez relever une série de 10 défis, allant du plus simple au plus complexe, tous liés à l'analyse de données et à la conception d'algorithmes efficaces.

## Sections

- [Règles](#regles)
- [Sujet](#sujet)
- [Exemple](#exemple)

## Règles <a name="regles"></a>:

Avant de commencer, assurez-vous de comprendre les règles du hackathon. Voici quelques règles de base à suivre :

1. Les participants doivent travailler individuellement.
2. Les participants sont tenus de respecter les règles de conduite appropriée ou pas mais belek.

### Langages de Programmation

- Tous les langages de programmation sont autorisés. Vous êtes libre de choisir le langage qui vous convient le mieux pour résoudre les défis.

### Ressources en Ligne

- L'utilisation d'Internet est autorisée. Vous pouvez effectuer des recherches en ligne, consulter la documentation, et accéder à des ressources utiles pour résoudre les défis.

### Assistance de Chat GPT

- Bien que l'utilisation d'Internet soit autorisée, nous déconseillons fortement l'utilisation de chatbots comme GPT (tels que ChatGPT) pour obtenir des réponses directes aux défis. Le but du hackathon est de tester vos compétences en résolution de problèmes et en programmation.

## Sujet <a name="sujet"></a>:

### 1. Tri de nombres

**Défi :** Trier une liste de nombres dans l'ordre croissant en utilisant un algorithme de tri au choix (comme le tri à bulles ou le tri rapide).

_Exemple :_

**Entrée :** `[5, 2, 9, 1, 5, 6]`

**Sortie :** `[1, 2, 5, 5, 6, 9]`

### 2. Recherche de mots clés

**Défi :** Identifier et compter le nombre d'occurrences de mots clés spécifiques dans un texte donné.

_Exemple :_

**Entrée : `Le hackathon DataCrunch est une compétition amusante pour les programmeurs. DataCrunch est génial.`

**Argument 1 :** `DataCrunch`

**Sortie :** `'DataCrunch': 2`

### 3. Analyse de fréquence des caractères

**Défi :** Trouver le caractère le plus fréquent dans une chaîne de caractères et afficher sa fréquence.

_Exemple :_

**Entrée :** `analyse de données`

**Argument 1: ** `a`

**Sortie :** `'a': 4`

### 4. Validation de mots de passe

**Défi :** Créer une fonction de validation de mots de passe qui vérifie si un mot de passe satisfait certaines conditions, à savoir :

- Doit contenir au moins 10 caractères.
- Doit commencer par une lettre majuscule.
- Doit contenir au moins un caractère spécial parmi : `!`, `@`, `#`, `$`, `%`, `&`, `*`.
- Doit contenir au moins un chiffre.

_Exemple :_

**Entrée :** `MonP@ssw0rd12`

**Sortie :** `SUCCESS`

**Entrée :** `1234abcdEFG`

**Sortie :** `FAILURE`

### 5. Compression de texte

**Défi :** Implémenter un algorithme de compression de texte pour réduire la taille d'une chaîne de caractères en supprimant les lettres répétées consécutives.

Dans ce défi, vous devrez créer un algorithme de compression de texte qui prendra une chaîne de caractères en entrée et supprimera les lettres consécutives répétées en les remplaçant par la lettre suivie du nombre de répétitions. Par exemple, "aaaaabbb" serait compressé en "a5b3". L'objectif est de réduire la taille de la chaîne de caractères sans perte d'information.

_Exemple :_

**Entrée :** `aaaaabbbcccddeeeefff`

**Sortie :** `a5b3c3d2e4f3`

### 6. Conversion binaire-décimal

**Défi :** Convertir un nombre binaire en décimal et vice versa en utilisant des opérations mathématiques.

_Exemple :_

**Entrée :** `1011`

**Sortie :** `11`

### 7. Recherche de texte dans une chaîne

**Défi :** Trouver un texte spécifique dans une chaîne de caractères et afficher ses positions.

_Exemple :_

**Entrée :**

`Epitech et la programmation c'est trop cool et trop bien!`

**Argument 1 :** `Programmation`

**Sortie :** `'Programmation': [3]`

**Entrée :**

`Epitech et la programmation c'est trop cool et trop bien! Et j'adore la programmation.`

**Sortie :** `'Programmation': [3, 13]`

### 8. Trouver des nombres premiers

**Défi :** Identifier tous les nombres premiers dans une plage donnée et les afficher.

_Exemple :_

**Entrée :** `[1, 20]`

**Sortie :** Nombres premiers : `[2, 3, 5, 7, 11, 13, 17, 19]`

### 9. Sudoku Solver

**Défi :** Créer un programme capable de résoudre un puzzle Sudoku en utilisant des algorithmes de résolution.

_Exemple :_

**Entrée :** Grille Sudoku à résoudre :

```
5 3 . . 7 . . . .
6 . . 1 9 5 . . .
. 9 8 . . . . 6 .
8 . . . 6 . . . 3
4 . . 8 . 3 . . 1
7 . . . 2 . . . 6
. 6 . . . . 2 8 .
. . . 4 1 9 . . 5
. . . . 8 . . 7 9
```

**Sortie :**

```
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
```

### 10. Création d'une carte en forme de cœur

**Défi :** Créer une carte en forme de cœur en fonction des dimensions spécifiées par l'utilisateur (taille x et y).

_Exemple :_

**Entrée :** [10, 7]

**Sortie :**

```
  ***      ***
 *****    *****
****************
***************
  ***********
    *******
      ***
       *
```
