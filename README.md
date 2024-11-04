# projet_bdd
# Ce projet est un site de gestion de citations inspirantes, comprenant un système de connexion, d'inscription, et une section pour les administrateurs afin de gérer les citations.

## Fonctionnalités principales :
### Connexion à la base de données : J’ai configuré une connexion sécurisée à une base de données MySQL pour stocker les utilisateurs et les citations.

### Création automatique de l'utilisateur admin : Lors du premier chargement, si l’utilisateur "admin" n’existe pas, il est automatiquement créé avec un mot de passe sécurisé. Le mot de passe se trouve dans le code PHP. Cela permet d'avoir un accès d'administration par défaut.
### Système de connexion et d'inscription : 
#### Les utilisateurs peuvent s'inscrire et se connecter via le formulaire à l'acceuil du site. Les mots de passe sont stockés de manière sécurisée grâce à un hachage. Lorsqu'un utilisateur se connecte, sa session est initialisée pour permettre l'accès aux fonctionnalités du site.

### Affichage des citations : 
  #### Une fois connecté, les utilisateurs peuvent voir des citations affichées dans un carrousel. Chaque citation est accompagnée d'une image et est mise en forme pour un       affichage attractif. Ainsi, a part ces droits d'accès qui ne permet seulement de visualiser les images et citations, ils ne peuvent rien faire d'autre. 

### Gestion des citations par l’administrateur : 
  #### Un utilisateur avec le rôle "admin" peut ajouter de nouvelles citations, incluant un texte et une URL d'image. Il peut également supprimer des citations existantes via une interface dédiée.

### Déconnexion : Les utilisateurs peuvent se déconnecter, ce qui détruit leur session pour sécuriser l’accès.

### Design et interface utilisateur : J’ai utilisé Bootstrap pour une mise en page responsive et agréable, avec des effets CSS pour améliorer l’apparence et l'interactivité du site.

  # CONCLUSION : 
### Ce projet combine donc une base de données pour la gestion des utilisateurs et des citations, 
### J'ai coder en PHP ce qui permet principalement des créer ce site web dynamique.


# Voici le lien : benji.alwaysdata.net
