# Introduction au MVC

## Petite initiation

- [Comprendre le MVC](https://docs.google.com/presentation/d/1OVz9HqSob9JskPsyxbxqXfbyqBh-SGtt-MjQHzK1SGw/edit?usp=sharing)

## Projet : Interview d'un webdev

Un site internet avec comme page :
- Making Of : comment vous avez trouvé votre webdev
- présentation de l'entreprise où travaille l'interviewé
- présentation du webdev
- interview (voir liste de questions)
- Conclusion (analyse/impression personnelle)

Il faut un MVC :
- un dossier **controller** avec le routeur, celui qui va rediriger
- un dossier **model** où on va mettre le traitement PHP (tu sais, tout ce qui se trouve au-dessus du doctype)
- un dossier **view** avec toutes les pages visuelles
- un fichier **config.php** avec les infos de connexion (user, password, login, host)
- un fichier **connexion.php** avec la connexion à la DB
- un fichier **index.php** qui inclut le connexion.php et le config.php, et également le contrôleur.

La liste des questions est [disponible ici](interviewwebdev.md).
