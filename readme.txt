Utilisation du hook pre-commit :

1. Placez le fichier pre-commit dans le répertoire .git/hooks/ de votre dépôt Git local.
2. Assurez-vous que le fichier pre-commit est exécutable (chmod +x pre-commit).
3. À chaque fois que vous exécutez un git commit, le hook pre-commit sera automatiquement exécuté.
4. Répondez à la question pour savoir si vous souhaitez sauvegarder les informations de commit.
5. Si vous répondez 'y', les informations de commit seront stockées dans le fichier suivi/commitInfo.txt.

Remarque : Ce hook est spécifique à ce dépôt Git. Si vous souhaitez utiliser le même hook pour d'autres dépôts Git, vous devrez copier le fichier pre-commit dans le répertoire .git/hooks/ de chaque dépôt Git.
